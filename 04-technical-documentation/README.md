# Technical Documentation Page

Projeto 4 de 5 da certificação **Design Responsivo para Web** do freeCodeCamp.

Página de documentação técnica estilo MDN/Stripe/React — barra lateral fixa com rolagem
independente, 6 seções sobre JavaScript moderno (ES6+: variáveis/const, arrow functions,
destructuring, promises/async-await) e media query pra colapsar o menu em mobile.

## Testes

22 de 22 asserções automatizadas: `#navbar` fixo com `header` único precedendo os links;
pelo menos 5 `.main-section` (6 implementadas), cada uma começando com `header` não-vazio
e `id` batendo exatamente com o texto do cabeçalho (espaços viram `_`); mesmo número de
`.nav-link` e `.main-section`, texto do link idêntico ao do cabeçalho, `href` apontando pro
`#id` certo; pelo menos 10 `<p>`, 5 `<code>` e 5 `<li>` dentro das seções; pelo menos uma
media query.

## Como ver funcionando

Abra o `index.html` em qualquer navegador — HTML e CSS puros, sem dependência.

## Desafio original

https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page

---
Parte do [currículo completo de Design Responsivo para Web](../README.md) no freeCodeCamp.
