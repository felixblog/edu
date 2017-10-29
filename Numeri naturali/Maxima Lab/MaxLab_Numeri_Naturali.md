
# Laboratorio Maxima Numeri Naturali

### LAB 1 - Sequenze di Multipli

Scrivi le istruzioni per generare la lista dei primi 20 multipli di:    

a) $6; 3, 5, 10$  

[Verifica con Maxima. Inserisci le espressioni e calcola il risultato] 


### ESERCIZIO 2 - Operazioni ed Espressioni (II)

Date le espressioni di seguito riportate:    

i. Individua le operazioni coinvolte ed il loro ordine di esecuzione;  
ii. Calcola il risultato.  

a) $4 + 6·9$;  
b) $(4 + 6)·9$;  
c) $15 + 20 : 4 − 2$;  
d) $15 + 20 : (4 − 2)$;  

### ESERCIZIO 3 - Divisori e multipli

a) Scrivi tutti i divisori di ciascuno dei numeri 6, 15, 18, 21, 24, 25.  
b) Scrivi i multipli minori di 100 dei numeri 25, 40, 33, 6.  
c) Scrivi i multipli minori di 100 comuni ai numeri 6 e 8, 10 e 12, 15 e 16.   

### ESERCIZIO 4 - Dalle parole ai numeri (I)

Scrivi le espressioni relative alle seguenti frasi e calcolane il risultato:  

a) Dividere 15 per la differenza tra 9 e 4 e poi sommare 2;  
b) Moltiplicare per 7 la differenza tra 10 e 8 e sottrarre al risultato 14.  
c) Sottrarre 3 al risultato della divisione di 12 per la differenza tra 5 e 1.

### ESERCIZIO 5 - Dai numeri alle parole

Scrivi a parole le seguenti espressioni:  

a) $12 − 6 : 3$;  
b) $(15 − 10) · 3 + 2$;  
c) $8·(12 : 6 − 2) + 1$;   
d) $6 − (15 : (2 + 3))$;  
e) $15 − (17 − (15 + 1) : 8)$.

### ESERCIZIO 6 - Dalle parole ai numeri (II)

Scrivi le espressioni che forniscono le soluzioni dei seguenti problemi e calcolane i valori.  

a) Anna riceve dalla madre 8 euro e va ad acquistare 2 scatole di colori del costo di 3 euro l'una. Al ritorno si ferma dalla nonna che le regala 5 euro. Con quanto denaro arriva a casa Anna? [R. 7 euro]  
b) Una cuoca possiede 4 sacchetti di farina del peso di 1 kg ciascuno. Deve fare 7 dolci: nei primi 3 occorrono 350 g di farina per ciascuno e negli altri, 600 g di farina per ciascuno. Alla fine quanta farina rimane alla cuoca? [R. 550 g]  
c) In uno stabilimento tessile, in una settimana (6 giorni lavorativi), si producono 26.304 m di tela. La tela viene suddivisa in pezze da 32 m ciascuna. Quanti giorni lavorativi occorrono per fabbricare 1233 pezze? [R. 9].

### ESERCIZIO 7 - Operazioni ed espressioni (III)

Calcola il valore delle seguenti espressioni eseguendo, in ciascun passaggio, solo operazioni indipendenti tra di loro.  

a) $((2·4 + 7) + (2 + 8 : 2)·5) − (6 + 2)·5 \enspace\enspace\enspace[R. 5]$    
b) $4 + 3·(15 : (3 + 1·2) − 1) \enspace\enspace\enspace[R. 10]$    
c) $((4 + 3^{2} − 1) : 2^{2} + 45 : 3^{2} ) : 2^{2} + (21·3) : 9 + 1^{2} \enspace\enspace\enspace[R. 10]$      
d) $(((3^{2} + 11) : 2^{2} )^{2} : 5 − 1)) · 2^{3} − ((7 : (2·3 + 1) + 2^{2} + 10^{0} ) \enspace\enspace\enspace[R. 16]$

[Verifica con Maxima. Inserisci le espressioni e calcola il risultato] 

### ESERCIZIO 8 - Sostituzioni
Negli esercizi seguenti, calcola (quando esiste) il valore delle espressioni per i valori delle lettere
scritti di fianco.  
a) $5x, \enspace x = 50$  
b) $2y, \enspace y = 32$  
c) $a − b, \enspace a = 10, b = 7$  
d) $a^{2} − b^{2}, \enspace a = 1, b = 1; \enspace a = 3, b = 2; \enspace a = 6, b = 5$  
e) $ab, \enspace a = 5, b = 2$  
f ) $(2a)b, \enspace a = 2, b = 3$
[Verifica con Maxima. simp: false; c1: a - b, a=10, b=7; c1, simp] 

### ESERCIZIO 9 - Dalle espressioni ai diagrammi ad albero
Rappresenta con diagrammi ad albero le seguenti espressioni:  

a) $4 + 6·9$  
b) $(4 + 6)·9$  
c) $15 + 20 : 4 − 2$  
d) $15 + 20 : (4 − 2)$

### ESERCIZIO 10 - Dai diagrammi ad albero alle espressioni
Scrivi le espressioni corrispondenti ai seguenti diagrammi ad albero:  

<center> a)![Albero](img/Albero1.png)    b) ![Albero](img/Albero2.png)    c) ![Albero](img/Albero3.png)  </center>

### ESERCIZIO 11 - m.c.m e M.C.D.

a) Scomponi in fattori primi i numeri 25, 40, 33, 6.  
b) Trova il Minimo Comune Multiplo ed il Massimo Comune Divisore delle coppie (6, 15), (18, 20), (24, 25).  
[Verifica con Maxima. load("functs"); factor(40); gcd(6,15); lcm(6,15)] 

### ESERCIZIO 12 - Proprietà delle potenze

a) Applica, quando è possibile, le proprietà delle potenze e indica la proprietà applicata.  

1. $2^{4} · 2^{2}·2; \enspace (3^{4})^{2} · 3^{7}; \enspace  2^{3} · 5^{3}; \enspace 2^{4} · 3^{4};$   
2. $(7^{2} · 2^{2}) · 7^{2}; \enspace (4^{3})^{2} · 2^{6}; \enspace 6^{5} · 2^{5}; \enspace  (4^{5})^{2};$  

[Verifica con Maxima. simp: false; e1: (4^3)^2 · 2^6; factor(e1)] 

b) Quali delle uguaglianze seguenti sono vere? Quali false?  

1. $6^{2} · 6^{4}=6^{8}; \enspace$  
2. $5^{3} + 5^{4} = 5^{7};$
3. $(10^{2})^{3} = 1.000.000;$  

c) Applicando le proprietà delle potenze, calcola il valore delle seguenti espressioni.  

1. $2^{5}:2^{4} + 2·2^{2} - 2^{0}$;  
2. $(3^{4} · 3^{3})^{4} · 3^{5} · (3^{2} )^{4}$;  
3. $2^{6} · 3^{6} · (18^{4} · 3^{4});$  