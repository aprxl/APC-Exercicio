# Exercício 4
## Módulo 2 - Vetores

> Dificuldade: Desafiador

### Descrição
Você será responsável por criar um programa em C capaz de preencher um vetor $V$ com uma lista crescente de números. 

Na entrada, você receberá um número $i$ que representa o primeiro número da lista, e
um número $l$ que representa o último número da lista. Você deverá preencher o vetor
com os números de $i$ até $l$, inclusivos, pulando apenas **os quadrados perfeitos** (4, 16, 81, 144 etc.).

Após preencher o vetor, você deverá imprimi-lo ao usuário, junto do tamanho final
do vetor.

### Entrada
A entrada possui apenas um caso teste.

Na primeira linha da entrada você recebera um inteiro $i$, o primeiro número da lista, e $l$, o último número da lista.

### Saída
A saida deverá conter duas linhas. A primeira deverá conter o tamanho do vetor formado e, a segunda, os números do vetor.

### Exemplos
```c
// Exemplo 1
// Entrada:
1 10

// Saida:
7
2 3 5 6 7 8 10
```

```c
// Exemplo 2
// Entrada:
21 32

// Saida:
11
21 22 23 24 26 27 28 29 30 31 32
```

### Dica
O exercício não necessariamente requer que você utilize um vetor, contudo, utilize-o
de qualquer forma.

Utilize a função `sqrt` da biblioteca `<math.h>` para checar se um número é quadrado perfeito ou não. Lembrando que a função `sqrt` retorna a raiz quadrada de um número real, ou seja, um `double`.

Para checar se um número real $n$ possui parte decimal em C, basta fazer:
```c
// Se essa expressao for verdadeira, o numero 'n' nao tem casa decimal. 
n == (int)n;
``` 

Utilize $l - i + 1$ como tamanho inicial do vetor.