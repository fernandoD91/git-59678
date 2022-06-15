# Clase 03

## Repaso ramas

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

Fast-Forward: Fusión automatica de las ramas.
Recursiva - Unión automática (No hay colisiones de cambios)
Manual (Conflictos - Colisiones - Vamos a tener que elegir nosotros con que nos quedamos)
