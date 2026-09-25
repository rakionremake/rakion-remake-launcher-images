# Rakion Remake - imagenes dinamicas del launcher (BW959)

Este contenido debe quedar en la rama `main` del repositorio PUBLICO:

`rakionremake/rakion-remake-launcher-images`

Estructura:

- `manifest.json` en la raiz.
- `images/` con PNG/JPG/JPEG/BMP/GIF.

Cada vez que cambies, agregues o elimines una imagen, cambia tambien `version` en `manifest.json`.
El launcher consulta el manifest al abrir y luego aproximadamente cada 30 segundos.
