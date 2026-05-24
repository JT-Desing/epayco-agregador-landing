# SEO, Schema y AI SEO - ePayco Agregador

## Objetivo de la pagina

Posicionar una landing de producto para la busqueda "agregador de pagos" y temas relacionados con pagos online en Colombia, links de cobro, QR, botones, checkout y cobros por WhatsApp, redes sociales, web o ecommerce.

URL publicada actual: https://jt-desing.github.io/epayco-agregador-landing/

## SEO audit

### Implementado

- Title unico: `Agregador de pagos para vender online en Colombia | ePayco`.
- Meta description enfocada en pagos online, links de cobro, QR, checkout, tiendas, botones y canales digitales.
- Canonical a la URL publicada en GitHub Pages.
- Meta robots `index,follow,max-image-preview:large`.
- Open Graph y Twitter metadata para compartir la pagina.
- Un solo H1 con keyword principal: "Empieza a recibir pagos online".
- H2s por bloques de intencion: beneficios, confianza, casos de uso, ecosistema, decision, como funciona, ruta evolutiva y FAQ.
- `robots.txt` y `sitemap.xml` en la raiz.

### Pendiente antes de dominio final

- Cambiar canonical, Open Graph URL, sitemap y `llms.txt` al dominio definitivo si se migra fuera de GitHub Pages.
- Validar indexacion en Google Search Console y Bing Webmaster Tools.
- Ejecutar PageSpeed Insights para medir LCP, INP y CLS con la version publicada.
- Revisar si los assets externos de imagen y GSAP deben alojarse localmente o servirse desde CDN propio.

## Schema

### Implementado en JSON-LD

- `Organization`: entidad ePayco.
- `WebSite`: sitio de la landing.
- `WebPage`: pagina principal con descripcion y relacion al servicio.
- `Service`: ePayco Agregador como servicio de pagos online para Colombia.
- `FAQPage`: preguntas frecuentes visibles en la pagina.

### Validacion recomendada

- Google Rich Results Test: https://search.google.com/test/rich-results
- Schema.org Validator: https://validator.schema.org/
- Verificar que el contenido del schema coincida con el contenido visible de la pagina.

## AI SEO

### Implementado

- `llms.txt` con resumen de producto, audiencia, temas clave y secciones utiles.
- `robots.txt` permite crawlers generales y crawlers de IA como GPTBot, ChatGPT-User, PerplexityBot, ClaudeBot, anthropic-ai y Google-Extended.
- FAQ visible y estructurada para extraccion de respuestas.
- Copy con bloques directos para consultas como "como cobrar online", "necesito pagina web para cobrar" y "como funciona un link de cobro".

### Recomendaciones siguientes

- Agregar una seccion visible "Que es un agregador de pagos" con respuesta directa de 40-60 palabras.
- Agregar una tabla comparativa simple: Agregador vs Gateway.
- Agregar fecha visible de ultima actualizacion.
- Agregar evidencia real cuando este disponible: cifras verificables, casos de cliente, medios de pago habilitados y cobertura.
- Si existe una pagina de precios oficial, crear o enlazar un `pricing.md` con informacion parseable para agentes de IA.
