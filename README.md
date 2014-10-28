# Huarpe
## Framework para automatización de tareas de construcción proyecto PHP

**Huarpe** es un framework que facilita la construcción de un proyecto `php` dando un marco de trabajo para automatizar las tareas típicas relacionadas con los proyectos php.
Estas son generalmente:
  * Resolución de dependencias
  * Configuración de parametros de proyecto
  * Configuración de parametros infraestructura
  * Configuración de entorno de infraestructura `web server` `ddbb`, etc.
  * Permisos

Esta basado en [phing](https://github.com/phingofficial/phing) y [composer](https://github.com/composer/composer).

## ¿Por qué?

Dado que existe multiples herramientas para deploy muy maduras, *puppet*, *chef*, etc, entonces me encontre con la necesitad de llenar un hueco a la hora de automatizar la construcción de un proyecto en php. Al momento de terminar un deploy sobre un proyecto suele exister tareas comunes que pueden ser automatizadas, como por ejemplo, borrado de cache, rotación de logs, rollback, etc. La idea del framework es disponer de tareas comunes que sean reutilizables y adaptables a la logica de cada proyecto independiente de como este construido el proyecto, sin depender de ningún framework en particular .

## ¿Como?

### Etapas
Este seria el ciclo tipo de la construcción de un proyecto.

 Básicamente el Huarpe trabaja sobre 3 etapas:

* **Setup**: Cuando es un nueva instalación. En realidad es un **release** desde cero
* **Release**: Lanzamiento de proyecto con todas sus etapas de construcción
* **Rollback**: Restauración del **release** anterior

![Cliclo](https://raw.github.com/javier123mendoza/huarpe/master/docs/stages.png)


