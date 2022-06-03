# Introdução ao CSS3

Você cria regras de estilo para elementos ou grupo de elementos.



#### Seletores

São elementos HTML.



#### Declarações

Ficam dentro de um par de chaves {} após os Seletores.

São formados por uma propriedade e um valor.



#### ID x Classe

Representam qualquer tipo de elemento.



< header id="header" class="header" >< /header>

- É precedida por um #
- Só pode ser usado uma vez na pagina.

< header class="header" >< /header > 

- É precedida por um ponto



#### Box model

- Margin (Margem): espaçamento entre elementos.



- Border (Borda): 

​	Circundam o padding e o conteudo, e pode alterar sua largura e cor. É possível se alterar sua largura(width), cor(color) e estilo(style).

​	Estilos: solid(Solido), dotted(Pontilhado), dashed(Tracejado).



- Padding:

​	Espaço entre a Borda e o Conteúdo. Podendo atribuir um tamanho para cada lado.



- Content (Conteúdo).

 

#### Background

Uma propriedade que é um atalho para outras propriedades, podendo mudar cor de fundo, adicionar imagem e alterar seu posicionamento, entre outras coisas.

###### Background-color

Background-color: Cor desejada

Background-color: Codigo hexadecimal da cor



#### Texto

​	Alterar a fonte do texto usa-se font-family junto com a fonte que quer adicionar.

- font-family: Verdana, Arial;



​	Para alterar o tamanho da fonte, se usa o font-size.

- font-size: 18px;



​	O font-style altera o aparecncia do texto.

- font-style: Normal;
- font-style: Italic;



​	O font-weight altera o peso do texto.

- font-weight: Normal;
- font-weight: Bold(Negrito); 



​	Text-transform alterna o texto em maiúscula e minúsculo.

- text-transform: uppercase (texto em caixa alta);
- text-transform: lowercase (texto em caixa baixa);
- text-transform: capitalizer (Primeira letra de cada parágrafo em maiúscula);



​	Text-decoration da destaque no texto.

- text-decoration: underline (Linha a baixo da palavra);
- text-decoration: overline (Em cima da palavra);
- text-decoration: line-through (Ao centro da palavra);



#### Listas

​	Mudar o marcador das listas ordenadas e não ordenadas usa-se o list-style-typer.

- list-style-typer: square (Muda o marcador para um quadrado em listas não ordenadas);
- list-style-typer: upper-roman (Muda o numero de uma lista ordena para um numero romano);
- list-style-typer: " \1F44D " (Muda o marcador por um símbolo, o codigo de exemplo e de um joinha );
- list-style-typer: none (Remove os marcadores);



​	Para usar uma imagem como marcador.

- list-style-image: url("url da imagem

#### Inserir CSS em HTML

< link rel = "stylesheet" hrel = "caminho para o arquivo css" />
