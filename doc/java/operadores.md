# Aritméticos
| Operador | Símbolo | Descrição                 | Exemplo        | Resultado |
|----------|---------|---------------------------|----------------|-----------|
| Adição   | `+`     | Soma dois valores         | `5 + 3`        | `8`       |
| Subtração| `-`     | Subtrai dois valores      | `10 - 4`       | `6`       |
| Multiplicação | `*` | Multiplica dois valores  | `6 * 7`        | `42`      |
| Divisão  | `/`     | Divide dois valores       | `20 / 5`       | `4`       |
| Módulo   | `%`     | Resto da divisão inteira  | `10 % 3`       | `1`       |


# Lógicos
| Operador Lógico | Símbolo | Descrição                                  | Exemplo              | Resultado |
|------------------|---------|--------------------------------------------|-----------------------|-----------|
| E lógico         | `&&`    | Retorna `true` se ambos os operandos forem verdadeiros | `true && false`     | `false`   |
| OU lógico        | `||`    | Retorna `true` se ao menos um operando for verdadeiro | `true || false`      | `true`    |
| NÃO lógico       | `!`     | Inverte o valor lógico                      | `!true`           | `false`   |

# Comparação
| Operador de Comparação | Símbolo | Descrição                                | Exemplo        | Resultado |
|------------------------|---------|------------------------------------------|----------------|-----------|
| Igualdade              | `==`    | Verifica se dois valores são iguais      | `5 == 5`       | `true`    |
| Diferença              | `!=`    | Verifica se dois valores são diferentes  | `3 != 4`       | `true`    |
| Maior que              | `>`     | Verifica se o valor da esquerda é maior  | `7 > 5`        | `true`    |
| Menor que              | `<`     | Verifica se o valor da esquerda é menor  | `2 < 8`        | `true`    |
| Maior ou igual         | `>=`    | Verifica se é maior ou igual             | `6 >= 6`       | `true`    |
| Menor ou igual         | `<=`    | Verifica se é menor ou igual             | `4 <= 3`       | `false`   |


# Atribuição
| Operador de Atribuição | Símbolo | Descrição                                 | Exemplo            | Resultado |
|------------------------|---------|-------------------------------------------|--------------------|-----------|
| Atribuição simples     | `=`     | Atribui o valor à variável                | `int x = 10;`      | `x = 10`  |
| Atribuição de soma     | `+=`    | Soma e atribui o resultado à variável     | `x += 5;` (equivalente a `x = x + 5`) | `x = 15` |
| Atribuição de subtração| `-=`    | Subtrai e atribui o resultado à variável  | `x -= 3;` (equivalente a `x = x - 3`) | `x = 12` |
| Atribuição de multiplicação | `*=` | Multiplica e atribui o resultado à variável | `x *= 2;` (equivalente a `x = x * 2`) | `x = 24` |
| Atribuição de divisão | `/=`    | Divide e atribui o resultado à variável   | `x /= 4;` (equivalente a `x = x / 4`) | `x = 6`  |
| Atribuição de módulo  | `%=`    | Aplica o módulo e atribui o resultado à variável | `x %= 4;` (equivalente a `x = x % 4`) | `x = 2`  |

# Ternário
```java
tipo nomeVariavel = (condiçao) ? expressãoVerdadeira :  expressaõFalsa;
```