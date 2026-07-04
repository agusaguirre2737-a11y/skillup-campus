# SkillUp Campus 🚀

SkillUp Campus es una plataforma web (EdTech) diseñada para centralizar, automatizar y escalar la gestión de cursos, inscripciones y usuarios de una startup educativa en crecimiento, reemplazando los procesos manuales basados en planillas y formularios dispersos.

---

## 🛠️ Stack Tecnológico

El proyecto está construido bajo una arquitectura de **Monorepo**, dividiendo claramente las responsabilidades del cliente y del servidor.

* **Backend:** Node.js, Express.js y [PostgreSQL / MongoDB Atlas]
* **Frontend:** [HTML/CSS/JS Vanilla / React]
* **Control de Versiones & Gestión:** Git, GitHub y GitHub Projects / Trello (Kanban)
* **Pruebas de API:** Postman

---

## 📌 Alcance del MVP (Fase 1)

El producto mínimo viable se centra en resolver la desorganización operativa a través de las siguientes características:

### Funcionalidades Incluidas ✅
* **Autenticación:** Registro e inicio de sesión de usuarios con roles diferenciados.
* **Catálogo Público:** Vista abierta de la oferta académica disponible.
* **Inscripciones:** Flujo para que los estudiantes se anoten a los cursos.
* **Panel de Usuario:** Espacio privado para que el alumno visualice sus cursos activos.
* **Panel de Administrador:** Módulo de control total (CRUD) sobre el catálogo de cursos y gestión básica de usuarios.

### Fuera del Alcance (Futuras Versiones) ❌
* Pasarela de pagos, aplicación móvil, streaming de video, chat/foros internos, certificados automáticos y notificaciones por correo electrónico.

---

## 📁 Estructura del Proyecto

```text
skillup-campus/
├── backend/          # API REST (Lógica de negocio y persistencia)
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   └── config/
│   └── package.json
├── frontend/         # Interfaz de usuario (SPA / Vistas estáticas)
│   ├── src/
│   └── index.html
├── docs/             # Documentación, diagramas y colecciones de Postman
└── README.md         # Documentación principal del repositorio