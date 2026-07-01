# ¡Hola! Soy Mirtha Gómez 👋

### Desarrolladora Full Stack & Infraestructura DevOps | +12 años de Trayectoria Profesional
Aporto al sector tecnológico una combinación de valor diferenciadora: la lógica analítica para diseñar arquitecturas de software limpias y desacopladas junto con una sólida madurez profesional en la gestión de entornos críticos, monitorización de alertas y resolución de incidencias en tiempo real bajo entornos de alta presión.

- 🌍 Ubicada en Parla, Madrid.
- 💻 Foco técnico: Rendimiento backend, contenedorización de servicios y optimización de bases de datos relacionales y NoSQL.
- ✉️ Contacto directo: **msgomezguadalupe@gmail.com**

---

## 🛠️ Stack Técnico Primario

### Backend & Arquitectura
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)

### Infraestructura, DevOps & Datos
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![WSL](https://img.shields.io/badge/WSL-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logicColor=white)

---

## 🚀 Proyectos Destacados

### 📁 [Optima SaaS - Gestión Integral Multi-Inquilino](https://github.com/mirsugogu/optima-saas)
*Software como Servicio (SaaS) multi-tenant con arquitectura desacoplada diseñado para la automatización de agendas, control de jornadas, turnos, ausencias y gestión de recursos en negocios del sector servicios.*
- **Backend:** Desarrollado con Java 21 y Spring Boot 3.4 (Spring Security, JPA/Hibernate, Validation). Expone una API REST con 17 grupos de endpoints estructurados e inmutabilidad gestionada mediante Records de Java.
- **Seguridad Avanzada:** Autenticación por tokens JWT en dos fases (Identity Token y Tenant Token)[cite: 5]. Implementación de un filtro lógico de aislamiento absoluto entre negocios (*Tenant Guard Filter*) y mitigación anti-fuerza bruta mediante *Rate Limiting* por IP con la librería Bucket4j 8.10[cite: 5].
- **Frontend:** Single Page Application (SPA) responsiva con React 19 y Vite 8. Incorpora atajos de teclado globales, geometría calculada en JavaScript para eventos en cuadrícula y asistente de creación de citas en 3 pasos con cálculo de disponibilidad cruzada en tiempo real[cite: 5].
- **Calidad de Software:** Validado mediante una rigurosa suite de pruebas en Postman con más de 180 escenarios de control de accesos y lógica empresarial[cite: 5].
- **Documentación:** [📄 Consultar Memoria de Proyecto (PDF)](https://github.com/mirsugogu/optima-saas/blob/main/docs/MEMORIA_TFG_OPTIMA.pdf) | Interfaz interactiva desplegada con Swagger UI[cite: 5].

### 📁 [Gestión Académica Multi-Database Backend](https://github.com/mirsugogu/gestion-academica-backend)
*API REST de alta disponibilidad para la administración de matrículas, alumnos y evaluaciones, diseñada bajo principios de arquitectura limpia y desacoplamiento de datos.*
- **Patrones de Diseño:** Implementación del patrón *Factory Pattern* en Python (FastAPI) para gestionar el aislamiento de persistencia dinámica[cite: 3].
- **Persistencia Flexible:** Integración e interoperabilidad simultánea con tres motores de bases de datos independientes: MySQL, SQLite y MongoDB (NoSQL)[cite: 3].
- **DevOps:** Entorno dockerizado con Dockerfile estructurado y scripts automatizados para la inicialización de esquemas locales e inyecciones de datos de prueba (*seed*)[cite: 3].
- [🔗 Acceder al Repositorio](https://github.com/mirsugogu/gestion-academica-backend)

### 📁 [Somama Web - Plataforma para Ludoteca SoMama](https://github.com/mirsugogu/somama-web)
*Desarrollo y reingeniería de la plataforma web corporativa para la ludoteca SoMama, mejorando el sistema informativo previo y desplegando un entorno de gestión interna privado.*
- **Optimización Frontend:** Rediseño completo de la interfaz pública preexistente, mejorando la arquitectura de la información, la estética visual y la experiencia de usuario (UX).
- **Backend Empresarial:** Desarrollo en Java y Spring Boot de una intranet segura con dos niveles de acceso diferenciados mediante autenticación de usuario y contraseña:
  - **Módulo de Familias:** Espacio privado para la gestión y centralización de fichas personales de alumnos, actividades asociadas y control estricto de datos sensibles de salud (alergias y observaciones médicas críticas).
  - **Panel de Administración (CMS):** Panel autogestionable para la propietaria del centro, permitiendo la edición dinámica de contenidos de la web, actualización del catálogo de talleres en tiempo real y consulta de listados de alumnos.
- **Datos & Despliegue:** Base de datos relacional MySQL parametrizada para el histórico del centro y orquestación unificada mediante Docker Compose.
- *🔒 Estado: Repositorio privado en fase de optimización final (Acceso público próximamente).*

---

## 📊 Competencias Profesionales (Soft Skills)

A lo largo de mi trayectoria de más de 12 años en entornos corporativos previos a mi especialización tecnológica, he consolidado aptitudes analíticas esenciales para equipos de ingeniería y operaciones:
*   **Gestión de Contingencias:** Capacidad resolutiva y templanza para mitigar incidencias técnicas críticas bajo exigentes acuerdos de nivel de servicio (SLAs) y KPIs de negocio.
*   **Comunicación Interdepartamental:** Capacidad para actuar como nexo conector fluido entre las necesidades estratégicas de negocio (Data/Management) y los requerimientos del equipo técnico de desarrollo.
*   **Enfoque de Automatización:** Orientación nativa hacia la observabilidad, mantenibilidad y la eficiencia de procesos. Reducción de tareas operativas manuales mediante scripting y despliegues controlados.

---

## 🌐 Canales de Contacto

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/msgomezguadalupe/)
[![Mi CV Online](https://img.shields.io/badge/Mi%20CV%20Online-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://mirsugogu.github.io/cv-MirthaGomez/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:msgomezguadalupe@gmail.com)
