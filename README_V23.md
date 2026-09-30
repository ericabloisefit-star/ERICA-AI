# ERICA AI V23 — PDF Import intelligente per schede a colonne

V23 aggiorna l'importatore PDF sulla base di una scheda reale ERICA: **scheda_settimanale_alessandro (2).pdf**.

## Cosa riconosce meglio
- 12 settimane separate
- 2 giorni per settimana
- layout a due colonne
- intestazioni `GIORNO 1` e `GIORNO 2`
- focus di ogni settimana
- settimane di scarico/deload
- esercizi mantenendo il nome originale del PDF
- serie, ripetizioni, MAX, cluster/rest-pause e prescrizioni miste
- note/indicazioni della riga
- righe che continuano sulla riga successiva

## Flusso
PDF → analisi del layout → W1…W12 → Giorno 1/Giorno 2 → esercizi → bozza modificabile → Salva nel cliente.

La versione mantiene la struttura ERICA AI esistente e il login Supabase. Il PDF viene elaborato nel browser tramite PDF.js; non viene inviato automaticamente a un servizio AI esterno.
