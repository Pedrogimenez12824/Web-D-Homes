# Design

Diseño de la web de D'Homes Peluquería. Estilo de barbería clásica bien hecha, en una sola página oscura con fondo granate.

## Color
- Fondo granate: `--bg #1e0c0b`, `--bg-2 #26100e` (bandas), `--surface #2e1513` (tarjetas)
- Dorado: `--gold #d8bd86` (acento único: botones, enlaces, cursivas), `--gold-hi`, `--gold-lo`
- Crema (texto): `--ink #f3e9d6`, `--ink-2 #d9c8a8`, `--muted #b9a585`
- Líneas: `--line` (dorado al 20%), `--line-2` (al 38%)
- Poste de barbero (solo en la franja `.pole`): rojo `#b3322c`, crema `#f3ead9`, azul `#2d5fa8`

## Tipografía
- Logotipo: Cinzel Decorative 700, "D'HOMES" + "Peluquería" en Jost espaciado. Sin "Nelly Mosteiro".
- Títulos: Bodoni Moda (cursiva dorada para los énfasis).
- Texto: Jost 400/500/600, base de 17px.

## Componentes
- Botón principal `.btn-gold` ("Pedir cita", siempre `tel:633247464`), botón secundario `.btn-line`, y enlace `.link` con flecha.
- Radio de esquina: 6px en todo (`--r`).
- Listas con separadores finos en lugar de rejillas de tarjetas.
- `.ph` es el hueco de foto mientras no hay fotos reales: se sustituye por `<img>` dentro del mismo `figure`.

## Movimiento
- Curva `--ease-out: cubic-bezier(.23,1,.32,1)`. Los botones se encogen a `scale(.97)` al pulsarlos.
- Aparición escalonada de la portada solo al cargar, más un fundido entre páginas.
- La franja del poste se desplaza en bucle lineal.
- Con `prefers-reduced-motion` se desactiva todo el movimiento.
