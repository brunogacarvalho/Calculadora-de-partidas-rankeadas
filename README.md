# Calculadora de Partidas Rankeadas

Desafio da DIO proposto pelo professor.

## O que faz

Calcula o nível de um jogador baseado em vitórias e derrotas.

## Como funciona

A função recebe vitórias e derrotas, calcula o saldo e retorna o nível do jogador.

## Níveis

- Menos de 10 vitórias = Ferro
- 11 a 20 vitórias = Bronze
- 21 a 50 vitórias = Prata
- 51 a 80 vitórias = Ouro
- 81 a 90 vitórias = Diamante
- 91 a 100 vitórias = Lendário
- 101+ vitórias = Imortal

## Exemplo

```javascript
let resultado = calcularNivel(75, 20);
```

Saída: "O Herói tem de saldo de 55 está no nível de Ouro"
