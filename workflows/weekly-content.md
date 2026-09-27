# Workflow settimanale

Attivato da comandi come *"Prepara i contenuti della prossima settimana."*

```
DIRECTOR
  ↓ analizza strategia (strategy/growth-phases.md, strategy/pillars.md, strategy/audience.md)
  ↓ controlla contenuti precedenti (content/published.md, content/planned.md)
  ↓ individua cosa manca (content/content-matrix.md)
  ↓ propone calendario (idee → content/planned.md, applicando la regola anti-ripetizione)
CONTENT AGENT
  ↓ scrive contenuti (hook, testo visual, caption, CTA, hashtag)
CREATIVE AGENT
  ↓ definisce visual e template (da templates/templates.md)
REVIEWER
  ↓ PASS / REWORK (checklist in agents/reviewer.md)
APPROVAZIONE UMANA
  ↓
content/planned.md (aggiornato con lo stato finale)
  ↓ (successivamente) Canva
  ↓ (successivamente) pubblicazione
```

**Nessuna pubblicazione automatica.** Il workflow si ferma all'approvazione umana; Canva e pubblicazione sono passi successivi manuali (per ora).

## Passi operativi

1. Il Director legge la fase corrente e la distribuzione target (`strategy/growth-phases.md`).
2. Il Director controlla `content/content-matrix.md` per capire quali combinazioni tema/target/angolo sono sotto-rappresentate.
3. Il Director propone un set di idee, verificandole subito contro `content/published.md` e `content/planned.md` (regola anti-ripetizione in `agents/director.md`). Le idee scartate non vengono riscritte: si cerca un angolo diverso.
4. Per ogni idea approvata dal Director, il Content Agent scrive il copy.
5. Il Creative Agent assegna un template Canva (esistente o nuovo, da registrare in `templates/templates.md`) e definisce la direzione visuale.
6. Il Reviewer applica la checklist a sette dimensioni. Se REWORK, il contenuto torna al passo 4 o 5 con indicazioni precise.
7. Dopo il PASS del Reviewer, il contenuto attende approvazione umana.
8. Solo dopo l'approvazione umana, il contenuto viene aggiornato in `content/planned.md` con lo stato definitivo e, quando pubblicato, spostato in `content/published.md` con aggiornamento di `content/content-matrix.md`.
