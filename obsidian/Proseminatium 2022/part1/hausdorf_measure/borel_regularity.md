Twierdznie 1.2.3
$(X,d)$ - przestrzeń metryczna, $p \in [0, +\infty), A \subset X. \mathcal{H}^p(A) < +\infty$. Wtedy następujące warunki są równoważne
	1. $A \in H_p$
	2. $\exists G$ typu $G_{\delta} \exists C \subset X: \mathcal{H}(C)=0 \wedge A = G \backslash C$ 
	3. $\exists B \in \mathcal{B}(X): \exists C \subset X: \mathcal{H}^p(C) = 0 \wedge A = B \cup C$ 

Dowód:
1. $\Longrightarrow$ 2. wynika z tego, że wiemy już, że istnieje takie $G$ typu $G_{\delta}$ który to spełnia, więc definujemy $C = A \backslash G$ i wtedy $\mathcal{H}^p(A) < \infty$ implikuje 2.
2. $\Longrightarrow$ 3. Weżmy $G$ i $C$ z 2. oraz $G'$ typu $G_{\delta}$ takie, że $G' \supset C$ i $\mathcal{H}^p(G') = 0$. Teraz $B:=G \backslash G'$ i $C:= A \backslash B$ spełniają warunki 3.
3. $\Longrightarrow$ 1. $B \in \mathcal{B}(X) \subset H_p \wedge \mathcal{H}^p(C) = 0 \wedge \mathcal{H}^p$ zupełna na $H_p \Longrightarrow A = B \cup C \in H_p$
  