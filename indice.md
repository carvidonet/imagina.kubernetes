# Índice curso Kubernetes Avanzado

## Tema 1 - Fundamentos de contenedores y Kubernetes

1. Del Monolito a Microservicios
2. ¿Qué es un contenedor?
3. Orquestación de contenedores
4. Arquitectura de Kubernetes
5. Clusters de Kubernetes
6. Los Nodos de Kubernetes
7. Los Pods de Kubernetes
8. Ciclo de releases y política de versiones (version skew policy)
9. Introducción a las redes de comunicación en Kubernetes
10. Container-to-Container
11. Comunicación Pod-to-Pod
12. Comunicación Pod-to-Service
13. Comunicación External-to-Service
14. Instalación de Kubernetes: consideraciones, métodos y requerimientos
15. Creación de un clúster de Kubernetes en local
16. minikube
17. microk8s
18. kind
19. Repasando de kubectl y Kubernetes API

## Tema 2 - Creación de cargas de trabajo

1. Cargas de trabajo en Kubernetes
2. Creación de un deployment imperativamente
3. Creación de desployment declarativamente
4. Escalado de un Deployment
5. Imperativo vs Declarativo
6. Gestionando Rollouts y Rollbacks de un Deployment
7. Gestión y versionando de ficheros YAML con Git y GitHub

## Tema 3 - Clústers de Kubernetes en el cloud

1. Introducción a las soluciones en la nube más destacables en la actualidad
2. Ventajas y desventajas del uso del cloud
3. Creación de una uenta gratuita de AWS
4. Configuración y trabajo de Kubernetes en AWS: EKS (EKS en AWS no es gratuito, se paga el control plane por hora ~70$ al mes)
5. Creación de una cuenta gratuita de Azure
6. Configuración y trabajo de Kubernetes en Azure: AKS (AKS puede ser gratuito en Azure con el budget de la primera cuenta 200$)
7. Creación una cuenta gratuita de Google Cloud Platform (GCP)
8. Configuración y trabajo de Kubernetes en GCP: GKE
9. Comparativa entre AWS, AKS y GKE
10. Recomendaciones y consejos para trabajar en la nube

## Tema 4 - Gestión de clústeres de Kubernetes con IAC (Infrastructure as Code)

1. ¿Qué es la infrastructura como código (IaC)?
2. Introducción a terraform
3. Ventajas y desventajas del uso de terraform
4. Alternativas a terraform más destacables
5. Generación de un cluster en la nube con terraform
6. Buenas prácticas de la IaC y terraform

## Tema 5 - Integración continua, testing y despliegue

1. Introducción a la ntegración continua (CI)
2. Introducción al despliegue continuo (CD)
3. Características principales de CI/CD
4. Ejemplos reales de CI/CD
5. Integración y despliegue continuo con GitHub Actions
6. Creación de imágenes de contenedor
7. Etiquetado de imágenes de contenedor y uso del container registry de GCP
8. Despliegue Continuo de apps en GKE
9. Estrategias de despliegue y recomendaciones

## Tema 6 - Profundizando en los Controladores

1. Controladores en Kubernetes
2. Jobs
3. StatefulSet
4. DaemonSet
5. CronJob y Job
6. HorizontalPodAutoscaler
7. VerticalPodAutoscaler
8. Keda

## Tema 7 - Profundizando en las redes y servicios de Kubernetes

1. Modelo de red en Kubernetes, CNI
2. Servicios en Kubernetes
3. Servicio ClusterIP
4. Servicio NodePort
5. Servicio Loadbalancer
6. Servicio ExternalName
7. Depuración con port-forward
8. Aplicaciones Accesibles a través de un balanceador de carga
9. Reglas de enrutamiento con IngressController y certificados TLS con Cert Manager
10. Patrón sidecar y service mesh con Istio
11. Gestion de redes y servicios en la nube

## Tema 8 - Almacenamiento persistente en Kubernetes

1. Cattle vs Pets
2. Ciclo de vida del almacenamiento persistente
3. Aprovisionamiento estático
4. La Importancia de PersistentVolumes
5. Almacenamiento efimero (EphemeralStorage)
6. Storage Class y Aprovisionamiento Dinámico
7. Volúmenes Persistentes en soluciones cloud
8. Aprovisionamiento dinámico en soluciones cloud

## Tema 9 - Securizando un clúster de Kubernetes

1. Seguridad en la API y autenticación
2. Buenas Prácticas en la gestión de usuarios y roles en Kubernetes
3. RBAC (Role Based Access Control) en Kubernetes
4. Cuentas de servicio y credenciales
5. TLS y certificados en Kubernetes
6. Políticas de red para gestionar tráfico (Network Policies)
7. CIS Benchmark

## Tema 10 - Gestión de fallos en Kubernetes

1. Fallos habituales en entornos reales
2. Fallos en los nodos control-plane
3. Fallos en los worker-node
4. Fallos en aplicaciones
5. Fallos de red
6. Fallos en el almacenamiento
7. Administrar y asegurar la tolerancia a fallos

## Tema 11 - End-to-End Tests en un Cluster Kubernetes

1. ¿Qué son las Ppuebas End-to-End (e2e)?
2. Tipos de pruebas e2e más vomunes para los clústeres de Kubernetes
3. Creación de tests e2e para Kubernetes
4. Accediendo y aAnalizando los resultados de las Pruebas e2e
5. Buenas prácticas y consejos al desarrollar tests e2e para clústeres de Kubernetes

## Tema 12 - Tolerancia a fallos, mantenimiento y recuperación de desastres

1. Alta Disponibilidad
2. Topología para un cluster de alta disponibilidad
3. Redundancia de etcd y respaldos
4. PersistentVolumes
5. Worker-nodes
6. Actualización de un clúster
7. Heptio Ark
8. Buenas prácticas

## Tema 13 - Observabilidad de Kubernetes

1. ¿Qué es la observabilidad?
2. Niveles de Logging
3. Gestion de logs en Kubernetes
4. Soluciones de Logging: Fluentd y Fluentbit
5. Introducción a las Métricas en Kubernetes
6. Metrics Server
7. Prometheus
8. Grafana
9. Plataformas de observabilidad
10. Datadog
11. Dynatrace
12. Comparativas y conclusiones 
13. Monitoreo y alertas en soluciones cloud

## Tema 14 - Gobernanza de los clústeres de Kubernetes

1. La importancia de la gobernanza de un clúster
2. Políticas de admission y control
3. Gatekeeper
4. Primer vistazo a gatekeeper
5. Definiendo restricciones y plantillas de restricciones
6. Replica de datos
7. Buenas prácticas

## Tema 15 - Gestión multi-clúster

1. Beneficios de usar múltiples clústeres
2. Problemas que nos podemos encontrar
3. Despliegue de múltiples clusteres
4. Patrones de despliegue y administración
5. GitOps para gestionar múltiples clusteres
6. Herramientas de administración
7. Kubernetes federation
8. Buenas prácticas

## Tema 16 - Proyecto Final

1. Estableciendo los requisitos del proyecto
2. Configuraciones e implementaciones de la solución
3. Revisando el correcto funcionamiento
4. Consejos y recomendaciones para siguientes Pasos
