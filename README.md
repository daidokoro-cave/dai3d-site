# dai3d-site

Landing page de **DAI** (extensión de SketchUp para diseño de gabinetes) — https://dai3d.com

- Estático puro (sin build): `index.html` + páginas legales. GitHub Pages lo sirve tal cual.
- Bilingüe EN/ES: strings en el objeto `I18N` dentro de `index.html`; el inglés vive en el
  HTML y el español se aplica por JS (auto-detección por `navigator.language` + toggle).
- `CNAME` apunta el dominio custom de GitHub Pages a `dai3d.com`.

## Publicar cambios

```
git push   # GitHub Pages se redespliega solo desde main
```

## Posicionamiento

AI-first (decisión 2026-06-12): el diferencial de DAI es que una IA dibuja gabinetes en
SketchUp desde lenguaje natural / planos / fotos (vía MCP). El hero lleva una demo
animada (typewriter + blueprint SVG que se dibuja solo); los estados de las features de
IA son honestos: EARLY ACCESS / IN DEVELOPMENT / ROADMAP. El toolkit actual se presenta
como la base en producción.

## Pendientes

- [ ] Captura real del plugin para la sección toolkit (opcional, la demo cubre el hero)
- [ ] Revisión legal de terms/privacy/refunds (están como DRAFT)
- [ ] Botón de compra Paddle cuando la cuenta seller esté aprobada (hoy: trial por email)
