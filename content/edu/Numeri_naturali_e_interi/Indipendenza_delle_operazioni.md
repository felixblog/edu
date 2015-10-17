Title: Quali operazioni nello stesso passaggio ?
Date: 2015-10-17 10:20
Modified: 2015-10-17 10:20
Category: Edu
Tags: Numeri naturali e interi
Slug: Quali-operazioni-nello-stesso-passaggio
Authors: Felice Del Mauro
Summary: Osservazioni sulle operazioni all'interno dello stesso passaggio di semplificazione

Indipendenza delle operazioni ed ordine di esecuzione
-----------------------------------------------------

Consideriamo la semplice espressione seguente

  (1)   $$2\overset{1}{\overbrace{+}}\left( - 3 \right)\overset{2}{\overbrace{+}}5$$   
  ----- ------------------------------------------------------------------------------ --

Le operazioni sono state numerate per riconoscerle nei passaggi
successivi. Ciascuna delle somme potrebbe essere eseguita per prima, ma,
nell’insieme, esse non sono indipendenti: qualunque si scelga, la
seconda operazione utilizza il risultato della prima e quindi dipende da
tale risultato.

Facciamo un esempio eseguendo la seconda somma. Si ha:

  (2)   $$\left( - 3 \right)\overset{2}{\overbrace{+}}5 = 2$$   
  ----- ------------------------------------------------------- --

e la prima somma utilizza il numero 2 trovato:

  (3)   $$2\overset{1}{\overbrace{+}}2 = 4$$   
  ----- -------------------------------------- --

Nell’insieme si ha la sequenza di passaggi:

  (3.1) $$2\overset{1}{\overbrace{+}}\left( - 3 \right)\overset{2}{\overbrace{+}}5\  = 2\overset{1}{\overbrace{+}}2 = 4$$
  ----- ------------------------------------------------------------------------------------------------------------------- --

Consideriamo un altro esempio:

  (4)   $$2\overset{1}{\overbrace{+}}\left( - 3 \right)\overset{3}{\overbrace{\cdot}}4\overset{2}{\overbrace{+}}5$$   
  ----- ------------------------------------------------------------------------------------------------------------- --

Né la prima, né la seconda somma possono essere eseguite prima del
prodotto; dopo il calcolo del prodotto, si vede come sia la prima che la
seconda somma dipendono dal risultato trovato:

  (5)   $$2\overset{1}{\overbrace{+}}\ \left( - 3 \right)\overset{3}{\overbrace{\cdot}}\ 4\overset{2}{\overbrace{+}}\ 5\  = \ 2\overset{1}{\overbrace{+}}\left( - 12 \right)\overset{2}{\overbrace{+}}\ 5$$   
  ----- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --
  (6)   $$2\overset{1}{\overbrace{+}}\left( - 12 \right)\overset{2}{\overbrace{+}}5\  = \  - 10\overset{2}{\overbrace{+}}5$$                                                                                  
  (7)   $$- 10\overset{2}{\overbrace{+}}5 = \ 5$$                                                                                                                                                             

Nella espressione seguente invece, le due somme sono indipendenti dalla
moltiplicazione, indipendenti tra di loro, e possono essere eseguite in
parallelo: è la moltiplicazione che dipende dal risultato delle somme.

  (8)   $$\left( 2\overset{1}{\overbrace{+}}\left( - 3 \right) \right)\overset{3}{\overbrace{\cdot}}\left( 4\overset{2}{\overbrace{+}}5 \right) = \ \left( - 1 \right)\overset{3}{\overbrace{\cdot}}9$$   
  ----- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --
  (9)   $$\left( - 1 \right)\overset{3}{\overbrace{\cdot}}9 = \  - 9$$                                                                                                                                    
  ----- ---------------------------------------------------------------- --
  ----- ---------------------------------------------------------------- --

Quali operazioni in un solo passaggio?
--------------------------------------

La semplificazione di una espressione è organizzata in passaggi. Un
passaggio è costituito da due espressioni in cui la seconda risulta
essere la prima dove alcune operazioni sono state eseguite e ad esse è
stato sostituito il relativo risultato.

L’organizzazione in più passaggi serve ad evidenziare le operazioni
effettuate per permettere una più semplice correzione di eventuali
errori.

Il problema che si pone è: quali operazioni effettuare in un singolo
passaggio?

In un passaggio potrebbero essere eseguite un numero indefinito di
operazioni. Consideriamo le seguenti semplificazioni alternative della
stessa espressione:

  (10)   $$\left( 2 + \left( - 3 \right) \right) \cdot \left( 4 + 5 \right) = - 1 \cdot 9 = - 9$$                                    
  ------ --------------------------------------------------------------------------------------------------------------------------- --
  (11)   $$\left( 2 + \left( - 3 \right) \right) \cdot \left( 4 + 5 \right) = - 9$$                                                  
  (12)   $$\left( 2 + \left( - 3 \right) \right) \cdot \left( 4 + 5 \right) = - 1 \cdot \left( 4 + 5 \right) = - 1 \cdot 9 = - 9$$   

La semplificazione (10) è costituita da 2 passaggi: due somme
indipendenti in parallelo nel primo passaggio ed una sola operazione (il
prodotto) nel secondo passaggio.

La semplificazione (11) ha un unico passaggio con due somme ed un
prodotto in cui il risultato dipende dalle somme. Non esplicita i
risultati delle singole operazioni e non offre alcun aiuto per la
correzione.

Nella (12) ci sono 3 passaggi con una sola operazione per passaggio. E’
la più efficace ai fini della correzione ma anche la più prolissa.

La norma consigliata è quella di non effettuare nello stesso passaggio
operazioni differenti dipendenti tra di lor**o**, ossia **non
riutilizzare nel passaggio risultati di operazioni eseguite sempre nel
passaggio**, in modo che nella seconda espressione di ogni passaggio
siano scritti i risultati di tutte le operazioni effettuate.

Nella casistica precedente, la semplificazione fuori norma sarebbe solo
la (11), in cui sono state eseguite sia prodotti che somme.

Se le operazioni in oggetto sono tutte somme o prodotti, la loro
esecuzione in un solo passaggio non altera la leggibilità del passaggio
stesso, come si vede dagli esempi seguenti:

  (13)   $$(2 + \left( - 3 \right) + 4) \cdot ( - 1) = 3 \cdot ( - 1) = - 3$$                                    
  ------ ------------------------------------------------------------------------------------------------------- --
  (14)   $$2 \cdot \left( - 3 \right) \cdot \left( - 2 \right) \cdot \left( - 1 \right) + 5 = - 12 + 5 = - 7$$   


