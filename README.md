# Crear-nueva-rama-en-git

Clonas el repositorio normalmente

git checkout -b <branch-name> 


# Forzar pull limpiando HEAD
git reset --hard HEAD
git pull origin master

# Cambiar URL Remota

git remote set-url origin https://github.com/USERNAME/REPOSITORY.git


# Please enter a commit message to explain why this merge is necessary,especially if it merges an updated upstream into a topic branch

1 - press "i"

2 - write your merge message

3 - press "esc"

4 - write ":wq"

5 - then press enter 


# Borrar archivos del git / para aplicar el .gitignore

```
git rm --cached /\*.exe

git rm --cached .externalNativeBuild
```

