# La Panetteria

Landing page vetrina per una panetteria artigianale, realizzata con HTML, Bootstrap e Sass.

Il progetto nasce come esercizio frontend per costruire una homepage completa, responsive e visivamente curata per una piccola attività locale. L'obiettivo principale è usare Bootstrap attraverso Sass, personalizzando il tema e i componenti senza scrivere troppo CSS manuale.

## Descrizione

**La Panetteria** è un sito vetrina statico pensato per presentare online una panetteria o un laboratorio artigianale.

La pagina include una struttura da sito reale: navbar responsive, menu mobile offcanvas, hero section, sezioni informative, area prodotti, contenuti dedicati al laboratorio, caroselli e area contatti. Il layout comunica un'identità calda e artigianale, con una palette basata su beige, marrone, oro e toni chiari.

Il progetto è adatto come esempio di landing page per piccole attività locali, negozi, artigiani o attività food che hanno bisogno di una presenza online semplice ma professionale.

## Funzionalità principali

- Homepage vetrina responsive
- Navbar con menu mobile offcanvas
- Hero section con immagine di copertura e call to action
- Sezioni dedicate a panificazione, prodotti e laboratorio
- Card prodotto con immagini uniformi
- Caroselli Bootstrap per contenuti dinamici
- Palette colori custom integrata nel tema Bootstrap
- Font personalizzati tramite Google Fonts
- CSS generato da Sass

## Tech stack

- **HTML5**
- **Bootstrap 5**
- **Sass / SCSS**
- **CSS3**
- **JavaScript / Bootstrap Bundle**
- **Font Awesome**
- **Google Fonts**

## Struttura del progetto

```text
laPanetteria/
├── package.json
├── README.md
└── src/
    ├── dist/
    │   ├── index.html
    │   ├── css/
    │   │   └── style.css
    │   ├── js/
    │   │   └── script.js
    │   └── assets/
    └── scss/
        ├── style.scss
        ├── _colors.scss
        ├── _fonts.scss
        ├── _customs.scss
        ├── _hero.scss
        ├── _main.scss
        └── _caroselli.scss
```

## Installazione

Installa le dipendenze:

```bash
npm install
```

Compila il CSS da Sass:

```bash
npm run build-css
```

Durante lo sviluppo puoi avviare il watch di Sass:

```bash
npm run watch-css
```

## Script disponibili

| Script | Descrizione |
| --- | --- |
| `npm run build-css` | Compila `src/scss/style.scss` in `src/dist/css/style.css` |
| `npm run watch-css` | Osserva le modifiche SCSS e ricompila automaticamente il CSS |

## Obiettivo didattico

Questo progetto è stato sviluppato per fare pratica con:

- layout responsive con Bootstrap;
- personalizzazione del tema Bootstrap tramite Sass;
- organizzazione dei file SCSS in moduli separati;
- costruzione di una landing page statica completa;
- uso di componenti Bootstrap come navbar, offcanvas, card e carousel.

## Descrizione per portfolio

**La Panetteria** è una landing page vetrina progettata per rappresentare online una panetteria artigianale. Il progetto simula un sito reale per una piccola attività locale, con una homepage responsive, una hero section d'impatto, sezioni dedicate ai prodotti, al laboratorio e alle informazioni principali per il cliente.

L'interfaccia è costruita con Bootstrap e personalizzata tramite Sass, con l'obiettivo di modificare colori, font e componenti del framework mantenendo il codice pulito e ordinato. La palette calda e l'uso di immagini e sezioni promozionali aiutano a comunicare un'identità visiva coerente con il mondo della panificazione artigianale.

## Stato del progetto

Progetto frontend statico completato come landing page dimostrativa.

## Autore

Giorgio Gambelli  
GitHub: [joxDev12](https://github.com/joxDev12)
