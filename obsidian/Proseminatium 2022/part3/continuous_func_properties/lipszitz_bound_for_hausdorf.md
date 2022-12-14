Lemat 3.1.3
Niech $f: \mathbb{R}^m \rightarrow \mathbb{R}^n$ jest funkcją Lipszitzowską o stałej $C$, oraz $A \subset \mathbb{R}^m$ i $p \in [0, + \infty)$ . Wtedy $$
	\mathcal{H}^p(f(A)) \leq (Lip(f))^p \mathcal{H}^p(A)
$$
Dowód:
Dla $p=0$ ta nierówność jest oczywista. Niech $p>0$. Jeśli $Lip(f) = 0$ to $f$ jest stała, a więc obraz tej funkcji jest miary zero. Niech teraz $Lip(f)>0$. Jeśli $\mathcal{H}^p(A) = +\infty$ to ta nierówność znowu jest oczywista. Pozostaje przypadek gdy $\mathcal{H}^p(A) < +\infty$ w którym korzystamy z nierówności $$
	diam(f(Z)) \leq Lip(f)(diam(Z))
$$
dla $Z \subset \mathbb{R}^m$ 