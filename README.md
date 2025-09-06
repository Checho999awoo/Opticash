# Gestión Laboratorio

## Resumen del Proyecto

El proyecto consiste en diseñar e implementar un sistema académico llamado **OptiCash** de gestión de préstamos personales. Su objetivo es permitir al usuario:
- Registrar sus créditos  
- Calcular cuotas básicas (con intereses simples o compuestos)  
- Realizar abonos a capital  
- Recibir alertas cuando los pagos superen un porcentaje de sus ingresos registrados  
- Sugerir o recalcular el crédito con abonos a capital para que el usuario termine el crédito lo más pronto posible  

## Documentación

Repositorios con la documentación:
- Documentación general  
- Gestión de Agenda  
- Gestión de Hoja de Vida  
- Enlace de interés  
- Drive Avance del proyecto  
- Mockups  

## Repositorio Frontend

Para el despliegue del frontend, consulte el repositorio correspondiente: **Frontend**

## Repositorio Backend

Los componentes del backend se despliegan mediante los siguientes repositorios:
- Backend Seguridad  
- Backend Gestión de Agenda  
- Backend Gestión de Hoja de Vida  

## Exponer Servicios

Para garantizar una arquitectura escalable y segura, los servicios del sistema se exponen a través de un **API Gateway**. Este componente actúa como un punto de entrada único para todas las solicitudes de los clientes, proporcionando una capa de abstracción que simplifica la interacción con los diferentes microservicios del sistema.

El API Gateway también ofrece funcionalidades avanzadas de seguridad, monitoreo y gestión del tráfico. Así:
- Implementa políticas de autorización y autenticación  
- Permite análisis de tráfico en tiempo real  
- Garantiza la alta disponibilidad del sistema  

De esta manera, el API Gateway juega un papel fundamental en la robustez y confiabilidad del sistema de gestión de laboratorios de la Corporación Universitaria del Huila - **CORHUILA**.

