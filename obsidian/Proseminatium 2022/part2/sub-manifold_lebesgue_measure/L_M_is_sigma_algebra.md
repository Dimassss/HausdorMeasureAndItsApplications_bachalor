Twierdzenie 2.1.2
$L_M$ jest $\sigma$-algebra oraz, że $\mathcal{B}(\mathbb{R}^n) \subset L_M$ 

Dowód:
Dla $d \in \{0, n\}$ to twierdzenie jest oczywiste. Niech $0 < d < n$. Oczywiście $\emptyset \in L_M$ . Ustalmy $A \in L_M$. 
Pokażemy, że $A^C \in L_M$ . Ustalamy dowolną parametryzację $p: P \rightarrow U$ . Mamy $p^{-1}(A^C) = p^{-1}(M \backslash A) = p^{-1}(M) \backslash p^{-1}(A) = P \backslash p^{-1}(A)$ . Poniważ $P$ jest otwarty oraz $p^{-1}(A) \in L_d$ to stąd wynika, że $p^{-1}(A^C) \in L_d$ .
Teraz pokażemy, że przeliczalna suma $\{A_j\}_{j \in \mathbb{N}} \subset L_M$ jest w $L_M$ co kończy dowód. Ustaliamy dowolne $p: P \rightarrow U$. $$ 
p^{-1}(\bigcup_{i \in \mathbb{N}} A_i ) = \bigcup_{i \in \mathbb{N}} p^{-1}(A_i) \in L_d
$$ Zostało pokazać, że zbiory borelowske są w tej algebrze. Wystarczy pokazać, że zbioru otwarte są w $L_M$ Ale widać, że tak jest z samej postaci tych parametryzacji. To kończy dowód.  