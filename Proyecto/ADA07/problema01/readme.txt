Compilar el programa

Abrir la terminal en Visual Studio Code y moverse a la carpeta donde está guardado el archivo:

cd "C:\<ruta>\ADA07_E02"


Compilar el programa con:

gcc ADA07_AP02.c -o ADA07_AP02.exe


Cómo ejecutar el programa

Después de compilar, ejecutar con:

.\ADA07_AP02.exe


1. Como usar el código:

Crea una tabla hash de tamaño 120.

Inserta tres o más estudiantes (Juan Pérez, Miguel Gómez y Ana López).

Busca un estudiante por matrícula.

Intenta eliminar un estudiante.

Muestra los resultados de búsqueda y eliminación en pantalla.

2. Estructuras usadas

Estudiante: contiene matrícula, nombre y carrera.

Tablahash: contiene un arreglo de estudiantes y otro de estados para manejar colisiones.

3. Funciones implementadas

inicializarTabla(): Inicializa la tabla hash.

insertar(): Inserta un estudiante usando sondeo lineal.

buscar(): Busca un estudiante por matrícula.

eliminar(): Elimina un estudiante marcándolo como borrado.

-> Nota <-

El programa ya incluye los datos de prueba en main(), por lo que se ejecuta directamente sin pedir datos al usuario.


