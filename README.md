# daiwood-site

Landing page de **DAI** (extensión de SketchUp para diseño de gabinetes) — https://daiwood.com

- Estático puro (sin build): `index.html` + páginas legales. GitHub Pages lo sirve tal cual.
- Bilingüe EN/ES: strings en el objeto `I18N` dentro de `index.html`; el inglés vive en el
  HTML y el español se aplica por JS (auto-detección por `navigator.language` + toggle).
- `CNAME` apunta el dominio custom de GitHub Pages a `daiwood.com`.

## Publicar cambios

```
git push   # GitHub Pages se redespliega solo desde main
```

## Pendientes

- [ ] Screenshot real del plugin en el hero (placeholder por ahora)
- [ ] Revisión legal de terms/privacy/refunds (están como DRAFT)
- [ ] Botón de compra Paddle cuando la cuenta seller esté aprobada (hoy: trial por email)
