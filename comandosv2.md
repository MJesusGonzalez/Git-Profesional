# Ramas

Crear y cambiarte a una rama
```Shell
git checkout -b nombre_rama
o
git switch -c nombre_rama
```
Eliminar rama
```Shell
git branch -D nombre_rama
```

Crear y cambiarte a una rama
```Shell
git checkout -b nombre_rama
```

Combinar una rama con main
```Shell
git checkout main
git merge nombre_rama
```

# Stash
Guardar en stash
```Shell
git stash
o
git stash save "nombre a guardar"
o
git stash --include-untracked
```
Ver el stash
```Shell
git stash list
```
Sacar del stach al área de trabajo
```Shell
git stash pop
o
git stash pop stash@{numero_del_indice}
```