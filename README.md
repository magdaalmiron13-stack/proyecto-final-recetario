# Mi Recetario 🍓

Sitio web estático y responsivo de cinco páginas, creado como Proyecto Final del curso de Desarrollo Web de Coderhouse.

Mi Recetario reúne recetas caseras dulces, saladas, saludables y preparaciones básicas. La idea es conservar sabores, historias y recetas para compartir en familia.

## Sitio publicado

**Ver Mi Recetario:** https://mi-recetario-web.netlify.app/

## Páginas

- **Inicio (`index.html`)**: presentación, recetas destacadas y galería.
- **Dulce (`pages/dulce.html`)**: tarta de frutilla y torta de chocolate.
- **Salado (`pages/salado.html`)**: tarta de zucchini y bondiola al horno.
- **Básicos (`pages/basicos.html`)**: masa sablée y crema pastelera.
- **Saludable (`pages/saludable.html`)**: budín de banana vegano y galletas de arroz.

## Tecnologías utilizadas

- HTML5 semántico y SEO on-page (títulos, metadatos y textos alternativos).
- CSS3 y SCSS con partials, variables, nesting, mixins y `@extend`.
- Bootstrap 5 para navegación responsiva, carrusel y acordeones.
- Animate.css y transiciones CSS.
- Git y GitHub para control de versiones.
- Netlify para el despliegue del sitio estático.

## Organización del proyecto

```text
index.html
pages/
  dulce.html
  salado.html
  basicos.html
  saludable.html
assets/
scss/
  main.scss
  base/
  components/
  layout/
  utilities/
styles/
  styles.css
package.json
```

## Ejecutar el proyecto localmente

1. Cloná el repositorio y abrilo en Visual Studio Code.
2. Instalá las dependencias con `npm install`.
3. Si modificás los archivos SCSS, compilá con:

   ```bash
   npx sass scss/main.scss styles/styles.css
   ```

4. Abrí `index.html` con Live Server, o abrilo directamente en el navegador.

## Autoría

Proyecto realizado como entrega final del curso de Desarrollo Web de Coderhouse.
