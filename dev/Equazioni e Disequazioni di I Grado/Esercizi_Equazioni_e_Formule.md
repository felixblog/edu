
# Equazioni e Disequazioni di I Grado

## UNITA' 1: Concetto di equazione e sue soluzioni

Capita frequentemente di risolvere problemi nei quali si cerca un numero sapendo che deve soddisfare una certa condizione. Vediamo un esempio: "Ho comprato un paio di pantaloni ai saldi sui quali c'era il $30 \%$ di sconto ed ho risparmiato $30$ euro. Quanto li ho pagati?"

Se la domanda fosse stata "Quanto risparmio se ho il $30 \%$ di sconto su un paio di pantaloni che costano $60$ euro?" la risposta si sarebbe trovata con una moltiplicazione: $30 \% \cdot 60 \longrightarrow 18$; nel primo caso invece conosciamo il risultato ($30$ euro) ma non gli elementi che lo determinano, nel caso specifico, il risparmio sul prezzo di listino. Se indichiamo la somma risparmiata con la lettera $r$, risparmio, sconto e prezzo devono soddisfare la ***condizione*** (relazione) per cui il $30 \%$ del prezzo è uguale al risparmio, ossia $30 \% \cdot r = 30$.

Il nostro problema si risolve quindi col trovare un numero che messo al posto della lettera $r$, e quindi moltiplicato per $30 \%$ dia come risultato $30$, cioè renda vera (o soddisfi) la condizione che dipende da $r$. Questo numero è $100$, infatti $30 \% \cdot 100 = 30 \longrightarrow True$. La condizione si definisce ***equazione*** ed il numero $100$ è la ***soluzione*** dell'equazione perché la sostituzione di $r$ con $100$ rende l'equazione una uguaglianza vera.

In generale una ***equazione*** (di I grado ad una incognita) è una uguaglianza tra due espressioni letterali in cui sia presente una lettera detta ***incognita***. Una ***soluzione*** dell'equazione è un numero che, sostituito alla incognita, rende l'equazione una uguaglianza numerica vera. Le due espressioni letterali si chiamano ***membri***: quello alla sinistra del simbolo di uguaglianza è il ***membro sinistro*** mentre l'altro è il ***membro destro***.

Le equazioni più semplici che esistano sono quelle ***elementari*** del tipo $x = -3$ oppure $\dfrac{2}{3} = x$. In questi casi la soluzione è ovvia ed è l'unico numero presente nell'equazione che se sostituito all'incognita conduce all'uguaglianza, come ad esempio: $\dfrac{2}{3} = \dfrac{2}{3} \longrightarrow True$.

Le equazioni immediatamente più complesse sono quelle del tipo $3x = -3$ e $10 = x + 4$ per le quali vedremo un metodo risolutivo nella prossima unità.



### ESERCIZIO 1 - Verifica di soluzioni

a) Controlla se il numero dato è soluzione delle seguenti equazioni.

1. $6,\enspace x + 12 = 28$;
2. $110,\enspace x - 50 = 60;$  
3. $-8,\enspace 2b + 3 = -15;$ 
4. $-2,\enspace 5t - 3 = -16$.

b) Controlla se il numero dato è soluzione delle seguenti equazioni.

1. $\{x=5\},\enspace 0.5x = 2.9$;
2. $\{x=6\},\enspace 33 - \dfrac{x}{2} = 30$;
3. $\{x=5\},\enspace 0.5x = 2.9$;
4. $\{a=1\},\enspace \dfrac{2}{a + 1} + 5 = \dfrac{12}{a + 1}$;
5. $\{a=\dfrac{7}{3}\},\enspace -4 = a + \dfrac{5}{3}$

#### Laboratorio GEOGEBRA

a) Risolvi i punti dell'esercizio con il comando GEOGEBRA seguente:

1. $Sostituisci(x + 12 = 28, x=6)$ &#9166; 

b) Risolvi i punti b.1 e b.2 con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $e1: 0,5x = 2,9$ &#9166; 
2. $s1: Sostituisci(e1, x=5)$ &#9166; 
3. $PrimoMembro(s1) == SecondoMembro(s1)$ &#9166;

Controlla che il comando $PrimoMembro(s1)$&#9166; fornisce $\dfrac{5}{2} \approx 2,5$ mentre $SecondoMembro(s1)$&#9166; fornisce $\dfrac{29}{10} \approx 2,9$  



## UNITA' 2: Metodo risolutivo delle equazioni di I grado

La soluzione alle equazioni molto semplici può essere trovata per tentativi, ossia con una ricerca "euristica". Ad esempio il numero che raddoppiato è uguale a $10$ è $5$, oppure il numero che sommato a $3$ è uguale ad $1$ è $-2$. Trovare questi numeri significa risolvere le equazioni $2x = 10$ e $3 + x = 1$, che sono molto semplici.

Se però l'equazione è anche di poco più complessa, trovare la soluzione senza un metodo diventa impossibile. Il metodo per risolvere le equazioni è basato sull'applicazione ripetuta di tre ***regole di equivalenza***, che consentono di trasformare una equazione in una nuova equazione, più vicina ad una equazione elementare, che però abbia le stesse soluzioni di quella originaria.

### REGOLA DELLA SEMPLIFICAZIONE

Possiamo effettuare operazioni algebriche su uno o entrambi i membri di una equazione ottenendo una nuova equazione che ha le stesse soluzioni di quella originaria.

#### ESEMPIO 1

a) $3 + x -3 = 1 -3$  Possiamo eseguire le somme algebriche tra $3$ e $-3$ e tra $1$ e $-3$ ed ottenere l'equazione b).

b) $x = -2$   Nuova equazione

L'equazione b) ha le stesse soluzioni della a), come si può controllare sostituendo in entrambe ad $x$ il numero $-2$.

### REGOLA DEL TRASPORTO (SOMMA)

Possiamo sommare ad entrambi i membri di una equazione una stessa espressione ottenendo una nuova equazione che ha le stesse soluzioni della equazione originaria.

#### ESEMPIO 2

a) $3 + x = 1$   Sommando a questa prima equazione $-3$ si ottiene l'equazione b);

b) $3 + x -3 = 1 -3$. Nuova equazione

L'equazione b) ha le stesse soluzioni della a), come si può controllare sostituendo in entrambe ad $x$ il numero $-2$. Se applichiamo alla b) la regola della semplificazione al membro sinistro otteniamo la c)

c) $x = 1 - 3$. 

Questa equazione ha le stesse soluzioni della a) ed il numero $+3$ è scomparso dal membro sinistro ed è comparso sommato al membro destro il suo opposto cioè $-3$. Questo succede sempre applicando in sequenza le regole della somma e della semplificazione, per cui si può enunciare la seguente regola, detta ***regola del trasporto***:

Possiamo trasportare una espressione da un membro ad un altro cambiando il suo segno (da termine di una somma di un membro a termine di una somma nell'altro, col segno opposto). La nuova equazione che si ottiene ha le stesse soluzioni della precedente.

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



### ESERCIZIO 2 - Regole delle Equazioni

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

### ESERCIZIO 3 - Risoluzione di equazioni

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



### ESERCIZIO 4 - Scrittura di equazioni

a) Per ciascuno dei punti seguenti, scrivi l'equazione con le caratteristiche richieste.

1. Ha come (unica) soluzione il numero -3;
2. ha come soluzione un numero che ha il doppio uguale a 6;
3. ha come soluzione il numero il cui doppio meno 5 è uguale al numero stesso.

b) Per ciascuno dei punti seguenti, scrivi l'equazione con le caratteristiche richieste e trova la sua soluzione.

1. Ha come soluzione il numero -3 e ha l'incognita in entrambi i membri;
2. ha come soluzione il numero che sommato al suo successivo è uguale a 3;
3. consiste nell'uguaglianza tra un numero ed il suo opposto.



## UNITA' 3: Equazioni letterali e formule

Fino ad ora si sono considerate solo equazioni numeriche, con una sola lettera, l'incognita. Oltre a queste però si usano anche equazioni in cui compaiono altre lettere, oltre a quella che ha il ruolo di incognita, come ad esempio $1-ax=b$, dove l'incognita è $x$.

Queste equazioni si risolvono con lo stesso metodo di quelle numeriche; la soluzione sarà una espressione letterale e non numerica.

a) $1-ax=b$;   Con la regola del trasporto portiamo 1 a destra;

b) $-ax=b-1$;   Con la regola della moltiplicazione/divisione moltiplichiamo tutto per il reciproco del coefficiente di $x$;

c) $-ax(-\dfrac{1}{a})=-\dfrac{1}{a}(b-1)$  Semplificando

d) $x = -\dfrac{1}{a}(b-1)$.

   

### ESERCIZIO 5 - Equazioni letterali

a) Risolvi le seguenti equazioni considerando la lettera $x$ come (unica) incognita.

1. $ax = 2a;\enspace bx - 2 = 0;\enspace 2x = y;$

2. $2a - 3x = 7a - 5x;\enspace b(x - 2) + b + 1 = 0;\enspace 2y = -\dfrac{1}{3}x;$

3. $2bx = 2b - 1;\enspace ax = ab;\enspace x + y = 1;$

4. $6x - 3(x + 2a) = a + 4(x - 2a) ;\enspace b(x - 2) + b + 1 = 0;\enspace \dfrac{-2}{3}(x - y) + 3y = -x + 4;$

b) Nei punti 1. e 2. precedenti sostituisci all'incognita l'espressione trovata dimostrando che è la soluzione.

#### Laboratorio GEOGEBRA

a) Risolvi la prima equazione del punto a.2) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $l: 2a -3x = 7a - 5x$ &#9166; 
2. $Risolvi(l, x)$ &#9166; 

b) Risolvi la seconda equazione del punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $l: bx -2 = 0$ &#9166; 
2. $m: Risolvi(l, x)$ &#9166; 

Controlla che la soluzione è corretta sostituendo all'incognita la soluzione trovata con il comando $Sostituisci(l, m)$ &#9166; . Osserva che il primo membro è uguale al secondo.



### ESERCIZIO 6 - Formule e formule inverse

Di seguito sono presentate alcune formule famose provenienti da discipline varie:

1) Area di un rettangolo: $A = b \cdot h$;     Area di un triangolo: $A = \dfrac{b \cdot h}{2}$;

2. Interesse semplice: $I = C\cdotp i\cdotp t$;      Montante: $M = C + I$;
3. Sconto: $S = P_l - P_s$  ($P_l$: Prezzo di listino, $P_s$: Prezzo scontato);     Percentuale di Sconto: $s = \dfrac{S}{P_l}$;
4. Profitto (Utile): $U = R - C$  ($R$: Ricavi, $C$: Costi);      Utile (in percentuale) sulle vendite: $m = \dfrac{U}{R}$:
5. Mark-Up (assoluto): $M = P_{v} - C$  ($P_v$: Prezzo di vendita, $C$: Costo);     Mark-Up (percentuale) $q$: $P_v = C \cdotp (1 + q)$.
6. Velocità: $v = \dfrac{s}{t}$.

a) Risolvi le equazioni letterali proposte considerando di volta in volta ciascuna formula come una equazione, con l'incognita indicata.

1. $M = C + I, ~~~ incognita ~~ C;$
1. $A = b \cdot h, ~~~ incognita ~~ b$;
3. $A = \dfrac{b \cdot h}{2}, ~~~ incognita ~~ b$;    $A = \dfrac{b \cdot h}{2},   ~~ incognita ~~ h$;
2. $S = P_l - P_s, ~~~ incognita ~~ P_s;$
2. $I = C\cdotp i\cdotp t ,~~~ incognita ~~ i$;       $I = C\cdotp i\cdotp t ,~~~ incognita ~~ C$;
3. $\dfrac{P_l - P_s}{P_l}= s ~~~ incognita ~~ P_s;$
3. $\dfrac{P_l - P_s}{P_l}= s ~~~ incognita ~~ P_l $;
4. $P_v = C \cdotp (1 + q) ~~~ incognita ~~ C;$
4. $P_v = C \cdotp (1 + q) ~~~ incognita ~~ q$, (dimostrando così che la formula del mark-up si può scrivere $q =\dfrac{P_v - C}{C}$). 

b) Risolvi ciascuna equazione considerando la lettera indicata come l'incognita.

1. $3x + y = 9, ~~~ incognita ~~ y; \enspace\enspace 5y - x = 25, ~~~ incognita ~~ y$

2. $-x + 3y = 9. ~~~ incognita ~~ y; \enspace\enspace \dfrac{7}{8}c + w = 9, ~~~ incognita ~~ c$

#### Laboratorio GEOGEBRA

a) Risolvi l'equazione a.6) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito.

1. $eq1: (P_{l} - P_{s})/P_{l}= s$ &#9166; 
2. $Risolvi(eq1, P_{l})$ &#9166; 



### ESERCIZIO 7 - Applicazione di formule

Risolvi i problemi seguenti individuando una formula risolutiva ed applicandola, sostituendo i numeri alle lettere, nel caso specifico. 

a) Nel 2006 il film Titanic ha avuto un incasso mondiale di 1835 milioni di dollari con un profitto di 1595 milioni. Quanto è costato il film?

b) Trova il margine (mark-up assoluto e percentuale) di un fioraio che nel giorno di San Valentino compra una dozzina di rose a 12.95 euro e le rivende a 47.50.  

c) Se una mongolfiera viaggia ad una media di 37 Km/h, quanto tempo impiegherà a percorrere 166 Km?  

d) Un aereo vola tra Chicago e S. Francisco in 3.75 ore. Se le città distano 2100 Km quale è la velocità media dell'aereo?



## UNITA' 4: Disequazioni ed intervalli

### ESERCIZIO 8 - Disuguaglianze e disequazioni

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



### ESERCIZIO 9 - Soluzione di Disequazioni I

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



### ESERCIZIO 10 - Intervalli e disequazioni elementari

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

1. $a : 0 <= x <= 3$ &#9166; 
2. $a(2)$ &#9166;

Per rappresenta graficamente l'intervallo:

1. Dal "Menu Principale" seleziona "Cambia Calcolatrice" / "Grafici";
2. Dal menu della casella di input, seleziona "Impostazioni" e quindi dalla scheda "Stile" seleziona "Mostra sull'asse X".

<img src="img\diseq-0-3.png" alt="diseq-0-3" style="zoom:25%;" />

b) Risolvi la restante parte del punto a.1) con sequenze di comandi GEOGEBRA analoghi a quelli precedenti. Ricorda di utilizzare altre etichette per indicare gli intervalli ($b, c$, etc.).



### ESERCIZIO 11 - Soluzione di Disequazioni II

a) Per ciascuno dei casi seguenti, scrivi l'insieme delle soluzioni delle disequazioni come intervalli.

1. $x-1\ge 2$;   $7x-1\ge 2$;   $-x-1\le 2$;   $\dfrac{x}{5}-1\ge 2$;
2. $4x - 3 > 5x + 1$;   $4[2(1 - x) -3] > 5x + 1$;    $5(x-1) < 2(x-3)$;
3. $3\left[(x+3)+\dfrac{1}{3}x\right]<7x$;   $3(x-1)-1 < \dfrac{x-2}{3} - \left(x-\dfrac{x-1}{3}\right)$;
4. $\dfrac{2+x}{3} \ge x + \dfrac{1}{2}$;   $2x-5\lt 3+2x$;   $2(x+1) - 5x\ge 3x + 4(x+1)$.

