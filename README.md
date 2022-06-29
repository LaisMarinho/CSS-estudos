# CSS-estudos
Continuação dos estudos com HTML

Com o código HTML, dei continuidado para estilização com CSS

CSS: Cascading style Sheet

É uma linguagem de estilos.
Ela serve para estilizar os elementos de uma página "WEB" ou "APLICATIVO MOBILE".
É como se fosse o designer( a maquiagem/roupa que dá todo o estilo visual) do corpo da página com o HTML.

SINTAXE CSS:

Seletor { 
bloco de declarações(propriedade: valor;)
}
Para cada "BLOCO DE DECLARAÇÂO" existe as "PROPRIEDADES" e seus "VALORES"
Propriedade: atributo que será aplicado no HTML. Existe uma TAG que é que é a TAG <link> que faaz a ligação de um documento com po HTML, exemplo:


<head>
<link rel="stylesheet" href="minhapagina.css">
</head>

Para estilizar no CSS é necessário atribuir uma CLASS no código HTML, exemplo:

<p class="titulo">

E para editar tem que mencionar no código CSS, exemplo:

p.titulo {
color: red;
}

Diferente das CLASS que pode ser utilizada para vários elementos ao mesmo tempo, tem o ID que só pode ser utilizado para estilizar apenas um elemento no código HTML, exemplo:

<h1 id="titulo">
 E no CSS, ele é mencionado com "#", ao contrário do CLASS que é mencionado com ".", exemplos da diferença entre eles:
 
 PARA CLASS:
 .titulo {
 color: red;
 }
 
 PARA ID:
 #titulo{ 
 color: red;
 }
 
 
 PSEUDOCLASSES
 
 São palavras chaves para especificar o estado do elemento que vai ser utilizado, exemplo:
 
 (hover)
ao ser colocado no seletor, ela vai indicar que aquele estilo será aplicado quando o usuário passar o mouse por cima daquele elemento, exemplo:

button: hover {
color: blue;
}
PS* QUANDO PASSAR O MOUSE, O BOTÃO QUE NORMALMENTE É "PRETO" VAI FICAR "AZUL"

Exemplo de CSS:

body {
background-color: pink;
}
.titulo {
color: #B22222;
text-align: center;
font-family: verdana;
}
#título {
font-family: verdana;
font-size: 20px;
color: #CD5C5C;
text-align: center;
}
