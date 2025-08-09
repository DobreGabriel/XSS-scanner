# XSS-scanner

## Descrizione
Scanner XSS educativo progettato **esclusivamente** per testare vulnerabilità XSS su ambienti locali o di laboratorio (es. OWASP Juice Shop).  

##  Requisiti
- Node.js ≥ 16
- npm o yarn
- Docker (opzionale, per Juice Shop)

## Installazione
```bash
npm install
```

## Uso
1. Avvia un target vulnerabile locale:
   ```bash
   docker run --rm -p 3000:3000 bkimminich/juice-shop
   ```
2. Esegui lo scanner:
   ```bash
   npm start
   ```

## Output
Report JSON in `xss-edu-report.json`.

## Checklist di sicurezza
- [ ] Solo su localhost/127.0.0.1
- [ ] Ambiente isolato
- [ ] Target di test autorizzati
- [ ] Nessuna connessione esterna
- [ ] Log salvati
- [ ] Aggiornamenti regolari

##  Avvertenze
L’uso improprio può essere illegale. Questo progetto è solo per scopi educativi.
