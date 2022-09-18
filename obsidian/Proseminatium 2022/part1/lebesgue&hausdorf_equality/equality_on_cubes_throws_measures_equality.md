Lemat 1.4.1
Niech $\mu$ będzie miarą na $\sigma$ - ciele $L_m$ w $\mathbb{R}^m, m \geq 1$ taka, że dla przedziałów zwartych $I$ w $\mathbb{R}^m$ mamy $\mu(I) = vol(I)$. Wtedy $\mu = \mathcal{L}^m$ 

Dowód:
Niech $\{I_i\}$ ciąg kostek zwartych który pokrywa $A \in L_m$ . Mamy $$ 
	\mu(A) \leq \sum_{i \in \mathbb{N}} \mu(I_i) = \sum_{i \in \mathbb{N}} vol(I_i)
$$
Zatem $\mu(A) \leq \mathcal{L}^m(A)$ . Zakładając, że $A$ jest ograniczony znajdziemy $I$ przedział zwarty taki, że $A \subset I$. Skoro $$
	\mu(I \backslash A) \leq \mathcal{L}^m(I \backslash A) 
$$ Stąd $\mu(I) - \mu(A) \leq \mathcal{L}^m(I) - \mathcal{L}^m(A)$. Czyli $\mathcal{L}^m(A) \leq \mu(A)$. Zatem dla zbiorów ograniczonych mamy równość $\mathcal{L}^m(A) = \mu(A)$ . Każdy zbiór $A \in L_m$ możemy przedstawić w postaci sumy rozłącznej zbirów mierzlnych ogranicznych skąd wynika teza.