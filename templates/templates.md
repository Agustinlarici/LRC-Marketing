# Registro Template Canva

Registro dei template Canva utilizzati per la produzione visuale. Il Creative Agent (`agents/creative.md`) preferisce sempre un template esistente + visual variabile, piuttosto che un layout nuovo ogni volta.

Per ogni template: Nome, ID Canva, Tipo, Target, Pillar, Struttura, Elementi modificabili, Elementi da NON modificare, Note visuali.

**Non inventare ID Canva.** Lasciare vuoto finché non disponibile.

---

## Instagram Brand / LRC (chiaro, degradé)

- **Nome:** Instagram Brand / LRC
- **ID Canva / Link:** https://canva.link/sj8y8oludfihf0b
- **Tipo:** Post feed (template principale del brand — variante chiara)
- **Target:** trasversale (PMI, Ristoranti, Aziende/Industria)
- **Pillar:** trasversale
- **Struttura:** hook in evidenza + sfondo con degradé pastello molto tenue (celeste/rosa/bianco) + accento blu + forma astratta minimale
- **Elementi modificabili:** testo hook, testo visual secondario, immagine/icona astratta, eventuale statistica
- **Elementi da NON modificare:** palette colori (degradé chiaro + blu di marca), stile tipografico, impostazione minimale/premium; il degradé deve restare discreto — mai diventare protagonista del design
- **Note visuali:** minimalista, premium, degradé tenue, blu, forme astratte — mai robot/circuiti/hologrammi/stock photo (vedi lista completa in `agents/creative.md`)
- **Copy principale del template:** *"La tecnologia che semplifica il tuo lavoro."*
- **Usato in:** POST 002 (uso diretto, senza illustrazione)

---

## Instagram Brand / LRC — Presentazione/Lista

- **Nome:** Presentazione/Lista (variante di Instagram Brand / LRC, chiara con degradé)
- **Design di riferimento (Canva):** https://www.canva.com/d/doOFe1gUJldkALB (POST 001)
- **Tipo:** Post feed — elenco di posizionamento
- **Target:** Trasversale
- **Pillar:** Trasversale / Awareness
- **Struttura:** riga scura con elenco puntato (es. "Software · Intelligenza Artificiale · Automazione") + riga di chiusura blu accento più grande
- **Elementi modificabili:** testo delle due righe, dimensione font in base alla lunghezza, illustrazione superiore
- **Elementi da NON modificare:** palette colori, font, impostazione minimale
- **Note visuali:** stessa identità del template principale, solo layout adattato a più elementi in elenco

---

## Instagram Brand / LRC — Domanda/Problema

- **Nome:** Domanda/Problema (variante di Instagram Brand / LRC, chiara con degradé)
- **Design di riferimento (Canva):** https://www.canva.com/d/aPKz3bsXtL3Pxaa (POST 003) — stessa struttura usata in https://www.canva.com/d/bywoHzfZ3gxOFZ6 (POST 005)
- **Tipo:** Post feed — problema/domanda al pubblico
- **Target:** trasversale (usato finora per PMI e Ristoranti)
- **Pillar:** Automazione (finora)
- **Struttura:** linea sottile blu orizzontale sopra il testo (firma visiva di questa famiglia) + riga scura breve + riga blu accento più lunga con la domanda
- **Elementi modificabili:** testo delle due righe, illustrazione sotto la linea
- **Elementi da NON modificare:** la linea blu sottile, palette colori, font
- **Note visuali:** stessa identità del template principale; la linea sottile distingue visivamente i post "problema" dagli altri

---

## Instagram Brand / LRC — Scuro con bagliore

- **Nome:** Scuro con bagliore (variante scura di Instagram Brand / LRC)
- **Design di riferimento (Canva):** https://www.canva.com/d/2ap2nyyWlKdB6Zd (POST 004)
- **Tipo:** Post feed — variante a sfondo quasi nero con bagliore blu radiale
- **Target:** trasversale
- **Pillar:** usato per Intelligenza Artificiale (POST 004)
- **Struttura:** sfondo quasi nero (#030303) con due immagini di bagliore/luce blu sovrapposte (una in alto, una specchiata in basso, stesso asset ruotato 180°) che creano un effetto radiale; prima riga in blu acceso (#2A80FF), seconda riga in bianco (#FAFCFF); wordmark "LRC" blu acceso, "IT Solutions" bianco; URL bianco
- **Elementi modificabili:** testo delle due righe, illustrazione aggiuntiva
- **Elementi da NON modificare:** le due immagini di bagliore e la loro posizione (creano l'effetto radiale); il blu acceso resta l'unico accento oltre al bianco — mai introdurre nero come testo o altri colori
- **Note visuali:** usata per alternare ritmo visivo nel feed su un post di impatto (es. IA); non va usata per troppi post di fila per non perdere l'effetto

---

## Stile illustrazioni: "code card" piatta

- **Nome:** Code card (illustrazione, non un template di post a sé)
- **Aggiunta il:** 28/09/2026, dopo vari tentativi (forme astratte generiche, mockup 3D con robot, finestra scura stile IDE) scartati dall'utente come poco premium o troppo affollati.
- **Aspetto:** card chiara e piatta (NON 3D), bordi arrotondati, leggero drop shadow, su sfondo con pattern di puntini chiaro. Dentro: etichetta file in alto in grigio monospace (es. "code.ts") + un riquadro bianco con numero di riga a sinistra e una riga di codice, con la parola chiave in un colore tenue viola/blu e la stringa/valore in blu di marca (#0A46D0). Stile developer-tool minimale (tipo Linear/Vercel), non finestra IDE scura.
- **Quando usarla:** come illustrazione sotto al testo (non sopra) nei post dove ha senso mostrare "il prodotto" in modo concreto ma elegante — es. POST 001.
- **Esempio di prompt generazione immagine (Canva AI):** "Clean flat UI mockup illustration, light and airy, NOT 3D. A light gray rounded card floating above a very subtle light dot-grid background, soft drop shadow. Inside the card, a filename label in small gray monospace text at the top. Below it, a white rounded inner box containing one line of code in dark monospace font: a small gray line number in the left gutter, then the code with the keyword in a soft purple/blue color and the key string/value in brand blue (#0A46D0). Minimal, precise, modern developer-tool aesthetic like a Linear or Vercel product screenshot. No other elements, no people, no logos. Square 1:1 composition, generous white space around the card."
- **Usato in:** POST 001 (`return "soluzioni su misura";`)
- **Scartato per POST 001:** forme astratte generiche (blob senza significato), mockup 3D robot+monitor (troppo elementi/cavo desprolijo), finestra codice scura stile IDE sola (bien pero se prefirió la versión clara/piatta).

## Stile illustrazioni: 3D minimale premium (opzionale, ammesso)

Ammesso anche uno stile diverso, più "oggetto 3D flottante" (monitor, dispositivo, o anche un robot stilizzato — vedi aggiornamento in `agents/creative.md`), sempre con: forme arrotondate, materiali bianco opaco, ombre morbide, accenti blu/celeste, sfondo bianco puro, composizione centrata, nessun elemento superfluo. Da valutare caso per caso con l'utente prima di applicarlo su più post — non è ancora lo standard, è un'alternativa.

## Come aggiungere un nuovo template

1. Il Creative Agent propone il nuovo template quando nessuno esistente è adatto.
2. Registrarlo qui con tutti i campi (anche vuoti se non ancora disponibili).
3. Una volta creato in Canva, aggiornare l'ID Canva.
