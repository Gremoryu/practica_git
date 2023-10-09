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

### git status

`git status` muestra el estado de los cambios como sin seguimiento, modificados o almacenados provisionalmente.

### git branch

`git branch` muestra las ramas en las que se trabaja localmente.

### git merge

`git merge `combina las líneas de desarrollo. Este comando habitualmente se utiliza para combinar los cambios que se realizan en dos ramas distintas. Por ejemplo, un desarrollador podría hacer una fusión cuando necesite combinar los cambios de una rama de característica en la rama de desarrollo principal.

### git pull

`git pull` actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local.

### git push

`git push` actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama.

### git checkout

Además de extraer las confirmaciones y las revisiones de archivos antiguas, git checkout también sirve para navegar por las ramas existentes. Combinado con los comandos básicos de Git, es una forma de trabajar en una línea de desarrollo concreta.

### git clean

Elimina los archivos sin seguimiento de tu directorio de trabajo. Es la contraparte lógica de git reset, que normalmente solo funciona en archivos con seguimiento.

### git commit--amend

Pasar la marca --amend a git commit permite modificar la confirmación más reciente. Es muy práctico si olvidas preparar un archivo u omites información importante en el mensaje de confirmación.

### git config

Este comando va bien para establecer las opciones de configuración para instalar Git. Normalmente, solo es necesario usarlo inmediatamente después de instalar Git en un nuevo equipo de desarrollo.

### git fetch

Con este comando, se descarga una rama de otro repositorio junto con todas sus confirmaciones y archivos asociados. Sin embargo, no intenta integrar nada en el repositorio local. Esto te permite inspeccionar los cambios antes de fusionarlos en tu proyecto.

### git log

Permite explorar las revisiones anteriores de un proyecto. Proporciona varias opciones de formato para mostrar las instantáneas confirmadas.

### git rebase 

Un cambio de base con git rebase permite mover las ramas, lo que ayuda a evitar confirmaciones de fusión innecesarias. El historial lineal resultante suele ser mucho más fácil de entender y explorar.

### git rebase-i

La marca -i se usa para iniciar una sesión de cambio de base interactivo. Esto ofrece todas las ventajas de un cambio de base normal, pero te da la oportunidad de añadir, editar o eliminar confirmaciones sobre la marcha.

### git reflog 

Git realiza el seguimiento de las actualizaciones en el extremo de las ramas mediante un mecanismo llamado registro de referencia o reflog. Esto permite volver a los conjuntos de cambios aunque no se haga referencia a ellos en ninguna rama o etiqueta.

### git remote 

Es un comando útil para administrar conexiones remotas. En lugar de pasar la URL completa a los comandos fetch, pull y push, permite usar un atajo más significativo.

### git reset 

Deshace los cambios en los archivos del directorio de trabajo. El restablecimiento permite limpiar o eliminar por completo los cambios que no se han enviado a un repositorio público.

### git revert 

Permite deshacer una instantánea confirmada. Si descubres una confirmación errónea, revertirla es una forma fácil y segura de eliminarla por completo del código base.
