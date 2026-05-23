# Ofertas Relâmpago — site estático

Static deals website built to apply for the Amazon Associates program and to serve as the
public showcase for the Telegram deals channel.

Plain HTML/CSS, no build step. Pages:

- `index.html` — home with the featured deals
- `sobre.html` — about page (who we are + affiliate disclosure)
- `post-*.html` — one article per deal, with original content
- `style.css` — styles

## Publish (GitHub Pages)

The repository must be **public** for free GitHub Pages. After pushing, enable Pages with
source = branch `main`, folder `/ (root)`. The site is then served at
`https://<user>.github.io/<repo>/`.

## Before going live / after Associates approval

- Replace the `#` in the "Receba as ofertas no Telegram" button (`index.html`) with your
  channel link, e.g. `https://t.me/yourchannel`.
- After approval, append your affiliate tag to each product link, e.g.
  `https://www.amazon.com.br/dp/ASIN?tag=yourtag-20` (see the TODO comments in each post).
- Prices shown are references captured on 2026-05-21 and should be reviewed periodically.
