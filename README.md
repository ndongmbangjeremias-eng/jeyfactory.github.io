# Jeyfactory — Landing page

Página web de una sola pieza (`jeyfactory.html`) para Jeyfactory, empresa de edición, marketing y gestión de redes sociales.

## Contenido del archivo

Todo está en un único archivo autocontenido: HTML, CSS y una ilustración SVG. No depende de imágenes externas ni de ningún backend.

Fuentes: se cargan desde Google Fonts (Anton para los títulos, Inter para el texto). Si vas a alojar la página sin conexión a internet, sustitúyelas por fuentes del sistema en el bloque `<style>`.

## Cómo usarla

1. Abre `jeyfactory.html` directamente en cualquier navegador para verla, o
2. Súbela tal cual a cualquier hosting estático (GitHub Pages, Netlify, Vercel, un cPanel, etc.). No necesita build ni instalación de dependencias.

## Secciones de la página

- **Header** — logo y menú de navegación.
- **Hero** — nombre de la empresa en letras grandes y llamativas, más una frase de presentación.
- **Cinta animada** — palabras clave de los servicios en movimiento.
- **Ilustración** — un ordenador mostrando publicaciones de redes sociales.
- **Servicios** — edición de video, gestión de redes, contenido y copy, publicidad paga.
- **Trabajo reciente** — cuadrícula tipo feed con ejemplos de piezas.
- **Cómo trabajamos** — proceso en 4 pasos.
- **Testimonio** — cita de un cliente.
- **Contacto** — correo (`ndongmbangjeremias@gmail.com`) e Instagram (`@jeyproyect_edicion`), como botones grandes y visibles.

## Personalizar

Los textos, precios, testimonios y datos de contacto son de ejemplo — búscalos y reemplázalos directamente en el HTML:

- Nombre y datos de contacto: sección `id="contacto"`.
- Colores de marca: variables al inicio del `<style>` (`--lime`, `--pink`, `--bg`, etc.).
- Textos de servicios y proceso: bloques `service-row` y `step`.
