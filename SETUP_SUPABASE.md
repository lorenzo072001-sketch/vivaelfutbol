# Configurazione Supabase per VIVAELFUTBOL

Il frontend è già collegato al progetto Supabase.

## 1. Creare le tabelle

Nel progetto Supabase apri **SQL Editor**, crea una nuova query, incolla ed esegui il file `schema.sql` fornito con il progetto VIVAELFUTBOL Reference Merge.

## 2. Impostare gli URL di autenticazione

Apri **Authentication → URL Configuration** e imposta:

- **Site URL:** `https://lorenzo072001-sketch.github.io/vivaelfutbol/`
- **Redirect URL:** `https://lorenzo072001-sketch.github.io/vivaelfutbol/**`

## 3. Verifica

Apri l’app pubblicata, registra un account e conferma l’email. Poi crea un gruppo e prova l’accesso da una finestra in incognito con un secondo account.

Non inserire mai nel frontend password del database, chiavi `service_role` o chiavi `sb_secret_`.
