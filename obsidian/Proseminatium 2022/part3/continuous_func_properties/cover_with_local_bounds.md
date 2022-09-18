Lemat 3.1.2
Niech $\Omega \in top(\mathbb{R}^n)$, $f: \Omega \rightarrow \mathbb{}R^m$  będzie funckją klasy $C^1$, $1 \leq n \leq m$ oraz $f'(x)$ będize monomorfizmem dla $x \in \Omega$, $\lambda > 1$. Wtedy istnieje ciąg par $\{(B_v, T_v)\}_{v \in \mathbb{N}}$ takich, że $B_v \in \mathcal{B}(\mathbb{R}^n)$, $T_v: \mathbb{R}^n \rightarrow \mathbb{R}^m$ liniowe dla każdego $v \in \mathbb{N}$ oraz :
	1. $B_v \cap B_{\mu} = \emptyset \; \Leftrightarrow \; \mu \neq v$ 
	2. $\bigcup_{v \in \mathbb{N}} B_v = \Omega$ 
	3. $\forall x \in B_v, h \in \mathbb{R}^n, v \in \mathbb{N}: \; \lambda^{-1}|T_v(h)| \leq |f'(x)(h)| \leq \lambda|T_v(h)|$
	4. $\forall x_1, x_2 \in B_v, v \in \mathbb{N}: \; \lambda^{-1}|T_v(x_1 - x_2)| \leq |f(x_1) - f(x_2)| \leq \lambda|T_v(x_1 - x_2)|$
	5. $f|_{B_v}: B_v \rightarrow f(B_v)$ jest odwzorowaniem bilipszitzowskim dla $v \in \mathbb{N}$ 

Dowód:
Korzystając z poprzedniego twierdzenia wiemy, że dla każdego $a \in \Omega$ możemy znalieźć $(K, T)$ które spełniają warunki 3.-5. . Korzystając z tego, że $\mathbb{R}^m$ jest ośrodkowa wiemy, że możemy znalieźć przeliczalną rodzinę $\{(K_v, T_v)\}_{v \in \mathbb{N}}$ taką, że ona spełnia 2.. Teraz definujemy indukcyjnie $B_0 = K_0$ oraz $B_v = K_{v} \backslash \bigcup_{j=0}^{v-1} K_j$ . Wtedy ciąg par $\{(B_v, T_v)\}_{v \in \mathbb{N}}$ spełnia wszystkie wymagane warunki