# Crear-nueva-rama-en-git

Clonas el repositorio normalmente

```git
git checkout -b NOMBRE DE LA NUEVA RAMA 
```

# Usar nuevos tokens de Github

```
git remote remove origin
git remote add origin https://[TOKEN]@github.com/[USER]/[REPO]
git push
```

# Forzar pull limpiando HEAD
```
git reset --hard HEAD
git pull origin master
```

# Cambiar URL Remota

```
---> git remote add origin URL <---

En desuzo
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

//Ahora en bitbucket es:


```

# Ver URL Remotas

```
git remote -v
```


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

