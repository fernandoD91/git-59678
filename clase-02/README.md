# Clase 02

https://github.com/abhisheknaiidu/awesome-github-profile-readme

## Agregar remoto en repositorio local

    git remote add origin <URL>

### Verificar que este configura el remoto

    git remote
    git remote -v

## Status de archivos

**UNTRACKED** => Archivos que no se agregaron al index (Staging Area) y por consecuencia no se les hará seguimientos

**STAGED** => Archivos que fueron agregados al area temporal o staging Area

**UNMODIFIED** => Archivos que se encuentran en el respositorio y que no fueron modificados

**MODIFIED** => Archivos que se encuentran en el respositorio pero difieren con los que sen ecuentran actualmente en el directorio de trabajo (Working Directory)

![status_archivos](img/3rFpi.png)


# Git amend
Agregar algo que me olvide en el último commit 

    git add . o <archivo>
    git commit --amend

# TRABAJAR CON RAMAS

## Crear un rama

    git branch <nombre>

## Mirar las ramas que tengo en el repo

    git branch

## ¿Cómo se en que rama estoy? 

En las consolas tipo linux/unix, voy a tenerlo al costado del path (dev, master...)

Otra forma es con git status

    git status
    git branch

## Listar ramas remotas

    git branch -r

## Eliminar ramas

ALT + 96 => backtick

```sh
git branch -d #Borrar la rama si en algún momento fue fusionada (Merge)
```

```sh
git branch -D #Borro la rama en el caso de que no me deje porque no fue fusionada o mergeada
```