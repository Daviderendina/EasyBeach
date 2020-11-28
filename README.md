## Assignment 2
### Studenti

| Nome e Cognome  | Mail Unimib | Utente GitLab |
| ---------------- | ------------- | ------------------  |
| Davide Rendina | d.rendina2@campus.unimib.it  |  @daviderendina |
| Gabriele Maria Bucosse  | g.bucosse@campus.unimib.it  | @gabriele_maria_bucosse  |
| Ruggero Panzeri  | r.panzeri12@campus.unimib.it  | @ruggero_panzeri_unimib |

### Repo
[2020_assignment2_booking_seaside_chalet](https://gitlab.com/gabriele_maria_bucosse/2020_assignment2_booking_seaside_chalet)

### Scopo

Definire una strategia per acquisire conoscenze su un prodotto software che deve essere sviluppato, lavorando sull'elicitazione.

## Descrizione Progetto
EasyBeach è un applicazione per permettere agli utenti di poter prenotare ombrelloni negli chalet presso le località di mare. Questa applicazione consente ai clienti di prenotare direttamente l’ombrellone e i lettini presso lo chalet desiderato, attraverso l’utilizzo del proprio smartphone.  
Il posto potrà essere prenotato per un periodo di tempo in base a quanto stabilito dal singolo chalet (es. nello chalet X è disponibile la prenotazione giornaliera, mensile e stagionale, mentre lo chalet Y accetta prenotazioni giornaliere, settimanali e mensili). Per ogni chalet, è possibile per l’utente la consultazione delle tariffe delle diverse combinazioni di ombrellone + lettino, stabilite anche queste dal singolo chalet.
Tramite la piattaforma è possibile inoltre esplorare tutti i servizi disponibili presso lo stabilimento  balneare, come ad esempio eventuale attività di bar e ristorazione (con relativi prezzi) oppure altri servizi gratuiti disponibili (campidi  beach  volley,  docce  fredde,  ..). Il gestore può inoltre comunicare ai clienti, attraverso l’applicazione, diversi sconti e promozioni per tutti i servizi offerti. Il gestore degli chalet potrà inoltre stabilire alcuni sconti e promozioni (es. paga  due  giorni  e  prenota per tre) per determinate giornate o periodi della stagione.
E' possibile inoltre effettuare il pagamento attraverso l'applicazione, utilizzando i servizi di pagamento online più utilizzati. Infine il gestore potrebbe anche essere disponibile la prenotazione tramite app e il pagamento in struttura.

## Piano di elicitazione

Viene ora presentato il piano di elicitazione, approfondito nelle varie attività svolte all'interno dei successivi paragrafi.

1. **Background analysis** si vuole ottenere la conoscenza necessaria riguardante il dominio di riferimento e il system as-is attraverso una loro analisi approfondita e comprensione.

2. **Analisi e identificazione degli stakeholder** al fine di identificare tutti i soggetti in relazione con il sistem to-be, descrivendo anche nel dettaglio perchè e in che modo hanno interesse nei confronti del sistema da sviluppare. 
<!--Per questa attività verra effettuato un brainstorming tra gli sviluppatori del progetto, utilizzando per l'identificazione le informazioni recuperate dalla _background analysis_ e le domande proposte nelle slide (assolutamente da cambiare - magari tutta questa frase va descritta nella parte dove descriviamo bene l'analisi)-->
3. **Riunione del team** per definire gli obiettivi del system to-be e identificare i primi requisiti.

4. **Preparazione e sottomissione dei questionari** saranno preparati i questionari da sottoporre alle varie tipologie di stakeholder. In particolare verrà preparato un questionario per ogni stakeholder ritenuto significativo per la scoperta di nuovi requisiti.

5. **Analisi delle risposte ricevute dai questionari** le risposte ricevute dai questionari saranno analizzate per comprendere il punto di vista degli stakeholder riguardo temi particolari e definire i requisiti in base alle risposte ricevute.

6. **Generazione degli scenari e discussione con gli stakeholder** verranno inoltre generati gli scenari più significativi dell'applicazione, per comprendere al meglio la gestione di situazioni particolari che potrebbero verificarsi.

7. **Definizione dei requisiti** infine saranno generati i requisiti dell'applicazione analizzando le informazioni ricevute da tutte le attività svolte.

![](img/workflow.png)


## Descrizione approfondita delle attività

### 1. Background Analysis

Obiettivo dell'attività di background analysis è la definizione delle caratteristiche del system as-is. Avendo già il team le conoscenze necessarie per il dominio di riferimento, non è stato necessario accedere a documenti e informazioni particolari.
Viene riportato di seguito ciò che il team è stato in grado di scoprire durante questa attività (TODO: forse va messo nell'appendice)

#### System as-is
- I clienti attualmente per prenotare gli chalet si recano personalmente sul posto o chiamano per telefono. 
- Se scelgono di recarsi sul posto ma trovano uno chalet completamente occupato oppure che ha un prezzo troppo elevato secondo le loro esigenze, si spostano verso il successivo.
- Se invece provano a chiamare lo chalet per verificare la disponibilità oppure i costi di un determinato chalet ma non lo considerano adatto oppure non risulta disponibile, devono effettuare una chiamata allo chalet successivo.
- Per la ricerca dei numeri di telefono possono utilizzare un'agenda telefonica oppure diversi servizi presenti sul web (ricerca con Google, pagine degli stabilimenti sui social network, ecc..). 
<!-- - Si segnala che è più probabile che le piattaforme web (più immediate nella ricerca) siano preferite da un utenza più giovane mentre per persone non esperte con la tecnologia è probabile venga utilizzato il primo metodo. -->
- Anche per la consultazione di servizi disponibili presso lo stabilimento ed eventuali menù/prezzi vengono utilizzati i metodi presentati in precedenza (contatto telefonico o recarsi sul posto).
- La reputazione degli chalet viene condivisa tramite passaparola senza un garante di veridicità.

    ##### PRO
    - Miglior interazione sociale
    - Adatto a tutte le fasce di età, anche per chi non è pratico con la tecnologia

    ##### CONS
    - Spreco di tempo
    - Nessuna garanzia di riuscita 
    - Nessuna garanzia di qualità
    - Difficile espanione
    - Notorietà degli chalet limitata
    - Difficoltà nel presentare eventuali offerte o promozioni


### 2. Identificazione degli stakeholder

Obiettivo dell'attività è l'identificazione degli stakeholder, ovvero tutti i soggetti che sono direttamente o indirettamente relazionati al progetto. In particolare gli stakeholder vengono divisi in due categorie, primari e secondari, in base al grado di interesse (rispettivamente forse oppure debole) mostrato nei confronti del system to-be.

Per l'identificazione degli stakeholder, è stata fatta una sessione di brainstorming tra i componenti del gruppo, utilizzando le seguenti domande:
- Su quale categoria di persone il progetto ha un impatto positivo o negativo?
- Chi ha il potere di permettere la riuscita o il fallimento del progetto?
- Chi effettua le decisione riguardo i soldi?
- Chi sono i fornitori?
- Chi sono gli utenti finali?
- Chi ha influenza sugli altri stakeholder?
- Chi può risolvere problemi potenziali con il progetto?
- Chi è responsabile dell'assegnazione o dell'approvvigionamento di risorse o strutture?
- Chi ha le skills necessarie che sono cruciali per il progetto?

Solo alcune domande sono state utili alla identificazione di nuove categorie di stakeholder mentre alcune non hanno portato alla scoperta di nulla.

#### Stakeholders primari:

##### Team di sviluppo:
- Punta alla ottima riuscita del progetto, per un rendiconto personale

##### Proprietari/Gestori chalet balneari: 
- Vogliono rendere visibile, in tempo reale, la disponibilità del proprio servizio.
- Vogliono incrementare i profitti
- Vogliono incrementare il loro bacino di utenza

##### Dipendenti dello chalet
- La buona riuscita del progetto potrebbe causare un aumento della visibilità dello chalet, con conseguente aumento del flusso di clienti e della possibilità di lavoro.
- I potenziali clienti sono già a conoscenza della maggior parte (se non totalità) dei servizi e prezzi dello chalet, quindi eviterebbero l'attività di fornire ogni volta informazioni generiche ai potenziali clienti.

##### Addetto agli ombrelloni dello chalet
- Ha interesse che il progetto abbia successo poiché il suo lavoro risulterebbe notevolmente alleggerito. Attraverso l'utilizzo dell'app dovrebbe solamente occuparsi della gestione dei pagamenti (se non viene già effettuato nell'app), ed eventualmente effettuare il controllo della prenotazione e accompanare i clienti all'ombrellone prenotato (anche se potrebbe essere svolto in autonomia dal cliente).

##### Clienti:
- Vogliono conoscere i vari locali che offrono quel determinato servizio
- Vogliono poter confrontare le varie offerte proposte
- Vogliono avere una possibilità di prenotare facilmente e velocemente
- Vogliono poter leggere/scrivere recensioni

##### Fornitori:
- Vogliono che il progetto abbia successo perchè loro guadagneranno tramite il numero clienti che scaricheranno l'app.

#### Stakeholders secondari:

##### Competitori:
- Altri servizi di booking: la loro utenza potrebbe diminuirsi a causa di questa applicazione.

#### Stakeholders scelti per i questionari:
- Proprietari/Gestori: vogliamo sapere quali funzionalità potrebbero apprezzare, in quale modo vorrebbero averle a disposizione, e gli aspetti più e meno interessanti tramite i quali l'applicazione potrebbe suscitare o meno interesse.

- Clienti: vogliamo sapere quali funzionalità potrebbero apprezzare, consigli su servizi che vorrebbero avere all'interno dell'applicazione, e la qualità generale del servizio.


### 3. Riunione del team

Nel processo di elicitazione, dovrebbe essere effettuato un primo studio delle funzionalità di EasyBeach, per effettuare una valutazione preliminare dei possibili requisiti del system-to-be, tenendo conto anche del dominio del software, utile al fine di creare un questionario mirato. Per questo motivo, in questo punto è presentato un ragionamento delle possibili funzionalità che abbiamo identificato, le quali dovrebbero essere presenti nell'app.

- Tutti possono accedere all'app, ma solamente chi si registra all'interno dell'app potrà: o inserire la propria struttura nel caso dei gestori, o effettuare qualunque tipo di prenotazione nel caso dei clienti.

- Per inserire il proprio chalet nell'app, il gestore dovrà superare il controllo di verifica di identità durante la registrazione.

- Ogni struttura sarà identificata attraverso il proprio nome.

- Ogni struttura inserita avrà la propria pagina con: foto, posizione sulla mappa, descrizione, relativo costo di ogni servizio offerto, sezione recensioni.

- Ogni struttura potrà essere ricercata/classificata da chiunque utilizzi l'app in base ad alcuni filtri sulla ricerca, basati sulle preferenze riguardo: servizi offerti, prezzi, metodi di pagamento etc.

- I clienti registrati potranno effettuare qualunque tipo di prenotazione per la struttura scelta, secondo le regole imposte da ogni struttura (Ad esempio pagamento immediato, pagamento in struttura, cancellazione gratuita etc.)

- I clienti, dopo aver effettuato la prenotazione ed aver terminato l'esperienza presso la struttura prenotata, potranno scrivere una recensione in merito alla stessa

- I gestori/personale della struttura, terminata l'esperienza del cliente, potranno dare fare una recensione al cliente.

- Per qualsiasi problematica riscontrata da qualunque utente all'interno dell'app, sarà presente una sezione "contattaci", nella quale sarà avviato un collegamento diretto con i manutentori dell'applicazione tramite mail o tramite live chat.

### 4. Preparazione e sottomissione dei questionari

Il questionario è diviso in due parti

![](img/workflow-quest.jpg)

##### Area introduttiva
Le domande presenti in quest'area servono a conoscere qualche informazione generale riguardo all'utente che sta svolgendo il questionario.

- *Quanti anni hai?* 
Comprensione dell'età dello stakeholder, per analizzare al meglio le esigenze di ogni fascia di età. Le fasce di età sono divise in base all'utilizzo che pensiamo gli utenti potranno fare della nostra app, e in particolare verranno prese in considerazione più le risposte delle fasce 15-30 e 31-50 rispetto alle altre, poichè sono le generazioni più abituate all'utilizzo del telefonino e di internet.

- *Hai mai usato un'applicazione per prenotare o usufruire di servizi?* 
Analizzare se l'utente ha dimestichezza con altri sistemi di prenotazione online, per analizzare le risposte in base alle esperienze passate. In particolare questa domanda serve per sottoporre l'utente a ulteriori domande di approfondimento dei sistemi utilizzati, al fine di comprendere l'utilità o meno di queste soluzioni online per la prenotazione.

##### Area introduttiva app usate
Le domande presenti in quest'area puntano a conoscere se l'utente che ha già utilizzato qualche app l'abbia ricevuta utile o meno, e se quindi le applicazioni di questo tipo siano effettivamente percepite come un valore aggiunto.

- *Quali app hai già usato per prenotare o usufruire di servizi?* 
Questa domanda è utile per comprendere i sistemi che gli utenti usano abitualmente (in modo da poterne analizzare i punti di forza e debolezza?) ??

- *Hai riscontrato benefici dall'utilizzo di queste applicazioni?* (vedi dopo)

- *Nelle app che hai usato per prenotare hai sempre trovato tutte le informazioni che cercavi sulle strutture?*
Attraverso queste due domande si vuole comprendere se l'utente ha trovato questi sistemi utili e completi, per capire se il nostro prodotto può portare a un valore aggiunto o meno e analizzare eventualmente le altre applicazioni di questo tipo per scovare i loro punti di debolezza.

##### Area chalet
Le domande presenti in quest'area hanno lo scopo di raccogliere le risposte e il punto di vista degli stakeholder riguardo la prenotazione degli chalet, sia attuale (system as-is) che nel nostro sistema (system to-be)

- *Ritieni utile un applicazione che ti permetta di effettuare la prenotazione smart di ombrelloni presso gli chalet nelle località di mare?*
Per comprendere se i potenziali stakeholder provano interesse nei confronti del system to-be.

- *Hai mai cercato informazioni o caratteristiche riguardo agli chalet nelle località di mare (attraverso passaparola, internet, guide turistiche, ecc..) ?* (vedi dopo)

- *Sei hai risposto sì alla domanda precedente, sei riuscito ad ottenere con facilità le informazioni richieste?*
Attraverso queste due domande cerchiamo di capire se le informazioni riguardanti gli chalet delle località marittime sono facilmente raggiungibili e esaustive, per comprendere se il nostro sistema potrebbe portare benefici agli utenti e fornire informazioni che sono attualmente difficilmente accessibili.

##### Area feature
Le domande presenti in quest'area pongono la loro enfasi maggiormente sulle feature dell'applicazione comuni a tutte e due le categorie di stakeholder alle quali stiamo sottoponendo il questionario.

- *Da quale device utilizzeresti il nostro servizio?* 
Attraverso questa domanda si vuole comprendere quali sono i device verso quale si dovrebbe porre maggior attenzione per la piattaforma.

- *Ritieni utile la possibilità di consultare ed effettuare e consultare recensioni riguardanti gli chalet all'interno dell'applicazione?*
Si vuole comprendere se la presenza di un sistema di recensione degli chalet sia percepita in maniera positiva da clienti e proprietari, per decidere se le recensioni debbano essere presenti all'interno dell'app o meno.

- *Troveresti utile avere recensioni da profili verificati, per avere una maggiore affidabilità?*
Si vuole comprendere se gli utenti percepirebbero le recensioni da utenti verificati (es. guide locali) come garanzia di affidabilità della recensione, e se un sistema del genere possa portare benefici al sistema di recensioni in generale. Si vuole quindi evitare di introdurre nelle specifiche una funzionalità che non sarebbe sfruttata a pieno dagli stakeholder oppure che gli utenti percepiscono come poco utile.

- *Preferiresti recensioni con solo testo, o con la possibilità di aggiungere allegati? (Foto, video etc.)*
Si vuole comprendere se l'introduzione di allegati alle recensioni sia effettivamente utile oppure utilizzata poco / non utilizzata dagli utenti., al fine di evitare di introdurre nelle specifiche una funzionalità che non sarebbe poi sfruttata a pieno dagli stakeholder.

- *Ritieni utile un servizio di supporto on-line in caso di problemi con le prenotazioni?*
Vogliamo conoscere il punto di vista degli utenti in merito al supporto on-line per l'applicazione, per comprendere eventualmente tra i requisiti del sistema anche quelli legati al supporto.

- *Nel caso, come preferiresti contattare il servizio ?*
Vogliamo comprendere le metodologie preferite dagli stakeholder per contattare il supporto, al fine di conciliare le loro esigenze con quelle del team di supporto.

- *Sei il proprietario di uno chalet?*
Poniamo questa domanda per suddividere la successiva parte del questionario in due aree dedicate per clienti e gestori.

##### Area proprietario
Le domande presenti in quest'area sono dedicate ai proprietari di chalet e puntano a comprendere il loro punto di vista riguardo l'applicazione ed eventuali feature da implementare o meno.

- *Ritieni EasyBeach uno strumento utile per avere una maggiore visibilità e conseguentemente aumentare l'afflusso di clienti?*
Chiediamo il punto di vista del gestore riguardo EasyBeach, per comprendere se anche dal punto di vista dello chalet è percepita come uno strumento utile per aumentare il fatturato e quindi invoglierebbe i gestori al loro utilizzo.

- *Come preferiresti ricevere pagamenti dai clienti che prenotano attraverso EasyBeach?*
Vogliamo capire quali metodi di pagamenti sono preferiti dai gestori, per evitare di implementare poi metodi poco oppure non utilizzati del tutto.

- *Pagheresti una quota per pubblicizzarti all interno dell app (es. comparire tra i risultati sponsorizzati)?*
Si vuole comprendere se un sistema di sponsorizzazione a pagamento possa essere utilizzato e percepito come utile dai gestori dello chalet, oppure sia percepita come una feature non necessaria e superflua.

- *Troveresti utile applicare tariffe personalizzate per chi prenota tramite l' app?*
Si vuole capire se i gestori sarebbero disposti a effettuare tariffe agevolate per le persone che prenotano attraverso l'app. Questo aumenterebbe il numero di utenti della nostra applicazione ma soprattutto potrebbe anche la competizione tra gli chalet, che potrebbero cercare di avere maggiore visibilità rispetto agli altri adottando prezzi più bassi. Risposte positive a questa domanda potrebbero quindi indurre alla specifica nei requisiti di un sistema per effettuare sconti.

- *Gradiresti vedere le statistiche relative alle prenotazioni ricevute attraverso l’applicazione?*
Per far percepire l'utilità o meno della presenza dello chalet nella piattaforma, si chiede se consulterebbe statistiche elaborate per le prenotazioni avvenute presso il suo chalet.

- *Quale mezzo di notifica preferisci per essere avvisato delle prenotazioni?*
Si vuole comprendere il gradimento del gestore riguardo ai diversi metodi di notifica proposti, per implementarli di conseguenza.

- *Ritieni utile un sistema per effettuare recensioni sui clienti?*
Si vuole capire se il gestore ritiene utile e utilizzerebbe un sistema per recensire i clienti che hanno effettuato le prenotazioni nello chalet, per specificarlo tra i requisiti dell'applicazione.  

- *Come preferiresti che la tua pagina chalet sia strutturata?*
Attraverso questa domanda vogliamo capire quali informazioni i gestori degli chalet ritengono debbano essere più in vista nella visita della pagina del singolo chalet, in modo da comprendere quali informazioni abbiano più importanza per loro rispetto ad altre e debbano essere quindi più in vista nella UI.

##### Area cliente
Le domande presenti in quest'area hanno lo scopo di conoscere il punto di vista nei confronti del sistem as-is e del system to-be da parte dei non proprietari di chalet (cioè i potenziali clienti).

- *Con quale frequenza vai al mare in estate?*
Attraverso questa domanda si vuole comprendere la frequenza con cui un cliente di uno chalet va al mare, in quanto in base alla frequenza potrebbero esserci diverse esigenze (es. una persona che va al mare una volta a settimana ha probabilmente più esigenza di utilizzare l'app, poichè potrebbe servirgli potenzialmente per ogni occasione. Una persona che al mare va tutti i giorni invece, probabilmente prende il lettino mensilmente/stagionalmente presso uno chalet conosciuto oppure utilizza comunque l'applicazione poche volte - poichè le prenotazioni potrebbero essere più lunghe). Inoltre se una persona non va mai al mare, non conosce le esigenze ..
TODO: da rivedere

- *Quando vai al mare, vai più spesso in spiagga libera o sugli chalet?*
Ci si vuole rendere conto per le risposte successive se l'utente utilizza effettivamente gli chalet oppure risponde solamente in base alle sue sensazioni (?)
Vogliamo conoscere ulteriori informazioni sul cliente. Le risposte dei clienti che non vanno mai agli chalet potrebbero essere interpretate diversamente rispetto a invece chi utilizza solamente chalet, poichè magari i secondi hanno più familiarità con il dominio dell'applicazione e con le caratteristiche e difficoltà del system as-is (ovvero come vengono effettuate ad oggi le prenotazioni senza metodologie smart).

- *Se dovessi scegliere uno chalet per andare al mare, quale tra queste opzioni preferiresti?*
Attraverso questa domanda vogliamo comprendere sia quale siano effettivamente le abitudini ad oggi degli utenti, in modo da ricevere ulteriori informazioni sugli utenti. Attraverso questa domanda si può inoltre capire quanto potrebbe essere ampio il bacino di utenza della nostra app (probabilmente persone che già utilizzano internet per effettuare ricerche di chalet utilizzeranno l'app con frequenza maggiore rispetto a invece chi preferisce scegliere lo chalet in base al primo che capita).

- *Quale caratteristica consideri prioritaria nella scelta di uno chalet?*
Si vuole comprendere quali siano le informazioni che l'utente ritiene maggiormente utili per la scelta dello chalet, in modo da metterle in primo piano e utilizzarle per effettuare filtri efficaci.

- *Per quale motivo prenoteresti tramite EasyBeach piuttosto che in un altro modo? (Es tramite telefono)*
Si vuole capire cosa spingerebbe l'utente a utilizzare la nostra app piuttosto che qualsiasi altro metodo, per porre eventualmente maggiore attenzione riguardo gli aspetti che l'utente percepisce come prioritari.

- *Ogni gestore per registrare il suo chalet all’interno dell’applicazione deve passare una procedura di verifica. Ritieni che questo metodo possa aumentare la tua fiducia nei confronti del sistema?*
Si vuole comprendere se questo sistema di verifica dell'identità sia effettivamente utile ad aumentare la fiducia dell'utente ed evitare possibili frodi. Se gli utenti non percepiscono questo sistema come utile, potrebbe anche non essere contemplato nei requisiti oppure non essere un requisito primario dell'applicazione.

- *Ritieni che una ricerca filtrata in base alle tue preferenze sia un modo efficace per ricercare chalet adatti?*
Si vuole comprendere se le ricerche filtrate in base agli interessi dell'utente (es. specifico servizio, fascia di prezzo, ..) siano poi effettivamente utilizzate dagli utenti.

- *Ritieni utile anche una mappa per vedere gli chalet più vicini e raggiungerli più facilmente?*
Attraverso questa domanda vogliamo capire se la presenza di una mappa sia una feature importante per i clienti e se quindi sia necessario specificarla tra i requisiti del sistema.


### 5. Analisi delle risposte ricevute dai questionari
### 6 Generazione degli scenari e discussione con gli stakeholder
### Prototipo ?
### 7. Definizione dei requisiti

