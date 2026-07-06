# Landing La Faixa Blanca — Auditoría Gratuita

Landing de captura para reservar la llamada de auditoría gratuita de La Faixa Blanca (sistema de captación + cierre para estudios de PMU y micropigmentación capilar).

## Antes de publicar

1. **Activa el formulario (Formspree)**
   El formulario envía a `aaronmon.work@gmail.com` vía [Formspree](https://formspree.io), sin necesidad de crear cuenta.
   - La **primera vez** que alguien lo envíe (puedes probarlo tú mismo), Formspree mandará un email de confirmación a `aaronmon.work@gmail.com`.
   - Tienes **24 horas** para hacer clic en ese enlace de confirmación o se pierde ese primer envío.
   - Una vez confirmado, todos los envíos siguientes llegan directamente a tu bandeja de entrada.
   - Prueba el formulario tú mismo en cuanto la página esté publicada.

2. **Enlaces legales pendientes**
   Los enlaces de "Aviso Legal", "Política de Privacidad" y "Política de Cookies" en el pie de página son placeholders (`#`). Sustitúyelos por las páginas reales cuando las tengas.

## Publicar con GitHub Pages

Este repo está pensado para servirse directo con GitHub Pages:

1. En GitHub, entra a **Settings → Pages**.
2. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
3. Guarda. En unos minutos tu landing estará en `https://<usuario>.github.io/<nombre-repo>/`.

## Estructura

- `index.html` — la landing completa (título, subtítulo, formulario, qué te ofrezco, sobre mí, por qué solo 3, CTA final, disclaimer).
- Paleta de marca v2.0 "Del Blanco al Negro" (Negro #000000 / Blanco #FFFFFF / Rojo Pantone 186 C #C8102E) embebida como CSS variables en el propio `index.html` — ver `../../docs/brand-guidelines.md` para el detalle completo y el racional de marca.
- Diseño y estructura visual (badges con dot, hero con glow, tarjetas oscuras con borde sutil, CTA en píldora roja) inspirados en una landing de referencia aportada por Aaron, adaptados al copy y al formulario de captación reales de La Faixa Blanca.

## Contenido fuente

El copy de esta landing viene del proyecto La Faixa Blanca en Business Operations OS — ver `Brand Setup/3_Oferta.md`, `4_Avatares.md` y `5_Selling_Points.md` para el contexto completo de negocio detrás de cada bloque.

