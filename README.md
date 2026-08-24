# Sito web — Ristorantino Da Enzo

Sito statico (HTML/CSS/JS puro, nessuna build necessaria) per il ristorante
**Ristorantino Da Enzo**, Marina di Montemarciano (AN).

## File

- `index.html` — struttura della pagina
- `style.css` — stile (palette mare/chalkboard, font Fraunces + Work Sans + Space Mono)
- `script.js` — menu mobile, animazioni di comparsa allo scroll

## Pubblicare su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `da-enzo-sito`).
2. Carica questi 3 file (`index.html`, `style.css`, `script.js`) nella root del repository.
3. Vai su **Settings → Pages**.
4. In **Source**, seleziona il branch `main` e la cartella `/ (root)`.
5. Salva: dopo qualche minuto il sito sarà online su
   `https://<tuo-utente>.github.io/da-enzo-sito/`.

Se vuoi un dominio personalizzato (es. `ristorantedaenzo.it`), in **Settings → Pages**
c'è il campo "Custom domain": basta configurare i record DNS del dominio come
indicato da GitHub.

## Cose da verificare / completare

Le informazioni sono state prese dalla scheda Google Maps del locale, che
non riporta l'orario settimanale completo:

- **Orari**: risultava solo "chiuso il lunedì, apre martedì alle 12". Nella
  sezione "Orari & contatti" ho lasciato una nota che invita a chiamare per
  conferma — se hai gli orari precisi, aggiornali nella tabella `.hours-table`
  in `index.html`.
- **Foto**: il sito non usa foto reali del locale (per non inventare immagini
  non autorizzate). Se hai foto di piatti o dell'ambiente, posso aiutarti a
  inserirle al posto degli elementi grafici attuali.
- **Menu completo**: sono riportati solo i 3 piatti segnalati come "popolari"
  su Google. Se hai il menu completo, possiamo aggiungere una sezione dedicata.
