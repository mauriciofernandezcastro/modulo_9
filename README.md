Cartera Digital - Proyecto Node y Express Web App | Módulo 10 ABP
Bootcamp: Desarrollo de Aplicaciones Full Stack JavaScript Trainee
Autor: Mauricio Fernandez Castro
Repo: https://github.com/mauriciofernandezcastro/Proyecto-Node-y-Express-Web-App---Modulo-8.git

📋 Descripción
Aplicación web de Cartera Digital que permite a usuarios crear cuenta, iniciar sesión, consultar saldo, realizar transferencias y ver historial de movimientos. Proyecto integrador Full Stack.

🎯 Objetivo ABP
Cumplir con aspectos técnicos, conceptuales y objetivo de la consigna M10: construir una Web App con Node.js y Express, con estructura clara, fundamentos documentados y valor para portafolio profesional.

🚀 Tecnologías
Node.js + Express.js
EJS / HTML, CSS, JavaScript
Base de datos: JSON / MongoDB
bcrypt, express-session / JWT, dotenv
Git & GitHub
✨ Funcionalidades
 Registro y Login de usuarios
 Dashboard con saldo actual
 Transferencia entre usuarios con validación de saldo
 Historial de transacciones
 Logout y protección de rutas
🏗️ Estructura del proyecto
/app.js (o server.js) -> Servidor principal
/routes -> Rutas de usuarios y transacciones
/controllers -> Lógica de negocio
/models -> Modelos de datos
/views -> Plantillas EJS
/public -> CSS, JS, imágenes
/.env -> Variables de entorno
/.gitignore
💡 Decisiones tomadas
Express por su minimalismo y comunidad.
Arquitectura MVC para escalabilidad.
Sesiones para mantener autenticación simple en MVP, escalable a JWT.
Validación de transacciones para evitar saldos negativos.
▶️ Cómo ejecutar
npm install
npm start
# Abrir http://localhost:3000
📦 Entrega Módulo 10
Este proyecto forma parte de mi portafolio de productos digitales y demuestra mi evolución en el bootcamp. Cumple con presentación clara, fundamentos y registro de decisiones.

Hecho con 💻 por Mauricio Fernandez Castro - Valparaíso, Chile
