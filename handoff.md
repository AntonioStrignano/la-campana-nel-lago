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
- Inserito il leaking dei ricordi come effetto del sigillo indebolito: indizi, oggetti, luoghi e resti possono far filtrare frammenti di Nera prima della rivelazione completa.
- Allineati Ivo, Alba, Mara, verità del master, sessione, run sheet, contingenze e dialoghi a questa regola; rimosso il debito soprannaturale futuro dalla contingenza.

## 2026-09-06 - Implementazione definitiva di Alba e Nera

- Riscritta `NPCs/23_NPC_Alba_La_Battelliera.md`: Alba conserva frammenti concreti di Nera, ha una cicatrice del tentativo fallito di interrompere il rito e ricorda tutto solo quando il patto viene spezzato.
- Definita la notte del sacrificio: il villaggio aveva scelto Il Debito; Nera propose di sostituirlo, Alba collaborò, Ivo rese possibile il passaggio e Il Debito fuggì.
- Stabilito che il villaggio non conserva una versione stabile dell'accaduto: tutti ricordano di aver perso un figlio, ma non quale; il rito resta una tradizione nata dalla paura, non un ordine necessario della Voce Profonda.
- Aggiornati `Sessioni/11_Verita_Del_Master_La_Campana.md` e `NPCs/20_NPC_Il_Custode.md`: Ivo crea l'urgenza, mente sul ritorno di Nera, nega per dolore e può confessare se i PG lo incalzano.
- Aggiornato `Sessioni/15_PG_Pregenerati_La_Campana.md`: la promessa de La Promessa era originariamente rivolta a Nera; Il Debito ricorda la fuga e il debito verso Alba.
- Aggiornati `Sessioni/10_Sessione_La_Campana_Sotto_Il_Lago.md`, `Sessioni/12_Testualita_Da_Leggere_La_Campana.md`, `Sessioni/13_Dialoghi_E_Scene_La_Campana.md` e `Sessioni/01_Run_Sheet_La_Campana_Sotto_Il_Lago.md` con il ritorno simultaneo della memoria e la domanda: "Adesso che ricordo, cosa dovrei fare?"
