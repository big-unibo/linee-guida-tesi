# Linee guida tesi

1. Consegna dei capitoli
    - Consegnare ogni capitolo una sola volta, uno per volta
    - Prima della consegna
        - **Fare un controllo della grammatica** ed eventuali errori di battitura (per tesi in inglese Grammarly è di grande aiuto)
        - Mettere il capitolo "nel cassetto" 2-3 giorni e rileggerlo
1. Contenuti
    - La tesi non è un libro didattico: scrivere **solo** i contenuti funzionali all'attività di tesi.
        - Esempio: se la tesi si colloca in ambito BI/OLAP e l'implementazione si basa su ROLAP, va bene citare anche MOLAP e HOLAP, ma è bene approfondire solo ROLAP. E' inutile e sbagliato copia-incollare capitoli di libri di testo come "Data Warehouse. Teoria e pratica della progettazione"
1. Linguaggio
    - Evitare sempre commenti non oggettivi/superficiali/informali (o sono supportati da citazioni o non si mettono). Ad esempio: banale, semplice, facile, difficile, molto, troppo, poco, impossibile
    - Concisione: Non scrivere frasi più lunghe di *due* righe
        - Esempio No: L'idea di traiettoria si delinea nell'abilità di catturare gli spostamenti di un oggetto
        - Esempio Sì: La definizione di traiettoria è: "testo quotato" [citazione]
    - **Evitare** l'abuso di **grassetto** e *corsivo*
1. Inglesismi
    - Se le tesi è in italiano è bene scrivere in italiano e limitare l'uso dell'inglese il più possibile (e.g., "Trajectory Mining" -> "Mining di traiettorie")
        - Ovviamente non tutto può essere tradotto in italiano (e.g., clustering, mining, deploy, etc.)
    - Usare un termine inglese se questo si ripete ma spiegalo una sola volta.
    - Un acronimo in inglese rimane in inglese: GPS (Global Positioning System) e non si usa il plurale
    - La prima volta in assoluto che il termine compare scrivilo in corsivo. Esempio "I *layer* (livelli) di un GIS (*Geographic Information System*)"
1. Struttura
    - Convenzione nomi
        - Titolo: 
            - Prima lettera maiuscola in tutti i nomi, pronomi, aggettivi, verbi, avverbi
            - Tutto maiuscolo acronimi
            - In minuscolo articoli e congiunzioni 
        - Sezioni: tutto minuscolo eccetto la prima lettera e acronimi (e.g., "Questa è una sessione OLAP")
    - Abstract (sommario): singolo paragrafo tra 150 e 250 parole
    - Usare il package `cleveref` e `\Cref{}` (e non `\ref{}`) di Latex per fare riferimento a label di capitoli/sezioni/sottosezioni/immagini
    - Quando si descrive un argomento è bene averlo già introdotto. Se non indispensabili, evitare le *forword reference* (riferimento a capitoli/sezioni/sottosezioni che appaiono dopo essere referenziati)
    - Non creare sezioni con singola sottosezione
    - Non creare (sotto)sezioni lunghe meno di una pagina
    - Evitare di disperdere le informazioni: definizione, dettagli e implicazioni stanno nello stesso paragrafo
    - Esiste differenza tra `.` e `. a capo`: `. a capo` si usa per cambiare discorso
1. Citazioni e copia/incolla
    - Non citare Wikipedia (su https://scholar.google.it/ esiste un oceano di letteratura)
        - Se necessario, sfruttare Wikipedia per trovare le citazioni a paper/libri
    - Non copiare testi troppo lunghi, è meglio riassumerli ed elaborarli
    - Non copiare traduzioni troppo lunghe, è meglio riassumerle ed elaborarle
    - Esplicitare la parte di testo copiata inserendola tra virgolette e aggiungi la citazione finale
        - Esempio: "Aggiungere inglesismi random non improva le vostre skills" [[Questa è una cit]](http://www.lercio.it/ricerca-aggiungere-inglesismi-random-non-improva-le-vostre-skills/)
    - La citazione precede il `.`: Testo citato [citazione]. (e non: Testo citato. [citazione]
1. Figure:
    - Se una figura è copiata/rielaborata indicare la sorgente con apposita citazione
    - Utilizzare figure in formato vettoriale (e.g., .pdf, .svg) e non raster (e.g., .png, .jpg)
    - In caso di screenshot, attenzione alle dimensioni (in MB) della figura
1. Punteggiatura, elenchi (e coerenza)
    - No punti nei titoli
    - Non `E'` ma `È` (È = Alt + 0200)  
    - In Latex, le virgolette si fanno \`\`così'' (\` = Alt + 96) e non "così"
    - Elenchi puntati iniziano con Maiuscola, finiscono con `;` o con `.` (l'importante è usare la stessa convenzione). Di solito si usa `;` per terminare frasi di senso non compiuto, e `.` per terminare frasi di senso compiuto
    - No `...`, sì "etc." 
1. Link di riferimento per elaborato tesi https://corsi.unibo.it/magistrale/IngegneriaScienzeInformatiche/volume-pdf-e-deposito-online-dellelaborato
