# aula_02
- Os elementos (marcações) do HTML são conhecidos como tags 
- As tags podem possuir somenteabertura ou a abertura/encerramento.

1. Principais tags
<h1></h1> até o <h6></h6> - Titulos.
<p></p> Parágrafos.
<a></a> Tag de link.
<img> -> Tag responsável por apresentar imagem.
<strong></strong> -> Tag semântica. Indica uma força na palavra /frase.
<em></em> -> Indica uma ênfase na palavra/frase.
<b></b> ->Coloca uma palavra/frase em negrito.
<i></i> -> Coloca uma palavra/frase em itálico.
<br> -> Realiza uma quebra de linha.NÃO É BEM VISTA!!!
<hr></hr> -> Cria uma linha na horizontal.
<div></div> -> Cria um bloco contendo outras tags.

2. Realizando a comunicação do CSS com o HTML.
- CSS Interno -> Fica no arquivo html e é separado pela tag <style>.
- CSS Externo -> É um arquivo separado ao arquivo HTML. Possui a extenção .CSS e é a forma mais recomendada.
- CSS Inline -> É utilizado exatemente na tag no HTML. Deve ser usado com CAUTELA.    

3. Estilizações básicas do CSS.
 - color: -> Irá coloca ruma cor no texto.
 - background: -> Irá colocar uma cor de preenchimento no fundo do elemento.
 - font-size: -> Irá alterar o tamanho da fonte.



 # AULA_03

 ## SELETORES NO CSS!
 =>È a forma como você irá chamar um determinado elemento do [HTML] no [CSS].
 link:css
 1. tag -> Basicamente, você chama a tag em sí para realizar a estilização.
 * Quando você chama diretamente a tag, cuidado para não estilizar todos os elementos que possuem aquela tag. 

2. #id -> Você cria um identificador único na tag do elemento [HTML] e chama esse identificador no [CSS].

3. .class -> Você cria um "apelido" na tag do elemento e esse "apelido" pode ser utilizado quantas vezes for necessário inclusive com outras tags diferentes.

## SISTEMA DE CORES!
1. nome da cor -> Especifíca o valor da cor em inglês.
2. hexadecimal -> Especifíca o valor da cor através de ua sequêcia alfa-numérica.
3. rgb -> Especifíca a cor través da intensidade do red[vermelho],green[verde] e blue[azul].
4. rgba -> São os mesmos valores do rgb,Porém com o valor do alpha[opacidade]. 


# AULA_04

1. <img> -> tag responsável por inserir uma imagem interna ou externa
- src -> É onde é inserido o caminho da imagem.
- alt -> É o texto alternativo que será exibido caso a imagem "quebre" e por questões de acesibilidade.
EX:<img src="Caminho da imagem" alt="descrição da imagem "> 

2. Listas 
<ul></ul> -> Informa que existirá itens e a posição desses itens não importa.(Lista não ordenada!)
<ol></ol> -> Informa que existirá itens e a posição desses itens importa.(Lista ordenada!) 
<li></li> -> Cada item da lista.(indepemdente da lista!)

3. tag de link 
<a></a> -> É utilizada para gerar um texto clicável.(link)
- href -> É uma propriedade onde voçê irá informar qual o caminho que o link irá enviar o usuário
EX:<a href="Caminho do link">Sobre</a>


## CSS
1. `font-family: Arial, Helvetica, sans-serif;`; -> Propriedade que altera a tipografia utilizada no elemento.

2. `padding` -> É o espaçamento interno de um conteúdo até a borda.

3. `margin` -> É o espaçamento externo entre a borda e o elemento 

4. border -> É o elemento.

5. text-align -> 