# HTML - Ada tech

## A base da WEB

### Front-end
A parte visual da aplicação, ou seja, a parte a qual o usuário interage.

### Introdução ao HTML
- **HTML:** *HyperText Markup Language*
- **Hipertexto** é o termo que remete a um texto ao qual se agregam outros conjuntos de informação na forma de blocos de textos, palavras, imagens ou sons, cujo acesso se dá através de referências específicas, no meio digital denominadas hiperligações.
- Essas referências são o que chamamos de **links**.
- Na semiótica é comum considerar praticamente a web inteira como único hipertexto.

#### Markup
- Uma linguagem de marcação é uma linguagem que possuem símbolos especiais que indicam **metainformações.**
- Elas referem-se à forma, hierarquia, ordem e/ou semântica dos elementos da página.
- Atualmente está na versão 5 (2014).

#### Resumo
- Marcação -> **tags**
- **Tags** HTML:
    - Delimitadas por `<` e `>`
    - Usadas para descrever o **elemento** que será adicionado;
    - Exemplos de tags HTML:
        - `<button>`
        - `<p>`
        - Dentre outras

#### Elemtento HTML (tag)
- Geralmente contém três componentes:
    - Tag de abertura;
    - Conteúdo;
    - Tag de fechamento.

    `<p>This is a paragraph.</p>`\
        - < > - opening tag\
        - This a paragraph - Conteúdo\
        - </ > - closing tag

- Possui um tipo (botão, parágrafo, imagem, lista, tabela)
- Permitem que podem declarar outros elementos no seu interior

```
 <div>
 <p>Um parágrafo dentro de uma div</p>
 </div>
```

- Podem ter informações adicionais (atributos)

### Estrutura básica de um Documento HTML

- DOCTYPE
    - html (lang)
        - head
            - title
            - meta (charset)
        - body
            - Tags de conteúdo (h1 (1a6), p, button, div, a, table, span, etc)

####  Tabela principais tags
| Tag            | Descrição                                                                                      |
|----------------|------------------------------------------------------------------------------------------------|
| `<!DOCTYPE>`   | Declara o tipo do documento e a versão do HTML.                                                |
| `<html>`       | Define o documento como um arquivo HTML.                                                       |
| `<head>`       | Contém metadados/informações sobre o documento.                                                |
| `<title>`      | Define o título do documento, mostrado na barra de título do navegador ou na aba da página.    |
| `<meta>`       | Define metadados sobre o documento, como charset, autor, descrição, etc.                       |
| `<link>`       | Define a relação entre o documento atual e um recurso externo (como uma folha de estilo).      |
| `<style>`      | Contém regras de estilo CSS para o documento.                                                  |
| `<script>`     | Define scripts de programação, geralmente em JavaScript.                                        |
| `<body>`       | Define o corpo do documento, onde todo o conteúdo visível é colocado.                          |
| `<header>`     | Define um cabeçalho para um documento ou uma seção.                                             |
| `<nav>`        | Define um conjunto de links de navegação.                                                      |
| `<section>`    | Define uma seção no documento.                                                                 |
| `<article>`    | Define um conteúdo independente e auto-contido.                                                |
| `<aside>`      | Define conteúdo à parte do conteúdo principal (como uma barra lateral).                        |
| `<footer>`     | Define um rodapé para o documento ou uma seção.                                                |
| `<h1>` - `<h6>`| Define cabeçalhos, sendo `<h1>` o mais importante e `<h6>` o menos importante.                 |
| `<p>`          | Define um parágrafo.                                                                           |
| `<a>`          | Define um hyperlink.                                                                           |
| `<ul>`         | Define uma lista não ordenada.                                                                 |
| `<ol>`         | Define uma lista ordenada.                                                                     |
| `<li>`         | Define um item de lista.                                                                       |
| `<div>`        | Define uma divisão ou seção no documento.                                                      |
| `<span>`       | Define uma seção em linha usada para agrupar elementos.                                         |
| `<img>`        | Define uma imagem.                                                                             |
| `<figure>`     | Define uma figura, contendo uma imagem e uma legenda.                                           |
| `<figcaption>` | Define uma legenda para uma figura.                                                            |
| `<table>`      | Define uma tabela.                                                                             |
| `<tr>`         | Define uma linha de tabela.                                                                    |
| `<th>`         | Define uma célula de cabeçalho em uma tabela.                                                  |
| `<td>`         | Define uma célula padrão em uma tabela.                                                        |
| `<form>`       | Define um formulário HTML para entrada do usuário.                                             |
| `<input>`      | Define um controle de entrada em um formulário.                                                |
| `<button>`     | Define um botão clicável.                                                                      |
| `<label>`      | Define um rótulo para um elemento `<input>`.                                                   |
| `<textarea>`   | Define uma área de texto de várias linhas.                                                     |
| `<select>`     | Define uma lista suspensa (dropdown).                                                          |
| `<option>`     | Define uma opção em uma lista suspensa.                                                        |
| `<video>`      | Define um vídeo ou filme.                                                                      |
| `<audio>`      | Define som ou conteúdo de áudio.                                                               |
| `<source>`     | Define múltiplos recursos de mídia para elementos `<video>` e `<audio>`.                       |
| `<canvas>`     | Define uma área de desenho para gráficos desenhados via scripting (geralmente JavaScript).      |
| `<svg>`        | Define gráficos vetoriais escaláveis.                                                          |

