# Huarpe
## Framework para automatización de tareas de construcción proyecto PHP

**Huarpe** es un framework que facilita la construcción de un proyecto `php` dando un marco de trabajo para automatizar las tareas típicas relacionadas con los proyectos php. Estas son generalmente la resolución de `dependencias`,  `configuración de parametros`, configuración de `permisos`, configuración de entorno de intraestructura `web server` `ddbb`, etc.

Esta basado en [phing](https://github.com/phingofficial/phing) y [composer](https://github.com/composer/composer).

## ¿Por qué?

Dado que existe multiples herramientas para deploy muy maduras, *puppet*, *chef*, etc, entoncre un hueco a la hora de automatizar el proceso de construcción de un proyecto en php. Al momento de terminar un deploy sobre un proyecto suele exister tareas comunes que pueden ser automatizadas, como por ejemplo, borrado de cache, rotación de logs, rollback, etc. La idea del framework es disponer de tareas comunes que sean reutilizables y adaptables a la logica de cada proyecto.

## ¿Como?

### Etapas
Este seria el ciclo tipo de la construcción de un proyecto- Básicamente el framework trabaja sobre 3 etapas:

* Setup: Cuando es un nueva instalación. En realidad es un **release** de cero
* Release: Lanzamiento de proyecto con todas sus etapas de contrucción
* Rollback: Puede llamar, vuelta atras del **release**

![Cliclo](https://raw.github.com/javier123mendoza/huarpe/master/docs/stages.png)


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
