# problema_dos_navios

O código é uma resolução em Python utilizando a biblioteca mip para o problema de otimização de Programação Linear Inteira Binária(PLIB). 
Problema de modelagem matemática apresentado na disciplina de Matemática Computacional.

**Problema abordado**

Três navios serão carregados no porto de Tubarãoo com minério de ferro. 
O terminal de minério tem 4 berços onde cada um deles possui um shiploader com capacidade diferente. 
Devido as diferenças nas capacidades dos navios e dos shiploaders, há diferentes
tempos de carregamento, dependendo das combinações entre navios e berços. 
A tabela a seguir apresenta os tempos de carregamento dos navios em horas para as diferentes combinações navio-berço.

**Valores da tabela é o tempo que está na matriz criada no código, navios (0,1,2) x berços (0,1,2,3)**

Por exemplo, se o navio A for carregado no berço 1, demorará 7 horas; mas se o mesmo
navio for carregado no berço 2, demorará 13 horas. Formule um modelo de PLIB de modo
que o tempo de carregamento total dos navios seja minimo.
