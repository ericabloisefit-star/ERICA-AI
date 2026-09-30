# ERICA AI V17 — Password Recovery

Questa versione aggiunge un flusso completo di recupero password Supabase:
- pulsante "Password dimenticata?" nel login;
- invio del reset link verso l'URL GitHub Pages corrente;
- schermata dedicata per impostare la nuova password;
- gestione dell'evento Supabase PASSWORD_RECOVERY;
- supporto al redirect con query/hash di recovery.

Prima di usare il reset, in Supabase Authentication → URL Configuration aggiungere come Site URL e Redirect URL:
https://ericabloisefit-star.github.io/ERICA-AI/

Non inserire mai service_role/secret key nel browser.
