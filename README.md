# Aplicación Móvil para la Gestión de Rutinas de Entrenamiento Físico en un Gimnasio

## Descripción

Esta aplicación móvil está diseñada para los clientes de un gimnasio, proporcionando una plataforma integral donde pueden gestionar sus entrenamientos y evaluaciones corporales. La aplicación permite a los usuarios realizar las siguientes acciones:

- **Registrarse**: Los nuevos usuarios pueden crear una cuenta en la aplicación de manera sencilla.
- **Comprar mensualidad**: Los usuarios registrados pueden adquirir una membresía mensual para acceder a todas las funcionalidades del gimnasio.
- **Seleccionar rutinas**: Los usuarios pueden elegir entre varias rutinas de entrenamiento diseñadas por profesionales.
- **Registrar medidas**: Los usuarios pueden registrar sus medidas corporales para llevar un seguimiento detallado de su progreso físico.
- **Generar QR**: Los usuarios pueden generar un código QR único que les permite ingresar al gimnasio de forma rápida y segura.

## Tecnologías Utilizadas

### Frontend
- **Framework**: Flutter (Dart)
- **Plataformas**: Android e iOS
- **Características**: Diseño responsivo y multiplataforma, accesibilidad para todos los usuarios, soporte para diferentes navegadores.

### Backend
- **Framework**: .NET 8
- **Arquitectura**: Clean Architecture con patrón MVC
- **Seguridad**: Autenticación y autorización, encriptación de datos sensibles

### Base de Datos
- **Gestor**: SQL Server 2022
- **Despliegue**: Servidor Linux con Nginx

### Infraestructura
- **Servidor**: Linux con Nginx
- **Despliegue**: Backend y base de datos desplegados en un entorno seguro y escalable

## Estructura del Proyecto

- **/frontend**: Contiene el código fuente del frontend desarrollado en Flutter.
- **/backend**: Contiene el código fuente del backend desarrollado en .NET 8.
- **/database**: Contiene los scripts y configuraciones de la base de datos SQL Server 2022.
- **/docs**: Documentación adicional del proyecto.

## Instalación y Configuración

### Requisitos Previos

- **Flutter**: [Instrucciones de instalación](https://flutter.dev/docs/get-started/install)
- **.NET 8 SDK**: [Instrucciones de instalación](https://dotnet.microsoft.com/download/dotnet/8.0)
- **SQL Server 2022**: [Instrucciones de instalación](https://docs.microsoft.com/en-us/sql/sql-server/download-sql-server-2022)
- **Nginx**: [Instrucciones de instalación](https://nginx.org/en/docs/install.html)

### Pasos de Instalación

1. **Clonar el Repositorio**
   ```sh
   git clone https://github.com/tu-usuario/app-gym-24.git
   cd app-gym-24
