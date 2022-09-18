Lemat 3.2.1
$\Omega \in top(\mathbb{R}^n)$, $f: \Omega \rightarrow \mathbb{R}^m$ klasy $C^1$, $1 \leq n \leq m$ . $\forall x \in \Omega: f'(x)$ jest monormifizmem. NIech $L_n \ni A \subset \Omega$ taki, że $f|_A$ - injekcja. Wtedy:
	1. $f(A) \in H_n$
	2. $\mathcal{H}^n(f(A)) = \int_A J_nfd \mathcal{L}^n$ 

Dowód:
Już wiemy, że $f(A) \in H_n$, więc musimy jedynie pokazać tą równość. Ustalmy $\lambda > 1$ i wybieramy rozbicie $\Omega$ oraz ciągi operatorów zgodnie z lematem 3.1.2 $\{(B_v, T_v)\}_{v \in \mathbb{N}}$ . Korzystając z własności normy w algebrze zewnętrznej oraz tego, że $J_nf = \|\bigwedge_nf\|$, dostajemy dla $x \in B_v$ oraz $v \in \mathbb{N}$ nierówność $$
	\lambda^{-n}|T_v| \leq (J_nf)(x) \leq \lambda^n|T_v|
$$
która wynika bezpośrednio z następującej nierówności z [lematu](part3/continuous_func_properties/cover_with_local_bounds) $$
	\lambda^{-1}|T_v(h)| \leq |f'(x)(h)| \leq \lambda|T_v(h)| \quad\quad  \text{dla} \; x \in B_v, h \in \mathbb{R^n}, v \in \mathbb{N}
$$
Definujemy $A_v := A \cap B_v$. Wtedy całkując otrzymaną nierówność na $A_v$ dostajemy $$
	\lambda^{-n}|T_v|\mathcal{L}^n(A_v) \leq \int_{A_v}J_nf d \mathcal{L}^n \leq \lambda^n |T_v| \mathcal{L}^n(A_v)
$$
W tym samym lemacie 3.1.2 mamy następującą nierówność $$
	\lambda^{-1}|T_v(x_1 - x_2)| \leq |f(x_1) - f(x_2)| \leq \lambda |T_v(x_1, x_2)| \quad \quad \text{dla } x_1,x_2 \in B_v  
$$
Skąd już wynika, że $$
	\lambda^{-1}|T_v(x_1) - T_v(x_2)| \leq |f(x_1) - f(x_2)| \leq \lambda|T_v(x_1) - T_v(x_2)| \quad \quad \text{dla } x_1, x_2 \in A_v
$$
Rozpatrzymy diagram

<img align="center" src="https://i.upmath.me/svg/%0A%25%20https%3A%2F%2Ftikzcd.yichuanshen.de%2F%23N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRABUB9GgCgEFuAShABfUuky58hFACZyVWoxZsAZvyGjxIDNjwEi82YvrNWiEAJpaJe6UQAsC6qZUWuvK8JGKYUAObwRKCqAE4QALZIAIzUOBBIZCAMdABGMAwACpL6MiChWP4AFjggLsrmIEXcNiBhkUjyIPGJ1CnpWTn2FgXFpeVmbB4APpzAViK19VGIsc0JiADMA25VNWIh4TNNLUsrlSNjE1NbjXELc66VqqPj3JM%2BIkA%0A%5Cbegin%7Btikzcd%7D%0AT_v(A_v)%20%26%20%20%26%20f(A_v)%20%5Carrow%5Bll%2C%20%22h_v%22'%5D%20%5Carrow%5Brr%2C%20%22h_v%22%5D%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%26%20%20%26%20T_v(A_v)%20%5C%5C%0A%20%20%20%20%20%20%20%20%20%26%20%20%26%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%26%20%20%26%20%20%20%20%20%20%20%20%20%20%5C%5C%0A%20%20%20%20%20%20%20%20%20%26%20%20%26%20A_v%20%5Carrow%5Blluu%2C%20%22T_v%7C_%7BA_v%7D%22'%5D%20%5Carrow%5Brruu%2C%20%22T_v%7C_%7BA_v%7D%22%5D%20%5Carrow%5Buu%2C%20%22f%7C_%7BA_v%7D%22%5D%20%26%20%20%26%20%20%20%20%20%20%20%20%20%0A%5Cend%7Btikzcd%7D%0A" alt="
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRABUB9GgCgEFuAShABfUuky58hFACZyVWoxZsAZvyGjxIDNjwEi82YvrNWiEAJpaJe6UQAsC6qZUWuvK8JGKYUAObwRKCqAE4QALZIAIzUOBBIZCAMdABGMAwACpL6MiChWP4AFjggLsrmIEXcNiBhkUjyIPGJ1CnpWTn2FgXFpeVmbB4APpzAViK19VGIsc0JiADMA25VNWIh4TNNLUsrlSNjE1NbjXELc66VqqPj3JM+IkA
\begin{tikzcd}
T_v(A_v) &amp;  &amp; f(A_v) \arrow[ll, &quot;h_v&quot;'] \arrow[rr, &quot;h_v&quot;]                                       &amp;  &amp; T_v(A_v) \\
         &amp;  &amp;                                                                                   &amp;  &amp;          \\
         &amp;  &amp; A_v \arrow[lluu, &quot;T_v|_{A_v}&quot;'] \arrow[rruu, &quot;T_v|_{A_v}&quot;] \arrow[uu, &quot;f|_{A_v}&quot;] &amp;  &amp;         
\end{tikzcd}
" />



dla $h_v = (T_v|_{A_v}) \circ (f|_{A_v})^{-1}$ mamy $Lip(h_v) \leq \lambda$, $Lip h_v^{-1} \leq \lambda$ dla $v \in \mathbb{N}$. Zatem dla $v \in \mathbb{N}$ otrzymujemy $$
	\lambda^{-n} \mathcal{H}^n(T_v(A_v)) \leq \mathcal{H}^n(f(A_v)) \leq \lambda^n \mathcal{H}^n(T_v(A_v))
$$
Skąd dostajemy $$
	\lambda^{-2n}\mathcal{H}^n(f(A_v)) \leq \int_{A_v}J_nf d \mathcal{L}^n \leq \lambda^{2n} \mathcal{H}^n(f(A_v))
$$
Dalej sumując tą nierówność po $v \in \mathbb{N}$ dostajemy $$
	\lambda^{-2n} \sum_{v=0}^{\infty} \mathcal{H}^n(f(A_v)) \leq \int_{A_v}J_nf d \mathcal{L}^n \leq \lambda^{2n} \sum_{v=0}^{\infty} \mathcal{H}^n(f(A_v))
$$
Skąd na podstawie injektywności $f$ dostajemy $$
	\lambda^{-2n}\mathcal{H}^n(f(A)) \leq \int_{A}J_nf d \mathcal{L}^n \leq \lambda^{2n} \mathcal{H}^n(f(A))
$$
Teraz widzimy, że jeśli $\mathcal{H}^n(f(A)) = +\infty$ to równość z tezy zachodzi. Jeśli $\mathcal{H}^n(f(A)) < +\infty$ to przechodząc z $\lambda > 1$ do $1$ dostajemy równość $$
	\mathcal{H}^n{f(A)} = \int_A J_nf d\mathcal{L}^n
$$