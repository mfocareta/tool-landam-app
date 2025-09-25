# Tool Landam - Tool di Classificazione per Landslide Dams

**Strumento web interattivo per la classificazione e la valutazione preliminare degli sbarramenti da frana (Landslide Dams) e dei loro effetti, sviluppato nell'ambito delle attività di progetto RETURN - LANDAM**

---

## Descrizione

**Tool Landam** è un'applicazione web statica progettata per assistere geologi, ingegneri, e operatori della protezione civile nella classificazione speditiva di eventi di sbarramento fluviale causati da frane. Attraverso una procedura guidata, il tool permette di definire un codice di classificazione standard e di ottenere una valutazione preliminare degli effetti potenziali e della suscettibilità alla formazione del lago.

Lo strumento si basa sulle metodologie e le matrici di correlazione definite nel progetto LANDAM dalle unità operative di UniChieti, Uni Urbino, Unisannio e UniPadova fornendo un output chiaro, visivo e facilmente condivisibile.

## Funzionalità Principali

-   **Classificazione Guidata:** Un percorso interattivo in 7 step per definire i parametri chiave dell'evento.
-   **Codice di Classificazione Standard:** Generazione di un codice univoco (es. `BmT3d`) che riassume le caratteristiche della diga da frana.
-   **Barcode Visuale:** Una barra cromatica che offre una rappresentazione immediata delle selezioni effettuate.
-   **Analisi degli Effetti:** Visualizzazione dettagliata dei potenziali effetti (stabilità della diga, tempi di formazione del lago, rischio di inondazione, etc.) con indicatori di rischio cromatici.
-   **Calcolo della Suscettibilità:** Determinazione della classe di suscettibilità alla formazione di un lago (da Lieve a Molto Elevata) basata su volume, velocità e probabilità.
-   **Esportazione PDF:** Possibilità di salvare l'intero report di classificazione in un file PDF per l'archiviazione e la condivisione.

## Come Utilizzare il Tool

L'applicazione è pubblicata e accessibile a tutti tramite GitHub Pages.

➡️ **Accedi al tool qui:** [**https://mfocareta.github.io/tool-landam-app/**]

L'utilizzo è semplice:
1.  Rispondi alle domande presentate in ogni passaggio.
2.  Una volta completate le 7 selezioni, il tool genererà automaticamente il report finale.
3.  (Opzionale) Inserisci un nome per la classificazione e clicca su "Salva come PDF".

## Metodologia e Fonti

La logica di classificazione e la base dati degli effetti sono state implementate a partire dai seguenti documenti di riferimento:

-   **Categorie di Intensità vs Tipologie di Frana.xlsx**
-   **Schema_landslide_dams_effetti.xlsx**

Questi schemi forniscono la base scientifica per le correlazioni tra le caratteristiche dell'evento e i suoi potenziali impatti.

## Tecnologie Utilizzate

-   HTML5
-   Tailwind CSS per lo styling
-   JavaScript (Vanilla) per la logica interattiva
-   Librerie JavaScript: `html2canvas` e `jsPDF` per l'esportazione in PDF

## Installazione Locale (per Sviluppatori)

Essendo un'applicazione puramente client-side, non è richiesta alcuna installazione complessa.
1.  Clona o scarica questo repository.
2.  Apri il file `index.html` in un qualsiasi browser web moderno.

## Autore

Sviluppato da **<Mariano Focareta / MapSat> <Lorenzo Girolamo / MapSat> <Gianna Ida Festa / MapSat>**

*Questo tool è stato concettualizzato da umani e sviluppato con il supporto dell'assistente AI Gemini*

## Licenza

Copyright © 2025, <Mariano Focareta / MapSat>. Tutti i diritti riservati.
