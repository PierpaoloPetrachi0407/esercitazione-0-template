# Osservazioni — Esercitazione 0

Gruppo:

Componenti (nome, cognome e username GitHub di entrambi):
Giacomo Petragnani petragnani2275541-creator
Pierpaolon Petrachi PierpaoloPetrachi0407

URL del repository condiviso:
https://github.com/PierpaoloPetrachi0407/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2:
Step 1 - Petrachi Pierpaolo
step 2 - Petragnani Giacomo

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc hello.c -o hello.exe 

Comando di esecuzione e risultato osservato:./hello.exe

Che cosa ho capito su sorgente ed eseguibile:
che la sorgente è solo il pogramma e devo dare iul comando di compilazione per renderlo eseguibvile


Output richiesto e comportamento del programma prima della modifica:
Nessun output e il programma non scrive nulla sul terminale.

Esito dopo la modifica e spiegazione della correzione:
Il programma stampa quello che gli è stato richiesto, perché è stata implementata la funzione printf.

## Step 1 — Git

Quali file ho incluso nel commit e perché:

hello.c per vedere come si usava git commit

Come ho verificato che la versione provata sia presente su GitHub:

andando su github e osservando che le modifiche fossero presenti

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:


## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:
ciao 7 8.43
./eco.exe ciao 7 8.43
ciao 7 8.430000

Che cosa posso concludere:
Che gli argomenti sono stati convertiti correttamente.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:
ciao 12 3.5

./eco ciao 12 3.5 > eco.txt
echo $?
cat eco.txt

0
ciao 12 3.500000


Che cosa ho capito su testo, conversioni e stampa:


## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:
Quella con argomenti validi ha fatto vedere gli argomenti inseriti, quella con "dodici" restituisce uno 0.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:
ciao 12 3.500000

0
ciao 0 3.500000

Come un controllo automatico può riconoscere un errore:
Se il programma restituice un numero diverso da 0, allora c'è un errore.

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:
quando modifico il programma devo ricompilare, altrimenti basta cambiare argomenti

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:
Grazie alla descrizione inserita dopo git commit

Come ho verificato che la versione finale sia presente su GitHub:
Andando su github e verificando cheb le mie modifiche fossero presenti.
