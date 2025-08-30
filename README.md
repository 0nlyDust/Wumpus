# 🌸 Wumpus

## Descripción del Proyecto
Implementación del juego del Wumpus en un entorno de Jupyter Notebook.  
El objetivo principal es que un agente controlado por inteligencia artificial explore un tablero en busca de oro, evitando caer en hoyos y enfrentarse al Wumpus.

## Ejecutar el juego en la nube
Puedes jugar directamente sin instalar nada usando Binder:  

[Ver Notebook en nbviewer](https://nbviewer.org/github/0nlydust/Wumpus/blob/main/carpeta/Wumpus.ipynb)


## Instrucciones para Jugar

### Ejecutar el Notebook
1. Abre el archivo `.ipynb` en Jupyter Notebook o a través del enlace de Binder.
2. Selecciona la opción **"Restart kernel and run all"** desde el menú **Kernel** o ejecuta cada celda en orden para cargar las funciones necesarias.

### Cómo ejecutar una celda
- Haz clic sobre la celda que deseas ejecutar.
- Presiona **Shift + Enter**.
- Alternativamente, puedes usar el botón **Run** en la barra de herramientas superior.

### Iniciar el juego
- Ejecuta la celda de la función `main()` para comenzar (generalmente la última celda).
- Aparecerá un menú con las siguientes opciones:

#### Opciones del Menú Principal
1. **Jugar con el tablero por defecto**  
   - Tamaño: 8x8  
   - Distribución de oro, hoyos y Wumpus configurada automáticamente con posiciones aleatorias.

2. **Crear un tablero modificado**  
   - Personaliza tamaño del tablero (6x6 a 8x8), número de hoyos (máx. 5) y posiciones iniciales del Wumpus y el oro.  
   - Si no defines posiciones específicas, se colocarán aleatoriamente.

3. **Salir**  
   - Termina la ejecución del programa.

## Posibles Fallos
- Demasiados hoyos en un tablero pequeño podrían generar conflictos de espacio.  
- Movimientos aleatorios del agente podrían ser inválidos en ocasiones, afectando la simulación.

## Detalles de Diseño
- Casillas diseñadas a mano con paleta de colores cohesiva. 

## Consideraciones Adicionales
- No se ha implementado la mecánica de la flecha.  
- Para probar la mecánica de caer en el Wumpus: usar tablero 8x8, oro en `(2,3)` y Wumpus en `(5,1)` (no garantizado).  
- La función heurística no considera la proximidad al Wumpus o al oro, pero podría añadirse.

---

¡Disfruta jugando y explorando el tablero del Wumpus!
