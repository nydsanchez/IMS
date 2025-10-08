# 🗃️ Sistema de Gestión de Inventario (IMS)

> **Versión 1.0 — Frontend con JavaScript puro y Sass**  
> Proyecto personal de desarrollo fullstack en progreso.  
> Esta primera versión se centra en la estructura visual y lógica inicial del sistema, sin conexión a base de datos ni servidor.

---

## 🧠 **Descripción general**

El **Inventory Management System (IMS)** es una aplicación web diseñada para facilitar el control y gestión de inventarios.  
Este proyecto es parte de mi proceso de profesionalización como desarrolladora fullstack JavaScript, diseñado para fortalecer mi capacidad de construir sistemas completos de manera autónoma, desde la interfaz hasta la integración con backend y bases de datos.

Esta primera versión es un MVP básico, que marca el inicio del desarrollo del sistema y que se irá perfeccionando progresivamente hasta la versión completa y refinada.

---

## 🚀 **Demo en vivo**
🔗 [Ver sitio publicado en GitHub Pages](https://nydsanchez.github.io/IMS)

---

## 🧩 **Características actuales**

- 🎨 Interfaz base con **HTML5** y **Sass**
- 📱 Diseño adaptable y estructura modular de estilos
- 🧭 Navegación inicial entre secciones (enlaces aún sin funcionalidad)
- ⚙️ Configuración lista para integrar lógica en memoria (arrays y objetos en JS)
- 🔧 Scripts configurados para compilación automática de Sass

---

## 🛠️ **Tecnologías utilizadas**

| Área | Tecnologías |
|------|--------------|
| Estructura | HTML5 |
| Estilos | Sass (CSS preprocessor) |
| Lógica | JavaScript (ES6) |
| Control de versiones | Git + GitHub |
| Despliegue | GitHub Pages |

---

## 📁 **Estructura del proyecto**
```text
IMS/
├── index.html
├── css/
│ └── main.css # Generado por Sass
├── scss/
│ ├── abstract/
│ │ └── _variables.scss # Variables globales 
│ ├── base/
│ │ ├── _base.scss # Estilos base del sitio
│ │ ├── _typography.scss # Tipografía
│ │ └── _utilities.scss # Clases utilitarias
│ ├── components/
│ │ └── _menu.scss # Estilos del menú de navegación
│ ├── layout/
│ │ └── _layout.scss # Layout general
│ └── main.scss # Archivo principal que importa todos los parciales
│
├── js/
│ └──  # Contendrá la lógica principal de la versión 1
├── img/
│ └── ... # Imágenes del sitio
└── README.md
```
---

## ⚙️ **Configuración Sass**

Para compilar los archivos Sass a CSS automáticamente:

```bash
npm install
npm run sass
```

📘 El comando npm run sass utiliza el script configurado en el package.json:
```
"scripts": {
  "sass": "sass --watch scss:css"
}
```
---
## 🎯 **Próximos pasos de desarrollo**

### 🔹 Etapa 2 – Lógica en memoria (Frontend adaptativo)

- Implementar CRUD de productos (crear, listar, editar y eliminar)
- Guardar datos temporalmente en localStorage
- Diseñar la interfaz responsive para móviles, tablets y escritorio usando Flexbox/Grid y media queries en Sass

### 🔹 Etapa 3 – Backend con Node.js + PostgreSQL

- Crear servidor con Express
- Conectar con base de datos
- Exponer API RESTful

### 🔹 Etapa 4 – Migración del frontend a React

- Reescribir la interfaz como aplicación SPA
- Integrar el backend y autenticación de usuarios
