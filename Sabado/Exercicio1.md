# Exercício 1
## Módulo 1 - For e While

> Dificuldade: Complicado

### Descrição
Você é responsável pela criação de uma calculadora. A cada linha da entrada, você receberá uma caractere $c$ que representa uma operação da calculadora - as operações
válidas são:

- **+**, adição
- **-**, subtração
- **\***, multiplicação
- **/**, divisão

Além do tipo de operação, você receberá um número $n$ que representa a quantidade de
números que haverão naquela entrada. Depois, você receberá os $n$ números que farão 
parte da conta.

O seu objetivo é computar a conta dada e imprimir o seu resultado para a saída.

### Entrada
Primeiramente, você receberá um inteiro $t$ que condiz com a quantidade de linhas que
a entrada possui.

A cada linha, você receberá uma caractere $c$ que representa a operação desejada, um número $n$ que representa a quantidade de números da entrada e os $n$ números necessários para a operação.

### Saída
A sua saída deverá conter $t$ linhas, cada uma com apenas um inteiro que é o resultado
da conta.

### Exemplos
```c
// Exemplo 1
// Entrada:
1
+ 3 1 1 1

// Saida:
3
```

```c
// Exemplo 2
// Entrada:
3
+ 2 1 4
- 4 5 5 5 5
* 3 1 2 3

// Saida:
5
-10
6
```

```c
// Exemplo 3
// Entrada:
2
* 5 1 2 3 4 5
/ 2 1 5


// Saida:
120
0
```

### Dica
O exercicio sempre especifica a quantidade de repetições necessárias para sua
resolução, portanto, utilize o **for**.

A entrada `+ 3 1 2 3`, por exemplo, se refere a expressão aritmética:

```c
1 + 2 + 3
```