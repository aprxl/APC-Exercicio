# Exercício 9
## Módulo 4 - Strings

> Dificuldade: Fácil

### Descrição
Faça um programa em C capaz de receber uma string qualquer, sem espaços, e retorne o tamanho dela.

### Entrada
A entrada possui apenas um caso teste.

Na primeira linha, você receberá uma string de até 64 caracteres, sem espaços.

### Saída
A saída deverá conter apenas uma linha, contendo um inteiro que representa o tamanho da string dada.

### Exemplos
```c
// Exemplo 1
// Entrada:
Olatudobem?

// Saida:
11
```

```c
// Exemplo 2
// Entrada:
Programaredivertido!

// Saida:
20
```

```c
// Exemplo 3
// Entrada:
Passarnamateriaemaisdivertindoainda!!

// Saida:
37
```

### Dica
Utilize 64 como tamanho da string.

Utilize a função `fgets([string], [tamanho_max], stdin)` para pegar a string da entrada.

Lembre-se de que uma string é apenas um vetor de tipo `char`.
