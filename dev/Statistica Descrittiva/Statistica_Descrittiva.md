# Statistica Descrittiva Parte Prima

Al giorno d'oggi ciascuno di noi ha a disposizione una grande quantità di informazioni che riguardano la realtà che lo circonda. Internet ci fornisce continuamente dati su prodotti in vendita, informazioni economiche sui titoli in borsa, notizie su altri paesi etc.

Abbiamo potenzialmente la possibilità di sapere tante cose per decidere nella maniera migliore cosa comprare, dove andare, cosa mangiare, in breve per prendere delle decisioni informate. E' però necessario organizzare queste informazioni, perché sono tante e ci servono dei criteri per fare le scelte migliori e non fermarci alla prima opzione che ci si presenta.

Una caratteristica comune a tutte le cose di cui abbiamo parlato è la loro quantità: abbiamo più primi piatti tra cui scegliere, più negozi per comprare lo stesso prodotto, più persone cui dare la nostra amicizia, ciascuno con le sue caratteristiche e particolarità. È solo quando un certo numero di dati viene raccolto, confrontato, analizzato e compreso che vengono generate informazioni utili per prendere delle decisioni.

Proprio di questo si occupa la statistica, che ci dà un insieme di strumenti e tecniche per trasformare dati grezzi (non elaborati) in informazioni sintetiche e riassuntive che rappresentano informazioni utili per supportare un processo decisionale efficace.



## UNITA' 1: Statistica e Fenomeni Collettivi

La statistica è la scienza che studia i ***fenomeni collettivi***, ossia fenomeni che **non sono percepibili con una sola osservazione** di una entità ma richiedono un certo numero di osservazioni, fatte su un insieme di individui o unità.

Sono per esempio fenomeni collettivi:

- il fatturato ed i costi di una azienda (la somma del valore delle vendite);
- la clientela di una azienda in una regione in un certo mese;
- la natalità e la mortalità degli individui di una nazione o città o regione;
- la valutazione in "stelle" di un prodotto su Amazon (Numero di 5 Stelle, 4 Stelle etc.);
- la qualità della produzione (definita come la media di una caratteristica sui prodotti dell'azienda)

Concetti come "natalità", "fatturato", "produzione", si dicono "collettivi" nel senso che riguardano una collettività nel suo insieme e non dei singoli individui, anche se ciascun individuo partecipa al fenomeno. Vi sono quindi delle proprietà riferibili al collettivo che saranno espresse in funzione di quelle dei singoli individui, solitamente come conteggio, somme, medie e così via. Ad esempio il "fatturato aziendale" è la somma del ricavato di ogni singola vendita, il reddito familiare è la somma, o la media, del reddito dei componenti di una famiglia e così via.

Fissato un fenomeno collettivo da studiare, diciamo **unità statistica** la singola entità in cui si osserva il fenomeno in esame. L’insieme delle singole unità statistiche interessate dallo studio del fenomeno collettivo è detto **collettivo statistico** o **popolazione**. 

Alcuni esempi di unità statistiche:

- individui (clienti di un albergo, turisti, studenti, dipendenti di un’azienda, ecc...);
- oggetti (automobili, aziende, prodotti di consumo, ecc...);
- aggregati territoriali (stati, regioni, province, comuni, altro ancora);
- unità temporali (anni, mesi, giorni, altro ancora);



### Osservazioni, caratteri e modalità

Il fenomeno di cui si parla è rilevabile attraverso una **osservazione o rilevazione**, mediante la quale si registrano i **dati di una unità**, ossia le **caratteristiche** che interessano.

Parlando di una popolazione di persone, caratteristiche di una singola unità sono il fatto che è nata il 22-04-2002, oppure che sia di sesso maschile o che pesa 67 Kg. Il "peso", la "data di nascita" o il "sesso" sono attributi di *tutte* le unità statistiche della popolazione e sono detti **caratteri** o **variabili**; se la popolazione è costituita dalle vendite di una azienda, le variabili di interesse possono essere il prodotto venduto, il venditore, il cliente etc.

Ci sono molti modi per rilevare una caratteristica in una osservazione. Ad esempio, se le unità sono le interrogazioni in una classe, la variabile "valutazione dell'interrogazione" potrebbe essere rilevata con un numero da 0 a 10 oppure con un giudizio, "sufficiente" o "insufficiente" e questo incide sul grado di accuratezza o **precisione** con cui rileviamo il fenomeno. Si dicono **valori** (o **modalità**) della variabile (o del carattere) i modi con cui una caratteristica viene rilevata: "sufficiente" e "insufficiente" sono un modo per fare una "valutazione dell'interrogazione", ma ce ne possono essere altri.

Si chiamano ***caratteri quantitativi*** quelli che hanno modalità numeriche. I dati sono il risultato di un **conteggio** o una **misurazione**, come ad esempio il reddito di una popolazione (in euro o altra unità), le vendite di un anno (ad esempio in milioni di euro), il numero delle unità abitative in un comune etc.

Si chiamano ***caratteri qualitativi*** quelli che hanno modalità che sono espressioni verbali, aggettivi o nomi. Ad esempio il carattere "sesso" ha modalità 'maschio' e 'femmina', o "Religione" che ha modalità:  'Cristiana', 'Islamica', 'Buddista', ecc. titolo di studio, marca .... In questi casi il carattere non assume valori numerici ma ammette gradi o attributi distinti.

La modalità che viene effettivamente assunta dal carattere in una specifica osservazione è il **dato statistico**. Al posto di dire che "un carattere assume una certa modalità", possiamo dire anche che "La variabile assume un certo valore".

#### ESEMPIO 1

Si vuole analizzare il titolo di studio dei dipendenti di un ufficio in relazione all'età. I dipendenti sono 7 . Sono stati raccolti i dati riportati nella tabella seguente.

$$
\textbf{DIPENDENTI} \\
\begin{array}{|l|l|c|}
\hline
\textbf{Nominativo} & \textbf{Titolo di Studio} & \textbf{Eta} \\
\hline
\text{Antonio Rossi} & \text{Laurea} & 48 \\
\hline
\text{Francesca Verdi} & \text{Diploma}         & 59  \\
\hline
\text{Franco  Gialli}   & \text{Licenza Media}  & 37  \\
\hline
\text{Luigi  Neri}       & \text{Laurea}         & 23  \\
\hline
\text{Giacomo  Bianchi} & \text{Laurea}         & 24  \\
\hline
\text{Antonio  Bianchi} & \text{Laurea}          & 37  \\
\hline
\text{Amedeo  Verdi}    & \text{Diploma}         & 61  \\
\hline
\end{array}
$$


La popolazione è costituita dall’insieme dei dipendenti dell'ufficio e ciascun dipendente è una unità statistica. Le **caratteristiche delle unità**, o **variabili** <u>di interesse</u>, sono "Titolo di Studio" ed "Età".

Le modalità del Titolo di studio sono: {Laurea, Diploma, Licenza Media, Licenza Elementare} mentre le modalità dell’età sono i numeri che vanno da 18 a 70.  $\bullet$



#### ESEMPIO 2

Si vuole effettuare un'indagine statistica sulla qualità del trasporto pubblico per le scuole di una determinata città. Si devono quindi individuare la popolazione, le unità statistiche, i caratteri più significativi per l'indagine e le loro modalità.

La popolazione potrebbe essere l'insieme di tutti i viaggi effettuati in un certo periodo di tempo da tutte le persone che si recano in una qualunque scuola della città (insegnanti, studenti, personale amministrativo e tecnico). L'unità statistica è quindi il viaggio ed i caratteri più rilevanti sono:

- Uso del mezzo di trasporto (modalità: Si, No) 

- Tipologia del mezzo (modalità: Nessuno, Autobus, Metropolitana, Auto, Moto, Bicicletta, Altro);

- Età del Viaggiatore (modalità: numeri interi compresi tra 2 a 90);

- Sesso  del Viaggiatore (modalità: M, F);

- Distanza del Domicilio dalla Scuola: (modalità: numeri decimali);

- Motivazione del non utilizzo di un mezzo (modalità: descrizione testuale);

- Grado di soddisfazione (modalità: valori da 1 a 10).

- Data ed ora del viaggio (modalità: data ed ora)

$\bullet$



### ESERCIZIO 1.1 - Popolazioni, caratteri e modalità

a) Per effettuare un'indagine sull'utilizzo dei computer nella tua città, quali potrebbero essere i caratteri da rilevare? Quali le unità statistiche?  

b) Per effettuare una indagine statistica sul consumo di alcol tra i ragazzi da 16 a 21 anni della tua città, quale sarebbe la popolazione statistica da considerare? quali i caratteri e la modalità?

c) In una Provincia, si vuole analizzare il numero delle abitazioni occupate in rapporto al numero di stanze. Quale è la popolazione da considerare? Quali sono i caratteri da rilevare?

d) In un Comune si svolge una indagine sul numero di giornate con precipitazioni nevose, secondo i mesi dell'anno, negli ultimi 10 anni. Quali sono le unità statistiche? Quali i caratteri?



## UNITA' 2: Frequenze ed Intensità

Avendo a disposizione i dati della popolazione, una prima analisi è quella che consiste nel calcolo di quante unità posseggono certe caratteristiche, cioè, nell'esempio del titolo di studio dei dipendenti, quanti dipendenti posseggono la laurea, quanti il diploma ecc. Questa analisi ci consente di sapere quale titolo di studio è il più frequente tra la popolazione e quale lo è meno (analisi delle frequenze).

La **Frequenza (assoluta) di una modalità** (in inglese "proportion") è il numero di unità della popolazione che presentano la modalità, ossia il numero di volte che la modalità di un carattere viene osservata nella popolazione.

La **Frequenza relativa di una modalità** è il rapporto tra la frequenza assoluta della modalità ed il numero delle unità della popolazione.

La **distribuzione di frequenza (assoluta o relativa) di un carattere** è l'associazione alle modalità del carattere, quantitativo o qualitativo, del numero delle frequenze assolute/relative osservate. 

#### ESEMPIO 1

Il direttore del personale di un’industria ha somministrato un breve questionario a 20 addetti nel quale si chiedeva:

- La qualifica (Operaio, Impiegato, Quadro, Dirigente)
- Il grado di pesantezza del lavoro svolto (1: "poco faticoso", 2: "moderatamente faticoso", 3: "faticoso", 4: "molto faticoso", 5: "estremamente faticoso")
- Il numero di figli a carico
- La retribuzione media oraria (in euro/h)
- La disponibilità di un’auto propria (0: "no", 1: "si")

I risultati sono riassunti nella tabella seguente.
$$
\textbf{RISULTATO QUESTIONARIO} \\
\begin{array}{|l|l|c|}
\hline
\textbf{Unita} & \textbf{Qualifica} & \textbf{Pesantezza} & \textbf{N. Figli} & \textbf{Retribuzione} & \textbf{Disp. Auto} \\
\hline 
1 & \text{Operaio}& 2 &  0 & 22,5 & 0 \\
\hline                                   
2 & \text{Impiegato}& 2 &  1 & 23,0 & 1 \\
\hline                                   
3 & \text{Operaio}	& 3  &  3 & 18,5 & 1 \\
\hline                                   
4 & \text{Impiegato}& 4	 &  2 & 18,3 & 1 \\
\hline                                   
5 & \text{Operaio}	& 1	 &  0 & 15,0 & 0 \\
\hline                                   
6 & \text{Impiegato}& 3	 &  1 & 25,7 & 0 \\
\hline                                   
7 & \text{Impiegato}& 3	 &  0 & 24,2 & 1 \\
\hline                                   
8 & \text{Operaio}	& 1	 &  2 & 16,7 & 1 \\
\hline                                   
9 & \text{Operaio}	& 2	 &  2 & 17,9 & 1 \\
\hline                                   
10 & \text{Operaio}	& 3	 &  1 & 15,0 & 0 \\
\hline                                   
11 & \text{Impiegato}& 4 &  2 & 24,6 & 0 \\
\hline                                   
12 & \text{Impiegato}& 2 &  0 & 26,8 & 1 \\
\hline                                   
13 & \text{Impiegato}& 3 &  2 & 21,5 & 1 \\
\hline                                   
14 & \text{Dirigente}& 5 &  2 & 50,3 & 1 \\
\hline                                   
15 & \text{Quadro}	& 3	 &  2 & 23,6 & 1 \\
\hline                                   
16 & \text{Operaio}	& 5	 &  2 & 18,4 & 1 \\
\hline                                   
17 & \text{Operaio} & 2	 &  1 & 18,9 & 0 \\
\hline                                   
18 & \text{Operaio}	& 4	 &  0 & 19,4 & 0 \\
\hline                                   
19 & \text{Operaio}	& 4	 &  3 & 19,3 & 1 \\
\hline                                   
20 & \text{Quadro}	& 1	 &  1 & 26,0 & 0 \\
\hline
\end{array}
$$

Ogni riga della tabella corrisponde a un individuo sul quale sono stati rilevati 5 caratteri. Ciascun carattere assume in corrispondenza di ogni individuo una determinata modalità.

Le frequenze assolute e relative, espresse in percentuale, del Gradi di Pesantezza (*distribuzione* dei Gradi di Pesantezza) e del Numero dei Figli sono le seguenti.


$$
\textbf{DIPENDENTI - Freq. Grado Pesantezza} \\
\begin{array}{|c|c|}
\hline
\textbf{Pesantezza} & \textbf{Freq.} & \textbf{Freq. (\%)}\\
\hline 
1 & 3 & 15\%\\
\hline 
2 & 5 & 25\% \\
\hline 
3 & 6 & 30 \% \\
\hline 
4 & 4 & 20 \% \\
\hline 
5 & 2 & 10 \% \\
\hline 
\textbf{Totale} & \mathbf{20} & \mathbf{100 \%} \\
\hline
\end{array}
$$



$$
\textbf{DIPENDENTI - Freq. N. Figli} \\
\begin{array}{|c|c|}
\hline
\textbf{N. Figli} & \textbf{Freq.} & \textbf{Freq. (\%)} \\
\hline 
0 & 5 & 25 \%\\
\hline 
1 & 5 & 25 \% \\
\hline 
2 & 8 & 40 \% \\
\hline 
3 & 2 & 10 \% \\
\hline 
\textbf{Totale} & \mathbf{20} & \mathbf{100\%}  \\
\hline
\end{array}
$$

Il grado di pesantezza più frequente è $3$ ed il numero di figli più frequente è $2$.  $\bullet$



Se la caratteristica ha molte molte modalità distinte, come ad esempio l'età degli individui, può essere conveniente, o addirittura necessario, raggruppare i valori in intervalli, denominati **classi** o **intervalli di classi** di valori tra loro disgiunti.

#### ESEMPIO 2

Riprendiamo l’esempio dei dipendenti di un ufficio che aveva i dati riportati di seguito.

$$
\textbf{DIPENDENTI} \\
\begin{array}{|l|l|c|}
\hline
\textbf{Nominativo} & \textbf{Titolo di Studio} & \textbf{Eta} \\
\hline
\text{Antonio Rossi} & \text{Laurea} & 48 \\
\hline
\text{Francesca Verdi} & \text{Diploma}         & 59  \\
\hline
\text{Franco  Gialli}   & \text{Licenza Media}  & 37  \\
\hline
\text{Luigi  Neri}       & \text{Laurea}         & 23  \\
\hline
\text{Giacomo  Bianchi} & \text{Laurea}         & 24  \\
\hline
\text{Antonio  Bianchi} & \text{Laurea}          & 37  \\
\hline
\text{Amedeo  Verdi}    & \text{Diploma}         & 61  \\
\hline
\end{array}
$$

Classifichiamo l’età creando tre classi (o fasce): $[18,  30]$ , $[31, 50]$ e $[51, 70]$. Nominiamo ciascuna fascia con le modalità "Giovane", "Maturo" ed "Anziano". Abbiamo allora la seguente distribuzione di frequenze:

$$
\textbf{FREQUENZA CLASSI ETA} \\
\begin{array}{|l|c|c|}
\hline
\textbf{Fascia Eta} & \textbf{Freq.} & \textbf{Freq.\%} \\
\hline 
\text{Giovane} & 1 & 14 \\
\hline                                   
\text{Maturo} & 4 & 57 \\
\hline
\text{Anziano} & 2 & 29 \\
\hline 
\textbf{Totale} & \mathbf{7} & \mathbf{100}  \\
\hline
\end{array}
$$

La classe di lavoratori più numerosa è quella dei Maturi.   $\bullet$



### Caratteri Trasferibili ed Intensità 

Un carattere è detto **trasferibile** se ha senso immaginare che (per un esito alternativo o futuro degli eventi) tutto o parte del carattere di un’unità statistica possa essere trasferito (incrementato o decrementato) a vantaggio di un’**altra unità statistica**. 

Esempi di caratteri trasferibili sono:

- il reddito di un soggetto (che anno dopo anno può variare a beneficio o danno per un altro soggetto) o il suo patrimonio (per cessione, donazione o altro);
- le vendite di una azienda (diminuzione o aumento verso altre aziende a causa della concorrenza);
- il numero di auto in una famiglia (dismissione o acquisto nei confronti di un’altra famiglia);
- i Km percorsi in un anno da una delle auto di una famiglia (se viene usata una piuttosto che un’altra auto per gli spostamenti);
- numero abitanti di una regione (aumento o diminuzione per trasferimento verso altra regione).

I caratteri non trasferibili sono quelli propri di ciascuna unità.

Esempi di caratteri non ttrasferibili sono:

- la statura, il peso, l'età di un soggetto;
- il numero di figli partoriti da una donna;
- la situazione fallimentare di una azienda.

La **Distribuzione di quantità o intensità** è l'associazione alle modalità di un <u>carattere qualitativo</u>, o alle classi se il carattere è quantitativo, del valore di un carattere <u>quantitativo trasferibile</u> calcolato (come somma, media o altro) su tutte le unità che hanno quel carattere (o ricadono nella classe considerata).

#### ESEMPIO 3

Riprendiamo l’esempio del questionario proposto nell'industria dal direttore del personale. La distribuzione delle retribuzioni per qualifica è riportata di seguito.

$$
\textbf{RETRIBUZIONE PER QUALIFICA} \\
\begin{array}{|l|c|c|}
\hline
\textbf{Qualifica}	& \textbf{N. Unita}	& \textbf{Retrib.}	& \textbf{Retrib.\%} \\
\hline
\text{Dirigente}	& 1	& 50,3	& 11 \\
\hline
\text{Quadro}	& 2	& 49,6	& 11 \\
\hline
\text{Impiegato}	& 7	& 164,1	& 37 \\
\hline
\text{Operaio}	& 10	& 181,6 & 41 \\
\hline
\textbf{Totale} &  \mathbf{20}	 & \mathbf{445,6}	 & \mathbf{100} \\
\hline
\end{array}
$$

Per ogni qualifica la colonna "Retrib." è ottenuta come somma delle retribuzioni individuali. E' importante osservare per quali qualifiche si raggiungono i valori massimi e minimi delle retribuzioni: il massimo si ha per gli operai ed il minimo per i quadri.   $\bullet$



#### ESEMPIO 4

In una azienda che vende in tutta Italia, il riepilogo delle vendite in un determinato mese per area geografica è una distribuzione di intensità. L'unità statistica è la vendita, la variabile qualitativo è l'area di vendita (Nord, Centro, Sud, Isole) e quello quantitativo è l'importo della vendita. La distribuzione è la seguente.

$$
\textbf{VENDITE PER AREA} \\
\begin{array}{|l|c|}
\hline
\textbf{Area}	& \textbf{Vendite} \\
  & \textbf{(Ml di euro)}	\\
\hline
\text{Nord}	& 120	 \\
\hline
\text{Centro}	& 80	 \\
\hline
\text{Sud}	& 50	 \\
\hline
\text{Isole}	& 24	 \\
\hline
\textbf{Totale} & \mathbf{274} \\
\hline
\end{array}
$$

L'area che vende di più è il Nord, quella  he vende di meno è l'area commerciale delle Isole.  $\bullet$



### ESERCIZIO 2.1 - Frequenze assolute e relative

a) Per ognuno dei casi seguenti, calcola e riporta in una tabella le frequenze assolute e relative.

1. Statura degli studenti di una classe, espressa in centimetri: 160, 165, 165, 162, 163, 165, 168, 168, 166, 161, 162, 166, 168, 165, 165, 165, 163, 168, 162, 161, 163, 165, 165, 161, 168, 165, 163, 165.  
2. Pioggia caduta giornalmente nel mese di febbraio in una certa località, espressa in millimetri: 2, 3, 3, 4, 6, 8, 5, 5, 0, 0, 0, 1, 1, 4, 2, 5, 1, 0, 0, 0, 1, 2, 2, 0, 1, 0, 1, 2.  
3. Libri letti in un anno da 40 persone: completa i dati raccolti nella tabella seguente con le frequenze relative:

$$
\textbf{CARATTERE: Libri letti in un anno} \\
\begin{array}{|c|c|}
\hline
\textbf{Modalita} & \textbf{Frequenza} \\
\hline
[0 ,2] & 9 \\
\hline
[3, 5] & 21 \\
\hline
[6, 9] & 4 \\
\hline
[10, 12] & 6 \\
\hline
\end{array}
$$

b) In un'indagine statistica sulla conoscenza delle lingue straniere da parte degli italiani di età compresa tra 16 e 40 anni (campione di 1000 unità) vengono poste le seguenti domande:

- Quante lingue conosci?

- Come le hai imparate?

1. Completa le seguenti tabelle in cui sono riassunti i risultati dell'indagine.
2. Calcola la percentuale di persone che conoscono almeno due lingue straniere.

$$
\textbf{CARATTERE: Numero di Lingue Straniere Conosciute} \\
\begin{array}{|c|c|}
\hline
\textbf{Modalita} & \textbf{Freq. Ass.} & \textbf{Freq. Rel.} \\
\hline
0 & 253  \\
\hline
1 & 536  \\
\hline
2 & 180 & 18\% \\
\hline
3 & & 2,8\%  \\
\hline
4 & 3  \\
\hline
\end{array}
$$

$$
\textbf{CARATTERE: Metodo di Apprendimento} \\
\begin{array}{|l|c|}
\hline
\textbf{Modalita} & \textbf{Freq. Ass.} & \textbf{Freq. Rel.} \\
\hline
\text{A Scuola} & 400 & 53,54 \%  \\
\hline
\text{Con Corsi Specifici} &  &   \\
\hline
\text{Viaggi Studio} & 156 & 20,89 \%  \\
\hline
\text{All'Universita} &  & 0,4 \%  \\
\hline
\end{array}
$$

c) I dati riportati nella seguente tabella si riferiscono a un gruppo di 20 soggetti per ognuno dei quali è stata osservata:

- l’**età** (colonna ***Eta***, in anni);
- il **livello socio-economico** (colonna ***Liv.***, modalità 1=elevato, 2=medio, 3=basso);
- la **zona di residenza**, (colonna ***Res.*** con modalità 1=urbana, 2=periferica)
- lo **stato di salute** (colonna ***Salute*** con modalità 1=buono, 0=cattivo);
- il **reddito** (colonna ***Reddito***, in euro). 

$$
\begin{array}{|c|c|c|c|r|}
\hline
\textbf{Eta} & \textbf{Liv.} & \textbf{Res.} & \textbf{Salute} & \textbf{Reddito} \\
\hline
33 & 1 & 1 & 1 & 75.000    \\
\hline
35 & 1 & 1 & 1 & 120.000   \\
\hline                         
6 & 1 & 1 & 0 & 55.000     \\
\hline                         
60 & 1 & 1 & 0 & 66.000    \\
\hline                         
18 & 3 & 1 & 1 & 14.000    \\
\hline                         
26 & 3 & 1 & 0 & 12.000    \\
\hline                         
6 & 3 & 1 & 0 & 17.500     \\
\hline                         
31 & 2 & 1 & 1 & 33.000    \\
\hline                         
26 & 2 & 1 & 1 & 42.000    \\
\hline                         
37 & 2 & 1 & 0 & 47.000   \\
\hline                         
23 & 1 & 1 & 0 & 51.000   \\
\hline                         
23 & 1 & 1 & 0 & 60.500   \\
\hline                         
27 & 1 & 1 & 0 & 140.000  \\
\hline                         
9 & 1 & 1 & 1 & 83.000    \\
\hline                         
37 & 1 & 2 & 1 & 73.000   \\
\hline                         
22 & 1 & 2 & 1 & 68.000   \\
\hline                         
67 & 1 & 2 & 1 & 65.000   \\
\hline                         
8 & 1 & 2 & 0 & 55.000    \\
\hline                         
6 & 1 & 2 & 1 & 59.000    \\
\hline                         
15 & 1 & 2 & 1 & 61.000   \\
\hline
\end{array}
$$


1. Calcola le distribuzioni semplici di frequenza dei caratteri livello socio-economico, stato di salute e età, utilizzando per quest’ultimo carattere le classi $[0, 25]$, $[26, 50]$ e $[51, 76]$; 
2. Calcola le frequenze assolute e relative per determinare la distribuzione del livello socio-economico.

#### Laboratorio FOGLIO ELETTRONICO

Tutti i dati utili alle esercitazioni di laboratorio sono contenuti nel file in formato Excel scaricabile [qui](http://felixblog.github.io/edu/dev/Statistica Descrittiva/Frequenze.xlsx).

a) Risolvi il punto a.1) con la sequenza di operazioni sul FOGLIO ELETTRONICO riportati di seguito.

1. Scarica ed apri il file di dati;
2. Sul foglio "Stature", copiare l'intervallo A2:A29 sull'intervallo B2:B29 e su quest'ultimo rimuovere i duplicati, in modo che  valori compaiano una sola volta. 
3. Generare, a partire dalla cella C2 e trascinando verso il basso, i valori delle frequenze con la formula: =CONTA.SE(\$A\$2:\$A\$29;B2).
4. L'intervallo B2:C8 conterrà la tabella della distribuzione di frequenza (assoluta) desiderata. 

b) Risolvi il punto a.2) dell'esercizio con una sequenza di operazioni analoga al punto a).

c) Risolvi il punto a.1) dell'esercizio con lo strumento TABELLA PIVOT

d) Risolvi il punto c.1) dell'esercizio prendendo ad esempio la sequenza di operazioni del punto a) del laboratorio.



### ESERCIZIO 2.2 - Intensità Assolute e Relative

Considera i dati dell'ESEMPIO 1 relativi ad un questionario somministrato a 20 addetti di una azienda.


a) Considerato che in un mese ci sono 20 giorni lavorativi e che la giornata lavorativa è di 8 ore, calcola:

1. La retribuzione mensile (intensità) per ciascuna unità;

2. la distribuzione della retribuzione mensile per qualifica, in assoluto ed in percentuale sul totale.

b) Considera le classi di retribuzione (fasce) seguenti: $[0, 20]$; $[21, 25]$; $[26, 40]$; $[41, \infty]$, e calcola

1. le frequenze assolute e relative di tali classi;
2. la distribuzione della retribuzione mensile per fascia d'età.




## UNITA' 3: Moda, Media e Mediana

La reportistica manageriale spesso contiene frasi come:

- il salario medio per livello lavorativo;
- la spesa sanitaria della famiglia italiana;
- il consumo di latte di una famiglia di quattro persone;
- la metà degli impiegati spende meno di $178$ euro al mese per il pendolarismo lavorativo;
- l’età media dei nostri impiegati.

I termini come "salario medio", "spesa della famiglia italiana" ecc. si riferiscono ad un valore assunto come tipico dell’insieme dei dati che stiamo considerando, un valore rappresentativo di "tutto" l’insieme dei salari, dei consumi di latte, dell'età e così via.

Non essendo di interpretazione univoca, ci sono più modi di definire tale questo valore per uno stesso insieme di dati; tutti questi indicatori vengono chiamati **statistiche di posizione centrale**.

Le tre statistiche di posizione centrale più utilizzate sono:

a) la media aritmetica (la "media");

b) la moda.

c) la mediana;

Per le variabili quantitative possono essere calcolati tutti e tre gli indicatori: media, moda e mediana, mentre per le variabili qualitative può essere usata solo la moda.



### La Media

La **media** aritmetica di $n$ numeri $x_1, x_2, …, x_n$ è il rapporto tra la loro somma e il numero $n$.
$$
Media = \dfrac{x_1+x_2+...+x_n}{n}
$$
Se non si hanno a disposizione tutti i dati, ma solo la distribuzione della frequenza di una variabile quantitativa, la media è ottenuta moltiplicando la modalità per la frequenza, sommando e dividendo tutto per la numerosità della popolazione.

#### ESEMPIO 1

Riprendiamo l’esempio dei dipendenti di un ufficio che avevano le età riportate di seguito.

$$
\textbf{DIPENDENTI} \\
\begin{array}{|l|c|}
\hline
\textbf{Nominativo} & \textbf{Eta} \\
\hline
\text{Antonio Rossi} & 48 \\
\hline
\text{Francesca Verdi}    & 59  \\
\hline
\text{Franco  Gialli}  & 37  \\
\hline
\text{Luigi  Neri}        & 23  \\
\hline
\text{Giacomo  Bianchi}    & 24  \\
\hline
\text{Antonio  Bianchi}   & 37  \\
\hline
\text{Amedeo  Verdi}    & 61  \\
\hline
\end{array}
$$

L'età media dei dipendenti è 
$$
\dfrac{48+59+37+23+24+37+61}{7} = \dfrac{289}{7} \approx 41,3 \;\;\;\bullet
$$

#### ESEMPIO 2

Di seguito sono viene riportato il numero di notti trascorse in albergo da 90 clienti.

$$
\textbf{NOTTI IN ALBERGO} \\
\begin{array}{|c|c|}
\hline
\textbf{N. Notti}	& \textbf{N. Clienti}	\\
\hline
1 & 25	\\
\hline
2 & 21	\\
\hline
3 & 15	\\
\hline
4 & 12	\\
\hline
5 & 8	\\
\hline
6 & 6	\\
\hline
7 & 3	\\
\hline
\textbf{Totale} & \mathbf{90}	\\
\hline
\end{array}
$$

La media delle notti si ottiene con la formula seguente:
$$
Media = \dfrac{25 \cdot 1 + 21 \cdot 2 +15 \cdot 3 + 12 \cdot 4 +8 \cdot 5 +6 \cdot 6 +3 \cdot 7}{90} = \dfrac{257}{80} \approx 2,85 \;\;\;\bullet
$$


### La Moda

Dati i numeri $x_1, x_2,...,xn$, si chiama **moda** il valore a cui corrisponde la frequenza massima.

#### ESEMPIO 3

Nell'esempio precedente delle notti in albergo, la moda è $1$ con $25$ clienti.   $\bullet$



### La Mediana

Data la sequenza ordinata di $n$ numeri $x_1, x_2, … x_n$, la **mediana** è:

- il valore centrale, se $n$ è dispari;
- la media aritmetica dei due valori centrali, se $n$ è pari.

#### ESEMPIO 4

Per trovare la mediana tra i numeri $21, 35, 22, 26, 28$ bisogna eseguire i passi seguenti:

1. Ordinare i numeri: $21, 22, 26, 28, 35$;
2. Poiché i numeri sono 5 (dispari), la mediana è il numero centrale: $26$.

Se l'insieme fosse stato  $21, 35, 22, 26, 28, 24$:

1. Ordinare i numeri: $21, 22, 24, 26, 28, 35$;
2. Poiché i numeri sono pari, la mediana è la media dei due numeri centrali: $\dfrac{24 + 26}{2} = 25$



### ESERCIZIO 3.1 - Calcolo di Media, Moda e Mediana I

a) Calcola minimo, massimo e media delle vendite sui dati dell'esercizio 7.b).

b) Per i primi 15 giorni di un mese viene rilevato il ritardo (in minuti) accumulato da un determinato treno rispetto all’orario previsto di arrivo. Di seguito sono riportati i dati rilevati, che presentano segno negativo nel caso di anticipo sull’orario di arrivo:

$$
\begin{array}{|c|r|}
\hline
\textbf{Giorno} & \textbf{Ritardo} \\ 	 
\hline
1 & 10\phantom{--}   \\
2 & 15\phantom{--}   \\
3 & -2\phantom{--}   \\
4 & 0\phantom{--}    \\
5 & 50\phantom{--}   \\
6 & 20\phantom{--}   \\
7 & 0\phantom{--}    \\
8 & 9\phantom{--}    \\
9 & -5\phantom{--}   \\
10 & 8\phantom{--}   \\
11 & 10\phantom{--}  \\
12 & 20\phantom{--}  \\
13 & 6\phantom{--}   \\
14 & 10\phantom{--}  \\
15 & -10\phantom{--} \\
\hline
\end{array}
$$
Calcola minimo, massimo, la moda, la mediana, la media aritmetica della distribuzione;

c) Per otto famiglie viene rilevato il risparmio medio annuo (in euro) come segue: 

$$
\begin{array}{|c|c|}
\hline
\textbf{Famiglia} & \textbf{Risparmio} \\
\hline
\text{A} & 500    \\
\hline
\text{B} & 5.000  \\
\hline
\text{C} & 2.600  \\
\hline
\text{D} & 0      \\
\hline
\text{E} & 9.200  \\
\hline
\text{F} & 3.000  \\
\hline
\text{G} & 5.400  \\
\hline
\text{H} & 6.300  \\
\hline
\end{array}
$$
Determina moda, media e mediana.

d) Considera il grafico riportato di seguito (relativo al 2013, in cui erano presenti in Italia 5 milioni di immigrati).

![F](img\Ind-Italia.png)

1. Individua la popolazione, il carattere esaminato, la tipologia di tabella su cui il grafico si basa.
2. Se nel mondo sono presenti 218 nazionalità, quale è la percentuale che in media ha ogni altra nazionalità non rappresentata nel grafico?  



### ESERCIZIO 3.2 - Calcolo di Media, Moda e Mediana II

a) Le autovetture di un salone per la vendita di auto usate sono classificate secondo l’età dell’usato.

$$
\textbf{AUTO USATE} \\
\begin{array}{|c|c|}
\hline
\textbf{Eta Usato}	& \textbf{N. Auto}	\\
\textbf{(mesi)}	&  \\
\hline
6	& 12 \\
\hline
12	& 16 \\
\hline
18	& 15 \\
\hline
24	& 9  \\
\hline
30	& 5  \\
\hline
36	& 1  \\
\hline
48	& 1  \\
\hline
60	& 1  \\
\hline
\end{array}
$$

Determina la media, la mediana e la moda dell’età.

b) In un campionato una squadra di calcio ha giocato 36 partite, realizzando 52 punti. I goal segnati sono stati 58, quelli subiti 40. Calcola: 

1. la media dei punti a partita;
2. la media dei goal segnati per partita e quella dei goal subiti. 

