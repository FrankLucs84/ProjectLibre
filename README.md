<a id="inizio-pagina"></a>
# ProjectLibre
Guida completa al miglior software opensource di Project Management

# Guida Completa a ProjectLibre: Inizia Subito a Gestire i Tuoi Progetti!

---

## Indice
- [1. Introduzione e Download del Software](#introduzione-download-guida)
- [2. Creazione e Gestione del Primo Progetto](#creazione-gestione-progetto-guida)
- [3. L'Interfaccia: Ribbon, Finestre e Schede](#interfaccia-ribbon-guida)
- [4. Gestione delle Attività e della Work Breakdown Structure (WBS)](#gestione-attivita-wbs-guida)
- [5. I Predecessori e i Legami tra Attività](#predecessori-legami-guida)
- [6. Il Diagramma di Gantt](#diagramma-gantt-guida)
- [7. Le Risorse](#risorse-guida)
- [8. I Milestone](#milestone-guida)
- [9. Le Baseline](#baseline-guida)
- [10. La Critical Path Method (CPM) su ProjectLibre](#cpm-guida)
- [11. I Report](#report-guida)

---

## Scaletta di Apprendimento di ProjectLibre (Aggiornata)

### 1. Introduzione e Download del Software
* Comprendere cos'è ProjectLibre: un software gratuito e open-source, alternativa a Microsoft Project.
* Capire l'importanza della community e della documentazione per il supporto.
* Scaricare e installare il software da projectlibre.com o sourceforge.net.

### 2. Creazione e Gestione del Primo Progetto
* Avviare ProjectLibre e scegliere di creare un nuovo progetto.
* Inserire le informazioni principali del progetto: nome, responsabile e data di avvio/fine.
* Imparare a salvare il progetto (Ctrl+S o tasto "Salva") e riconoscere i progetti non salvati (asterisco nel titolo).
* Comprendere il formato di salvataggio predefinito (.pod) e l'opzione "Salva con nome".
* Gestire più progetti aperti contemporaneamente.

### 3. L'Interfaccia: Ribbon, Finestre e Schede
* Familiarizzare con la "Ribbon", la barra degli strumenti superiore, che contiene tutti gli strumenti.
* Utilizzare le "tooltip" (informazioni a comparsa) per capire la funzione di ogni strumento passando il mouse.
* Capire come annullare o ripetere le modifiche.
* Gestire le impostazioni della lingua.
* Esplorare le schede principali: File, Attività, Risorse, Visualizza.

### 4. Gestione delle Attività e della Work Breakdown Structure (WBS)
* **Cos'è la WBS?** Comprendere che è una tecnica per scomporre un progetto in parti elementari (work breakdown elements) per capirne meglio la struttura e comunicare le fasi agli stakeholder. Può essere paragonata alla programmazione top-down.
* **Work Package**: Identificare le azioni finali da svolgere nell'ultimo livello gerarchico della WBS, chiamate "work package". Un work package è descritto chiaramente, assegna un compito a un solo responsabile e include attività, obiettivi, risorse (umane e materiali), date di inizio/fine, output (deliverable).
* **Inserire Attività e Strutturare la WBS**:
    * Comprendere la struttura dell'interfaccia principale: Tabella delle Attività (sinistra) e Diagramma di Gantt (destra).
    * Inserire nuove attività nella tabella.
    * Creare sotto-attività (indentazione) usando "Aumenta Rientro" (Increase Indent) nella scheda "Attività" per costruire la gerarchia della WBS. Le attività raggruppate visualizzano la durata dell'attività secondaria più lunga.
    * Applicare la "regola del 100%" alla WBS: ogni livello del progetto deve rappresentare il 100% del lavoro che lo compone, e la somma dei livelli inferiori deve dare il 100% del loro livello padre.
    * Eliminare e inserire righe per le attività.
* **Impostare la Durata delle Attività**:
    * Specificare la durata (es. "3d" per giorni, "4h" per ore, "10m" per minuti).
    * Utilizzare il punto interrogativo (es. "3?") per indicare che una durata è prevista ma non certa. È possibile anche inserire una colonna "previsto" per spuntare se la durata è certa o meno.
* **Impostazioni del Calendario**:
    * Visualizzare il calendario e impostare i giorni non lavorativi (es. sabato e domenica) per non contarli nel calcolo del tempo.
    * Impostare le ore lavorative per giorno, settimana e mese (es. 8 ore/giorno, 40 ore/settimana, 20 giorni/mese).
    * Impostare un vincolo di avvio per un'attività o l'intero progetto (es. "non iniziare prima del...").

### 5. I Predecessori e i Legami tra Attività
* Comprendere il concetto di dipendenza tra attività.
* **Conoscere i tipi di legami**:
    * Finish-to-Start (FS) (predefinito): una attività inizia dopo che l'altra finisce.
    * Start-to-Start (SS): l'inizio di un'attività dipende dall'inizio di un'altra.
    * Finish-to-Finish (FF): la fine di un'attività dipende dalla fine di un'altra.
    * Start-to-Finish (SF): l'inizio di un'attività è subordinato alla fine di un'altra.
* **Assegnare i predecessori**:
    * Utilizzando la colonna "Predecessori" (inserendo il numero di riga dell'attività precedente e il tipo di legame, es. "6" o "6SS").
    * Trascinando il mouse direttamente nel Diagramma di Gantt.
    * Utilizzando lo strumento "Inserisci Collegamento".
* Eliminare i legami tra attività.
* Assegnare più predecessori a una singola attività, separandoli con un punto e virgola (es. "10;12").

### 6. Il Diagramma di Gantt
* Il **Diagramma di Gantt** è una rappresentazione grafica del progetto nel tempo, che mostra le attività, la loro durata e le dipendenze.
* È un supporto per la WBS, visualizzando i tempi di sviluppo e le relazioni tra attività.
* Permette di monitorare e modificare le date del progetto in corso d'opera.
* Può mostrare i collegamenti tra attività (frecce) e le righe della griglia del calendario.

### 7. Le Risorse
* **Creazione delle Risorse**: In ProjectLibre è possibile inserire risorse di tipo "Lavoro" (persone) o "Materiale" (es. carta, computer). Per le risorse di tipo "Lavoro", si impostano il compenso orario standard e quello straordinario. Per le risorse "Materiale", si imposta il costo per utilizzo.
* **Assegnazione delle Risorse**: Le risorse vengono associate alle attività per indicare chi o cosa è coinvolto. I nomi delle risorse appaiono accanto alle barre nel Diagramma di Gantt.
* **Impatto delle Risorse sulla Durata**: Di default, ProjectLibre può ridurre la durata di un'attività se vengono assegnate più persone ( "unità fissa"). Se si vuole che la durata rimanga invariata nonostante più risorse, si può impostare l'attività come a "durata fissa".

### 8. I Milestone
* I **milestone** (pietre miliari) sono punti focali o traguardi importanti nel progetto.
* Vengono utilizzati per verificare lo stato di avanzamento dei lavori e capire a che punto si è arrivati.
* In ProjectLibre, un milestone viene inserito come una normale attività, ma con una durata di 0 (zero) giorni. Nel Diagramma di Gantt appaiono come un simbolo specifico. Solitamente non ci sono più di 3-4 milestone oltre quello iniziale e finale.

### 9. Le Baseline
* Una **baseline** è una "fotografia" dello stato di avanzamento del progetto in un determinato momento, solitamente all'inizio.
* Permette di confrontare lo stato attuale del progetto con la sua pianificazione originale.
* Se si verifica uno scostamento dei tempi rispetto alla baseline, è possibile correggere il progetto (es. accorciare i tempi, aggiungere risorse) e salvare una nuova baseline per futuri confronti.

### 10. La Critical Path Method (CPM) su ProjectLibre
* Capire cos'è il "**Cammino Critico**": il percorso più lungo di attività interconnesse nel progetto.
* Comprendere che il cammino critico determina la durata complessiva del progetto.
* Identificare le attività critiche, che sono visualizzate in rosso nel Diagramma di Gantt. Le attività non critiche sono in blu.

### 11. I Report
* ProjectLibre offre diversi report per visualizzare i risultati del progetto:
    * **Network Diagram**: Rappresentazione grafica delle attività e dei loro collegamenti/sequenze.
    * **WBS**: Mostra i livelli della WBS con i costi associati a ogni livello.
    * **Uso Attività/Uso Risorse**: Elenchi dettagliati delle risorse utilizzate in ogni attività e il loro impegno.
    * **Istogramma**: Per ogni risorsa, mostra l'utilizzo nel tempo.
    * **Filtri**: Permettono di visualizzare attività specifiche (es. attività extra budget).
* Il Diagramma di Gantt stesso è uno strumento flessibile che aiuta a ridefinire il progetto.

---

## Breve Guida Semplice a ProjectLibre (Aggiornata)

ProjectLibre è un software gratuito e open-source che ti aiuta a gestire i tuoi progetti, offrendo una valida alternativa a Microsoft Project. È supportato da una community online e dispone di documentazione.

<a id="introduzione-download-guida"></a>
### 1. Iniziare: Download e Installazione
Per iniziare, vai su [projectlibre.com](https://www.projectlibre.com). Clica sul pulsante "**Download**" e verrai reindirizzato a [sourceforge.net](https://sourceforge.net/), dove potrai scaricare l'installer. Puoi anche trovare un link diretto sul sito del produttore ProjectLibre open source. Una volta scaricato, esegui l'installazione guidata.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="creazione-gestione-progetto-guida"></a>
### 2. Creare il Tuo Primo Progetto
Quando avvii ProjectLibre, scegli "**Crea Progetto**". Inserisci il **Nome Progetto**, il **Responsabile** e la **Data di Avvio** (o chiusura, che regolerà l'avvio). Clica "**OK**". Ricorda di salvare il tuo progetto (Ctrl+S o icona "**Salva**") per non perdere le modifiche (l'asterisco nel titolo indica modifiche non salvate). I progetti vengono salvati con estensione `.pod`. Puoi avere più progetti aperti contemporaneamente.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="interfaccia-ribbon-guida"></a>
### 3. Familiarizzare con l'Interfaccia
L'interfaccia principale è divisa in due parti:
* **Tabella delle Attività (a sinistra)**: Qui gestisci i dettagli delle tue attività.
* **Diagramma di Gantt (a destra)**: Una rappresentazione grafica del tuo progetto nel tempo.
In alto, la "**Ribbon**" contiene tutti i comandi. Passando il mouse sulle icone, vedrai una descrizione (tooltip). Puoi annullare o ripetere le modifiche. Le schede principali sono **File**, **Attività**, **Risorse**, **Visualizza**.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="gestione-attivita-wbs-guida"></a>
### 4. Gestire Attività e Strutturare il Progetto (WBS)
* **Cos'è la WBS?** La **Work Breakdown Structure (WBS)** ti aiuta a scomporre un progetto in parti più piccole e gestibili, creando una gerarchia. Le "azioni" finali di questa scomposizione sono chiamate "**work package**". Ogni parte del progetto deve rispettare la "**regola del 100%**", ovvero la somma delle sue sotto-parti deve rappresentare il 100% del lavoro di quel livello.
* **Inserire e Organizzare Attività**: Digita il nome dell'attività nella colonna "**Nome**". Per creare sotto-attività (e quindi costruire la tua WBS), seleziona l'attività e usa "**Aumenta Rientro**" (Increase Indent) nella scheda "**Attività**". Le attività raggruppate (i "livelli" della WBS) mostreranno la durata della sotto-attività più lunga al loro interno.
* **Durata delle Attività**: Nella colonna "**Durata**", inserisci un numero seguito da "**g**" (giorni), "**h**" (ore) o "**m**" (minuti). Se la durata è solo una stima, puoi aggiungere un punto interrogativo (es. "**3g?**") per indicare che non è certa.
* **Calendario e Vincoli**: Puoi impostare i giorni non lavorativi (es. sabato e domenica) e le ore lavorative giornaliere, settimanali o mensili tramite il pulsante "**Calendario**". Puoi anche impostare un vincolo di avvio per un'attività o il progetto, come "non iniziare prima del...".

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="predecessori-legami-guida"></a>
### 5. Collegare le Attività (Predecessori)
Le attività possono dipendere l'una dall'altra. Per collegarle:
* **Colonna "Predecessori"**: Inserisci il numero di riga dell'attività che deve precedere.
* **Tipi di Legame**: Di default, ProjectLibre usa il legame "**Fine-Inizio**" (FS), cioè un'attività inizia solo dopo che la precedente è finita. Puoi cambiarlo (doppio click sulla cella dei predecessori) in "**Inizio-Inizio**" (SS) (entrambe iniziano insieme), "**Fine-Fine**" (FF) o "**Inizio-Fine**" (SF).
* **Trascina nel Gantt**: Clica sull'estremità di una barra nel Gantt e trascina sulla barra dell'attività successiva per creare un legame.
* **Strumento "Inserisci Collegamento"**: Seleziona le attività e usa questo strumento nella Ribbon.
* Per assegnare più predecessori a un'attività, inserisci i numeri di riga separati da un punto e virgola (es. "**10;12**") nella colonna "**Predecessori**".

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="diagramma-gantt-guida"></a>
### 6. Il Diagramma di Gantt
È la rappresentazione visiva del tuo progetto. Mostra le attività come barre, la loro durata e i legami (frecce) tra di esse. Ti aiuta a vedere come il progetto si sviluppa nel tempo e a monitorare i progressi.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="risorse-guida"></a>
### 7. Le Risorse
* **Creare Risorse**: Nella scheda "**Risorse**", puoi aggiungere persone (tipo "**Lavoro**") o materiali (tipo "**Materiale**"). Per le persone, inserisci un costo orario. Per i materiali, un costo per utilizzo.
* **Assegnare Risorse**: Torna nella scheda "**Attività**". Nella colonna "**Nome Risorse**", fai doppio clic o usa il pulsante "**Assegna Risorse**" per scegliere chi o cosa lavorerà su un'attività. I nomi delle risorse appariranno accanto alle attività nel Gantt.
* **Durata Fissa vs. Unità Fissa**: Se assegni più risorse a un'attività, ProjectLibre potrebbe ridurre automaticamente la durata (modalità "**unità fissa**"). Se vuoi che la durata dell'attività rimanga quella impostata, indipendentemente dal numero di risorse, puoi impostarla come "**durata fissa**".

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="milestone-guida"></a>
### 8. I Milestone
I **milestone** sono punti chiave o traguardi importanti nel tuo progetto. Servono a monitorare l'avanzamento. Per inserirli, crea un'attività e imposta la sua durata a 0 (zero) giorni. Nel Diagramma di Gantt, saranno rappresentati da un simbolo specifico.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="baseline-guida"></a>
### 9. Le Baseline
Una **baseline** è una "fotografia" del tuo progetto in un momento specifico (di solito all'inizio). Ti permette di confrontare lo stato attuale del progetto con la sua pianificazione originale. Se il progetto devia dalla baseline, puoi apportare correzioni e salvare una nuova baseline per tenere traccia delle modifiche.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="cpm-guida"></a>
### 10. Il Cammino Critico (Critical Path Method - CPM)
Il **Cammino Critico** è la sequenza di attività più lunga del tuo progetto che determina la sua durata totale. Le attività che ne fanno parte sono visualizzate in **rosso** nel Diagramma di Gantt, indicando che qualsiasi ritardo su di esse ritarderà l'intero progetto.

[⬆️ Torna all'inizio](#inizio-pagina)

<a id="report-guida"></a>
### 11. I Report
ProjectLibre può generare diversi report per analizzare il tuo progetto:
* **Network Diagram**: Mostra i collegamenti tra tutte le attività.
* **WBS**: Dettaglia i costi per ogni livello della tua Work Breakdown Structure.
* **Uso Attività** e **Uso Risorse**: Riportano dettagli sull'impegno delle risorse e sull'utilizzo delle attività.
* **Istogramma**: Grafici che mostrano l'utilizzo delle risorse nel tempo.
* **Filtri**: Permettono di visualizzare attività specifiche (es. attività extra budget).

[⬆️ Torna all'inizio](#inizio-pagina)
