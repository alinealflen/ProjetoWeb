# Tags Semanticas

As tags semanticas em HTML tem como objetivo deixar o conteudo das paginas da web mais claros e compreensiveis para o programador e para sua equipe, assim como para as *Engines* dos navegadores onde estao sendo exibidas.

* ### As principais tags semanticas do HTML5 sao as seguintes:
  * `<header>`
  * `<section>`
  * `<article>`
  * `<nav>`
  * `<aside>`
  * `<main>`
  * `<figure>`
  * `<footer>`
  * `<a>`
  * `<em>`
  * `<strong>`
  * `<cite>`
  * `<q>`
  * `<time>`
  
  
  Abaixo descreveremos cada uma delas para melhor entendimento:
  
### Header
Essa tag é utilizada para representar o cabeçalho ou uma seção de um documento HTML, contendo informações tais como títulos, listas de navegação, ou até mesmo imagens.
Diferentemente da tag HEAD a HEADER pode ser declarada mais de uma vez por página.
Exemplo de uso do header em uma página HTML:
       <br> `<header>` 
          <br>`<h1>Título da página</h1>`<br>
          `<h2>Subtítulo da página</h2>`
        <br>`</header>`

### Section
Essa tag representa uma seção dentro de um documento HTML que geralmente contém um título, ela é utilizada para escrever seções ou tópicos de um documento. Exemplo de uso da tag section em uma página HTML:
<br>`<section>`
    <br>`<h3>Seção 1</h3>`  
   <br> `<p>Aqui vai uma descrição sobre o texto </p>`
 <br>`</section>`
 
 ### Article
Essa tag é utilizada para declarar um conteúdo que não precise de outro para fazer sentido em um documento HTML. É recomendado identificar cada tag article com título. Exemplo
<br>`<article>`
 <br>   `<h3>Título do artigo 1</h3>`
   <br>   `<p>Aqui vai uma breve descrição...</p>`
<br>`</article> `             
<br>`<article>`
 <br>   `<h3>Título do artigo 2</h3>`
  <br>    `<p>Aqui vai uma breve descrição...</p>`
<br>`</article>`

### Nav
A tag é utilizada para quando precisarmos representar agrupamentos de links, criados com os elementos `<ul>, <li> e <a>`.

### Aside
Usada para quando precisamos criar um conteúdo de apoio ao conteúdo principal.Seria um link de uma sugestão de leitura complementar por exemplo.

### Main
A tag main represente o conteúdo principal e de maior valor dentro da página HTML. Uma página HTML bem construída deve possuir apenas um conteúdo principal, ou seja, uma tag main.

### Figure
Essa tag é uma marcação para adicionarmos uma figura em um documento HTML, e figcaption serve para adicionarmos a descrição da figura.

 ### Footer
O elemento `<footer>` representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.

### A
A principal função do elemento `<a>` é descrever um link, conectando os diversos documentos de um site e permitindo a navegação por esse conteúdo. Normalmente esses documentos estão relacionados por compartilharem um assunto em comum.

### em
O elemento `<em>` é utilizado quando desejamos enfatizar um trecho ou palavra no texto, indicando que ela contribui de forma mais relevante para o sentido/compreensão do conteúdo.

### Strong
O elemento `<strong>` também é utilizado para destacar uma parte do texto. Sua principal diferença em relação ao elemento `<em>` é que `<em>` pode alterar o propósito de uma frase, como vimos anteriormente.

### Cite e Q
O elemento `<cite>` é utilizado para declarar que naquele trecho há uma citação, isto é, um trecho de texto que não foi escrito pelo autor do conteúdo. Normalmente utiliza-se o `<cite>` em conjunto com o elemento `<q>`, responsável por apresentar o conteúdo retirado de outra fonte.

### Time
O elemento `<time>` é utilizado para representar datas. Assim, caso seja necessário informar a data em que um conteúdo foi escrito, podemos declarar a tag `<time>` e acrescentar a ela o atributo datetime para escrever a data de forma padronizada.


