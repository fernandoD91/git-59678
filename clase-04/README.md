# Clase 04

## 2 tipos de aputadores

Estaticos -> Ramas locales como remotas.
Dinamicos -> HEAD

## TAGs
Nos sirven para marcas algun commit que tenga cierta importancia. 
También me sirve para marcas versiones o releases.

### Crear TAG

    git tag v1.1

### Eliminar TAG

    git tag -d v1.1

### Versionado semantico
Si no le coloco el HASH me lo va a poner en el último commit de la rama actual.

    git tag -a v1.0.0 -m "Versión 1.0.0 - Aplicación funcionando"

    git tag -a v0.1.0 <HASH> -m "Versión beta de nuestra aplicación"

### Para mostrar los tags

    git tag

### Versión larga para mostrar los tags

    git tag -n

### Para subir todos los tags 
**IMPORTANTE**: No recomendada salvo que sepa lo que estoy haciendo

    git push --tags

### Subir un tag en particular

    git push origin <tag_name>

# Agregar al escenario y sacar foto.

    git commit -am "Mensaje"

# GIT STASH

### Creo un stash

    git stash

### Muestro la cajita de stashes 

    git stash list

### Aplicar último stash

    git stash pop
    git stash apply

### Aplico un stash en particular

    git stash apply stash@{0}
    git stash apply stash@{1}

### Borrar un stash

    git stash drop stash@{0}
    git stash drop stash@{1}

### Para crear una rama a partir de un stash

    git stash branch <nombre_rama>

# Trabajar con Fork

1. Fork
2. Clone
3. Configuro el remoto del repositorio original

    git remote add upstream <url-remoto>

4. Actualizar si fuera necesario mi fork con el repositorio original

    git pull upstream <rama>

5. Tengo el local y para actualizar mi fork remoto

    git push origin main

# GIT RESET

## Tipos de reset

* Soft. No destructivo.

    git reset --soft <hash>

* Mixed. No destructivo. Saca todo del staged y los cambios quedan listos para el commit

    git reset <hash>
    git reset --mixed <hash>

* Hard. Destructivo. Peligroso, mucho cuidado.

    git reset --hard <hash>

# GIT REFLOG
Un log de las referencias de todo lo que ha sucedido en el repositorio en orden cronologico.

    git reflog

# GIT ALIAS

## Crear alias

    git config --global alias.ll "log --oneline --decorate --all --graph"
    git config --global alias.l "log --oneline"

## Listar alias

    git config --get-regexp alias

## Para borrar alias

    git config --global --unset alias.ll