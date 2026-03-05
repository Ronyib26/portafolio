# 🚀 Portafolio de Rony Lopez — Full-Stack Developer

Portafolio profesional construido con **Astro** + CSS.

## 🛠 Tecnologías
- [Astro](https://astro.build) — Framework principal
- CSS Variables + CSS puro
- Font Awesome — Iconos
- Google Fonts

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
git commit -m "comit inicial"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/portfolio.git
git push -u origin main
```

### Paso 2 — Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. **Settings** → **Pages**
3. En *Source* seleccionar **GitHub Actions**

### Paso 3 — Actualizar la URL en astro.config.mjs
```js
export default defineConfig({
  site: 'https://TU_USUARIO.github.io',
  base: '/portfolio', // nombre de tu repositorio
});
```
