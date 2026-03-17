# Ex02 - Introdução ao DOM

## Descrição
Exercício de introdução ao DOM (Document Object Model) utilizando JavaScript para acessar e modificar elementos da página.

## Objetivo
Praticar a manipulação de elementos HTML através do JavaScript.

## Conceitos aplicados
- Acesso ao documento com `window.document`
- Seleção de elementos com `getElementsByTagName`
- Manipulação de conteúdo com `innerText`
- Alteração de estilos com `.style`

## O que o código faz
- Seleciona o corpo da página (`body`)
- Seleciona o primeiro parágrafo (`<p>`)
- Exibe o conteúdo do parágrafo na tela
- Altera a cor do texto do parágrafo
- Modifica a cor de fundo da página

## Trecho importante

```javascript
var p1 = window.document.getElementsByTagName('p')[0]
window.document.write('Está escrito assim: ' + p1.innerText)
