
================ PASOS DE COMANDOS GIT PARA REPOSITORIOS ===================

git init
------------------------------------------------------------------------------  

Crea en la ruta o carpeta un repositorio 

git add archivo.txt o git add . 
------------------------------------------------------------------------------  

El primero añade un archivo en especifico y el otro añade todos los archivos.
 

git commit -m "mensaje"
------------------------------------------------------------------------------  

Envia los últimos cambios del archivo al repositorio, se le agrega un mensaje para saber que se guarda o que
cambios se hicieron
          

git status
------------------------------------------------------------------------------  

Para mirar el status de los archivos, para ver que cambios no se han añadido.
        

git show 
------------------------------------------------------------------------------  

Muestra todos los cambios históricos hechos y sus detalles (qué cambió, cuándo y quién los hizo)

git log archivo.txt 
------------------------------------------------------------------------------  

Muestra la historia completa de un archivo 
       

git push
------------------------------------------------------------------------------  

Envía los cambios al repositorio remoto

git remote add origin https://github.com/nombreDeUsuario/repositorio.git
------------------------------------------------------------------------------  

Esto conectará la carpeta existente en tu sistema local al repositorio de Github recién creado.


git push origin master
------------------------------------------------------------------------------  

Manda los cambios al repositorio remoto


git pull
------------------------------------------------------------------------------  

Agrega o trae los cambios del commit más reciente del proyecto.




=========================== COMANDOS EN LA TERMINAL DE GIT ==========================

pwd
------------------------------------------------------------------------------  

Muestra la carpeta actual en la que estás
  

cd 
------------------------------------------------------------------------------  

Cambias de carpeta o directorio
  

mkdir
------------------------------------------------------------------------------  

Crea carpetas
  

touch 
------------------------------------------------------------------------------  

Crea archivos en la ruta actual
  

history
------------------------------------------------------------------------------  

Muestra el historial de comandos realizados
  

!11
------------------------------------------------------------------------------  

Repite el comando realizado en ese número
  

cat
------------------------------------------------------------------------------  

Muestra el contenido o el código dentro del archivo
  

rm Archivo.txt
------------------------------------------------------------------------------  

Elimina el archivo creado en la ruta
  

--hepl
------------------------------------------------------------------------------  

Info. de todos los comandos existentes en GIT
  

git diff
------------------------------------------------------------------------------  

Compara cambios de un commit con otro
  

git reset  hard
------------------------------------------------------------------------------  

vuelve a una verción anterior del archivo, tener MUCHO cuidado con este comando


==================== Ramas en GIT =========================================

git branch new_rama
------------------------------------------------------------------------------  

Crea una rama nueva
     

git branch
------------------------------------------------------------------------------  

Muestra la rama en la cual estás
     

git checkout nombre_de_la_rama
------------------------------------------------------------------------------  

Para cambiarte de rama
     

git merge nombreDeLaRama
------------------------------------------------------------------------------  

Fuciona o une una rama con otra para una versión final.
                

git branch -D nombreRama
------------------------------------------------------------------------------  

Elimina una rama en especifico
     

