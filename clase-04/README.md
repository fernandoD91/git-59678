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