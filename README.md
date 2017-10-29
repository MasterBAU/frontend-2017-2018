# Master en Diseño Web - Front-End

## Clases

- [Presentacion de la asignatura](/clases/2017-10-23/2017-10-23.md)
- [Intro a Git y la terminal](/clases/2017-10-30/2017-10-30.md)

---

## Mantener el repositorio actualizado

### 1. Clona tu fork:

    git clone git@github.com:TU-USERNAME/TU-FORKED-REPO.git

### 2. Añade el remoto del repositorio original en tu repositorio forked: 

    cd ruta/al/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-FORKED-ORIGINAL.git
    git fetch upstream

### 3. Actualiza tu fork del repositorio original para obtener los últimos cambios:

    git pull upstream master