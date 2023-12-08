# Exercício 2
## Módulo 1 - For e While

> Dificuldade: Facil

### Descrição
Escreva um simples programa capaz de formar um número dados os seus dígitos

### Entrada
A entrada possui apenas um caso teste.

Na entrada, existem $n$ inteiros, sendo que $n$ é **indefinido**. Cada um dos inteiros
é um dígito do número final, ou seja, o primeiro digito é a unidade, o segundo é a dezena, o terceiro é a centena, o quarto é o milhar etc.

A entrada acaba em **EOF**. A entrada contem no minimo um inteiro.

### Saída
A sua saída deverá conter apenas um inteiro, o número formado pelos digitos dados.

### Exemplos
```c
// Exemplo 1
// Entrada:
3 2 1

// Saida:
123
```

```c
// Exemplo 2
// Entrada:
4 7 2 1 3 1

// Saida:
131274
```

```c
// Exemplo 3
// Entrada:
7 1 7

// Saida:
717
```

### Dica
A função **scanf** retorna *EOF* ao atingir o final da entrada. Portanto, você pode usar a seguinte expressão para detectar o EOF:

```c
scanf("%d", ...) == EOF
```

O exercício em nenhum momento especifica a quantidade necessária de repetições, portanto, utilize o **while**.

No Windows, ao testar o seu programa, você pode utilizar o **CTRL+Z** para representar
o *EOF* no terminal.