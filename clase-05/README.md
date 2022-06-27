# CLASE 05

## REPASO MARKDOWN

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Lista ordenadas

1. Item
2. Item
3. Item

### Lista desordenadas

* Item
* Item
* Item

### Poner código

    git init 

```sh
git init
```

```php
$variable = "HOLA"
```

```js
let variable = "HOLA"
```

### Línea de separación

--- 

### Negrita y cursiva

*Hola mundo*

> Hola mundo

**Chau mundo**

### Incluir imagenes en Markdown

![Imagen](img/chocolate.jpg)

### Check list

- [x] Write the press release
- [x] Update the website
- [ ] Contact the media

### Ejemplo Git RESET

1. Agrego un parte de código
2. Agrego otra línea de código
3. Agrego una línea más.
4. Agrego otra línea de código
5. Agrego una más
6. Terminé la funcionalidad

# GIT RESET

## Tipos de reset

* Soft. Saca todo del commit y lo deja en el area de staged (Escenario) listo para ser commiteado. No destructivo.

```sh
git reset --soft <hash> 
```

* Mixed. No destructivo. Saca todo del commit, no pasa por staged (Escendario) y deja los cambios listos Working directory para un nuevo commit

```sh
git reset <hash>
git reset --mixed <hash>
```

* Hard. Destructivo. Saca commit y borra los archivos o carpetas que estuvieran en los commits. **Peligroso, mucho cuidado.**

```sh
git reset --hard <hash>
```

# GITHUB Issues
Puedo crear y avisar al dueño del repositorio de problemas que puede llegar a tener su código.

# GITHUB Projects
Puedo crear un kanban y usar la metología Scrum para ir colocando las tareas y resolviendolas.

# GIT REBASE

## ¿Para qué sirve el rebase?

* Ordenar commits
* Corregir mensajes de los commits (Siempre y cuando no esten subidos al remoto)
* Unir commits
* Separar commits


## Como utilizo. Lo mismo que el merge.
Tengo estar en la rama que quiero recibir los cambios. O sea si quiero traerme los cambios de **r-rebase** en **master**. Tengo que estar sobre la rama **master**.

