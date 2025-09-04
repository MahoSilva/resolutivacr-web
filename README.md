# Starter Resolutiva para GitHub Pages

Publica el sitio de **Resolutiva** en GitHub Pages y conecta el dominio **www.resolutivacr.com**.

## Pasos rápidos
1) Crea un repositorio (sugerido: `resolutivacr-web` o `mahosilva.github.io` si usas el sitio de usuario).
2) Sube estos archivos a la **raíz** del repo.
3) Settings → Pages → Source: `Deploy from a branch`, Branch: `main` (`/root`).
4) Abre tu sitio (`https://tuusuario.github.io/nombre-repo`) y verifica.
5) Custom domain: `www.resolutivacr.com` (se crea `CNAME` automáticamente si lo pones desde Settings → Pages).
6) En GoDaddy (DNS):
   - **Apex (resolutivacr.com)** → Registros **A** a:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - **www.resolutivacr.com** → **CNAME** a `tuusuario.github.io`.
7) Habilita **Enforce HTTPS** en Settings → Pages.

## Edición
Edita `index.html`, `styles.css` y sube imágenes a `assets/`. Actualiza `robots.txt`/`sitemap.xml` si cambias URLs.
