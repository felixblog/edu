# Le Funzioni Goniometriche

## UNITA' 1: Angoli e loro misura

Gli angoli sono un concetto molto importante in geometria, in matematica in generale, in fisica ed in tante altre discipline. Quella parte della matematica che si occupa della misura degli angoli e delle relative funzioni si chiama Goniometria. Per cominciare vediamo la definizione di Angolo.

Un angolo è la parte di piano individuata da due semirette a e b (dette lati) che hanno origine comune V (detto vertice).

<img src="img/angoli.bmp" alt="angoli" style="zoom:50%;" />

Le unità di misura più usate sono il grado (sessagesimale) ed il radiante.



#### La misura in gradi

Nel sistema sessagesimale, l’unità di misura degli angoli è il grado sessagesimale,
definito come quell'angolo pari alla 360-esima parte dell’angolo giro.
Il grado sessagesimale viene indicato con un piccolo cerchio in alto a destra 
della misura:
$$
1^\circ = \dfrac{1}{360} \cdot \text{Angolo Giro}
$$
Il grado viene suddiviso a sua volta in $60$ primi, che 
vengono indicati con un apice: $1^\circ = 60'$.
Ogni primo viene suddiviso a sua volta in 60 secondi, indicati con due apici: $1' = 60''$.

Dalla formula precedente risulta quindi che un angolo giro, in gradi, misura $360$.



#### La misura in radianti

Gli angoli, oltre ad essere misurati in gradi, vengono misurati anche in radianti, cioè utilizzando un'altra unità di misura. Il radiante è l’angolo al centro di una circonferenza che sottende un arco di lunghezza uguale al raggio.

<img src="img/Radiante.png" alt="Radiante" style="zoom:67%;" />

L'angolo sotteso da un arco lungo un raggio misura quindi un radiante. Quello sotteso da un arco lungo due raggi, due radianti, e quello sotteso da un arco lungo $2\pi$ raggi, $2\pi$ radianti. Ma un arco di $2\pi$ raggi è tutta la circonferenza, e l'angolo è l'angolo giro, per cui l'angolo giro, in radianti, misura $2\pi$, cioè 
$$
\text{Angolo Giro} = 2\pi\; \text{rad}
$$
Confrontando con la formula dei gradi abbiamo l'equivalenza di conversione tra gradi e radianti, cioè
$$
360 \cdot 1^\circ = 2\pi\; \text{rad}
$$



#### Proporzionalità tra archi ed angoli

In una circonferenza la lunghezza $s$ di un arco e l'angolo $\omega$ sotteso sono due grandezze direttamente proporzionali, ossia il loro rapporto è costante. La costante di proporzionalità è uguale al rapporto tra tutta la circonferenza e l'angolo giro, quindi, misurando gli angoli in radianti:
$$
\dfrac{s}{\omega_{rad}} = \dfrac{2{\pi}r}{2\pi}
$$
 Semplificando abbiamo che
$$
s = {\omega_{rad}} \cdot r
$$



#### Gli angoli orientati

La definizione di angolo come parte di piano, che è stata già data, non è adatta per descrivere tutte le 
situazioni. Per esempio, nell’avvitare o svitare una vite si descrive un angolo che 
può essere maggiore di un angolo giro.
È più utile quindi collegare il concetto di angolo a quello di **rotazione**, cioè al 
movimento che porta uno dei lati dell’angolo a sovrapporsi all’altro.
La rotazione è univoca solo quando ne viene specificato il verso, orario o antiorario. Nella figura a lato il senso adottato è quello antiorario.

Un angolo si dice **orientato** quando si è scelto uno dei due lati come lato di origine e un senso di rotazione. 
Un angolo orientato sarà **positivo **
quando è descritto mediante una 
rotazione in senso antiorario, **negativo** quando la rotazione 
è in senso orario.

![Angoli-Orientati](img/Angoli-Orientati.png)

Un angolo orientato può anche essere maggiore di un angolo giro: poiché $750^\circ = 30^\circ + 2 \cdot 360^\circ$, l’angolo di $750^\circ$ si ottiene con la rotazione della 
semiretta $OA$ di due giri completi e di ulteriori $30^\circ$.

![Angolo-750](img/Angolo-750.png)

È possibile scrivere in forma sintetica un qualunque angolo $\alpha$, minore di un angolo giro, e tutti gli infiniti angoli orientati che da $\alpha$ differiscono di un multiplo dell’angolo giro nel seguente modo:
in gradi: $a + k \cdot 360^\circ$, con $k \in \mathbb{Z}$; in radianti: $a + 2k\pi$, con $k \in \mathbb{Z}$. 
Quando $k = 0$, otteniamo l’angolo $\alpha$.

Ad esempio, la scrittura $\dfrac{\pi}{4} + 2k\pi, \;\; k \in \mathbb{Z}$ equivale alla successione di angoli
$$
\dfrac{\pi}{4}, \; \dfrac{\pi}{4} + 2\pi, \; \dfrac{\pi}{4} - 2\pi, \; \dfrac{\pi}{4} + 4\pi, \; \dfrac{\pi}{4} - 4\pi, \; ...
$$


#### La circonferenza goniometrica

Per **circonferenza goniometrica** intendiamo la circonferenza che in un piano cartesiano ha come centro l’origine $O$ degli assi ed il raggio di lunghezza $1$, ossia la 
circonferenza di equazione $x^2 + y^2 = 1$.

![Circonferenza-goniometrica](img/Circonferenza-goniometrica.png)

Utilizzando la circonferenza goniometrica, si possono rappresentare gli angoli 
orientati, prendendo come lato origine l’asse orizzontale delle $x$. In questo modo, ad ogni angolo corrisponde un punto di intersezione $B$ fra la circonferenza e il lato termine.

Ad esempio, gli angoli $\alpha_1 = \dfrac{\pi}{6}$, $\alpha_2 = \dfrac{5}{6}\pi$, $\alpha_3 = -\dfrac{\pi}{3}$ individuano sulla circonferenza i punti $B1$, $B2$ e $B3$.

![B123](img/B123.png)



### ESERCIZIO 1.1 - Misure di angoli in gradi

a) Esprimi in gradi e decimali di grado (forma sessadecimale) le seguenti misure di angoli.

1. $0^\circ \; 59^{'} \; 59^{''}$
2. $1^\circ \; 59^{'} \; 30^{''}$
3. $2^\circ \; 40^{''}$
4. $60^\circ \; 20^{'}$
5. $92^\circ \; 20^{'} \; 36^{''}$

b) Esprimi in gradi, primi e secondi le seguenti misure di angoli, espresse in forma sessadecimale (arrotondando 
eventualmente i secondi).



### ESERCIZIO 1.2 - Gradi e radianti

a) Trasforma in radianti le misure dei seguenti angoli, espresse in gradi sessagesimali.

1. $15^\circ$, $36^\circ$, $210^\circ$, $300^\circ$; 
2. $121^\circ \; 3^{''}$, $200^\circ \; 36^{''}$. 

b) Trasforma in gradi sessagesimali le misure dei seguenti angoli, espresse in radianti.

1. $\dfrac{2}{3}$, $\dfrac{2}{3}\pi$, $\dfrac{9}{5}\pi$, $\dfrac{3}{2}\pi$;
2. $4\pi$, $4$, $\dfrac{5}{2}$, $\dfrac{5}{2}\pi$.



#### ESERCIZIO 1.3 - Problemi vari

a)  Calcola la misura, in gradi e in radianti, di un angolo al centro di una circonferenza il cui raggio è uguale a 
$5$ cm e che sottende un arco lungo $23$ cm.

b) Disegna sul cerchio goniometrico i seguenti angoli, misurati in radianti: $\dfrac{\pi}{4}$,  $\dfrac{3}{4}\pi$,  $\dfrac{11}{4}\pi$, $\dfrac{\pi}{8}$.



## Unità 2: Le funzioni seno e coseno

Consideriamo la circonferenza goniometrica, un angolo orientato $\alpha$ ed il punto della circonferenza associato ad $\alpha$ che chiamiamo $B$. Definiamo coseno e seno dell’angolo $\alpha$, e le indichiamo con $\sin \alpha$ e $\cos \alpha$, le funzioni che associano ad $\alpha$ rispettivamente, il valore dell’ascissa $x_B$
e quello dell’ordinata $y_B$ del punto $B$, ossia
$$
B=(x_B, y_B) \;\;\; \text{e} \;\;\; \sin \alpha = x_b, \;\; \cos \alpha = y_B
$$
![sin-cos](img/sin-cos.png)

Seno e coseno di un angolo $\alpha$ sono funzioni che hanno come dominio $\mathbb{R}$, perché per ogni valore di $\alpha \in \mathbb{Z}$ esiste uno e un solo punto sulla circonferenza.



#### Variazioni delle funzioni seno e coseno

Supponiamo che un punto B percorra l’intera circonferenza goniometrica, a par-
tire da E, in verso antiorario. 
Se a = EOWB, come variano sen a e cos a al variare della posizione di B? Basta 
osservare che cosa succede all’ascissa di B (ossia il coseno) e alla sua ordinata 
(ossia il seno).

![Variazioni-seno-coseno](img/Variazioni-seno-coseno.png)

Qualunque sia la posizione di $B$ sulla circonferenza, la sua ordinata e la sua ascissa 
assumono sempre valori compresi fra $-1$ e $1$, quindi:
$-1 \le \sin \alpha \le 1$ e $-1 \le \cos \alpha \le 1$.
Il codominio delle funzioni seno e coseno è quindi $[-1; 1]$.



<img src="img/sinusoide.png" alt="sinusoide" style="zoom:30%;" />



#### I grafici delle funzioni seno e coseno



![Grafico-seno](img/Grafico-seno.png)



![Grafico-coseno](img/Grafico-coseno.png)



#### Il periodo delle funzioni seno e coseno

Dopo aver percorso un giro completo, il punto $B$ sulla circonferenza goniometrica può ripetere lo stesso movimento altre volte e le funzioni seno e coseno assumono di nuovo gli stessi valori ottenuti al "primo 
giro":

$\sin \alpha = \sin (\alpha + 2\pi) = \sin (\alpha - 2\pi) = \sin (\alpha + 4\pi) = \sin (\alpha - 4\pi)  \; ...$  

$\cos \alpha = \cos (\alpha + 2\pi) = \cos (\alpha - 2\pi) = \cos (\alpha + 4\pi) = \cos (\alpha - 4\pi)  \; ...$ 

Le funzioni seno e coseno sono quindi periodiche di periodo $2\pi$. In modo sintetico si può scrivere:
$$
\sin (\alpha + 2k\pi) =\sin \alpha, \;\; k \in \mathbb{Z} \\

\cos (\alpha + 2k\pi) =\cos \alpha, \;\; k \in \mathbb{Z}
$$


#### La relazione fondamentale della goniometria

Poiché il punto $B(\cos \alpha; \sin \alpha)$ appartiene alla circonferenza goniometrica, le sue 
coordinate soddisfano l’equazione $x^2 + y^2 = 1,$ che è conseguenza diretta dell'applicazione del teorema di pitagora al triangolo rettangolo $\widehat{AOB}$:

![Pitagora-seno-coseno](img/Pitagora-seno-coseno.png)

Da questa relazione è possibile ricavare $\sin \alpha$ conoscendo $\cos \alpha$ e viceversa. 
Infatti, se è noto $\cos \alpha$, si ha: 

$\sin \alpha = \pm \sqrt{1 - \cos^2 \alpha}$ . 
Viceversa, se si conosce $\sin \alpha$, si ha: $\cos \alpha = \pm  \sqrt{1 - \sin^2 \alpha}$ .



#### ESERCIZIO 2.1 - Calcolo delle funzioni seno e coseno

a) Individua sulla circonferenza goniometrica i seguenti valori.

1. $\cos\left(-\dfrac{\pi}{3}\right)$, $\sin\dfrac{5}{8}\pi$, $\sin(-240^\circ)$, $\cos\dfrac{7}{4}\pi$;
2. $\sin300^\circ$, $\cos 330^\circ$.

b)  Trova quale condizione deve soddisfare il parametro affinché sia verificata l’uguaglianza.

1. $\cos x = k-2$;
2. $4a \cos x = a + 1$;
3. $(k-1)\sin x = k$.

c) Calcola il valore della funzione indicata, utilizzando le informazioni fornite.

1. Calcolo di $\cos \alpha$ se $\sin \alpha = \dfrac{7}{25}$ e $0 \lt \alpha \lt \dfrac{\pi}{2}$;
2. Calcolo di $\sin \alpha$ se $\cos \alpha = -\dfrac{4}{5}$ e $\dfrac{\pi}{2} \lt \alpha \lt \pi$;



#### ESERCIZIO 2.2 - Calcolo di espressioni goniometriche

a) Calcola il valore delle seguenti espressioni.

1. $\dfrac{1}{2} \cos 540^\circ + \dfrac{2}{3} \sin 720^\circ -\dfrac{1}{4} \sin 450^\circ + 6\sin (-270^\circ)  $;
2. $\cos 4\pi + 2\sin\left(-\dfrac{15}{2}\pi \right) + \dfrac{1}{3}\cos(-3\pi) + \sin\dfrac{9}{2}\pi  $.

b) Se $\alpha= \dfrac{\pi}{2}$ calcola il valore della seguente espressione:
$$
\dfrac{a \sin\alpha + b \cos\alpha}{\sin(-4\alpha) - a\cos\left(\alpha + \dfrac{\pi}{2}\right) - b\cos\left(\dfrac{7}{2}\pi + \alpha \right)} 
$$

#### ESERCIZIO 2.3 - Grafico delle funzioni goniometriche

Es. 116



ESERCIZIO 2.4 - Semplificazione di espressioni

Es. 124 e 125



## Unità 3: La funzione Tangente

Consideriamo un angolo orientato $\alpha$ sulla circonferenza goniometrica, come in figura. Chiamiamo come al solito $B$ l’intersezione fra il lato termine e la circonferenza di centro $O$. Si definisce tangente di $\alpha$ la funzione che associa al $\alpha$ il rapporto, quando esiste, fra l’ordinata e l’ascissa del punto $B$.
$$
\tan \alpha = \dfrac{y_B}{x_B}
$$
![Tangente](img/Tangente.png)

Il rapporto  non esiste quando $x_B = 0$ ossia per $\alpha = \dfrac{\pi}{2} + k\pi, \;\; k \in \mathbb{Z}$. Il dominio della funzione tangente è quindi $\{\alpha \in \mathbb{R}: \alpha \ne \dfrac{\pi}{2} + k\pi, \;\; k \in \mathbb{Z} \}$.



#### Un altro modo di definire la tangente

Consideriamo la circonferenza goniometrica e la retta tangente a essa nel punto
$E$, origine degli archi.
Il prolungamento del lato termine $OB$ interseca la retta tangente nel punto $T$, come riportato in figura.
La tangente dell’angolo $\alpha$ può anche essere definita come il valore dell’ordinata 
del punto $T$, ossia:
$\tan \alpha = y_T$.

![Tangente2](img/Tangente2.png)

L'equivalenza della definizione deriva dal fatto che i triangoli $TOE$ e $BOA$ sono simili e quindi $\dfrac{BA}{OA} = \dfrac{TE}{OE}$, ma $OE = 1$ perché il cerchio è goniometrico ed ha raggio $1$.



#### Il grafico della funzione tangente

![Grafico-tangente](img/Grafico-tangente.png)

Analogamente a quanto fatto per le funzioni seno e coseno, tracciamo il grafico della funzione $y = tan\; x$ nell’intervallo $[0; \pi]$, riportando 
sull’asse $x$ i valori degli angoli e sull’asse $y$ le ordinate dei punti corrispondenti 
sulla retta tangente alla circonferenza goniometrica.

Il valore $\dfrac{\pi}{2}$ è critico perché se la $x$ vi si avvicina da sinistra (restando minore) il valore della $y$ tende a diventare sempre più grande ossia tende a $+\infty$, se si avvicina da destra (restando maggiore), il valore della funzione tende a $-\infty$.

La retta $x = \dfrac{\pi}{2}$ è quindi un asintoto verticale e la funzione ha periodo $\pi$, cioè, qualunque sia l'angolo $\alpha$:
$$
\tan \alpha = tan(\alpha + k\pi), \;\;  k \in \mathbb{Z}
$$
![Grafico-Tangente2](img/Grafico-Tangente2.png)
