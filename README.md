# ProjectLibre
Guida completa al miglior software opensource di Project Management

# Guida Completa a ProjectLibre: Inizia Subito a Gestire i Tuoi Progetti!

---

## Indice
- [1. Introduzione e Primo Avvio: La Tua Porta sul Project Management](#uno)
- [2. Familiarizzare con l'Interfaccia: Il Tuo Centro di Controllo](#due)
- [3. Gestire le Attività: Il Cuore del Tuo Progetto](#tre)
- [4. Collegare le Attività: I Predecessori e i Legami](#quattro)
- [5. Il Cammino Critico (CPM): La Chiave della Durata del Progetto](#cinque)

---

Sei pronto a portare la tua gestione progettuale a un nuovo livello, senza costi? **ProjectLibre** è la soluzione open-source che ti offre tutte le funzionalità essenziali per pianificare, monitorare e gestire i tuoi progetti, proprio come faresti con strumenti più complessi, ma con la flessibilità di una soluzione gratuita.

Questa guida ti accompagnerà passo dopo passo nell'esplorazione di ProjectLibre, partendo dalle basi fino alla comprensione del cruciale **Cammino Critico**, un concetto fondamentale per ogni Project Manager.

---
<a id="uno"></a>
### 1. Introduzione e Primo Avvio: La Tua Porta sul Project Management
ProjectLibre è un'alternativa gratuita e open-source a software come Microsoft Project. Essendo un progetto basato sulla community, avrai accesso a un'ampia documentazione e supporto online, un aspetto cruciale per risolvere dubbi e approfondire funzionalità.

#### Scaricare e Installare ProjectLibre
* **Visita il sito ufficiale**: Il primo passo è andare su [projectlibre.com](https://www.projectlibre.com).
* **Trova il link di download**: Clicca sul pulsante "**Download**". Verrai reindirizzato a [sourceforge.net](https://sourceforge.net/), una piattaforma sicura da cui potrai scaricare il file d'installazione.
* **Processo di installazione**: Una volta scaricato, esegui il file e segui le istruzioni. Potrebbe apparire una schermata per inserire un'email, ma sappi che è un passaggio opzionale e puoi tranquillamente saltarlo per procedere con l'installazione.

#### Il Tuo Primo Progetto
Appena avviato ProjectLibre, ti verrà chiesto di scegliere tra "**Crea Progetto**" o "**Apri Progetto**". Seleziona "**Crea Progetto**" per dare vita alla tua prima pianificazione.

Si aprirà una finestra dove dovrai inserire le informazioni fondamentali del tuo nuovo progetto:

* **Nome Progetto**: Un titolo chiaro che identifichi il tuo progetto (es. "Lancio Nuovo Prodotto X").
* **Responsabile**: La persona o il team a cui è affidata la responsabilità del progetto.
* **Data di Avvio**: La data in cui il progetto è previsto iniziare. Puoi anche impostare una data di fine, e ProjectLibre adatterà la data di avvio di conseguenza, se necessario.

Clicca **OK** per confermare e accedere all'interfaccia principale.

---

### 2. Familiarizzare con l'Interfaccia: Il Tuo Centro di Controllo {#due}
L'interfaccia di ProjectLibre è progettata per essere intuitiva e funzionale. È suddivisa principalmente in due aree e una barra degli strumenti superiore:

* **Tabella delle Attività (a sinistra)**: Questa è la tua area di lavoro principale per inserire e gestire i dettagli delle attività, come nomi, durate, date di inizio e fine, e predecessori.
* **Diagramma di Gantt (a destra)**: La rappresentazione grafica del tuo progetto nel tempo. Qui vedrai le barre che visualizzano la durata delle attività e le dipendenze. Le aree grigie nel diagramma indicano solitamente i giorni non lavorativi, come i weekend.

#### La Ribbon: La Tua Cassetta degli Attrezzi
Nella parte superiore dell'interfaccia, troverai la "**Ribbon**", una barra degli strumenti che raggruppa tutte le funzionalità per categoria. Se passi il mouse su un'icona, apparirà una "**tooltip**" che ti spiegherà la sua funzione, rendendo l'apprendimento rapido e semplice.

* **File**: Per salvare, aprire, chiudere progetti e per opzioni di stampa o esportazione.
* **Attività**: Contiene gli strumenti per la gestione delle attività, le diverse "**viste**" (come il Diagramma di Gantt o la WBS) e le opzioni di copia/incolla (clipboard).
* **Risorse**: Qui gestirai le risorse del tuo progetto (persone, attrezzature) e le relative visualizzazioni.
* **Visualizza**: Per cambiare la modalità di visualizzazione del progetto, applicare filtri e gestire lo zoom.

#### Salvare il Tuo Lavoro
Un aspetto fondamentale: se vedi un asterisco (\*) accanto al nome del tuo progetto nella parte superiore della finestra, significa che hai delle modifiche non salvate. Salva il tuo lavoro regolarmente cliccando sull'icona "**Salva**" o usando la scorciatoia **Ctrl+S**. I progetti vengono salvati con l'estensione predefinita `.pod`.

---

### 3. Gestire le Attività: Il Cuore del Tuo Progetto {#tre}
Le attività sono i mattoni del tuo progetto. Imparare a gestirle efficacemente è essenziale per una pianificazione robusta.

#### Inserire e Impostare le Attività
* **Inserire una nuova attività**: Clicca semplicemente nella colonna "**Nome**" della Tabella delle Attività e digita il nome desiderato.
* **Impostare la durata**: Nella colonna "**Durata**", puoi specificare il tempo stimato per l'attività. Di default, ProjectLibre imposta "**1g**" (1 giorno) con un punto interrogativo, indicando una stima provvisoria. Puoi modificare questo valore usando:
    * "**3g**" per 3 giorni
    * "**4h**" per 4 ore
    * "**10m**" per 10 minuti

La data di chiusura dell'attività si aggiornerà automaticamente in base alla durata inserita.

#### Creare Sotto-Attività (Indentazione)
Per organizzare il tuo progetto in una struttura gerarchica (come una **WBS - Work Breakdown Structure**), puoi creare sotto-attività. Questo ti aiuta a suddividere il lavoro in parti più piccole e gestibili.

1.  Seleziona l'attività che vuoi rendere una sotto-attività.
2.  Nella scheda "**Attività**" della Ribbon, clicca su "**Aumenta Rientro**" (Increase Indent).

L'attività selezionata verrà rientrata, diventando una dipendenza dell'attività superiore. L'attività genitore diventerà un "**gruppo**" che puoi espandere o collassare. La durata del gruppo si adeguerà automaticamente alla durata della sotto-attività più lunga al suo interno. Per annullare il rientro, usa "**Diminuisci Rientro**" (Decrease Indent).

#### Eliminare o Inserire Righe
* **Eliminare un'attività**: Seleziona l'attività e premi il tasto **Canc**.
* **Inserire una riga vuota**: Posizionati nella riga dove desideri inserire una nuova attività e clicca su "**Inserisci Attività**" nella Ribbon.

---

### 4. Collegare le Attività: I Predecessori e i Legami {#quattro}
Le dipendenze tra attività sono fondamentali per definire la sequenza logica del tuo progetto. Un'attività potrebbe non poter iniziare prima che un'altra sia completata.

#### Tipi di Legami
ProjectLibre supporta i tipi di dipendenza standard del Project Management:

* **Fine-Inizio (FS - Finish-to-Start)**: Il tipo più comune. L'attività successiva inizia solo dopo che la precedente è completata. (Es. "Progettazione" deve finire prima che "Sviluppo" possa iniziare). Questo è il legame predefinito.
* **Fine-Fine (FF - Finish-to-Finish)**: Un'attività può finire solo dopo che un'altra è finita. (Es. "Test finale" può finire solo dopo che "Sviluppo" è finito).
* **Inizio-Inizio (SS - Start-to-Start)**: Un'attività può iniziare solo dopo che un'altra è iniziata. (Es. "Installazione infrastruttura" può iniziare dopo che "Acquisto server" è iniziato).
* **Inizio-Fine (SF - Start-to-Finish)**: Un'attività deve iniziare prima che un'altra possa finire. (Meno comune, es. "Vecchia funzionalità disattivata" deve iniziare prima che "Nuova funzionalità attivata" possa finire).

#### Assegnare i Predecessori
Ci sono diversi modi per creare i legami nel tuo progetto:

* **Tramite la colonna "Predecessori"**: Il metodo più diretto. Nella colonna "**Predecessori**" della Tabella delle Attività, digita il numero di riga dell'attività che deve precedere quella corrente. Ad esempio, se l'attività sulla riga 6 deve finire prima che inizi l'attività corrente, scrivi "**6**".
* **Trascinando nel Diagramma di Gantt**: Un metodo visivo. Nel Diagramma di Gantt, trascina una freccia dalla fine della barra dell'attività predecessore all'inizio della barra dell'attività successiva.
* **Usando lo strumento "Inserisci Collegamento"**: Seleziona le due attività che vuoi collegare e usa lo strumento "**Inserisci Collegamento**" (Insert Link) nella Ribbon.

Le dipendenze sono visualizzate come frecce nel Diagramma di Gantt, indicando il flusso logico del tuo progetto. Per eliminare un legame, puoi selezionare l'attività e rimuovere il numero di riga nella colonna "**Predecessori**" o selezionare la freccia nel Gantt e premere "**Canc**".

---

### 5. Il Cammino Critico (CPM): La Chiave della Durata del Progetto {#cinque}
Come Project Manager, la comprensione del **Cammino Critico (Critical Path Method - CPM)** è fondamentale per la gestione dei tempi.

#### Cos'è il Cammino Critico?
Il **Cammino Critico** è la sequenza più lunga di attività interconnesse nel tuo progetto, dalla data di inizio alla data di fine. È "**critico**" perché determina la durata complessiva minima del progetto. Qualsiasi ritardo in un'attività che fa parte del cammino critico si tradurrà direttamente in un ritardo dell'intero progetto. Le attività non sul cammino critico, invece, hanno un certo margine di flessibilità (chiamato "**slack**" o "**float**") senza influenzare la data di fine complessiva.

#### Identificare il Cammino Critico in ProjectLibre
ProjectLibre ti aiuta a identificare visivamente il cammino critico:

* Nel Diagramma di Gantt, le attività che fanno parte del cammino critico sono evidenziate in **rosso**.
* Le attività non critiche sono visualizzate in **blu**.

Questa distinzione visiva ti permette di concentrare la tua attenzione sulle attività più sensibili per mantenere il progetto in linea con le scadenze. È importante notare come l'assegnazione di più predecessori a una singola attività possa influenzare la durata e il cammino critico, e come i legami tra attività raggruppate (sotto-attività) vengano considerati nel calcolo.
