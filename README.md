# Portafolio - Karina Guevara

Sitio web personal tipo portafolio, desarrollado como proyecto del bootcamp de **TripleTen**. Presenta información profesional, habilidades técnicas y proyectos destacados con un diseño oscuro, moderno y totalmente responsive.

## 🔗 Demo

- **Demo en vivo:** https://kgue27ara.github.io/web_project_portfolio_es/
- **Repositorio:** https://github.com/kgue27ara/web_project_portfolio_es

## 🖼️ Vista previa

_[Puedes agregar aquí una captura de pantalla del sitio, por ejemplo:]_

```markdown
![Vista previa del portafolio](./images/preview.png)
```

## 📋 Descripción

El sitio está organizado en cuatro secciones principales:

- **Header:** presentación personal, foto de perfil y navegación (descarga de CV, enlace a GitHub, contacto).
- **Habilidades y herramientas:** logos de las tecnologías utilizadas (HTML5, CSS3, JavaScript, Git, GitHub, ChatGPT).
- **Proyectos destacados:** tarjetas (cards) con imagen, overlay de tecnologías, descripción y enlaces a demo/GitHub de cada proyecto.
- **Footer / Contacto:** información de contacto y enlaces a redes sociales.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura semántica del sitio.
- **CSS3** — estilos, maquetación y efectos visuales:
  - **Flexbox** para la organización de layouts (header, nav, cards, footer).
  - **Media Queries** para diseño responsive (tablet: `max-width: 1023px`, móvil: `max-width: 767px`).
  - **`position: relative` / `position: absolute`** para overlays de imágenes y elementos decorativos.
  - **`linear-gradient`** para subrayados con degradado en los links de navegación y overlays de las cards.
  - **`radial-gradient`** y `filter: blur()` para los destellos de luz (glows) decorativos del header y footer.
  - **`order`** para reordenar visualmente elementos (como la imagen del header) en distintos breakpoints sin alterar el HTML.
- **Git & GitHub** — control de versiones y flujo de trabajo colaborativo.
- **Figma** — referencia de diseño.

## 📱 Diseño responsive

El sitio se adapta a tres tamaños de pantalla:

| Dispositivo | Breakpoint |
|---|---|
| Escritorio | > 1023px (estilos estándar) |
| Tablet | ≤ 1023px |
| Móvil | ≤ 767px |

## 📂 Estructura del proyecto

```
proyecto/
├── index.html
├── styles/
│   ├── index.css
├── fonts/
│   ├── Archivo Black. woff
│   ├── Archivo Black. woff2
│   ├── Archivo Open Sans italic. woff
│   ├── Archivo Open Sans italic. woff2
│   ├── Archivo Open Sans Regular. woff
│   ├── Archivo Open Sans Regular. woff2
├── images/
│   ├── perfil_karina.jpg
│   ├── proyectos/
│   ├── iconos/
│   └── iconos/logos_overlay/
├── downloads/
│   ├── 2026_cv_karina.pdf
├── favicon
├── editorconfig
├── prettierignore
├── gitignore
└── README.md
```

## 🚀 Cómo verlo localmente

1. Clona este repositorio:
   ```bash
   git clone <https://github.com/kgue27ara/web_project_portfolio_es>
   ```
2. Abre la carpeta del proyecto en VS Code.
3. Usa la extensión **Live Server** (o similar) y abre `index.html`.

## ✅ Estado del proyecto

En desarrollo — ajustes de diseño responsive y detalles visuales en progreso.

## 👩‍💻 Autora

**Karina Guevara**
Desarrolladora Full-Stack Junior | HTML, CSS, JavaScript, React, Node.js
Proyecto formativo — TripleTen Bootcamp
