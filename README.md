# Introducción a Git
## Descripción
Este programa es un "Hola mundo" usando el lenguaje de Java, el objetivo de la tarea fue:
* Conocer lo que es un sistema de control de versiones.
* Introducir al alumno en el enterno de GitHub.
* Conocer los diferentes comandos que permitan al alumno, crear un repositorio y actualizar un repositorio.
## Instrucciones de uso
1. Asegurese de tener el Java Development Kit en el sistema de su dispositivo.
2. Abra el archivo "HolaMundo.java" en cualquier editor que tenga las extensiones para Java (Visual Studio Code, Apache Neatbeans, etc).
3. Para el caso de Visual Studio Code, tener previamente instalados el  "Extension Pack for Java" (disponible en el buscador de extensiones).
4. Correr el programa usando el boton de "Run Java".
5. En la terminal aparecera el mensaje "Hola Mundo".
## Comandos utilizados
A continuación, se muestran los comandos utilizados en Git Bash:
Para la crear el repositorio local se usaron los siguientes comandos:
* `git init`
* `git remote add origin "Dirección del repositorio"`

Para ir agregando archivos al repositorio se utilizó:
* `git add "Nombre del archivo"`

Para ir agregando commits se utilizó:
* `git commit -m "mensaje del commit""`

Para crear el .gitignore se utilizó:
* `touch .gitignore`

Para verificar el repositorio se utilizó:
* `git status`
  
Para enviar los cambios al repositorio se utilizó:
* `git push origin master`
## Notas sobre el archivo .gitignore
> Este archivo se creo para poder ignorar los archivos que no queremos tener en el repositorio, para este caso dentro del archivo .gitignore, pusimos la siguiente instrucción:
* `*.log`

> A la hora de ejecutar el programa, nos dara un mensaje en terminal "Hola Mundo", para la verificación que debug.log no se subió, podemos usar el comando  `git status` y observar si esta el archivo .log, y en caso de no estarlo, entonces no se subió.

