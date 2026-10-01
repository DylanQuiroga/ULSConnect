# ULSConnect: Plataforma para SOULS

## Resumen del Proyecto
La plataforma web UlsConnect es un sistema diseñado para gestionar actividades y convocatorias de voluntariado pertenecientes al programa SOULS de la Universidad de La Serena. El sistema permite:

* Publicación de convocatorias
* Inscripción de voluntarios
* Seguimiento de participación


## Objetivos y Alcance
Objetivo principal: Digitalizar y automatizar el proceso de gestión del voluntariado para mejorar la organización, trazabilidad y participación estudiantil.
Contexto previo: Antes de UlsConnect, el programa SOULS utilizaba herramientas como Google Forms y plataformas de mensajería (ej. WhatsApp) para coordinar sus actividades.


## Alcance Funcional
La plataforma contempla las siguientes funcionalidades:

* Registro e inicio de sesión de voluntarios
* Panel de administración para gestión de convocatorias
* Inscripción en actividades
* Control de asistencia
* Evaluación posterior del impacto del voluntariado
  
## Tecnologías Utilizadas
### Frontend
* React: Biblioteca de JavaScript para construir interfaces dinámicas y eficientes.
* React Router DOM: Gestión de rutas y navegación en aplicaciones SPA.
* Axios: Cliente HTTP para consumir APIs de manera sencilla y estructurada.
* Bootstrap / React-Bootstrap: Framework de estilos y componentes predefinidos para diseño responsivo.
* React Calendar: Componente para gestión y visualización de calendarios.
* React Icons: Librería de íconos personalizables para mejorar la interfaz.
* Zustand: Librería ligera para manejo de estado global en React.
* 
### Backend
* Express: Framework minimalista para Node.js que facilita la creación de APIs y servidores web.
* Mongoose: ODM para trabajar con MongoDB de forma estructurada y orientada a objetos.
* Express Validator: Middleware para validación de datos en las solicitudes.
* Express Session + Connect-Mongo: Manejo de sesiones persistentes con almacenamiento en MongoDB.
* BcryptJS: Librería para encriptación y verificación de contraseñas.
* Helmet: Middleware de seguridad para proteger la aplicación de vulnerabilidades comunes.
* Express Rate Limit: Control de peticiones para prevenir ataques de fuerza bruta o abuso de la API.
* Nodemailer: Herramienta para envío de correos electrónicos desde el servidor.
* EJS: Motor de plantillas para renderizar vistas dinámicas.
* Sanitize-HTML: Librería para limpiar y proteger contenido HTML contra inyecciones maliciosas.
* 
### Base de Datos
* MongoDB
* Base de datos NoSQL orientada a documentos
* Utiliza colecciones y documentos en formato JSON/BSON
* Ideal para datos estructurados y semiestructurados
* Escalabilidad horizontal y alto rendimiento
* Amplia integración con entornos de desarrollo web modernos

## Arquitectura de la Plataforma
La arquitectura se basa en un modelo cliente-servidor con las siguientes capas:
* Frontend (React): interfaz de usuario interactiva
* Backend (Express): lógica de negocio y gestión de servicios
* Base de datos (MongoDB): almacenamiento y gestión de información

