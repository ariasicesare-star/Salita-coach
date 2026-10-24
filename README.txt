# Salita Coach — mini-app Android

## Contenuto
- `index.html`: app con calendario, piano e checkbox.
- `manifest.webmanifest`: configurazione installabile.
- `sw.js`: cache offline di base.
- `icon.svg`, `icon-192.png`, `icon-512.png`: icone.

## Installazione Android
Per essere installabile come PWA, il sito deve essere servito via HTTPS (non basta aprire `index.html` dal file manager).

### Metodo semplice: GitHub Pages
1. Estrai lo ZIP sul computer.
2. Crea un repository GitHub nuovo (può essere pubblico).
3. Carica nella cartella principale tutti i file estratti.
4. In Settings → Pages, abilita la pubblicazione dal branch `main` e dalla cartella `/ (root)`.
5. Attendi la pubblicazione e apri l'indirizzo HTTPS ottenuto con Chrome sul telefono Android.
6. Nel menu ⋮ di Chrome scegli **Installa app** oppure **Aggiungi a schermata Home** e conferma.

### Uso
- Seleziona la settimana dal menu.
- Spunta ogni seduta completata: lo stato è salvato in `localStorage` sul dispositivo/browser.
- Usa “Esporta progressi” per fare un backup JSON.
- Non cancellare i dati del sito/browser se vuoi mantenere le spunte.
- Le spunte non si sincronizzano con Zwift o con altri dispositivi.

## Nota sul piano
I nomi dei workout Zwift possono cambiare o non comparire in ogni versione della libreria. Se non trovi un nome, scegli un workout equivalente per categoria, durata e intensità. Le potenze sono basate su FTP iniziale 200 W e vanno aggiornate dopo un test FTP.
