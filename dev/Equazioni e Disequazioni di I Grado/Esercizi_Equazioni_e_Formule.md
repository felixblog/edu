
# Equazioni e Disequazioni di I Grado

## UNITA' 1: Concetto di equazione e sue soluzioni

Capita frequentemente di risolvere problemi nei quali si cerca un numero sapendo che deve soddisfare una certa condizione. Vediamo un esempio: "Ho comprato un paio di pantaloni ai saldi sui quali c'era il $30 \%$ di sconto ed ho risparmiato $30$ euro. Quanto costavano di listino?"

Se la domanda fosse stata "Quanto risparmio se ho il $30 \%$ di sconto su un paio di pantaloni che costano $60$ euro?" la risposta si sarebbe trovata con una moltiplicazione: $30 \% \cdot 60 \longrightarrow 18$; nel primo caso invece conosciamo il risultato ($30$ euro) ma non tutti gli elementi che lo determinano, nel caso specifico, il prezzo di listino. Se indichiamo il prezzo con la lettera $p$, risparmio, sconto e prezzo devono soddisfare la ***condizione*** (relazione) per cui il $30 \%$ del prezzo è uguale al risparmio, ossia $30 \% \cdot p = 30$.

Il nostro problema si risolve quindi col trovare un numero che messo al posto della lettera $p$, e quindi moltiplicato per $30 \%$ dia come risultato $30$, cioè renda vera (o soddisfi) la condizione che dipende da $p$. Questo numero è $100$, infatti $30 \% \cdot 100 = 30 \longrightarrow True$. La condizione si definisce ***equazione*** ed il numero $100$ è la ***soluzione*** dell'equazione perché la sostituzione di $r$ con $100$ rende l'equazione una uguaglianza vera.

In generale una ***equazione*** (numerica di I grado ad una incognita) è una uguaglianza tra due espressioni letterali in cui sia presente una sola lettera detta ***incognita***. Una ***soluzione*** dell'equazione è un numero che, sostituito alla incognita, rende l'equazione una uguaglianza numerica vera. Le due espressioni letterali si chiamano ***membri***: quello alla sinistra del simbolo di uguaglianza è il ***membro sinistro*** mentre l'altro è il ***membro destro***.

I problemi che ci si pongono di fronte ad una equazione sono due:

1. ***Verifica di Soluzione***: Dato un numero, controllare se è una soluzione dell'equazione;
2. ***Ricerca di soluzioni***: Data una equazione, trovare le sue soluzioni.

Per rispondere alla prima domanda basta sostituire alla incognita il numero e controllare che l'uguaglianza risulti vera, qualunque sia l'equazione.

Ricercare le soluzioni è un compito molto più complesso. Procedendo per gradi, le equazioni più semplici da risolvere sono quelle ***elementari*** del tipo $x = -3$ oppure $\dfrac{2}{3} = x$. In questi casi la soluzione è ovvia ed è l'unico numero presente nell'equazione che una volta sostituita all'incognita produce: $\dfrac{2}{3} = \dfrac{2}{3} \longrightarrow True$.

Le equazioni immediatamente più complesse sono quelle del tipo $3x = -3$ e $10 = x + 4$ per le quali vedremo un metodo risolutivo nella prossima unità.



### ESERCIZIO 1.1 - Verifica di soluzioni

a) Controlla se il numero dato è soluzione delle seguenti equazioni.

1. $6,\enspace x + 12 = 28$;
2. $110,\enspace x - 50 = 60;$  
3. $-8,\enspace 2b + 3 = -15;$ 
4. $-2,\enspace 5t - 3 = -16$.

b) Controlla se il numero dato è soluzione delle seguenti equazioni.

1. $0.5x = 2.9, \; \{x=5\}$;
2. $33 - \dfrac{x}{2} = 30, \; \{x=6\}$;
3. $\dfrac{2}{a + 1} + 5 = \dfrac{12}{a + 1}, \; \{a=1\}$;
5. $-4 = a + \dfrac{5}{3}, \; \{a=\dfrac{7}{3}\}$.

#### Laboratorio GEOGEBRA

a) Risolvi i punti dell'esercizio con il comando GEOGEBRA seguente:

1. $Sostituisci(x + 12 = 28, x=6)$ &#9166; 

b) Risolvi i punti b.1 e b.2 con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $e1: 0,5x = 2,9$ &#9166; 
2. $s1: Sostituisci(e1, x=5)$ &#9166; 
3. $PrimoMembro(s1) == SecondoMembro(s1)$ &#9166;

Controlla che il comando $PrimoMembro(s1)$&#9166; fornisce $\dfrac{5}{2} \approx 2,5$ mentre $SecondoMembro(s1)$&#9166; fornisce $\dfrac{29}{10} \approx 2,9$  



## UNITA' 2: Metodo risolutivo delle equazioni di I grado

La soluzione alle equazioni molto semplici può essere trovata per tentativi, ossia con una ricerca "euristica". Ad esempio il numero che raddoppiato è uguale a $10$ è $5$, oppure il numero che sommato a $3$ è uguale ad $1$ è $-2$. Trovare questi numeri significa risolvere le equazioni $2x = 10$ e $3 + x = 1$, che sono molto semplici.

Se però l'equazione è anche di poco più complessa, trovare la soluzione senza un metodo diventa impossibile. Il metodo per risolvere le equazioni è basato sull'applicazione ripetuta di tre ***regole di equivalenza***, che consentono di trasformare una equazione in una nuova equazione, più vicina ad una equazione elementare, che però abbia le stesse soluzioni di quella originaria.

### REGOLA DELLA SEMPLIFICAZIONE

Possiamo effettuare operazioni algebriche su uno o entrambi i membri di una equazione ottenendo una nuova equazione che ha le stesse soluzioni di quella originaria.

#### ESEMPIO 1

a) $3 + 2x -3 -x = 1 -3$  Possiamo eseguire le somme algebriche tra $3$ e $-3$ , $2x$ e $-x$ e tra $1$ e $-3$ ed ottenere l'equazione b).

b) $x = -2$   Nuova equazione

L'equazione b) ha le stesse soluzioni della a), come si può controllare sostituendo in entrambe ad $x$ il numero $-2$.

### REGOLA DEL TRASPORTO (DELLA SOMMA)

Possiamo trasportare una espressione, parte di una somma, da un membro ad un altro cambiando il suo segno e sommandola ai termini già presenti. La nuova equazione che si ottiene ha le stesse soluzioni della precedente.

#### ESEMPIO 2

a) $3 + x = 1$   Trasportando $+3$ a sinistra e sommandolo ad $1$ si ottiene l'equazione b);

b) $x = 1 -3$. Nuova equazione

L'equazione b) ha le stesse soluzioni della a). Se applichiamo alla b) la regola della semplificazione al membro sinistro otteniamo la c)

c) $x = -2$. 

Questa equazione ha le stesse soluzioni della a).

In realtà la vera regola è quella della somma:

***Regola della Somma***: Possiamo sommare ad entrambi i membri di una equazione una stessa espressione ottenendo una nuova equazione che ha le stesse soluzioni della equazione originaria.

#### ESEMPIO 3

a) $3 + x = 1$   Sommando a questa prima equazione $-3$ si ottiene l'equazione b);

b) $3 + x -3 = 1 -3$. Nuova equazione

L'equazione b) ha le stesse soluzioni della a), come si può controllare sostituendo in entrambe ad $x$ il numero $-2$. Se applichiamo alla b) la regola della semplificazione al membro sinistro otteniamo la c)

c) $x = 1 - 3$. 

Il numero $+3$ è scomparso dal membro sinistro ed è comparso sommato al membro destro il suo opposto cioè $-3$. Questo succede sempre applicando in sequenza le regole della somma e della semplificazione, per questo è stata coniata la regola del trasporto, che è quella più spesso applicata.



### REGOLA DELLA MOLTIPLICAZIONE/DIVISIONE

Possiamo moltiplicare/dividere entrambi i membri di una equazione per una stessa espressione (diversa da zero); otteniamo una nuova equazione che ha le stesse soluzioni della equazione originaria.

#### ESEMPIO 3

a) $2x = 10$    Se moltiplichiamo per il reciproco di 2 ossia $\dfrac{1}{2}$ otteniamo la nuova equazione b).

b) $\dfrac{1}{2} \cdot2x = \dfrac{1}{2} \cdot 10$.   Se applichiamo la regola della semplificazione otteniamo l'equazione c) che ha le stesse soluzioni di b).

c) $x = 5$.

L'equazione b) ha le stesse soluzioni della a), come si può controllare sostituendo ad $x$ il numero $5$.

La strategia per risolvere le equazioni consiste nell'applicare ripetutamente le regole scegliendo opportunamente le espressioni da moltiplicare o sommare in modo da semplificare l'equazione riducendo entrambi i membri a polinomi (somma di monomi). A questo punto si trasportano i monomi che contengono l'incognita tutti in un solo membro e quelli che non la contengono tutti nell'altro; i monomi con l'incognita si sommano tra di loro dando come risultato un solo monomio; anche i numeri si sommano e si arriva ad una equazione come: $m \cdot x = q$, dove $m$ e $q$ sono due numeri.

A questa equazione si applica la regola della moltiplicazione e divisione per $\dfrac{1}{m}$, quindi la semplificazione e si ottiene una equazione elementare con la soluzione $\dfrac{q}{m}$, come riportato di seguito:

a) $m \cdot x = q$;   Regola della moltiplicazione/divisione per $\dfrac{1}{m}$; 

b) $\dfrac{1}{m} \cdot mx = \dfrac{1}{m} \cdot q$;   Regola della semplificazione; 

c) $x = \dfrac{q}{m}$;   La soluzione è $\dfrac{q}{m}$. 

#### ESEMPIO 4

I passi per risolvere L'equazione $3 + 2x = 1$ sono i seguenti:

a) $3 + 2x = 1$	Regola della somma con $-3$. Si sceglie $-3$ perché è l'opposto di $3$ e dopo la semplificazione il numero scompare dal membro sinistro e rimane solo il monomio con l'incognita.

b) $3 + 2x -3 = 1 -3$    Regola della semplificazione

c) $2x = -2$    Regola della moltiplicazione/divisione per $\dfrac{1}{2}$;

d) $\dfrac{1}{2} \cdot 2x = \dfrac{1}{2} \cdot (-2)$   Regola della semplificazione;

e) $x = -1$   Equazione elementare, soluzione $-1$.

#### ESEMPIO 5

a) $2(10 + x) = 3 + 7x$    Con la regola della semplificazione moltiplichiamo il numero per il polinomio al primo membro;

b) $20 + 2x = 3 + 7x$     Spostiamo il $3$ a sinistra sommando $-3$ e $2x$ a destra sommando $-2x$;

c) $20 + 2x -3 -2x = 3 + 7x -3 -2x$     Facendo la semplificazione si ottiene la prossima equazione;

d) $17 = 5x$	Regola della moltiplicazione/divisione per $\dfrac{1}{5}$

e) $\dfrac{1}{5} \cdot 17 = \dfrac{1}{5} \cdot 5x$	Regola della semplificazione

f) $\dfrac{17}{5} = x$	L'equazione è elementare e la soluzione è $\dfrac{17}{5}$.

#### ESEMPIO 6

A volte le equazioni presentano delle frazioni con un polinomio al numeratore come nel caso seguente:

$\dfrac{x + 2}{3} + \dfrac{x + 3}{4} = \dfrac{13}{3}$.

Quello delle due frazioni a sinistra dell'$=$ è un modo di scrivere che equivale a $\dfrac{1}{3}(x+2) = \dfrac{x+2}{3}$, per cui l'equazione è equivalente a:

a) $\dfrac{1}{3}(x+2) + \dfrac{1}{4}(x+3) = \dfrac{13}{3}$.

Ci sono due modi di procedere per risolvere questa equazione. Il primo è moltiplicare tutto per il minimo comune multiplo di $3$ e $4$ cioè $12$, così i denominatori scompaiono e l'equazione ha solo numeri interi:

b) $12 \cdot \dfrac{1}{3}(x+2) + 12 \cdot  \dfrac{1}{4}(x+3) = 12 \cdot  \dfrac{13}{3}$; 

c) $4(x+2) + 3(x+3) = 4 \cdot 13$;

d) $4x + 8 + 3x + 9 = 52$;

e) $7x = 52 - 8 - 9$;

f) $7x = 35$;

g) $x = 5$.

L'altro modo è eliminare le parentesi dall'equazione a) e procedere come sempre:

b') $\dfrac{1}{3}x + \dfrac{2}{3} + \dfrac{1}{4}x + \dfrac{3}{4} = \dfrac{13}{3}$;

c') $\dfrac{1}{3}x  + \dfrac{1}{4}x  = \dfrac{13}{3} - \dfrac{2}{3} - \dfrac{3}{4}$;

d') $\dfrac{4}{12}x  + \dfrac{3}{12}x  = \dfrac{52}{12} - \dfrac{8}{12} - \dfrac{9}{12}$;

e') $\dfrac{7}{12}x = \dfrac{35}{12}$;

f') $\dfrac{12}{7} \cdot \dfrac{7}{12}x = \dfrac{12}{7} \cdot \dfrac{35}{12}$;

g') $x = 5$.



### ESERCIZIO 2.1 - Regole delle Equazioni

Risolvi le seguenti equazioni applicando le regole indicate.

a) Regola del trasporto, regola della semplificazione.

1. Trova il numero da sommare a $5$ per avere $7$:  $5 + x = 7$;

2. Trova il numero da sommare a $1$ per avere $0$:  $x + 1 = 0$;

3. Trova il numero da sommare a $-2$ per avere $-5$:  $-2 + x = -5$;

4. Trova il numero che sommato a $-1$ dà $4$:  $x - 1 = 3$;

5. Trova il numero che sommato ad $\dfrac{1}{2}$ dà $2$:  $x + \dfrac{1}{2} = 2$;

6. $\dfrac{7}{15} = b - \dfrac{1}{15};$
7. $9.4 + h = 0.81$;
8. Trova il numero che sommato a $4$ dà il doppio del numero più $1$:   $4 + x = 2x + 1$; (Trasportare i monomi a destra).

b) Regola della moltiplicazione/divisione e regola della semplificazione.

1. Trova il numero che moltiplicato per $2$ da $6$:   $x \cdot 2 = 6$;
2. Trova il numero da moltiplicare per $2$ per avere $-6$:   $x \cdot 2 = -6$;
3. Trova il numero che moltiplicato per $\dfrac{1}{2}$ dà $6$:   $x \cdot \dfrac{1}{2} = 6$;
4. Trova il numero che diviso per $5$ da $-30$:   $\dfrac{x}{5} = -30$;
5. $\dfrac{x}{15} = 3$;
6. Trova il numero che diviso per $11$ da $0$:  $0 = \dfrac{v}{11};$
7. Trova il numero che diviso per $-2$ da $-11$:  $\dfrac{c}{-2} = -11;$
8. Trova il numero da dividere per $-\dfrac{3}{2}$ per avere $\dfrac{4}{5}$:   $\dfrac{c}{-\dfrac{3}{2}} = \dfrac{4}{5};$

### ESERCIZIO 2.2 - Risoluzione di equazioni

a) Risolvi le seguenti equazioni scrivendo a fianco di ogni passaggio la proprietà dell'uguaglianza utilizzata.

1. $2x + 5 = 17$;     $5q - 2 = 23$;
2. $-55 = 3w + 5$;    $\dfrac{5}{6}k - 5 = 10$;
3. $\dfrac{x}{5} - 5 = -12$;     $-5 - 2d = 0$;
4. $0.7 - 4y = 1.7$;     $0.3 - 2x = -0.9$;
5. $3\left(2y - 2\right) - y = 5$;     $-\left(4 -m\right) = -10$;
6. $5x = 4x + 7$;     $7 + 3w = 4 + 9w$   

b) Risolvi le seguenti equazioni scrivendo a fianco di ogni passaggio la proprietà dell'uguaglianza utilizzata.

1. $\dfrac{1}{8}y - \dfrac{1}{2} = \dfrac{1}{4}$;
2. $\dfrac{2}{3} = -\dfrac{2}{3}x + \dfrac{3}{4}$   
3. $\dfrac{10 - 5s}{3} = s$;
4. $\dfrac{5\left(1 - x\right)}{6} = -x + 1$   
5. $\dfrac{x + 2}{3} + \dfrac{x + 3}{4} = \dfrac{13}{3}$;
6. $\dfrac{x - 4}{2} + 3 = \dfrac{x - 2}{4}$

#### Laboratorio GEOGEBRA

a) Risolvi le equazioni del punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $Risolvi(2x + 5 = 17, x)$ &#9166; 
2. $Risolvi(5q - 2 = 23, q)$ &#9166;  

b) Risolvi le equazioni del punto b) con sequenze di comandi GEOGEBRA analoghe a quella seguente (Ricorda di utilizzare altre etichette ($e2, e3$, etc.) per indicare le equazioni).

1. $e1: \dfrac{1}{8}y - \dfrac{1}{2} = \dfrac{1}{4}$&#9166;
2. $Risolvi(e1, y)$&#9166;



### ESERCIZIO 2.3 - Scrittura di equazioni

a) Per ciascuno dei punti seguenti, scrivi l'equazione con le caratteristiche richieste.

1. Ha come (unica) soluzione il numero -3;
2. ha come soluzione un numero che ha il doppio uguale a 6;
3. ha come soluzione il numero il cui doppio meno 5 è uguale al numero stesso.

b) Per ciascuno dei punti seguenti, scrivi l'equazione con le caratteristiche richieste e trova la sua soluzione.

1. Ha come soluzione il numero -3 e ha l'incognita in entrambi i membri;
2. ha come soluzione il numero che sommato al suo successivo è uguale a 3;
3. consiste nell'uguaglianza tra un numero ed il suo opposto.



## UNITA' 3: Equazioni letterali

Fino ad ora si sono considerate solo equazioni numeriche, con una sola lettera, l'incognita. Oltre a queste però si usano anche equazioni in cui compaiono altre lettere, oltre a quella che ha il ruolo di incognita, come ad esempio $1-ax=b$, dove l'incognita è $x$.

Queste equazioni si risolvono con lo stesso metodo di quelle numeriche; le regole di soluzione delle equazioni riguardano somme, moltiplicazioni e divisioni di espressioni letterali (monomi, polinomi e frazioni algebriche) e la soluzione sarà una espressione letterale e non numerica.

#### ESEMPIO 1

Risolviamo l'equazione $1+ax=b$ considerando la lettera $x$ come incognita.

a) $1+ax=b$;   Con la regola del trasporto portiamo $1$ a destra;

b) $+ax=b-1$;   Con la regola della moltiplicazione/divisione dividiamo tutto per il coefficiente di $x$;

c) $\dfrac{+ax}{+a}=\dfrac{b-1}{+a}$;  Semplificando

d) $x = \dfrac{b-1}{a}$.

#### Laboratorio GEOGEBRA

Per risolvere con GEOGEBRA l'istruzione è:

$Risolvi(1+ax=b, x)$ &#9166;

$= \bigg\{ x = \dfrac{b+1}{a}\bigg\}$   $\bullet$



#### ESEMPIO 2

Risolviamo l'equazione $1-ax=bx + 2a$ considerando la lettera $x$ come incognita.

a) $1-ax=bx + 2a$;   Con la regola del trasporto portiamo $2a$ a sinistra e $-ax$ a destra;

b) $1 - 2a = bx + ax$;    Fattorizziamo il polinomio a sinistra mettendo $x$ in evidenza;

c) $1 - 2a = (a+b)x$;   Dividiamo entrambi i membri per il coefficiente dell'incognita $a + b$;

d) $\dfrac{1 - 2a}{a + b} = \dfrac{(a + b)x}{a + b}$;    Semplificando si ottiene la soluzione $\dfrac{1 - 2a}{a + b}$.

e) $\dfrac{1 - 2a}{a + b} = x$    $\bullet$



### ESERCIZIO 3.1 - Equazioni letterali

a) Risolvi le seguenti equazioni considerando la lettera $x$ come (unica) incognita.

1. $ax = 2a$;    $bx - 2 = 0$;    $2x = y$.

2. $2a - 3x = 7a - 5x$;    $b(x - 2) + b + 1 = 0$;    $2y = -\dfrac{1}{3}x$.

3. $2bx = 2b - 1$;    $ax = ab$;    $x + y = 1$.

4. $6x - 3(x + 2a) = a + 4(x - 2a)$;    $b(x - 2) + b + 1 = 0$;    $\dfrac{-2}{3}(x - y) + 3y = -x + 4$.

b) Nei punti 1. e 2. precedenti sostituisci all'incognita l'espressione trovata dimostrando che è la soluzione.

#### Laboratorio GEOGEBRA

a) Risolvi la prima equazione del punto a.2) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $l: 2a -3x = 7a - 5x$ &#9166; 
2. $Risolvi(l, x)$ &#9166; 

b) Risolvi la seconda equazione del punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $l: bx -2 = 0$ &#9166; 
2. $m: Risolvi(l, x)$ &#9166; 

Controlla che la soluzione è corretta sostituendo all'incognita la soluzione trovata con il comando $Sostituisci(l, m)$ &#9166; . Osserva che il primo membro è uguale al secondo.



## UNITA' 4: Equazioni e Formule

Una formula è una uguaglianza tra due espressioni letterali dove le lettere rappresentano delle misure di quantità economiche, fisiche, geometriche o di altra natura. Vediamo alcuni esempi di formule famose ed importanti.

#### Area del Rettangolo e del Triangolo

L'area di un rettangolo si calcola moltiplicando la base de rettangolo per l'altezza. Se indichiamo con $b$ la base, con $h$ l'altezza e con $A$ l'area abbiamo la formula: $A = b \cdot h$.

L'area di un triangolo è simile: la base del triangolo deve essere moltiplicata per l'altezza ed il tutto diviso per due: $A = \dfrac{b \cdot h}{2}$.

#### Esempio 1

 $\bullet$



#### Lo sconto dei saldi

Durante i saldi di fine stagione i negozi abbassano il prezzo dei prodotti per vendere di più; se indichiamo con $P_l$ il prezzo di listino e con $P_s$ il prezzo ribassato (scontato) lo **sconto** è la differenza dei prezzi: $S = P_l - P_s$. Il prezzo scontato si calcola a partire dal prezzo di listino meno lo sconto: 
$$
P_s = P_l - S
$$
Lo sconto si misura in euro; quello che invece si vede sui cartelli pubblicitari è la **percentuale di sconto**, che è il rapporto $ \dfrac{S}{P_l}$ scritto in percentuale. Questa percentuale, ad esempio il $30\%$  è la stessa per tanti prodotti; se la indichiamo con $s$ abbiamo la formula $s = \dfrac{S}{P_l}$. Da questa formula si trova che $S = sP_l$ e se sostituiamo questa nella formula del prezzo scontato otteniamo $P_s = P_l - sP_l$, ossia, mettendo in evidenza $P_l$:
$$
P_s = P_l(1 - s).
$$

#### Esempio 2

 $\bullet$



#### Peso lordo, tara e peso netto

Tutte le volte che incontriamo un oggetto racchiuso in un contenitore, ad esempio di carta, cartone o altro, diciamo che il peso totale è la somma di quello dell'oggetto stesso e del contenitore. Questo peso totale è detto **peso lordo**, mentre il peso dell'oggetto SENZA contenitore è detto **peso netto**. Relativamente al peso, il contenitore è detto **tara**, per cui, se indichiamo con $L$ il peso lordo, $N$, il peso netto e $T$ il peso della tara abbiamo:
$$
L = N + T
$$
Questa schematizzazione è così comune che anche in altri contesti, quando vogliamo parlare di una quantità che è la somma di  qualcosa di essenziale (il "netto") e qualcosa di accessorio (la "tara"), diciamo "al lordo" dell'accessorio per indicare la quantità totale, o "al netto" per indicare l'assenza dell'accessorio, come nelle espressioni "retribuzione lorda" e "retribuzione netta", al lordo dell'IVA" o "al netto degli interessi". 

#### Esempio 3

 $\bullet$

#### Ricavi, costi e margine

Quando un soggetto rivende ad un prezzo di $R$ euro un prodotto che precedentemente aveva comprato a $C$ euro, diciamo che dalla operazione ottiene un **utile** di $R - C$ euro. Se indichiamo questo utile con $U$ possiamo scrivere:
$$
U = R - C
$$
Con $R$ abbiamo indicato il **ricavo** e con $C$ il **costo** di questa operazione; l'utile è anche detto **mark-up** dell'operazione.

Spesso è utile calcolare anche l'utile di una operazione in percentuale sul suo costo; in questo caso $R - C$ è detto **mark-up assoluto** e $q = \dfrac{R - C}{C}$ è detto **mark-up percentuale**.



#### Esempio 4

 $\bullet$



#### La formula dell'IVA 

L'IVA (Imposta sul Valore Aggiunto) è una imposta che il consumatore paga quando acquista un prodotto. E' determinata da una percentuale del costo (IVA esclusa) del prodotto. In pratica, se indichiamo con $i$ la percentuale da applicare, l'importo in euro dell'IVA su un prodotto che, IVA esclusa, costa $C$ sarà $I = i \cdot C$.

Il prezzo $P$ del prodotto, IVA inclusa, sarà allora $P = C + I$ ossia $P = C + i \cdot C$ e mettendo in evidenza $C$ abbiamo:
$$
P = C(1 + i)
$$

#### Esempio 5

 $\bullet$



####  La velocità

La velocità misura la rapidità con la quale un fenomeno si manifesta o un processo si svolge.

Se osserviamo il movimento di una automobile su una strada e vediamo che questa percorre, in un certo tempo un certo spazio, ad esempio in $2$ ore percorre $100 \; Km$, possiamo dire che l'automobile ha una velocità di $\dfrac{100}{2} = 50 \; Km/h$​. 

La velocità di un oggetto che si muove è quindi misurata dal rapporto tra la distanza che percorre ed il tempo impiegato a percorrerla.

La formula generale della velocità dice che la velocità di un corpo in movimento (es. una macchina) è uguale al rapporto tra la distanza che la macchina percorre ed il tempo che impiega a percorrerlo:
$$
v = \dfrac{s}{t}
$$

#### ESEMPIO 6

Una persona passeggia per un'ora e mezza alla velocità di $6 \; Km/h$​. Quanti chilometri percorre?

Dalla formula generale, esplicitando la $s$, ossia risolvendo come se $s$ fosse l'unica incognita, otteniamo $s = v \cdot t$, cioè $s = 6 \cdot 1,5 \longrightarrow 9 \; Km/h$.   $\bullet$



#### ESEMPIO 7

Nel 2009 l’atleta giamaicano Usain Bolt ha corso i 100 metri piani in $9.58$ secondi. Quale è stata la sua velocità media in $Km/h$?

Dalla formula otteniamo $v = \dfrac{s}{t}$, cioè $v = \dfrac{100}{9,58} \longrightarrow 10,44 \;m/s$. Per trasformarli in $Km/h$ al posto di $m$ sostituiamo $\dfrac{1}{1000}Km$ ed al posto di $s$ $\dfrac{1}{3600}h$, per cui $10,44 \;m/s \longrightarrow 10,44 \cdot \dfrac{\dfrac{1}{1000}}{\dfrac{1}{3600}} \longrightarrow 10,44 \cdot 3,6 = 37,584 \; Km/h$.   $\bullet$



### ESERCIZIO 4.1 - Formule ed Equazioni Letterali I

Risolvi le equazioni letterali proposte considerando di volta in volta ciascuna formula come una equazione, con l'incognita indicata.

1. $M = C + I$,  incognita $C$;
2. $A = b \cdot h$,  incognita $b$;
3. $A = \dfrac{b \cdot h}{2}$, incognita $b$;    $A = \dfrac{b \cdot h}{2}$,  incognita $h$;
4. $S = P_l - P_s, ~~~ incognita ~~ P_s;$
5. $I = C\cdotp i\cdotp t ,~~~ incognita ~~ i$;       $I = C\cdotp i\cdotp t ,~~~ incognita ~~ C$;
6. $v = \dfrac{s}{t}$,  incognita $s$.



### ESERCIZIO 4.2 - Formule ed Equazioni Letterali II

a) Risolvi le equazioni letterali proposte considerando di volta in volta ciascuna formula come una equazione, con l'incognita indicata.

1. $v = \dfrac{s}{t}$,  incognita $t$;
2. $\dfrac{P_l - P_s}{P_l}= s$, incognita $P_s$;
3. $\dfrac{P_l - P_s}{P_l}= s$, incognita $P_l$;
4. $P_v = C \cdotp (1 + q)$, incognita $C$;
5. $P_v = C \cdotp (1 + q)$; incognita $q$, (dimostrando così che la formula del mark-up si può scrivere $q =\dfrac{P_v - C}{C}$). 

b) Risolvi ciascuna equazione considerando la lettera indicata come l'incognita.

1. $3x + y = 9$, incognita $y$;  $5y - x = 25$, incognita $y$;

2. $-x + 3y = 9$. incognita $y$;   $\dfrac{7}{8}c + w = 9$, incognita $c$

#### Laboratorio GEOGEBRA

a) Risolvi l'equazione a.6) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $eq1: (P_{l} - P_{s})/P_{l}= s$ &#9166; 
2. $Risolvi(eq1, P_{l})$ &#9166; 



### ESERCIZIO 4.3 - Applicazione di formule

Risolvi i problemi seguenti individuando una formula risolutiva ed applicandola, sostituendo i numeri alle lettere, nel caso specifico. 

a) Nel 2006 il film Titanic ha avuto un incasso mondiale di 1835 milioni di dollari con un profitto di 1595 milioni. Quanto è costato il film?

b) Trova il margine (mark-up assoluto e percentuale) di un fioraio che nel giorno di San Valentino compra una dozzina di rose a 12.95 euro e le rivende a 47.50. 

c) Se una mongolfiera viaggia ad una media di 37 Km/h, quanto tempo impiegherà a percorrere 166 Km?  

d) Un aereo vola tra Chicago e S. Francisco in 3.75 ore. Se le città distano 2100 Km quale è la velocità media dell'aereo?

e) Un gruppo di persone guarda dei fuochi di artificio in lontananza. Vede le luci colorate e dopo circa tre secondi sente il rumore. Se la velocità del suono è di circa $330$ metri al secondo, quanto è distante il gruppo dal punto di esplosione dei fuochi?



## UNITA' 5: Inversione delle Formule



## UNITA' 6: Diseguaglianze ed intervalli

La scrittura $3 \gt 5$ afferma una **relazione** tra due numeri, precisamente che il numero 3 è maggiore del numero 5 ed è chiaramente falsa. Si dice che il suo "***valore di verità***" è "Falso" e si scrive che $3 \gt 5 \longrightarrow{} False $ . Invece $4 = 2 + 2$ afferma una cosa vera e si scrive che $4 = 2 + 2 \longrightarrow True$ , dove $True$ sta per "Vero". Analogamente "$\lt$" è il simbolo di "minore"; $1+2 \lt 5$ afferma che il risultato dell'espressione $1+2$ è minore del numero 5, è chiaramente vera, e simbolicamente scriviamo che $1+2 \lt 5 \longrightarrow True$ . Osserviamo che $1+2 \lt 3 \longrightarrow False$ .

I simboli "$\le$" e "$\ge$" significano "minore o uguale" e "maggiore o uguale", per cui $3 \le 5 \longrightarrow True$  e  $3 \le 3 \longrightarrow True$​ .

Come per le equazioni, scrivere $x < -2$ significa scrivere qualcosa che di per se non è ne vera ne falsa in quanto non contiene solo numeri, ma è importante perché con essa possiamo porci un problema , che è quello di trova i numeri che sostituiti alla lettera $x$​ rendono la relazione vera.

La scrittura $x \lt -2$ si chiama "disequazione" ed i numeri che la rendono vera si chiamano "soluzioni" della disequazione. Come si vede, le soluzioni della disequazione sono tutti i numeri che sono minori di $-2$, ad esempio $-3$, $-10$, $-100$, ma non $0$. Sono un insieme infinito di numeri che indichiamo con la notazione $\{x: x \lt -2\}$ che si legge "***l'insieme delle x tali che x è minore di meno due*** ". In particolare "$\{$" si legge "L'insieme delle... ":" si legge "tali che" .... e la parentesi chiusa non si legge.

Per indicare questo insieme si utilizza anche un'altra notazione, detta "**intervallo**": $(-\infty, -2)$; in questo modo si indicano tutti i numeri minori di $-2$ tranne il numero $-2$ che non fa parte dell'insieme. Se vogliamo indicare anche $-2$ scriviamo $(-\infty, -2]$.

Se volessimo indicare tutti numeri minori di $-2$ ma maggiori di -$4$, scriveremmo $[-4, -2]$, intendendo che sia $-4$ che $-2$ fanno parte dell'insieme. Se vogliamo escludere $-4$ scriviamo $(-4, -2]$, e così via.

Gli intervalli si possono rappresentare anche graficamente su una retta. Il grafico dell'intervallo $[0,3]$ è:

<img src="img\diseq-0-3.png" alt="diseq-0-3" style="zoom:75%;" />

Nella simbologia grafica usata da GEOGEBRA, ogni estremo del segmento è un puntino pieno, se il numero fa parte dell'intervallo, mentre è vuoto se non vi fa parte, come nell'esempio seguente dove è rappresentato l'intervallo $(3, 5]$.

<img src="img/diseq-3-5.png" alt="diseq-3-5" style="zoom:75%;" />



### ESERCIZIO 6.1 - Disuguaglianze e disequazioni

a) Indicare quali delle seguenti disuguaglianze sono vere e quali false.  

1. $9 - 2 \lt 3$;
2. $5+8 \gt 19$;
3. $5 \cdot 2 \le 5 \cdot 7$;
4. $4 \cdot 8 \gt  2 \cdot 16$;
5. $8-2 \lt 14$;
6. $x + 1 \gt 0$;
7. $6 + 4 \le 10$

b) Trovare almeno due numeri che rendono vere le seguenti disequazioni.

1.  $x + 1 \gt 0; x + 3 \le 4$;
2.  $2x-1 \lt 6; x^2 + 2x -1 \ge 0$; 

### ESERCIZIO 6.2 - Soluzione di Disequazioni I

a) Nei casi riportati di seguito, determina quali tra i valori indicati nell'insieme è soluzione della disequazione associata.

1. $\{0, 1, -1\}: x-2<6;$   $\{0, 3\}: 2x-1<3$;
2. $\{0, 5, 7\}: 3(x-5) - 6 < 0$;   $\{0, 5, 7\}: 5x - (6-x) \ge 0$;

b) Scrivi la disequazione corrispondente alle frasi riportate di seguito.

1. Insieme dei numeri minori o uguali ad 1; Insieme dei numeri non maggiori di 2;
2. Insieme dei numeri il cui doppio è minore di 3; Insieme dei numeri non maggiori di $-\dfrac{4}{13}$.

#### Laboratorio GEOGEBRA

a) Risolvi la prima parte del punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $d1(x) : x - 2 < 6$ &#9166; 
2. $\{d1(0), d1(1), d1(-1)\}$ &#9166;



### ESERCIZIO 6.3 - Intervalli e disequazioni elementari

a) In ciascuno dei casi riportati di seguito determina se il numero indicato appartiene all'intervallo associato.

1. $2\in [0; 3]$;   $\dfrac{1}{3} \in (-2; 2]$;   $2, \in [0; 3]$;   $\dfrac{2}{5}, \in (\dfrac{2}{5}; 1)$;   
2. $-1, \in [-3; -2]$;   $-4, \in [-4; 0)$;   $0, \in (0; 1]$.

b) Rappresenta graficamente su una retta gli intervalli riportati di seguito.

1. $(0;1)$;   $[-1;1]$;   $(1;+\infty)$;   $(-\infty;5)$;   $(0;1)$;   
2. $[-1;0)$;   $[-3;+\infty)$;   $(-\infty; +\infty)$;   $(2;\dfrac{33}{5}])$;   $[\dfrac{1}{2};3)$.
3. $(-1;3) \cap (-2;0)$;   $(-1;3) \cup (-2;0)$;
4. $(1;5) \cap (5;7)$;   $(1;5) \cup (5;7)$;
5. $(3;+\infty) \cap [3;7]$;   $(3;+\infty) \cup [3;7]$;
6. $[0;\dfrac{3}{2}) \cap (-\dfrac{4}{5};0]$;   $[0;\dfrac{3}{2}) \cup (-\dfrac{4}{5};0]$.

c) Per ciascuno dei casi seguenti, scrivi la disequazione (elementare) o il sistema di disequazioni che ha come soluzioni l'intervallo indicato.

1.  $(-\infty;-5)$;   $[1;+\infty)$;   $(1;+\infty)$;   $(-\infty;-\dfrac{50}{11})$;   $(-3;+\infty)$;
2.  $[0; 3]$;   $(-2; 2]$;   $(2; \dfrac{33}{5}]$;   $(\dfrac{2}{5}; 1)$;
3.  Gli intervalli dei punti b.3) e b.4).

#### Laboratorio GEOGEBRA

Per il presente laboratorio, utilizzare la versione on-line di GEOGEBRA Classic all'indirizzo: https://www.geogebra.org/classic.

a) Risolvi la prima parte del punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $a : 0 \le x \and x \le 3$ &#9166; 
2. $a(2)$ &#9166;

Per rappresenta graficamente l'intervallo:

1. Dal "Menu Principale" seleziona "Cambia Calcolatrice" / "Grafici";
2. Dal menu della casella di input, seleziona "Impostazioni" e quindi dalla scheda "Stile" seleziona "Mostra sull'asse X".

<img src="img\diseq-0-3.png" alt="diseq-0-3" style="zoom:25%;" />

b) Risolvi la restante parte del punto a.1) con sequenze di comandi GEOGEBRA analoghi a quelli precedenti. Ricorda di utilizzare altre etichette per indicare gli intervalli ($b, c$, etc.).



## UNITA' 7: Disequazioni di I grado con una incognita

### ESERCIZIO 7.1 - Soluzione di Disequazioni II

a) Per ciascuno dei casi seguenti, scrivi l'insieme delle soluzioni delle disequazioni come intervalli.

1. $x-1\ge 2$;   $7x-1\ge 2$;   $-x-1\le 2$;   $\dfrac{x}{5}-1\ge 2$;
2. $4x - 3 > 5x + 1$;   $4[2(1 - x) -3] > 5x + 1$;    $5(x-1) < 2(x-3)$;
3. $3\left[(x+3)+\dfrac{1}{3}x\right]<7x$;   $3(x-1)-1 < \dfrac{x-2}{3} - \left(x-\dfrac{x-1}{3}\right)$;
4. $\dfrac{2+x}{3} \ge x + \dfrac{1}{2}$;   $2x-5\lt 3+2x$;   $2(x+1) - 5x\ge 3x + 4(x+1)$.

