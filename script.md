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

# Capitolo 03: Tecniche Base di Prompt Engineering

---

## Slide apertura capitolo

Bene. Sappiamo cos'è l'AI generativa, sappiamo come funziona. Adesso arriva la parte pratica. Quella che potete portare in ufficio domani mattina.

Parliamo di prompt engineering. E lo dico subito: il nome è un po' ingannatore. "Engineering" fa pensare a qualcosa di tecnico, riservato agli sviluppatori. Non è così. È comunicazione. È la capacità di parlare con uno strumento in modo che lo strumento vi risponda nel modo che volete.

Questa è la skill che separa chi usa l'AI in modo trasformativo da chi la usa e rimane deluso. Non è una questione di quale tool usate — ChatGPT, Claude, Gemini, poco cambia. È una questione di come li usate.

---

## 03.01 — Cos'è il Prompt Engineering

Definiamo il campo. Semplice, preciso.

Il prompt engineering è la disciplina di **progettare input efficaci** per ottenere output di qualità da un modello AI. Non si tratta di trovare parole magiche o trucchi segreti. Si tratta di applicare la stessa chiarezza che usereste in un briefing con un collaboratore nuovo — uno molto capace, ma che non sa nulla del vostro contesto.

Pensateci: se assumete un consulente esperto e il primo giorno gli dite "fai qualcosa di utile", cosa ottenete? Niente di buono. Ma se gli date il contesto, il progetto, l'obiettivo, il formato in cui volete il risultato — ottenete qualcosa di valore.

L'LLM è esattamente questo: un collaboratore straordinariamente capace, ma completamente privo di contesto sul vostro lavoro. Il prompt engineering è il briefing.

Perché questo conta per il PM in modo specifico? Perché il PM è il punto di integrazione tra tutte le parti di un progetto. Sa il contesto. Sa cosa serve. Sa a chi serve. Ha esattamente le informazioni che il modello ha bisogno di ricevere per dare risposte utili. Il PM che padroneggia il prompt engineering ha un moltiplicatore di produttività che i suoi colleghi non hanno.

---

## 03.02 — Prompt Deboli vs Prompt Efficaci

Facciamo un confronto diretto. Guardare esempi concreti vale più di qualsiasi teoria.

A sinistra avete un prompt debole. È il tipo di prompt che la maggior parte delle persone scrive la prima volta che apre ChatGPT: **"Scrivimi un post."** Sembra una richiesta ragionevole. Ma per il modello è quasi vuota.

L'AI non sa quale piattaforma, quale argomento, quale tono, per chi, quanto lungo. Il risultato sarà inevitabilmente generico — e vi convincerà che lo strumento non funziona. Il problema non è lo strumento.

A destra avete lo stesso caso, riformulato: **"Scrivi un post LinkedIn per promuovere un webinar gratuito sulla sostenibilità in azienda. Target: manager di PMI italiane. Max 200 parole, stile professionale ma accessibile."**

Adesso il modello sa dove pubblica, qual è il tema, chi leggerà il post, quanto deve essere lungo e con quale registro. In dieci secondi avete una bozza professionale, pronta da rifinire.

La differenza non è tecnica. È la stessa differenza tra un briefing buono e uno cattivo.

---

## 03.03 — Checklist per Prompt Efficaci

Rendiamo questo operativo. Quattro ingredienti. Non servono sempre tutti e quattro — dipende dalla complessità del task. Ma ognuno che aggiungete migliora l'output.

Questa lista viene direttamente dalle linee guida di Anthropic e OpenAI — i team che costruiscono i modelli che usate ogni giorno.

**01 — Compito.** Il verbo è fondamentale. "Scrivi", "analizza", "identifica", "sintetizza", "confronta" — ogni verbo orienta il modello verso un tipo di output diverso. Siate specifici: "scrivi una bozza" è diverso da "elenca i punti chiave".

**02 — Contesto.** Tutto quello che il modello non può sapere da solo: il progetto, il settore, la fase, il team, il cliente, il vincolo. Più contesto rilevante date, più la risposta sarà pertinente. Non abbiate paura di essere prolissi in questa parte.

**03 — Formato.** Come volete l'output? Tabella, elenco puntato, testo continuo, massimo X parole, in italiano formale, in tono diretto? Senza questa indicazione, il modello sceglie da solo — e spesso sceglie in modo sbagliato per il vostro uso specifico.

**04 — Vincoli.** Cosa non deve fare. "Evita tecnicismi." "Non usare linguaggio commerciale." "Non fare assunzioni su dati che non ti ho fornito." I vincoli sono spesso la parte più trascurata, e sono quelli che evitano le sorprese più fastidiose.

Usate questa checklist come base di lavoro. Con il tempo diventerà automatica.

Una nota: il ruolo — "sei un esperto di risk management", "sei un responsabile comunicazione" — non è in questa lista di base. È una tecnica potente, e la vedremo nel prossimo capitolo come tecnica dedicata. Per ora, quattro ingredienti. Partite da qui.

---

## 03.04 — Il Concetto di Contesto

C'è un concetto tecnico che devo spiegarvi, perché cambia il modo in cui usate questi strumenti. Si chiama **context window** — la finestra di contesto.

Ogni volta che aprite una conversazione con un modello, c'è uno spazio di lavoro — come un foglio bianco molto grande. In quello spazio il modello legge tutto: le vostre istruzioni, i documenti che allegate, tutta la storia della conversazione fino a quel momento. Elabora tutto insieme, ogni volta che rispondete.

Questo spazio non è infinito. Modelli diversi hanno finestre di contesto diverse. Ma il principio è lo stesso: più informazioni rilevanti ci mettete dentro, migliore sarà la risposta.

Cosa mettere nel contesto? La vostra posizione e il destinatario dell'output. Il progetto: settore, obiettivo, fase, stakeholder chiave. I documenti rilevanti: brief, verbali, dati di sprint. Il tono e il pubblico dell'output atteso.

E guardate il confronto a destra. "Analizza i rischi del progetto." È un compito. Ma senza contesto, il modello non sa di quale progetto, in quale settore, con quale team, con quali vincoli. La risposta sarà generica.

"Progetto ERP, team 5 persone, go-live Q3, budget 180k. Identifica i 3 rischi critici in formato tabella." — stessa richiesta di base, ma adesso il modello ha qualcosa su cui lavorare. La risposta sarà specifica, strutturata, utilizzabile.

Il contesto non è decorativo. È il carburante del prompt.

---

## 03.05 — Il Contesto in Azione

Chiudiamo il capitolo con due esempi reali. Non semplificati. Prompt che potreste scrivere domani mattina.

Guardateli e notate la struttura cromatica: il giallo è il contesto — le informazioni di progetto che solo voi potete dare. Il bianco è il compito — cosa deve fare il modello. Il grigio è il formato e i vincoli — come deve rispondere.

**Primo esempio: analisi dei rischi.** Il contesto arriva prima del compito: migrazione CRM, quattro sviluppatori, go-live a cinque settimane, trenta utenti finali. Solo dopo arriva il compito: identifica i tre rischi critici. E poi il formato: tabella con quattro colonne — Rischio, Probabilità, Impatto, Azione — in italiano. Trenta parole di prompt, output professionale in dieci secondi.

**Secondo esempio: aggiornamento al comitato direttivo.** Stessa struttura. Il contesto descrive la situazione reale del progetto — sistema di ticketing, tre persone, quattro mesi, settanta percento completato, ritardo di due settimane per una causa esterna su un'API. Il compito è scrivere l'aggiornamento. I vincoli definiscono il tono e la lunghezza — professionale, rassicurante, centoventi parole, con una proposta di recupero entro fine mese.

Notate una cosa: in nessuno dei due prompt c'è "sei un esperto di". Non c'è il ruolo. Questi prompt funzionano già così. Il ruolo — quello che vedremo come Role Prompting nel prossimo capitolo — è una tecnica aggiuntiva che migliora ulteriormente l'output. Ma la base, già così, porta risultati.

Questo è il capitolo tre. Adesso avete tutti gli strumenti fondamentali. Nel prossimo capitolo li potenziamo.

---

# Capitolo 04: Tecniche di Prompt Engineering

---

## Slide apertura capitolo

Siamo arrivati al cuore del discorso. Abbiamo visto la struttura base di un prompt — competenza fondamentale, ma è solo l'inizio.

Adesso facciamo il salto di qualità. Parliamo di tecniche avanzate: Zero-Shot, Role Prompting, Few-Shot, Chain of Thought. Nomi inglesi, concetti molto pratici.

Queste non sono astrazioni teoriche. Sono i pattern sintattici che vi permettono di passare da risultati "accettabili" a output che potete inoltrare direttamente a un team o a uno stakeholder senza dover riscrivere tutto da capo.

Iniziamo dalla base, per arrivare alla fine a combinare tutto in un unico prompt in grado di gestire task aziendali complessi.

---

## 04.01 — Zero-Shot Prompting

Partiamo dalla tecnica base: lo Zero-Shot. "Zero tentativi".

Cosa significa? Fare una richiesta diretta al modello *senza fornire alcun esempio* di come volete la risposta. Ci si affida esclusivamente a quello che il modello ha appreso dal suo addestramento generale.

È la modalità di default. Quella che userete per il 90% delle interazioni rapide per snellire il lavoro quotidiano.

Funziona benissimo quando il task è chiaro, quando fornite un buon contesto o quando volete mappare un terreno: brainstorming di idee, sintesi veloci di testi, esplorazioni. Non importa il millimetro, importa il concetto e l'output può essere flessibile.

Ma attenzione ai limiti: quando vi serve che l'output rispetti un formato rigidissimo ("Voglio una tabella fatta in questo esatto modo"), o un tono aziendale difficilissimo da descrivere a parole... lo Zero-Shot fallisce. E se dovete delegare un'analisi complessa a molti step, l'AI si perde. Qui servono le prossime tecniche.

---

## 04.02 — Role Prompting

Ed ecco la tecnica che dovreste usare quasi sempre: il Role Prompting.

Il concetto è potentissimo: assegnare al modello un'identità o un ruolo professionale *prima* di chiedergli di fare qualcosa. "Sei un [RUOLO] con esperienza in [DOMINIO]."

Perché funziona così bene? Perché gli LLM contengono la conoscenza "media" di internet. Se non date un ruolo, otterrete una risposta media. Se invece dite "Sei un senior project manager specializzato in migrazioni cloud", il modello istantaneamente restringe il proprio campo probabilistico. Adotterà il vocabolario di quel settore, i framework mentali di quel ruolo, l'autorevolezza di quel professionista.

È il vostro filtro di qualità. Volete preparare un'analisi sui rischi? "Sei un esperto enterprise di risk management". Dovete scrivere un comunicato impopolare? "Sei un responsabile comunicazione corporate". Dovete smarcare una retrospective che temete sia improduttiva? "Sei un agile coach certificato".

Aggiungere quelle poche parole all'inizio del prompt trasforma nettamente il livello di partenza della risposta. Usatelo sempre.

---

## 04.03 — Few-Shot Prompting

A volte spiegare a parole cosa volete e come lo volete è un inferno. Molto più facile "farlo vedere". Questo è il Few-Shot Prompting. "Pochi tentativi".

Invece di spiegare verbalmente le regole del formato al modello, gli date da 1 a 3 esempi concreti di *Input* e *Output* direttamente nel prompt. In questo modo riconoscerà la struttura e il tono, replicandoli per il task che gli assegnate.

Vi faccio un caso pratico. Magari la vostra azienda usa un formato tabellare precisissimo per mappare i rischi. Piuttosto che scrivere parametri complessi, gli fornite due esempi di rischi già compilati perfettamente tratti dalla vostra documentazione:
*Esempio 1: Causa -> Classe: Alta -> Azione.*
*Esempio 2: Causa -> Classe: Media -> Azione.*
Poi gli dite: "Adesso classifica questo nuovo rischio usando lo stesso identico schema".

Il modello si nutre di pattern e regole implicite. Riconoscere questa struttura ed emularla chirurgicamente è la cosa che sa fare meglio.

La regola d'oro da ricordarvi? Uno, a esagerare tre esempi. Metterne cinque o dieci non vi darà un risultato 10 volte migliore, appesantirà solo il sistema e brucerà budget context token. Ne bastano pochissimi.

---

## 04.04 — Chain of Thought Prompting

Adesso andiamo sui prompt analitici: la "Catena di Pensiero" o Chain of Thought.

Spesso, se chiedete a un LLM la risposta "finale" a un problema sfaccettato e con molte variabili contrastanti, sbaglierà. Cercherà di arrivare alla conclusione con un balzo logico solo, spesso incappando in un'allucinazione.

Il trucco è questa istruzione "magica": **"Prima di rispondere, ragiona passo per passo"**.

Aggiungere questa singola frase forza il modello a frenare l'output verboso iniziale, e lo costringe a esplicitare il proprio percorso logico sul "foglio" della chat: "Fase 1: analizzo il contesto. Fase 2: isolo l'IP. Fase 3: propongo il workaround".

I vantaggi per un Project Manager sono due, enormi. 
Numero uno: l'accuratezza della risposta migliora drasticamente perché ridurre il salto deduttivo rimpicciolisce lo spazio d'errore. 
Numero due: il processo diventa "auditabile". Perché avete la prova scritta dei passaggi logici operati dall'intelligenza artificiale, e potete verificare come è arrivata a una certa conclusione tecnica.

Usate il Chain of Thought quando chiedete all'AI diagnosi collegate a problemi complessi, decisioni con trade-off rischiosi e valutazioni progettuali determinanti.

---

## 04.05 — Combinare le Tecniche

E per chiudere la parte formativa sui prompt: come mettiamo a terra queste lezioni? Combinandole in un singolo "Prompt Master".

Nella slide vedete un caso reale e utilissimo. Creazione di un Risk Register.

Notate l'anatomia del prompt:
C'è il **Role**: *Sei un senior PM con 10 anni di esperienza SaaS.* (l'orientamento)
C'è il **Contesto**: *Siamo a 3 settimane dal go-live, team di 4 dev.* (la realtà)
C'è il **Few-Shot**: *[Un esempio reale di rischio compilato della vostra azienda]* (il formato)
C'è il **Chain of Thought**: *Per ogni rischio, ragiona causa -> probabilità -> impatto -> azione.* (l'analisi strutturata)
E poi c'è il **Task**: *Identifica i 5 rischi critici in formato tabella.*

Pensate un minuto e mezzo a scrivere un prompt del genere. Ma il file di foglio di calcolo che ne esce non è "un generico elenco di minacce". È un'analisi concreta e formattata, pronta per essere revisionata in un decimo del tempo e inviata nel flusso di progetto aziendale.

---

## 04.06 — Guida Decisionale Rapida

Riassumiamo e schematizziamo. Come capire qual è la tecnica giusta al volo?

Task semplice o brainstorming rapido? **Zero-Shot**.
Elevazione del linguaggio, task specifico: imponete un **Role**.
Formattazioni obbligatorie, JSON, schemi aziendali ripetitivi: usate gli esempi con il **Few-Shot**.
Decisioni critiche e percorsi non lineari: pretendete il **Chain of Thought**.

Non siate pigri nei task chiave. Per i problemi cruciali del progetto, metteteci tre minuti e **combinatele tutte**.

Le tecniche adesso ci sono. Ma queste tecniche sono "potenza", e "la potenza è nulla senza il controllo". Nel prossimo capitolo dobbiamo parlare di cosa l'AI generativa NON capisce, dei suoi allucinanti limiti tecnici e di come un PM debba relazionarsi ad essa.

---
