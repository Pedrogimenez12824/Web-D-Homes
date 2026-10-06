# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS in `site/` (published folder): one `site/index.html` with inline styles and scripts, hash-based routing between pages, self-hosted fonts in `site/fonts/`, media in `site/media/`. While in preview, `site/robots.txt`, `site/_headers` and a robots meta block indexing (remove at launch). No build step. Google Maps only loads after the visitor clicks "Ver mapa" (consent stored in localStorage `dhomes-mapas`).

## Users

Vecinos de Vilagarcía de Arousa y alrededores que buscan peluquería de caballeros. Público variado: clientes fieles de toda la vida (corte clásico), gente que busca degradados y cortes actuales, y chavales (atendidos por un peluquero joven del equipo). Una parte usa el servicio a domicilio por movilidad reducida. Muchos llegan desde el móvil buscando teléfono, horario o cómo llegar.

## Product Purpose

Web de D'Homes Peluquería: que quien la visite confíe en el sitio y llame para pedir cita. Éxito = llamadas al móvil 633 247 464 (único teléfono que se publica; el fijo 986 500 766 NO debe aparecer) y visitas al local.

## Positioning

Peluquería de caballeros abierta desde 1994 (más de 32 años) en Vilagarcía, dirigida por Nelly Mosteiro: oficio de barbería clásica con técnicas actuales, trato cercano por el nombre, cita previa sin esperas, y servicio a domicilio.

## Operating Context

- Cita previa solo por teléfono (no WhatsApp, no reservas online).
- Horario de invierno (sep–may) y verano (jun–ago); la web calcula "abierto/cerrado ahora" con hora de Madrid.
- Dirección: Arzobispo Gelmírez, 7 Bajo, 36600 Vilagarcía de Arousa (Pontevedra). Email: nellymosteiro69@gmail.com.

## Capabilities and Constraints

- Servicios: Cabello (corte, marcado, contornos), Barba (arreglo, afeitado a navaja con toalla caliente), Color (tintes, mechas), A domicilio.
- **No se publican precios** (decisión de la dueña). Precios "a consultar por teléfono".
- Acceso para movilidad reducida. Pago con tarjeta y efectivo.
- Los datos actuales se mantienen; el propietario de la web enviará correcciones puntuales.

## SEO

- URL provisional en canonical, og:url, og:image y JSON-LD: `https://dhomes-peluqueria.pages.dev`. Al conectar el dominio: sustituirla en `site/index.html` y quitar noindex (meta robots, `site/robots.txt`, `site/_headers`).
- Imagen para compartir: `site/media/compartir.jpg` (1200x630). Iconos: `site/apple-touch-icon.png`, `site/icon-512.png`, `site/site.webmanifest`.

## Legal

- Titular: D' Homes Peluquería. NIF pendiente (XXXXXX en la web). Domicilio: Calle Arzobispo Gelmírez, 7, 36600 Vilagarcía de Arousa (Pontevedra).
- Páginas: #/aviso-legal, #/privacidad, #/cookies. Sin analítica ni cookies propias; solo Google Maps tras permiso.

## Brand Commitments

- Nombre: D'HOMES · Peluquería. El logotipo NO debe incluir "Nelly Mosteiro" (el nombre puede aparecer en el texto de "Conócenos").
- No hay logo oficial; el logotipo tipográfico actual (D'HOMES en Cinzel Decorative dorado + "Peluquería") es válido.
- Paleta a mantener aproximadamente: granate/vino oscuro + dorado + crema. Franja de poste de barbero (rojo/blanco/azul) presente.
- Tono: cercano, sencillo, sin prisas, en español de España.

## Evidence on Hand

- Fotos y vídeos reales de cortes en `media/` (WebP 900px; vídeos solo MP4 H.264 baseline (máxima compatibilidad), 540x960, sin sonido; si un vídeo falla se sustituye por su póster). Se usan en la cinta de la portada, la página Galería y los paneles de Cabello y Barba. Fotos del equipo: `media/equipo-nelly.webp` (Conócenos) y `media/equipo-barbero.webp` (portada y franja de equipo). Equipo: Nelly Mosteiro (fundadora) y Marcos Paz (peluquero).

- Reseñas reales de Google (10) ya en la web.
- Fachada: `media/fachada.webp` (fondo casi transparente de la portada) y `media/fachada-lateral.webp` (sin usar aún). Conócenos: `equipo-dos.webp` (los dos con tijeras, brillo corregido) y retratos `retrato-nelly.webp`, `retrato-marcos.webp`.
- No hay precios, ni logo oficial. No inventar reseñas, cifras ni premios.

## Product Principles

1. Llamar tiene que estar siempre a un toque, sobre todo en móvil.
2. Horario, dirección y teléfono visibles sin buscar.
3. Oficio y confianza por encima de modas: transmitir trayectoria real (desde 1994).
4. Las fotos reales serán la prueba principal; el diseño debe dejarles sitio.

## Accessibility & Inclusion

Público de todas las edades, incluidos mayores: texto legible (≥17px), alto contraste, objetivos táctiles grandes, respetar reduced-motion.
