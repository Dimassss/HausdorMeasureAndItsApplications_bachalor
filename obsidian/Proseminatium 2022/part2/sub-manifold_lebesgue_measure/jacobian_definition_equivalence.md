Twierdzenie 2.1.5
Pokażemy, że ta definicja Jacobianu jest równoważna definicji przez iloczyn zewnętrzny zdefiniowany w książce Federera "Geometric Mesure Thoery" in 3.2.1. Będzie wystaczająco pokazać równość dla odwzorowania liniowego $L: \mathbb{R}^n \rightarrow \mathbb{R}^m, \quad 1 \leq n \leq m$. Niech $e_1, \cdots, e_n$ i $e_1', \cdots, e_m'$ bazy kanoniczne odwpoiednio dla $\mathbb{R}^n$ i $\mathbb{R}^m$ . Wtedy $$
	L(e_i) = \sum_{j=1}^m a_{ji} e_j'
$$
Dalej chcemy pokazać, że definicja Federera i definicja w tu są równoważne. Oczywiście:
$$
	\| \bigwedge^n L \| = |(\bigwedge^n L) (e_1 \wedge \cdots \wedge e_n)| 
	= |L(e_1) \wedge \cdots \wedge L(e_n)| 
	= \left| (\sum^m_{j_1=1}a_{j_1, 1} e_{j_1}') \wedge \cdots \wedge (\sum_{j_n=1} a_{j_n, n} e_{j_n}') \right| 
$$
$$
	= \left| \sum_{\lambda \in \bigwedge^n_d; \sigma \in S_n} a_{\lambda(\sigma(1)), 1} \cdots a_{\lambda(\sigma(1)), n} 
		 \cdot e_{\lambda(\sigma(1))}' \wedge \cdots \wedge e_{\lambda(\sigma(n))}'\right|
	= \left| \sum_{\lambda \in \bigwedge^m_n} \left( \sum_{\sigma \in S_n} (sgn(\sigma))a_{\lambda(\sigma(1)), 1} \cdots a_{\lambda(\sigma(n)), n} \right) e_{\lambda} \right|
	= \left| \sum_{\lambda \in \bigwedge_n^m} M_{\lambda} e_{\lambda} \right| = \sqrt{\sum_{\lambda \in \bigwedge_n^m} M_{\lambda}^2}
$$
Ostatnia równość wynika z tego, że baza algebry zewnętrznej złożona z $\{ e_{\lambda}: \lambda \in \bigwedge_n^m\}$ jest ortonormalna.