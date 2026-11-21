# Burraco – Punteggio da foto

Web app (si usa da Safari, senza App Store). Scegli i giocatori, fotografa le carte a terra e quelle in mano: il punteggio viene calcolato da solo.

## Pubblicare su GitHub Pages
1. Crea un repository su github.com (es. `burraco`), pubblico.
2. Carica `index.html` e `icon.svg` (Add file → Upload files).
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
4. Dopo 1–2 minuti il link è `https://TUOUSERNAME.github.io/burraco/`.

## Su iPhone
1. Apri il link in Safari → Condividi → **Aggiungi a Home**.
2. In fondo alla pagina incolla la tua API key Anthropic (console.anthropic.com) e tocca Salva.
   La chiave resta solo sul tuo telefono. Non metterla mai nel codice su GitHub.

## Punteggi usati
3–7 = 5 · 8–K = 10 · Asso = 15 · 2 = 20 · Jolly = 30
Burraco pulito +200 · sporco +100 · chiusura +100 · pozzetto non preso −100
Carte a terra sommate, carte in mano sottratte. I bonus si possono correggere a mano.
