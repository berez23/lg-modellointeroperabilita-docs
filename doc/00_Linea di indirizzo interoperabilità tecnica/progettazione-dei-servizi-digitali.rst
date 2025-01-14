Progettazione dei servizi digitali
==================================

Nella realizzazione delle proprie funzioni istituzionali le Pubbliche
Amministrazioni implementano procedimenti amministrativi, definendo
processi con l’obiettivo di realizzare servizi ai cittadini e imprese
efficienti ed efficaci.

Un servizio consiste in un’attività o in una serie di attività svolte in
uno scambio tra un fornitore e un cliente.

Se l’efficacia è determinata dal soddisfacimento della norma,
l’efficienza può essere incrementata utilizzando gli strumenti propri
della Information and Communication Technology (ICT).

I processi che utilizzano gli strumenti ICT sono qui detti processi
digitali.

Un e-service è un servizio erogato via Internet o attraverso una rete
privata tramite un processo digitale in cui sono coinvolti erogatori e
fruitori.

Gli e-service di interesse della Linea di indirizzo sono caratterizzati
da:

-  il descrittore dell’e-service, un’entità che descrive l’obiettivo e
   le modalità per usufruire del servizio;

-  le API che comprendono le modalità di accesso ad un e-service, le cui
   implementazioni tecnologiche si basano sulla combinazione dei pattern
   di interoperabilità e sicurezza o l'utilizzo di profili di
   interoperabilità;

-  gli accordi di interoperabilità in cui sono definiti i legami tra
   fruitore ed erogatore.

Si assume che le Pubbliche Amministrazioni siano viste come un'entità
unica da cittadini e imprese, e che, coordinandosi e collaborando,
forniscano servizi.

Ne consegue che la realizzazione di un processo digitale necessita di un
modello organizzativo che individui ruoli e responsabilità dei soggetti
coinvolti. Nel caso in cui il servizio offerto necessiti di interazioni
tra diverse Pubbliche Amministrazioni il modello organizzativo deve
essere condiviso dalle stesse.

Il processo digitale determina l’insieme di e-service:

-  necessari ad assicurare l'interazione tra le Pubbliche
   Amministrazioni (e-service di backend);

-  finalizzati ad assicurare l’offerta di e-service a cittadini e
   imprese (e-service di frontend).

La conoscenza della disponibilità e le modalità di utilizzo degli
e-service di backend e dei servizi di front-end, utilizzati direttamente
da sistemi informatici, è assicurata dalla pubblicazione sul Catalogo
delle API previsto nel ModI.

Tali azioni sono realizzate direttamente dagli erogatori di e-service o
da un ente capofila.

|image0|

*Figura 2 - (A) Processo Digitale Semplice. (B) Processo Digitale
Collettivo*

Nell’ambito del ModI, con processi digitali semplici si intendono i
processi digitali che vedono coinvolta un singolo erogatore verso i
cittadini e le imprese. Viceversa, con processi digitali collettivi si
indicano i processi digitali che vedono coinvolte più organizzazioni.

Di seguito sono descritte delle buone pratiche per:

-  supportare l’interoperabilità dei sistemi informatici;

-  favorire il riutilizzo degli e-service.

Per dare seguito alla trasformazione digitale della Pubblica
Amministrazione, nel ModI, la definizione dei processi digitali deve
assicurare il rispetto dei principi del digital-by-default [1]_ e
once-only [2]_.

La definizione di un processo digitale è avviata da una Pubblica
Amministrazione ed è composta dalle seguenti fasi:

1. Individuazione delle esigenze.

Fase in cui vengono determinate le esigenze, attraverso cui l'erogatore:

a. analizza la norma per determinare le funzioni di competenza e gli
   obiettivi da raggiungere. Sulla base di questi, evidenzia le
   caratteristiche del servizio da offrire, e individua i dati in
   ingresso e quelli restituiti.

b. determina se coinvolgere altre organizzazioni quali fonti
   autoritative dei dati necessari o soggetti preposti all’esecuzione di
   endoprocedimenti specifici.

c. determinare le attività necessarie ad implementare ed assicurare
   l’implementazione del servizio da offrire.

2. Organizzativa.

Fase in cui l'erogatore in base al punto 1.b coinvolge o meno altre
organizzazioni:

d. se non sono state individuate altre organizzazioni, l'erogatore
   realizza un processo digitale semplice in cui:

   i.  valuta la possibilità soddisfare le esigenze riusando e/o
       reingegnerizzando uno o più e-service già erogati;

   ii. altrimenti implementa nuovi e-service progettandoli in modo da
       favorirne il riuso.

e. se sono state individuate altre organizzazioni si realizza un
   processo digitale collettivo dove:

   iii. l'erogatore individua le organizzazioni da coinvolgere in quanto
        fonti autoritative dei dati o soggetti preposti all’esecuzione
        di endoprocedimenti, evitando la duplicazione non necessaria dei
        dati;

   iv.  l'erogatore si confronta con esse per determinare ruoli e
        responsabilità;

   v.   ogni organizzazione, per dare seguito alle responsabilità
        individuate:

        1. valuta la possibilità soddisfare le esigenze riusando e/o
           reingegnerizzando uno o più e-service già erogati;

        2. altrimenti implementa nuovi e-service progettandoli in modo
           da favorirne il riuso.

3. Semantica.

Fase in cui le organizzazioni interessate, definiscono il modello dati
da utilizzare (entità, proprietà e relativa metadatazione). La
definizione del modello dati è realizzata in coerenza con i vocabolari
controllati e modelli di dati definiti a livello nazionale e
internazionale.

4. Tecnica.

Fase in cui le organizzazioni interessate provvedono, ove necessario, a
garantire la conformità al modello dati da utilizzare degli e-service
individuati in fase di individuazione e/o implementazione delle API, per
assicurare la disponibilità degli e-service.

5. Governance dei servizi.

Fase in cui ciascuna erogatore pubblica sul Catalogo le API
implementate, in modo da incentivare l'utilizzo ed il riuso.

Stipula degli accordi di interoperabilità, dove sono formalizzati ruoli
e responsabilità delle parti (erogatore e fruitore), per assicurare che
le Pubbliche Amministrazioni interessate possano usufruire di un
e-service fornito da un’altra PA attraverso un’API.

.. toctree::
  :maxdepth: 3
  :caption: Indice dei contenuti

  progettazione-dei-servizi-digitali/individuazione-delle-esigenze.rst
  progettazione-dei-servizi-digitali/organizzativa.rst
  progettazione-dei-servizi-digitali/semantica.rst
  progettazione-dei-servizi-digitali/tecnica.rst

.. [1]
   Il principio digital-by-default prevede che sia data priorità
   all'utilizzo dei servizi pubblici tramite canali digitali,
   preservando l’erogazione multicanale, ovvero coesistenza di canali
   fisici e digitali.

   https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52016DC0179&from=EN

.. [2]
   Il principio del once-only prevede che cittadini ed imprese non
   debbano farsi carico di fornire la certificazione dei propri stati
   già conosciuti dalla Pubblica amministrazione, nel rispetto della
   norma sulla protezione dei dati personali.

.. |image0| image:: ./media/image2.png
   :width: 4.33333in
   :height: 6.83333in
