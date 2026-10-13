# Sito personale - Francesco Ingallati

Sito personale di presentazione, progetto finale del corso HTML e CSS di start2impact.

**Online:** https://francescoingallati.github.io

## Cos'è
Un sito di tre pagine (Home, CV, Contatti) che presenta il mio percorso verso l'AI engineering, le competenze e i progetti che sto portando avanti con i miei studi. Il form di contatto è funzionante tramite EmailJS.

## Tecnologie
- HTML semantico
- Sass (organizzato in partial, compilato in CSS)
- Bootstrap 5 (navbar)
- CSS Grid e Flexbox per i layout
- Responsive mobile-first
- EmailJS per il form di contatto
- Pubblicato su GitHub Pages

## Come compilare il Sass
I file sorgente sono in `scss/`. Il file principale `scss/style.scss` importa i partial e viene compilato in `css/style.css`.
Per compilare: usare un compilatore Sass (es. l'estensione Live Sass Compiler di VS Code) sul file `scss/style.scss`.

## Struttura
- `index.html`, `cv.html`, `contatti.html` - le pagine
- `scss/` - i sorgenti Sass (partial)
- `css/style.css` - il CSS compilato
- `img/` - immagini e favicon