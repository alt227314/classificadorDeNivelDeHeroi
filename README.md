# Classificador de Nível de Herói

## Descrição

Este projeto é um simples programa que classifica o nível de um herói baseado na sua quantidade de experiência (XP). A classificação segue uma escala definida, que vai desde o nível **Ferro** até o nível **Radiante**.

O programa recebe o nome do herói e a quantidade de XP, e então exibe uma mensagem indicando o nível correspondente.

## Regras de Classificação

| XP                      | Nível      |
|-------------------------|------------|
| Menor que 1.000         | Ferro      |
| Entre 1.001 e 2.000     | Bronze     |
| Entre 2.001 e 5.000     | Prata      |
| Entre 5.001 e 7.000     | Ouro       |
| Entre 7.001 e 8.000     | Platina    |
| Entre 8.001 e 9.000     | Ascendente |
| Entre 9.001 e 10.000    | Imortal    |
| Maior ou igual a 10.001 | Radiante   |

## Tecnologias

- JavaScript
- Node.js (para versão em terminal)
- HTML (para rodar em navegador)

## Como rodar

### No navegador

1. Abra o arquivo `index.html` no navegador.
2. O programa irá pedir o nome do herói e a quantidade de XP via pop-ups (`prompt`).
3. Após inserir os dados, uma mensagem será exibida com o nível do herói.

