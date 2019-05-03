# Análise de Algoritmos

Trabalho em Markdown para a matério de Estrutura de Dados   
Estudante: JOÃO HENRIQUE MAY SPENGLER

------------

## Exercícios

### Problema 1
Quais são as duas características mais comuns para analisar algoritmos?

**R**: É o tempo de execução e o consumo da memória.

### Problema 2
Por que a medida de tempo em segundos não representa qualiﬁcadamente o tempo de execução de um algoritmo?

**R**: Pois ele se torna muito dependente da tecnologia que esta sendo usada, seja software ou hardware.

### Problema 3
A medida de tempo de um algoritmo é realizada através de qual informação? O que pode afetá-la?

**R**: É realizada de acordo com os passos que o algoritmo que precisa efetuar para finalizar a sua execução. As principais causas que podem afetá-la são o ambiente do hardware em que ela é executada e o tamanho da entrada.

### Problema 4
Na análise de algoritmos, qual é o valor da base da função logarítmica e exponencial? Por que é escolhido este valor?

**R**: O valor da base é 2. É escolhido esse valor pois representa as possiveis variações de um binário.

### Problema 5
O que é complexidade de tempo?

**R**: A complexidade de tempo é a quantidade de tempo gasta para rodar um algoritmo em relação da entrada da função.

### Problema 6
Dado dois algoritmos *A* e *B* com as complexidades de tempo respectivamente *f1* e *f2*, qual é o melhor algoritmo? O que indica qual é o melhor algoritmo?

**R**: O melhor algoritmo é aquele com a menor complexidade de tempo, logo, seria o algoritmo A.

### Problema 7
Em uma função de complexidade, o que representa o termo *n*?

**R**: *n* represente a o tamanho da entrada.

### Problema 8
Quais são as operações primitivas de um algoritmo?

**R**: As operações básicas são:
  - atribuição de valores a variáveis, 
  - chamadas de métodos, 
  - operações aritméticas,
  - comparação entre valores, 
  - acesso a um vetor, 
  - ponteiro para um objeto 
  - retorno de um método.


### Problema 9
Qual é o valor de uma operação primitiva de um algoritmo?

**R**: Para as operações primitivas é atribuito o valor **1**.

### Problema 10
Desenvolva o pseudocódigo do algoritmo *SOMA*, que realiza a soma de dois números inteiros recebidos por parâmetro e tem como saída a resultado da operação. Identiﬁque a sua função de complexidade de tempo.

~~~~
SOMA (NUMERO1, NUMERO2)    
  SOMA ← NUMERO1 + NUMERO2    
  RETORNA SOMA    
~~~~

### Problema 11
Desenvolva o pseudocódigo do algoritmo *SOMA VETOR*, que realiza a soma de todos os elementos de um vetor. O algoritmo recebe o vetor *V* e tem como saída o resultado. Identiﬁque a sua função de complexidade de tempo.

~~~~
SOMA_VETOR (V)
	TOTAL ← 0
  PARA I ← 1 ATÉ N
      TOTAL ← TOTAL + V[I]
    RETORNA TOTAL
~~~~

### Problema 12
Desenvolva o pseudocódigo do algoritmo *CONTAGEM IMPARES*, que realiza a contagem de números impares de um vetor. O algoritmo recebe o vetor *V* e tem como saída o resultado. Identiﬁque a sua função de complexidade de tempo.

~~~~
CONTAGEM_IMPARES (V)
	IMPARES ← 0
	PARA I ← 1 ATÉ N
		SE V[I] % 2 != 0 ENTÃO
			IMPARES ← IMPARES + 1
	RETORNA IMPARES
~~~~

### Problema 13
Desenvolva o pseudocódigo do algoritmo *SOMA MATRIZ*, que realiza a soma de todos os elementos de uma matriz. O algoritmo recebe a matriz *M* e tem como saída o resultado. Identiﬁque a sua função de complexidade de tempo.

~~~~
SOMA_MATRIZ (M)
	SOMA ← 0
	PARA I ← 1 ATÉ N
		PARA J ← 1 ATÉ N
			SOMA ← SOMA + M[I][J]
	RETORNA SOMA
~~~~

### Problema 14
Desenvolva o pseudocódigo do algoritmo *BUSCA MATRIZ*, que identiﬁca posição *x* e *y* de um elemento em uma matriz. O algoritmo recebe a matriz *M* e o valor *V* e tem como saída a posição *x* e *y* . Identiﬁque a sua função de complexidade de tempo.

~~~~
BUSCA_MATRIZ(M, V)
	POS ← [2]
	PARA I ← 1 ATÉ N
		PARA J ← 1 ATÉ N
			SE M[I][J] = V ENTÃO
				POS[0] ← I
				POS[1] ← M
	RETORNA POS
~~~~

### Problema 15
O que é análise assintótica? Qual é o seu objetivo?

**R**: É uma estimativa que tem como objetivo compreender o tempo de execução para entradas grandes e serve para descrever o comportamento de limites.

### Problema 16
Qual é o processo da análise assintótica? Crie um exemplo.

**R**: 

### Problema 17
O que é a notação assintótica?

**R**: É um tipo de notação utilizada para analisar algoritmos que recebem uma entrada de dados muito grande. Nesta notação é considerado apenas a variável de maior grau (sem considerar à constante também).

### Problema 18
O que é a notação O-Grande ou Big-Oh?

**R**: É uma notação assintótica que serve para descrever relações onde uma função é **maior que** ou **igual** a outra.

### Problema 19
Qual é a deﬁnição formal da notação O-Grande?

**R**: *f(n) = O(g(n))* quando *f(n) <= Kg(n)* (onde **K** é uma constante qualquer)

### Problema 20
Crie um gráﬁco explicando a notação O-grande. Utilize *f(n) = 2n + 4*. Qual é um valor possível para *n<sub>0</sub>*?

**R**:

### Problema 21
O que é a notação o-pequeno ou Little-Oh?

**R**: É uma notação assintótica que serve para descrever relações onde uma função é **menor que** outra.

### Problema 22
Qual é a deﬁnição formal da notação o-pequeno?

**R**: *f(n) = o(g(n))* onde *f(n) > Kg(n)* (onde **K** é uma constante qualquer).

### Problema 23
Crie um gráﬁco explicando a notação o-pequeno.

**R**:

### Problema 24
Passe a notação O-grande e o-pequeno as funções abaixo:   
**1.** *F(n) = n + 1*   
**2.** *F(n) = 8*   
**3.** *F(n) = 2n<sup>2</sup> −1*   
**4.** *F(n) = nlogn*   
**5.** *F(n) = 3n! + 2n*   
**6.** *F(n) = 3n<sup>3</sup> + 2n<sup>2</sup> + 4n + 6*   
**7.** *F(n) = 5<sup>n</sup> + 11*   
**8.** *F(n) = 3logn*   

| N° | Big-Oh | Little-Oh |
|:--:|:------:|:---------:|
|  1 |    n   |   nlogn   |
|  2 |    1   |     n     |
|  3 |    n²  |    2n³    |
|  4 |  nlogn |     n²    |
|  5 |    n!  |    3n²!   |
|  6 |    n³  |   2<sup>n</sup>|
|  7 |   5<sup>n</sup> |     n!    |
|  8 |  logn  |     n     |
  
### Problema 25
Identiﬁque o O-Grande dos algoritmos desenvolvidos nos Problemas 10 até 14.
