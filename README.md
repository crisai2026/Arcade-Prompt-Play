# 🕹️ Arcade crisai2026

Portada pública con todos mis juegos de navegador: **https://crisai2026.github.io**

## Agregar un juego

Edita `index.html` y, dentro de la lista `GAMES`, copia un bloque `{ ... }` y cambia:

- `repo`: nombre del repositorio en github.com/crisai2026
- `name`, `emoji`, `color`, `updated` (fecha AAAA-MM-DD)
- `tags`: categorías (3d, action, sim, adventure, platform, rpg, calm, strategy, rhythm, 2p)
- `play`: `"auto"` = https://crisai2026.github.io/&lt;repo&gt;/ (necesita GitHub Pages activado en ese repo), otro link, o `""`
- `es` / `en`: descripción en español e inglés
- `by`: quién lo hizo (opcional)
- `hidden: true` para esconderlo sin borrarlo

La portada revisa sola qué juegos tienen GitHub Pages activado y apaga el botón ▶ de los que no.
