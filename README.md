# README - Cálculo do Produto

## Descrição do Problema
Este programa lê dois valores inteiros do usuário, calcula o produto entre esses dois valores e exibe o resultado em um formato específico. O valor do produto deve ser atribuído a uma variável chamada `PROD`, que será impressa junto com a mensagem correspondente.

## Especificações

### Entrada
- O programa deve ler dois valores inteiros.
- Os valores serão fornecidos em linhas separadas.

### Saída
- O programa deve imprimir a mensagem `"PROD"` seguida do resultado do produto dos dois valores.
- A saída deve seguir o formato: `PROD = X`, onde `X` é o valor do produto.
- Deve haver um espaço em branco antes e depois do sinal de igualdade (`=`).
- O programa deve terminar com uma nova linha. Não incluir a nova linha pode resultar em um erro de apresentação ("Presentation Error").

## Exemplo de Entrada e Saída

### Exemplo 1

**Entrada**
```
3
9
```

**Saída**
```
PROD = 27
```

### Exemplo 2

**Entrada**
```
-5
6
```

**Saída**
```
PROD = -30
```

## Implementação em Python

O código a seguir implementa a solução do problema:

```python
# Leitura dos valores inteiros
A = int(input())
B = int(input())

# Cálculo do produto
PROD = A * B

# Impressão no formato especificado
print("PROD = {}".format(PROD))
```

### Explicação do Código
1. **Leitura dos Valores**: Os valores inteiros `A` e `B` são lidos a partir da entrada do usuário.
2. **Cálculo do Produto**: O produto dos valores `A` e `B` é calculado e armazenado na variável `PROD`.
3. **Saída Formatada**: A mensagem `"PROD = X"` é impressa, onde `X` é o valor do produto.

## Observações
- Certifique-se de que a saída está formatada corretamente, com os espaços adequados e a nova linha no final, para evitar erros de apresentação.
- O código foi desenvolvido para ser executado em Python 3.9.
