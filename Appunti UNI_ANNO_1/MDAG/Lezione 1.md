
**MONOMIO**: Un monomio, definito su un campo di numeri $\mathbb{K}$ rispetto a variabili $x,y$ , e' un'espressione $a * x^n * y^m$ dove $a \in \mathbb{K} , m,n \in \mathbb{N}$ , per esempio $x^2 y^3$ oppure $\sqrt{5}x$ oppure $-5$ .
Il grado del monomio e' dato dalla somma degli esponenti: $deg(ax^ny^m) = n+m$ 

**POLINOMIO**: Un polinomio, definito su un campo di numeri $\mathbb{K}$ e' dato dalla somma di tutti i monomi ed il suo grado e' definito dal massimo tra i gradi dei monomi che lo compongono, per esempio: $\sqrt{3}x^5 + 2x^6 y^2 + 3$ avra' il grado massimo di 6. 

**OPERAZIONI TRA POLINOMI**: Nei polinomi, come in $\mathbb{Z}$ possiamo effettuare la somma, la sottrazione, la moltiplicazione ma non la divisione, poiche' dividere un polinomio non sempre ci dara' un valore intero, ma ci lascera' sempre del resto, per esempio:
![[Pasted image 20240930191647.png]]

**RADICI (O SOLUZIONI) DI UN POLINOMIO**: $a \in \mathbb{K}$ e' una soluzione di $P(x) \in \mathbb{K}$ se $P(a) = 0$. $a \in \mathbb{K}$ e' una soluzione di $P(x) \in \mathbb{K} \iff \frac{(x-a)} {P(x)}$ . Per esempio: $P(x) = x + 1 \to P(-1) = -1 + 1 = 0$ 
oppure:
$P(x) = x^2 + 1 \to P(\sqrt-1) = (\sqrt-1)^2 + 1 = 0 \to P(-\sqrt-1) = (-\sqrt-1)^2 + 1 = 0$ 

**MOLTEPLICITA' DI $Q(x)$**: La Molteplicita' di $Q(x)$ come divisore di $P(x)$ = potenza $k | P(x) = Q(x)^k  * P(x)$ . Per esempio, calcoliamo la molteplicita' di $x-2$ come divisore di $2x^2 - 8x + 8$: $2x^2 - 8x + 8 = (x-2)(2x-4) \to 2x-4 = (x-2)*2 \to 2x^2 - 8x + 8 = (x-2)^2 *2 \to Molt. = 2$ 

Inoltre, sia $a \in C$ una soluzione di $P(x)$ allora la molteplicita' di $a$ e' quel $k$ in $\mathbb{N} | P(x) = (x-a)^k * Q(x)$, con $Q(a) \ne 0$ . 

Le soluzioni di un polinomio di secondo grado, si possono trovare graficamente, ove la funzione interseca l'asse delle x, per esempio: 
![[Pasted image 20240930194318.png]]
Oppure: 
![[Pasted image 20240930194512.png]]
Ed infine:
![[Pasted image 20240930194634.png]]

**TEOREMA FONDAMENTALE**: Ogni polinomio di grado $n$ in $\mathbb{C}[x]$ ha $n$ soluzioni contate con molteplicita'. 