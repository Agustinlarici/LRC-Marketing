# Processo di approvazione

Ogni contenuto attraversa un flusso a stadi. Nessuno stadio viene saltato.

## Stadi

1. **Bozza** — Content Agent + Creative Agent hanno prodotto copy e direzione visuale.
2. **In review** — il Reviewer applica la checklist a sette dimensioni (`agents/reviewer.md`).
   - **REWORK** → torna in Bozza con indicazioni precise su cosa cambiare. Non c'è limite al numero di round di rework.
   - **PASS** → passa allo stadio successivo.
3. **In attesa di approvazione umana** — il contenuto (copy + direzione visuale + template Canva indicato) viene presentato alla persona per l'approvazione finale. Solo un essere umano può approvare in modo definitivo.
4. **Approvato** — il contenuto viene registrato in `content/planned.md` con stato "Approvato" e data prevista.
5. **In produzione Canva** *(passo futuro, non ancora attivo)* — il template indicato in `templates/templates.md` viene compilato con i contenuti approvati.
6. **Pubblicato** *(passo futuro, non ancora attivo — sempre manuale per ora)* — il contenuto viene spostato in `content/published.md` e `content/content-matrix.md` viene aggiornata.

## Regole

- **Nessuna pubblicazione automatica.** Gli stadi 5 e 6 restano manuali finché non verrà esplicitamente attivata un'integrazione Canva/Instagram.
- Un contenuto non può saltare dallo stadio 2 (In review) direttamente allo stadio 4 (Approvato): l'approvazione umana è sempre richiesta anche dopo un PASS del Reviewer.
- Ogni cambio di stadio deve essere riflesso nella colonna "Status" di `content/planned.md`.
