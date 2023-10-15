# Classe de Herói para Jogo de Aventura em JavaScript

## Índice

1. [Descrição](#descrição)
2. [Utilização](#utilização)

## Descrição

Esta é uma classe genérica em JavaScript que representa um herói em um jogo de aventura. A classe possui propriedades para nome, idade e tipo, bem como um método para realizar ataques de acordo com o tipo do herói.

## Utilização

Para usar esta classe em seu projeto, siga as etapas abaixo:

```javascript
// Copie a classe Heroi para o seu projeto JavaScript.
class Heroi {
  constructor(nome, idade, tipo) {
    // ...
  }

  atacar() {
    // ...
  }
}

// Crie objetos Heroi, passando o nome, idade e tipo como argumentos para o construtor.
const meuHeroi = new Heroi("Herói Exemplo", 25, "mago");

// Chame o método `atacar` em seu objeto Heroi para realizar um ataque.
meuHeroi.atacar();
