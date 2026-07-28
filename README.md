# Portfolio Profesional - Karen Barboza (Diseñadora Gráfica)

Este es el repositorio del sitio web del portfolio profesional de **Karen Barboza**, Diseñadora Gráfica. El sitio está diseñado con una estética moderna, minimalista y de alto contraste, ideal para resaltar proyectos visuales y de diseño creativo.

## 🚀 Características principales

- **Diseño Premium y Minimalista:** Interfaz de usuario limpia, en modo oscuro por defecto, utilizando la tipografía *Inter* y una paleta de colores curada y armoniosa.
- **Visualización Interactiva (SPA/Detalles):** Permite explorar la cuadrícula de trabajos y ver los detalles de cada proyecto de forma dinámica y fluida utilizando JavaScript.
- **Efectos y Microanimaciones:** Animación de carga y aparición suave al hacer scroll (*Intersection Observer*) en la grilla de proyectos.
- **Páginas de Soporte:** Incluye secciones dedicadas sobre la profesional (`about.html`) y métodos de contacto (`contact.html`).
- **Completamente Responsivo:** Adaptado para una experiencia perfecta en dispositivos móviles, tablets y ordenadores de escritorio usando Tailwind CSS.

## 📂 Estructura del Proyecto

El proyecto está construido con tecnologías web estándar (HTML, CSS, JavaScript) y Tailwind CSS:

*   [`index.html`](file:///home/ana/Github/porfolio-ka/index.html): Página de inicio que aloja la grilla principal de trabajos y la vista detallada de proyectos mediante SPA.
*   [`about.html`](file:///home/ana/Github/porfolio-ka/about.html): Sección sobre Karen Barboza, su trayectoria y enfoque de diseño.
*   [`contact.html`](file:///home/ana/Github/porfolio-ka/contact.html): Página para ponerse en contacto con enlaces y formulario.
*   [`project.html`](file:///home/ana/Github/porfolio-ka/project.html): Vista de detalle de un proyecto en particular.
*   [`main.js`](file:///home/ana/Github/porfolio-ka/main.js): Lógica de navegación dinámica, interactividad y control del estado activo de los menús.
*   [`style.css`](file:///home/ana/Github/porfolio-ka/style.css): Estilos CSS personalizados para complementar las utilidades de Tailwind.

## 🎨 Proyectos Destacados

El portfolio incluye una selección de trabajos en diversas disciplinas del diseño.

## 🛠️ Cómo Visualizar Localmente

Dado que es un sitio estático puro, no requiere compilación ni servidores complejos. Puedes ejecutarlo de las siguientes maneras:

### Opción 1: Abrir directamente
Simplemente haz doble clic en `index.html` para abrirlo en tu navegador favorito.

### Opción 2: Servidor local simple
Si deseas una experiencia de recarga en vivo o navegación local más realista, puedes utilizar un servidor local de desarrollo como:

*   **Live Server** (Extensión de VS Code).
*   Usando Python desde tu terminal:
    ```bash
    python3 -m http.server 8000
    ```
    Y luego abriendo `http://localhost:8000` en tu navegador.
