# Mini tutorial de Git!

## ![Octocat](https://raw.githubusercontent.com/gist/johan/1007813/raw/a25829510f049194b6404a8f98d22978e8744a6f/octocat.svg)

## Configuración de Git

- Se abre el terminal Gitbash(pulsamos shift)
-  git config --global user.name "David Garcia"
 - git config --global user.email "cardenete29@hotmail.com"
 - git config --global core.editor "code --wait"
- git config --global -e: para ver la configuración

## Comandos de Git

- git init: para iniciar repositorio
- git add: para añadir fichero al stage
- git status y  git status -s:Estado de los ficheros
- git diff: para ver los cambios en los ficheros
- git rm --cached xxxxx: para sacar fichero del stage
- git commit -m "mensaje":Para crear el commit(minuto 38)
- git log --oneline: para crear un log de commit. Para salir :q
- git checkout -b ramaNueva: Crear ramaNueva.
- git checkout: Para cambiar de rama
- git merge ramaNueva: Para hace merge nos tenemos que situar en la rama princicpal
- git remote add origin https://github.com/david201002/proyecto-curso-git.git: Para 		      conectar al respositorio remoto.
- git Push -u origin main: Para subir al repositorio remoto
- git branch -u origin/main:para conectar la rama con el repositorio remoto o (git push -u   origin main)
- git tag etiqueta1:Para etiquetar un commit
- git switch main: Cambia a a la rama main
- git stash: Para modificar algo de forma temporal
- git stash list: Para listar los cambios temporales
- git stash pop: Para volver al fichero temporal
- git branch -d rama3: Borrar una rama en local
 - git push origin --delete rama3: Para borrarla en remoto
- git fetch: Para bajar un historico remoto
- git log --oneline --all: Para ver los cambios de git fetch.
- git reset --hard: Para volver al estado anterior todos los archivos.
- git reset: Para sacar archivo del stage
- git checkout archivo1.txt: Vuelve al estado anterior.
- git reset --hard fa21ab4(es el hash con el que nos queremos quedar):Para borrar un  commit,  a partir del que pongamos se borran todos.
- fork: para copiar un repositorio de otra persona en tu repositorio.

> David García
