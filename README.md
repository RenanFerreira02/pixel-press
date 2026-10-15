# Pixel Press nº 1 · Como nasce um jogo

Página de estudo da Fase 1 do portfólio (HTML + CSS). É a primeira edição de uma zine de videogames que acompanha a criação de um pequeno jogo, o Brotinho, da ideia ao lançamento. Ela é construída etapa por etapa, um conceito por commit, para ser usada em aula.

## Como abrir

Não precisa instalar nada: abra o arquivo `index.html` no navegador.

Para ver a página como ela estava em uma etapa, use `git log --oneline` e depois `git checkout <hash>`. Para voltar ao fim do projeto, `git checkout main`.

## Etapas

- `00-ponto-de-partida`: esqueleto do documento HTML.
- `01-estrutura-editorial`: todo o conteúdo da revista em HTML semântico, ainda sem CSS.
- `02-tipografia`: `style.css` com as fontes Press Start 2P e Atkinson Hyperlegible, escala de tamanhos, `line-height` e `letter-spacing`.
- `03-paleta-com-variaveis`: cores em variáveis `--color-*`, contraste conferido e fundos alternados noite e papel.
- `04-grid-de-colunas`: grid de 12 colunas em todos os blocos, com `grid-column`, `margin`, `padding` e `border`.
- `05-grid-areas`: mosaico de depoimentos com `grid-template-areas`.
- `06-grid-aninhado`: grids dentro do grid (regras, canais, passos, paleta e glossário) e `flex` nas barras simples.
- `07-position`: sol, lugar do Brotinho e chão da capa com `position: absolute` dentro de `position: relative`.
- `08-box-shadow`: o Brotinho e o sol em pixel art com `box-shadow`, ampliados com `transform: scale`, e as bordas pixeladas.
- `09-gradientes`: scanlines na capa com `repeating-linear-gradient` e a grade de 32 px atrás do sprite com `linear-gradient`.
- `10-hover-e-foco`: `:hover` e `:focus-visible` nos links do sumário e no botão COMPRAR, com contorno de foco bem visível.
- `11-css-nesting`: o `style.css` reescrito com CSS nesting nativo, com o mesmo resultado visual.

## Navegadores

A página foi feita para telas de computador, a partir de 1280 px de largura. A versão para celular fica para depois.

A partir da etapa `11-css-nesting`, o `style.css` usa CSS nesting nativo, suportado no Chrome 120+, Firefox 117+ e Safari 17.2+. Em navegadores mais antigos, as regras aninhadas são ignoradas e a página perde parte do estilo.

## Créditos

Projeto educacional de Renan Ferreira. O Brotinho, sua equipe e seus testadores são fictícios. Não há imagens externas: toda a arte, incluindo o Brotinho e o sol, foi feita com CSS.

Fontes [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) e [Atkinson Hyperlegible](https://fonts.google.com/specimen/Atkinson+Hyperlegible), do Google Fonts, sob a licença SIL Open Font License.

## Licença

Código sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
