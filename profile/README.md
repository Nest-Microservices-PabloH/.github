<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# 🚀 Sistema de Microservicios con NestJS

## 📝 Descripción
Este proyecto implementa una arquitectura de microservicios moderna y escalable utilizando NestJS como framework principal. Diseñado para ofrecer alta disponibilidad, escalabilidad y mantenibilidad, este sistema demuestra las mejores prácticas en el desarrollo de aplicaciones distribuidas.

## 🛠 Tecnologías Principales

- **NestJS**: Framework principal para el desarrollo de aplicaciones Node.js
- **Prisma**: ORM moderno para la gestión de bases de datos
- **NATS**: Sistema de mensajería para la comunicación entre microservicios
- **Docker**: Containerización de servicios
- **PostgreSQL**: Base de datos principal con Neon Tech
- **MongoDB Atlas**: Base de datos NoSQL en la nube
- **TypeScript**: Lenguaje de programación principal
- **Stripe**: Procesamiento de pagos
- **Google Cloud Platform**: Infraestructura en la nube
- **Kubernetes**: Orquestación de contenedores

## 🌟 Características

- 🔄 Comunicación asíncrona entre servicios
- 📦 Arquitectura modular y desacoplada
- 🔒 Manejo seguro de datos y autenticación
- 📊 Monitoreo y logging centralizado
- 🚀 Alta disponibilidad y escalabilidad
- 🛡 Manejo de errores robusto
- 💳 Integración con Stripe para pagos
- 🔔 Sistema de webhooks para eventos
- ☁️ Despliegue en Google Cloud Platform
- 🎯 Orquestación con Kubernetes
- 📱 API RESTful para integración con clientes

## 🏗 Estructura del Proyecto

El sistema está compuesto por los siguientes microservicios independientes, cada uno con su propia base de datos y responsabilidades específicas:

- **auth-ms**: Gestión de autenticación y autorización de usuarios
- **client-gateway**: API Gateway para la gestión de clientes
- **orders-ms**: Procesamiento y gestión de órdenes
- **payments-ms**: Procesamiento de pagos y transacciones con Stripe
- **products-ms**: Gestión del catálogo de productos
