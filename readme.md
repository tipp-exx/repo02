
PRINCIPALES COMANDOS DE GIT

    📌 git init
 > ``Creará un nuevo repositorio local GIT.``

    📌"git init [nombre del proyecto]"   
 >``Crear un repositorio dentro de un nuevo directorio especificando el nombre del proyecto.``  

    📌git clone  
 > ``Para copiar un repositorio.`` 

    📌git clone nombredeusuario@host:/path/to/repository  
 > ``Si el repositorio está en un servidor remoto.``

    📌git clone /path/to/repository  
 > ``Copiar un repositorio local.``

    📌git add <temp.txt>

 >``Agregar archivos al área de preparación.``

    📌git commit –m “El mensaje que acompaña al commit va aquí”  
 >``Creará una instantánea de los cambios y la guardará en el directorio git.``

    📌git config  
 > ``Establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc.``  

    📌git config --global user.email tuemail@ejemplo.com  
 > ``La opción -global le dice a GIT que vas a usar ese correo electrónico para todos los repositorios locales.``

    📌git config --local user.email tuemail@ejemplo.com  
 > ``Si quieres utilizar diferentes correos electrónicos para diferentes repositorios.``

    📌git status  
 > ``Muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.``  

    📌git push  origin <master>  
 >``Enviar confirmaciones locales a la rama maestra del repositorio remoto.``

    📌command git checkout -b <branch-name>  
 > ``Crea ramas y te ayuda a navegar entre ellas.``

    📌git checkout <branch-name>  
 > ``Para cambiar de una rama a otra.``

    📌git remote -v  
 > ``Te permite ver todos los repositorios remotos.``

    📌git branch  
 > ``listar, crear o borrar ramas.``  

    📌git pull  
 > ``Fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local.``  

    📌git merge  
 > ``Se usa para fusionar una rama con otra rama activa.``
