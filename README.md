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
2. **Configurar el Backend**

Navega a la carpeta del backend:
sh
Copiar código
cd backend
Restaura los paquetes de NuGet:
sh
Copiar código
dotnet restore
Configura las cadenas de conexión y otras configuraciones necesarias.
3. **Configurar la Base de Datos**

Navega a la carpeta de la base de datos:
sh
Copiar código
cd database
Ejecuta los scripts de SQL para crear la base de datos y las tablas necesarias.
4. **Configurar el Frontend**

Navega a la carpeta del frontend:
sh
Copiar código
cd frontend
Instala las dependencias de Flutter:
sh
Copiar código
flutter pub get
5. **Desplegar en el Servidor**

Configura Nginx para servir tu aplicación backend y frontend.
Asegúrate de que todos los servicios estén corriendo correctamente.
### Uso de la Aplicación
### Registro de Usuario
Los usuarios pueden registrarse proporcionando sus datos personales a través de un formulario en la aplicación.

### Compra de Membresía
Una vez registrados, los usuarios pueden comprar una membresía mensual que les da acceso a todas las funcionalidades de la aplicación.

### Selección de Rutinas
Los usuarios pueden navegar por una lista de rutinas de entrenamiento disponibles y seleccionar la que mejor se adapte a sus objetivos.

### Registro de Medidas Corporales
La aplicación permite a los usuarios registrar y hacer seguimiento de sus medidas corporales para monitorear su progreso físico.

### Generación de Código QR
Los usuarios pueden generar un código QR único que les permite ingresar al gimnasio de forma rápida y segura.

### Licencia
Este proyecto está licenciado bajo la Licencia BSD 3-Clause. Para más detalles, consulta el archivo LICENSE.

### Contacto
Para más información o preguntas, puedes contactarnos a través de jimmycarrionp@gmail.com.

### Referencias
Flutter Documentation
Microsoft .NET Documentation
SQL Server Documentation
Nginx Documentation
