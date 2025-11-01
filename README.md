# 🛡️ Módulo de Autenticación de Usuarios

## 1. Objetivo del Módulo

El propósito de este módulo es **implementar un sistema de autenticación** robusto y seguro que permita a los usuarios registrarse e iniciar sesión en la aplicación. Este sistema es crítico para garantizar que solo los usuarios verificados puedan acceder al panel de control y a las funcionalidades principales, manteniendo la integridad y privacidad de los datos.

---

## 2. Historias de Usuario (HU)

La siguiente lista define los requisitos de alto nivel del usuario que guían el desarrollo de este módulo:

### HU-1: Login de Usuarios

> **Como** usuario registrado **quiero** iniciar sesión con mi correo y contraseña **para** acceder al panel de control de la aplicación.

### HU-2: Registro de Nuevos Usuarios

> **Como** nuevo usuario **quiero** registrarme con mi nombre, correo y contraseña **para** poder acceder a las funcionalidades completas de la aplicación.

### HU-3: Visualización de un Dashboard

> **Como** usuario autenticado **quiero** ver un dashboard principal al iniciar sesión **para** tener un resumen de mi información y funcionalidades clave.

---

## 3. Planificación y Seguimiento

Utilizamos GitHub Projects para organizar, planificar y realizar el seguimiento de cada tarea, asegurando la trazabilidad del código a cada Historia de Usuario.

### Enlace al Tablero de GitHub Projects

| Tipo de Recurso | Enlace |
| :--- | :--- |
| **Tablero Kanban/Scrum** | [Ir al Project Board]([https://github.com/users/juanda22-ty/projects/2]) |

**Flujo de Trabajo:** El tablero sigue un flujo **Kanban** con las etapas: **Pendiente** **En Desarrollo** **Pruebas/Revisión**  **Terminado**.

---

## 4. Integrantes del Equipo y Roles

Este proyecto ha sido desarrollado por:

**Juan David Rodriguez Vargas**  | **Scrum Master / Analista** | Gestión del tablero, eliminación de impedimentos, definición de esquemas (HU-2.1). |
**Paula Valentina Rache Fonseca** | **Líder Técnico / Desarrollador Backend** | Revisión de código, implementación de la lógica de seguridad y endpoints (HU-1.1, HU-2.2). |
**Juan Camilo Viviescas Triana** | **Desarrollador Frontend** | Implementación de componentes de interfaz de usuario (Login/Registro) y vistas (HU-1.2, HU-3.1). |

---

## 5. Criterios de Planificación Adicionales

Para asegurar una planificación robusta, utilizamos los siguientes campos personalizados en nuestro Project Board:

* **Esfuerzo Estimado:** Se mide en **horas (h)**.
* **Tipo de Recurso Necesario:** Clasifica si la tarea requiere un recurso **Frontend**, **Backend**, o **Analista**.
* **Etiquetas de Prioridad:** Utilizamos las etiquetas `high`, `medium` y `low`.
