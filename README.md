# Portafolio de Ronald Avilés M.

Sitio de una sola página (`index.html`), sin dependencias de build: HTML + CSS puro, tipografías de Google Fonts.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `ronald-aviles.github.io` (si lo nombras así, tu sitio quedará en esa misma URL) o cualquier otro nombre, por ejemplo `portafolio`.
2. Sube `index.html` a la raíz del repositorio (puedes arrastrarlo desde la web de GitHub con "Add file → Upload files", o con git):
   ```bash
   git init
   git add index.html
   git commit -m "Sitio inicial"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git push -u origin main
   ```
3. En el repositorio, ve a **Settings → Pages**.
4. En "Build and deployment", selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
5. Espera un par de minutos; GitHub te dará la URL pública (algo como `https://TU-USUARIO.github.io/TU-REPO/`).

## Qué cambiar

- **Enlaces de descarga**: los botones de cada proyecto usan los enlaces de Google Drive que ya tenías en tu sitio anterior. Si prefieres alojar los archivos tú mismo, súbelos al repositorio (por ejemplo en una carpeta `/archivos`) y actualiza los `href` en `index.html`.
- **CV**: por ahora la sección "Sobre mí" invita a escribirte por correo para pedirlo. Si quieres un botón de descarga directa, sube el PDF al repositorio y agrega un enlace, por ejemplo `<a href="cv-ronald-aviles.pdf">Descargar CV</a>`.
- **Dominio propio**: si más adelante compras un dominio, en Settings → Pages puedes configurarlo como "Custom domain".

## Estructura del diseño

El diseño sigue la metáfora de una lámina de dibujo técnico: recuadro de hoja, numeración de secciones y de "láminas" para cada proyecto — un guiño directo a tu formación en ingeniería civil. Los colores (papel cálido, azul de plano y un acento tipo sello de bronce) y las tipografías (Space Grotesk para títulos, Source Serif 4 para el cuerpo) están pensados para leerse como un portafolio técnico, no como una plantilla genérica.
