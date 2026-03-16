# Holy Grail Layout

Este é um layout "Holy Grail" responsivo, construído com uma abordagem moderna de HTML e CSS. Foi criado como um template base para futuros projetos, com foco em boas práticas e semântica.

## Descrição

Este projeto implementa o clássico layout "Holy Grail" utilizando técnicas modernas para garantir que seja visualmente agradável e funcional em qualquer tamanho de tela, de celulares a desktops.

## Tecnologias e Conceitos Aplicados

*   **HTML5 Semântico:** A estrutura do `index.html` utiliza tags semânticas como `<header>`, `<main>`, `<aside>` e `<footer>`. Isso melhora a acessibilidade e a organização do código, dando mais significado à estrutura da página.

*   **CSS Grid Layout:** O layout principal é construído com CSS Grid, permitindo um controle poderoso e flexível sobre o posicionamento dos elementos tanto no modo de uma coluna (mobile) quanto no de três colunas (desktop).

*   **Design Responsivo (Mobile First):** A folha de estilos `styles.css` foi escrita com a abordagem *Mobile First*. O layout padrão é otimizado para telas pequenas (uma única coluna empilhada). Uma **Media Query** (`@media (min-width: 768px)`) é usada para aplicar estilos adicionais em telas maiores, transformando o layout para o formato de três colunas.

*   **Flexbox:** Usado para alinhamento de conteúdo dentro de componentes como o header e o footer.

## Como Usar

Basta clonar este repositório e usar os arquivos `index.html` e `styles.css` como ponto de partida para o seu próprio projeto. O código está comentado para facilitar o entendimento das principais decisões de estilo.
