# 🌿 Mint CRM - Talent Recruitment Tracker

**Mint CRM** es una herramienta ligera de gestión de candidatos (ATS/CRM) diseñada para optimizar el flujo de trabajo de selección de talento. Con una interfaz inspirada en herramientas SaaS modernas, permite gestionar múltiples procesos de selección de forma simultánea con un control visual total.

## ✨ Características Principales

* **Gestión Multi-proceso:** Crea y alterna entre diferentes vacantes o procesos de selección con un solo clic.
* **Tablero Kanban Interactivo:** Sistema de *Drag & Drop* fluido para mover candidatos entre etapas (Invitado, Aceptado, Llamada, Entrevista, Manager).
* **Visualización de Datos Directa:** Acceso inmediato a información crítica (Email, Teléfono, LinkedIn y Expectativa Salarial) sin clics adicionales.
* **Zero Backend:** Funciona completamente en el lado del cliente utilizando `LocalStorage`. No requiere base de datos externa ni configuración de servidor.
* **Diseño Mint Pro:** Interfaz limpia, optimizada para largas jornadas de trabajo con una paleta de colores relajante (Verde Menta y Crema).

## 🚀 Instalación y Uso

No requiere instalación. 

1. Clona este repositorio o descarga el archivo `index.html`.
2. Ábrelo en cualquier navegador moderno.
3. ¡Empieza a trackear tus candidatos!

## 🛠️ Tecnologías utilizadas

* **HTML5** (Semántico)
* **CSS3** (Variables personalizadas, Flexbox, Grid y Animaciones)
* **JavaScript ES6+** (Manipulación del DOM, Drag & Drop API y LocalStorage)

## 📂 Estructura de Datos
La herramienta guarda la información de forma local en el navegador bajo las claves:
- `li_crm_mint_proc`: Almacena la lista de procesos creados.
- `li_crm_mint_cand`: Almacena la base de datos de candidatos vinculados a sus procesos.
