ADRI Fit v3
============

Archivos:
- index.html: aplicación.
- manifest.webmanifest: permite instalarla como PWA.
- sw.js: funcionamiento offline del "app shell".
- icon-192.png / icon-512.png: iconos.

IMPORTANTE PARA INSTALARLA COMO APP
-----------------------------------
Los navegadores solo permiten instalar una PWA desde HTTPS (o localhost), no abriendo index.html como file://.

Opciones sencillas:
1. Subir esta carpeta a GitHub Pages, Netlify, Cloudflare Pages o cualquier hosting HTTPS.
2. Abrir la URL publicada en el móvil.
3. Android/Chrome: usar "Instalar" cuando aparezca.
4. iPhone/Safari: Compartir -> Añadir a pantalla de inicio.

Los datos se guardan en localStorage del navegador. En Ajustes puedes exportar/importar un backup JSON.
