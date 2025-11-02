# 🛡️ Módulo de Autenticación de Usuarios | [Nombre de tu Proyecto]

## 1. Objetivo del Módulo

El propósito de este módulo es **implementar un sistema de autenticación** robusto y seguro que permita a los usuarios registrarse e iniciar sesión en la aplicación. Este sistema es crítico para garantizar que solo los usuarios verificados puedan acceder al panel de control y a las funcionalidades principales, manteniendo la integridad y privacidad de los datos del sistema.

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

## 3. Planificación y Seguimiento (GitHub Projects)

Utilizamos GitHub Projects para organizar, planificar y realizar el seguimiento de cada tarea, asegurando la trazabilidad del código a cada Historia de Usuario.

### Enlace al Tablero de GitHub Projects

| Tipo de Recurso | Enlace |
| :--- | :--- |
| **Tablero Kanban/Scrum** | [Ir al Project Board](https://github.com/users/juanda22-ty/projects/2) |

**Flujo de Trabajo:** El tablero sigue un flujo **Kanban** con las etapas: **Pendiente** $\rightarrow$ **En Desarrollo** $\rightarrow$ **Pruebas/Revisión** $\rightarrow$ **Terminado**.

---

## 4. Integrantes del Equipo y Roles

Este proyecto ha sido desarrollado por:

| Integrante | Responsabilidades Clave |
| :--- | :--- |
| **Juan David Rodriguez Vargas** | Gestión del tablero, organización de tareas, análisis de requisitos (HU-2.1) y remoción de impedimentos. |
| **Paula Valentina Rache Fonseca** | Revisión de código, implementación de la lógica de seguridad y endpoints de API (HU-1.1, HU-2.2). |
| **Juan Camilo Viviescas Triana** | Desarrollo de la interfaz de usuario, pruebas de aceptación y validación de calidad (HU-1.2, HU-3.1). |
| **Ivan Rene Figueroa** | Definición de la experiencia de usuario y diseño visual de la interfaz. Encargado de la documentación técnica y el `README`. |

---

## 5. Criterios de Planificación Adicionales

Para asegurar una planificación robusta, utilizamos los siguientes campos personalizados en nuestro Project Board:

* **Esfuerzo Estimado:** Se mide en **horas (h)**.
* **Tipo de Recurso Necesario:** Clasifica si la tarea requiere un recurso **Frontend**, **Backend**, **Analista**, **Diseñador** o **QA**.
* **Etiquetas de Prioridad:** Utilizamos las etiquetas `high`, `medium` y `low` para indicar la urgencia de cada tarea.
