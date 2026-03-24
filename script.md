# Script — Masterclass AI per Project Manager

---

# Capitolo 01: Introduzione all'Intelligenza Artificiale

---

## Slide apertura capitolo

Bene, iniziamo dal principio.

Prima di parlare di prompt, di ChatGPT, di strumenti e casi d'uso pratici — dobbiamo costruire un vocabolario comune. Perché una delle cose che rallenta di più i team quando si introduce l'AI in azienda è proprio questo: tutti usano le stesse parole per dire cose diverse.

Quindi prendiamoci dieci minuti per mettere le fondamenta.

---

## 01.01 — Le Categorie dell'AI

Quando sentiamo parlare di "intelligenza artificiale" tendiamo a mettere tutto nello stesso calderone. ChatGPT, i robot di Amazon, il riconoscimento facciale, i filtri di Instagram — AI. Ma non è la stessa cosa.

L'AI è un campo enorme. Esistono da decenni sistemi che rientrano sotto questo cappello: dai motori di scacchi degli anni '90 ai sistemi esperti usati in ambito medico. L'AI è qualsiasi sistema che simula funzioni cognitive umane.

Dentro l'AI c'è un sottoinsieme chiamato **Machine Learning**. Qui il cambio di paradigma è importante: invece di programmare esplicitamente ogni regola, si addestrano gli algoritmi sui dati. Il sistema impara da solo. Più dati di qualità ha a disposizione, migliori sono i risultati.

Dentro il Machine Learning c'è il **Deep Learning**, basato su reti neurali a molti strati — da qui il "deep", profondo. È questa tecnologia che ha reso possibile il riconoscimento vocale, la traduzione automatica, la guida assistita. Il Deep Learning eccelle nel trovare pattern complessi in grandi volumi di dati non strutturati: testi, immagini, audio.

Dentro il Deep Learning c'è l'**AI Generativa** — il campo che ci interessa di più oggi. I modelli generativi non si limitano a classificare o prevedere: creano contenuto originale a partire da un input in linguaggio naturale. Testo, immagini, codice, audio.

E al centro di tutto, il nucleo che alimenta strumenti come ChatGPT, Claude e Gemini: i **Large Language Model**, i modelli linguistici di grandi dimensioni. Addestrati su miliardi di testi, questi modelli hanno imparato a comprendere e generare linguaggio umano con una fluidità che fino a tre anni fa sembrava fantascienza.

---

## 01.02 — Definizione

Una definizione tecnica semplice ma precisa: l'intelligenza artificiale è la capacità di un computer o di un programma di simulare funzioni cognitive umane.

Tre funzioni in particolare:

**Apprendimento.** Un sistema AI non viene semplicemente programmato con regole fisse. Acquisisce informazioni dall'esperienza — dai dati — e migliora le proprie prestazioni nel tempo. Come un junior che diventa senior, ma in scala e velocità impossibili per un essere umano.

**Ragionamento.** Il sistema elabora le informazioni e trae conclusioni. Non segue uno script rigido: è in grado di affrontare situazioni nuove applicando ciò che ha appreso. Questo è il salto rispetto ai software tradizionali, che fanno esattamente quello per cui sono stati programmati — né più né meno.

**Risoluzione dei problemi.** Il sistema trova soluzioni ottimali in contesti complessi e si adatta al contesto. È questa capacità che lo rende utile per il PM: non esiste un modello unico per gestire un progetto, e l'AI sa navigare la complessità.

Attenzione però: simulare non significa replicare. Un LLM non "pensa" nel senso umano del termine. Sa riconoscere pattern e generare risposte statisticamente coerenti con ciò su cui è stato addestrato. Questa distinzione — tra simulazione e comprensione autentica — è fondamentale per capire quando fidarsi dello strumento e quando no. Ci torneremo.

---

## 01.03 — AI nella Storia

L'AI non è nata con ChatGPT. Ha una storia lunga oltre settant'anni — e conoscerla ci aiuta a capire perché oggi siamo arrivati a questo punto.

**1950 — Alan Turing.** Tutto comincia con una domanda filosofica: "Le macchine possono pensare?" Turing non risponde direttamente, ma propone un criterio operativo — il Test di Turing. Se una macchina riesce a sostenere una conversazione indistinguibile da quella con un essere umano, allora, per scopi pratici, "pensa". È il primo atto fondativo di tutta la disciplina.

**1997 — Deep Blue.** IBM costruisce un computer capace di battere Garry Kasparov, allora campione mondiale di scacchi. È un momento storico: per la prima volta un sistema artificiale supera il migliore esperto umano in un dominio cognitivo complesso. Non usa il Machine Learning — è ancora un sistema a regole — ma dimostra che le macchine possono eccellere dove gli umani eccellono. Il mondo nota.

**2016 — AlphaGo.** DeepMind, sussidiaria di Google, costruisce un sistema basato su Deep Learning che batte il campione mondiale di Go. Il Go è un gioco di strategia con più configurazioni possibili degli atomi nell'universo osservabile — impossibile da "risolvere" con regole esplicite. AlphaGo impara guardando milioni di partite, poi sviluppa mosse che nessun umano aveva mai considerato. I commentatori parlano di "mosse creative". Per la prima volta, il Deep Learning dimostra capacità che sembrano andare oltre la mera computazione.

**2022 — ChatGPT.** OpenAI rilascia ChatGPT il 30 novembre 2022. In due mesi raggiunge 100 milioni di utenti attivi — record assoluto nella storia dei prodotti digitali. Per la prima volta, la tecnologia AI diventa accessibile a chiunque abbia una connessione internet. Non serve saper programmare, non serve un dottorato: scrivi in italiano, ottieni una risposta utile. Questo cambia tutto. E ci porta qui, oggi.

---

# Capitolo 02: Cos'è l'AI Generativa

---

## Slide apertura capitolo

Bene. Sappiamo cos'è l'AI, sappiamo da dove viene. Adesso entriamo nel vivo.

Parliamo di AI Generativa — il sottoinsieme che ha cambiato le regole del gioco. Quella che usate quando aprite ChatGPT, Claude, Gemini. Quella che genera il testo, le immagini, il codice. Quella che, come PM, può diventare il vostro secondo cervello operativo.

Per usarla bene, però, bisogna capire come funziona. Non a livello ingegneristico — quello lo lascio agli ingegneri. Ma a livello di logica di base. Perché chi non capisce come funziona uno strumento, lo usa male. E usarla male, in certi contesti, può fare danni.

---

## 02.01 — Definizione

Partiamo dalla definizione. Semplice, diretta.

L'AI Generativa è una classe di modelli di intelligenza artificiale capaci di **creare contenuto originale** — testo, immagini, codice, audio — a partire da un input in linguaggio naturale.

Notate il verbo: creare. Non classificare. Non prevedere un valore numerico. Non rispondere sì o no. **Generare** qualcosa che prima non esisteva.

Questo è il cambio fondamentale rispetto all'AI "classica". E la chiave di tutto è nella parola "linguaggio naturale": non serve interfaccia specializzata, non serve configurare parametri. Scrivi in italiano — o in inglese, o in spagnolo — e ottieni una risposta. Questa accessibilità è ciò che ha reso lo strumento dirompente.

Il flusso è semplice: c'è un **input** — il prompt, la tua istruzione. C'è una **elaborazione** — il modello attiva i pattern che ha appreso durante il training. E c'è un **output** — il contenuto generato, pronto da usare, modificare, affinare.

---

## 02.02 — AI Tradizionale vs AI Generativa

Per capire davvero cos'è l'AI Generativa, è utile metterla a confronto con quello che c'era prima.

L'**AI tradizionale** funziona per regole. Il programmatore definisce la logica: se entra questo, esce quello. Il filtro antispam, il motore di raccomandazione di Netflix, il sistema di scoring del credito bancario — tutti sistemi brillanti, ma costruiti attorno a un dominio specifico, con input strutturati e output predeterminati. Stessa domanda, stessa risposta. Sempre.

L'**AI Generativa** funziona per pattern statistici appresi dai dati. Non le importa del dominio — scrive, analizza, traduce, programma, disegna. Non produce output prevedibili — ogni risposta è contestuale, influenzata dalla formulazione della domanda, dal tono, dal contesto. E la sua interfaccia non è un'API o una form con campi predefiniti: è **il linguaggio umano**.

Questo cambio di paradigma è enorme. Significa che non serve più costruire un'applicazione separata per ogni caso d'uso. Significa che chiunque sappia comunicare può interagire con il sistema. Il PM che sa formulare bene un prompt è più produttivo del PM che ha accesso a dieci tool specializzati ma non sa come usarli.

---

## 02.03 — Come è cambiato il lavoro

Facciamo una cosa concreta. Guardate questa slide.

A sinistra, come lavoravamo fino a ieri. A destra, come lavoriamo oggi — o meglio, come potete lavorare da domani mattina se iniziate a integrare questi strumenti.

**I report.** Ieri: appunti su OneNote, ricerca, struttura, draft, revisioni, formattazione. Due, tre, quattro ore. Oggi: dai al modello il contesto, chiedi la bozza, la ottieni in trenta secondi. Il PM non sparisce — rivede, corregge, firma. Ma il lavoro meccanico sparisce.

**I verbali.** Ieri: qualcuno prendeva appunti durante la call, poi doveva ricostruire a mente cosa si era detto, cosa era stato deciso, chi doveva fare cosa. Un'ora di lavoro post-riunione. Oggi: trascrizione automatica, sintesi, action item estratti e assegnati. In minuti.

**Le comunicazioni stakeholder.** Ieri: ogni email adattata manualmente al destinatario — tono formale per il C-level, tono operativo per il team, tono persuasivo per il cliente. Oggi: un prompt, tre versioni, scegli quella giusta.

**L'analisi rischi.** Ieri: workshop, template, brainstorming, checklist. Oggi: descrivi il progetto, chiedi un risk register iniziale, ottieni scenari e priorità come punto di partenza.

Attenzione: il punto non è che l'AI fa il lavoro al posto vostro. Il punto è che **vi libera dal lavoro meccanico** così potete dedicare il vostro tempo a quello che richiede davvero il vostro giudizio.

---

## 02.04 — Come funziona un modello generativo

Ultimo pezzo. Come funziona concretamente.

Lo spieghiamo in quattro step, e prometto che non entreremo in matematica.

**Step 1: Addestramento.** Immaginate di prendere praticamente tutto il testo scritto dagli esseri umani — libri, articoli, siti web, codice, conversazioni — e darlo in pasto a un sistema. Il modello viene esposto a miliardi e miliardi di esempi di linguaggio. Non gli vengono insegnate le regole della grammatica: le *inferisce* dai dati. Non gli viene detto cosa è giusto o sbagliato: lo *apprende* statisticamente.

**Step 2: Apprendimento.** Durante l'addestramento, la rete neurale — che è un sistema con miliardi di parametri, miliardi di "manopole" regolabili — aggiusta continuamente questi parametri per ridurre gli errori. L'obiettivo è uno solo: data una sequenza di parole, imparare a prevedere quale parola viene dopo. Semplice come obiettivo. Enormemente complesso come computazione.

**Step 3: Predizione.** Quando voi scrivete un prompt, il modello non "cerca" la risposta in un database. Calcola, token per token, quale parola è statisticamente più probabile dato il contesto. E poi il successivo. E il successivo ancora. È una macchina di predizione sequenziale.

**Step 4: Costruzione.** Il risultato è testo che si costruisce in tempo reale, parola dopo parola, seguendo i pattern appresi. Non è copiato da nessuna fonte. Non è recuperato da nessun archivio. Viene **generato** — da qui il nome.

E qui arriva la cosa più importante di questa slide, quella su cui vi chiedo di soffermarvi: il modello **non capisce**. Non nel senso in cui capisce un essere umano. Sa riconoscere pattern e predire sequenze statisticamente coerenti. È enormemente utile. Ma non ragiona, non ha intenzioni, non verifica i fatti. Genera il testo più probabile — che potrebbe essere corretto, o potrebbe essere plausibile ma sbagliato.

Questa distinzione non è filosofica. È pratica. Ci dice esattamente quando fidarci dello strumento e quando no. E ci porterà direttamente al capitolo sul mindset e i limiti.

---
