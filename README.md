# Huellitas 🐾

Sitio web para un centro de adopción canina. Conecta perros rescatados con familias listas para darles un hogar.

🔗 Demo: [https://jonnschenk.github.io/Huellitas/](https://jonnschenk.github.io/Huellitas/)

## Estructura

```
Huellitas/
├── index.html      # Página principal
├── contacto.html   # Formulario de solicitud de adopción
└── css/
    └── styles.css   # Estilos del sitio
```

## Secciones

- **Hero** — Mensaje principal de bienvenida y llamado a la acción.
- **Perros destacados** — Selección semanal de perros disponibles para adopción.
- **Cómo funciona** — Proceso de adopción en cuatro pasos.
- **Historias** — Testimonios de adopciones exitosas y estadísticas.
- **CTA final** — Invitación a solicitar una adopción.
- **Contacto** (`contacto.html`) — Formulario de solicitud de adopción. Si llegas desde la tarjeta de un perro, ese perro ya viene seleccionado.

## Accesibilidad

- Idioma de la página con `lang="es"` y frases en inglés marcadas con `lang="en"`.
- HTML semántico: `header`, `nav`, `main`, `section`, `article`, `ol`, `figure`/`blockquote`/`figcaption` y `footer`, con títulos en orden (h1 → h2 → h3).
- Todas las imágenes tienen un `alt` que describe al perro y lo que pasa en la foto.
- El formulario usa `label` con `for` en cada campo, `fieldset`/`legend` para las opciones de vivienda y `aria-describedby` para el texto de ayuda.
- Roles ARIA: `banner`, `contentinfo` y `status` (el mensaje que aparece al enviar el formulario).
- `aria-label` en la navegación principal, la del pie de página y el logo.
- Contrastes revisados con WCAG AA: todo el texto supera 4.5:1. El color de acento se oscureció a `#A34D2D` para cumplirlo.
- Enlace "Saltar al contenido", foco visible al navegar con teclado y `aria-current` en la página activa.

## Créditos

Fotos de [Unsplash](https://unsplash.com), de uso libre bajo la [licencia de Unsplash](https://unsplash.com/license).

## Uso

Abre `index.html` en un navegador para ver el sitio. No requiere build ni dependencias.

## Autor

Jonathan M. Ramírez

- Email: [jonathanrott.dev@gmail.com](mailto:jonathanrott.dev@gmail.com)
- GitHub: [github.com/jonnschenk](https://github.com/jonnschenk)
- LinkedIn: [linkedin.com/in/jonathan-ramírez](https://www.linkedin.com/in/jonathan-ramírez-2b0043246/)

---

© 2026 Jonathan Ramírez.
