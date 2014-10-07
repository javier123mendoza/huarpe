# Huarpe
## Framework para automatización de tareas construcción proyecto PHP

**Huarpe** es un framework que facilita la construcción de un proyecto `php` dando un marco de trabajo para automatizar las tareas típicas relacionadas con los proyectos php. Estas son generalmente la resolución de `dependencias`,  `configuración de parametros`, configuración de `permisos`, configuración de entorno de intraestructura `web server` `ddbb`, etc.

Esta basado en [phing](https://github.com/phingofficial/phing) y [composer](https://github.com/composer/composer).

## ¿Por qué?

Dado que existe multiples herramientas para deploy muy maduras, *puppet*, *chef*, etc. En el mundo de php al momento de terminar un deploy sobre un proyecto suele exister tareas comunes que pueden ser automatizadas. Como por ejemplo borrado de cache, rotación de logs, rollback, etc. La idea del framework es disponer de tareasc comunes que sean reutilizables y adaptables a la logica de cada proyecto.

## ¿Como?

Este seria el ciclo tipo de la construcción de un proyecto

![Cliclo](https://raw.github.com/javier123mendoza/huarpe/master/docs/stages.png)

## Etapas



### Instalación

Instalacion de proyecto nuevo

### Update

### Reset

### Rollback

### Release Building

* Tags `git` o `hg`

        phing release.build.up

* agregar cambios en CHANGELOG.md

## Procesos

### Deploy
#### Configuración del deploy
### Resolución de dependencia de composer
** --dev require-dev
### Configuración del proyecto
### Procesos propios del proyecto
### Migraciones
### DDBB
### Configuración de web service
#### Apache vhost
### Rollback



* SymLinks de los build de phing
* propertie generales
* propertis del proyecto
*
