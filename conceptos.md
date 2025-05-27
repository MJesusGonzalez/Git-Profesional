# Control de Versiones
- Qué se hace?
- Por qué se lo hace?
- Quien lo hace?
- Cuando lo hace?

Ayuda a llevar el seguimiento de un proyecto sea o no de 

# Tipos
| Tipo | Descripción | Ventaja | Desventaja |
|----------|----------|----------|----------|
| Local | En el equipo | Control y acceso directo | Si algo le pasa al equipo se pierde todo |
| Centralizado | En un servidor con copia en el equipo personal | El historial se almacena en el servidor y permite el trabajo en equipo | Si algo le pasa al servidor, se pierde todo |
| Distribuido | Servidor y los equipos almacenan el repositorio | no es necesario tener acceso a internet | No lo dijo la aweona :v |

# Git
- Copia de seguridad
- Trabajo offline
- Facilita trabajo en equipo
- Recupera versiones anteriores.

## Características importantes
- Almacena una snapshot / referencias del estado de cada elemento del proyecto.
- Creación de ramas
- Integridad
- Todo cambio es registrado y se puede navegar sobre estos

## Repositorio git
- carpeta .git con todos los cambios gestionados automáticamente

## funciones básicas
- commit: guardar cambios local
- push: guardar cambios en remoto
- pull: actualizar cambios

## Areas

Organizar los cambios por estados:
1. Trabajo: no forma parte del repositorio
2. Staging: caché
3. Repositorio: almacena snapshots (commmit) del proyecto

# Github
- Almacenar en la nube los repositorios locales
- Aplicaciones de CI/CD, automatizacion, etc.
- Herramientas similares como Bitbucket y GitLab

| Git | Github |
|----------|----------|
| Control de versiones | Almacenamiento del control de versiones + proyectos |
| Local | Nube |

# LLave SSH
Compartir información entre el Git local y Github
- Generara una clave SSH y pegarla en SSH Keys de Github