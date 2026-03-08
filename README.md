# Production Lot Optimizer

Strumento web per l'ottimizzazione dei lotti di produzione nell'industria medicale (prodotti incontinenza).

## Funzionalità

- **Setup Dati** — Configurazione linee produttive e articoli con logiche MTS/MTO/SS/Promo. Import/export CSV.
- **Ottimizzazione EBQ** — Calcolo Economic Batch Quantity adattato per logica gestionale, OEE e scarti.
- **Sequenza Produzione** — Sequenza ottimizzata per famiglia prodotto, minimizza changeover. Visualizzazione utilizzo linea.
- **Analisi Costi** — Breakdown holding vs setup per articolo e per logica gestionale.
- **Simulatore What-If** — Variazione domanda con slider ±50%, analisi sensitività, confronto scenari.

## Utilizzo

Apri `index.html` in qualsiasi browser moderno. Nessuna installazione richiesta.

## Deploy

Il progetto è deployato su Vercel con deploy automatico ad ogni push su `main`.

## Tecnologie

- HTML5 + CSS3 + JavaScript vanilla
- Chart.js (CDN) per i grafici
- Algoritmo EBQ (Economic Batch Quantity) per ottimizzazione lotti
