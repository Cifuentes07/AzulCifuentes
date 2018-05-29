# Comandos en terminal
- **ls** muestra archivos (carpetas,doc)
- **ls -l** muestra archivos (carpetas, docs) en forma de lista
- **ls -a**  muestra todos los archivos (carpetas,doc ocultos)
- **pwd**    describe en donde te encuentras
- **cd**     abre carpeta que se desea, p.e cd NombreCarpeta
- **cd ..** regresa a ruta anterior
- **mkdir**  crear carpetas
- **mkdir -p** crea carpeta origen y subcarpeta
- **touch**  crea docs con cualquier extensión/ crea varios doc al mismo tiempo p.e touch ejemplo1.txt ejemplo2.txt nutr.md
- **rm**     borrar docs
- **rmdir**  borrar carpeta vacia
- **rm -r**  borra carpeta con documentos
- **mv** mover doc p.e NombreDoc.txt ../ruta
- **mv -i** mover doc esta opción te pregunta si deseas sobreescribir el doc a mover en caso que ya exista algún doc con el mismo nombre  
- **mv** cambiar nombre a doc p.e mv ejemplo1.txt metabolismo.txt
- **cp** copiar doc p.e NombreDoc ../ruta
- **cp -i**
- **cp -f**
- **cp -R**
######NOTA: No se recomienda nombrar carpeta con espacios usar camelCase
- **echo" "**  "permite escribir mensaje" > NombreDoc escribe men al inicio de doc, >> NombreDoc escribe men al final del doc sin sobreescribir, >> NombreDoc.txt si no existe el doc lo crea
- **cat** muestra lo que hay dentro del doc p.e cat NombreDoc
#Comandos en terminal para GIT
- **git init** inicializa repositorio en ruta donde se encuentre
- **git remote** muestra remotos que se hayan creado
- **git remote -v** muestra remotos creados detallados (con url asociado a cada remoto) aquí muestra url push "subir cambios de pc a la nube" & url fetch "bajar cambios de nube a pc"
- **git remote add [nombre] url** añade un remoto git remote add *origin* + url dada por gitHub
- **git status** detalla el estado de los archivos del directorio en el que se esta trabajando
- **git diff** diferencias entre el último commit y los nuevos cambios
- **git add** añade..
- **git add [NombreArchivos]** añade archivo(s) para preparalos, darles seguimiento
- **git add -A**
- **git add .**
- **git commit -m** -m indica el mensaje:describe cuales fueron los cambios realizados en ese commit
- **git log** muestra los cambios realizados
- **git log -n #** muestra últimos cambios que se desean saber, escribiendo en el #
- **git push** origin master --> sube cambios realizados en pc a la remote
- **git push NombredelRemoto<p.e origin> nombreDeLaRama< p.e master>** git push origin master, para subir archivos al remoto
- **git rm --cached <archivo>...** para sacar del area de stage?
- **git pull origin master** bajar cambios del remoto a la pc
######NOTA: en caso de crear un git init (repositorio) en un directorio equivocado hacer:
1.  ls -a en el directorio, para que nos muestre todos los archivos (ocultos y demas) git init crea un archivo oculto .git
2. rm -rf .git borra el git init creado y se puede realizar otro git init en el directorio que se desea

gitHub directorio público, directorio privado costo

gitbucket directorio privados sin costo

gitlab
# titulo1  comandos en atom
## titulo2
### titulo...
###### titulo6
Con 2 asteriscos puedo poner **letras negritas**

con 1 asterisco puedo poner *letra en cursiva*

para formato lista numerico:
1. primer elemento
    - dos tab para poner elementos secundarios dentro del elemento principal
      - 1 o 3 tab ? elementos terciario

2. segundo elemento
    - segundo nivel
      - tercer nivel

para formato lista viñetas:
- elemento
- elemento

> "Esto es una cita"

abrir tres tildes ~ y cerrar para que lo que este dentro el markdown lo tome como un bloque de codigo
~~~
<html>

</html>
~~~

`function startlearning();` nota: tilde invertida abrir/cerrar para solo una linea de codigo

[este es un link](https://atom.io/packages/markdown-preview-plus)
![link perritos](https://i.ytimg.com/vi/2D8XRCF8uNw/hqdefault.jpg)
