# Locandine Uscite

App web installabile (PWA) per creare e condividere locandine delle uscite escursionistiche. Funziona offline. Tema di default: Freedomtrek (verde).

## Uso locale
Apri `index.html` nel browser. Su telefono: menu -> Aggiungi alla schermata Home. Per salvare/condividere una locandina usa i pulsanti Salva/Condividi (su telefono passano dal menu di sistema -> Salva su Foto / WhatsApp).

## Pubblicazione su GitHub Pages
1. Crea un repo su GitHub (es. `locandine-uscite`).
2. In questa cartella:
   ```bash
   git remote add origin https://github.com/TUO-UTENTE/locandine-uscite.git
   git branch -M main
   git push -u origin main
   ```
3. Settings -> Pages -> Source: main / root. Dopo qualche minuto l'app e' online e installabile.

## Aggiornare
Dopo una modifica, incrementa `CACHE` in `sw.js` (es. locandine-v4) e fai push.
