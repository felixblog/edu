# I Sistemi di I Grado

## UNITA' 1: Equazioni con due incognite e loro soluzioni

Fino ad ora abbiamo visto equazioni di I grado con una sola incognita, ma una equazione di primo grado può avere anche due incognite, come ad esempio $x + y = 5$. Le soluzioni di equazioni del genere sono sempre numeri che sostituiti alle incognite rendono l'equazione una uguaglianza vera, ma stavolta i numeri da sostituire sono due, uno per incognita, per cui una soluzione è sempre una ***coppia di numeri*** che sostituita ordinatamente alle incognite (il primo elemento della coppia per la prima lettera, la $x$, ed il secondo per la seconda, la $y$) rende l'equazione vera.

Parlando di equazioni con due incognite, i problemi che ci si pongono, come nel caso di una incognita, sono tre:

1. ***Verifica di Soluzioni***: Data una coppia di numeri, controllare se la coppia è una soluzione dell'equazione;
2. ***Ricerca di soluzioni***: Data una equazione, trovare qualche soluzione dell'equazione (almeno due);
3. **Scrittura di Equazioni**: Dato un problema, scrivere una o più equazioni le cui soluzioni risolvono il problema

Per rispondere alla prima domanda basta sostituire alle incognite ordinatamente i numeri della coppia e controllare che l'uguaglianza risulti vera.

#### ESEMPIO 1

Controlliamo se la coppia $(1,4)$ è soluzione di $x + y = 5$.

a) $x + y = 5, \; \{x = 1, y = 4\}$;

b) $1 + 4 = 5 \longrightarrow True$.

La coppia è soluzione. La tabella seguente riporta alcuni esempi di sostituzioni di coppie di numeri nell'equazione $x + y = 5$.
$$
\textbf{Sostituzioni} \\
\begin{array}{|c|c|}
\hline
\mathbf{(x, y)} & \mathbf{x + y = 5} \\
\hline 
(0, 5) & 0 + 5 = 5 \longrightarrow True \\
\hline 
(1, 4) & 1 + 4 = 5 \longrightarrow True \\
\hline 
(-1, 6) & (-1) + 6 = 5 \longrightarrow True \\
\hline 
(2, 6) & 2 + 6 = 5 \longrightarrow False \\
\hline 
(-2, 7) & (-2) + 7 = 5 \longrightarrow True \\
\hline 
(3, 3) & 3 + 3 = 5 \longrightarrow False \\
\hline\end{array}
$$
Come si può notare a differenza delle equazioni con una sola incognita, dove c'è di norma una sola soluzione, le soluzioni alle equazioni con due incognite sono più di una, di norma sono ***infinite***.     $\bullet$



La ricerca di soluzioni di una equazione con due incognite si fa nel modo seguente: si sceglie un numero a caso come primo elemento della coppia, si sostituisce ad una incognita e si risolve l'equazione ad una sola incognita che rimane per trovare l'altro elemento della coppia.

#### ESEMPIO 2

Per trovare una soluzione dell'equazione $x + y = 5$ partiamo sostituendo ad $x$ il valore $0$ e risolviamo l'equazione così ottenuta rispetto ad $y$.

a) $x + y = 5, \{x = 0\}$;

b) $(0) + y = 5$;

c) $y = 5$.

La soluzione trovata è $(0, 5)$. Troviamone un'altra sostituendo ad $x$ il valore $1$:

a) $x + y = 5, \{x = 1\}$;

b) $(1) + y = 5$;

c) $y = 5 -1$;

d) $y = 4$;

Le due soluzioni trovate sono $(0,5)$ e $(1, 4)$.     $\bullet$



### ESERCIZIO 1.1 - Verifica di soluzioni di equazioni con due incognite

a) Verifica di quale equazione è soluzione la coppia di numeri proposta nei punti seguenti.    

1. $(3;1)$     $eq1: 5x-3y=12$;    $eq2: x-2y=1$;

2. $(5;-2)$    $eq1: 3x+2y=-1+y$;     $eq2: 6x-9y=2y+x$;
3. $(9;2)$     $eq1: y+3(y+x)=-1$;    $eq2: x-y=7$.

b) Verifica di quale delle equazioni seguenti è soluzione la coppia di numeri $(9,-2)$.

1. $eq1: y+3(y+x)=-1$;    $eq2: x-y=11$.

#### Laboratorio GEOGEBRA

a) Risolvi il punto a) dell'esercizio con la sequenza di comandi GEOGEBRA:

1. $eq1: 5x-3y=12$ &#9166; 
2. $Sostituisci(eq1, {x=3,y=1})$ &#9166; . 



### ESERCIZIO 1.2: Ricerca di soluzioni di equazioni con due incognite

a) Trova tre soluzioni dell'equazione $x-2y=1$;

b) Trova due soluzioni dell'equazione $y+3(y+x)=-1$. 



## UNITA' 2: Equazioni in forma esplicita

Spesso è utile scrivere una equazione con due incognite in una forma diversa da quella originale, detta ***forma esplicita*** (rispetto ad una incognita). L'equazione in forma esplicita deve essere equivalente a quella originale, ossia deve avere le stesse soluzioni, ma una forma diversa, la seguente:
$$
y = \text{espressione in x;}
$$
è la forma esplicita dell'equazione rispetto alla $y$.

#### ESEMPIO 1

Se risolviamo l'equazione $x + y = 5$ rispetto all'incognita $y$, otteniamo, applicando la regola del trasporto $y = 5 - x$, che è in forma esplicita rispetto alla $y$. La nuova equazione ha ovviamente per soluzioni le stesse coppie di numeri dell'equazione originaria. Questo procedimento viene detto di **esplicitazione** rispetto all'incognita $y$.    $\bullet$

#### ESEMPIO 2

Equazione originale: $0 = 2y + x$,  forma esplicita rispetto alla $y$:  $y = -\dfrac{1}{2}x$.      $\bullet$

La trasformazione dell'equazione in forma esplicita viene fatta risolvendo l'equazione rispetto all'incognita da esplicitare **come se questa fosse l'unica incognita**.



### ESERCIZIO 2.1 - Esplicitazione di incognita

a) Risolvi le equazioni seguenti come se la lettera $y$ fosse l'unica incognita.

1. $2x-y=0$;

2. $x+3y=-1$;

3. $7x-\dfrac{1}{3}y+1=y$.

b) Risolvi le equazioni seguenti come se la lettera $x$ fosse l'unica incognita.

1. $3x+y=1-2y$;
2. $4x-3y = 2y+2-5x$;
3. $4(y - 2x) + 10x - 3 = -2$.

#### Laboratorio GEOGEBRA

a) Risolvi il punto a) dell'esercizio con la sequenza di comandi GEOGEBRA:

1. $eq1: 5x-y=0$ &#9166; 

2. $Risolvi(eq1, \{y\})$ &#9166; . 



## UNITA' 3: Sistema di equazioni e metodo di soluzione

Un ***sistema*** di equazioni è un gruppo (due) di equazioni (in due incognite) **di cui si cercano le soluzioni comuni**, ossia le coppie di numeri che siano soluzioni simultaneamente di tutte le equazioni. Mentre una equazione ha solitamente infinite soluzioni, due equazioni hanno solitamente (ossia tranne casi particolari) una sola soluzione. Per trovarla si utilizza un metodo detto di ***sostituzione*** che si articola in 4 passi. Per illustrare il metodo risolveremo il sistema seguente:

$$\left\{  
\begin{array}{c} 
2x+y=-1 \\  
x-3y=10\\   
\end{array} 
\right.$$

#### PASSO 1:  Esplicitazione

Si sceglie una equazione, si sceglie una incognita e si esplicita rispetto a questa incognita, ossia si risolve come se questa fosse l'unica incognita, trovando come soluzione una **espressione letterale**. Ad esempio consideriamo la prima equazione e risolviamo rispetto alla $y$ ottenendo la soluzione $-1-2x$:

a) $y = -1 - 2x$.

La nostra equazione con due incognite avrà quindi una **soluzione letterale** della forma $(x, -1-2x)$.

#### PASSO 2: Sostituzione

Si sostituisce la soluzione trovata, $(x,-1-2x)$, nell'altra equazione (il secondo elemento della coppia deve sostituire la $y$ tutte le volte che compare) perché la soluzione deve rendere vera anche la seconda equazione. Si ottiene così una equazione con una sola incognita, che deve essere verificata dalla soluzione del sistema:

b) $x - 3y = 10, \{x = x, y = -1-2x\}$;

c) $x - 3(-1-2x) = 10$.

#### PASSO 3: Risoluzione

Si risolve l'equazione con una sola incognita trovando il numero che la verifica.

d) $x +3 +6x = 10$;

e) $7x = 7$;

f) $x = 1$.

#### PASSO 4: Completamento

Si sostituisce il numero alla incognita nella soluzione letterale trovata alla fine del PASSO 1, che diventa così una soluzione numerica:

g) $(x, -1-2x), \{x = 1\}$;

h) $(1, -1 - 2(1))$;

i) $(1, -3)$.

La coppia $(1, -3)$ è una soluzione numerica di entrambe le equazioni e di conseguenza del sistema.



### ESERCIZIO 3.1 - Metodo di sostituzione

a) Risolvi i sistemi seguenti con il metodo di sostituzione. 

1. $$\left\{  
   \begin{array}{l} 
   2x+y=-1 \\  
   x-3y=12 \\   
   \end{array} 
   \right.$$

2. $$ \left\{  
   \begin{array}{l} 
   2y-5=-2x-6+y \\  
   2(x-1)=3(1-2y)+19 \\   
   \end{array} 
   \right.$$

3. $$ \left\{  
   \begin{array}{l} 
   x-2=\dfrac{y}{3}-1+\dfrac{x}{2} \\  
   \dfrac{5x+3y}{6}-3=\dfrac{2x-y}{4}+\dfrac{7}{12} \\  
   \end{array} 
   \right.$$

4. $$ \left\{  
   \begin{array}{c} 
   3x-1=0 \\ 
   4x+2y=0 \\ 
   \end{array} 
   \right.$$

b) Verifica che la soluzione del sistema a.1) non è soluzione del sistema a.4)

#### Laboratorio GEOGEBRA

a) Risolvi il punto a.1) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito:

1. $a: 2x+y=-1$ &#9166; 
2. $b: x-3y=12$ &#9166; 
3. $Risolvi(\{a,b\}, \{x,y\})$ &#9166; . 

b) Risolvi i punti a.2) e a.3) dell'esercizio con analoghe sequenze di comandi GEOGEBRA (utilizza altre lettere per indicare le equazioni).



## UNITA' 4: Problemi di I grado risolubili con un sistema

### ESERCIZIO 4.1 - Problemi vari

Risolvere con un sistema i problemi seguenti.  

a) Hai a disposizione € $5,00$ per acquistare penne e quaderni. Se compri $4$ quaderni e $3$ penne, ti mancano
€ $0,25$; se compri $3$ quaderni e $3$ penne, ti avanzano € $0,65$. Quanto costa un quaderno e quanto una penna?  

b) Possiedo € $30,00$. Con questo denaro acquisto alcune magliette da € $6,50$ ciascuna e alcuni calzini da € $3,50$ al paio. Sapendo che il numero di magliette coincide col numero di paia di calzini, calcola quante sono.    

c) Lucia e Elena sono sorelle. La somma delle loro età è $31$ e Lucia è nata tre anni prima di Elena.
Quanti anni ha ciascuna?  

d) $10$ sacchi di frumento ed $8$ di mais pesano $1\ 646 \ Kg$; $30$ sacchi di frumento e $12$ di mais, rispettivamente uguali ai precedenti, pesano $3\ 894\ Kg$.
Quanto pesa ciascun sacco di frumento e ciascun sacco di mais?  

e) In una fabbrica ci sono $2$ macchine, la prima produce $10$ pezzi all’ora, la seconda $7$ pezzi all’ora.
Le due macchine hanno prodotto in tutto $191$ pezzi, lavorando complessivamente $23$ ore. Determina il numero dei pezzi prodotti dall’una e dall’altra macchina.  

f) Due serbatoi hanno capacità rispettivamente proporzionali a $7$ e $4$. Il serbatoio maggiore contiene tanto liquido quanto quello minore più i $\dfrac{3}{4}$ di quest’ultimo. Determina le capacità. 



### ESERCIZIO 4.2 - Sistemi con tre incognite

Risolvere i sistemi seguenti con il metodo di sostituzione. 

a)  $$\left\{  
\begin{array}{l} 
2x+y-z=-1 \\  
y-3z=11 \\   
z=1 \\   
\end{array} 
\right.$$

b)  $$ \left\{  
\begin{array}{l} 
x+y=0 \\  
x+y-2z=3 \\
x-y+z=1
\end{array} 
\right.$$

c)  $$ \left\{  
\begin{array}{l} 
x+y-z=10 \\ 
-2x+y+2z=4 \\ 
3x-2y+3z=8 \\ 
\end{array} 
\right.$$

d)  $$ \left\{  
\begin{array}{l} 
a+b=-1 \\ 
b+c=-4 \\ 
a+c=1 \\ 
\end{array} 
\right.$$

#### Laboratorio GEOGEBRA

a) Risolvi il punto d) dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito:

1. $e: a+b=-1$ &#9166; 
2. $f: b+c=-4$ &#9166; 
2. $g: a+c=1$ &#9166; 
3. $Risolvi(\{e,f,g\}, \{a,b,c\})$ &#9166; . 
