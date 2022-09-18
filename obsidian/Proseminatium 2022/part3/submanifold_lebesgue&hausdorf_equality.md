Twierdzenie 3.3.1
Niech $M \in \mathcal{M}^1_d(\mathbb{R}^n)$ . Wtedy $L_M \subset H_d$ oraz $\mathcal{L}^M = \mathcal{H}^d$ na $L_M$ 

Dowód:
Dla $d \in \{0, n\}$ teza twierdzenia jest oczywista. Niech $1 \leq d \leq n -1$.
Ustalmy $A \in L_M$. Ustalmy dowolny atlas $\{p_v: P_v \rightarrow U_v\}_{v \in \mathbb{N}}$ podrozmaitości $M$. Definujemy indukcyjnie $C_0:=p_0^{-1}(A)$ oraz $C_v := p_v^{-1}(A) \backslash \bigcup_{j=0}^{v-1} p_j^{-1}(A)$. Ponieważ $A \in L_M \Leftrightarrow \forall v \in \mathbb{N}: \; p_v^{-1}(A) \in L_d$ to stąd wynika, że $A$ jest $H^d$ mierzalny jako suma obrazów $p_v^{-1}(A)$ przez $p_v$ które są bijektywne klasy $C^1$. 
Definujemy indukcyjnie $B_0:=U_0$ oraz $\mathcal{B}_v := U_v \backslash \bigcup_{j=0}^{v-1} U_j$ , $C_0:=p_0^{-1}(B_0)$ oraz $C_v := p_v^{-1}(B_v)$ .  Dalej korzystając z własności miary $\mathcal{L}^M$ dostajemy $$
	\mathcal{L}^M(A) = \mathcal{L}^M(\bigcup_{v \in \mathbb{N}} A \cap B_v) 
	= \sum_{v \in \mathbb{N}} \mathcal{L}^M(A \cap B_v) 
	= \sum_{v \in \mathbb{N}} \mathcal{L}^M(p_v(p_v^{-1}(A \cap B_v))) 
	= \sum_{v \in \mathbb{N}} \int_{p_v^{-1}(A \cap B_v)} J_d p_v d \mathcal{L}^d
	= \sum_{v \in \mathbb{N}} \mathcal{H}^d(p_v(p_v^{-1}(A \cap B_v))) 
	= \sum_{v \in \mathbb{N}} \mathcal{H}^d(A \cap B_v) 
	= \mathcal{H}^d(A)
$$
