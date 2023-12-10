# Exercício 5
## Módulo 2 - Vetores

> Dificuldade: Facil

### Descrição
Faça um programa que recebe dois vetores de inteiros $V_1$ e $V_2$ de tamanho $n$. Após
recebe-los da entrada, adicione os números de $V_1$ com os números de $V_2$ e imprima o
vetor resultante.

### Entrada
A entrada possui apenas um caso teste.

Na primeira linha, você receberá um inteiro $n$, o tamanho dos vetores.

Nas próximas duas linhas, você receberá $n$ inteiros cada, os números de $V_1$ e $V_2$
respectivamente.

### Saída
A saída possui apenas uma linha que contém os números do vetor resultante, ou seja, o
vetor que contém os resultados das somas.

### Exemplos
```c
// Exemplo 1
// Entrada:
5
1 0 1 0 1
1 1 1 1 1

// Saida:
2 1 2 1 2
```

```c
// Exemplo 2
// Entrada:
3
10 20 30
25 35 45

// Saida:
35 55 75
```

```c
// Exemplo 3
// Entrada:
4
7 5 4 -2
1 0 -3 -7

// Saida:
8 5 1 -9
```

### Dica
O vetor-resultante $V_r$ contém a soma dos elementos de $V_1$ e $V_2$, ou seja:

```c
Vr[0] = V1[0] + V2[0];
Vr[1] = V1[1] + V2[1];
...
```

Use $n$ como tamanho dos vetores.
