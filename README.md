# BrawlGrammar 🎮
### Analisi del periodo — strumento di allenamento per studenti

---

## Come caricare il sito su GitHub Pages

### Passo 1 — Crea il repository
1. Vai su [github.com](https://github.com) e accedi
2. Clicca sul **+** in alto a destra → **New repository**
3. Nome repository: `brawlgrammar` (tutto minuscolo, senza spazi)
4. Lascia tutto il resto come sta (Public, senza README)
5. Clicca **Create repository**

### Passo 2 — Carica i file
1. Nella pagina del repository appena creato, clicca **uploading an existing file**
2. Trascina o seleziona il file `index.html`
3. Clicca **Commit changes** in basso

### Passo 3 — Crea la cartella data/ e carica i JSON
GitHub non permette di creare cartelle vuote, ma puoi farlo così:
1. Clicca **Add file** → **Create new file**
2. Nel campo nome scrivi: `data/sezione1_semplice_complessa.json`
3. Apri il file JSON con un editor di testo (Blocco Note su Windows, TextEdit su Mac), seleziona tutto il testo e incollalo nell'editor di GitHub
4. Clicca **Commit changes**
5. Ripeti per `data/sezione2_arraffagemme.json`
6. Man mano che aggiungi sezioni, carica i nuovi JSON nella stessa cartella `data/`

> **Alternativa più rapida per i JSON**: clicca **Add file** → **Upload files**, ma GitHub non permette di caricare file direttamente in sottocartelle con questo metodo. Usa quindi il metodo "Create new file" come descritto sopra.

### Passo 4 — Attiva GitHub Pages
1. Nel repository, clicca **Settings** (in alto)
2. Nel menu a sinistra clicca **Pages**
3. Sotto "Branch" seleziona **main** e lascia **/ (root)**
4. Clicca **Save**
5. Dopo 1-2 minuti il sito sarà online all'indirizzo:
   `https://TUOUSERNAME.github.io/brawlgrammar`

---

## Come aggiornare il sito (aggiungere sezioni)

1. Vai sul repository su GitHub
2. Entra nella cartella `data/`
3. **Add file** → **Create new file**
4. Scrivi il nome del file (es. `sezione3_footbrawl.json`) e incolla il contenuto
5. **Commit changes** — il sito si aggiorna automaticamente in pochi secondi

> ⚠️ I progressi degli studenti (salvati in LocalStorage sul loro dispositivo) **non vengono cancellati** quando aggiorni i file. Possono continuare da dove avevano lasciato.

---

## Struttura dei file

```
brawlgrammar/
├── index.html                          ← il sito completo
└── data/
    ├── sezione1_semplice_complessa.json   ← ✅ pronto
    ├── sezione2_arraffagemme.json         ← ✅ pronto
    ├── sezione3_footbrawl.json            ← 🔜 in preparazione
    ├── sezione4_dominio.json              ← 🔜 in preparazione
    ├── sezione5_sopravvivenza.json        ← 🔜 in preparazione
    └── sezione6_mapmaker.json            ← 🔜 in preparazione
```

---

## Sezioni attive

| # | Nome | Sottotitolo | Stato |
|---|------|-------------|-------|
| 1 | Ricercati | Frase semplice o complessa? | ✅ Attiva |
| 2 | Arraffagemme | Trova la proposizione principale | ✅ Attiva |
| 3 | Footbrawl | Coordinate: tipi e connettivi | 🔒 Presto |
| 4 | Dominio | Subordinate: tipi e connettivi | 🔒 Presto |
| 5 | Sopravvivenza | Analisi completa del periodo | 🔒 Presto |
| 6 | Map Maker | Costruisci il periodo | 🔒 Presto |

---

*Questo sito non è affiliato a Supercell. Brawl Stars è un marchio registrato di Supercell. Uso educativo non commerciale.*
