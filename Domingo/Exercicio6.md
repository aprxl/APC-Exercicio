# Exercício 6
## Módulo 2 - Vetores

> Dificuldade: Complicado

### Descrição
Faça um programa em C que recebe dois vetores de inteiros $A$ e $B$ de tamanho $n$. Dado um pivô (posição) $p$, imprima os elementos de $A$ das posições $0$ (início) até $p$ e os elementos de $B$ das posições $p + 1$ até $n - 1$ (fim).

### Entrada
A entrada possui apenas um caso teste.

Na primeira linha, você receberá $n$, o tamanho dos vetores, e $p$, a posição pivô.

Nas próximas duas linhas, você receberá $n$ inteiros cada, os números de $A$ e $B$ respectivamente.

### Saída
A saída possui apenas uma linha. 

Primeiramente, imprima os inteiros do vetor $A$ desde o início até a posição $p$, depois imprima os inteiros a partir da posição $p + 1$ até o fim.

### Exemplos
```c
// Exemplo 1
// Entrada:
5 2
1 2 3 4 5
6 7 8 9 0

// Saida:
1 2 3 9 0
```

```c
// Exemplo 2
// Entrada:
10 4
0 0 0 0 0 0 0 0 0 0
1 1 1 1 1 1 1 1 1 1

// Saida:
0 0 0 0 0 1 1 1 1 1
```

```c
// Exemplo 3
// Entrada:
2 0
-13 14
12 11

// Saida
-13 11
```

### Dica
Ao imprimir os números desejados do vetor $A$, lembre-se que você deverá percorrer até
a posição $p$, portanto, utilize `i <= p` como condição para o for.

Utilize $n$ como tamanho para os vetores.
