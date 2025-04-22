# Tipos de variáveis

- Variáveis de instância;
- Variáveis de classe(static);
- Variáveis locais;
- Parâmetros

# Tipos primitivos

| Tipo      | Bits | Faixa de Valores                                                        |
|-----------|------|-------------------------------------------------------------------------|
| `byte`    | 8    | -128 a 127                                                              |
| `short`   | 16   | -32.768 a 32.767                                                        |
| `int`     | 32   | -2³¹ a 2³¹-1 → -2.147.483.648 a 2.147.483.647                           |
| `long`    | 64   | -2⁶³ a 2⁶³-1 → -9.223.372.036.854.775.808 a 9.223.372.036.854.775.807   |
| `float`   | 32   | ±3.4 × 10³⁸ (aproximadamente, com ~7 dígitos de precisão)               |
| `double`  | 64   | ±1.8 × 10³⁰⁸ (aproximadamente, com ~15 dígitos de precisão)             |
| `char`    | 16   | 0 a 65.535 (representa um caractere Unicode)                            |
| `boolean` | 1*   | `true` ou `false` *(tamanho depende da implementação da JVM)*           |

# Declaração

```
tipo nomeDaVariavel = valorASerRecebido;
```
