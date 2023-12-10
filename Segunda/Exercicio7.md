# Exercício 7
## Módulo 3 - Matrizes

> Dificuldade: Fácil

### Descrição
Dada uma matriz quadrada $M$, isto é, uma matriz que têm o mesmo número de linhas e colunas, de tamanho $n$, imprima a versão transposta de $M$.

Uma matriz transposta $M_t$ é definida como uma matriz onde as linhas e colunas trocam de lugar. Ou seja, se uma matriz $M$ é definida como:

$$
M = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$

A sua transposta $M_t$ será:

$$
M_t = \begin{bmatrix}
1 & 3 \\
2 & 4
\end{bmatrix}
$$

### Entrada
A entrada possui apenas um caso teste.

A primeira linha terá apenas um inteiro $n$, as dimensões da matriz quadrada.

As próximas $n$ linha terão $n$ inteiros cada, os números que fazem parte de cada linha da matriz.

### Saída
A saída deverá conter a matriz transposta. Serão $n$ linhas, cada uma com $n$ números. 

### Exemplos
```c
// Exemplo 1
// Entrada:
2
1 1
2 2

// Saida:
1 2
1 2
```

```c
// Exemplo 2
// Entrada:
3
1 2 3
4 5 6
7 8 9

// Saida:
1 4 7
2 5 8
3 6 9
```

```c
// Exemplo 3
// Entrada:
3 
1 0 0 
0 1 0
0 0 1

// Saida:
1 0 0
0 1 0
0 0 1
```

### Dica
Uma matriz quadrada, em C, não é nada mais nada menos que um vetor onde cada elemento deste vetor é mais um vetor. Ou seja, dada a matriz `int M[2][2]`, teremos que `M[0]` é um vetor e `M[1]` é outro vetor. Pode-se imaginar uma matriz como uma lista de vetores.

Ao visualizar a matriz, imagine uma planilha do Excel, onde cada linha contém $n$ colunas que podem armazenar um inteiro cada.

Ao imprimir a matriz normalmente com dois **for**s, com os iteradores $i$ e $j$ respectivamente, pode-se imaginar que $i$ corresponde a linha da matriz e $j$, a coluna da matriz.

Utilize $n$ como tamanho para ambas dimensões da matriz.