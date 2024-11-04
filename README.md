# Função de Fatorial em JavaScript

Este projeto implementa uma função recursiva em JavaScript que calcula o fatorial de um número inteiro positivo.

## Funcionalidade

- **Cálculo de Fatorial**: A função `factorialize(num)` calcula o fatorial de um número inteiro `num`. O fatorial de um número é o produto de todos os números inteiros positivos até ele (ex.: 5! = 5 × 4 × 3 × 2 × 1 = 120).

## Explicação do Código

1. **Condição de Número Negativo**  
   A função retorna `-1` se o número fornecido for negativo, indicando que não é possível calcular o fatorial de números negativos.

2. **Caso Base**  
   Se `num` for igual a 0, a função retorna 1. Por definição, 0! = 1.

3. **Chamada Recursiva**  
   Para números positivos maiores que zero, a função chama a si mesma, multiplicando o número atual `num` pelo fatorial de `num - 1`. Esse processo continua até que `num` seja 0, completando o cálculo.

## Exemplo de Uso

```javascript
console.log(factorialize(5));  // Saída: 120
