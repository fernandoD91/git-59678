
# Comandos de consola

## Crear directorios

    mkdir directorio1 directorio2 directorio3

## Creo archivos vacios

    touch archivo1 archivo2

## Limpio consola

    clear

## Listar directorios

    ls

## Cambio de directorio (Con tabulador me va ir sugiriendo)

    cd <directorio>

## Salir de un directorio

    cd ..


## Comando de ejemplo

    mkdir css js img; touch index.html css/styles.css js/main.js


## Configurar GIT

Quedar siempre configura para todos los proyectos
git config --global user.name "Maximiliano Príncipe"
git config --global user.email "mlapeducacionit@gmail.com"

Creas un repo de git, vas configurar local para este repo.

git config --local user.name "Maximiliano Príncipe"
git config --local user.email "mlapeducacionit@gmail.com"

## Inicializar proyecto git (Crea un repositorio de git)

Entonces, es un repositorio de git por proyecto. Una carpeta o directorio.

    git init

## Veo el estado de los archivos 

    git status

## GIT: No versiona carpetas
En el caso de querer versionar la carpeta tengo que colocar un archivo. Y estandar por la comunidad es .gitkeep

## Estados de GIT

### Working Directory.
Es el area de trabajo. El area sucia. Donde interactatuo con mis archivos y voy creando el código.

### Staging Area
Preserva y le dice a git que lo prepare para sacarle un a foto.

### Local Repo 


## Para ver la información de configuración

    git config --global -l # Salgo con q del comando (quit)
    git config --global --get-regexp user
    git config --global --get-regexp email

## Ver la diferencia entre lo que tengo WD y el Repo local

    git diff clase-01/README.md

## Para ignorar un archivo en particular
Creo el archivo .gitignore. Puede estar en la raíz o no.