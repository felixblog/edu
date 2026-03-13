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

Qualunque sia la posizione di B sulla circonferenza, la sua ordinata e la sua ascissa 
assumono sempre valori compresi fra -1 e 1, quindi:
-1 # sen a # 1 e -1 # cos a # 1.
Il codominio delle funzioni seno e coseno è quindi [-1; 1].



<img src="img/sinusoide.png" alt="sinusoide" style="zoom:30%;" />



#### I grafici delle funzioni seno e coseno





#### Il periodo delle funzioni seno e coseno



#### La relazione fondamentale della trigonometria











