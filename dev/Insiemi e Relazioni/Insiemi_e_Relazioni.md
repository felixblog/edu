
# Insiemi e Relazioni

## UNITA' 1: Insiemi e loro rappresentazione

Un ***insieme*** è qualcosa di cui tutti abbiamo un'idea e precisamente è un gruppo di oggetti, concreti o astratti (come lettere dell'alfabeto, numeri, etc.); gli oggetti che formano l'insieme sono detti ***elementi*** dell'insieme.

Un po' più complesso è trovare un modo per descrivere (o ***rappresentare***) un insieme; vi sono tre modi:

1. graficamente, mediante un diagramma di Venn;
2. per elencazione;
3. mediante proprietà caratteristica degli elementi.

Rappresentare un insieme in modo grafico significa disegnare un cerchio o ellisse (che rappresenta l'insieme) con all'interno gli elementi rappresentati con dei punti ed il loro nome (univoco) o dal nome soltanto.

#### ESEMPIO 1

L'insieme delle vocali, che chiameremo $V$, è rappresentato graficamente dalla figura seguente.

<img src="img/venn-1.png" alt="venn-1" style="zoom:15%;" />



Rappresentare un insieme per elencazione significa scrivere la sequenza degli elementi identificati dai loro nomi univoci (in un insieme ***non ci possono essere due elementi uguali***) separati da virgola e racchiusi tra parentesi graffe.

#### ESEMPIO 2

Per rappresentare per elencazione l'insieme delle vocali scriviamo $\{ a, e, i, o, u\}$; se vogliamo dare il nome $V$ all'insieme (di solito i nomi degli insiemi sono maiuscoli) scriviamo $V = \{ a, e, i, o, u\}$.



Una proprietà è ***caratteristica*** degli elementi di un insieme se consente di individuare tali oggetti tra tutti gli altri che non sono elementi dell'insieme. Una proprietà di un oggetto si esprime attraverso una frase che sarà vera per tutti gli oggetti che possiederanno quella proprietà e falsa per gli altri.

Solitamente la proprietà si esprime utilizzando una frase generica, che riguarda un oggetto qualsiasi $x$ e che dovrà essere vera se al posto dell'oggetto generico abbiamo un oggetto specifico, come nell'esempio seguente.

#### ESEMPIO 3

Presupponendo che tutti sappiano, tra le lettere dell'alfabeto, quali sono le vocali, la proprietà caratteristica dell'insieme delle vocali è data dalla proposizione: "$\text{`x' e' una vocale}$", perché sostituendo alla $\text{x}$ una vocale ed un'altra lettera abbiamo:

$\text{"x" e' una vocale}, \{x = u\} \longrightarrow \text{"u" e' una vocale} \longrightarrow True$.

$\text{`x' e' una vocale}, \{x = b\} \longrightarrow \text{`b' e' una vocale} \longrightarrow False$.

Quindi l'insieme delle vocali è indicato come $V = \{x: x \; \acute{e} \; una \; vocale\}$ che si legge "V è ***l'insieme delle x tali che...*** x è una vocale". In particolare "$\{$" si legge "L'insieme delle... ":" si legge "tali che" .... e la parentesi chiusa non si legge.



Introduciamo ora il simbolo $\in$ che si legge "appartiene a". Con questo simbolo possiamo scrivere, riprendendo l'insieme delle vocali $V$, che $a \in V$, che si legge "a appartiene a $V$"e che è una formula vera. Invece $b \in V$ è falsa perché $b$ è una consonante e non appartiene a $V$. 

Se vogliamo affermare che $b$ non appartiene a $V$ possiamo usare il simbolo $\notin$ che si legge "non appartiene a", per cui $b \notin V$​ diventa una formula vera. 



Un sottoinsieme di un insieme $I$ è un insieme formato da alcuni elementi di $I$ (al limite anche tutti). Per indicare che un insieme è sottoinsieme di un altro usiamo il simbolo $\sub$: se vogliamo dire che l'insieme delle vocali $V$ è un sottoinsieme delle lettere dell'alfabeto $L$ scriviamo
$$
V \sub L
$$
che è vero.



### ESERCIZIO 1.1 - Rappresentazione per Elencazione.

a) Rappresenta per elencazione, e con diagramma di Eulero-Venn, gli insiemi $A$, $B$ e $C$ formati rispettivamente dalle lettere delle parole «rododendro», «giglio», «azalea».

b) Rappresenta per elencazione i seguenti insiemi:  

1. I naturali non maggiori di 8;  
2. I naturali dispari compresi fra 30 e 40;  
3. I multipli pari di 7 minori di 40;  
4. I divisori di 42;  
5. I divisori primi di 42:  
6. I giorni della settimana che iniziano per «b»;  
7. Le vocali della parola «farfalla»

c) Rappresenta per elencazione i seguenti insiemi:  
1. L’insieme A dei numeri del tipo $3n$, con n ∈ {0, 2, 4, 6};  
2. L’insieme B dei numeri del tipo $2n + 1$, con n ∈ {0, 1, 2, 3, 4};  
3. L’insieme C dei numeri del tipo $-2n$, con n ∈ {-2, -1, 0, 1, 2};  
4. L’insieme D dei numeri del tipo $\dfrac{3n + 1}{3}$, con n ∈ {-3, -2, -1, 1, 2, 3}.

#### Laboratorio

a) Risolvi il punto a) dell'esercizio prendendo ad esempio i comandi GEOGEBRA riportati di seguito:

​		$Unico(Suddividi(''rododendro'',\{''''\})))$ &#9166; 

b) Risolvi il punto c) dell'esercizio prendendo ad esempio i comandi GEOGEBRA riportati di seguito:

1. $Compatta(3\cdot n, n, \{0, 2, 4, 6\} )$ &#9166; 
2. $Compatta(2 \cdot n + 1, n, \{0, 1, 2, 3, 4\} )$ &#9166; 



### ESERCIZIO 1.2 - Rappresentazione mediante proprietà caratteristica

a) Rappresenta gli insiemi seguenti mediante una proprietà caratteristica dei loro elementi.  
1. $A = \{martedi, mercoledi\}$;  
2. $B = \{Nord, Sud, Est, Ovest\}$;  
3. $C = \{\alpha, \beta, \gamma\}$;  
4. $D = \{a, e, i, o, u\}$;  
5. $E = \{5, 7, 9, 11, 13\}$;  
6. $F = \{8, 9, 10, 11, 12, 13, 14, 15\}$;  
8. $G = \{12, 16, 20, 24, 28, 32\}$;  
9. I numeri interi pari minori o uguali a 16;  
10. I numeri naturali compresi fra 10 e 30;  
11. Gli interi negativi.



### ESERCIZIO 1.3 - Dalla proprietà caratteristica all'elencazione

a) Scrivi la rappresentazione per elencazione dei seguenti insiemi.  
1. $A = \{x: x \; \acute{e} \; una \; lettera \; della \; parola \; «avvocato»\}$;  
2. $B = \{x: x \; \acute{e} \; una \; vocale\}$;  
3. $C = \{x: x \; \acute{e} \; il \; nome \; di \; un \; mese \; che \; inizia \; con \; la \; lettera \; «g»\}$;  

b) Trova il numero degli elementi degli insiemi riportati di seguito.  

1. $A = \{x: x \; \acute{e} \; un \; pianeta \; del \; sistema \; solare \}$;  
2. $B = \{x: x \; \acute{e} \; una \; provincia \; del \; Lazio \}$;
5. $C = \{x: 2x - 5 = -x + 7 + 3x\}$.

#### Laboratorio

a) Risolvi il punto b.2 dell'esercizio con la sequenza di comandi GEOGEBRA riportata di seguito:

1. $B = \{''Roma'', ''Latina'', ''Rieti'', ''Viterbo'', ''Frosinone''\}$ &#9166; 
2. $ContaSe(true, B)$  &#9166;

b) Utilizzando le istruzioni GEOGEBRA del punto precedente, risolvi il punto a) dell'esercizio.

 

### ESERCIZIO 1.4 - I Sottoinsiemi

a) Considera i seguenti insiemi: $A = \{SERA\}$, $B = \{S, E, R, A\}$, $C = \{A, R, S, E\}$, $D = \{R, E, S, A\}$, $E = \{RESA\}$.  
1. Descrivi a parole i loro elementi  
2. Quali insiemi sono uguali tra loro?  

b) Scrivi tutti i sottoinsiemi dell’insieme $A = \{a, b, c\}$.

c) Scrivi tre parole le cui lettere formino tre insiemi $A$, $B$, $C$, tali che $A \subset B \subset C$.

d) Stabilisci se gli insiemi $A$, $B$, $C$ sono sottoinsiemi dell’insieme $D$:  

1. $A = \{x \in \mathbb{N}: x \; \acute{e} \; multiplo \; di \; 5\}$, $B = \{x \in  \mathbb{Z}: x \ge -1\}$, $C = \{5, 10, 15\}$, $D = \mathbb{N}$.  
2. $A = \{x: x \; \acute{e} \; una \; lettera \; di \; «diario»\}$, $B = \{x: x \; \acute{e} \; una \; lettera \; di \; «ardore»\}$, $C = \{x: x \; \acute{e} \; una \; lettera \; di \; «orda»\}$, $D = \{x: x \; \acute{e} \; una \; lettera \; di \; «radio»\}$.

#### Laboratorio

a) Risolvi il punto a) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito:

1. $Unico(\{''SERA''\}) == Unico(\{''S'',  ''E'', ''R'', ''A''\})$  &#9166;
2. $Unico(\{''S'', ''E'', ''R'', ''A''\}) == Unico(\{''A'', ''R'', ''S'', ''E''\})$  &#9166;
3. $Unico(\{''A'', ''R'', ''S'', ''E''\}) == Unico(\{''R'', ''E'', ''S'', ''A''\})$  &#9166;
4. $Unico(\{''R'', ''E'', ''S'', ''A''\}) == Unico(''RESA'')$  &#9166;

b) Risolvi il punto d.2) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito:

1. $A=Unico(Suddividi(''diario'',\{''''\})))$ &#9166;
2. $B=Unico(Suddividi(''ardore'',\{''''\})))$ &#9166;
3. $C=Unico(Suddividi(''orda'',\{''''\}))$ &#9166;
4. $D=Unico(Suddividi(''radio'',\{''''\})))$&#9166; 
5. $A \subseteq B$  &#9166; 
6. $A \subseteq D$  &#9166; 
7. $A \subset D$  &#9166; 



## UNITA' 2: Operazioni tra insiemi

Con gli insiemi è possibile fare delle operazioni, come ad esempio con la moltiplicazione tra numeri: moltiplicando due numeri si produce un terzo numero, che è il prodotto dei due. Tra insiemi è possibile fare tre operazioni, l'**unione**, l'**intersezione** e la **differenza**. 

L'**unione** tra due insiemi $A$ e $B$ è un terzo insieme, che indichiamo con $A \cup B$ formato dagli elementi che appartengono ad $A$ o a $B$; in simboli:
$$
A \cup B = \{x: x \in A \; oppure \;x \in B\}
$$


L'**intersezione** tra due insiemi $A$ e $B$ è un terzo insieme, che indichiamo con $A \cap B$ formato dagli elementi che appartengono sia ad $A$ che a $B$:
$$
A \cup B = \{x: x \in A \; e \;x \in B\}
$$


La differenza tra due insiemi $A$ e $B$ è un terzo insieme, che indichiamo con $A \setminus B$ formato dagli elementi che appartengono ad $A$ ma non a $B$:
$$
A \setminus B = \{x: x \in A \; e \;x \notin B\}
$$


### ESERCIZIO 2.1 - Intersezione ed Unione

a) Per ogni coppia di insiemi determina l’unione e l’intersezione, e rappresentale per elencazione e mediante un diagramma di Eulero-Venn:  
1. $A = \{x: x \; \acute{e} \; una \; lettera \; della \; parola \; «tegame»\}$, $B = \{x: x \; \acute{e} \; una \; lettera \; della \; parola \; «gomito»\}$.
2. $C = \{x: x \; \acute{e} \; una \; lettera \; della \; parola \; «attesa»\}$, $D = \{x: x \; \acute{e} \; una \; lettera \; della \; parola \; «paese»\}$.  

b) Per ciascuna coppia di insiemi $A$ e $B$ determina l'insieme $A \cap B$:  
1. $A = \{x: x \; \acute{e} \; un \; multiplo \; di \; 4\}$ e $B = \{x: x \; \acute{e} \; un \; multiplo \; di \; 6\}$;  
2. $A = \{x: x \; \acute{e} \; un \; divisore \; di \; 8\}$ e $B = \{x: x \; \acute{e} \; un \; divisore \; di \; 12\}$.  

c) Dati gli insiemi $A = \{0, 1, a\}$, $B = \{1, 2, a, b\}$ e $C = \{0, 2, 4\}$, calcola i risultati delle seguenti espressioni:  
1. $A \cap B \cap C$  
2. $A \cup (B \cup C )$

#### Laboratorio

a) Risolvi il punto a) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito:

1. $A=Unico(Suddividi(''tegame'',\{''''\})))$ &#9166;   $B=Unico(Suddividi(''gomito'',\{''''\})))$ &#9166;   
2. $C=Unico(Suddividi(''attesa'',\{''''\}))$ &#9166;   $D=Unico(Suddividi(''paese'',\{''''\})))$ &#9166; 
3. $Unione(A, B)$  &#9166; 
4. $Interseca(A, B)$  &#9166;  




### ESERCIZIO 2.2 - Problemi su intersezione ed unione

a) In una classe di 32 alunni, 18 giocano a calcio e 20 a pallavolo. Di essi, 16 praticano entrambi gli sport. Calcola quanti alunni non praticano ne’ il calcio ne’ la pallavolo.  

b) Un’indagine di mercato compiuta su 90 famiglie ha evidenziato che 59 possiedono il robot da cucina, 80 hanno il forno a microonde o il robot da cucina e 24 possiedono entrambi gli elettrodomestici.  
Quante famiglie hanno solo il robot e quante solo il forno? Quante non possiedono nessuno di questi elettrodomestici? [R. 35; 21; 10]  

c) In un gruppo di 18 persone ciascuno porta almeno uno fra cappello, giacca e cravatta. Si sa che in 6 portano il cappello, in 9 la giacca e in 12 la cravatta. Due persone portano cappello e cravatta e nessuno porta cappello e giacca. Stabilisci quante persone hanno giacca e cravatta.  

d) In una sala sono presenti 62 persone, ognuna delle quali ha almeno una delle caratteristiche seguenti: essere europei o essere studenti. Si sa che gli studenti non europei sono 12, che gli inglesi non studenti sono 8, che gli studenti europei non inglesi sono 22 e che gli europei non inglesi né studenti sono tanti quanti gli studenti inglesi. Determina il numero degli inglesi.



### ESERCIZIO 2.3 - Differenza e Complemento

a) Dati $A = \{x: \; x \;è \;residente \;in \;Veneto \}$ e $B = \{x: \;x \;è \;residente \;a \;Venezia\}$, descrivi a parole $A \setminus B$ e $B \setminus A$.

b) Dati gli insiemi $A$, $B$, $C$, formati rispettivamente dalle lettere delle parole «colore», «sapore», «odore», determina la differenza fra tutte le possibili coppie di insiemi.

c) Determina $A$ e $B$ in modo che:

1. $A \cup B = \{a, b, c, d, e, f, g, h\}$;
2. $A \cap B = \{e, g\}$;
3. $A \setminus B = \{a, d, h, b\}$;
4. $B \setminus A = \{c, f \}$.

Le informazioni fornite sono eccessive. Quante ne bastano?

d) Determina descrivendolo a parole, il complementare dei seguenti insiemi rispetto all’insieme $U$ indicato.  

1. $U = \{x: \;x \;è \;una \;lettera \;dell’alfabeto\}$, $A = \{x: \;x \;è \;una \;vocale\}$.  
2. $U = \{x: \;x \;è \;un \;punto \;della \;superficie \;terrestre\}$, $A = \{x: \;x \;è \;un \;punto \;delle \;terre \;emerse\}$.

#### Laboratorio

a) Risolvi il punto b) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito:

1. $A=Unico(Suddividi(''colore'',\{''''\})))$ &#9166;
2. $B=Unico(Suddividi(''sapore'',\{''''\})))$ &#9166;   
3. $A \setminus B$  &#9166; 
4. $B \setminus A$  &#9166; 



### ESERCIZIO 2.4 - Prodotto Cartesiano

a) Dati gli insiemi $A$ e $B$, rappresenta il prodotto $A \times B$ per elencazione e con un diagramma cartesiano nei casi seguenti.

1. $A = \{a, b\}$ e $B = \{4, 6\}$
2. $A = \{x ∈ N: 1 \lt x \;e \; x \le 4 \}$ e $B = \{x ∈ N: 5 \lt x \;e \; x \lt 10 \}$
3. $A = \{Milan, Inter, Sampdoria\}$ e $B = \{Roma, Lazio, Juventus\}$

b) Dati i seguenti prodotti cartesiani, scrivi gli elementi dell’insieme A e quelli dell’insieme B.

1. $A \times B = \{(r, t), (e, r), (r, e), (e, t), (r, r), (e, e)\}$
2. $B \times A =  \{(1, a), (2, a), (1, b), (2, b)\}$
3. $A \times B = \{(+, a), (+ , b), (+, c), (+ , a), (- , b),  (-, c)\}$

#### Laboratorio

a) Risolvi il punto a) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito (utilizza una singola lettera minuscola al posto dei nomi delle squadre):

1. $A=\{a, b\}$  &#9166;   $B=\{4, 6\}$  &#9166;
2. $Compatta(Compatta((h,k),h,A), k, B\})$ &#9166;   



## UNITA' 3: Le relazioni

In questa unità studieremo le relazioni tra elementi di due insiemi. Una relazione tra gli elementi di due insiemi è una **proprietà delle coppie di elementi**, dove il primo elemento della coppia appartiene al primo insieme ed il secondo al secondo insieme. Questa proprietà si esprime attraverso una frase che sarà vera se gli elementi sono in relazione tra di loro e falsa se non lo sono.

#### ESEMPIO 1

Consideriamo l'insieme $A = \{0, 1, -1, 2, -2\}$ e $B = \{0, 1, -1\}$ e la relazione tra due elementi: il primo è il doppio del secondo.

Quali sono gli elementi in relazione tra di loro?

E' evidente che $0$ ed $1$ non sono in relazione tra di loro perché $0$ non è il doppio di $1$ mentre $0$ è in relazione con $0$ perché è il doppio di $0$. Se consideriamo l'insieme di tutte le coppie $A \times B$, dove il primo numero è in $A$ ed il secondo in $B$, abbiamo che i numeri in relazione tra di loro sono quelli facenti parte del sottoinsieme $S=\{(0,0), (2,1), (-2, -1)\}$.

Se quindi esprimiamo la relazione utilizzando una frase generica, che riguarda due elementi qualsiasi $x$ ed $y$, $x \in A$ e $y \in B$ e  $R(x, y):\; x \; è \; il \; doppio \; di \; y$, possiamo dire che la relazione $R(x,y)$ è la proprietà caratteristica di $S$, un sottoinsieme del prodotto cartesiano $A \times B$:
$$
\{(0,0), (2,1), (-2, -1)\} = \{(x,y): x \; è \; il \; doppio \; di \; y\}
$$
cioè $S = \{(x,y): R(x,y)\}$.



### RAPPRESENTAZIONE DELLE RELAZIONI

Le relazioni si possono rappresentare i diversi modi. Quella vista fin'ora è la rappresentazione insiemistica per elencazione. Possiamo poi fare di una relazione una rappresentazione **tabellare**, come nell'esempio seguente.

In ogni colonna ci sono gli elementi di un insieme e gli elementi in relazione tra di loro sono sulla stessa riga. 

#### ESEMPIO 1: Rappresentazione Tabellare

$$
\begin{array}{r|r}
x\; & y \\
\hline 
0\; & 0 \\
2\; & 1 \\
-2\; & -1 \\
\end{array}
$$



#### ESEMPIO 2: Rappresentazione Cartesiana

<img src="img/Relazioni-cartesiana.png" alt="Relazioni-cartesiana" style="zoom:15%;" />





#### ESEMPIO 3: Rappresentazione Sagittale



<img src="img/Sagittale.png" alt="Sagittale" style="zoom:80%;" />



#### ESEMPIO 4: Rappresentazione Tabellare a doppia entrata (Matrice)


$$
\begin{array}{r|c} 
 & -1 & \;0\;\; & \;1\;\;\; \\ 
\hline -2 & \times & &  \\ 
\hline -1 &  \\ 
\hline 0 &  & \times\\  
\hline 1 &  &  \\  
\hline 2 &  & & \times \\  
\end{array}
$$


#### ESEMPIO 5: Rappresentazione ad Albero





### ESERCIZIO 3.1 - Le relazioni. Dalla proprietà caratteristica all'elencazione

a) Considera il disegno seguente che illustra i rapporti di parentela tra gli elementi di una famiglia.

![Famiglia](img/Famiglia.drawio.png)

Se $P = \{Sara, Tommaso, Roberto, Elisa, Anna, Patrizia, Giovanni\}$, elenca le coppie, elementi di  $P \times P$, con le proprietà definite di seguito:

1. $R_1$: $\text{«x \'e madre di y»}$;
2. $R_2$: $\text{«x \'e genitore di y»}$;;
3. $R_3$: $\text{«x \'e  sorella di y»}$;
4. $R_4$: $\text{«x \'e nipote di y»}$;;

b) Dati gli insiemi $A = \{1, 2, 3, 4, 5\}$ e $B = \{-1, 0, 1, 2\}$, scrivi i sottoinsiemi di $A \times B$ le cui coppie soddisfano le proprietà seguenti:

1. $R_1$: $«x + y = 4»$;
2. $R_2$: $«x = 2y»$;
3. $R_3$: $«x \le y»$.

c) Considera l'insieme di persone $P$ del punto a) e l'insieme di città $C = \{Roma, Latina, Rieti, Viterbo, Frosinone\}$. I fatti seguenti indicano la città di abitazione di ciascuno:

f~1~: "Sara e Tommaso abitano a Roma";

f~2~: "Anna abita a Latina e Patrizia a Frosinone";

f~3~: "Elisa abita a Viterbo";

f~4~: "Giovanni abita a Frosinone".

Tenendo conto dei fatti precedenti, elenca gli elementi di:

1. $P \times C$ che soddisfano la proprietà $R_1(x, y)$: $\text{«x abita a y»}$";
2. $P \times P$, che soddisfano $R_2(x,y)$: $\text{«x abita nella stessa città di y»}$;
3. $I = \{x \in P: R_2(x,Roma)\}.$ 

#### Laboratorio

a) Risolvi il punto b) dell'esercizio prendendo esempio dalla sequenza di comandi GEOGEBRA riportata di seguito:

1. $A = \{1, 2, 3, 4, 5\}$  &#9166;
2. $B = \{-1, 0, 1, 2\}$  &#9166;
3. $C = Singola(Compatta(Compatta((h, k), h, A), k, B))$ &#9166;   
4. $TieniSe(x(A) + y(A) == 4, A, C)$   &#9166;



### ESERCIZIO 3.2 - Rappresentazione delle relazioni

a) Dati gli insiemi $A = \{x ∈ N:  x \lt 4 \}$ e $B = \{2, 4, 5\}$, rappresenta la relazione in $A \times B$, definita dalla proprietà caratteristica «La somma di x e y è dispari», in forma sagittale, cartesiana, tabellare ed a matrice (tabellare a doppia entrata).

b) Nell'esercizio 9.a  rappresenta le relazioni in forma sagittale, cartesiana, tabellare. A quale delle tre rappresentazioni corrisponde quella riportata in figura? 

b) Scrivi in forma sagittale, cartesiana e tabellare la relazione $R = \{(Franco;3), (Anna;6), (Luigi;8), (Ester;7), (Marco; 6)\}$, che rappresenta i voti di 5 alunni in un compito in classe di italiano. Quali sono gli insiemi di cui è composto il prodotto cartesiano di questa relazione? 



### ESERCIZIO 3.3 - Dall'elencazione alla proprietà caratteristica

a) Riflettendo sui nomi utilizzati, rappresenta le relazioni seguenti mediante una proprietà caratteristica dei loro elementi, dopo aver trovato gli insiemi del prodotto cartesiano su cui si basa la relazione.

1. $A = \{(lunedi, martedi), (mercoledi, giovedi), (venerdi, sabato)\}$;  
2. $B = \{(Nord, Sud), (Est, Ovest)\}$;  
3. $C = \{(0,0), (1, 2), (-1, -2), (2, 4), (-2, -4)\}$;  
