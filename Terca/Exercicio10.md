# Exercício 9
## Módulo 4 - Strings

> Dificuldade: Complicado

### Descrição
Faça um programa em C que recebe uma string de $n$ linhas, com espaços, e retorne a frequência de uma caractere $c$ específica. Ou seja, a quantidade de vezes que $c$ aparece na string.

Cada linha pode ter no máximo 256 caracteres.

### Entrada
A entrada contém apenas um caso teste.

A primeira linha contem um inteiro $n$, a quantidade de linhas, e $c$, a caractere desejada para o cálculo da frequência.

As próximas $n$ linhas conterão cada uma string, com espaços, de até 256 caracteres.

### Saída
A saída deverá conter apenas uma linha da seguinte forma:

```
Freq.: Q
```

Onde $Q$ é a quantidade de vezes que a caractere $c$ aparece nas strings recebidas.

### Exemplos
```c
// Exemplo 1
// Entrada:
3 a
opa, essa e uma string
de teste e nao tem proposito
maior do que servir para testes

// Saida:
Freq.: 7
```

```c
// Exemplo 2
// Entrada:
2 o
outra string para testes
ela continua nao tendo proposito maior

// Saida:
Freq.: 8
```

### Dica
Utilize 256 como tamanho da string.

Não é necessário a criação de múltiplas strings; crie apenas uma e recicle-a a medida que for  necessário.

A frequência da caractere $c$ vale para todas as linhas da entrada.

Utilize a função `fgets([string], [tamanho_max], stdin)` para pegar a string da entrada.

Lembre-se de limpar o **lixo de memória** da entrada, caso contrário o `fgets` pode não funcionar de forma esperada!

> **Atenção** Eu posso ter errado na hora de contar as caracteres dos exemplos, portanto, cheque você também se o resultado está correto.