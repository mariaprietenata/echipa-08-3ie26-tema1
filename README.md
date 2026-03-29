# FelineWorld - Site Web Static

## Tematica site-ului
Site de prezentare dedicat celor mai populare rase de pisici domestice: Ragdoll, Bengal, Maine Coon si British Shorthair.

## Platforme utilizate
- Generare si editare cod: Claude AI (claude.ai)
- Editare locala: VS Code
- Versioning: GitHub

## Structura paginilor
| Pagina | Fisier | Descriere |
|--------|--------|-----------|
| Acasa | `index.html` | Hero banner, prezentare generala, carduri rase |
| Rase | `rase.html` | Profile detaliate per rasa, statistici, trait bars |
| Galerie | `galerie.html` | Grid foto cu filtre pe rasa si lightbox |
| Contact | `contact.html` | Formular de contact cu validare JS |

## Structura fisierelor
```
static-site/
├── index.html
├── rase.html
├── galerie.html
├── contact.html
├── css/
│   ├── style.css      (stiluri comune: nav, footer, butoane)
│   ├── home.css       (hero, carduri, sectiune intro)
│   ├── rase.css       (profile rase, trait bars)
│   ├── galerie.css    (grid masonry, filtre, lightbox)
│   └── contact.css    (formular, validare, harti)
├── js/
│   ├── main.js        (nav sticky, hamburger, fade-in)
│   ├── home.js        (parallax hero)
│   ├── rase.js        (animatii trait bars)
│   ├── galerie.js     (filtre + lightbox)
│   └── contact.js     (validare formular)
└── img/               (imagini locale - optional)
```

## Cerinte bifate
- [x] HTML, CSS, JS pur (fara framework-uri)
- [x] 4 pagini cu layout si continut diferit
- [x] Pagina Contact cu formular si validare
- [x] Design responsive (mobile, tablet, desktop)
- [x] Meniu sticky desktop
- [x] Meniu hamburger mobil
- [x] 2 fonturi Google: Playfair Display + Lato
- [x] Hero banner cu Hero Text pe pagina Home
- [x] Taguri structurale HTML5 (header, nav, main, section, article, footer)
- [x] Grupare cu `<section>`
- [x] CSS in fisiere separate
- [x] Organizare fisiere in foldere (css/, js/, img/)

## Contributii per membru
| Membru | Pagina | Fisiere modificate |
|--------|--------|--------------------|
| Membru 1 (Lider) | index.html - Acasa | index.html, css/home.css, js/home.js |
| Membru 2 | rase.html - Rase | rase.html, css/rase.css, js/rase.js |
| Membru 3 | galerie.html - Galerie | galerie.html, css/galerie.css, js/galerie.js |
| Membru 4 | contact.html - Contact | contact.html, css/contact.css, js/contact.js |

## Rulare locala
1. Copiati folderul `static-site` in directorul `www` din WAMP64
2. Porniti serverul WAMP
3. Accesati `http://localhost/static-site/` in browser
