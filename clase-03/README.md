# Clase 03 - 15-06-2022

## REPASO RAMAS Y MERGE

### Crear un rama

    git branch <nombre-rama>

### Listar ramas

    git branch

### Cambiar rama

    git switch <nombre-rama>


## MERGE (Una fusión de ramas)

**IMPORTANTE**: Tengo en la rama que quiero traerme los cambios. Ej: Si quiero traerme a **master** lo que vengo haciendo en **development**, tengo que estar en **master**


    git merge <rama-que-me-quiero-traer>

### TIPOS DE MERGE

* Fast-Forward: Fusión automatica de las ramas.
* Recursiva - Unión automática (No hay colisiones de cambios)
* Manual (Conflictos - Colisiones - Vamos a tener que elegir nosotros con que nos quedamos)

## Detener el merge

    git merge --abort

## Para comparar 2 ramas

    git diff <rama-1> <rama-2>

## Si quiero crear una rama y moverme a esa rama

    git checkout -b <nombre-rama>

# GIT GIST
Para compartir snippets de código y documentar

https://gist.github.com/



