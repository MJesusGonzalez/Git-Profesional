# Configuracion inicial
Ver las configuraciones 
```Shell
git config --list
git config user.name
git config user.email
```
configurar user y email
```Shell
git config --global user.name "nombre usuario"
git config --global user.email "correo@correo.com"
```

configurar SSH
```Shell
ssh-keygen -t ed25519 "correoDeGithub@correo.com"
```
Agente SSH
```Shell
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed2559
```
Almacenar SSH
```Shell
clip < ~/.ssh/id_ed2559.pub
```
Comprobar funcionamiento
```Shell
ssh -T git@github.com
```

# Repositorio
Iniciar
```Shell
git init
```

Agregar
```Shell
git add
```
Agregar los archivos solo del subdirectorio
```git
git add -A
```
Agregar solo los cambios (no nuevos archivos)
```Shell
git add -U
```

Quitar del staging al trabajo
```Shell
git reset
```

Enviar al repo
```Shell
git commit -m 'Mensaje'
```

# Github
Subir a un repo en Github
```Shell
git push
```

Descargar cambios
```Shell
git pull
```
Clonar un repo remoto
```Shell
git clone url_del_repo.com
```

# Comandos de visualizacion
estado de los archivos
```Shell
git status
o
git status -s
```

Registro (Log) de los commits
```Shell
git log
o
git log --oneline
o
git log -n 2
o
git log --format=short medium full
```

Ver cambios entre repo local vs trabajo
```Shell
git dif
```

Ver cinfo de un commit específico
```Shell
git show id_del_commit
```