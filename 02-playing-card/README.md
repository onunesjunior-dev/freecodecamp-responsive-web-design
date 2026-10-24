# Playing Card

Projeto 2 de 5 da certificação **Design Responsivo para Web** do freeCodeCamp.

3 cartas de baralho (Ás de Espadas, Rei de Copas, 7 de Ouros) com layout de 3 zonas
(canto superior esquerdo, centro, canto inferior direito) usando Flexbox bidimensional —
`justify-content` no contêiner da carta e `align-self` individual em cada zona.

## Testes

18 de 18 asserções automatizadas: `#playing-cards` com `display: flex`,
`justify-content: center`, `flex-wrap: wrap` e `gap: 20px`; pelo menos 3 `.card` com
`width`/`height` fixos e exatamente 3 filhos (`.left`, `.middle`, `.right`);
`.card` com `display: flex` e `justify-content: space-between`; cada zona com o
`align-self` certo (`flex-start`/`center`/`flex-end`); `.middle` como `flex-direction: column`.

## Como ver funcionando

Abra o `index.html` em qualquer navegador — HTML e CSS puros, sem dependência.

## Desafio original

https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-playing-card

---
Parte do [currículo completo de Design Responsivo para Web](../README.md) no freeCodeCamp.
