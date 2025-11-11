# 👟 Analisi Comparativa PittaRosso vs Deichmann

Questo progetto confronta i **prodotti di due grandi catene di calzature — PittaRosso e Deichmann** — per analizzare differenze di prezzo, brand, categorie e distribuzione per genere.  
L’obiettivo è comprendere le **strategie di assortimento e posizionamento di mercato** dei principali retailer italiani nel settore delle scarpe.

---

## 🛠️ Tecnologie usate

- **Python 3**
- **Requests** → per scaricare le pagine web  
- **BeautifulSoup (bs4)** → per estrarre i dati dai siti  
- **Pandas** → per analizzare e confrontare i dataset  
- **CSV** → per salvare i risultati  
- **Matplotlib / Seaborn** → per creare visualizzazioni comparative

---

## ⚙️ Funzionamento

1. **Estrazione dei dati**
   - Per ciascun sito vengono raccolti:
     - Nome prodotto  
     - Marca  
     - Prezzo (intero o scontato)  
     - Categoria  
     - Genere  
   - I dati vengono salvati in file CSV separati:
     - `pittarosso_prodotti.csv`
     - `deichmann_prodotti.csv`

2. **Pulizia e normalizzazione**
   - I dataset vengono uniformati per consentire il confronto diretto (es. categorie, formati prezzo).

3. **Analisi comparativa**
   - Confronto tra:
     - Prezzo medio per categoria e brand  
     - Presenza dei brand nei due cataloghi  
     - Distribuzione dei prodotti per genere  
     - Range di prezzo e sconti

4. **Visualizzazioni**
   - Grafici e tabelle per evidenziare le differenze principali.

---

## 🎯 Obiettivi

- Analizzare la **competitività dei prezzi** tra retailer.  
- Identificare **differenze di assortimento** e brand più diffusi.  
- Fornire insight utili per **strategie commerciali o studi di mercato**.
