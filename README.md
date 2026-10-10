# Cartera Digital - Proyecto Node y Express Web App | Módulo 10 ABP

**Bootcamp:** Desarrollo de Aplicaciones Full Stack JavaScript Trainee  
**Autor:** Mauricio Fernandez Castro  
**Repo:** (https://github.com/mauriciofernandezcastro/modulo_9.git)

### 📋 Descripción
Aplicación web de Cartera Digital que permite a usuarios crear cuenta, iniciar sesión, consultar saldo, realizar transferencias y ver historial de movimientos. Proyecto integrador Full Stack.

### 🎯 Objetivo ABP
Cumplir con aspectos técnicos, conceptuales y objetivo de la consigna M10: construir una Web App con Node.js y Express, con estructura clara, fundamentos documentados y valor para portafolio profesional.

### 🚀 Tecnologías
- Node.js + Express.js
- EJS / HTML, CSS, JavaScript
- Base de datos: JSON / MongoDB
- bcrypt, express-session / JWT, dotenv
- Git & GitHub

### ✨ Funcionalidades
- [x] Registro y Login de usuarios
- [x] Dashboard con saldo actual
- [x] Transferencia entre usuarios con validación de saldo
- [x] Historial de transacciones
- [x] Logout y protección de rutas

### 🏗️ Estructura del proyecto
```
/app.js (o server.js) -> Servidor principal
/routes -> Rutas de usuarios y transacciones
/controllers -> Lógica de negocio
/models -> Modelos de datos
/views -> Plantillas EJS
/public -> CSS, JS, imágenes
/.env -> Variables de entorno
/.gitignore
```

### 💡 Decisiones tomadas
1. **Express** por su minimalismo y comunidad.
2. **Arquitectura MVC** para escalabilidad.
3. **Sesiones** para mantener autenticación simple en MVP, escalable a JWT.
4. Validación de transacciones para evitar saldos negativos.

### ▶️ Cómo ejecutar
```bash
npm install
npm start
# Abrir http://localhost:3000
```

### 📦 Entrega Módulo 10
Este proyecto forma parte de mi portafolio de productos digitales y demuestra mi evolución en el bootcamp. Cumple con presentación clara, fundamentos y registro de decisiones.

---
Hecho con 💻 por Mauricio Fernandez Castro - Valparaíso, Chile
