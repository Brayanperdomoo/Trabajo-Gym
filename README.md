<div align="center">

# 🏋️ Gym Management System

### Sistema integral de gestión para gimnasios

Aplicación web full stack desarrollada para administrar usuarios, membresías, entrenamientos, pagos y control general de un gimnasio.

---

![Angular](https://img.shields.io/badge/Frontend-Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![PHP](https://img.shields.io/badge/Backend-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

---

## 📌 Descripción del proyecto

Gym Management System es una solución tecnológica diseñada para optimizar la administración de gimnasios mediante una plataforma moderna y escalable.

El sistema permite gestionar:

- 👥 Usuarios y roles
- 💳 Membresías
- 📅 Reservas o control de acceso
- 🏋️ Rutinas y planes de entrenamiento
- 💰 Pagos y control financiero
- 📊 Administración general del gimnasio

Este proyecto está dividido en una arquitectura modular basada en tres repositorios independientes:

---

# 📂 Repositorios del proyecto

## 🔧 Backend API

Repositorio encargado de toda la lógica de negocio, autenticación, seguridad y conexión con base de datos.

🔗 **Repositorio:**  
https://github.com/Brayanperdomoo/gym-back-end

### Funcionalidades principales

- API REST
- CRUD completo
- Validaciones
- Autenticación y autorización
- Manejo de roles
- Conexión a base de datos
- Arquitectura limpia

### Tecnologías

- PHP
- JWT/Auth
- API REST
- MySQL

---

## 🎨 Frontend

Interfaz gráfica del sistema desarrollada para brindar una experiencia moderna, intuitiva y responsive.

🔗 **Repositorio:**  
https://github.com/Brayanperdomoo/gym-front-end

### Funcionalidades principales

- Dashboard administrativo
- Login
- Gestión visual de usuarios
- Formularios dinámicos
- Responsive design
- Consumo de API

### Tecnologías

- Angular
- TypeScript
- Bootstrap
- HTML5
- CSS3

---

## 🗄️ Database

Repositorio encargado del modelado y estructura de la base de datos.

🔗 **Repositorio:**  
https://github.com/Brayanperdomoo/gym-database

### Contenido

- Scripts SQL
- Modelo relacional
- Tablas
- Relaciones
- Constraints
- Datos semilla

### Tecnologías

- MySQL
- SQL

---

# 🏗️ Arquitectura del proyecto

```bash
Gym Management System
│
├── Frontend (Angular)
│
├── Backend (PHP/API REST)
│
└── Database (MySQL)
```

Arquitectura basada en separación de responsabilidades:

- **Frontend:** experiencia de usuario
- **Backend:** lógica de negocio
- **Database:** persistencia de datos

---

# ⚙️ Instalación

## 1. Clonar repositorios

```bash
git clone https://github.com/Brayanperdomoo/gym-front-end.git
git clone https://github.com/Brayanperdomoo/gym-back-end.git
git clone https://github.com/Brayanperdomoo/gym-database.git
```

---

## 2. Base de datos

Importar script SQL desde:

```bash
gym-database/
```

Crear base de datos en MySQL.

---

## 3. Backend

Configurar variables de conexión a base de datos y ejecutar servidor.

Ejemplo:

```bash
php -S localhost:8000
```

---

## 4. Frontend

Instalar dependencias:

```bash
npm install
```

Ejecutar proyecto:

```bash
ng serve
```

Abrir:

```bash
http://localhost:4200
```

---

# 👨‍💻 Autor

## Brayan Perdomo

Desarrollador Full Stack en formación enfocado en:

- Backend
- Frontend
- Bases de datos
- Arquitectura de software

### GitHub

🔗 https://github.com/Brayanperdomoo

---

# 📈 Estado del proyecto

🟢 En desarrollo activo

Próximas mejoras:

- Notificaciones
- Reportes PDF
- Dashboard analytics
- Gestión avanzada de pagos
- Auditoría

---

# 📄 Licencia

Proyecto académico y de portafolio.

© 2026 Brayan Perdomo
