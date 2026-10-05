# Acta de Entrega de actuaria.com

Acta de Entrega de la web de Actuaria Consultores en Webflow: infraestructura, dominio, cuentas, medición, formularios, código propio, scripts y pendientes. Se lanzó la noche del 1 de octubre de 2026 y se actualiza con cada cambio del sitio (ver "Registro de cambios").

**Léelo aquí:** https://renatopuente-ux.github.io/actuaria-web-entrega/

- `index.html`: el acta, una sola página sin dependencias de compilación. Tipografía de marca: Lemon Milk Pro (archivo del sitio en el CDN de Webflow), Nunito y Prompt (Google Fonts); íconos de Font Awesome (cdnjs).
- `Acta-de-Entrega-actuaria.com.pdf`: la misma acta en PDF (A4), para firmar y archivar.
- `capturas/`: capturas reales del sitio en producción (WebP) que usa el acta.
- `redirecciones-301.csv`: las 317 redirecciones 301 vigentes (origen, destino, tipo, nivel), las mismas que muestra el acta.
- Es público a propósito para poder compartirlo con un enlace. No contiene contraseñas, tokens, URLs de webhooks ni correos personales, y lleva `noindex` para no aparecer en buscadores.

Mantiene: Área de Producto de Actuaria Consultores. La fuente vive en el workspace del área, en `Migracion-Web/entrega/`, y se publica con `node publicar.mjs`.
