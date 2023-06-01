# APPUNTI e DOMANDE d'ESAME - INTERAZIONE UOMO MACCHINA

***Un prodotto che nessuno compra è un prodotto inutile***

## Appunti

### design

HMI

design prodotto

design esperienza

design interfaccia

### HCD

schema HCD

- specificare il contesto d'uso
- specificare i requisiti
- progettare la soluzione
- testare e valutare

usabilità

### Progettazione delle interfacce

discoverability e understanding

design of useful things

incidente di three mile island

### Principi fondamentali dell'interazione

esperienza

affordance

significanti

mapping

feedback

modello concettuale

immagine di sistema

### Vincoli

classi di vincoli:

- vincoli fisici
- vincoli culturali
- vincoli semantici
- vincoli logici

funzioni obbliganti

- interlock
- lock-in
- lock-out
  
comandi centrati sulle attività

### Come le persone fanno le cose

golfi dell'esecuzione e della valutazione

i 7 stati dell'azione

- scopo
- progettare
- specificare
- eseguire
- percepire
- interpretare
- confrontare

i 7 principi fondamentali della progettazione

- cosa voglio ottenere?
- quali sono le sequenze d'azione alternative?
- quale azione posso fare ora?
- cosa è successo?
- cosa significa?
- va bene? ho realizzato il mio scopo?

i 7 principi fondamentali del design

- visibilità
- feedback
- modello concettuale
- affordance
- significanti
- mapping
- vincoli
  
pensiero umano

tipi di memoria:

- memoria dichiarativa
- memoria procedurale

processing del cervello:

- livello viscerale
- livello comportamentale
- livello riflessivo

### Errore Umano

root cause analysis

i cinque perché

definizione di errore

- lapsus o slips
  - di azione
  - di memoria
  - mistakes
- rule based
  - knowledge based
  - knowledge based
  - memory lapse

prevenzione dell'errore

- comprendere le cause dell'errore
- controlli di sensibilità
- annunciare le azioni
- rendere più semplice la scoperta e comprensione degli errori
- aiutare l'utente a compiere correttamente le azioni

per la prevenzione dell'errore utilizzare:

- constraints
- undo
- messaggi di errore e di conferma
- aumentare il numero di controlli
- migliorare il modello concettuale dell'utente
- allertare l'operatore umano quando ci si avvicina a un errore

### Le interfacce utente

livelli di interfacce:

- Human Interface Device (HID)
- Human Machine Interface (HMI)
- Human Computer Interface (HCI)

classificazione delle interfacce:

- tactile UI
- visual UI
- auditory UI
- olfactory UI
- gustatory UI
- equilibrial UI

interfacce che utilizzano più di un senso:

- Composite User Interface (CUI) e  classificazione
  - macrocategorie
    - standard
    - virtual
    - augmented
  - classificazione per numero di sensi
- Graphical User Interface (GUI)
- Multimodal User Interface (MUI)

### Human Interface Design (HID)

protocollo HID

- identità:
  - device
  - host
- protocolli
  - bluetooth HID
  - serial HID
  - ZigBee HID
  - HID over I2C
  - HOGP
  
periferiche HID

- testi e caratteri
  - tastiere
    - layout fisico
    - layout virtuale
    - layout funzionale
  - lettore codici a barre
- sistemi di puntamento
  - classificazione
    - tipo di input
      - diretto
      - indiretto
    - modo in cui il movimento viene mappato
      - assoluto
      - relativo
    - come i dispositivi producano il segnale
      - isotonico
      - isometrico
      - elastico
    - velocità in cui si fa avanzare il puntatore
      - position control
      - rate control
  - esempi
    - eye tracker
      - bright pupil
      - dark pupil
      - passive light  
    - gaze tracking
    - data glove
    - dispostivi aptici
    - smart papers
    - lavagne digitali
- dispositivi per il suono
  - microfono
  - array di microfoni
- sensori di immagini
  - 3D scanning
    - passivi
      - camere stereoscopiche
      - sistemi fotometrici
      - tecniche silhouette
    - attivi
      - time-of-flight
      - triangolazione
      - scanner 3D a luce strutturata
      - scanner 3D a luce modulata
- inertial measurement unit (IMU)
- dispositivi wearable

### Natural User Interface (NUI)

per essere tale:

- apprendimento progressivo
- expertise instantanea
- interazione diretta
- basso carico cognitivo

una strategia per realizzare NUI è l'uso della Reality User Interface (RUI)

### Graphical User Interface (GUI)

struttura dell'interfaccia

- struttura gerarchica
- struttura sequenziale
- struttura matriciale
- struttura a database

architettura dell'informazione

- componenti principali:
  - schemi o strutture organizzative
  - sistemi di labelling
  - sistemi di navigazione
  - sistemi di ricerca
- tipi di schemi organizzativi:
  - esatti
    - schema alfabetico
    - schema cronologico
    - schema geografico  
  - soggettivi
    - topic scheme
    - task scheme
    - audience scheme
    - metaphoric scheme

layout di interfacce e componenti

### UX design

identificare le personas mediante:

- task analysis
- feedback
- prototipazione

requirements

- funzionali
- non funzionali

user stories

scenarios
un buon scenario deve rispondere:

- chi è l'utente?
- motivazione e aspettativa dal prodotto?
- qual'è il suo obiettivo?

grazie agli scenarios possiamo determinare:

- i punti importanti durante progettazione per l'UX
- fasi del processo che richiedono ulteriore revisione e attenzione
- le principali esigenze e motivazioni dell'utente
  
modi per scrivere scenarios:

- goal o task orinentati agli scenarios
- elaborated scenarios
- full scale task scenarios

casi d'uso
includono:

- l'utente
- cosa vuole fare
- il suo scopo
- step necessari per raggiungere lo scopo
- feedback
- trigger
- basic flow
- alternative flow
  
non includono:

- dettagli implementativi o di scelta tecnologica
- dettagli di UI

i passaggi da seguire per la creazione di un caso d'uso sono:

1. identificare le personas
2. sceglierne una per caso d'uso
3. identificare il suo scopo
4. discenderne i task principali da quelli secondari
5. considerare le sequenze alternative
6. accoppiare punti in comune tra in vari casi d'uso
7. ripetere per tutte le personas

### Metodi e strumenti per l'innovazione

disruptive innovation

human centered desing process

fasi:

1. ispirazione
2. ideazione
3. implementazione

design thinking

obiettivi:

- avvicinarsi al cliente
- favorire la creatività e generare idee
- sperimenare le idee con prototipi

fasi principali:

1. empatizzare
2. definire
3. ideare
4. prototipare
5. testare

agile, scrum e devops

modello waterfall:

1. analisi dei requisiti
2. progettazione
3. svilluppo
4. collaudo
5. manutenzione

modello agile
i 12 principi del modello agile

modello scrum : sottocategoria agile

modello devops : sottocategoria agile per cloud

### Prototipazione di interfacce

prototipo

thoughtland

actionland

pretotype vs prototype

obiettivi del pretotyping sono aiutare a:

- identificare funzionalià chiave
- decidere le funzionalità da implemtare nel mockup
- test sui mockup e collezione dei feedback e dati
- analisi dei dati e determinare il prossimo passo

i 7 pilasti del pretotyping:

- obbedire alla legge del fallimento del mercato
- assicurarsi di star costruendo il prodotto giusto
- non perdersi in chiacchere, idee o opinioni
- fidarsi solo dei propri dati
- fare pretotyping
- parlare con i numeri e con i fatti
- pensa globalmente, testa localmente

Flusso del pretotyping

1. isolare l'assunzione chiave
2. scegliere un tipo di pretotype
3. fare ipotesi di mercato
4. testare il pretotype
5. imparare, rifinire, hyperzoom

tipi di pretotyping

- fake door
- mechanical turk
- impersonator

minimum viable product

## Domande orale

1. differenza tra design thinking e human center design
2. esempio di mapping
3. cos'è uno scenarios? da cosa parto per definirli?
4. cos'è un prototipo? gradi di fedeltà?
5. cos'è la ppg?
6. cos'è lo scanner time-of-flight?
7. user behavior pattern?
8. come deve essere un feedback?
9. differenza tra mockup e prototipo^
10. cos'è una imu?
11. cos'è un sistema di eyetracking e quali tecnologie conosciamo?
12. cosa sono  l'euristiche di newtan?
13. quali sono gli errori umani?
14. prese x persone. quale sarà il numero y che fa le z cose?
15. cos'è lo human center design process?
16. cos'è un test qualitativo?
17. scanner 3d a luce strutturata
18. cosa sono lapsus d'azione
19. modello concettuale fa parte del sistema?
20. cos'è il paradigma?
21. cos'è una nui?
22. come si scrivono le user stories?
23. cos'è l'immagine di un sistema
24. quali sono i sette stadi dell'azione?
25. cos'è un wireframe?
26. cos'è un modello a doppio diamante?
27. cos'è un dispositivo aptico?
28. differenza affor
29. tipi di test?
30. quali sono i principi fondamentali dell'interazione?
31. cos'è l'HID protocol?
32. differenza tra user stories e requirements?
33. parlami dei vincoli
34. come devono essere i feedback?
35. struttura interallacciata
36. la regola dei 5 perché?
37. discoverability e understanding
38. differenza tra prototipo e pretotipo
39. livelli mentali dell'essere umano
40. i 7 stadi dell'azione
41. come si dividono i sistemi di puntamento?
42. distruptive innovation
43. 6 caratteristiche principali del prototipo
