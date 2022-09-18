Twierdzenie 1.3.2
Niech $m \in \mathbb{N} \backslash \{0\}$. Wtedy:
1. $\mathcal{L}^m$ jest miarą zewnętrzną metrzyczną w $\mathbb{R}^m$
2. $\mathcal{B}(\mathbb{R}^m) \subset L_m$
3. $\mathcal{L}^m$ na $L_m$ jest miarą zupełną 
4. Jeśli $I$ kostka, to $\mathcal{L}^m(I) = vol(I)$
5. Jeśli $Y$ ograniczony, to $\mathcal{L}^m(Y) < \infty$
6. $\mathcal{L}^m$ jest $\sigma$-skończona
7. $\forall Y \subset \mathbb{R}^m \exists G \subset \mathbb{R}^m: G$ - typu $G_{\delta} \wedge Y \subset G \wedge \mathcal{L}^m(G) = \mathcal{L}^m(Y)$ 
8. $\mathcal{L}^m$ jest miarą zewnętrzną regularną 
9. $(Y \subset \mathbb{R}^m \wedge a \in \mathbb{R}^m) \Longrightarrow (\mathcal{L}^m(a + Y) = \mathcal{L}^m(Y))$ 
10. $(Y \subset \mathbb{R}^m, s \in [0, +\infty)) \Longrightarrow (\mathcal{L}^m(sY) = s^m\mathcal{L}^m(Y))$

Dowód:
1., 2. 3. oraz 4. są oczywiste 
5. Istnieje $N \in \mathbb{N}, Y \subset [-N, N]^m$ więc $\mathcal{L}^m(Y) \leq (2N)^m$
6. $A \in L_m$ ; $A = \bigcup_{n \in \mathbb{N}} A \cup [-n,n]$ i każdy zbiór w tej sumie ma miarę skończoną
7. Jeśli $Y \subset \mathbb{R}^m$ i $\mathcal{L}^m(Y) = +\infty$ to bierzemy $G = \mathbb{R}^m$. Niech teraz $\mathcal{L}^m(Y) < \infty$. Dobieramy ciąg pokryć Y kostkami $\{I_i^{(n)}\}_{n \in \mathbb{N}}$ taki, że $Y \subset \bigcup_{i \in \mathbb{N}} I_i^{(n)}, n \in \mathbb{N}$ tak aby $$ \sum_{i \in \mathbb{N}} vol(I_i^{(n)}) \leq \mathcal{L}^m(Y) + 2^{-n} $$ Określając $G_n' := \bigcup_{i \in \mathbb{N}} I^{(n)}_i \supset Y, n \in \mathbb{N}$ mamy $\mathcal{L}^m(Y) \leq \mathcal{L}^m(G_n') \leq \mathcal{L}^m(Y) + 2^{-n}, n \in \mathbb{N}$ . Biorąc $G_j := \bigcap_{n = 0}^j G_n'$ dla $j \in \mathbb{N}$. Dostajemy $\mathcal{L}^m(Y) \leq \mathcal{L}^m(G_n') \leq \mathcal{L}^m(Y) + 2^{-n}$ . Ciąg $\{G_n\}_{n \in \mathbb{N}}$ jest stępujący i jego zbiory mają miary skończone więc dla $G = \bigcap_{n \in \mathbb{N}} G_n$ mamy $Y \subset G$ i $\mathcal{L}^m(G) = \mathcal{Y}^m$
8. Zbiory typu $G_{\delta}$ są mierzalne, więc regularność wynika z 7.
9. Translację nie zmieniją objętości kostek więc równierz objętości zbiorów
10. Jeśli $s>0$ to równość dostajemy obserwując, że dla kostek zwartych $vol(sI) = s^m vol(I)$ . Dla $s=0$ jest oczywiste, bo $m \leq 1$ oraz $sI = \{0\}$ ma miarę zero.  