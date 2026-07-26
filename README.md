# Plinko Chaos — website

Public marketing, support and legal pages for the **Plinko Chaos** mobile game
(Gies Games). Served by GitHub Pages from `main` at
<https://gijs-afk.github.io/plinko-chaos-site/>.

The game's source lives in a separate private repository; nothing here is part
of the app build.

## Pages

| File | URL | Used for |
| --- | --- | --- |
| `index.html` | `/` | Marketing landing page |
| `support.html` | `/support.html` | App Store & Play **Support URL** |
| `privacy.html` | `/privacy.html` | App Store & Play **Privacy Policy URL** |
| `terms.html` | `/terms.html` | EULA / terms link, copyright notice |
| `404.html` | any unknown path | Not-found page |

Static HTML with one shared `styles.css` — no build step. Edit, commit, push;
Pages redeploys in about a minute.

Artwork in `img/` is copied from the app's `assets/` folder (icon and Play
feature graphic).
