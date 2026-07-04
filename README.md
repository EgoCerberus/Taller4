# Taller4
# CyberTech - Tienda de Tecnología 🎮💻

¡Bienvenido al repositorio del **Taller 4**! Este proyecto consiste en el diseño y maquetación web de una interfaz para una tienda en línea especializada en componentes de hardware de alta gama, consolas y periféricos premium, desarrollada como parte del programa de formación en **Análisis y Desarrollo de Software**.

## 📌 Características del Proyecto

* **Diseño Responsivo:** Adaptado para una visualización óptima en dispositivos móviles, tablets y pantallas de escritorio utilizando el sistema de rejilla de **Bootstrap 5**.
* **Barra de Navegación Unificada:** Un menú de navegación fijo (`fixed-top`) con transiciones homogéneas de estilo oscuro (`btn-dark`) al pasar el cursor (*hover*) por cada una de sus opciones e iconos integrados.
* **Componente de Carrusel (Hero Section):** Un slider interactivo para destacar promociones de hardware, consolas y periféricos con imágenes de fondo optimizadas mediante CSS (`object-fit-cover`).
* **Sección de Categorías:** Organización modular en tarjetas (*cards*) para clasificar de forma atractiva los productos (PCs Ensambladas, Componentes y Accesorios).

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructuración semántica del sitio web y metadatos de optimización móvil.
* **Bootstrap v5.3:** Framework de CSS utilizado para agilizar los estilos, componentes interactivos (Carrusel, Dropdowns) y la adaptabilidad móvil.
* **Bootstrap Icons v1.11.3:** Librería de iconos vectoriales para enriquecer visualmente la interfaz de usuario.

## 📂 Estructura de Archivos

```text
├── app/                  # Páginas secundarias de la aplicación
│   ├── admin.html        # Panel de Administración
│   ├── cliente.html      # Panel de Cliente
│   ├── login.html        # Vista de Iniciar Sesión
│   ├── recuperar.html    # Vista de Recuperación de Contraseña
│   └── registro.html     # Formulario de Registro de Usuarios
├── assets/               # Recursos estáticos
│   ├── css/
│   │   └── bootstrap.min.css
│   ├── img/              # Imágenes y vectores de la tienda
│   └── js/
│       └── bootstrap.bundle.min.js
├── index.html            # Página de inicio del proyecto (Landing Page)
└── README.md             # Documentación del repositorio