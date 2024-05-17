
# Matematica Finanziaria: Regimi Finanziari

## UNITA' 1: Concetti fondamentali e capitalizzazione

La Matematica ﬁnanziaria è quella branca della matematica
applicata che ha per oggetto lo studio delle ***operazioni ﬁnanziarie***, ovvero delle operazioni di scambio di importi monetari tra due o più soggetti (creditori e debitori) in date diverse.

Le operazioni finanziarie di cui parliamo di definiscono "certe", ossia non dipendenti da alcun evento imprevisto che possa modificare o influenzare l'esito finale previsto e concordato fra i due attori dell'operazione, sia nel valore delle somme pattuite che nei tempi. (Nella realtà nessuna operazione che riguardi il futuro è certa: qui si vuole dire che i calcoli che si fanno in matematica finanziaria non tengono conto di eventi aleatori, come invece succede in altre discipline).

Le operazioni finanziarie avvengono all'interno di ***contratti ﬁnanziari***, ossia di accordi tra due o più parti per
scambiarsi degli importi monetari in determinate date. Esempi di contratti finanziari sono i seguenti:

- Un cittadino investe i propri risparmi (creditore) in un deposito
  bancario cedendoli quindi alla banca (debitore) e posticipando
  la disponibilità dei risparmi ad una data futura;
- Un cittadino stipula un contratto di mutuo immobiliare
  (debitore) ottenendo un ﬁnanziamento da una banca (creditore) e quindi
  anticipando la disponibilità di denaro;
- Un’impresa ottiene un prestito (debitore) da una banca (creditore) per ﬁnanziare un progetto produttivo;
- Un cittadino compra un BOT (creditore) emesso dallo Stato
  Italiano (debitore) che da il diritto di restituzione della somma con interessi.
- Viene stipulato con una assicurazione un contratto per il pagamento ai beneﬁciari di un importo di 100.000 Euro alla morte
  dell’assicurato (Assicurazione caso morte vita intera). Non rientra nella matematica finanziaria perché in questo contratto è noto l’importo, ma non la sua durata. 

Un contratto ﬁnanziario genera un’operazione ﬁnanziaria, cioè
una serie di scambi di importi ciascuno caratterizzato da
una propria ***data di esigibilità*** (scadenza) e valuta di
denominazione. Una operazione finanziaria viene rappresentata con un grafico dove sono indicate con $x_i$ le somme scambiate e con $t_i$ le date (scadenzario).

<img src="img/op-fin-1.png" alt="op-fin-1" style="zoom:80%;" />

Parliamo di ***operazione ﬁnanziaria elementare*** quando sono
coinvolte soltanto due date: $(x_0, t_0)$ e $(x_1, t_1)$ e solitamente gli importi sono uno positivo ed uno negativo corrispondente ad una operazione di finanziamento o investimento.

<img src="img/fin-1.png" alt="fin-1" style="zoom:80%;" />

<img src="img/inv-1.png" alt="inv-1" style="zoom:80%;" />

In entrambe le operazioni un soggetto (creditore) cede la somma di denaro $C$ detta ***capitale*** (iniziale), al tempo $0$, ad un altro soggetto (debitore). Quest'ultimo, al tempo $t$ dovrà restituire la somma $M$, detta ***montante*** o capitale finale, tipicamente maggiore di $C$. 

La differenza $M-C$ è detta ***interesse*** ed è indicata da $I$, cioè:
$$
M-C = I
$$
$I$ è detto "prezzo del tempo" ed economicamente rappresenta il compenso che il debitore paga al creditore per avere la disponibilità del denaro $C$ (o equivalentemente perché il creditore rinunci alla disponibilità di $C$). 

L’operazione di calcolo del montante, che si può scrivere $M = C+I$ e che corrisponde al calcolo del valore "futuro" della somma $C$, si chiama operazione di
***capitalizzazione***.

Il problema che ci poniamo è quali relazioni ci siano tra $M$, $C$ e $t$, quest'ultima la ***durata*** dell'operazione finanziaria. Essendo queste quantità regolate da un contratto tra le parti, si potrebbe pensare che vengano usate per il loro calcolo modalità dei tipi più vari; in realtà vengono solitamente applicate delle regole, o schemi, standard, che vanno
sotto il nome di ***regimi ﬁnanziari***.

Facciamo alcune considerazioni. E' intuitivo pensare che l'interesse di una operazione finanziaria sia più grande quanto più grande è il capitale e più lunga la durata dell'operazione, così come l'importo dell'affitto da pagare per la disponibilità di una casa cresce al crescere della superficie della casa e della durata del periodo. Vi è però anche da considerare il prezzo "unitario" dell'affitto, ossia il prezzo "mensile" al "metro quadro", che dipendere dalla "qualità" dell'abitazione (popolare, media, lusso, etc.).

Analogamente il prezzo "unitario" per la disponibilità di denaro, ossia l'interesse da pagare per avere una unità di capitale per una unità di tempo è detta ***tasso di interesse*** dell'operazione e dipende dal mercato dei capitali del momento.

Detto ciò, il regime più semplice che esamineremo, detto dell'***interesse semplice***, prevede che l'interesse di una operazione elementare sia direttamente proporzionale al capitale ed alla durata dell'operazione e la costante di proporzionalità sia data dal tasso di interesse, cioè:
$$
I = C \cdot i \cdot t
$$
L'interesse, calcolato nel regime dell'interesse semplice, è detto ***interesse semplice***. In questo regime il montante è allora calcolato sostituendo la formula dell'interesse nella definizione di montante.
$$
M = C(1+it)
$$


### ESERCIZIO 1.1 - Interesse semplice: montante

Calcola l’interesse semplice e il montante dei seguenti capitali (in euro) impiegati alle condizioni indicate: 

a) 500 per 1 anno al tasso del 12% annuo;

b) 1.200 per 8 mesi al tasso dell’11% annuo;

c) 400 per 4 mesi e 20 giorni al tasso del 9% annuo;

d) 1.500 per 8 mesi al tasso del 3% bimestrale;

e) 600 per 7 mesi al tasso del 2,50% trimestrale;

f) 845 per 4 mesi e 15 giorni al tasso del 6% semestrale.




### ESERCIZIO 1.2 - Interesse semplice: capitale
a) Determina i capitali che, nel regime dell’interesse semplice, hanno prodotto i seguenti montanti alle condizioni indicate:  

1. 890 in 9 mesi al tasso del 15% annuo  
2. 504 in 150 giorni al tasso del 12% annuo  
3. 861,42 in 102 giorni al tasso del 3% quadrimestrale

b) Calcola quale capitale impiegato al tasso annuo del 10% da in 8 mesi l’interesse semplice di 34 euro.  

c) Calcola quale capitale impiegato al tasso annuo del 9% da in 3 mesi e 10 giorni un interesse semplice di 115 euro.

d) Il capitale di 6.000 euro ha prodotto l’interesse semplice di 480 euro. Calcola i tassi annui se la durata dell’impiego e stata di:

1. un anno;
2. 10 mesi; 
3. 8 mesi;
4. 4 mesi 




### ESERCIZIO 1.3 - Interesse semplice: durata

a) Calcola in quanto tempo il capitale di 3.300 euro, impiegato al tasso annuo del 10%, ha prodotto il montante di 3.547 euro  

b) Per quanto tempo e necessario lasciare depositato il capitale di 540 euro, al tasso del 4% trimestrale, per poter ritirare il montante di 600 euro? 



## UNITA' 2: Operazioni di Attualizzazione e Sconto

Immaginiamo ora che ci sia una operazione finanziaria in corso che preveda la restituzione della somma $C$, detta ***valore nominale*** alla data di scadenza.  Se l'operazione si concludesse prima della scadenza, la somma restituita non sarebbe $C$ ma $V \; (< C)$, dove la differenza
$$
C-V=S
$$
detta ***sconto*** è il compenso che il debitore paga al creditore (in termini di riduzione degli interessi pattuiti) per la rinuncia alla disponibilità di denaro. La quantità $V$ si chiama ***valore attuale*** o somma scontata. L’operazione di calcolo del valore attuale, che ci consente di
valutare importi restituiti anticipatamente nel tempo, si chiama operazione di*** attualizzazione***, o anche di sconto.

Nel regime dell'***interesse semplice*** la relazione tra valore attuale e valore nominale è
$$
V = \dfrac{C}{1+it}
$$
dove $t$ è la durata del periodo di anticipazione e $i$​ è il tasso di interesse dell'operazione.




### ESERCIZIO 1.4 - Interesse semplice: sconto

a) Una cambiale del valore nominale di 510 euro viene scontata, in regime di capitalizzazione semplice, 3 mesi prima della scadenza, al tasso dell’8% annuo. Calcolare la somma scontata e lo sconto. 

b) Con il pagamento di 840 euro si salda anticipatamente un debito del valore nominale di 863 euro fruendo dello sconto razionale, al tasso dell’8,50% annuo. Determinare il tempo di anticipazione.

c) Un debito viene saldato prima della scadenza, fruendo dello sconto razionale al tasso del 16%. Calcolare la scadenza del debito se la somma scontata è pari ai 9/10 del valore nominale. 

d) Un commerciante per 1'acquisto di una merce deve fare tre pagamenti uguali, di 300 euro ciascuno, scadenti il primo oggi, il secondo fra 2 mesi, il terzo fra 6 mesi. Pagando tutto oggi può fruire dello sconto razionale al tasso del 9% annuo. Calcolare il valore complessivo da pagare oggi.



## UNITA' 3: Regime dell'interesse composto

Nel regime dell’interesse semplice, il capitale resta sempre
“separato” dagli interessi, qualunque sia la durata
dell’investimento o del ﬁnanziamento.
Nella pratica accade invece che, periodicamente (ad es. ogni anno,
piuttosto che ogni 3 mesi), gli interessi vengano “capitalizzati”,
cioè diventino a loro volta capitale e quindi concorrano a
produrre nuovi interessi (questo fenomeno, detto "anatocismo", nel passato era vietato per legge, a tutela dei debitori, ora è ammesso).

Supponiamo, per ﬁssare le idee, che la capitalizzazione avvenga
una volta all’anno, e che l’investimento del capitale $C$ sia
effettuato in una data di capitalizzazione (cioè al tempo $0$ corrispondente ad
una data $31/12$ di fine anno).

Dopo un anno, gli interessi vengono aggiunti al capitale,
per cui il montante, che diventa il nuovo capitale su cui calcolare gli interesse all'inizio del secondo periodo sarà pari a
$M_1 = C +Ci = C(1 +i)$.

Dopo un ulteriore anno, questa somma produrrà interessi pari a
$C(1 +i)i$ che saranno di nuovo aggiunti al capitale di inizio periodo portando il montante del secondo periodo a 
$M_2 = C(1 +i)+iC(1 +i) = C(1 +i)(1 +i) = C(1 +i)^2$.

Dopo 3 anni il montante sarà pari a $M_3 = C(1 +i)^3$ e, in
generale, dopo un numero intero $n$ di anni si riceverà un montante pari a
$M_n = C(1 +i)^n$.

Se la capitalizzazione avvenisse, ad esempio, ogni trimestre, si
potrebbe ragionare in modo analogo supponendo però che l’unità
di misura del tempo non sia l’anno bensì il trimestre, cioè che $m$
(intero) rappresenti il numero di trimestri ($m=4$), e inoltre che il tasso sia "periodale", indicato con $i_{1/m}$, in questo caso trimestrale.


### ESERCIZIO 3.1 - Interesse composto: montante I

a) Calcolare il montante ad interesse composto delle operazioni seguenti.

1. 500 euro per 10 anni al tasso dell’8,10% annuo;

2. 1.800 euro per 6 anni al tasso del 12,15% annuo;

b) Calcolare il montante ad interesse composto delle operazioni seguenti che hanno capitalizzazione periodale

1. $800$ euro per un anno al tasso del $3,10\%$ semestrale ($m=2$);

2. $1.000$ euro per $10$ anni al tasso del $5,30\%$ quadrimestrale ($m=3$);

3. $600$ euro per $5$ anni e $6$ mesi al tasso del $3,50\%$ bimestrale.




### ESERCIZIO 3.2 - Interesse composto: montante II
a) II capitale di 6.000 euro è impiegato ad interesse composto al tasso annuo del $14\%$ per $5$ anni. Il montante viene subito reinvestito per altri $4$ anni al tasso annuo dell’$11\%$.  
1. Quale montante si può ritirare? 
2. Quale montante si sarebbe ritirato se per i primi $4$ anni il tasso fosse stato dell’$11\%$ e per i successivi $5$ fosse stato del $14\%$? 

b) Una persona prende in prestito $20.000$ euro al tasso annuo del $12\%$ e le investe al tasso annuo del $15\%$. Quanto guadagna se l'impiego e di $5$ anni?




### ESERCIZIO 3.3 - Interesse composto: valore attuale I

a) Calcola il valore attuale con interesse composto dei seguenti capitali alle condizioni indicate:

1. 1.200 euro per 5 anni al tasso del 7% annuo;

2. 800 euro per 10 anni al tasso del 12% annuo;

b) Calcola il valore attuale con interesse composto dei seguenti capitali alle condizioni indicate:

1. 665 euro per 4 anni e 6 mesi al tasso del 3% trimestrale;

2. 3.012 euro per 2 anni e 5 mesi al tasso dell’1,50% mensile.




### ESERCIZIO 3.4 - Interesse composto: valore attuale II
a) Scontiamo una cambiale del valore di 20.000 euro scadente fra 5 anni con sconto composto al tasso del 12%. Investiamo subito la somma riscossa al lasso del 16%. Quale guadagno realizzeremo fra 5 anni?

b) Per l’acquisto di un alloggio sono richiesti i seguenti pagamenti: L. 30.000.000 alla stipulazione del contralto e tre somme di euro 10.000 ciascuna scadenti fra 2, 4 e 6 anni. Se si vuole pagare tutto subito si applica lo sconto composto al tasso annuo del 9%. Quale somma complessivamente si deve pagare alla stipulazione del contratto per acquistare l’alloggio in contanti? 



## UNITA' 4: Tassi equivalenti e tassi nominali

Nel regime dell’interesse composto, ci si può porre il problema di quale tasso periodale (trimestrale, quadrimestrale etc.) sia **equivalente** ad un tasso di interesse annuale ossia produca dopo $n$ anni lo stesso montante.

Indicando con $m$ il numero di periodi che compongono l'anno, ossia $m=3$ per il trimestre, $m=2$ per il semestre e così via, Il tasso periodale $i_{1/m}$ equivalente a quello annuale $i$ è il tasso periodale che produce dopo un anno lo stesso montante di quello annuale, ossia
$$
M_1 = C(1 + i_{1/m})^m = C(1 + i)
$$
per cui
$$
i_{1/m} = (1 + i)^\frac{1}{m} - 1
$$
Il calcolo di un tasso annuale a partire da uno periodale non viene fatto dalla formula precedente ma dalla moltiplicazione del tasso periodale per il numero dei periodi. Il tasso annuo che si ottiene in questo caso è detto **tasso annuo nominale convertibile** (trimestralmente, semestralmente etc.), si indica con $j(m)$ e vale la relazione
$$
j(m) = m \cdot i_{1/m}
$$



### ESERCIZIO 4.1 - Tassi equivalenti

a) Determinare il tasso trimestrale equivalente al tasso
annuo di interesse dell’$1.8\%$.

b) Determinare il tasso annuo di interesse $i$ di un investimento sapendo che il tasso mensile corrispondente $0,31\%$.

### ESERCIZIO 4.2 - Tassi nominali convertibili

a)  Determinare il tasso nominale annuo di interesse convertibile $3$ volte all’anno associato al tasso annuo di interesse del
$3.7\%$.



