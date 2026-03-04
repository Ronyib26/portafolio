# 🚀 Portafolio de Rony Lopez — Full-Stack Developer

Portafolio profesional construido con **Astro** + CSS puro. Diseño dark theme con acentos en cian.

## 🛠 Tecnologías
- [Astro](https://astro.build) — Framework principal
- CSS Variables + CSS puro — Sin frameworks CSS externos
- Font Awesome — Iconos
- Google Fonts (Space Mono + DM Sans)

## ⚡ Desarrollo local

```bash
# Instalar dependencias
npm install

# Correr servidor de desarrollo
npm run dev

# Build para producción
npm run build
```

## 🌐 Publicar GRATIS en GitHub Pages

### Paso 1 — Subir a GitHub
```bash
git init
git add .
git commit -m "Initial commit: Portfolio Rony Lopez"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/portfolio.git
git push -u origin main
```

### Paso 2 — Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. **Settings** → **Pages**
3. En *Source* selecciona **GitHub Actions**
4. ¡Listo! En unos minutos tu sitio estará en `https://TU_USUARIO.github.io/portfolio`

### Paso 3 — Actualizar la URL en astro.config.mjs
```js
export default defineConfig({
  site: 'https://TU_USUARIO.github.io',
  base: '/portfolio', // nombre de tu repositorio
});
```

## 🌐 Alternativa: Publicar en Netlify (aún más fácil)

1. Ve a [netlify.com](https://netlify.com) y crea cuenta gratuita
2. Haz clic en **"Add new site"** → **"Import an existing project"**
3. Conecta tu repositorio de GitHub
4. Build command: `npm run build`
5. Publish directory: `dist`
6. ¡Deploy automático cada vez que hagas `git push`!

URL gratuita: `https://rony-portfolio.netlify.app` (puedes personalizar el nombre)

## 📝 Personalizar

Para agregar tu foto, reemplaza el bloque `.avatar-placeholder` en `index.astro`:

```astro
<!-- Reemplaza esto: -->
<div class="avatar-placeholder">
  <span>RL</span>
</div>

<!-- Con esto: -->
<img src="/tu-foto.jpg" alt="Rony Lopez" class="avatar-img" />
```

Y pon tu foto en `/public/tu-foto.jpg`
