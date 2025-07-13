# 🚀 Alexander López - Portfolio

Un portfolio moderno y minimalista construido con **Astro**, **Tailwind CSS** y desplegado en **Vercel**.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge&logo=vercel)](https://portfolio-alex.vercel.app)
[![Astro](https://img.shields.io/badge/Astro-4.0-orange?style=for-the-badge&logo=astro)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.0-blue?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com)

## ✨ Características

- 🎨 **Diseño moderno** con gradientes y efectos visuales
- ⚡ **Rendimiento optimizado** con Astro (sitio estático)
- 📱 **Completamente responsive** 
- 🎯 **SEO optimizado**
- 📊 **Analytics integrados** (Vercel Analytics + Google Analytics)
- 🌙 **Tipografía premium** (Poppins + Fira Code)
- 🔥 **Deploy automático** en Vercel

## 🛠️ Tecnologías

- **[Astro](https://astro.build)** - Framework web moderno
- **[Tailwind CSS](https://tailwindcss.com)** - Framework de CSS utility-first
- **[TypeScript](https://typescriptlang.org)** - Tipado estático
- **[Vercel](https://vercel.com)** - Deploy y hosting
- **[Google Fonts](https://fonts.google.com)** - Poppins & Fira Code

## 📁 Estructura del Proyecto

```text
/
├── public/
│   ├── favicon.svg
│   └── images/
│       └── photo-profile.jpeg
├── src/
│   ├── components/
│   │   └── Header.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tailwind.config.mjs
└── vercel.json
```

## 🚀 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando | Acción |
| :-- | :-- |
| `npm install` | Instala las dependencias |
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build` | Construye el sitio para producción en `./dist/` |
| `npm run preview` | Vista previa del sitio construido localmente |
| `npm run astro` | Ejecuta comandos de Astro CLI |

## 🎯 Inicio Rápido

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/aalexlpez/portfolio-alex.git
   cd portfolio-alex
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**
   ```bash
   npm run dev
   ```

4. **Abre tu navegador**
   ```
   http://localhost:4321
   ```

## 📊 Analytics

Este portfolio incluye:
- **Vercel Analytics** - Métricas de rendimiento y Core Web Vitals
- **Google Analytics** - Análisis detallado de usuarios (configurar `GA_MEASUREMENT_ID`)

## 🌐 Deploy

El sitio se despliega automáticamente en Vercel cuando se hace push a la rama `main`.

### Deploy manual:
```bash
npm run build
npx vercel --prod
```

## 🎨 Personalización

### Colores y diseño
Los estilos están en `src/layouts/Layout.astro` y se pueden personalizar fácilmente.

### Fuentes
Configuradas en `tailwind.config.mjs`:
- **Poppins** - Fuente principal (sans)
- **Fira Code** - Fuente monospace (código)

### Analytics
Para configurar Google Analytics, reemplaza `GA_MEASUREMENT_ID` en `src/layouts/Layout.astro`.

## 📄 Licencia

MIT © [Alexander López](https://github.com/aalexlpez)

## 🤝 Contribuciones

Las contribuciones, issues y sugerencias son bienvenidas.

---

⭐ **¿Te gustó el proyecto? ¡Dale una estrella!**
