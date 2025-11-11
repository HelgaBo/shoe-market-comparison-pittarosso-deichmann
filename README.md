# 👟 Analisi Comparativa PittaRosso vs Deichmann  

Questo progetto realizza un’**analisi comparativa dei prodotti offerti da PittaRosso e Deichmann**, due tra i principali retailer di calzature in Italia.  
Attraverso tecniche di **web scraping e data analysis**, vengono confrontati **prezzi, brand, categorie e distribuzione per genere**, con l’obiettivo di comprendere le **strategie di assortimento e posizionamento di mercato** dei due marchi.

---

## 🧠 Panoramica del progetto  

L’analisi è stata sviluppata interamente in **Python**, integrando librerie per l’estrazione, la pulizia e la visualizzazione dei dati.  
Il progetto genera dataset confrontabili per entrambe le piattaforme e produce **grafici e tabelle** che mettono in evidenza le principali differenze di mercato.  

---

## 🛠️ Tecnologie e strumenti  

- **Python 3**  
- **Requests** → per il download delle pagine web  
- **BeautifulSoup (bs4)** → per il parsing e l’estrazione dei dati HTML  
- **Pandas** → per la pulizia, trasformazione e analisi dei dataset  
- **CSV** → per la memorizzazione strutturata dei risultati  
- **Matplotlib / Seaborn** → per la creazione di visualizzazioni comparative  

---

## ⚙️ Metodologia  

1. **Raccolta dei dati**  
   - Estrazione dei prodotti da ciascun sito con:
     - Nome  
     - Marca  
     - Prezzo (intero o scontato)  
     - Categoria  
     - Genere  
   - Esportazione in file CSV separati:
     - `pittarosso_prodotti.csv`  
     - `deichmann_prodotti.csv`  

2. **Pulizia e normalizzazione**  
   - Uniformazione dei dati (categorie, formati prezzo, denominazioni brand) per rendere i due dataset comparabili.  

3. **Analisi comparativa**  
   - Confronto diretto su:
     - Prezzo medio per categoria e brand  
     - Presenza e varietà dei brand  
     - Distribuzione dei prodotti per genere  
     - Differenze di prezzo e scontistica  

4. **Visualizzazione dei risultati**  
   - Grafici e tabelle che evidenziano pattern e scostamenti tra i due retailer.  

---

## 🎯 Obiettivi principali  

- Valutare la **competitività dei prezzi** tra PittaRosso e Deichmann.  
- Identificare **differenze di assortimento** e **strategie di brand positioning**.  
- Offrire **insight utili** per analisi di mercato e strategie commerciali.  
