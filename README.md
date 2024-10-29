# Conversor de Moedas

Um conversor de moedas simples desenvolvido em Java que utiliza a API ExchangeRate-API para obter taxas de câmbio em tempo real. Este projeto permite converter valores entre diferentes moedas, incluindo Dólar, Peso Argentino, Real Brasileiro e Peso Colombiano.

## Funcionalidades

- Conversão entre Dólar, Peso Argentino, Real Brasileiro e Peso Colombiano.
- Exibição da taxa de câmbio atual durante a conversão.
- Interface de linha de comando amigável.

## Tecnologias Utilizadas

- Java 11 ou superior
- [Gson](https://github.com/google/gson) para manipulação de JSON
- HTTP Client para requisições à API

## Exemplo de Uso

```plaintext
Seja bem-vindo(a) ao Conversor de Moeda

1) Dólar =>> Peso Argentino
2) Peso Argentino =>> Dólar
3) Dólar =>> Real Brasileiro
4) Real Brasileiro =>> Dólar
5) Dólar =>> Peso Colombiano
6) Peso Colombiano =>> Dólar
7) Sair

Escolha uma opção válida: 1
Agora insira o valor na moeda de origem que deseja converter: 100
Conversão Efetuada!
Opção escolhida: 1
Valor a ser convertido: 100.00
Taxa de câmbio atual: 988.8300
Valor convertido: 98883.00
```
