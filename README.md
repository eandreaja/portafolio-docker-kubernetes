# Portafolio Docker y Kubernetes

Andrea Jaramillo · Python Developer · Data Science en formación

Este repositorio reúne mi trabajo práctico del workshop **"De Cero a Capitán en Kubernetes"** (Cloud Native Medellín, capítulo CNCF). Mi objetivo es aprender a llevar un proyecto de Python desde el código hasta un contenedor y un clúster.

Cada reto parte de un escenario roto (troubleshooting) que hay que diagnosticar y corregir. Por eso, cada solución explica el síntoma, la causa y el arreglo, no solo el código final.

## Progreso

El progreso oficial y verificado está en el portafolio del curso, que se actualiza solo: [ver portafolio verificado](https://github.com/edwinbermudez91/Fundamentos-Kubernetes/tree/main/aportes-comunidad/soluciones-retos/eandreaja).

Mi entrega de la Semana 00 fue incorporada al repositorio del curso mediante el [PR #89](https://github.com/edwinbermudez91/Fundamentos-Kubernetes/pull/89).

Este repositorio guarda una copia curada de mis soluciones y bitácoras, que actualizo al terminar cada semana.

| Semana | Tema | Estado |
| --- | --- | --- |
| 00 | Fundamentos de Docker | Entregada |
| 01 | Arquitectura de Kubernetes y Pods | Pendiente |
| 02 | Deployments, réplicas y autorreparación | Pendiente |
| 03 | Redes en Kubernetes (Services y Gateway API) | Pendiente |
| 04 | ConfigMaps, Secrets y volúmenes persistentes | Pendiente |
| 05 | Probes, límites y RBAC | Pendiente |
| 06 | Helm y proyecto final | Pendiente |

## Semana 00: Fundamentos de Docker

| Reto | Qué se resolvió |
| --- | --- |
| [01 · Dockerfile roto](semana-00/01-dockerfile-roto) | Contenedor que se apagaba al instante |
| [02 · Variable de entorno faltante](semana-00/02-variable-entorno-faltante) | Configuración por variables de entorno |
| [03 · Contenedor como root](semana-00/03-contenedor-como-root) | Ejecución sin privilegios (rootless) |
| [04 · .dockerignore y archivos secretos](semana-00/04-dockerignore-y-archivos-secretos) | Evitar filtrar secretos en la imagen |
| [05 · Puerto y host desalineado](semana-00/05-puerto-y-host-desalineado) | Red y puertos entre contenedor y host |

Reflexión técnica de la semana: [bitácora](semana-00/bitacora.md).
