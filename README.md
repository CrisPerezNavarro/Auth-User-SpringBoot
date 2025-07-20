# 🔐 Sistema de Autenticación con JWT - Spring Boot + React

Este proyecto es una solución completa de autenticación de usuarios basada en **JWT (JSON Web Tokens)**, construida con un **backend en Spring Boot** y un **frontend en React**. Incluye funcionalidades como registro, inicio de sesión, protección de rutas y control de acceso por roles.

---

## 🚀 Tecnologías utilizadas

### 🔧 Backend (Spring Boot)
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- MySQL
- JPA / Hibernate
- Maven

### 🌐 Frontend (React)
- React.js
- Axios
- CSS

---

## 📁 Estructura del repositorio
jwt-auth-app/
├── backend/ # Proyecto Spring Boot
│ ├── src/
│ └── pom.xml
├── frontend/ # Proyecto React
│ ├── src/
│ └── package.json
└── README.md


---

## 📋 Requisitos

- Java 17 o superior
- Maven
- MySQL
- Postman o frontend para pruebas (opcional)

---

## ⚙️ Configuración

### 1. Variables de entorno

Asegúrate de agregar las siguientes propiedades en `application.properties`:

```properties
# Nombre de la aplicación (opcional)
spring.application.name=jwt-auth-backend

# Configuración de la base de datos
spring.datasource.url=jdbc:mysql://localhost:3306/jwt_auth_db?useSSL=false&serverTimezone=UTC
spring.datasource.username=tu_usuario_mysql
spring.datasource.password=tu_contraseña_mysql

# Configuración JWT
jwt.secret=TuJWTSecretSeguro123456789
jwt.expiration=86400000  # 1 día en milisegundos



