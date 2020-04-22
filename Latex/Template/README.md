# STRUTTURA 

## config 
Nella della cartella config è presente un solo file: "commands.tex", all'interno del quale sono specificati dei comandi relativi
al documento considerato (es. nome del documento, stato di approvazione, ecc...). Ovviamente i comandi devono essere modificati 
in modo tale che rispecchino la situazione attuale del documento. 

## res 
La directory res contiene due cartelle: img e sections. <br />
- La cartella img contiene due immagini: logo.png e cropped_logo.png, che vengono usate per la creazione della copertina e la 
formattazione delle varie pagine. Ulteriori immagini necessarie all'interno del documento devono essere inserite all'interno
di questa cartella. 
- La cartella sections contiene le varie sezioni del documento. Ho già provveduto ad inserire al suo interno un file "changelog.tex",
che rappresenta il "diario delle modifiche". 

## document.tex 
Il file ha la struttura generica di un documento. Il nome deve essere modificato in maniera da rispecchiare il documento considerato. 
A seconda del documento potrebbe essere necessario rimuovere le righe relative all'inserimento della table of content / lista delle 
figure / lista delle tabelle. 