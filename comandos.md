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
```git
git init
```

Agregar
```git
git add
```
Agregar los archivos solo del subdirectorio
```git
git add -A
```
Agregar solo los cambios (no nuevos archivos)
```git
git add -U
```

Quitar del staging al trabajo
```git
git reset
```