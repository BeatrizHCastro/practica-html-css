# Práctica HTML y CSS

Portfolio ficticio de **Satoru Gojo (Jujutsu Kaisen)**, desarrollado como práctica de **HTML5 y CSS3** en el Bootcamp Full Stack Web de **KeepCoding**, en el módulo impartido por [**@kevinccbsg**](https://github.com/kevinccbsg).

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
  - Texto destacado con y sin botón de llamada a la acción

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
  - Contraste con variables de color

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

````

## Cómo usar

1. Clona este repositorio:  
   ```bash
   git clone https://github.com/BeatrizHCastro/practica-html-css.git
   cd practica-html-css
````

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
* Inspirado en el personaje **Satoru Gojo** de *Jujutsu Kaisen*
* Recursos visuales:
  - Capturas y pósters promocionales de la serie y película
  - Logo creado con herramientas de IA
  - Imágenes del banner obtenidas de:  
    - [WallpaperCave](https://wallpapercave.com/w/wp8674359)  
    - [Pinterest](https://es.pinterest.com/pin/742460688566282547/)  
  - Imagen de fondo del formulario obtenida de [Pinterest](https://mx.pinterest.com/pin/859554278878253832/)  


## Licencia

MIT © 2025 BeatrizHCastro



