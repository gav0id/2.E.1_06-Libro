Ejercicio 2.E.1 06 - Libro

Lógica del programa
Para resolver este ejercicio, diseñé la clase `Libro` con el objetivo de simular el progreso de lectura. Le definí cuatro atributos de estado: `titulo` (String), `autor` (String), `paginasTotales` (int) y `paginaActual` (int). 

Implementé un constructor que recibe el título, el autor y el total de páginas por parámetro, e inicializa automáticamente el atributo `paginaActual` en 0 al momento de crear el objeto.

Para definir su comportamiento, desarrollé dos métodos principales:
1. `leer(int paginas)`: Recibe una cantidad de páginas leídas y las suma al progreso actual. Le agregué una validación condicional (`if`) para evitar que el progreso supere la cantidad de páginas que tiene el libro. Si eso ocurre, el valor se ajusta al tope de páginas totales y el sistema imprime un mensaje indicando que la lectura ha finalizado.
2. `mostrarProgreso()`: Calcula el porcentaje de avance. Para que la operación matemática sea exacta y no se pierdan los decimales en la división, apliqué un casteo explícito a `double` sobre `paginaActual` antes de calcular el porcentaje.

Ejecución en consola
<img width="1366" height="722" alt="imagen" src="https://github.com/user-attachments/assets/7c613c40-64f3-490c-a693-10d0dcd2ede2" />

