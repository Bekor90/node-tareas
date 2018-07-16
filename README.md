##Aplicación de comandos crud basico

Creación de tareas por medio de linea de comandos la cual toma argumentos de una descripcion y un estado para generar una tarea y almacenarla en un archivo json. Permite crear, actualizar, listar y eliminar tareas.

Recuerda usar el comando:
 npm install

 Para poder ejecutar la aplicaciòn.

 ejemplo:

 Desde una terminal accede a la ubicación del archivo app.js ejecuta el comando para:

 crear:
 node app crear -d "tarea a realizar"

 actualizar:
 node app actualizar -d "tarea" -c estado (true o false)

 listar:
 node app listar

eliminar:
node app borrar -d "tarea"



