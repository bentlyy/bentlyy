# ¡Hola! 👋 Soy Alejandro Muñoz Garay

### Ingeniero Civil en Informática · Full Stack Developer | DevOps | Machine Learning

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=Full+Stack+Developer;TypeScript+%7C+Node.js+%7C+React;DevOps+%26+Automation;Docker+%7C+CI%2FCD;Machine+Learning+%7C+Python;Siempre+aprendiendo+cosas+nuevas" alt="Typing SVG" />

## 🌐 Portafolio Web — [amgdeveloper.cl](https://amgdeveloper.cl) | [Descargar CV](https://amgdeveloper.cl/cv.pdf)

---

## 🧑‍💻 Sobre mí

Ingeniero Civil en Informática de la **Universidad Adventista de Chile (2024)**. Me enfoco en construir sistemas completos, desde el backend hasta el despliegue, priorizando código claro y bien estructurado. He desarrollado sistemas **SaaS multi-tenant**, plataformas **IoT**, APIs containerizadas y herramientas **CLI**.

En cada proyecto la optimización de operaciones, rendimiento y escalabilidad es parte intrínseca del desarrollo: seguridad multicapa (autenticación, cifrado, control de acceso), manejo estructurado de logs y errores, y pipelines de CI/CD que garantizan despliegues confiables y autónomos. Desarrollo, infraestructura e inteligencia artificial convergen en software eficiente, seguro y autosuficiente.

- 🔭 Actualmente desarrollando [**Vitaria**](https://github.com/bentlyy/Clinica-Salud-Vital), un sistema de gestión clínica SaaS con más de 1100 tests automatizados
- 🌱 Aprendiendo constantemente sobre IA y Deep Learning
- 📍 San Pablo, Santiago, Chile
- 📫 Contáctame: [munozgarayalejandro@gmail.com](mailto:munozgarayalejandro@gmail.com)

---

### Tecnologías con las que trabajo

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📂 Proyectos Destacados

### 🏥 Sistema de Gestión Clínica SaaS — *Vitaria*

[![Sitio](https://img.shields.io/badge/Sitio-Render-46E3B7?style=flat-square&logo=render&logoColor=white)](https://clinica-salud-vital.onrender.com)
[![GitHub](https://img.shields.io/badge/Código-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bentlyy/Clinica-Salud-Vital)

Sistema SaaS de gestión clínica con **16 módulos**: agenda médica, historias clínicas electrónicas, facturación, laboratorio, analítica y panel de administración. Construido con **Node.js + Express 5 + TypeScript**, frontend en **React 19**, y base de datos **PostgreSQL 15**. Incluye más de **1100 tests automatizados (~89% cobertura)** con Vitest + Supertest, autenticación **JWT + TOTP 2FA**, RBAC granular, auditoría HMAC-SHA256, multi-tenancy con aislamiento de datos por cliente, i18n en 4 idiomas, notificaciones email/SMS/WhatsApp y despliegue con Docker.

---

### 🌱 Sistema de Monitoreo Agrícola — *AgroBot-Alert*

[![Sitio](https://img.shields.io/badge/Sitio-Cloudflare-000000?style=flat-square&logo=cloudflare&logoColor=white)](https://agrobot.amgdeveloper.cl)
[![GitHub](https://img.shields.io/badge/Código-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bentlyy/agrobot-alert)

Plataforma IoT de monitoreo en tiempo real para sensores agrícolas conectados a **Wialon**. Backend en **Node.js + Express + MySQL 8** con motor de alertas que evalúa condiciones (temperatura, humedad, batería) y notifica automáticamente vía **Email (Nodemailer) + WhatsApp (Twilio)** con prevención de duplicados. Frontend en **React 18** con mapas interactivos (Leaflet/OpenStreetMap) y gráficos en tiempo real (Recharts). Roles admin/usuario con JWT y rate limiting, modo de simulación para desarrollo sin hardware real, y completamente dockerizado.

---

### 🔧 Sistema de Gestión de Taller Mecánico SaaS — *TallerPro*

[![Sitio](https://img.shields.io/badge/Sitio-Render-46E3B7?style=flat-square&logo=render&logoColor=white)](https://taller.amgdeveloper.cl)
[![GitHub](https://img.shields.io/badge/Código-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bentlyy/TallerMecanico)

Sistema **SaaS multi-tenencia** para administración de múltiples talleres mecánicos. Backend en **Node.js + Express 5 + TypeScript + Prisma (PostgreSQL 15)** con **arquitectura hexagonal** (dominio/aplicación/infraestructura). Módulos de clientes, vehículos, órdenes de reparación con flujo de estados, inventario con descuento automático y facturación. Seguridad con JWT + RBAC (3 roles), bloqueo por 5 intentos fallidos y rate limiting. Monitoreo con **Prometheus + Grafana** + Pino logging, y CI/CD con GitHub Actions. Totalmente dockerizado.

---

### 🚚 Transport Management System — *Transporte*

[![Sitio](https://img.shields.io/badge/Sitio-Render-46E3B7?style=flat-square&logo=render&logoColor=white)](https://transporte.amgdeveloper.cl)
[![GitHub](https://img.shields.io/badge/Código-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bentlyy/Transallendes)

TMS en tiempo real para flota de carga internacional: gestión de clientes, conductores, camiones y viajes con **tracking GPS en vivo** (Leaflet) y alertas por geocercas. Base de datos **PostgreSQL + PostGIS** y motor de simulación de rutas (encendido, combustible, velocidad). Frontend en **React 19 + Vite** con WebSocket para datos en vivo. Autenticación JWT + refresh y roles RBAC (superadmin/admin/driver). Dockerizado.

---

### ⚡ Generador de APIs TypeScript — *TypeForge*

[![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/typeforge)
[![GitHub](https://img.shields.io/badge/Código-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bentlyy/typeforge)

CLI publicado en **npm** que genera APIs TypeScript listas para producción en segundos. Interactivo con **Commander + Inquirer** y templates personalizables con **Handlebars**. Incluye Express, Prisma, autenticación JWT opcional, Docker multi-stage y CI/CD listos para usar.

---

## 💼 Experiencia

### Desarrollador Full Stack — Proyectos Autónomos · *2024 - Presente*
Desarrollé sistemas completos aplicando buenas prácticas de arquitectura, testing, DevOps y seguridad, incluyendo Vitaria (SaaS clínico con 16 módulos y 1122 tests), TallerPro (CI/CD en 5 etapas) y TypeForge (CLI en npm).

### Desarrollador Full-Stack — Plataforma IoT · *Geotrace (Proyecto INIA) · Jun 2024 - Nov 2024*
Trabajo de título. Construí una plataforma IoT con monitoreo en tiempo real para sensores agrícolas. Alertas automáticas por WhatsApp y Email que redujeron el tiempo de respuesta en un **20-25%**. Plataforma containerizada con Docker, integrando APIs de Wialon y OpenAI.

### Práctica en Ingeniería de Software — Infraestructura · *Dpto. de Informática, Univ. Adventista de Chile · Jul 2020 - Oct 2020*
Automaticé el aprovisionamiento de servidores con **Ansible** y pipelines CI/CD. Administré servidores Linux con hardening de seguridad y creé runbooks para estandarizar la respuesta ante incidentes.

---

## 🛠️ Stack por categoría

| Categoría | Tecnologías |
|---|---|
| **Lenguajes** | TypeScript, JavaScript, Python, SQL |
| **Backend** | Node.js, Express, REST API, JWT |
| **Frontend** | React, Next.js, Tailwind CSS, MUI |
| **DevOps** | Docker, GitHub Actions, Nginx, Linux, Oracle Cloud |
| **Bases de Datos** | PostgreSQL (+ PostGIS), MySQL, Prisma ORM |
| **Testing** | Jest, Vitest, Supertest |
| **Seguridad** | JWT + Refresh Tokens, TOTP 2FA, RBAC, Helmet/CORS, Auditoría |
| **Monitoreo** | Prometheus, Grafana |

---

## 📫 Conecta conmigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-mu%C3%B1oz-garay-668324347)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bentlyy)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:munozgarayalejandro@gmail.com)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=bentlyy&color=blue&style=flat-square&label=Visitas" alt="Visitas"/>
</p>
