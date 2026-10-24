# Book Inventory

Projeto 3 de 5 da certificação **Design Responsivo para Web** do freeCodeCamp.

Tabela de inventário de livros com status de leitura (`Read`, `To Read`, `In Progress`)
destacado por gradiente contextual e um indicador de nota por círculos preenchidos —
tudo via **seletores de atributo CSS avançados** (`[class="..."]`, `[class^="..."]`,
`[class~="..."]`) combinados com `:first-child` e `:nth-child(-n + 2)`, sem precisar de
classes extras individuais pra cada combinação.

## Testes

53 de 53 asserções automatizadas: estrutura semântica da tabela (`thead` com 5 colunas,
`tbody` com linhas classificadas `read`/`to-read`/`in-progress`); badge de status com
borda e gradiente por classe da linha; geometria compartilhada dos indicadores via
`span[class^="rate"]`; preenchimento das esferas de nota (1, 2 ou 3) via seletor de
palavra exata `[class~="..."]` combinado com `:first-child`/`:nth-child(-n + 2)`.

## Como ver funcionando

Abra o `index.html` em qualquer navegador — HTML e CSS puros, sem dependência.

## Desafio original

https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-book-inventory-app

---
Parte do [currículo completo de Design Responsivo para Web](../README.md) no freeCodeCamp.
