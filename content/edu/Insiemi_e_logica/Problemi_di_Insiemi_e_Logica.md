Title: Problemi di insiemi e logica
Date: 2015-10-01 22:20
Modified: 2015-10-01 22:20
Category: Edu
Tags: Insiemi e Logica
Slug: pb-insiemi-logica
Authors: Felice el Mauro
Summary: Problemi di insiemi e logica

Problema
--------

In una classe di 32 alunni, 18 giocano a calcio e 20 a pallavolo. Di
essi, 16 praticano entrambi gli sport. Calcola quanti alunni non
praticano ne’ il calcio ne’ la pallavolo.

### Soluzione

Problema
--------

In un gruppo di 18 persone ciascuno porta almeno uno fra cappello,
giacca e cravatta. Si sa che in 6 portano il cappello, in 9 la giacca e
in 12 la cravatta. Due persone portano cappello e cravatta e nessuno
porta cappello e giacca. Stabilisci quante persone hanno giacca e
cravatta.

### Soluzione

Detto U il gruppo di persone della sala, $x \in U$, ed indicati gli
insiemi seguenti:

$$C = \{ x \in U:x\ porta\ il\ cappello\}$$

$$G = \{ x \in U:x\ porta\ la\ giacca\}$$

$$R = \{ x \in U:x\ porta\ la\ cravatta\}$$

Il fatto che nessuno porta cappello e giacca si traduce in:

$$C \cap G = \{\}$$

Osserviamo che questa asserzione implica che nessuno porta tutte e tre
gli indumenti. Indicando con “x” la cardinalità incognita di $R \cap G$,
si ha la situazione della figura seguente:

![](img/img1.png)

La condizione per risolvere il problema è che la somma di tutte le
persone è 18, per cui:

$$4\  + \ 2\  + \ (10\  - \ x)\  + \ x\  + \ (9\  - \ x)\  = \ 18$$

$$25 - x = 18$$

$$7 = x$$

Le persone che portano la cravatta sono 7.

Problema
--------

ln una sala sono presenti 62 persone, ognuna delle quali ha almeno una
delle caratteristiche seguenti: essere europei o essere studenti. Si sa
che gli studenti non europei sono 12, che gli inglesi non studenti sono
8, che gli studenti europei non inglesi sono 22 e che gli europei non
inglesi né studenti sono tanti quanti gli studenti inglesi. Determina il
numero degli inglesi.

### Soluzione

Detto U l’insieme delle persone della sala, e, considerando che
$x \in U$,

$S = \{ x \in U:x\ e'\ studente\}$;

$I = \{ x \in U:x\ e'\ inglese\}$;

$E = \{ x \in U:x\ e'\ europeo\}$;

L’affermazione per cui ogni persona della sala o è europea o è studente
si traduce in:

$$U = E \cup S$$

Inoltre

$I \subset U$.

$$\{ x \in U:x\ e'\ studente\ non\ europeo\} = S - E$$

$$\{ x \in U:x\ e'\ inglese\ non\ studente\} = I - S$$

$$\{ x \in U:x\ e'\ studente\ europeo\ non\ inglese\} = (E \cap S) - I$$

$$\{ x \in U:x\ e'\ europeo\ non\ inglese\ e\ non\ studente\} = E - I - S$$

$$\{ x \in U:x\ e'\ studente\ inglese\} = S \cap I$$

La figura seguente riepiloga le informazioni sulla cardinalità degli
insiemi (le cardinalità non note sono indicate con “x”):

La somma delle cardinalità di tutte le aree è 62, cioè:

![](img/img2.png)

$$12 + 22 + x + 8 + x = 62$$

Semplificando

$$2 \bullet x = 20$$

Da cui

$$x = 10$$

Per cui gli inglesi sono 10 + 8 = 18.
