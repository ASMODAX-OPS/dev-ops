# 🚀 DevOps Project - CI/CD Pipeline

## 📋 Descripción del Proyecto

Este es un proyecto completo de **DevOps** que implementa una **Pipeline de Integración y Entrega Continua (CI/CD)** automatizada. El sistema despliega una aplicación web Java utilizando tecnologías modernas de desarrollo y operaciones.

## 🛠️ Stack Tecnológico

### 🔧 Backend & Frontend
- **Java 11** - Lenguaje de programación principal
- **Maven** - Gestión de dependencias y construcción
- **Servlet API 4.0** - Tecnología web para aplicaciones Java
- **JUnit & Mockito** - Testing y mocking framework

### 🏗️ Infraestructura & DevOps
- **Jenkins** - Servidor de automatización CI/CD
- **Docker** - Contenerización y despliegue
- **Git/GitHub** - Control de versiones y repositorio
- **SSH** - Conexiones seguras entre servidores

## 🔄 Pipeline CI/CD

### 📥 Fase 1: Integración Continua

**Git Push → Jenkins Webhook → Build Automático → Pruebas Unitarias → Análisis de Calidad**

### 🚀 Fase 2: Entrega Continua  

**Empaquetado WAR → Transferencia SSH → Despliegue en Docker Host → Verificación**

## 🏗️ Estructura del Proyecto  

 **dev-ops/
├── 📁 server/ # Módulo de lógica de negocio (JAR)
├── 📁 webapp/ # Aplicación web desplegable (WAR)
├── ⚙️ pom.xml # Configuración principal Maven
├── 🔧 Jenkinsfile # Pipeline como código
└── 🐳 Dockerfile # Configuración de contenedores**

## ✨ Características Principales

### ✅ Automatización Completa
- **Build automático** en cada commit
- **Pruebas automatizadas** y reportes de calidad
- **Despliegue continuo** sin intervención manual

### 🔒 Seguridad y Estabilidad
- **Conexiones SSH seguras** entre servidores
- **Gestión de dependencias** con Maven
- **Contenerización** con Docker para entornos consistentes

## 🚀 Quick Start

### Prerrequisitos
```bash
Java 11+, Maven 3.6+, Docker, Jenkins
```

⭐ **Si este proyecto te resulta útil, por favor dale una estrella en GitHub!**
