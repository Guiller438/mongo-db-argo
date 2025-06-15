# MongoDB + Mongo Express en Kubernetes con Argo CD (GitOps)

Este repositorio contiene los manifiestos YAML necesarios para desplegar una base de datos MongoDB y su interfaz web Mongo Express en un clúster Kubernetes usando Argo CD como herramienta de Continuous Delivery.

## 🚀 Componentes desplegados

- `mongo-deployment.yaml`: Despliegue de MongoDB con usuario y contraseña.
- `mongo-service.yaml`: Servicio interno para exponer MongoDB.
- `mongo-express-deployment.yaml`: Despliegue de la interfaz web Mongo Express.
- `mongo-pod.yml`: Versión de pod simple de MongoDB (usado en pruebas).

## 🧠 Arquitectura

Los componentes son desplegados en el namespace `default` y sincronizados automáticamente desde este repositorio.

