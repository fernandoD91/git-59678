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
