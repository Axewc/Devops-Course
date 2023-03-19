# Notas DevOps con Docker, Jenkins, Kubernetes, git, GitFlow CI/CD y más.

Antes de empezar, haremos una reflexión del como se compone una compañía en la que no tenemos un departamento de DevOps, y como se compone una compañía en la que si tenemos un departamento de DevOps.

Tenemos el equipo de desarrollo, que es el que se encarga de desarrollar el producto, y el equipo de operaciones, que es el que se encarga de mantener el producto en producción.

## Problemática de la compañía sin DevOps

Desarollo : aisalmiento de equipos, fricción entre los equipo, uso de correo sobre comunicación ágil, baja automatización.

Infraestructura: Scripts rudimentarios, calendarios de relases fijos y puesta en producción más lenta. 

La puesta en producción es más lenta porque se tiene que hacer un calendario de releases, y se tiene que hacer una puesta en producción manual.

Buscamos agilidad en el desarrollo, pero justamente esto está basado en lo que ocurriría si en la comañía no hubiera un departamento de DevOps.

Con DevOps se busca eliminar la fricción entre los equipos, y mejorar la comunicación entre ellos.

## ¿Qué es DevOps?
Es la unión de procesos, personas y tecnologia, con el fin de proporcionar valor continuamente a los clientes.

Mayor calidad, menor costo y menor tiempo.

DevOps = Dev (Development) + Ops (Operation)

El ciclo de vida de DevOps es el siguiente:

Todo empieza con un plan, seguido del desarrollo, la construcción, la prueba, el relase, deploy operaciones y el monitoreo.
Como se ve en la siguiente imagen: 

![Ciclo de vida de DevOps](https://www.simform.com/wp-content/uploads/2022/01/what-is-devops-lifecycle.png)

## Aspectos fundamentales de DevOps
* Control de versiones: git,svn, -> github, gitlab, bitbucket, mercurial
* Integración continua: Pipelines jenkins -> Automatizar compilaciones y pruebas cuando se hace un push a un repositorio.
* Entrega continua: Suministro de software rápido y confibale a los usuarios finales en cualquier momento.
* Infraestructura como código: Terraform -> Definición declarativa de la infraestructura mediante archivos de definición basados en texto, para revertir, desmontar y reproducir la infraestructura.
* Supervusión y registro: Prometheus, Grafana, ELK, -> Recopilaicón de metricas y vinculación de datos de performance y logs, monitoreo de la infraestructura y aplicaciones.
* Aprendizaje validado: Analisis de datos para mejorar los procesos en cada nuevo ciclo, y mejorar la calidad del producto. Por ejemplo con A/B testing.

## Estructura de las notas, y como se van a ir desarrollando

Objetivo: Concertirnos en un Site Reliability Engineer (SRE), es decir un ingeniero de confiabilidad de sitios.

Comprenderemos en un 50% la parte de desarrollo, y en un 50% la parte de operaciones.

Vamos a empezar por la parte de operaciones:
1. Docker 
2. Kubernetes
3. Prometheus
4. Grafana
    * Pipelines Jenkins
    * Slack 

Por la parte de desarrollo:
1. Git flow
2. Github / gitlab
3. Microservicios
4. Pruebas unitarias

DevOps es algo tan ambicioso que no se puede aprender en un día, por lo que se va a ir desarrollando en el tiempo, ser una persona que sepa trabajar todo esto, con los objetivos de entregar software de calidad, en menor tiempo y con menor costo.

La responsabilidad del SRE es proveer estos conocimientos y herramientas para tener mejores prácticas. 

A grandes rasgos, el SRE es un ingeniero que se encarga de la confiabilidad de los sistemas, y que se encarga de que los sistemas estén siempre disponibles, y que se puedan recuperar de cualquier problema que ocurra.



