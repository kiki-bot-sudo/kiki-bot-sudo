# Enrique Zavala Martínez

**Estudiante de Desarrollo de Software** · Backend, Cloud y Datos
📍 Mérida, Yucatán, México

---

## Sobre mí

Estudiante de Ingeniería en Desarrollo de Software y Negocios Digitales (Tecnológico de Software, Mérida). Me enfoco en **backend con Java/Spring Boot**, con bases sólidas en cloud (AWS Academy) y automatización de integración continua. Antes de esto competí como atleta de tenis de mesa de alto rendimiento representando a Yucatán a nivel nacional — de ahí viene la disciplina con la que encaro cada proyecto: entender bien el problema antes de escribir código, y no dejar nada a medias.

Me interesa el desarrollo de software que combine backend sólido, datos y automatización, con un ojo puesto en cómo la IA se integra a ese flujo.

---

## Stack técnico

| Área | Tecnologías |
|---|---|
| **Backend** | Java, Spring Boot, Spring Security, JWT, C#/.NET, APIs REST |
| **Datos** | PostgreSQL, SQL, MySQL |
| **DevOps / Cloud** | Docker, Git, GitHub Actions (CI), AWS, Amazon EC2, Linux |
| **Documentación y arquitectura** | OpenAPI/Swagger, DTOs, arquitectura por capas |
| **Idiomas** | Inglés B2 (intermedio-alto) |

---

## Proyectos destacados

### 🪙 Bitcoin Payment Gateway
`Java` `Spring Boot` `PostgreSQL` `Docker` `GitHub Actions`

Plataforma de órdenes de pago con Bitcoin, desarrollada en equipo de 3 personas: generación de facturas y monitoreo de transacciones sobre una red de prueba.

**Mi rol:**
- Desarrollé endpoints de API REST documentados con OpenAPI/Swagger, con manejo estandarizado de errores.
- Escribí pruebas automatizadas y configuré el flujo de CI en GitHub Actions, para que ningún cambio llegara a `main` sin pasar validación primero.
- Trabajé con Spring Security + Spring Data JPA sobre PostgreSQL para persistencia y control de acceso.
- El proyecto corre contenerizado con Docker, lo que facilita levantar el entorno completo (app + base de datos) de forma reproducible sin depender de configuración manual en cada máquina.

**Por qué así:** en un sistema que maneja transacciones, la prioridad es que los cambios no rompan nada silenciosamente — de ahí el CI con pruebas automatizadas antes del merge, y el uso de DTOs para no exponer las entidades de base de datos directamente en la API.

🔗 [github.com/Marcelo-30/bitcoin-payment-gateway](https://github.com/Marcelo-30/bitcoin-payment-gateway)

---

### 👥 Plataforma de Red Social (Backend)
`Java` `Spring Boot` `Spring Security` `JWT` `PostgreSQL`

Backend de una red social diseñado desde cero, con foco en separar responsabilidades con claridad.

**Lo que construí:**
- Arquitectura por capas orientada al dominio (controller → service → repository), para mantener separadas la lógica de negocio, la persistencia y la transferencia de datos.
- Autenticación con JWT sobre Spring Security, para manejar sesiones sin estado.
- Persistencia con JPA sobre PostgreSQL, usando DTOs para desacoplar lo que la API expone de cómo están modeladas las tablas internamente.

**Por qué así:** separar por capas hace que el proyecto se pueda extender (agregar nuevos endpoints o cambiar la base de datos) sin reescribir la lógica de negocio. Es la misma disciplina de "hacer las cosas bien desde el diseño" que aplico en cualquier proyecto, aunque sea uno personal.

🔗 [github.com/kiki-bot-sudo/socialnetwork-EnriqueZavala-3b](https://github.com/kiki-bot-sudo/socialnetwork-EnriqueZavala-3b)

---

### 📋 TaskFlow
`C#` `ASP.NET Core` `Entity Framework Core` `PostgreSQL`

Aplicación de gestión de tareas para estudiantes, con interfaz web (MVC) y API REST sobre la misma capa de servicios.

**Lo que construí:**
- Arquitectura en capas (Domain → Application → Infrastructure → API), documentada formalmente con **ADRs (Architecture Decision Records)**: contexto, decisión, alternativas consideradas y por qué se descartaron.
- API REST con endpoints CRUD para tareas, DTOs propios y mapeo con AutoMapper, documentada con Swagger.
- Persistencia con Entity Framework Core sobre PostgreSQL.
- Las 4 vistas del modelo arquitectónico 4+1 (lógica, procesos, despliegue, física), documentadas con diagramas Mermaid.

**Por qué así:** documentar las decisiones de arquitectura (no solo el código) es lo que le permite a cualquiera —incluido yo mismo meses después— entender por qué el proyecto está estructurado así y no de otra forma. Fue justo lo que permitió agregar la capa de API REST después sin tocar el dominio ni la lógica de negocio ya existente.

🔗 [github.com/kiki-bot-sudo/Arq-Soft-TaskFlow-Enrique](https://github.com/kiki-bot-sudo/Arq-Soft-TaskFlow-Enrique)

---

## Educación

**Ingeniería en Desarrollo de Software y Negocios Digitales** — Tecnológico de Software, Mérida, Yucatán *(2025 – 2029)*

**Bachillerato** — Centro de Alto Rendimiento Deportivo (CARD)
Estudiante-atleta de tenis de mesa de alto rendimiento; representé a Yucatán en competencias de nivel nacional.

---

## Certificaciones

- **AWS Academy** — Cloud Foundations (jun. 2026) · Cloud Operations (jul. 2026)
- **Cisco Networking Academy** — Linux Essentials (jun. 2026) · Python Essentials 1 (may. 2026) · Python Essentials 2 (jun. 2026)
- **DataCamp** — SQL Fundamentals (jul. 2026)

---

## Contacto

📧 [Enrique.zavala@tecdesoftware.edu.mx](mailto:Enrique.zavala@tecdesoftware.edu.mx)
💼 [linkedin.com/in/enrique-zavala-martinez-4662943a6](https://linkedin.com/in/enrique-zavala-martinez-4662943a6)
