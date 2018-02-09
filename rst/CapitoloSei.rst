================================================
Cap 6 | Costruire software gestionali e piattaforme digitali nella PA
================================================


6.1 La metodologia del “function point”
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: imgrel/functionpoint.png
   :alt: function point
   :align: center
   
   fondamentali del function point (fonte dell’immagine: `video <https://www.youtube.com/watch?v=N2-9GC7__P8>`_)

Il **Function point** è: 
un *“metodo di progettazione del software, definito nell'Azienda IBM da Allan Albrecht tra il 1975 ed il 1980”*. Gli elementi di conteggio nella metodologia del “function point” sono:
- internal logical file (ILF), i file interni dell'applicazione;

- external interface file (EIF), i file esterni all’applicazione;

- external input (EI), attività elementari di Input;

- external output (EO), attività elementari di Output;

- external inquiry (EQ), attività elementari di interrogazione.

**Function point → per arrivare al budget**

Al fine della creazione del software, questa metodologia riporta il “function point” (il punto di funzione) analizzato, al parametro “giorni” o “ore” di lavoro per la quantificazione in termini di budget di spesa. Non focalizza l’attenzione sulla quantità di righe di codice create, se sono tante o poche per lo stesso “punto di funzione”, importa solo i giorni o ora di lavoro per persona impiegati per la realizzazione.

.. figure:: imgrel/videopiacentini.PNG
   :alt: video Piacentini
   :align: center
   
   Ascoltiamo, in un `intervista <https://youtu.be/8j9U54m5Shk?t=1727>`_, cosa pensa il Commissario tecnico del `Team Trasformazione Digitale <https://teamdigitale.governo.it/>`_ dell’Agenzia per l’Italia Digitale, `Diego Piacentini <https://teamdigitale.governo.it/it/people/1-profile.htm>`_, del *“function point”*  nella fase di costruzione dei software gestionali
   
.. important::
   **Da Piacentini arriva un messaggio chiaro → costruire “digital service” da fruire online, non “siti web”**

**Sempre sul “function point” altri punti di vista autorevoli**:

**↓**

`Fabio Pistella <https://www.linkedin.com/in/fabio-pistella-846457ba/>`_, ex presidente del `CNIPA <https://it.wikipedia.org/wiki/DigitPA>`_ (Centro Nazionale per l’Informatica nella Pubblica Amministrazione, sostituito dal 2012 dall’Agenzia per l’Italia digitale), si esprime sul “function point”, in occasione della Commissione parlamentare di inchiesta sul livello di digitalizzazione e innovazione della Camera (`Seduta n. 6 di Martedì 17 gennaio 2017 <http://documenti.camera.it/leg17/resoconti/commissioni/stenografici/html/73/audiz2/audizione/2017/01/17/indice_stenografico.0006.html>`_):

.. figure:: imgrel/fabiopistella.png
   :alt: Fabio Pistella
   :align: center
   
   ricerca del termine “function point” nel testo dei lavori della Camera dei Deputati nella seduta del 17 gennaio 2017
   
**Sul “function point” si esprime anche la Commissione parlamentare di inchiesta sul livello di digitalizzazione e innovazione delle PA**:

.. figure:: imgrel/testocommissione.png
   :alt: testo commissione
   :align: center
   
|

Paolo Coppola, onorevole della Commissione parlamentare di inchiesta sul livello di digitalizzazione e innovazione delle PA, dopo un anno di lavoro di indagine sulla digitalizzazione delle PA rileva, in `un articolo <https://www.agendadigitale.eu/cultura-digitale/coppola-la-pa-dello-spreco-digitale-la-nostra-galleria-degli-orrori-rivela-la-vera-causa/>`_, che “la radice delle inefficienze sta nell'assoluto disinteresse della PA riguardo alle competenze digitali”.

Qualcuno nelle PA deve cominciare, quindi, a interessarsi di competenze digitali, avviando cicli di sensibilizzazione e formazione ai dirigenti e ai dipendenti, così come si fa con i corsi obbligatori per la conoscenza dei Piani Anti Corruzione ai sensi del Decreto Legislativo 33/2013.

|

.. figure:: imgrel/cameradeputati.png
   :alt: camera deputati
   :align: center
   
Sul “function point” così relaziona, a fine ottobre 2017, la Commissione parlamentare di inchiesta sul livello di digitalizzazione e innovazione delle PA nella `relazione finale <https://relazione-commissione-digitale.readthedocs.io/it/latest/index.html>`_ (al paragrafo Indicazioni Conclusive): per quanto riguarda il procurement dei sistemi informativi, sarebbe di utilità aggiornare le linee guida, imponendo una disciplina dei bandi che preveda studi di fattibilità e progettazione dei sistemi informativi prima della messa a bando della realizzazione, in modo da specificare meglio gli obiettivi di digitalizzazione e gli indicatori di risultato del progetto. Si deve uscire dalla logica del massimo ribasso sul costo dei function point e passare ad una logica di prodotto, con opportune metriche di qualità. `Qui una sintesi <https://medium.com/@cirospat/sintesi-zen-del-report-della-commissione-parlamentare-dinchiesta-sul-livello-di-digitalizzazione-4bc10e081fa4>`_ della relazione della Commissione parlamentare.

|
   
6.2 I “micro servizi” nella progettazione del software per la PA
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Probabilmente le software house chiamate a costruire piattaforme digitali nella PA dovrebbero/potrebbero spostare una dose di attenzione e risorse dal metodo del “function point” ad altri aspetti della progettazione:

→ il co-design del servizio digitale da realizzare, con attenzione agli aspetti di facile usabilità sia dal lato utente cittadino che dal lato dipendente pubblico, e agli aspetti di facile implementazione della piattaforma, prevedendo un approccio progettuale per micro-servizi (tanti piccoli servizi che svolgono funzioni specifiche e interoperabili tra loro anziché una sola mega piattaforma complessa);

→ le buone prassi delle altre amministrazioni pubbliche che hanno realizzato piattaforme digitali oggi usate quotidianamente, e per questo fare riferimento al cosiddetto `“riuso applicativo” <http://www.agid.gov.it/agenda-digitale/pubblica-amministrazione/riuso-software>`_, uno spazio online dove molte PA hanno censito il software progettato, utilizzato e messo a disposizione gratuitamente di altre Amministrazioni.

.. figure:: imgrel/microservizi.png
   :alt: micro servizi
   :align: center
   
   la logica dei micro-servizi nelle piattaforme digitali dell’Associazione dei Comuni Trentini (`da un webinar con intervento di Gabriele Francescotto <https://drive.google.com/file/d/0B9q5qob_W3NiSVlFRTdEMFNwSmJjekR5aUJBYmgwMGFKbW13/view>`_)

.. important::
   Pillole curative: 
   
   **Software, non solo “cosa fa” →  ma “come lo fa”**
   Inserire — nella costruzione del software — un focus, oltre al “cosa fa”, anche al “come lo fa”, tenendo sempre in mente come riferimento 1)la semplificazione dei processi e 2)l’esperienza d’uso del software.
   
Oggi, rispetto agli anni 80, considerati i progressi nel campo della Tecnologia della Comunicazione e dell’Informazione, c’è un ampia disponibilità di strumenti e metodi (mercato) per analizzare i criteri di costruzione di un applicativo necessario a gestire in digitale i processi della PA, ed è più facile effettuare una scelta tenendo in considerazione “come” i software gestiscono le singole azioni, quelle azioni con cui dipendenti e cittadini dovranno interfacciarsi quotidianamente su un monitor.

Gli strumenti per la generazione e la diffusione di servizi digitali sono quelli previsti dal cap. 7 del `Piano Triennale per l’Informatica nella PA 2017–19 <http://pianotriennale-ict.readthedocs.io/it/latest/doc/07_strumenti-per-la-generazione-e-la-diffusione-di-servizi-digitali.html>`_.

.. figure:: imgrel/pianoict.png
   :alt: piano ict
   :align: center
 
