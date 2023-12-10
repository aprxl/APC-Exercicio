# Exercício 8
## Módulo 3 - Matrizes

> Dificuldade: Desafiador

### Descrição
Faça um programa em C que, dado um número $n$, crie uma matriz $M$ com $n+1$ linhas e $n$ colunas. 

Você primeiramente preencherá essa matriz $M$ como se ela fosse uma matriz quadrada normal. Após preenche-la, você somará os números de cada coluna da matriz e guardará o resultado na última linha. 

Por fim, você deve multiplicar todos os números da última linha e imprimir o resultado.

### Entrada
A entrada contém apenas um caso teste.

Na primeira linha, você receberá um inteiro $n$, que será utilizado para a inicialização da matriz.

Nas próximas $n$ linhas, você receberá $n$ inteiros cada, os números de cada linha da matriz.

### Saída
A saída deve conter apenas um inteiro, o resultado da multiplicação entre as somas de cada coluna da matriz.

### Exemplos
```c
// Exemplo 1
// Entrada:
2
1 2
0 1

// Saida:
3
```

```c
// Exemplo 2
// Entrada:
2
3 -1
4 7

// Saida
42
```

```c
// Exemplo 3
// Entrada:
3
 0 -1 -2
 4  0  7
-3  5  0

// Saida:
20
```

```c
// Exemplo 4
// Entrada:
3
 -1  7   -14
 12  13  -13
 24  12  20

// Saida:
-7840
```

### Dica
Use $n$ para inicializar a matriz. Lembrando que a quantidade de linhas da matriz deve ser $n + 1$.

Esse exercício também requer que você percorra a matriz de coluna em coluna, não de linha em linha.

A última linha da matriz serve apenas para guardar o resultado das somas. Por isso que existe uma linha extra na matriz.