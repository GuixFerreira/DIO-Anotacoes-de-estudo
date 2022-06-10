# Introdução de Java Script

- Interpretada: A compilação e feita em tempo real e instantaneamente .

- Baseada em Protótipos: Tem uma base da maioria das estruturas de dados.

- Multiparadigma: É usado em mais de um paradigma.

- Comumente utilizada em aplicações web client-side: É uma linguagem voltada a interação do usuário.

- Segue o padrão ECMAScript: Segue um padrão de linguagens.



#### Inserir Java Script para HTML

< script src="Caminho para o arquivo com JS">< /script>



 #### Comentário no Arquivo

- // = Comentário de uma Linha.

- /* = Comentário de varias linhas, necessário adicionar */ no fim do comentário. 

###### Atalhos

- Ctrl + / = Comentário de Linha



#### Variável (var)

Usa-se variáveis como nomes simbólicos para os valores em sua aplicação.

Escopo global e local, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null.

 

#### Constante (const)

Uma constante é criada como uma variável inicializada, de escopo local de bloco, e seu valor é permanente/para leitura, não podendo ser alterado. 



#### Let

Escopo local de bloco, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null.



#### Tipos de Variáveis

###### Primitivos

- Boolean: Recebem valores que são verdadeiros ou falsos.

- Null: Quando você que que o valar não exista.
- Undefined: O valor é indefinido.
- Number: Recebe um numero.
- String: Recebe um nome qualquer/texto.

###### Não primitivos

- Array
- Object



- Function



#### Escopo 

Define a limitação e visibilidade de um bloco de código.

- Escopo global: Quando a variável é declarada fora de qualquer bloco, sua visibilidade fica disponível em todo o código.
- Escopo local: Quando a variável é declarada dentro de um bloco, sua visibilidade pode ficar disponível ou não.



#### Atribuição 

O sinal de igualdade "=" significa atribuição.

- var nome = "meu nome";

A variável nome acima recebe o valor "meu nome".



#### Comparação

Para fazer uma comparação usa-se dois sinais de igualdade "==".

- "0" == 0; 		// "0" tem o valor igual a 0?

Ira sempre retornar um valor booleano, no caso acima retorna "true".



#### Comparação Idêntica

Comparação de valor e tipo usamos "===".

- "0" === 0; 		// "0" tem o valor e tipo idêntico a 0?

Ira sempre retornar um valor booleano, no caso acima retorna "false" pois esta comparando uma string com um numero.

###### Outros tambem usados

- != :	     Diferente;
- !== :       Valor e tipos diferentes;
- " < " :     Menor que;
- " > " :     Maior que;
- " <= ":    Menor ou Igual;
- " >= ":    Maior que;



#### Operadores aritméticos
São tipos de operadores matemáticos com valor numérico:

+ "+":      adição;
+ "++":    incrementar;
+ "-":       subtração;
+ "--":      decrementar;
+ ''*":      multiplicação;
+  "/":      divisão real;
+ "%":     divisão inteira/modulo;
+  "**":   potenciação;



#### Operadores lógicos

São tipos de operadores que consultam valores lógicos:

- && :    “e” – considera que todos os valores sejam true;
- ||:      “ou” – considera que qualquer valor seja true;
- ! :        “não” – inverte o valor de true para false ou vice-versa;



#### Array

Arrays são um tipo de lista, ou matriz de variáveis, onde cada variável possui um índice. Os valores podem ser de vários tipos.

O array deve ser declarado entre colchetes “[]”, e podem guardar
qualquer valor dentro de seus índices: inclusive outros arrays.

-  let array = ['string', 1, true, false, [‘array1], [‘array2’]...]

- O índice só é acessado por um número inteiro.

- 0 é o primeiro índice. 

- Cada índice é separado por vírgula.



#### Manipulando Arrays

Ao ser declarado, o Array traz consigo uma série de métodos para manipulá-lo.

-  forEach() – itera um array;
-  push() – add item no final do array;
- pop() – remove item no final do array;
- shift() – remove item no início do array;
- unshift() – add item no início do array;
- indexOf() – retorna o índice de um valor;
- splice() – remove ou substitui um item pelo índice
- slice() – retorna uma parte de um array existente;



#### Objetos

Dados que possuem propriedades e valores que definem suas características. 

Deve ser declarado entre chaves “{}”.

Uma xícara, tem cor azul, pode ter vários tamanhos e funções. Pode ser declarada assim:

​	var xicara = {
​		cor: ‘azul’,
​		tamanho: ‘p’,
​		funcao: tomarCafe()
​	}



#### Manipulando objetos

As propriedades de objetos podem ser atribuídas à variáveis, facilitando a manipulação do objeto. Chamamos isso de desestruturação. 

- var xicara = {cor: ‘azul’, tamanho: ‘p’, funcao: tomarCafe()}



- var cor = xicara.cor;
  var tamanho = xicara.tamanho;
  var funcao = tomarCafe();



- var { cor, tamanho, funcao } = xicara;



#### Estruturas condicionais

São instruções para realizar determinadas tarefas a partir de uma condição, seja de decisão ou repetição.



##### If

“if” é usado para estabelecer uma condição:

​	var jogador1 = 0;
​	var jogador2 = 0;

​	if (jogador1 > 0) {
​			console.log(‘jogador1 marcou ponto’);
​	}



##### Else

No caso de a condição "if" não ser atendida podemos usar o “else” :

​	var jogador1 = 1;
​	var jogador2 = 0;

​	if (jogador1 > 0) {
​			console.log(‘jogador1 marcou ponto’);
​	} 

​	else {
​			console.log(‘ninguém marcou ponto’);

​	}



##### Else If

Caso haja mais de uma condição usamos o “else if“.

​	var jogador1 = 1;
​	var jogador2 = 0;

​	if (jogador1 > 0) {
​			console.log(‘jogador1 marcou ponto’);
​	} 

​	else if (jogador2 > 0) {
​			console.log(‘jogador2 marcou ponto’);
​	} 

​	else {
​			console.log(‘ninguém marcou ponto);
​	}



##### If ternário

Podemos também fazer uma verificação em uma única linha usando o “if” ternário:

Ex.: [condição] ? [instrução1] : [instrução2];

jogador1 > 0 ? console.log(‘marcou ponto’) : console.log(‘não marcou ponto”);

// lembre de usar a interrogação “?” e dois pontos “:”



##### Switch/Case

O “switch/case” funciona como uma estrutura condicional também:

​	switch (${expressao}) {
​			case 1:
​				${instrucao};
​				break;
​			case 2:
​				${instrução};
​				break;

​			default:

​				retorna quando nenhuma outro caso aconteça 

​		}



#### Laços de repetição

São estruturas condicionais que repetem uma instrução até atingir uma determinada condição.

- For;
- For/in;
- For/of;
- While;
- Do/while;



##### For

Funciona como uma repetição de instrução até que a condição
seja falsa:

- for ([expressaoInicial]; [condicao]; [incremento]) {

​		declaracao 

​		}



​	var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

​	for (let i = 0; i < array.length; i++) {
​		console.log(i);
​	}



##### For/in

Funciona como uma repetição a partir de uma propriedade:

- for ([indice] in [objeto ou array]) {

​		declaracao 

​		}



​	var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

​	for (i in array) {
​		console.log(i);
​	}



##### For/of

Funciona como uma repetição a partir de um valor:

- for ([indice] of [array]) {

  declaracao 

  }

  

​	var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

​	for (i of array) {
​		console.log(i);

​	}

O For/of não funciona com objetos pois as propriedades variam, diferentes do índice em um array que sempre serão números inteiros.

Mas da para fazer com:

- for (i of object.propriedade) {console.log(i);}

Porém cada caractere dentro do valor será Impresso em linhas separadas.



##### While

Executa uma instrução “enquanto” determinada condição for verdadeira, a verificação é feita antes da execução;

​	var a = 0;
​	while (a < 10) {
​		a++;
​		console.log(a);
​	}

// como ler: enquanto a variável a for menor que 10 ela vai receber mais um e imprimir no console.



##### Do/while

Executa uma instrução “até que” determinada condição seja falsa, a verificação é feita depois da execução;

​	var a = 0;
​	do {
​		a++;
​		console.log(a);
​	} while (a < 10)

// como ler: a variável a vai receber mais um e imprimindo console até que seu valor chegue a 10



#### Funções

São blocos de comandos e instruções para a execução de determinadas tarefas.

​	function nomeDaFuncao() {
​		instrucao;
​	}

​	nomeDaFuncao();



Geralmente se utiliza a palavra reservada “function” seguida de parênteses “()” e chaves “{}”.

​	function funcao() {
​		console.log(“mensagem”);
​	}

​	funcao();



- () – indica que é um objeto do tipo function;
- {} – indica que é um bloco de instrução;



##### Funções com parâmetros
As funções podem receber em sua declaração, parâmetros, que servem como variáveis, onde sua atribuição pode ser feita durante a chamada da função.

​	function nomeDaFuncao(parametro) {
​		instrucao;
​	}

​	nomeDaFuncao(valorDoParametro);



​	function mensagem(primeiro, segundo) {
​		console.log(primeiro, segundo);
​	}

​	nomeDaFuncao(“Tudo certo”, "ok");



##### Função Anônima

Uma variavel pode armazenar uma função.

​	const soma = function (a, b) {

​		return a + b;

​	}

​	soma(1,2)  // 3

​	soma(5,4)  // 9
