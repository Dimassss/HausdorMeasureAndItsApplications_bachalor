Twierdzenie 3.2.3
Niech $\Omega \in top(\mathbb{R}^n)$, $f: \Omega \rightarrow \mathbb{R}^m$ klasy $C^1$, $1 \leq n \leq m$  , $A \subset \Omega$, $A \in L_n$, $f|_A$ injekcja. Wtedy $\mathcal{H}^n(f(A)) = \int_A J_nf d \mathcal{L}^n$  

Dowód:
Niech $F := \{x \in \Omega: J_nf(x) = 0\}$ oraz $\Omega' := \Omega \backslash F$ . Wiemy, że $\mathcal{H}^n(f(F)) = 0$ . Stąd już wynika, że $$
	\mathcal{H}^n(f(A)) = \mathcal{H}^n(f(A \cap \Omega')) + \mathcal{H}^n(f(A \cap F)) = \mathcal{H}^n(f(A \cap \Omega')) = \int_{A \cap \Omega'} J_nf d \mathcal{L}^n + \int_{A \cap F} 0 d \mathcal{L}^n = \int_{A} J_nf d \mathcal{L}^n
$$ 