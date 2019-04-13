# Applicazioni-per-ambienti-intelligenti-basati-su-MongoDB-e-sul-protocollo-CoAP
La tesi che ho presentato per la laurea triennale in Ingegneria Informatica presso l'Università degli Studi di Messina.

## Overview
L'obiettivo della tesi è la realizzazione di un sistema di monitoraggio e gestione di un ambiente intelligente. 
Gli utenti del sistema possono accedere ai servizi personalizzati e dinamici, che integrano i dati ambientali (provenienti da sensori) con le esigenze degli 
utenti, modificando le caratteristiche dell'ambiente stesso (tramite gli attuatori). Il sistema sviluppato sfrutta il protocollo CoAP come protocollo di 
comunicazione tra i dispositivi embedded (sensori ed attuatori) e immagazzina l'ingente quantità di dati che viene continuamente prodotta dai sensori per il 
monitoraggio ambientale nel Cloud, mediante il DBMS MongoDB.

Il lavoro della tesi è stato portato avanti in modo da fornire un'analisi ed un'implementazione delle tecnologie considerate, creando un sistema 
flessibile e funzionale per varie applicazioni.

Il servizio finale consente all’utente di:

* tenere sotto controllo i propri sensori, visualizzandone le misure effettuate nel tempo (anche applicando filtri come tag, gruppi o posizione);
* comandare i propri attuatori, stabilendo regole di funzionamento in base all'orario e alla locazione dell'interruttore attivato, accendendo solo determinate luci oppure caricando da remoto un proprio programma in python da eseguire ottenendo, così, dei servizi personalizzati;
* raggruppare i dispositivi in gruppi, in modo tale da avere una gestione più semplificata;
* rendere pubblici i propri dispositivi, in modo che tutti gli utenti registrati nel sistema possano accedervi;
* creare gruppi di utenti che hanno accesso solo a determinati gruppi di dispositivi. +
Per esemplificare, si pensi ad un'università in cui tutte le porte siano considerate degli attuatori collegati a uno strumento capace di identificare un utente (lettore di impronte digitali, tastierino numerico, card reader, ecc.). Si potrebbe abilitare a un gruppo di tirocinanti l’apertura di tutte le porte che conducono al laboratorio dove devono recarsi, in modo tale da farli accedere solamente a determinate zone e salvare l’orario di entrata e di uscita dal laboratorio di ogni tirocinante;
* ottenere informazioni in base alla posizione dei dispositivi. Ad esempio, è possibile ottenere una media della temperatura di un determinato luogo pesata in base alla precisione di ogni dispositivo a cui si ha accesso nelle vicinanze di un determinato punto, identificato da latitudine e longitudine.

## Info ##
* Nella cartella `/src` si trova la tesi, che è stata scritta con il formato asciidoc;
* La tesi è stata convertita in html e pdf a partire dal file `/src/tesi_main.adoc`;
* Il file `/src/tesi.html` è stato creato con [Asciidoctor](http://asciidoctor.org/) ed è la tesi in formato html;
* Il file `/tesi.pdf` è stato creato con [Asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf) ed è la tesi in formato pdf;
* Il file `presentazione.ppt` è la presentazione della tesi, utilizzata durante la discussione.
