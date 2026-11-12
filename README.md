# Objednávky MR / CT

Osobní webová aplikace pro objednávání MR a CT obstřiků: fronta pacientů, zpracování přepisu hovoru (Soniox → Claude), archiv termínů a předvyplněné maily pacientům.

- Frontend: `index.html` (statická stránka, GitHub Pages)
- Backend: Supabase (databáze s RLS, edge funkce `vytahni-terminy`)

Repozitář neobsahuje žádná data ani tajné klíče. Klíč v `index.html` je veřejný (publishable) klíč Supabase; přístup k datům chrání přihlášení a RLS.
