Definicja 1.1.1
Niech $(X, \varrho)$ będzie przestrzenią metryczną, niech $\mathcal{F} \subset \mathcal{P}(X)$,  $\emptyset \in \mathcal{F}$ i niech $\zeta: \mathcal{F} \rightarrow [0, +\infty]$ będzie dowolnym odwozorowaniem takim, że $\zeta(\emptyset) = 0$. Funkcję $\zeta$ będziemy czasem nazywać funkcją tworzącą. Dla dowolnego $0 < \delta \leq +\infty$ niech  $\phi_{\delta}, \phi: \mathcal{P}(X) \rightarrow [0, +\infty]$ będą zdefiniowane następująco: $$
    \phi_{\delta}(A) := \inf \{
            \sum_{j=1}^{\infty} \zeta(A_j):
            A_j \in \mathcal{F}, diam(A_j) \leq \delta, A \subset \bigcup_{j=1}^{\infty} A_j
        \},
    \quad 
    A \subset X,
    \quad
    \phi := \sup_{\delta > 0} \phi_{\delta}
$$
Powyższa konstrukcja nazywa się konstrukcją Carathedeorego

