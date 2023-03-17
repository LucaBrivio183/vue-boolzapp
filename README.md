# Boolzapp - a (not very) innovative messaging platform

Il progetto si pone  di ottenere una web app funzionale, emulando quella di what's app web.
Il progetto si basa su una serie di array statici e non su una base dati esterna, per questo motivo il risultato sarà interattivo nelle possibilità e capacità attuali.



## Screenshots

![App Screenshot](/img/Boolzapp-screenshot.png)


## Milestone 1

- **Replica della grafica** con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
- **Visualizzazione dinamica della lista contatti:** tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto


### Roadmap

- Creare la struttura HTML/CSS basata su framework bootstrap, replicando lo screenshot allegato.

- Creare la struttura JavaScript, contentente la struttura dati statica, costrutita tramite VUE js framework.

### Features

- Grafica responsiva creata tramite Bootstrap framework
- Menù delle conversazioni creato interattivamente tramite Vuejs framework
- Struttura dati statica presente in js

## Milestone 2

- **Visualizzazione dinamica dei messaggi:** tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
- **Click sul contatto** mostra la conversazione del contatto cliccato

### Roadmap

- Creazione di un indice variabile per tracciare correttamente la chat attiva

- Richiamare la messaggistica corretta all'interno della main chat section

- Assegnare correttamente la classe Sent/Received ai messaggi per applicare il corretto stile css
### Features
- creazione di messaggi dinamica con funzione v-for
- selezione della chat attiva basata sul click del contatto
- cambiamento dinamico delle informazioni contatto
- creata funzione per creare lo status dei messaggi
- assegnazione dinamica della classe sent/received controllando con la funzione
## Milestone 3

- **Aggiunta di un messaggio:** l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
- **Risposta dall’interlocutore:** ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.

### Roadmap

- creazione di una variabile dinamica reattiva, collegata all'input text html

- creazione di una funzione per aggiungere all' array di messaggi corrispondente nell' oggetto contatto corretto

- creare una funzione di risposta automatica

### Features
- corretto invio tramite push nell'array dei messaggi inviati dall'utente,  aggiunta cancellazione del campo dopo la pressione di invio

- messaggio automatico di risposta ('Ok') con timeout di 3 secondi

## Milestone 4

- **Ricerca utenti:** scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo “mar” rimangono solo Marco e Martina)

### Roadmap

- creazione di una variabile dinamica reattiva, collegata all'input text html di ricerca

- controllare per tutto l'array della corrispondeza di caratteri

- creare un nuovo array filtrato della corrispondenza

- ciclare attraverso il nuovo array filtrato

