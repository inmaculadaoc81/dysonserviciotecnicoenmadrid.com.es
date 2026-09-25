DYTECH SERVICIO TÉCNICO DYSON EN ALICANTE
=========================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DyTech, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Alicante y área metropolitana.

Dominio: https://serviciotecnicoenmadrid.com.es/
Marca: DyTech Servicio Técnico Dyson en Alicante
Ficha de Google: https://maps.app.goo.gl/uUcrnVkuVyAoRTnX8
Mapa: iframe de la ficha "DyTech Servicio Técnico Dyson en Alicante" (identificador
0xb91d0d3bb36228f:0x807027ad8874b999, el mismo del enlace de Google), en la sección
de contacto (ancho 100% vía CSS). Sustituye al anterior, que mostraba la ficha de Murcia.

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Alicante y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.

ESTRUCTURA
- index.html: toda la página y el JSON-LD.
- style.css, mobile-navigation.css, social-footer.css, cal-booking.css: base.
- dytech.css: identidad visual de la marca. dytech-header-hero.css: cabecera.
- dytech.js: menú móvil, formulario y cookies ("dytech_cookie_preference").
- dytech-n8n-chat.js / .css: chatbot n8n con el webhook compartido del grupo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_* y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.

PALETA: se mantiene la identidad actual de la marca, color principal #00B8D9 (cian).
WhatsApp conserva su verde y YouTube su rojo corporativo.
