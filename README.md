# Practica git para Programacion Web

## Comandos basicos para Git

Para utilizar **Git** los desarrolladores utilizan comandos especificos para copiar, crear, cambiar y combinar codigo. 
Estos comandos pueden ejecutarse directamente desde la linea de comandos o utlizando una aplicacion como GitHub Desktop 
o Sourcetree.

### git init

El comando `git init` inicializa un repositorio nuevo de **Git** y supervisa el repositorio creado.
Este genera una subcarpeta oculta dentro del repositorio creado para almacenar la estructura de datosinterna que se 
requiere para el control de versiones.

### git clone

Para crear una copia local del proyecto que existe remotamente se utliza el comando `git clone`. El clon contiene
todos los archivos, historial y ramas del proyecto

### git add

El comando `git add` almacena un cambio de forma provisional. De esta manera Git rastrea todos los cambios que se
hacen a la base del codigo de un desarrollador, pero es necesario probarlos y tomarle captura de pantalla a ellos
para incluirlos en el historial del proyecto. Este comando realiza las siguientes pruebas:

1. Cualquier cambio que se pruebe, se convertira en parte de la siguiente captura de pantalla y tambien del
   del proyecto.
2. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial
   y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.

### git commit

`git commit` guarda la instantánea del historial del proyecto y completa el proceso de seguimiento de los cambios.
En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se haya almacenado 
provisionalmente con `git add` pasara a formar parte de la instantanea con `git commit`.
