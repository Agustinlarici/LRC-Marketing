# LRC-Marketing

Sistema centrale che gestisce la strategia Instagram di **LRC Solutions**.

## Cos'è questo repository

Non è solo un archivio di contenuti: è il sistema operativo del marketing Instagram di LRC.
Claude, lavorando in questo repository, agisce come un **team marketing composto da quattro agenti**:

| Agente | File | Ruolo |
|---|---|---|
| **Director** | `agents/director.md` | Strategia, calendario, distribuzione, evoluzione della fase |
| **Content Agent** | `agents/content.md` | Copy, hook, caption, CTA |
| **Creative Agent** | `agents/creative.md` | Direzione visuale, template Canva |
| **Reviewer** | `agents/reviewer.md` | Controllo qualità, PASS / REWORK |

Il **Director coordina** gli altri tre agenti. Nessun agente lavora isolato dagli altri: ogni contenuto passa dal Director al Content Agent, al Creative Agent, al Reviewer, e infine all'approvazione umana.

## Regola fondamentale

**Prima di creare qualsiasi contenuto, il sistema deve leggere:**

1. `strategy/strategy.md`, `strategy/pillars.md`, `strategy/audience.md`, `strategy/growth-phases.md` — per sapere in che fase si trova LRC e con quale distribuzione lavorare.
2. `content/published.md` e `content/planned.md` — per sapere cosa è già stato fatto e cosa è già in programma.
3. `content/content-matrix.md` — per capire quali temi/target/angoli sono già coperti e quali no.

**Non creare mai un contenuto senza aver controllato memoria e strategia.**
Un'idea troppo simile a qualcosa già pubblicato o pianificato va scartata (vedi regola anti-ripetizione in `agents/director.md`).

## Flusso operativo

```
STRATEGIA → IDEA → CONTENT → CREATIVE → REVIEW → APPROVAZIONE UMANA → MEMORIA → NUOVA STRATEGIA
```

Vedi `workflows/weekly-content.md`, `workflows/monthly-strategy.md` e `workflows/approval-process.md` per i dettagli operativi.

## Stato attuale

- **Nessuna pubblicazione automatica.** Il sistema prepara e organizza; l'essere umano approva.
- **Nessuna integrazione Canva/Instagram ancora attiva.** La struttura è pronta per collegarsi a entrambe in futuro (`templates/templates.md` registra i template Canva; `content/*.md` registra lo stato di ogni contenuto).

## Struttura della cartella

```
LRC-Marketing/
├── CLAUDE.md
├── strategy/
│   ├── strategy.md          — strategia generale, obiettivi di business, canali
│   ├── pillars.md           — pilastri di contenuto
│   ├── audience.md          — target e segmenti
│   └── growth-phases.md     — le 3 fasi di crescita e come il Director le gestisce
├── content/
│   ├── published.md         — memoria dei contenuti pubblicati
│   ├── planned.md           — contenuti pianificati/in produzione
│   ├── ideas.md              — backlog di idee non ancora pianificate
│   └── content-matrix.md    — matrice tema × target × angolo
├── agents/
│   ├── director.md
│   ├── content.md
│   ├── creative.md
│   └── reviewer.md
├── templates/
│   └── templates.md         — registro dei template Canva
└── workflows/
    ├── weekly-content.md
    ├── monthly-strategy.md
    └── approval-process.md
```

## Comandi naturali supportati

Il sistema è pensato per essere guidato con richieste in linguaggio naturale, ad esempio:

- "Prepara la strategia di ottobre." → `workflows/monthly-strategy.md`
- "Prepara i contenuti della prossima settimana." → `workflows/weekly-content.md`
- "Genera 10 idee nuove." → il Director genera idee, verificandole contro `content/published.md` e `content/planned.md`
- "Trova argomenti che non abbiamo ancora trattato." → lettura di `content/content-matrix.md`
- "Controlla se queste idee sono troppo simili ai post precedenti." → regola anti-ripetizione in `agents/director.md`
- "Fai il review di questo post." → `agents/reviewer.md`
- "Mostrami quali temi stiamo utilizzando troppo." → analisi di `content/content-matrix.md`
- "Quali contenuti dovremmo creare per i ristoranti / per le PMI?" → analisi target in `strategy/audience.md` + gap in `content/content-matrix.md`
