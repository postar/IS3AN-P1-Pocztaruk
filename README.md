# IS3AN-P1-Pocztaruk
# Consigna
INGENIERÍA DE SOFTWARE 
PARCIAL 1 - PARTE PRÁCTICA
Fecha de entrega: Jueves 22/05 - 19:00
(La parte teórica se realiza el jueves de manera sincrónica luego de la revisión de la práctica)

Enunciado:
Nos contratan para desarrollar UaiOS, un novedoso sistema operativo multiusuario en red que se instala en un servidor en la nube y todos los clientes accederán a él y a partir de esta única instalación podrán acceder a un sistema de archivos por línea de comando. Este sistema de archivos se compone de una carpeta principal asociada a un cliente, el cual se podrá conectar a la instancia del SO y por comandos manipular el sistema de archivos. 
Al momento de iniciar el programa, se verá una consola que pida nombre de usuario y contraseña. Una vez que el sistema operativo valide los datos de la sesión, se verá un cursor que permita comenzar a escribir los comandos del sistema operativo.
Nos piden, adicionalmente, poder observar la ruta en donde el usuario se encuentra ubicado cuando utiliza el sistema operativo, por  ejemplo
Usuario/directorio/directorio> 
Por el momento, los comandos permitidos son:
•	MD nombredirectorio – Para hacer un directorio nuevo, dentro del directorio donde el usuario se encuentra posicionado. Si el directorio ya existe, deberá infiormar un error.
•	CD nombredirectorio – Para cambiar a otro directorio a un directorio dentro de la lista de directorios en donde el usuario se encuentra posicionado. Si el directorio no existe, deberá informar un error.
•	MF nombrearchivo (tamaño) – Para crear un nuevo archivo (debe definirse el tamaño durante su construcción). Si el nombre del archivo ya existe, deberá informar un error.
•	LS – para listar todos los archivos y directorios dentro del directorio donde este posicionado el usuario. Si no hay nada, deberá indicar que no hay datos, en cambio, si hay datos deberá indicar el tamaño de cada componente, tanto del directorio actual, como de todos los subdirectorios y archivos que lo componen
•	DI – para desconectarse del sistema operativo y volver al inicio de sesión
Se pide:
1)	Identificar patrones de diseño utilizados para el SO y desarrollar diagrama de clases correspondiente.
2)	Desarrollar el código necesario para poder simular una consola
3)	Persistir en una base de datos el sistema de archivos, utilizando solamente 3 tablas. Separar en 4 capas.
Nota:
En el enunciado se pueden observar, al menos 2 patrones de diseño, diferentes e integrados. Uno de ellos es el Composite, el cual deberá estar correctamente diseñado e implementado para asegurar el porcentaje mínimo de aprobación.
