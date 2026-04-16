# BrawlGrammar 🎮
### Analisi del periodo — strumento di allenamento per studenti

---

## Come caricare il sito su GitHub Pages

### Passo 1 — Crea il repository
1. Vai su [github.com](https://github.com) e accedi
2. Clicca sul + in alto a destra → New repository
3. Nome repository: brawlgrammar (tutto minuscolo, senza spazi)
4. Lascia tutto il resto come sta (Public, senza README)
5. Clicca Create repository

### Passo 2 — Carica i file principali
1. Clicca Add file → Upload files
2. Trascina index.html e README.md
3. Clicca Commit changes

### Passo 3 — Crea la cartella data/ e carica i JSON
1. Clicca Add file → Create new file
2. Nel campo nome scrivi: data/sezione1_ricercati.json
3. Apri il file JSON con un editor di testo, seleziona tutto (Ctrl+A), copia e incolla
4. Clicca Commit changes
5. Ripeti per ogni file JSON

### Passo 4 — Attiva GitHub Pages
1. Clicca Settings → Pages
2. Sotto Branch seleziona main e lascia / (root)
3. Clicca Save
4. Dopo 1-2 minuti il sito e' online: https://TUOUSERNAME.github.io/brawlgrammar

---

## Come aggiornare (aggiungere sezioni)
1. Vai sul repository → cartella data/
2. Add file → Create new file
3. Scrivi nome file (es. sezione7_sopravvivenza.json) e incolla il contenuto
4. Commit changes — il sito si aggiorna in pochi secondi

I progressi degli studenti non vengono cancellati quando aggiorni i file.

---

## Struttura dei file

brawlgrammar/
├── index.html
├── README.md
└── data/
    ├── sezione1_ricercati.json           pronto
    ├── sezione2_arraffagemme.json        pronto
    ├── sezione3_footbrawl.json           pronto
    ├── sezione4_rapina.json              pronto
    ├── sezione5_cacciastelle.json        pronto
    ├── sezione6_pezzogrosso.json         pronto
    ├── sezione7_sopravvivenza.json       in preparazione
    └── sezione8_mapmaker.json            in preparazione

---

## Sezioni

| # | Nome | Sottotitolo | Livelli | Stato |
|---|------|-------------|---------|-------|
| 1 | Ricercati | Frase semplice o complessa? | 3 | Attiva |
| 2 | Arraffagemme | Trova la proposizione principale | 3 | Attiva |
| 3 | Footbrawl | Coordinate: tipi e connettivi | 3 | Attiva |
| 4 | Rapina | Completive e relative | 4 | Attiva |
| 5 | Caccia alle stelle | Circostanziali: causale, temporale, finale | 4 | Attiva |
| 6 | Pezzo grosso | Circostanziali: consecutiva, concessiva, condizionale | 4 | Attiva |
| 7 | Sopravvivenza | Analisi completa del periodo | 4 | Presto |
| 8 | Map Maker | Costruisci il periodo | 3 | Presto |

Una sezione si sblocca solo dopo aver ottenuto Star Player (5/5) all'ultimo livello della sezione precedente.

---

Questo sito non e' affiliato a Supercell. Brawl Stars e' un marchio registrato di Supercell. Uso educativo non commerciale.
