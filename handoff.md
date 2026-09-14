# Handoff Operativo

## 2026-08-15

- Creata struttura iniziale del vault one-shot D&D.
- Cartelle create: `Sessioni/`, `NPCs/`, `Luoghi/`, `Oggetti/`, `Piste/`, `Archivio_Grezzo/`.
- Creato `.clinerules` con prompt archivista adattato a one-shot.
- Creato `README.md` con mappa concettuale e flusso operativo.
- Ottimizzato setup: rimossa la logica di archiviazione in `Archivio_Grezzo/` da `.clinerules` e `README.md`.
- Nuova regola file grezzi: restano in `Sessioni/` con tag `#grezzo` finché non consolidati.
- Raccolto primo questionario stile mastering: focus su investigazione + azione + horror psicologico, struttura a timeline dinamica, supporto system-agnostic con dettaglio meccanico opzionale.
- Vincoli dichiarati: sessione target ~2h (possibile overrun), almeno 4 giocatori, combattimenti rari ma significativi, enfasi su ruolo e spotlight individuale dei PG.
- Raccolto questionario di affinamento: cold open, tracker spotlight dedicato, indizi core senza tiro + extra su tiro, fail-forward misto per importanza scena, escalation per numero scene.
- Preferenze operative: output molto modulare, no tag globali, appendice meccanica separata dal flusso narrativo, reattività NPC dettagliata, formato luoghi ibrido.
- Template richiesti in priorita: prep rapido, run sheet live, tracker indizi/escalation, tracker spotlight PG, debrief avanzato, contingenze anti-stallo.
- Metriche successo confermate: spotlight per ogni PG, climax raggiunto, nessuno stallo >10 minuti, almeno una scelta morale ad alto impatto, feedback positivo nel debrief.
- Rischi da prevenire: scelte PG non previste, frustrazione da dadi, ritmo lento, incomprensione schede PG preparate dal master, combattimenti lunghi o mal bilanciati.
- Aggiornato `README.md` in versione operativa centrata su ritmo, spotlight, indizi core accessibili e modularità dei file.
- Aggiornato `.clinerules`: approccio system-agnostic, no dipendenza da tag obbligatori, struttura minima schede con appendice meccanica separata.
- Creati template modulari e verticali, successivamente raccolti nella cartella `Template/`.

## 2026-09-03

- Avviata l'implementazione dello scenario `La Campana sotto il Lago`.
- Fissato il dilemma morale: non agire dissolve la memoria collettiva del villaggio; agire trasferisce il vincolo a una singola persona; la terza via richiede ricordi fondamentali come costo.
- Creati `Sessioni/10_Sessione_La_Campana_Sotto_Il_Lago.md` e `Piste/50_Pista_La_Campana_Sotto_Il_Lago.md`.
- Definita la convergenza del mistero verso il terzo rintocco e il principio che nessun tiro decide chi viene sacrificato.
- Creati i luoghi `Luoghi/30_Luogo_Il_Lago_Sommerso.md` e `Luoghi/31_Luogo_La_Cappella_Sommersa.md`.
- Creati `NPCs/20_NPC_Il_Custode.md` e `Oggetti/40_Oggetto_La_Campana.md`.
- Creati `NPCs/21_NPC_La_Persona_Designata.md` e `NPCs/22_NPC_La_Voce_Della_Comunita.md` per rendere il dilemma concreto e dare voce a entrambi i costi.
- Creati gli strumenti operativi `Sessioni/01_Run_Sheet_La_Campana_Sotto_Il_Lago.md`, `Sessioni/02_Debrief_La_Campana_Sotto_Il_Lago.md` e `Sessioni/03_Contingenze_La_Campana_Sotto_Il_Lago.md`.
- Definiti escalation in tre rintocchi, matrice reattiva del custode, costi delle tre vie e contingenze per stallo, ritmo e scelte inattese.
- Creata la verità completa per il master in `Sessioni/11_Verita_Del_Master_La_Campana.md`.
- Creati copione di letture e descrizioni in `Sessioni/12_Testualita_Da_Leggere_La_Campana.md` e dialoghi reattivi in `Sessioni/13_Dialoghi_E_Scene_La_Campana.md`.
- Creata la player guide in `Sessioni/14_Player_Guide_La_Campana.md` con temi, limiti, domande e aspettative.
- Creati cinque profili di PG pregenerati e personalizzabili in `Sessioni/15_PG_Pregenerati_La_Campana.md`.
- Creato l'handout del registro della notte originaria in `Piste/51_Registro_Della_Notte_Originaria.md`.
- Spostati tutti gli otto template in `Template/`, fuori dalle cartelle dei materiali di sessione.
- Definiti i quartieri del villaggio: `Porto del Fondo`, `Borgo Vecchio`, `Case Nuove` e `Piazza del Mercato`.
- Confermata una popolazione di riferimento di 300 abitanti, espandibile a 350-400 se la mappa richiede più attività o abitanti secondari.
- Impostata come regola di scrittura l'italiano UTF-8 con accenti e apostrofi corretti in `.clinerules`.
- Eseguita revisione grammaticale completa del contenuto Markdown: corretti gli accenti mancanti su `è`, `c'è`, `sé`, `lì`, `là`, `sì`, verbi, sostantivi e aggettivi; mantenute senza accento le congiunzioni e le preposizioni corrette.
- Prossimo passo consigliato: revisione editoriale del dilemma e primo playtest a secco per misurare chiarezza dei costi e durata delle scene.

## 2026-09-03

- Eseguita revisione linguistica completa dei file Markdown: corretti accenti, apostrofi, concordanze e forme verbali; mantenuti invariati nomi propri, link, identificatori e dati JSON.
- Creato `Sessioni/04_Riassunto_Regole_Shadowdark.md`, foglio rapido da tavolo con risoluzione prove, CD, vantaggio/svantaggio, combattimento, morte, esplorazione, luce, riposo, incantesimi e promemoria live.
- Verificati sul manuale PDF i valori chiave Shadowdark: CD 9/12/15/18, iniziativa con DES, timer della morte `1d4 + MOD COS` minimo 1, stabilizzazione `INT CD 15`, torcia da un'ora reale e turno d'esplorazione da 10 minuti.

## 2026-09-03 - Architettura emotiva dei PNG e dei PG

- Stabilito che il PNG condiviso da La Promessa e Il Debito sarà la loro madre biologica, una battelliera del lago ancora viva e combattiva.
- Definita la famiglia: La Promessa, Il Debito e Nera, la terza figlia completamente rimossa dalla memoria dei fratelli, della madre e del villaggio.
- Verità per il master: Il Debito era destinato al sacrificio; il Custode ricattò la madre, che cedette e permise che Nera fosse presa al suo posto. La madre coprì poi la verità costruendo una versione falsa del passato.
- La Promessa è legata a Il Debito: la promessa che ricorda riguarda il fratello, mentre l'origine precisa di quel dovere resta deformata dall'oblio.
- Il Ritorno resta autonomo e non occupa il posto di Nera nella memoria di La Promessa. Il suo legame con una casa o un luogo d'infanzia può riattivare dettagli appartenuti alla sorella dimenticata, senza trasformarlo nella sua sostituzione narrativa.
- La rivelazione completa di Nera avviene solo spezzando tutta la maledizione: il ricordo torna simultaneamente a La Promessa, Il Debito e alla madre, insieme al lutto e alla responsabilità della scelta.
- Distribuzione provvisoria dei PNG: Il Custode -> La Memoria; Mara/Persona Designata -> La Voce; La Voce della Comunità -> Il Ritorno; la madre -> La Promessa + Il Debito.
- La scheda PG mantiene una versione giocabile e ambigua del legame; la verità su Nera resta materiale riservato al master.
- Corretta la rete dei legami: La Promessa è legata a Il Debito, non a Il Ritorno; i due PG sanno di essere fratelli e hanno dimenticato soltanto Nera.
- Stabilito che il PNG condiviso è Alba, madre dei due PG, battelliera del lago e moglie dell'attuale Custode Ivo. Ivo è anche il padre biologico dei tre figli.
- Il Ritorno resta un PG autonomo, collegato alla Voce della Comunità; può riattivare dettagli appartenuti a Nera ma non occupa il suo posto nella storia.
- Creata `NPCs/23_NPC_Alba_La_Battelliera.md` con segreto, legami, reazioni alle tre vie e appendice Shadowdark.
- Aggiornati `Sessioni/15_PG_Pregenerati_La_Campana.md`, `NPCs/20_NPC_Il_Custode.md` e `Sessioni/11_Verita_Del_Master_La_Campana.md` per rendere coerenti famiglia, ricatto, sacrificio di Nera e distribuzione dei PNG.
- Implementata la profondità di La Memoria: è originaria di Varda, allieva di Ivo e coinvolta nella ricostruzione dei registri. Ivo ha usato una fiducia autentica per guidare la sua ricerca con verità parziali e tenere nascosta la pagina di Nera.
- Definita la rivelazione in due tempi: La Memoria individua dai registri le omissioni intenzionali, poi Ivo ammette di aver controllato ciò che poteva conoscere. Il suo possibile costo nella terza via è perdere il senso di sicurezza legato a Ivo, conservando però la verità.
- Creato `NPCs/00_Indice_PNG.md` con nomi, titoli, categorie e nodi ancora da definire.
- Aggiunta in `NPCs/00_Indice_PNG.md` la tabella di collegamento tra PNG e PG, distinguendo i quattro referenti attivi dal legame segreto di Nera con La Promessa e Il Debito.
- Resa esplicita nell'intestazione di `NPCs/21_NPC_La_Persona_Designata.md` l'identità di Mara Varda.

## 2026-09-06 - Rifondazione del funzionamento della campana

- Separati concettualmente Voce Profonda, sigillo, campana e rintocchi.
- Stabilito che la campana segnala l'indebolimento del sigillo e avvia una finestra di tempo prima del ritorno dell'acqua.
- Stabilito che, senza un'offerta, la Voce Profonda divora casualmente volti, legami e infine la storia comune del villaggio.
- Stabilito che la persona offerta perde identità e ricordi, viene dimenticata dal villaggio e muore annegata quando il lago riempie il campanile.
- Inseriti i resti dei sacrificati precedenti come presenza ambientale e possibile ostacolo per uno o due combattimenti brevi, senza boss fight obbligatoria.
- Allineati oggetto, verità del master, cappella, pista, sessione, letture, dialoghi e run sheet al nuovo ciclo fisico del rito.
- Lasciati volutamente da definire in una fase successiva: il criterio preciso di selezione della vittima, il destino del vecchio Custode, il ruolo di Nera e la risoluzione definitiva del patto.

## 2026-09-06 - Implementazione trama di Nera e ciondolo di famiglia

- Approvato il riempimento dei buchi della trama di Nera: sacrificio circa vent'anni fa, con i tre figli adolescenti; Nera resta morta e il ricordo completo torna solo quando il patto viene spezzato.
- Definita la designazione: la campana non sceglie autonomamente una vittima; il ciclo fa emergere il legame più vicino alla storia irrisolta del patto e il villaggio lo trasforma in una procedura umana. Il Custode interpreta e conduce, ma non decide da solo.
- [SUPERATO] Chiarita la sostituzione: Il Debito era il designato; Alba pronunciò Nera durante la finestra del rito sotto il ricatto di Ivo. La vecchia ipotesi secondo cui la voce del Custode avrebbe trasformato il nome di Nera in un ordine è stata sostituita dalla regola del rito specifico.
- Aggiunto il ciondolo di bronzo con tre onde incise, simbolo domestico creato da Alba per i tre figli. Uno zombie o scheletro del combattimento nel campanile lo porta ancora addosso.
- Inserito il ciondolo nei background di La Promessa, Il Debito e Il Ritorno con ricordi incompleti e distinti; il reperto non rivela automaticamente il nome di Nera.
- Aggiornati verità del master, schede di Ivo, Alba e Mara, oggetto campana, cappella, dialoghi dei resti, pista investigativa, sessione principale, run sheet e contingenze anti-stallo.

## 2026-09-06 - Pulizia schede di Alba e Ivo

- Allineata Alba alle regole della Campana: un'offerta volontaria è possibile se la persona comprende e assume la scelta; non viene rifiutata solo perché nasce dalla paura.
- Distinti per Ivo obiettivo immediato e desiderio profondo, chiarendo che il Custode conduce il rito ma non sceglie autonomamente la vittima.
- Verificata la coerenza di Alba e Ivo con il sacrificio di Nera, il ciondolo e la rivelazione completa dopo la rottura del patto.

## 2026-09-06 - Rito e leaking della sottotrama di Nera

- Separato il nome pronunciato fuori dal rito dall'offerta rituale: il Custode può parlare liberamente, conduce il passaggio al campanile ma non rende vittima una persona con la sola voce.
- Definita la sequenza del sacrificio come designazione della comunità, conduzione del Custode, consegna nel cerchio e ritorno dell'acqua.

## 2026-09-07 - Avvio implementazione allineamento campana

- Stabilito che non esiste alcun rintocco prima dell'inizio della sessione: il primo suono di escalation avviene durante il gioco.
- Aggiornati verità del master, testo d'apertura, sessione, oggetto campana e pista per distinguere atmosfera iniziale e primo rintocco.
- Riscritto il registro della notte originaria come documento umano: la paura, il residuo interpretato come ordine, la pressione di Tomaso e la successiva cancellazione del nome spiegano perché il villaggio creda alla designazione.
- Chiarito che la campana non seleziona la vittima; la responsabilità nasce dalla comunità e dal rito.
- La Memoria può sospettare la lettura ufficiale grazie al metodo che Ivo le ha insegnato: cercare omissioni, formule assolute e contraddizioni nei registri.
- Lasciati da definire: struttura completa della sessione, timer reale, conseguenza definitiva dell'esilio de Il Ritorno, eventuale scheda della Voce Profonda e abitanti secondari.
- Inserito il leaking dei ricordi come effetto del sigillo indebolito: indizi, oggetti, luoghi e resti possono far filtrare frammenti di Nera prima della rivelazione completa.
- Allineati Ivo, Alba, Mara, verità del master, sessione, run sheet, contingenze e dialoghi a questa regola; rimosso il debito soprannaturale futuro dalla contingenza.

## 2026-09-06 - Implementazione definitiva di Alba e Nera

- Riscritta `NPCs/23_NPC_Alba_La_Battelliera.md`: Alba conserva frammenti concreti di Nera, ha una cicatrice del tentativo fallito di interrompere il rito e ricorda tutto solo quando il patto viene spezzato.
- Definita la notte del sacrificio: il villaggio aveva scelto Il Debito; Nera propose di sostituirlo, Alba collaborò, Ivo rese possibile il passaggio e Il Debito fuggì.
- Stabilito che il villaggio non conserva una versione stabile dell'accaduto: tutti ricordano di aver perso un figlio, ma non quale; il rito resta una tradizione nata dalla paura, non un ordine necessario della Voce Profonda.
- Aggiornati `Sessioni/11_Verita_Del_Master_La_Campana.md` e `NPCs/20_NPC_Il_Custode.md`: Ivo crea l'urgenza, mente sul ritorno di Nera, nega per dolore e può confessare se i PG lo incalzano.
- Aggiornato `Sessioni/15_PG_Pregenerati_La_Campana.md`: la promessa de La Promessa era originariamente rivolta a Nera; Il Debito ricorda la fuga e il debito verso Alba.
- Aggiornati `Sessioni/10_Sessione_La_Campana_Sotto_Il_Lago.md`, `Sessioni/12_Testualita_Da_Leggere_La_Campana.md`, `Sessioni/13_Dialoghi_E_Scene_La_Campana.md` e `Sessioni/01_Run_Sheet_La_Campana_Sotto_Il_Lago.md` con il ritorno simultaneo della memoria e la domanda: "Adesso che ricordo, cosa dovrei fare?"

## 2026-09-07 - Approfondimento di Ivo e La Memoria

- Reso esplicito che Ivo si è legato a La Memoria riconoscendo in lei gesti e ostinazioni di Nera, trasformando inconsapevolmente l'allieva in un rimpiazzo della figlia sacrificata.
- Mantenuto l'affetto di Ivo come autentico ma contaminato: il controllo dei registri e delle informazioni è una ripetizione del gesto con cui ha deciso per Nera.
- Aggiunti alla scheda di Ivo la confessione sul rimpiazzo e la condanna finale: ricordare Nera significa capire che La Memoria non era lei.
- Aggiornata la verità del master con il nuovo asse emotivo e con il costo concreto della terza via per La Memoria.
- Aggiornati il profilo giocatore di La Memoria e i dialoghi finali con segnali, battute e risposta possibile.

## 2026-09-07 - Controllo coerenza famiglia/rito e rinvio cripta/cerchio

- Eseguito controllino di coerenza tra La Promessa, Il Debito, Alba, Nera e il rapporto Ivo-La Memoria: nessuna contraddizione rilevata sui fatti principali.
- Segnalato in `Luoghi/31_Luogo_La_Cappella_Sommersa.md` che il rapporto fisico tra cripta e campanile e l'aspetto/funzione del cerchio di sale nero non sono ancora definiti nel dettaglio.
- Rinviata la definizione di cripta e cerchio di sale a dopo il completamento di tutti i materiali di PG e PNG.

## 2026-09-07 - Fondamenta operative di La Voce e Il Ritorno

- Rifondato La Voce come mediatore pubblico: Mara non gli/le consegna più una frase-indizio; chiede una testimonianza esplicita che il proprio silenzio non vale come consenso al sacrificio.
- Definito Tomaso Riva come sindaco di Varda e decisore politico della designazione di Mara. Il party mantiene agency su due livelli: può legittimare o contestare pubblicamente la scelta e può impedirne o consentirne materialmente l'esecuzione.
- Rifondato Il Ritorno come persona allontanata da Varda il cui motivo d'esilio è stato sfocato dall'indebolimento del sigillo. Il suo obiettivo è scoprire quale colpa o persona sia stata nascosta dietro l'esilio; resta estraneo alla famiglia di Nera.
- Aggiornati `Sessioni/15_PG_Pregenerati_La_Campana.md`, `NPCs/21_NPC_La_Persona_Designata.md`, `NPCs/22_NPC_La_Voce_Della_Comunita.md`, `NPCs/00_Indice_PNG.md`, `Sessioni/11_Verita_Del_Master_La_Campana.md` e `Sessioni/13_Dialoghi_E_Scene_La_Campana.md`.

## 2026-09-07 - Rifondazione della cappella e dei residui mnemonici

- Stabilito che la cappella è sempre stata sul fondo del lago: il calo del livello fa emergere solo la punta del campanile e la campana; la base e la cripta restano sommerse e si raggiungono scendendo nella torre.
- Stabilito che la Voce Profonda era già nella cripta sigillata e che Tomaso ruppe il sigillo durante una crisi, nel tentativo di trovare una soluzione per il villaggio.
- Definito Elian come primo sacrificato dopo la rottura del sigillo: si offrì per richiudere la Voce, ma non è il modello del ruolo di Custode.
- Definito il funzionamento degli indizi: la Voce restituisce un residuo della memoria dell’ultima vittima, già dimenticata dal villaggio; Tomaso lo presenta come designazione della prossima vittima, anche se la Voce richiede soltanto un’offerta compresa e pronunciata.
- Definito Tomaso come vincolato alla Voce: ricorda i sacrificati e la falsificazione degli indizi, mentre il villaggio dimentica ogni vittima.
- Definito Il Ritorno come testimone della falsificazione: prima dell’esilio aveva capito che gli indizi appartenevano ai sacrificati precedenti; l’indebolimento del sigillo gli ha lasciato frammenti e la certezza dell’inganno, ma non la memoria cosciente completa.
- Aggiornati `Sessioni/11_Verita_Del_Master_La_Campana.md`, `Luoghi/31_Luogo_La_Cappella_Sommersa.md`, `Oggetti/40_Oggetto_La_Campana.md`, `Sessioni/13_Dialoghi_E_Scene_La_Campana.md`, `NPCs/20_NPC_Il_Custode.md`, `NPCs/22_NPC_La_Voce_Della_Comunita.md` e `Sessioni/15_PG_Pregenerati_La_Campana.md`.
- Prossimo passo: allineare pista, sessione, run sheet e scena operativa della discesa dal campanile alla cripta.

## 2026-09-07 - Ricordi progressivi e pressione del tempo

- Estesi i cinque profili pregenerati con un contesto iniziale, Ricordo I, Ricordo II e Ricordo III; i primi due sono personali e cancellabili, il terzo e preservato per il climax.
- Formalizzata in `Sessioni/10_Sessione_La_Campana_Sotto_Il_Lago.md` la pressione temporale: il conteggio parte dall'ingresso effettivo nella cappella, con checkpoint flessibili attorno a 30 e 60 minuti di gioco effettivo.
- Collegati i primi due checkpoint ai rintocchi: ogni giocatore barra il ricordo corrispondente; il terzo rintocco apre il dilemma e non cancella Ricordo III.
- Confermato che il ricordo fondamentale non e una perdita automatica: resta un costo consensuale e facoltativo della Terza Via.
- Aggiornati `Sessioni/01_Run_Sheet_La_Campana_Sotto_Il_Lago.md` con tracker e procedura live, e `Sessioni/14_Player_Guide_La_Campana.md` con istruzioni di consenso, barratura e ricalibrazione.
- Verifica svolta: nessun errore rilevato nei file Markdown toccati. Prossimo passo consigliato: dry run da 90 minuti di gioco effettivo per verificare le due perdite e la riserva di 25-30 minuti per il climax.

## 2026-09-07 - Accesso alla cripta e causalita dell'acqua

- Corretto il ciclo fisico: il lago si ritira durante i tre rintocchi, esponendo la campana e l'apertura della torre; i PG raggiungono il luogo in barca e scendono alla cripta prima della scelta.
- Stabilito che l'acqua risale soltanto dopo una consegna nel cerchio di sale nero della procedura tradizionale: nutre la Voce, annega la vittima e ricopre la cappella.
- Se non viene compiuta un'offerta entro il terzo rintocco, il lago continua a ritirarsi e la Voce consuma memoria, legami e storia comune del villaggio.
- Reso Ivo una guida possibile ma non necessaria: puo condurre la barca e spiegare rito e torre, ma Alba o l'esplorazione dei PG permettono comunque di raggiungere il climax.
- Allineati verita del master, luogo, campana, sessione, run sheet, pista e contingenze. Da definire in seguito: esito fisico del lago dopo la Terza Via, natura della Voce e comportamento preciso dei resti.

## 2026-09-07 - Avvio riordino strutturale

- Confermata la nuova convenzione semantica `TIPO-NN_NomeBreve.md`, senza numerazioni a salti.
- Creata `MATRICE_Migrazione.md` con i percorsi finali e la separazione Master/Giocatori/Handout/Post-sessione.
- Aggiornato `README.md` con la struttura finale e le regole per nuovi contenuti.
- Stabilito che la prima migrazione riguarderà i materiali condivisi di `Sessioni/`; la scomposizione dei cinque PG seguirà in una cartella autonoma `PG/`.
- Prossimo passo: creare le cartelle finali, spostare e rinominare i file secondo la matrice, quindi aggiornare tutti i link interni.

## 2026-09-07 - Migrazione Sessioni e separazione PG

- Create `Sessioni/Master/`, `Sessioni/Giocatori/`, `Sessioni/Handout/` e `Sessioni/Post-sessione/`.
- Spostati e rinominati i materiali di sessione secondo `MATRICE_Migrazione.md`; il registro della notte originaria ora vive tra gli handout.
- Creato `PG/` con cinque cartelle autonome: `La_Memoria`, `La_Promessa`, `La_Voce`, `Il_Debito`, `Il_Ritorno`.
- Assegnati nomi propri ai PG: Ada Ferri, Elio Varda, Viola Serra, Nino Varda e Marta Lodi.
- Sostituito l'indice monolitico con `PG/INDICE_PG_La_Campana.md`; ogni scheda contiene identità, legami, ricordi, spotlight e segreto del master.
- Aggiornati i link wikilink coinvolti nella migrazione; audit eseguito senza link rotti nei file non storici.
- Prossimo passo: normalizzare i template e rinominare le schede di NPC, luoghi, oggetti e piste con codici semantici.

## 2026-09-07 - Normalizzazione cataloghi

- Rinominati gli otto template con codici `TMP-01` fino a `TMP-08`.
- Rinominati i cataloghi esistenti: `NPC-01` fino a `NPC-04`, `LUO-01` fino a `LUO-03`, `OBJ-01` e `PST-01`.
- Aggiornato `NPCs/INDICE_NPC.md` e corretti i link tra PNG, luoghi, oggetti e pista principale.
- Audit intermedio eseguito sui riferimenti obsoleti; resta da completare la verifica globale dei link e la creazione delle nuove schede di entità e piste.
- Prossimo passo: aggiungere il diario di Tomaso, le schede degli oggetti nominati e le prime figure secondarie, poi completare la separazione Master/Player dove necessario.

## 2026-09-07 - Verifica link e template

- Aggiornati i wikilink interni dei cinque template rinominati.
- Audit finale completato: zero riferimenti ai vecchi basename navigazionali e zero wikilink rotti fuori dai riferimenti storici.
- La struttura attiva ora e: cataloghi semantici, Sessioni divisa per pubblico/funzione e cinque cartelle PG autonome.
- Prossimo blocco narrativo: diario di Tomaso, schede autonome per ciondolo/frammento/registro/cera/resti e abitanti secondari con legami espliciti.

## 2026-09-14 - Bonifica wikilink e indici per cartella

- Standardizzato il collegamento su wikilink Obsidian `[[Cartella/NomeFile]]` ovunque: convertiti i link Markdown residui in `NPCs/INDICE_NPC.md` e `PG/INDICE_PG_La_Campana.md`, corretti i wikilink con percorso incompleto in `Sessioni/Master/SES-04_Regole_Shadowdark.md` e `Sessioni/Master/SES-06_Verita_La_Campana.md`.
- Aggiunta la sezione `## Note correlate` dove mancava: le cinque schede PG, `Sessioni/Giocatori/PG-00_Guida_La_Campana.md`, `Sessioni/Handout/HND-01_Testualita_La_Campana.md` e `HND-02_Registro_Della_Notte_Originaria.md`.
- Creati sette nuovi indici di cartella sul modello di `INDICE_NPC.md`: `Luoghi/INDICE_Luoghi.md`, `Oggetti/INDICE_Oggetti.md`, `Piste/INDICE_Piste.md`, `Template/INDICE_Template.md`, `Sessioni/Master/INDICE_Sessioni_Master.md`, `Sessioni/Giocatori/INDICE_Sessioni_Giocatori.md`, `Sessioni/Handout/INDICE_Sessioni_Handout.md`.
- Aggiornato `README.md`: sezione "Struttura cartelle" con rimando a ogni indice, nuova sezione "Convenzione collegamenti" che dichiara il wikilink come standard unico.
- **TODO (rimandato a chat dedicata):** canovaccio scena per scena — espandere `Sessioni/Master/SES-01_Run_Sheet_La_Campana.md` con narrazione Apertura → Scena 1 → 2 → 3 → Climax, testi da leggere da `HND-01`, indizi da `PST-01` e battute da `SES-07`, mantenendo invariati i tracker live esistenti.
