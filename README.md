# algoritmos_busca
Implementação dos Algoritmos de Busca gulosa e Busca A* (A Estrela) em Python

Este repositório contém a resolução dos exercícios do capítulo de Algoritmos de Busca do curso Inteligência Artificial e Machine Learning: O Guia Completo do professor Jones Granatyr.

# Problema: Efetuar a busca utilizando os dois algoritmos para ir da cidade de Porto União até Curitiba e comparar os resultados.

# Resultado do exercício utilizando o algoritmo de busca gulosa:

-------
Atual: Porto União
0  -  São Mateus do Sul  -  123
1  -  Canoinhas  -  141
2  -  Paulo Frontin  -  172
-------
Atual: São Mateus do Sul
0  -  Palmeira  -  59
1  -  Lapa  -  74
2  -  Três Barras  -  131
3  -  Irati  -  139
-------
Atual: Palmeira
0  -  Campo Largo  -  27
1  -  Irati  -  139
-------
Atual: Campo Largo
0  -  Curitiba  -  0
1  -  Balsa Nova  -  41
-------
Atual: Curitiba

# Km total Percorrido = São Mateus do Sul (87) + Palmeira (77) + Campo Largo (55) + Curitiba (29) = 87+77+55+29 = 248 Km

# Resultado do exercício utilizando o algoritmo de busca A* (A Estrela):

------------------
Atual: Porto União
0  -  São Mateus do Sul  -  87  -  123  -  210
1  -  Paulo Frontin  -  46  -  172  -  218
2  -  Canoinhas  -  78  -  141  -  219
------------------
Atual: São Mateus do Sul
0  -  Lapa  -  60  -  74  -  134
1  -  Palmeira  -  77  -  59  -  136
2  -  Três Barras  -  43  -  131  -  174
3  -  Irati  -  57  -  139  -  196
------------------
Atual: Lapa
0  -  Contenda  -  26  -  39  -  65
1  -  Mafra  -  57  -  94  -  151
------------------
Atual: Contenda
0  -  Araucaria  -  18  -  23  -  41
1  -  Balsa Nova  -  19  -  41  -  60
------------------
Atual: Araucaria
0  -  Curitiba  -  37  -  0  -  37
------------------
Atual: Curitiba

# Km total Percorrido = São Mateus do Sul (87) + Lapa (60) + Contenda (26) + Araucaria (18) + Curitiba (37) = 87+60+26+18+37 = 228 Km

# Fica evidenciado que o algoritmo de busca A * obtem um resultado melhor do que a busca gulosa para o resultado do problema proposto no exercício.
