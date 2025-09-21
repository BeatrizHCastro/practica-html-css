# Práctica HTML y CSS

Portfolio ficticio de **Satoru Gojo (Jujutsu Kaisen)**, desarrollado como práctica de **HTML5 y CSS3**.

## Objetivo de la práctica

Construir un **portfolio responsive** sin JavaScript ni frameworks externos, aplicando:
- HTML5 semántico
- CSS3 modular con variables, flexbox, grid y media queries
- Animaciones y transiciones CSS
- Validaciones nativas en formularios

## Funcionalidades implementadas

- **Header + Navbar**
  - Logo y navegación horizontal
  - Links con estado `hover` y transición
  - Enlaces ocultos en móvil y visibles en desktop (mobile first)

- **Intro + Skills**
  - Sección de introducción con texto descriptivo
  - Skills representadas como barras de progreso animadas con `@keyframes`

- **Banner**
  - Imagen de fondo distinta en móvil y escritorio (media queries)
  - Dos variantes: solo texto, o texto acompañado de un botón de llamada a la acción (CTA)

- **Formulario de contacto**
  - Inputs con validación nativa (`required`, `pattern`, `type`)
  - Campos: Nombre, Apellidos, Teléfono, Radios, Tag de GitHub (regexp), Textarea, Checkbox newsletter
  - Botones: Guardar (submit) y Reset
  - Diseño accesible y responsive

- **Proyectos**
  - Página independiente con **grid CSS** para mostrar pósters de la serie
  - Vídeo con reproducción automática, animación de fade-in y con dos formatos (`.mp4` y `.webm`) para asegurar reproducción en distintos navegadores  

- **Footer**
  - Enlaces externos a redes sociales (Instagram, Twitch) con iconos SVG

- **Accesibilidad**
  - Uso de etiquetas `<nav>` en header y footer para navegación semántica  
  - Enlace "Saltar al contenido" oculto visualmente con la clase `sr-only`, pero accesible para lectores de pantalla
  - Contraste asegurado mediante variables de color

## Estructura del proyecto

```
.
├── index.html        # Home con presentación, skills y banner
├── projects.html     # Página de proyectos (vídeo + grid)
├── signin.html       # Página de contacto con formulario validado
├── styles/
│   ├── common.css
│   ├── components.css
│   ├── header.css
│   ├── footer.css
│   ├── banner.css
│   ├── intro.css
│   ├── skills.css
│   ├── projects.css
│   ├── info.css
│   └── signin.css
└── assets/           # Imágenes, vídeos y SVGs
```

## Cómo usar

1. Clona este repositorio:

   ```bash
   git clone https://github.com/BeatrizHCastro/practica-html-css.git
   cd practica-html-css
   ```

2. Abre `index.html` en tu navegador.
3. Navega entre páginas (`index.html`, `projects.html`, `signin.html`).

## Capturas

<!-- ![Home](ENLACE PANTALLAZO) -->

<!-- ![Projects](ENLACE PANTALLAZO) -->

<!-- ![Signin](ENLACE PANTALLAZO) -->

## Requisitos

* Google Chrome, Mozilla Firefox o Microsoft Edge (última versión)
* No requiere instalación ni dependencias externas

## Criterios cumplidos

* [x] Header + Navbar con hover y transición
* [x] Intro con descripción y skills animadas
* [x] Banner con imágenes responsive
* [x] Formulario completo con validación HTML
* [x] Footer con enlaces externos
* [x] Página con vídeo autoplay + fade-in
* [x] Página con grid responsive
* [x] Mobile first + media queries
* [x] README completo

## Créditos

* Desarrollo: [@BeatrizHCastro](https://github.com/BeatrizHCastro)
* Enunciado y tutoría: [@kevinccbsg](https://github.com/kevinccbsg) (Bootcamp Full Stack Web – KeepCoding)
* Inspirado en el personaje Satoru Gojo de *Jujutsu Kaisen*
* Recursos visuales:
  - Capturas y pósters promocionales de la serie y película
  - Vídeo trailer segunda temporada *Jujutsu Kaisen: Hidden Inventory / Premature Death*
  - Logo creado con herramientas de IA
  - Imágenes del banner obtenidas de:  
    - [WallpaperCave](https://wallpapercave.com/w/wp8674359)  
    - [Pinterest](https://es.pinterest.com/pin/742460688566282547/)  
  - Imagen de fondo del formulario obtenida de [Pinterest](https://mx.pinterest.com/pin/859554278878253832/)  


## Licencia

MIT © 2025 BeatrizHCastro


---


# HTML & CSS Practice

Fictional portfolio of **Satoru Gojo (Jujutsu Kaisen)**, developed as an **HTML5 and CSS3** practice.

## Practice Goal

Build a **responsive portfolio** without JavaScript or external frameworks, applying:

* Semantic HTML5
* Modular CSS3 with variables, flexbox, grid, and media queries
* CSS animations and transitions
* Native form validations

## Implemented Features

* **Header + Navbar**

  * Logo and horizontal navigation
  * Links with `hover` state and transition
  * Links hidden on mobile and visible on desktop (mobile first)

* **Intro + Skills**

  * Introduction section with descriptive text
  * Skills represented as animated progress bars using `@keyframes`

* **Banner**

  * Different background image for mobile and desktop (media queries)
  * Two variants: text only, or text with a call-to-action (CTA) button

* **Contact Form**

  * Inputs with native validation (`required`, `pattern`, `type`)
  * Fields: Name, Surname, Phone, Radios, GitHub tag (regexp), Textarea, Newsletter checkbox
  * Buttons: Save (submit) and Reset
  * Accessible and responsive design

* **Projects**

  * Independent page with **CSS grid** to display series posters
  * Video with autoplay, fade-in animation, and two formats (`.mp4` and `.webm`) to ensure playback across different browsers

* **Footer**

  * External links to social networks (Instagram, Twitch) with SVG icons

* **Accessibility**

  * Use of `<nav>` tags in header and footer for semantic navigation
  * "Skip to content" link visually hidden with the `sr-only` class but accessible to screen readers
  * Contrast ensured through color variables

## Project Structure

```
.
├── index.html        # Home with introduction, skills, and banner
├── projects.html     # Projects page (video + grid)
├── signin.html       # Contact page with validated form
├── styles/
│   ├── common.css
│   ├── components.css
│   ├── header.css
│   ├── footer.css
│   ├── banner.css
│   ├── intro.css
│   ├── skills.css
│   ├── projects.css
│   ├── info.css
│   └── signin.css
└── assets/           # Images, videos, and SVGs
```

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/BeatrizHCastro/practica-html-css.git
   cd practica-html-css
   ```

2. Open `index.html` in your browser.

3. Navigate between pages (`index.html`, `projects.html`, `signin.html`).

## Screenshots

<!-- ![Home](SCREENSHOT LINK) -->

<!-- ![Projects](SCREENSHOT LINK) -->

<!-- ![Signin](SCREENSHOT LINK) -->

## Requirements

* Google Chrome, Mozilla Firefox, or Microsoft Edge (latest version)
* No installation or external dependencies required

## Fulfilled Criteria

* [x] Header + Navbar with hover and transition
* [x] Intro with description and animated skills
* [x] Banner with responsive images
* [x] Complete form with HTML validation
* [x] Footer with external links
* [x] Page with autoplay video + fade-in
* [x] Page with responsive grid
* [x] Mobile first + media queries
* [x] Complete README

## Credits

* Development: [@BeatrizHCastro](https://github.com/BeatrizHCastro)
* Statement and tutoring: [@kevinccbsg](https://github.com/kevinccbsg) (Full Stack Web Bootcamp – KeepCoding)
* Inspired by the character **Satoru Gojo** from *Jujutsu Kaisen*
* Visual resources:

  * Screenshots and promotional posters from the series and movie
  * Video trailer season two *Jujutsu Kaisen: Hidden Inventory / Premature Death*
  * Logo created with AI tools
  * Banner images obtained from:
    * [WallpaperCave](https://wallpapercave.com/w/wp8674359)
    * [Pinterest](https://es.pinterest.com/pin/742460688566282547/)
  * Contact form background image obtained from [Pinterest](https://mx.pinterest.com/pin/859554278878253832/)

## License

MIT © 2025 BeatrizHCastro




