# Linkcelerate · POC Prototype (V4)

Prototipo interattivo di Linkcelerate, il CRM personale per il networking professionale.
Sito statico: nessuna build, nessuna dipendenza da installare.

## Pubblicazione su GitHub Pages

1. Crea un repository (es. `linkcelerate`) e carica **tutto il contenuto di questa cartella** nella root, incluse la cartella `vendor/` e il file `.nojekyll`.
2. Vai su **Settings → Pages**.
3. In *Build and deployment* scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
4. Dopo 1-2 minuti il sito è online su `https://<tuo-utente>.github.io/linkcelerate/`.

## Struttura

```
index.html              prototipo completo
vendor/lucide.min.js    icone (Lucide 0.344.0, ISC)
vendor/leaflet/         mappa (Leaflet 1.9.4, BSD-2)
.nojekyll               disattiva Jekyll su GitHub Pages
```

## Dipendenze esterne residue

Font (Google Fonts), tile della mappa (CARTO) e foto demo (randomuser.me) restano remoti.
Se non caricano, il prototipo continua a funzionare con font di sistema, iniziali al posto delle foto e mappa senza sfondo.
