# shu-world — Referencias de Reels

Página de una sola hoja (`index.html`) con reels de referencia para Shu. Se publica sola en GitHub Pages
(https://diegorex17.github.io/shu-world/) con cada push a `main`. El repo es público.

## Agregar un reel (cuando Diegore pase un link)
1. Abre el link en el navegador (RedNote bloquea WebFetch; el navegador sí funciona).
2. Saca: título, nombre de usuario, link del perfil (sin `xsec_token`) y la portada (`meta og:image`).
3. Baja la portada y guárdala como JPG (ancho máx. 720) en `assets/` con el siguiente número: `reel-002.jpg`, `reel-003.jpg`...
4. Escribe `desc`: una línea en español que diga de qué trata el video.
5. Agrega `{ user, thumb, url, channel, desc }` al final del arreglo `REELS` en `index.html`, commit y push.

Si no puedes leer un link, di qué datos faltan; no los inventes. Los links con `xsec_token` pueden caducar: avisa si uno deja de abrir.

## Reglas
- Cambia solo lo necesario y explica por qué. Antes de borrar o renombrar archivos, muestra qué cambia y espera OK.
- Mantén el diseño: tarjetas `<details>`, buscador, "Colapsar/Expandir todo", tokens de color claro/oscuro,
  bien en celular. Estética de Shu (logo en `assets/shu-logo.png`): azul cielo, amarillo crema, rosa,
  contornos café tipo sticker; fuentes Baloo 2 (títulos) + Nunito (texto).
- `gh` está en `C:\Program Files\GitHub CLI\gh.exe` (cuenta diegorex17).
