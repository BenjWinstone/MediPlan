# MediPlan

## Tecnologías de MediPlan

### Resumen por plataforma

| Plataforma | Estado | Tecnologías principales |
|---|---|---|
| Android | Aplicación móvil inicial | .NET MAUI 10, C#, SQLite, FCM |
| Escritorio (web) | Portal web inicial | Blazor Web App, C#, HTML, CSS, Razor |
| iOS | Expansión futura | .NET MAUI 10, C#, SQLite, APNs |
| Backend (común) | Servicios compartidos | ASP.NET Core Web API 10, EF Core 10, Hangfire, Azure SQL, Azure App Service |

### Desglose

| Tecnología | Categoría | Para qué se usa | Plataforma |
|---|---|---|---|
| C# | Lenguaje de programación | Lenguaje principal del proyecto, compartido por la app, el portal y el servidor | Android, iOS, Web (escritorio), Backend |
| HTML | Lenguaje de programación | Estructura de las páginas del portal web | Web (escritorio) |
| CSS | Lenguaje de programación | Estilos y presentación del portal web | Web (escritorio) |
| Razor | Lenguaje de programación | Combina HTML y C# para construir componentes de Blazor | Web (escritorio) |
| .NET 10 | Ecosistema | Plataforma común sobre la que se construye toda la solución | Android, iOS, Web (escritorio), Backend |
| .NET MAUI 10 | Framework frontend | Aplicación móvil multiplataforma con una sola base de código en C# | Android (inicial), iOS (futuro) |
| Blazor Web App | Framework frontend | Interfaz del portal web, con modo interactivo Interactive Server | Web (escritorio) |
| ASP.NET Core Web API 10 | Framework backend | API REST que atiende a la app y al portal, y concentra la lógica de negocio | Backend común |
| Entity Framework Core 10 | ORM | Acceso a datos y comunicación con la base de datos central | Backend |
| Hangfire | Backend | Tareas programadas y trabajos en segundo plano | Backend |
| Azure SQL | Almacenamiento / Infraestructura | Base de datos central en la nube, compartida por todas las plataformas | Backend (nube) |
| SQLite | Almacenamiento local | Almacenamiento local dentro del dispositivo | Android, iOS |
| Azure App Service | Infraestructura | Alojamiento en la nube del backend y del portal web | Backend, Web |
| HTTPS/TLS | Seguridad | Comunicación cifrada entre clientes y servidor | Todas |
| Notificaciones locales | Notificaciones | Notificaciones programadas del propio dispositivo | Android, iOS |
| Firebase Cloud Messaging (FCM) | Notificaciones push | Notificaciones push | Android |
| Apple Push Notification service (APNs) | Notificaciones push | Notificaciones push | iOS |
| Git | Control de versiones | Control de versiones del código fuente de todo el proyecto | Todas |
| GitHub | Colaboración | Repositorio remoto y espacio de colaboración del equipo | Todas |
