# EsercitazioneFinale_PowerBI  

**IT**  
# **Analisi e-commerce Olist Store**  
*(Anni 2016-2018, dati elaborati con PowerBI)*  

Il progetto ha riguardato l'analisi dei dati di Olist Store, un e-commerce brasiliano, attraverso la creazione di un report dinamico in Power BI. Partendo dai dataset originali (2016-2018), ho ottimizzato la struttura trasformando i dati in uno schema a stella, con tabelle fatti e dimensioni dedicate.

Durante la preparazione dei dati, ho sistemato formati e valori: recensioni convertite in numeri, ID in testo, valute uniformate (punti sostituiti con virgole) e stati federativi estesi per il corretto mapping geografico. Un'attenta pulizia ha evidenziato 775 ordini con dettagli mancanti, integrati nell'analisi complessiva.

Sono state create misure specifiche per calcolare ricavi, variazioni annue e valutazioni clienti, permettendo di visualizzare l'andamento delle vendite con filtri temporali, geografici e delle categorie merceologiche. 
Il risultato è un report interattivo che trasforma dati complessi in informazioni chiare, pronto per l'esplorazione e l'analisi strategica. Questo strumento offre anche l'opportunità di approfondire anomalie, come le vendite precedentemente menzionate (775), che, nonostante incidano solo per l'1,02% delle entrate, corrispondono a circa 163K R$. Grazie alle recensioni, è possibile verificare che la valutazione media è stata di 1,73, evidenziando così alcune criticità.

**Tecnologie utilizzate:**  

- 🔄 **Power Query** (ETL, trasformazione del dataset)  
- 📊 **PowerBI** (report interattivo) - Data modeling, DAX



**EN**  
**Olist Store E-Commerce Analysis**  
*(2016-2018 | Power BI Data Project)*  

This Power BI project analyzes sales data from Olist Store, a Brazilian e-commerce platform. Starting from raw datasets (2016-2018), I optimized the structure by implementing a star schema with dedicated fact and dimension tables.  

**Data Preparation Highlights**
  - Standardized formats:
    - Reviews → Numeric values
    - IDs → Text strings
    - Currency → Decimal standardization (replaced dots with commas)
    - State names → Full names for geographic mapping

  - Identified 775 incomplete orders (1.02% of revenue ≈ R$163K), later integrated into analysis

**Key Features**
  - Custom DAX measures for:
    - Revenue calculations
    - YoY performance comparisons
    - Customer rating analytics
  - Interactive filters for:
    - Time periods
    - Geographic regions
    - Product categories

**Insights Uncovered**
The dashboard reveals critical patterns, including:
  - Low-rated orders (avg. 1.73 stars) linked to incomplete data
  - Revenue anomalies in specific regions

**Technical Stack:**  

- 🔄 **Power Query** (ETL)
- 📊 **Power BI** (Data Modeling, DAX)
- 📈 **Star Schema Design**

