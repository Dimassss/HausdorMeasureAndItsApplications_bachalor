Twierdzenie 1.3.3
Niech $A \subset \mathbb{R}^m$, $m \geq 1$. Wtedy następujące warunki są równoważne:
	1. $A \in L_m$
	2. $\forall \epsilon > 0 \exists G \in top(\mathbb{R}^m): A \subset G \wedge \mathcal{L}^m(G \backslash A) < \epsilon$
	3. $A = B \backslash C$, gdzie $B$ typu $G_{\delta}$, $\mathcal{L}^m(C) = 0$ 
	4. $\forall \epsilon \exists F \in cotop(\mathbb{R}^m): F \subset A \wedge \mathcal{L}^m(A \backslash F) = 0$  
	5. $A = B \cup C$, gdzie $B$ typu $F_{\sigma}$ i  $\mathcal{L}^m(C) = 0$ 
	6. $A = B \cup C$, gdzie $B$ jest $\sigma$-zwarty i $\mathcal{L}^m(C) = 0$ 

Dowód:
 1. $\Longrightarrow$ 2. $\mathcal{L}^m$ jest $\sigma$-skończona więc $A = \bigcup_{i \in \mathbb{N}} A_i$, $A_i \in L_m$ dla $i \in \mathbb{N}$, $\mathcal{L}^m(A_i) < \infty$ dla $i \in \mathbb{N}$. Możemy dobrać zbiory otwarte $G_i$, $i \in \mathbb{N}$, takie że $$ \mathcal{L}^m(G_i) \leq \mathcal{A_i} + \epsilon / 2^{2 + i}, \quad i \in \mathbb{N} $$  Niech $G = \bigcup_{i \in \mathbb{N}} G_i$ $$ G \backslash A = (\bigcup_{i \in \mathbb{N}} G_i) \backslash (\bigcup_{i \in \mathbb{N}} A_i) \subset (\bigcup_{i \in \mathbb{N}} G_i \backslash A_i) $$ Zatem $$ \mathcal{L}^m(G \backslash A) \leq \sum_{i \in \mathbb{N}} \mathcal{L}^m(G_i \backslash A_i) \leq \epsilon/2 $$
 2. $\Longrightarrow$ 3. $n \in \mathbb{N}$, $G_n \supset A$, $\mathcal{L}^m(G_n \backslash A) < 2^{-n}$. Dalej wystarczy przyjąć $B = \bigcap_{n \in \mathbb{N}} G_n$, $C = B \backslash A$ 
 3. $\Longrightarrow$ 1. $B, C \in L_m \Longrightarrow A = B \backslash C \in L_m$ 
 4. $\Longrightarrow$ 5. $F_n \subset A, \mathcal{L}^m(A \backslash F_n) < 2^{-n}, n \in \mathbb{N}$. Niech $B = \bigcup_{n \in \mathbb{N}} F_n \subset A$ oraz $C = A \backslash B \subset A \backslash F_n$ dla $n \in \mathbb{N}$. Zatem $A = B \cup C$, $\mathcal{L}^m(C)=0$  
 5. $\Longrightarrow$ 6. Każdy zbiór domknięty jest $\sigma$-zwarty wieć $B$ jest $\sigma$-zwarty 
 6. $\Longrightarrow$ 1. $B,C \in L_m \Longrightarrow B \cup C \in L_m$
 1. $\Longrightarrow$ 4. $A \in L_m$ więc $A^C \in L_m, \epsilon > 0$. Istnieje $A^C \subset G \in top(\mathbb{R}^m)$ taki, że $\mathcal{L}^m(G \backslash A^C) < \epsilon$. $$ G \backslash A^C = G \cap A = A \cap (G^C)^C = A \backslash G^C $$ Kładąc $F = G^C$ mamy $F \subset A$ i $\mathcal{L}^m(A \backslash F) < \epsilon$ 