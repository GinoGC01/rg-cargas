# 🚚 RG Cargas - Landing Page

Landing page moderna y profesional para RG Cargas, empresa de transporte, fletes y mudanzas con más de 15 años de experiencia en Argentina.

## 📋 Tabla de Contenidos

- [Características](#características)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Desarrollo](#desarrollo)
- [Componentes](#componentes)
- [Imágenes Requeridas](#imágenes-requeridas)
- [Estilos](#estilos)
- [SEO y Accesibilidad](#seo-y-accesibilidad)
- [Despliegue](#despliegue)
- [Licencia](#licencia)

## ✨ Características

### Diseño y UX
- 🎨 **Diseño moderno** inspirado en la identidad de Racing Club (celeste, blanco, negro)
- 📱 **Totalmente responsive** - Funciona perfecto en desktop, tablet y mobile
- ⚡ **Animaciones suaves** - Fade-in, slide-in y efectos hover
- 🎯 **Orientado a conversión** - CTAs estratégicos y copys persuasivos

### Funcionalidades
- 📍 **5 Secciones principales**: Home, Nosotros, Servicios, Contacto, Términos
- 🖼️ **Galería de servicios** interactiva con efectos hover
- 📝 **Formulario de contacto** funcional con validación
- 📱 **Menú móvil animado** con transición suave
- 🔍 **SEO optimizado** con meta tags completos y Schema.org

### Tecnología
- ⚛️ **Astro** - Framework moderno y rápido
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 📘 **TypeScript** - Tipado estático en scripts
- ♿ **Accesible** - ARIA labels y semántica HTML correcta

## 📁 Estructura del Proyecto
```
RG-CARGAS/
├── .astro/                 # Archivos de caché de Astro
├── node_modules/           # Dependencias del proyecto
├── public/                 # Archivos estáticos
│   └── images/            # Imágenes del sitio
│       ├── hero-truck.jpg
│       ├── about-team.jpg
│       ├── service-transport.jpg
│       ├── service-freight.jpg
│       ├── service-moving.jpg
│       ├── gallery-1.jpg
│       ├── gallery-2.jpg
│       ├── gallery-3.jpg
│       ├── gallery-4.jpg
│       ├── why-choose-us-1.jpg
│       ├── why-choose-us-2.jpg
│       └── contact-office.jpg
├── src/                    # Código fuente
│   ├── components/        # Componentes Astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Elegimos.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   └── Terminos.astro
│   ├── layouts/           # Layouts
│   │   └── Layout.astro
│   ├── pages/             # Páginas
│   │   └── index.astro
│   └── styles/            # Estilos CSS
│       ├── global.css
│       └── style.css
├── .gitignore
├── astro.config.mjs       # Configuración de Astro
├── package-lock.json
├── package.json
├── README.md              # Este archivo
└── tsconfig.json          # Configuración TypeScript
```

## 🛠️ Tecnologías Utilizadas

- **[Astro](https://astro.build/)** - Framework web moderno
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utility-first
- **[TypeScript](https://www.typescriptlang.org/)** - JavaScript con tipado estático
- **HTML5** - Semántica y accesibilidad
- **CSS3** - Animaciones y efectos modernos

## 🚀 Instalación

### Prerrequisitos

- Node.js 18.0 o superior
- npm o yarn

### Pasos

1. **Clonar el repositorio**
```bash
   git clone https://github.com/tu-usuario/rg-cargas.git
   cd rg-cargas
```

2. **Instalar dependencias**
```bash
   npm install
```

3. **Agregar las imágenes**
   - Coloca todas las imágenes en la carpeta `public/images/`
   - Ver la sección [Imágenes Requeridas](#imágenes-requeridas) para detalles

4. **Iniciar servidor de desarrollo**
```bash
   npm run dev
```

5. **Abrir en el navegador**
```
   http://localhost:4321
```

## 💻 Desarrollo

### Comandos Disponibles

| Comando                | Acción                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Instala las dependencias                         |
| `npm run dev`          | Inicia servidor local en `localhost:4321`        |
| `npm run build`        | Construye el sitio para producción en `./dist/`  |
| `npm run preview`      | Vista previa del build antes de desplegar        |
| `npm run astro ...`    | Ejecuta comandos CLI de Astro                    |

### Estructura de Componentes

#### **Layout.astro**
Layout principal que envuelve todas las páginas. Incluye:
- Meta tags SEO
- Schema.org markup
- Imports de estilos globales

#### **Header.astro**
Navegación principal con:
- Logo de RG Cargas
- Menú desktop
- Menú móvil animado
- Botón CTA

#### **Hero.astro**
Sección hero con:
- Headline persuasivo
- CTAs principales
- Estadísticas (años, envíos, satisfacción)
- Imagen principal

#### **About.astro**
Sección "Nosotros" con:
- Historia de la empresa
- Imagen del equipo
- Features destacados

#### **Services.astro**
Servicios ofrecidos:
- 3 servicios principales con imágenes
- Galería de 4 imágenes
- Iconos y descripciones

#### **Contact.astro**
Formulario de contacto con:
- Información de contacto
- Imagen de la oficina
- Formulario funcional

#### **Terminos.astro**
Términos y condiciones completos con 10 secciones legales

#### **Footer.astro**
Footer con:
- Links rápidos
- Newsletter
- Redes sociales
- Copyright

## 🖼️ Imágenes Requeridas

Todas las imágenes deben colocarse en `public/images/`. Aquí están las especificaciones:

### Imágenes Principales

| Archivo | Descripción | Tamaño Recomendado | Aspecto |
|---------|-------------|-------------------|---------|
| `hero-truck.jpg` | Camión RG Cargas en ruta | 1200x1200px | 1:1 |
| `about-team.jpg` | Equipo y flota | 1200x675px | 16:9 |
| `contact-office.jpg` | Oficina de RG Cargas | 800x600px | 4:3 |

### Servicios

| Archivo | Descripción | Tamaño Recomendado | Aspecto |
|---------|-------------|-------------------|---------|
| `service-transport.jpg` | Transporte de productos | 800x600px | 4:3 |
| `service-freight.jpg` | Fletes especializados | 800x600px | 4:3 |
| `service-moving.jpg` | Mudanzas integrales | 800x600px | 4:3 |

### Galería

| Archivo | Descripción | Tamaño Recomendado | Aspecto |
|---------|-------------|-------------------|---------|
| `gallery-1.jpg` | Flota moderna | 600x800px | 3:4 |
| `gallery-2.jpg` | Rastreo GPS | 600x800px | 3:4 |
| `gallery-3.jpg` | Embalaje profesional | 600x800px | 3:4 |
| `gallery-4.jpg` | Atención 24/7 | 600x800px | 3:4 |

### Por Qué Elegirnos

| Archivo | Descripción | Tamaño Recomendado | Aspecto |
|---------|-------------|-------------------|---------|
| `why-choose-us-1.jpg` | Transparencia | 1000x750px | 4:3 |
| `why-choose-us-2.jpg` | Seguridad | 1000x750px | 4:3 |

### Recomendaciones para las Imágenes

- ✅ Formato: JPG (optimizado para web)
- ✅ Peso: Máximo 500KB por imagen
- ✅ Optimización: Usar herramientas como TinyPNG
- ✅ Calidad: 80-85% para balance entre calidad/peso
- ✅ Colores: Incluir elementos celestes de la marca

## 🎨 Estilos

### Variables CSS (global.css)
```css
:root {
  --racing-blue: #00A9E0;    /* Celeste Racing */
  --racing-dark: #1A1D29;    /* Negro/Gris oscuro */
  --racing-light: #F8FAFB;   /* Blanco/Gris claro */
}
```

### Clases Principales (style.css)

- `.gradient-racing` - Gradiente celeste de marca
- `.glass-effect` - Efecto glassmorphism
- `.hover-scale` - Efecto hover con escala
- `.fade-in` - Animación de aparición
- `.slide-in-left` - Animación desde izquierda
- `.mobile-menu-open/closed` - Estados del menú móvil

### Tailwind Config

El proyecto usa Tailwind CSS desde CDN. Para personalizar, crear `tailwind.config.js`:
```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        'racing-blue': '#00A9E0',
        'racing-dark': '#1A1D29',
      }
    }
  }
}
```

## 🔍 SEO y Accesibilidad

### Meta Tags Implementados

- ✅ Title optimizado con keywords
- ✅ Meta description con emojis
- ✅ Keywords relevantes
- ✅ Open Graph (Facebook/WhatsApp)
- ✅ Twitter Cards
- ✅ Canonical URL
- ✅ Geo tags (Buenos Aires)

### Schema.org Markup
```json
{
  "@context": "https://schema.org",
  "@type": "MovingCompany",
  "name": "RG Cargas",
  "telephone": "+54-11-4258-7896",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Av. Mitre 2450",
    "addressLocality": "Avellaneda",
    "addressRegion": "Buenos Aires",
    "addressCountry": "AR"
  }
}
```

### Accesibilidad

- ✅ Semántica HTML5 correcta
- ✅ ARIA labels en botones y menús
- ✅ Alt text descriptivo en todas las imágenes
- ✅ Contraste de colores AA/AAA
- ✅ Navegación por teclado
- ✅ Focus visible en elementos interactivos

## 🚀 Despliegue

### Vercel (Recomendado)

1. **Push a GitHub**
```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
```

2. **Importar en Vercel**
   - Ir a [vercel.com](https://vercel.com)
   - Click en "New Project"
   - Importar el repositorio de GitHub
   - Vercel detectará automáticamente Astro

3. **Configurar variables de entorno** (si es necesario)

4. **Deploy** 🚀

### Netlify

1. **Build command**: `npm run build`
2. **Publish directory**: `dist`
3. **Deploy**

### GitHub Pages
```bash
npm run build
# Subir la carpeta dist/ a gh-pages branch
```

## 📝 Personalización

### Cambiar Colores

Editar `src/styles/global.css`:
```css
:root {
  --racing-blue: #TU_COLOR;
  --racing-dark: #TU_COLOR;
}
```

### Cambiar Textos

Todos los textos están en los componentes `.astro`. Buscar y reemplazar directamente.

### Agregar Secciones

1. Crear componente en `src/components/`
2. Importar en `src/pages/index.astro`
3. Agregar al layout

### Modificar Formulario

El formulario en `Contact.astro` tiene una función `handleSubmit()`. Para conectar a backend:
```typescript
async function handleSubmit(event: Event): Promise<void> {
  event.preventDefault();
  const form = event.target as HTMLFormElement;
  const formData = new FormData(form);
  
  // Enviar a tu API
  const response = await fetch('/api/contact', {
    method: 'POST',
    body: formData
  });
  
  // Manejar respuesta
}
```

## 🐛 Troubleshooting

### Las imágenes no cargan
- ✅ Verificar que estén en `public/images/`
- ✅ Nombres exactos sin espacios
- ✅ Extensión en minúsculas (.jpg)

### El menú móvil no funciona
- ✅ Verificar que el script esté con `is:inline`
- ✅ Comprobar IDs de elementos
- ✅ Revisar console del navegador

### Estilos no se aplican
- ✅ Imports correctos en Layout.astro
- ✅ Archivos CSS en `src/styles/`
- ✅ Reiniciar servidor de desarrollo

## 📞 Soporte

Para dudas o problemas:
- 📧 Email: contacto@rgcargas.com
- 🐛 Issues: [GitHub Issues](https://github.com/tu-usuario/rg-cargas/issues)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

**Desarrollado con ❤️ por [Tu Nombre]**

**RG Cargas** - Transporte profesional desde 2010 🚚