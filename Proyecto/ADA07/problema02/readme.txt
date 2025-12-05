Instrucciones para compilar y correr:

Moverse a la carpeta de la tarea en la terminal de Visual Studio Code:
cd "C:\<Ruta donde la carpeta descomprimida es>\ADA07_E02\ADA07_AP02"

Comando para compilar:
g++ -std=c++11 -g ADA07_AP02.cpp hash_table.cpp -o ADA07_AP02.exe

Comando para correr el codigo:
.\ADA07_AP02.exe


Como usar el código:

1.- "Add Identifier" te dejara agregar un identificador al archivo. te preguntara primero por la clave/Identificador de la variable, y luego por su ámbito. si ya existe un identificador con esa variable, no se te dejara crear el nuevo identificador.
En caso de ser valido, podras ingresar su tipo y su valor (Si nada es puesto, nada será asignado).
2.- "Search Identifier" puedes buscar un identificador en el archivo. de encontrarse, se desplegara. en caso de multiples identificadores, con ambito diferente, se desplegaran y se podra elegir cual se quiere obtener mas detalles, incluyendo el numero de colisiones que esa tuvo. en caso de no encontrar ninguno, se mandara error y regresara al menu principal.
3.- "Delete Identifier" es similar a la busqueda, solo que te pedira confirmar si quieres borrarlo.
4.- "Display All Identifiers" desplega todos los identificadores, agrupados por index, así como sus detalles.
5.- "Exit" Cierra el programa.

Ahora, tambien se pueden agregar Funciones (vacias, esencialmente variables con diferente tipo) y Variables desde el identifiers.txt

Sin embargo, debe seguir la syntaxis correcta:

<"Global" o "Local"> <Tipo de variable> <ID> = <Valor>;
(el programa automáticamente ordenara el ID de acuerdo a su Index, y calculara las colisiones necesarias para añadirlo en ese momento.)

Ejemplo:

Global int y = 2;

Pasara a ser:

Global int y = 2 #collisions=0;

cuando el código lea el archivo.

