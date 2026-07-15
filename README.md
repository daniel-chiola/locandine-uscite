# Locandine Uscite — Freedomtrek

App per creare le **locandine delle escursioni** e condividerle su WhatsApp e social.

Compili i campi dell'uscita, carichi una foto, e l'app genera un'immagine pronta da mandare. Niente Photoshop, niente Canva, niente account: si apre nel browser e funziona anche **senza connessione**.


---

## Cosa fa

**Genera la locandina in tempo reale.** Mentre scrivi, l'anteprima si aggiorna: quello che vedi è esattamente il PNG che otterrai.

**Si adatta al testo.** Titoli lunghi, dieci accompagnatori, note chilometriche: il layout si ridimensiona da solo e non manda mai il testo fuori dai bordi.

**Tre formati** a seconda di dove la pubblichi:
- `9:16` — Storia Instagram / stato WhatsApp (default)
- `4:5` — post Instagram/Facebook
- `1:1` — quadrato

---

## I campi

| Sezione | Cosa ci metti |
|---|---|
| **Immagine** | Foto di sfondo + fino a **due loghi** (es. Freedomtrek + FIE), affiancati in alto a sinistra |
| **Intestazione** | Nome associazione, titolo dell'uscita, località |
| **Quando & dove** | Data, ritrovo (+ bottone per cercarlo su Google Maps) |
| **Dettagli percorso** | Difficoltà (T / E / EE / EEA), dislivello, distanza, durata, traccia GPX |
| **Persone** | Referente (nome e telefono), accompagnatori (uno per riga) |
| **Chiusura** | Equipaggiamento, note, barra info in fondo |

I campi vuoti **spariscono** dalla locandina: se non metti la durata, quella casella non compare. Nessun buco, nessun trattino.

---

## Le funzioni che fanno risparmiare tempo

### Traccia GPX
Carichi il `.gpx` del giro e l'app:
- calcola **distanza** e **dislivello** e li scrive nei campi (restano modificabili)
- disegna il **profilo altimetrico** sulla locandina — o il tracciato del percorso, se il file non ha le quote

> ⚠️ Il dislivello calcolato dal GPS è una **stima**: il segnale è rumoroso e tende a gonfiare il D+. L'app liscia i dati per avvicinarsi al valore reale, ma controlla sempre il numero prima di pubblicare.

### Sfondo dei loghi
Carichi un logo su fondo bianco e l'app **toglie lo sfondo** in automatico, così il logo si appoggia sulla foto senza il rettangolo bianco intorno.

> Funziona con sfondi **a tinta piatta**. Su un logo ritagliato da una fotografia lascia aloni: in quel caso usa un PNG già trasparente, o togli la spunta "Rimuovi sfondo uniforme dei loghi".

### QR code per il punto di ritrovo
Se nel campo **Ritrovo** scrivi delle **coordinate** (es. `42.44283, 13.58593`), sulla locandina compare un **QR code**: chi lo inquadra apre la posizione su Google Maps, sia Android sia iOS.

Se scrivi solo un luogo o un orario, il QR non compare.

> Il QR è utile su carta o inquadrandolo da un secondo schermo. Chi riceve l'immagine sul proprio telefono non può inquadrare il proprio schermo: in quel caso conviene mandare il **pin posizione di WhatsApp** insieme alla locandina.

### Bottone Google Maps
Accanto al campo Ritrovo: apre Google Maps sul luogo scritto, ignorando l'orario. Serve a te per verificare il punto mentre compili. Funziona sia con nomi di posti sia con coordinate.

---

## Colori

Il tema di default è **Freedomtrek** (verde). Ci sono altri tre preset (Sentiero, Roccia, Tramonto) e, soprattutto, puoi scegliere **due colori liberi**:

- **Colore del gruppo** — l'accent: titoli, icone, dettagli
- **Colore di sfondo** — il pannello delle informazioni

L'app calcola da sola il contrasto: se scegli uno sfondo chiaro, il testo diventa scuro; il testo sopra la barra colorata passa a bianco o nero secondo il caso. **Non puoi ottenere una locandina illeggibile** giocando coi colori.

La spunta *"Barra info su sfondo chiaro"* rende la barra in fondo una tinta pastello del colore scelto: verde chiaro col verde, azzurra col blu.

---

## Salvare e condividere

**Su telefono** — i pulsanti **Salva** e **Condividi** aprono il menu di sistema, da cui scegli **"Salva su Foto"** o direttamente **WhatsApp**.

> Sul telefono il download classico non salva l'immagine nella galleria (soprattutto su iPhone): passare dal menu di sistema è l'unico modo che funziona davvero. Per questo il pulsante si comporta così.

**Su computer** — Salva scarica direttamente il file PNG.

**Se qualcosa blocca il salvataggio** (es. l'app aperta dentro un'anteprima o un contenitore), compare l'immagine a tutto schermo: tienila premuta → *Salva su Foto*, oppure tasto destro → *Salva immagine*.

---

## Installarla sul telefono

1. Apri il link nel browser (Safari o Chrome)
2. Menu **Condividi** → **Aggiungi alla schermata Home**
3. Da lì si apre come un'app vera: a schermo intero, **e funziona anche senza rete**

Tutto gira sul tuo dispositivo: le foto che carichi **non vengono inviate a nessun server**.

---
