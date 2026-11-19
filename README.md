# Artina Qhanapa

Web del colectivo de arte Artina Qhanapa (Tacna, Perú): galería de obras, artistas y compra por WhatsApp.

Los datos de las obras están en `datos.json` y las fotos en `obras/`.

## Panel de administración

En `admin.html` (www.artinaqhanapa.com/admin.html) se editan las obras, las artistas, las exposiciones y los datos del colectivo.
Al tocar **Guardar y publicar**, el panel guarda `datos.json` y las fotos en este repositorio con un solo commit, y Cloudflare publica la web en un minuto.
Para entrar se necesita un token de GitHub de grano fino, limitado a este repositorio, con permiso **Contents: Read and write**.

## Exposiciones virtuales

Cada exposición de `datos.json` (`exposiciones`) aparece en la sección Exposiciones con su estado (próximamente, en curso o finalizada, según las fechas) y abre un catálogo que se hojea. Enlace directo: `#exposicion=<id>`. Los afiches se guardan en `exposiciones/`.
