# Scratchpad - Médico Online Landing Page

## Trabajo Realizado

### Proyecto Astro Creado
- Inicializado proyecto Astro 5.x con template minimal
- Configurado para despliegue en GitHub Pages:
  - `output: 'static'`
  - `outDir: 'docs'` 
  - `site` y `base` configurados para mbarriosRojas/perro-caballo

### Estructura Implementada
- **Layout Base**: Sistema de CSS variables, estilos globales responsivos
- **Componentes Astro**:
  - Header: Navegación sticky con menú mobile
  - Hero: Sección principal con CTA y estadísticas
  - Services: Grid de 6 servicios médicos
  - HowItWorks: Proceso en 4 pasos
  - Benefits: 6 beneficios clave
  - Testimonials: 3 testimonios de pacientes
  - Contact: Formulario + info de contacto
  - Footer: Links, redes sociales, legal

### Características Técnicas
- HTML5 semántico (header, nav, main, section, footer)
- CSS Grid y Flexbox para layouts responsivos
- Mobile-first design
- Smooth scroll navigation
- Interactividad con JavaScript (menú mobile, formulario)

### Archivos Clave
- `/src/pages/index.astro` - Página principal
- `/src/layouts/BaseLayout.astro` - Layout base con estilos globales
- `/src/components/*` - 8 componentes reutilizables
- `/public/favicon.svg` - Icono personalizado
- `astro.config.mjs` - Configuración para GitHub Pages

### Pendiente
- Build del proyecto
- Commit y push a main
