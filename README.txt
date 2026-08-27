GC DESIGN — Revisione Work/About

FILE DA SOSTITUIRE
- index.html
- about.html
- cv.html
- contact.html
- jojob.html
- scss/main.scss
- css/main.css
- js/main.js

ASSET GIÀ PREVISTI
assets/img/work/last-minute-cover.webp
assets/img/work/orizon-cover.webp
assets/img/work/lookbook-cover.webp

assets/pdf/last-minute-sotto-casa.pdf
assets/pdf/orizon-brand-guidelines.pdf
assets/pdf/lookbook-copywriting.pdf

Asset Jojob usati:
assets/img/jojob/jojob-home-desktop.png
assets/img/jojob/jojob-criticita-opportunita.png
assets/img/jojob/jojob-user-journey-as-is.png
assets/img/jojob/jojob-user-journey-to-be.png
assets/img/jojob/jojob-evidenza-critica-accessibilita.png
assets/img/jojob/jojob-user-flow-desktop.png
assets/img/jojob/jojob-wireframe-home-desktop.png
assets/img/jojob/jojob-wireframe-home-mobile.png
assets/img/jojob/jojob-design-system.png
assets/img/jojob/jojob-componenti-ui-mobile.png
assets/video/home-hero-jojob-poster.webp
assets/video/home-hero-jojob.webm
assets/video/home-hero-jojob.mp4

NOTA
portfolio.html non viene più usato dalla navigazione principale. Non cancellarlo subito:
tienilo finché non hai verificato che tutto funzioni.

Bootstrap 5.3.3 è caricato via CDN. Il sito continua a usare soprattutto SCSS/CSS
personalizzato; Bootstrap viene usato in modo circoscritto per alcune utility.

Open Graph è già inserito. Quando pubblicherai con GitHub Pages, conviene aggiungere
anche og:url e trasformare og:image in un URL assoluto.

Il form Contact resta una demo e non invia messaggi finché non colleghi EmailJS
o un altro servizio.


IMPORTANTE — ASSET
I PDF e le cover devono stare DENTRO la cartella assets del progetto GC Design
(quella allo stesso livello di index.html), non nella cartella Start2Impact esterna.

Percorsi attesi:
GC-DESIGN/
  index.html
  assets/
    pdf/
      last-minute-sotto-casa.pdf
      orizon-brand-guidelines.pdf
      lookbook-copywriting.pdf
    img/
      work/
        last-minute-cover.webp
        orizon-cover.webp
        lookbook-cover.webp


V3
- About > Approccio corretto: niente più testo stretto parola per parola.
- Il titolo a sinistra resta sticky su desktop e accompagna lo scroll della sezione.
- Reveal on scroll più morbido.
- Home aggiornata con assets/img/jojob/jojob-cover.png.


ULTIME MODIFICHE
- Home: CTA About me / Contattami ridisegnate come pill buttons più moderne e distanziate.
- Contact: informazioni e form ora sono impilati verticalmente.
- Le informazioni sono organizzate in una griglia orizzontale su desktop e in colonna su mobile.


JOJOB — NUOVA STRUTTURA
- Racconto alleggerito.
- Discovery, Accessibilità, Wireframing e UI Design sono integrati nel processo.
- Ogni fase contiene due card cliccabili verso i PDF.
- Le cover previste sono in assets/img/jojob/covers/.
- I PDF previsti sono in assets/pdf/jojob/.
- Le vecchie immagini più confuse sono state rimosse dal racconto principale.
