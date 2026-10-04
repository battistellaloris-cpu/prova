# TIDAL Event Finder

Web app mobile per importare una libreria TIDAL CSV e trovare eventi musicali compatibili con gli artisti più rappresentati nella libreria.

## Pubblicazione veloce

Questa cartella è pronta per essere pubblicata su un hosting statico (per esempio GitHub Pages, Netlify o Vercel).

Non serve un server per la prima versione.

## Ticketmaster API

La ricerca degli eventi usa Ticketmaster Discovery API. Devi ottenere una API key dal portale sviluppatori Ticketmaster e inserirla nell'app.

La chiave viene memorizzata nel localStorage del dispositivo e non viene inclusa nei file del progetto.

## Come usarla

1. Pubblica i file `index.html` e `manifest.webmanifest`.
2. Apri il link dal telefono.
3. Inserisci la API key Ticketmaster.
4. Esporta la libreria TIDAL in CSV.
5. Importa il CSV.
6. Inserisci una città oppure usa "Usa la mia posizione".
7. Imposta il raggio.
8. Premi "Trova eventi per i miei gusti".

## Nota sul matching

La prima versione costruisce il gusto musicale usando gli artisti più rappresentati nella libreria TIDAL. Non inventa generi se il CSV non li contiene.

## Prossimo livello

Si può aggiungere:
- generi e sottogeneri;
- distanza reale dall'utente;
- preferiti;
- esclusione di artisti già visti;
- calendario;
- notifiche;
- più fonti di eventi;
- un vero backend per proteggere le API key;
- installazione PWA più completa.
