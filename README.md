# Médico Online - Landing Page

Landing page estática de alta conversión para "Médico Online", una plataforma integral de telemedicina y bienestar humano.

## 🚀 Tecnologías

- **Astro 5.x** - Framework web moderno para sitios estáticos
- **HTML5 Semántico** - Estructura accesible y SEO-friendly
- **CSS3 con Variables** - Diseño responsivo con Grid y Flexbox
- **TypeScript** - Tipado estático para mayor seguridad

## 📋 Características

- ✅ Diseño totalmente responsivo (mobile-first)
- ✅ Optimizado para SEO
- ✅ Componentes reutilizables Astro
- ✅ CSS variables para fácil personalización
- ✅ Navegación fluida con scroll suave
- ✅ Formulario de contacto interactivo
- ✅ Configurado para GitHub Pages

## 🛠️ Instalación

```bash
# Instalar dependencias
npm install
```

## 🏃 Comandos Disponibles

| Comando                | Descripción                                    |
| :--------------------- | :--------------------------------------------- |
| `npm run dev`          | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`        | Genera el sitio estático en `/docs`            |
| `npm run preview`      | Previsualiza la build localmente               |

## 📦 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── HowItWorks.astro
│   │   ├── Benefits.astro
│   │   ├── Testimonials.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🌐 Deployment en GitHub Pages

El proyecto está configurado para desplegarse automáticamente en GitHub Pages:

1. La configuración en `astro.config.mjs` ya incluye:
   - `output: 'static'` - Genera sitio estático
   - `outDir: 'docs'` - Output en carpeta /docs
   - `site` y `base` configurados para GitHub Pages

2. Para desplegar:
   ```bash
   npm run build
   git add .
   git commit -m "Build para producción"
   git push
   ```

3. En GitHub, ve a Settings > Pages y configura:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /docs

## 🎨 Personalización

Las variables CSS están centralizadas en `BaseLayout.astro`:

```css
:root {
  --color-primary: #0066cc;
  --color-secondary: #00bfa5;
  --spacing-md: 2rem;
  /* ... más variables */
}
```

## 📄 Secciones de la Landing Page

1. **Hero** - Mensaje principal y CTA
2. **Servicios** - 6 servicios médicos principales
3. **Cómo Funciona** - Proceso en 4 pasos
4. **Beneficios** - Ventajas de la plataforma
5. **Testimonios** - Opiniones de pacientes
6. **Contacto** - Formulario y datos de contacto
7. **Footer** - Enlaces y redes sociales

## 📝 Notas

- Este es un proyecto de demostración y no proporciona servicios médicos reales
- Todos los datos y testimonios son ficticios
- El formulario de contacto es funcional pero solo muestra alertas (no envía emails)

## 📧 Contacto

Para consultas sobre el proyecto: contacto@medicoonline.com

---

Desarrollado con Astro 🚀
