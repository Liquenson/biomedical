# bioMedical

Proyecto demo basado en Spring Boot para una aplicación biomédica.

## Descripción

bioMedical es una aplicación web desarrollada con Spring Boot que integra funcionalidades de acceso a datos con JPA, renderizado de vistas con Thymeleaf, seguridad con Spring Security, y soporte para correo electrónico. Utiliza una base de datos H2 en memoria para desarrollo y pruebas, y está preparada para usar otras bases de datos como MySQL si se desea.

## Tecnologías y dependencias principales

- **Spring Boot 2.2.4.RELEASE**
- **Java 8**
- **Spring Data JPA** – Gestión de persistencia y acceso a base de datos.
- **Thymeleaf** – Motor de plantillas para renderizar vistas HTML.
- **Spring Web** – Creación de controladores REST y MVC.
- **Spring Security** – Autenticación y autorización.
- **Spring Boot DevTools** – Mejoras para desarrollo (recarga automática).
- **Base de datos H2** – Base de datos en memoria para pruebas y desarrollo.
- **Zxcvbn** – Librería para evaluar la fortaleza de contraseñas.
- **NekoHTML** – Parser HTML para procesamiento adicional.
- **Spring Boot Starter Mail** – Soporte para envío de correos electrónicos.
- **Spring Boot Starter Test** – Dependencias para pruebas unitarias e integración.

## Requisitos

- JDK 8 instalado
- Maven instalado (para gestionar dependencias y construir el proyecto)

## Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd bioMedical



# patients_geolocation
Project to locate patients in order to facilitate their home appointments by medical specialists
