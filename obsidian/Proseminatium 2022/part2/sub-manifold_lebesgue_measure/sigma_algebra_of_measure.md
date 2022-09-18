Twierdzenie 2.1.3
Niech $(p_i: P_i \rightarrow U_i)_{i \in I}$ będzie dowolnym, co najwyżej przeliczalnym, układem lokalnych parametryzacji takim, że $\cup_{i \in I} U_i = M$ 
	(a) Dla $A \subset M$ mamy: $A \in L_M \Leftrightarrow \forall i \in I: p_i^{-1}(A) \in L_d$ 
	(b) Dla $f: M \rightarrow Y$. gdzie $Y$ jest przestrzenią topologiczną, następujące warunki są równoważne:
		(i) $f \in \mathcal{M}(M, Y, L_M)$
		(ii) $f \circ p \in \mathcal{M}(P, Y, L_d)$ dla dowolnej parametryzacji $p: P \rightarrow U$
		(iii) $\forall i \in I: f \circ p \in \mathcal{M}(P_i, Y, L_d)$

Dowód:
(a) Niech $p: P \rightarrow U$ będzie dowolną parametryzacją i niech $\phi_i: p^{-1} \circ p_i: p^{-1}_i(U \cap U_i) \rightarrow p^{-1}(U \cap U_i)$, dla $i \in I$  . Wtedy $p^{-1}(A) = p^{-1}(A \cap \bigcup_{i\in I} U_i) = \bigcup_{i \in I} p^{-1}_i(A \cap U_i) = \bigcup_{i \in I} \phi_i(p_i^{-1}(A) \cap p_i^{-1}(U)) \in L_d$ 
(b) 
	(i) $\Longrightarrow$ (ii): $(f \circ p)^{-1}(\Omega) = p^{-1}(f^{-1}(\Omega))$ 
	(ii) $\Longrightarrow$ (iii): oczywsite
	(iii) $\Longrightarrow$ (i): $p_i^{-1}(f^{-1}()\Omega) = (f \circ p_i)^{-1}(\Omega)$ i korzystamy z (a)