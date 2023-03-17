# Boolzapp - a (not very) innovative messaging platform

Il progetto si pone  di ottenere una web app funzionale, emulando quella di what's app web.
Il progetto si basa su una serie di array statici e non su una base dati esterna, per questo motivo il risultato sarà interattivo nelle possibilità e capacità attuali.



## Screenshots

![App Screenshot](/img/Boolzapp-screenshot.png)


## Milestone 1

Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto


## Roadmap

- Creare la struttura HTML/CSS basata su framework bootstrap, replicando lo screenshot allegato.

- Creare la struttura JavaScript, contentente la struttura dati statica, costrutita tramite VUE js framework.

## Features

- Grafica responsiva creata tramite Bootstrap framework
- Menù delle conversazioni creato interattivamente tramite Vuejs framework
- Struttura dati statica presente in js

## Milestone 2

Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
Click sul contatto mostra la conversazione del contatto cliccato

## Roadmap

- Creazione di un indice variabile per tracciare correttamente la chat attiva

- Richiamare la messaggistica corretta all'interno della main chat section

- Assegnare correttamente la classe Sent/Received ai messaggi per applicare il corretto stile css