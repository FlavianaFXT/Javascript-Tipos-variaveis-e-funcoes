# Javascript-Tipos-variaveis-e-funcoes
Repositorio destinado ao curso de mesmo nome realizado com a Alura, em parceria com a Reprograma.

Profs: Juliana Amoasei e Leonardo Sartorello


# APRENDIZADOS DESSE CURSO 

o computador consegue apenas armazenar valores em alguns tipos de variáveis, como números, texto e booleanos.

Como declarar uma variável numérica, com tipo number, e associar um valor a ela, podendo ser um inteiro ou um valor de ponto flutuante.

Como declarar uma variável de texto, conhecida como string, e colocar uma frase, número, pontuação ou uma mistura de todos esses dentro dela.

Como declarar uma variável booleana e definir seu valor como verdadeiro (true) ou falso (false).

Onde as booleanas mais aparecem, como resultados de comparações com === ou outros operadores de comparação como >=.



# 1. Tipos Primitivos

## O Visual Studio Code


Para este curso, vamos utilizar o editor de código Visual Studio Code, da Microsoft. É um dos editores mais utilizados e conta com várias ferramentas para facilitar o dia a dia do desenvolvimento, além do terminal integrado que vamos usar para executar nossos códigos durante o curso.

Caso você não tenha familiaridade com o VSC e suas ferramentas, preparamos estes materiais para começarmos:

VSCode: dicas e truques ([vídeo](https://www.youtube.com/watch?v=C3o9KwOHeCk&ab_channel=AluraCursosOnline)) que explica passo a passo várias ferramentas que o VSC usa para nos ajudar a escrever código melhor;
Como utilizar o terminal integrado do VSC ([artigo](https://www.alura.com.br/artigos/como-utilizar-terminal-integrado-visual-studio-code?_gl=1*1thiizd*_ga*MTAyMjIzNjI2OC4xNzAxODc3NTU5*_ga_1EPWSW3PCS*MTcwOTczMTQ4NS4zNS4xLjE3MDk3MzI3NjEuMC4wLjA.*_fplc*UEg3RkVXQTFWQXpOU3BGdUdoWkpOWDR6Qmk2QkJFbmR4RXpEdjl1OVh6Qm1DZCUyRnRwVDJ3UzZ4UDZja0NwWjVJWEhta3JaUUZuanZHcDRXa3UwUXNOJTJCeGtsME5Ca0g0dWszU1pFRFIlMkJITVU0MHNFZ2VGR3E1JTJCanlkZU5nYXclM0QlM0Q.)), focado especialmente no uso do terminal;
Trabalhando com caminhos e pastas no terminal ([artigo](https://www.alura.com.br/artigos/trabalhando-com-caminhos-e-pastas-no-terminal?_gl=1*1jc8r5w*_ga*MTAyMjIzNjI2OC4xNzAxODc3NTU5*_ga_1EPWSW3PCS*MTcwOTczMTQ4NS4zNS4xLjE3MDk3MzI4NDYuMC4wLjA.*_fplc*UEg3RkVXQTFWQXpOU3BGdUdoWkpOWDR6Qmk2QkJFbmR4RXpEdjl1OVh6Qm1DZCUyRnRwVDJ3UzZ4UDZja0NwWjVJWEhta3JaUUZuanZHcDRXa3UwUXNOJTJCeGtsME5Ca0g0dWszU1pFRFIlMkJITVU0MHNFZ2VGR3E1JTJCanlkZU5nYXclM0QlM0Q.)) para entender melhor como funciona a hierarquia de pastas e como acessar nossos arquivos via terminal.

## Tipo Number

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/31be6dab-7523-4f96-80ee-a08fde0046f9)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/0d434b09-fe73-43c4-8306-303fbfe29dae)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/a2f2fc38-9dfa-4f52-99f2-fda5be0b86e9)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/dddc27f9-da94-4a09-be9b-d2c0bfe66aeb)


Nesta primeira aula, vamos revisar alguns dos pontos mais fundamentais da linguagem que estamos estudando: JavaScript. Vamos começar pelos tipos de dados.

Léo, poderia nos explicar por que é importante entender quais são os tipos de dados que cada linguagem consegue manipular, uma vez que isso também pode variar de linguagem para linguagem?

A Importância dos Tipos de Dados nas Linguagens de Programação
Leonardo: Nosso computador só consegue armazenar os dados que vamos introduzir nele dentro de determinados tipos. No JavaScript, temos três tipos principais: os primitivos, que utilizaremos mais durante as aulas.

Estes são os números (para armazenar numerais), as strings (para armazenar textos e caracteres) e os booleanos (para armazenar verdadeiro ou falso).

Vamos começar hoje trabalhando com números, pode ser?

Juliana: Certo.

Tipos primitivos
Tipo Number
Arquivo type-number.js no repositório do GitHub

Juliana: Vamos começar a trabalhar com o tipo number. Esses três tipos principais, os chamamos de tipos primitivos. Haverá mais material sobre eles disponível neste curso. O JavaScript trabalha com os números de uma maneira própria, que pode diferir de outras linguagens de programação.

Vamos ao arquivo type-number.js e adicionar um comentário "tipo number".

type-number.js

// tipo Number
COPIAR CÓDIGO
Quando um programa precisa armazenar um valor para usar futuramente, já sabemos que usamos variáveis para isso. Vamos começar criando uma constante. Usamos constantes e variáveis, mas vamos entender mais sobre isso para esclarecer quaisquer dúvidas mais adiante no curso.

Toda vez que precisamos armazenar um número, ou qualquer tipo de dado, seja texto ou um tipo de dado mais complexo, guardamos o número, ou o dado, em uma variável. Portanto, criamos uma constante chamada meuNumero e atribuímos a ela o valor 3, simplesmente escrevendo = 3;.

type-number.js

// tipo Number

const meuNumero = 3;
COPIAR CÓDIGO
A variável meuNumero é um nome que usamos para identificar um espaço na memória que armazena um dado específico. Neste caso, um dado do tipo número, cujo valor é 3.

É fundamental que o JavaScript consiga determinar qual é o tipo de dado para poder manipulá-lo. Por exemplo, para executar cálculos matemáticos, o dado armazenado na variável precisa ser um número.

Por exemplo, iremos criar uma constante chamada primeiroNumero e atribuir o valor 1 a ela, e outra constante segundoNumero com o valor 2.

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;
COPIAR CÓDIGO
Criamos duas variáveis, ambas do tipo de dado número. Uma guarda o valor 1, a outra guarda o valor 2. Agora, podemos executar operações matemáticas com esses números, como somar ou multiplicar.

Assim, vamos criar uma constante operacaoMatematica e somar os valores dessas variáveis.

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;

const operacaoMatematica = primeiroNumero + segundoNumero;
COPIAR CÓDIGO
Por que conseguimos fazer isso neste caso? Porque os dados que estamos armazenando nas variáveis são do tipo Number, e o JavaScript pode realizar uma operação com eles.

Leonardo: Legal, Ju, criamos essa variável e realizou a operação de adicionar primeiroNumero a segundoNumero. Pode mostrar para nós o resultado dessa operação?

Juliana: Claro. O melhor é testarmos o que estamos fazendo. Usaremos um comando do JavaScript chamado console.log. Mais adiante neste curso, vamos aprender mais sobre ele.

Por enquanto, vamos usá-lo para solicitar que console.log exiba no terminal o dado armazenado na constante operacaoMatematica. Esperamos que o dado seja o resultado da soma entre o valor armazenado em primeiroNumero e segundoNumero. No caso, seria 3.

Se tudo estiver correto, isso deverá imprimir o valor 3 no console.

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;

const operacaoMatematica = primeiroNumero + segundoNumero;

console.log(operacaoMatematica)
COPIAR CÓDIGO
Vamos executar.

Já me encontro na pasta correta, onde está o arquivo com o qual estou trabalhando. Eu criei um arquivo chamado type-number, que é o que nós estamos utilizando agora.

E executaremos isto com o comando node e o nome do arquivo no JavaScript. Nós iremos entender um pouco mais sobre o significado disso no decorrer das aulas, procurando manter todas as pessoas na mesma página. Por enquanto, vamos apenas executar o comando.

node type-number.js
COPIAR CÓDIGO
E foi exibido no console o número 3, que era o que nós esperávamos.

3

Seria possível alterar, por exemplo, essa constante matemática para ser o resultado de uma multiplicação? Assim sendo, inseriremos um operador de multiplicação. Trata-se de um asterisco, ele representa o operador de multiplicação.

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;

const operacaoMatematica = primeiroNumero * segundoNumero;

console.log(operacaoMatematica)
COPIAR CÓDIGO
E rodamos novamente no terminal:

node type-number.js
COPIAR CÓDIGO
Obtemos, como retorno:

2

Sim, é possível. Observamos o resultado que tem que ser 2, que é 1 vezes 2.

Estamos esquecendo algo sobre essas primeiras informações, Léo? Sobre números?

Leonardo: Sobre essas primeiras informações, não. Também é importante ressaltar que podemos usar outros operadores, como, por exemplo, a barra para realizar divisão e o símbolo menos para subtração.

Juliana: Ótimo, então nós também podemos testar. Portanto, quando queremos realizar uma divisão, nós utilizamos a barra. Então, 1 dividido por 2 vai resultar em 0.5 e o hífen é o operador de subtração, que resultará em menos 1, neste caso.

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;

const operacaoMatematica = primeiroNumero / segundoNumero;

console.log(operacaoMatematica)
COPIAR CÓDIGO
E rodamos o comando node novamente no terminal:

node type-number.js
COPIAR CÓDIGO
Obtemos, como retorno:

0.5

Alteramos para a subtração no código:

type-number.js

// tipo Number

const meuNumero = 3;

const primeiroNumero = 1;
const segundoNumero = 2;

const operacaoMatematica = primeiroNumero - segundoNumero;

console.log(operacaoMatematica)
COPIAR CÓDIGO
Rodamos o comando node mais uma vez e obtemos como retorno no terminal:

-1

Podemos operar com números negativos, positivos e assim por diante. Normalmente, em linguagem de programação, não estamos restritos a números inteiros, mas podemos trabalhar com números que costumamos chamar de decimais em nosso cotidiano, que têm um ponto seguido de outros números.

Você consegue explicar um pouco mais para nós sobre esses números decimais no JavaScript, Léo?

Leonardo: Claro.

Ponto Flutuante no JavaScript
Leonardo: Em computação chamamos esse tipo de número de ponto flutuante. Nós veremos o porquê desse nome em breve. Mas no JavaScript, podem ser declarados da mesma forma que declaramos os números inteiros e, na hora de associar um valor a ele, podemos apenas inserir o ponto seguido pelo valor desejado.

Então, por exemplo, colocamos 3.3 em uma constante chamada numeroPontoFlutuante.

type-number.js

// código omitido

// ponto flutuante

const numeroPontoFlutuante = 3.3;
COPIAR CÓDIGO
Nós temos agora um número de ponto flutuante com valor 3.3. Se quisermos, nós também podemos criar outra variável de ponto flutuante para demonstrar melhor, a qual colocaremos, por exemplo, 0.5. Mas nós podemos declará-la apenas como .5.

O JavaScript também aceita isto.

type-number.js

// código omitido

// ponto flutuante

const numeroPontoFlutuante = 3.3;
const pontoFlutuanteSemZero = .5;
COPIAR CÓDIGO
Juliana: Então, se criarmos uma variável apenas como .5, não precisamos declarar o zero?

Leonardo: Sim, é uma forma que acaba se tornando mais prática para economizarmos teclas no momento da digitação. Isso acontece bastante no dia a dia.

Juliana: Mais uma vez, podemos realizar cálculos, comumente, com os números de ponto flutuante ou números inteiros. Podemos mesclar os dois também, certo?

Leonardo: Sim, podemos. Com todas as contas que fizemos, podemos replicar agora utilizando os mesmos operadores matemáticos: soma, subtração, multiplicação, divisão.

Juliana: Iremos somar o nosso primeiro número dividido pelo número com ponto flutuante e solicitar que o console.log exiba para nós o resultado desta nova operação na qual estou salvando o resultado. Para isso, criamos uma variável chamada novaOperacao.

type-number.js

// código omitido

// ponto flutuante

const numeroPontoFlutuante = 3.3;
const pontoFlutuanteSemZero = .5;

const novaOperacao = primeiroNumero / numeroPontoFlutuante;

console.log(novaOperacao)
COPIAR CÓDIGO
Limpamos o console e rodamos o comando node. E ele retornou um número com várias casas decimais, que chamamos de ponto flutuante.

0.30303030303030304

E o JavaScript também possui algumas ferramentas prontas para conseguirmos truncar o número. Existe muitos dígitos após a vírgula e desejamos truncar apenas para dois, conseguimos fazer isso também. O JavaScript tem várias ferramentas prontas de operações matemáticas das mais simples até as um pouco mais complexas.

Vamos deixar um material extra para vocês.

Not a number no JavsScript
Juliana: Uma coisa muito interessante que visualizamos quando estamos realizando nossas primeiras operações com números no JavaScript é o que acontece quando o JavaScript tenta fazer operações com números, mas ele não consegue. Que é o tal do Not a number (Não é um número, em português).

Leonardo: Sim. Isso às vezes acontece, principalmente quando tentamos multiplicar duas coisas e alguma delas ou as duas não são realmente um número. Nesse caso, em vez de retornar um erro, o JavaScript retorna NaN(NOT A NUMBER).

Juliana: Vamos inserir uma seção sobre esse assunto no código com um comentário:

type-number.js

// código omitido

// NaN -> Not A Number (não é um número)
COPIAR CÓDIGO
Por exemplo, vamos supor que tenhamos uma primeira constante chamada primeiroNumero, com valor igual a 1. Teoricamente, conseguimos fazer qualquer operação matemática com ela. Mas se tivermos uma segunda constante, Alura, que de repente não é um número, mas sim uma string com o texto "ALURA".

type-number.js

// código omitido

// NaN -> Not A Number (não é um número)

const alura = "Alura";
COPIAR CÓDIGO
O que acha que acontece se tentarmos criar uma operação matemática, como multiplicar alura por primeiroNumero? Conseguimos imaginar o que vai acontecer?

Não dá para fazer isso, certo? Não conseguimos, e, teoricamente, o JavaScript também não.

Quando pedimos para o console exibir o resultado de alura, multiplicado pela nossa variável primeiroNumero, o que acontece?

type-number.js

// código omitido

// NaN -> Not A Number (não é um número)

const alura = "Alura";
console.log(alura * primeiroNumero)
COPIAR CÓDIGO
Vejamos. Após limpar o terminal e rodar o código novamente, obtemos NnN, referente a Not a Number (Não é um número).

NaN

Isso significa que o JavaScript tentou realizar uma operação matemática, mas não conseguiu retornar o resultado dessa operação como um número.

Portanto, sempre que estivermos fazendo qualquer operação matemática e visualizarmos NaN, significa que alguma das partes dessa conta não está sendo reconhecida como um número.

É uma situação que reforça a importância de conhecermos os tipos de dados em JavaScript.

Conclusão
Juliana: Vamos continuar nosso estudo revisitando cada um desses pontos, acrescentando mais conhecimento sobre tipos, números e NaN.


## Para saber mais: Mais sobre números


Programas funcionam manipulando valores, como o número 3.14 ou o texto Juliana e Leonardo. Os tipos de valores que podem ser representados e manipulados em uma linguagem de programação são conhecidos como tipos, e uma das características mais fundamentais de uma linguagem de programação é o conjunto de tipos que ela suporta.

Variáveis
Quando um programa precisa reter um valor para uso futuro, ele atribui o valor a (ou “armazena” o dado em) uma variável. As variáveis têm nomes e permitem o uso desses nomes em nossos programas para se referir a valores. A maneira como as variáveis funcionam é outra característica fundamental de qualquer linguagem de programação.

Os tipos de JavaScript podem ser divididos em duas categorias: tipos primitivos e tipos de objetos. Os tipos primitivos do JavaScript incluem números, palavras ou texto (conhecidas como strings) e valores booleanos (conhecidos como booleanos).

Tipos numéricos
Como vimos em aula, podemos armazenar números de diferentes formas:

const idade = 28
const pi = 3.14COPIAR CÓDIGO
Dica: podemos utilizar o número PI através do código Math.PI.

O ponto flutuante pode ter um ponto decimal; eles usam a sintaxe tradicional para números reais. Um valor real é representado como a parte integral do número, seguido por um ponto decimal e a parte fracionária do número.

Pontos flutuantes também podem ser representados usando notação exponencial: um número real seguido pela letra e (ou E), seguido por um sinal opcional de mais (+) ou menos (-), e por um expoente inteiro. Essa notação representa o número real multiplicado por 10 à potência do expoente.

Divisão por zero não é um erro em JavaScript: ele simplesmente retorna “Infinity”. No entanto, há uma exceção: zero dividido por zero não tem um valor bem definido e o resultado dessa operação é o valor especial não numérico NaN.

var a = 10
var b = 0
console.log(a/b) // InfinityCOPIAR CÓDIGO
var a = 0
var b = 0
console.log(a/b) // NaNCOPIAR CÓDIGO
Links
[Como formatar número com JavaScript](https://www.alura.com.br/artigos/formatando-numeros-no-javascript?_gl=1*1j0vrgf*_ga*MTAyMjIzNjI2OC4xNzAxODc3NTU5*_ga_1EPWSW3PCS*MTcwOTczMTQ4NS4zNS4xLjE3MDk3MzM0NTAuMC4wLjA.*_fplc*UEg3RkVXQTFWQXpOU3BGdUdoWkpOWDR6Qmk2QkJFbmR4RXpEdjl1OVh6Qm1DZCUyRnRwVDJ3UzZ4UDZja0NwWjVJWEhta3JaUUZuanZHcDRXa3UwUXNOJTJCeGtsME5Ca0g0dWszU1pFRFIlMkJITVU0MHNFZ2VGR3E1JTJCanlkZU5nYXclM0QlM0Q.)
[Como ordenar uma sequência de números no JavaScript](https://www.alura.com.br/artigos/ordenacao-de-numeros-no-javascript-nao-funciona?_gl=1*164k246*_ga*MTAyMjIzNjI2OC4xNzAxODc3NTU5*_ga_1EPWSW3PCS*MTcwOTczMTQ4NS4zNS4xLjE3MDk3MzM0NzkuMC4wLjA.*_fplc*UEg3RkVXQTFWQXpOU3BGdUdoWkpOWDR6Qmk2QkJFbmR4RXpEdjl1OVh6Qm1DZCUyRnRwVDJ3UzZ4UDZja0NwWjVJWEhta3JaUUZuanZHcDRXa3UwUXNOJTJCeGtsME5Ca0g0dWszU1pFRFIlMkJITVU0MHNFZ2VGR3E1JTJCanlkZU5nYXclM0QlM0Q.)


## Tipo String


 
 Continuamos com tipos primitivos, fundamentais para que qualquer pessoa que deseja aprender qualquer linguagem de programação. Já aprendemos o tipo number (número), e nesta aula vamos analisar o tipo string (cadeia de caracteres).

Na verdade, podemos classificá-los como tipos textuais, que não se enquadram na categoria de números ou booleanos.

Vamos lá! O que podemos afirmar sobre strings, Léo?

Tipo String
Leonardo: Podemos utilizar strings em JavaScript para armazenar texto, ou seja, tudo que não for número ou booleano. Podemos armazenar neles caracteres, como, por exemplo, letras do alfabeto, pontuação e, basicamente, qualquer coisa que quisermos.

Juliana: Criaremos um novo arquivo chamado type-string.js, para escrevermos um pouco de código nele. Na mesma pasta do arquivo type number.js.

Arquivo type-string.js no repositório do GitHub

Por definição, usamos as strings para armazenar qualquer outro tipo de dado que não seja número nem booleano. Como colocamos isso em prática? Criamos uma const chamada texto1. Como criamos uma string em JavaScript?

type-string.js

const texto1 =
COPIAR CÓDIGO
Leonardo: Para criar uma string em JavaScript, precisamos usar aspas. Podem ser duplas ou simples.

Criamos um texto chamado "Olá, mundo!", o clássico em computação! Colocamos este texto entre aspas duplas. Ou seja, qualquer conjunto de caracteres que colocamos entre aspas, sejam duplas ou simples, o JavaScript considerará como um dado do tipo string.

Criamos outra constante chamada texto2 com aspas simples.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
COPIAR CÓDIGO
Para o JavaScript, ambos os casos serão reconhecidos como dados do tipo string.

Entretanto, as strings devem ser exclusivamente textos que conseguimos ler, como um nome, uma frase ou um parágrafo? Não necessariamente. Usamos as strings para, por exemplo, salvar um dado de uma senha.

Para exemplificar, criamos outra constante chamada senha que recebe "senhaSuperSegura456!".

Nossas senhas precisam ter números, textos, caracteres. Por isso, precisamos informar ao JavaScript que é uma string, para que consiga entender que se trata de uma cadeia de caracteres que envolve texto, números e caracteres especiais, como acentos.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
COPIAR CÓDIGO
Leonardo: Tudo que colocarmos entre aspas, o JavaScript considerará como uma string. Isso pode também incluir apenas números. Se colocarmos somente números entre aspas, para o JavaScript, ainda será uma string.

Juliana: Podemos criar uma constante chamada StringDeNumeros, abrir e fechar aspas e inserir um conjunto de números.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
const StringDeNumeros = "34567";
COPIAR CÓDIGO
Fica um pouco mais complicado quando mencionamos a possibilidade de usar tanto aspas simples quanto duplas. É realmente a mesma coisa? Quando usamos uma, podemos usar outra? Existe algum caso em que precisamos usar ambas, Léo?

Leonardo: Certamente, existem situações em que é necessário utilizar ambos os tipos de aspas. Por exemplo, ao citar algo que alguém disse em um texto, podemos iniciar com aspas simples, inserir o texto da citação e destacar a citação com aspas duplas.

Juliana: Criamos então a const citacao = 'O Leo disse "oi!"'.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
const StringDeNumeros = "34567";

const citacao = 'O Leo disse "oi!"'
COPIAR CÓDIGO
Abrimos a string usando aspas simples, tudo que está dentro dela é uma cadeia de caracteres, mas, dentro dessa cadeia, precisamos utilizar aspas como parte do texto.

Para que o JavaScript não se confunda com o início e o fim da string, usamos aspas simples juntamente com aspas duplas para fazer essa diferenciação. O contrário também se aplica.

Podemos também abrir com aspas duplas e fechar com aspas simples. Vamos exibir isso no console, apenas para confirmar se está tudo certo. Digitamos console.log() passando citacao.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
const StringDeNumeros = "34567";

const citacao = 'O Leo disse "oi!"'
console.log(citacao)
COPIAR CÓDIGO
No terminal, rodamos o comando Node passando o arquivo type-strings.js.

node type-strings.js
COPIAR CÓDIGO
E o resultado é:

"O Léo disse "oi!"

Funcionou!

Se trocarmos as aspas de dentro e de fora. Então, abrimos a cadeia de strings com aspas duplas e a citação do Léo colocamos entre aspas simples.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
const StringDeNumeros = "34567";

const citacao = "O Leo disse 'oi!'"
console.log(citacao)
COPIAR CÓDIGO
Executamos novamente o programa e o resultado é:

"O Léo disse 'oi!'

O JavaScript tem vários métodos e ferramentas prontas. Por exemplo, para transformar todas as letras em minúsculo, para transformar tudo em maiúsculo, para contar quantas letras tem uma cadeia de caracteres, retirar espaços.

Vamos disponibilizar um material extra para vocês e ao longo do curso vamos ver, aos poucos, como cada um funciona, para que serve e quais são os usos.

Juliana: Além disso, temos outro tipo de aspa, que na verdade é um acento grave, que conseguimos utilizar também como se fossem as aspas da string. Isso se chama template string ou template literal.

Deixaremos como desafio para você pesquisar a terceira forma de escrever strings, mas tenha em mente que voltaremos a esse tópico. Tudo o que mencionamos será explorado ou referenciado ao longo do curso.

Portanto, vamos estudar as template strings, que são a terceira forma de se escrever strings em JavaScript, em breve. Mas, se tiver curiosidade, pode ir estudando como funciona e para que serve.

Strings em variáveis
Uma das últimas coisas que podemos abordar é que conseguimos utilizar strings com variáveis. Por exemplo, você quer escrever o seu nome, colocar o nome das pessoas em uma frase pré-definida, não é mesmo, Léo?

Leonardo: Isso pode ser feito, chama-se concatenação.

Concatenação
Leonardo: Vamos unir duas partes de texto usando o operador de adição, que também desempenha essa função no JavaScript. Portanto, o operador de adição serve para adicionar, seja com números ou texto.

type-string.js

// código omitido

// concatenação (+)
COPIAR CÓDIGO
Juliana: Isso destaca a importância do JavaScript em deixar claro para o programa se estamos lidando com texto ou números, já que o mesmo operador de adição pode ser usado para somar números ou concatenar texto.

Apesar do que mencionamos anteriormente, pode parecer um pouco confuso. Lembramos do "NaN" (não é um número), que deixa claro que não é possível realizar operações matemáticas com texto. No entanto, é exatamente isso que faremos agora, demonstrando como isso funciona.

Vamos construir nossa citação da seguinte forma: a citação é "Meu nome é". O nome pode ser tanto Juliana quanto Leonardo. Podemos usar a concatenação aqui para criar uma frase que faça sentido da seguinte maneira: "Meu nome é Juliana." ou "Meu nome é Leonardo."

Leonardo: Por enquanto, vamos declarar outra variável com o nome da pessoa.

Juliana: Sendo assim, criamos uma constante chamada meuNome e atribuímos "Leonardo" a ela. Agora que temos o nome armazenado, vamos fazer esse nome aparecer na tela. Então, para isso, usaremos o comando console.log para podermos visualizar na saída.

Leonardo: Vamos adicionar a nossa primeira constante, que é a citação, mais a variável meuNome.

Juliana: Portanto, citação + meuNome.

type-string.js

const texto1 = "Olá, mundo!";
const texto2 = 'Olá, mundo!';
const senha = "senhaSuperSegura456!";
const StringDeNumeros = "34567";

const citacao = "Meu nome é ";
const meuNome = "Leonardo";

// concatenação (+)

console.log(citacao + meuNome)

//template string OU template literal
COPIAR CÓDIGO
Pegamos a variável citacao, que contém a primeira parte da frase, e estamos utilizando o operador de adição para concatená-la com outra parte de texto, que é o nome do Léo. Vamos ver se isso funcionará corretamente.

No terminal, rodamos:

node type-strings.js
COPIAR CÓDIGO
Vamos executar o código novamente e o resultado é:

Meu nome é Leonardo

Agora conseguimos entender como funcionaria para capturarmos informações de variáveis. Porque nesse programa, por ser pequeno, conseguimos visualizar claramente o que está guardado em cada variável. No entanto, na prática, normalmente não é assim.

Às vezes não temos completa certeza do que as variáveis estão guardando, mas é preciso ter certeza de que isso aqui é uma string (cadeia de caracteres), que isto é um nome, e que podemos juntar esse nome com outra string utilizando o operador +, que Leo nos lembrou que é chamado de "concatenação".

Conclusão
Note que a concatenação não funcionará com outros operadores, apenas com o operador +. Existem alguns outros detalhes sobre o uso de concatenação que aprenderemos ao longo do curso. Certo? Esquecemos de mencionar algo, Léo? Ou, por enquanto, encerramos a questão sobre strings (cadeias de caracteres).

Leonardo: Acredito que abordamos tudo que era mais importante em relação às strings.

Juliana: Ótimo! Então nos vemos no próximo vídeo.

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/609f05fc-ad7d-400a-a7a8-897e23b69562)

## Para saber mais: Codificação de strings
PRÓXIMA ATIVIDADE

Acabamos de ver que usamos o tipo string sempre que queremos trabalhar com dados de texto. Mas se pararmos para pensar, vários idiomas utilizam caracteres diferentes, como acentos e ideogramas. Como as linguagens de programação lidam com isso? E o que dizer dos emojis :question:? Você já visitou algum site e notou que os caracteres dos textos não pareciam corretos, que no lugar de alguns deles aparecia um sinal de interrogação, quadrados ou traços?

Isso tudo tem a ver com a codificação de caracteres, ou character encoding. Nas últimas décadas, foram desenvolvidos diversos conjuntos de caracteres especiais, cada um com seus próprios códigos, para que pessoas que escrevem e leem em linguagens diferentes do inglês pudessem utilizar computadores com seus próprios idiomas. E como isso funciona?

Para que o computador consiga decifrar um caractere especial, é preciso utilizar um sistema específico que tenha basicamente um código para cada caractere, e que o computador possa acessá-lo para fazer a conversão - uma ideia similar a que está por trás da criptografia.

Foram desenvolvidos diversos conjuntos de caracteres, desde os específicos de cada linguagem como Western, Latin-US, Japanese e assim por diante, até o ASCII (American Standard Code for Information Interchange ou ”Código Padrão Americano para o Intercâmbio de Informação”) e a partir de 2007 foi adotado o formato Unicode. O padrão UTF (de Unicode Transformation Format ou “formato de conversão de unicode”, em tradução livre) é utilizado como padrão na web até hoje.

O Unicode tem códigos específicos para “cifrar” e “decifrar” caracteres de mais de 150 idiomas antigos e modernos, e também diversos outros conjuntos de caracteres como símbolos matemáticos e inclusive emojs. A [Wikipedia](https://en.wikipedia.org/wiki/List_of_Unicode_characters) tem uma lista extensa de todas as tabelas com os códigos Unicode e os caracteres, como por exemplo os que estão abaixo:

caractere	UTF-16	descrição oficial
$	U+0024	DOLLAR SIGN
A	U+0041	LATIN CAPITAL LETTER A
✅	U+2705	CHECK MARK
ぁ	U+3041	HIRAGANA LETTER SMALL A
Podemos testar a transformação/conversão do código Unicode em caractere utilizando o console.log(). Faça o teste:

const cifrao = '\u0024'
const aMaiusculo = '\u0041'
const tique = '\u2705'
const hiragana = '\u3041'

console.log(cifrao)
console.log(aMaiusculo)
console.log(tique)
console.log(hiragana)
COPIAR CÓDIGO
Os caracteres \u no início do código são caracteres de escape que usamos para sinalizar ao JavaScript de que estamos falando de códigos Unicode, e não de strings de texto usuais.

O JavaScript usa, por padrão, o UTF-16. O número 16 está relacionado aos espaços em bits ocupados por cada caractere, 16 neste caso. Não vamos nos aprofundar na relação entre tipos de dados e espaço de memória ocupado por cada tipo - você pode pesquisar mais sobre o assunto, assim como sobre o que são caracteres de escape! - mas por enquanto é bacana vermos na prática como o Unicode funciona.

Bancos de dados podem aceitar outros tipos de codificação de caracteres, o que faz sentido se pensarmos que o UTF-16 utiliza uma quantidade relativamente grande de espaço em memória para salvar cada caractere. 16 bits parece pouco, mas algumas vezes os bancos precisam salvar quantidades enormes de dados! Porém, com as tecnologias de armazenamento e tráfego de dados que temos hoje, esta já não é uma preocupação tão grande, a não ser em casos muito específicos. Já não é muito comum utilizar uma codificação diferente da UTF em bancos mesmo em caso de grandes volumes de dados, mas sempre vai depender muito do caso.

Mais detalhes precisos e documentação sobre o Unicode na página da [Unicode Foundation](https://home.unicode.org/).

## Para saber mais: Trabalhando com strings
PRÓXIMA ATIVIDADE

O JavaScript traz em sua biblioteca-base vários métodos que usamos para manipular strings de texto: alterar de maiúsculas para minúsculas, contar quantas letras tem uma palavra, retirar espaços, juntar duas strings, etc.

Vamos pensar em alguns exemplos práticos para fazer esse tipo de alteração. Por exemplo, para padronizar uma comparação entre strings:

const cidade = "belo horizonte";
const input = "Belo Horizonte";

console.log(cidade === input); // falseCOPIAR CÓDIGO
Nós, como pessoas, conseguimos perceber o valor das variáveis cidade e input como sendo da mesma cidade, Belo Horizonte. Porém, para o JavaScript, ambos os dados são apenas sequências de caracteres, e a comparação vai falhar, pois como já vimos, o JavaScript diferencia minúsculas e maiúsculas, tanto nos valores dos dados quanto no código que escrevemos.

Uma das formas de tratar isso é padronizando todos os inputs para o formato de texto que será comparado antes mesmo de fazer a comparação. Nesse caso, transformando todos os caracteres em letras minúsculas.

const cidade = "belo horizonte";
const input = "Belo Horizonte";

const inputMinusculo = input.toLowerCase();

console.log(cidade === inputMinusculo); // trueCOPIAR CÓDIGO
Acima, vemos um dos métodos de string nativos do JavaScript em ação, o toLowerCase() que converte todos os caracteres da string informada (no caso, input) para letras minúsculas (se forem algarismos, nada é convertido). Você pode conferir mais sobre este método no [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase).

Outro exemplo: qualquer inserção de texto que exija uma quantidade mínima de caracteres, como uma senha ou um nome. A propriedade length pode ser utilizada para sabermos quantos caracteres uma string contém:

const senha = "minhaSenha123"
console.log(senha.length) // 13 caracteres
COPIAR CÓDIGO
A propriedade length é muito usada no dia a dia do desenvolvimento web. Você pode descobrir mais sobre ela [aqui](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase).

Percebeu que length não leva parênteses no final da palavra? Há uma diferença entre métodos e propriedades que não vamos abordar durante este curso, mas vamos deixar aqui a dica caso tenha curiosidade! ;)

Você pode conferir a lista completa de [métodos de string do MDN (são vários)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/String#m%C3%A9todos), com a descrição de cada um, e praticar com os exemplos.


## Tipo Boolean

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/4d58577c-d895-4a58-92b3-6ab6f4fd5a33)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/af75b810-49b3-4d49-a628-9c40b1f96698)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/95c1405c-082a-44b1-a07d-72b150d81a1c)


Neste último vídeo sobre tipos primitivos nesta introdução, aprenderemos sobre um tipo bem particular, o tipo booleano - também conhecido como verdadeiro e falso, ou true ou false.

É peculiar, pois não é um número nem um texto e possui apenas dois valores: podemos ter somente true ou false. Parece estranho que tenhamos um tipo exclusivo para essas opções. Você consegue nos explicar melhor, Léo?

Tipo booleano
Leonardo: De fato, parece peculiar, mas são tipos que usamos com frequência na programação. Usamos os booleanos com frequência quando precisamos fazer alguma comparação, como, por exemplo, em estrutura if-else, estrutura while e estrutura for.

Juliana: Entendi.

Vamos criar um novo arquivo chamado type-boolean.js e adicionar mais um pouco de código. Faremos alguns testes. Léo, quais são alguns exemplos de comparações que determinam se algo é verdadeiro ou falso?

Exemplos de comparação usando o booleano
Arquivo type-boolean.js no repositório do GitHub

Leonardo: Para fazermos a comparação, precisamos de duas coisas para comparar. Comecemos pela criação desses dois elementos. Você poderia definir duas variáveis numéricas, Ju?

Juliana: Claro

Definimos então const primeiroNumero, cujo valor definimos como 5, por exemplo, e const segundoNumero, cujo valor será 10, por exemplo.

type-boolean.js

const primeiroNumero = 5;
const segundoNumero = 10;
COPIAR CÓDIGO
Leonardo: Agora que temos nossos dois primeiros números, podemos fazer a comparação entre eles. Isso pode ser feito com um if ou diretamente no console.log(). Facilitamos o processo ao fazê-lo diretamente no console, assim tornando o código um pouco mais curto.

Juliana: Vamos digitar console.log().

type-boolean.js

const primeiroNumero = 5;
const segundoNumero = 10;

console.log();
COPIAR CÓDIGO
Estamos comparando o valor armazenado na variável chamada primeiroNumero com o valor armazenado na variável segundoNumero. Correto?

Leonardo: Exato.

Juliana: Como fazemos isso, então?

Leonardo: Inserimos primeiroNumero, que é o nome da nossa variável. Agora, colocamos três sinais de igual (===). Esses três sinais, são exclusivos do JavaScript, veremos mais detalhes em breve. Com o que vamos compará-lo? Com o segundoNumero.

type-boolean.js

const primeiroNumero = 5;
const segundoNumero = 10;

console.log(primeiroNumero === segundoNumero);
COPIAR CÓDIGO
Juliana: Basta prestar atenção ao iniciar. É comum cometer um erro nesta fase. Quando se utiliza apenas um sinal de igual no JavaScript, ocorre uma atribuição de valor a uma variável. Portanto, o valor à direita do sinal de igual é atribuído à variável mencionada à esquerda.

Para comparações no JavaScript, como Léo explicou, usamos dois ou três sinais de igual, e abordaremos isso mais detalhadamente em breve. E o resultado das comparações sempre será? Verdadeiro ou falso.

Leonardo: Podemos salvar e executar agora.

Juliana: Já estou na pasta correta no terminal, agora executamos o arquivo type-boolean.js com node.

node type-boolean.js
COPIAR CÓDIGO
E obtemos como retorno o valor false.

false

O programa comparou se cinco e dez são iguais, e como são diferentes, retornou false. Ou seja, o resultado é um booleano, que geralmente é o resultado de uma comparação.

Leonardo: Vamos alterar o valor de segundoNumero para cinco para verificar se retorna true?

Juliana: Alteramos o valor para 5, salvamos e executamos novamente o programa.

type-boolean.js

const primeiroNumero = 5;
const segundoNumero = 5;

console.log(primeiroNumero === segundoNumero);
COPIAR CÓDIGO
Rodamos o comando node:

node type-boolean.js
COPIAR CÓDIGO
Agora, retornou true.

true

Portanto, confirmamos no JavaScript que cinco é igual a cinco. Anotaremos que true significa verdadeiro e false, falso, no código.

type-boolean.js

// boolean
// true -> verdadeiro
// false -> falso

const primeiroNumero = 5;
const segundoNumero = 5;

console.log(primeiroNumero === segundoNumero);
COPIAR CÓDIGO
A saída será true, confirmando que 5 é igual a 5.

Já sabemos que sempre que comparamos duas coisas, usualmente em linguagem de programação, o retorno será verdadeiro ou falso. Ou seja, retornará um valor booleano.

Pode parecer um pouco estranho, mas usamos muito isso, como o Léo mencionou no começo. O que confirmamos?

Por exemplo, se a senha de uma pessoa usuária salva em um banco de dados corresponde à senha que está sendo inserida agora, é uma comparação que fazemos constantemente quando estamos acessando a internet. O resultado dessa comparação será verdadeiro ou falso e permitirá ou não que a pessoa usuária acesse uma área do sistema, e assim por diante.

Ou, por exemplo, se um cadastro está ativado, comparado a verdadeiro, sim, o cadastro está ativo. Então, a pessoa usuária pode receber alguma informação, etc. O booleano é utilizado frequentemente.

Boolean como valores de variáveis
Juliana: Além de comparação, ele pode assumir valores de variáveis. Então, por exemplo, a variável cadastroAtivo, pode inicialmente ter valor falso. E podemos executar alguns testes, como verificar a senha, e ele assumir um novo valor de verdadeiro, significando que o cadastro está ativo.

type-boolean.js

// boolean
// true -> verdadeiro
// false -> falso

const primeiroNumero = 5;
const segundoNumero = 5;
const cadastroAtivado = true;

console.log(primeiroNumero === segundoNumero);
COPIAR CÓDIGO
Isso funciona, Léo?

Leonardo: Funciona, podemos utilizar. Mas a questão é a seguinte: criamos uma constante. A constante não poderá ter seu valor alterado futuramente, esse é um ponto muito importante a se considerar. Nós vamos ver isso com mais detalhes mais adiante.

Juliana: Verdade. Léo, você está correto, escrevemos tantas constantes que acabamos adicionando mais uma. Vamos alterar a const para let.

type-boolean.js

// boolean
// true -> verdadeiro
// false -> falso

const primeiroNumero = 5;
const segundoNumero = 5;
let cadastroAtivado = true;

console.log(primeiroNumero === segundoNumero);
COPIAR CÓDIGO
Vamos ver a diferença muito importante entre const e let em breve.

Vamos aplicar mais alguns exemplos para finalizarmos com nossos exemplos de booleanos?

Leonardo: Podemos fazer comparação entre duas strings também.

Comparando duas strings com boolean
Juliana: Criamos então mais duas consts. Chamaremos de texto1 igual. Qual valor devemos atribuir a essa string?

Leonardo: Podemos inserir apenas a palavra Alura.

Juliana: Certo. E a texto2, que será somente a letra a. Na sequência colocamos um console.log(). Vamos comparar o texto1 com texto2.

Comentamos o primeiro console.log, aquele dos números, só para não ficarmos confusos com o que aparece no console.

type-boolean.js

// boolean
// true -> verdadeiro
// false -> falso

const primeiroNumero = 5;
const segundoNumero = 5;
let cadastroAtivado = true;

//console.log(primeiroNumero === segundoNumero);

const texto1 = "Alura";
const texto2 = "a";

console.log(texto1 === texto2)
COPIAR CÓDIGO
Rodamos novamente no terminal o comando node. Obtemos como retorno:

false

E falso.

O programa comparou as duas variáveis, alura com a. Embora as duas sejam strings, o valor não é o mesmo. Uma tem apenas uma letra, que é a letra a, e a outra tem cinco letras. Forma a cadeia de caracteres alura. O JavaScript comparou e retornou para nós que não é a mesma coisa.

E se tentássemos fazer Alura com letra maiúscula e alura com letra minúscula? Será que ele compararia?

Leonardo: Podemos tentar.

Juliana: Vamos tentar e examinar o que ocorre. Portanto, vamos tentar executar isso novamente.

type-boolean.js

// boolean
// true -> verdadeiro
// false -> falso

const primeiroNumero = 5;
const segundoNumero = 5;
let cadastroAtivado = true;

//console.log(primeiroNumero === segundoNumero);

const texto1 = "Alura";
const texto2 = "alura";

console.log(texto1 === texto2)
COPIAR CÓDIGO
Rodamos o comando node no terminal e seguimos recebendo false. No entanto, não considerou alura em maiúsculas e alura em minúsculas como idênticos. Existem alguns detalhes a serem considerados sobre isso.

Deixaremos um material extra explicando a diferença entre letras maiúsculas e minúsculas, que não é apenas visual.

E o que mais podemos mencionar sobre booleano neste exato momento?

Leonardo: Neste exato momento, sobre booleano, abordamos bastante coisa já.

Vamos fazer o seguinte, Ju. Importante também, vamos salvar todos esses códigos que geramos no Git para facilitar a distribuição e ser mais fácil para as pessoas verem o código?

Subindo o código no GitHub
Juliana: Claro. Já criamos três arquivos, cada um com os exemplos e exercícios. Vamos fazer o que o Léo sugeriu.

Salvamos e subimos todo esse código que criamos para um repositório no GitHub. Dessa forma, ele ficará salvo e poderemos compartilhá-lo com outras pessoas.

Eu já criei um repositório no meu perfil pessoal no GitHub com o nome do curso para irmos salvando esses códigos. Por enquanto, o repositório está vazio.

Lembrando que deixaremos material extra sobre Git e GitHub para você consultar caso precise.

Para começar a armazenar nossos primeiros códigos no repositório, vamos realizar os primeiros passos. No terminal, usaremos o comando git init para criar um novo repositório vazio dentro dessa pasta.

git init
COPIAR CÓDIGO
Depois de criar um novo repositório Git na pasta local, usamos o comando git status e ele mostra os três arquivos que criamos. Os arquivos, indicados em vermelho, ainda não estão prontos para serem enviados para a nuvem.

git status
COPIAR CÓDIGO
Agora podemos seguir com os quatro primeiros passos principais. O primeiro é associar o endereço desse repositório na nuvem.

https://github.com/JulianaAmoasei/2206-fundamentos-js.git
COPIAR CÓDIGO
Este é o endereço da pessoa instrutora, você deve usar o seu endereço do GitHub.

Associamos o nosso repositório ao endereço do nosso computador usando o comando git remote add origin e colando o endereço copiado do GitHub.

git remote add origin https://github.com/JulianaAmoasei/2206-fundamentos-js.git
COPIAR CÓDIGO
O terminal não fornece nenhum feedback, mas é normal, não indica que ocorreu algum erro.

Agora, os três comandos principais do GitHub: git add ., que adiciona todos os arquivos na caixa que será enviada para a nuvem.

git add .
COPIAR CÓDIGO
Podemos usar o comando git statusnovamente para ver que eles foram indexados.

git status
COPIAR CÓDIGO
Eles aparecem em verde. Em seguida, o comando git commit -m, que adiciona uma mensagem para identificar o que fizemos.

git commit -m
COPIAR CÓDIGO
Para este commit, utilizamos a mensagem "Exemplos da aula 1" para descrever os códigos que estou subindo para o GitHub.

git commit -m "Exemplos da aula 1"
COPIAR CÓDIGO
O comando final é git push origin master, que é o nome do repositório principal no GitHub.

git push origin master
COPIAR CÓDIGO
Neste momento, ocorre um erro na ação da pessoa instrutora. Isso aconteceu porque ela confundiu o comando. Não é main, mas sim git push origin master. Portanto, ela teve que autenticar a conta no GitHub, algo que ainda não havia feito. Isso pode ocorrer com qualquer pessoa.

Nesse caso, basta conceder ao GitHub a autorização para acessar o terminal do Visual Studio Code. Depois disso, a conexão será estabelecida adequadamente e o envio será realizado.

Quando visualizamos a mensagem "new branch" indica que tudo concluído com sucesso, significa que conseguimos fazer o commit do código.

Agora, é hora de voltar ao nosso repositório, recarregar a página e lá estarão os três exemplos de código, salvos no GitHub. Não precisamos nos preocupar se perdermos o computador, o código estará salvo na nuvem.

Lembrando que estamos mencionando bastante sobre fundamentos. Aprendemos sobre tipos primitivos, mas voltaremos a mencionar mais sobre eles, porque existe muita coisa para falar sobre cada um.

## Para saber mais: Padrão de nomes no JavaScript
PRÓXIMA ATIVIDADE

Um detalhe muito importante, mas que às vezes não percebemos quando começamos a programar, é que cada linguagem possui seus próprios padrões. Eles servem não somente para a escrita de códigos que funcionem, mas também para criar nomes de variáveis, estruturar um programa e muito mais.

A primeira coisa que precisamos ter em mente é que o JavaScript é case-sensitive, ou seja, diferencia maiúsculas e minúsculas. Isso significa que tudo o que escrevemos, sejam instruções próprias da linguagem (como console.log) ou quando damos nome a uma variável, tem que ser feito em um mesmo padrão, o que inclui a questão de maiúsculas e minúsculas.

Para ilustrar, o JavaScript trata os quatro exemplos abaixo como variáveis diferentes e não apresentará nenhum erro se você executar o programa:

const minhaVar = 1;
const MinhaVar = "texto";
const minhavar = "3";
const MINHAVAR = 2;

console.log(minhaVar, MinhaVar, minhavar, MINHAVAR)COPIAR CÓDIGO
Podemos ver que, em um programa muito grande, a possibilidade de problemas é grande. Então como sabemos a forma certa de nomear? Aí entra o que chamamos de convenções, para padronizar estes aspectos do código.

Existem várias convenções para nomes e cada linguagem de programação tem o seu. Seguem alguns deles:

camelCase: Inicia com letra minúscula e a primeira letra de cada palavra em seguida é escrita com letra maiúscula. Por exemplo: minhaVar ou senhaDoUsuario. Esta é a convenção utilizada pelo JavaScript para variáveis e funções.
snake_case: Os espaços são substituídos pelo caractere _ (underline), com todas as palavras em letra minúscula. Por exemplo: minha_variavel ou senha_do_usuario.
kebab-case: Similar ao anterior, porém com os espaços substituídos por hífens. Por exemplo: minha-var ou senha-do-usuario. Esta convenção não pode ser utilizada no JavaScript para variáveis e funções.
PascalCase: Similar ao CamelCase, porém neste caso todas as palavras começam com letra maiúscula. Por exemplo: MinhaVar ou SenhaDoCliente.
Importante: Nunca utilize espaço nem caracteres especiais, nem inicie os nomes das variáveis com números.

Quando falamos de convenção, estamos falando de boas práticas e padronização. Se você utilizar qualquer um dos padrões acima para nomear variáveis com JavaScript (com exceção do padrão kebab-case), seu código continuará funcionando, mas seguir as convenções é parte de desenvolver um código legível e bem escrito.

Esse é um assunto vasto e com muitos detalhes, e é parte do nosso trabalho no cotidiano como pessoas que desenvolvem garantir que os chamados guias de estilo definidos para um produto de código sejam seguidos.

Você pode ir aprendendo os detalhes aos poucos, enquanto estuda, e observá-los sendo aplicados nos códigos que vê por aí.

## Para saber mais: Tipos null e undefined
PRÓXIMA ATIVIDADE

Nesta aula falamos sobre três tipos primitivos: number, string e boolean. Mas existem ainda mais dois tipos que não abordamos com profundidade: null e undefined.

O null é um tipo especial, pois pode ser traduzido como “ausência de valor” e pode ser atribuído como valor de uma variável:

let input = null;

if (input === null) {
 console.log('não há informação');
} else {
 console.log(input);
}COPIAR CÓDIGO
Nesse caso, qual seria a diferença entre os dois casos abaixo?

let input = null;
let input2;

console.log(input); // null
console.log(input2); // undefinedCOPIAR CÓDIGO
É aqui que entra o tipo undefined. Este tipo também representa “ausência de valor”, porém de uma outra forma: usualmente, enquanto null é um valor atribuído a uma variável que existe e foi iniciada, undefined se refere ao valor de uma variável que não foi inicializada (ou seja, não foi atribuído nenhum valor a ela).

undefined também é o valor retornado por uma função que não tem cláusula return. Veremos mais sobre funções e return mais adiante no curso.

É importante notar que, embora os dois tipos sejam utilizados para sinalizar ausência de valor, os operadores de comparação do JavaScript podem ou não diferenciá-los:

console.log(null == undefined); // true
console.log(null === undefined); // falseCOPIAR CÓDIGO
No cotidiano é comum considerar undefined como uma ausência de valor “inesperada” (causada por um bug ou erro no código) e null como um tipo de dado que também significa ausência de valor, mas não de maneira inesperada. Por exemplo, um campo em uma tabela de um banco de dados que esteja sem dados ou uma informação solicitada que não seja obrigatória e não tenha sido preenchida pelo usuário pode ter valor null.

# 2. Declarando Variaveis

## Var, Let e Const

var --> funciona basicamente em qq parte do codigo

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/c3fd71d9-6e99-4490-89c6-8b4613dce389)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/7a3195c5-93f3-42a9-b7d0-d8d851c74848)


let --> surgiu com o js 2015

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/fe86c7fc-0573-4c71-ad14-4051aaafb19d)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/4e9cbd2f-b297-4adb-acb9-6d80f7238968)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/d6522e1e-def5-40a4-82bd-12d5d6cceece)

const --> impede que alguem mude o valor da variavel;

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/5eed77d3-e0bb-47f6-a928-daae9f7ac15f)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/654c65a8-5991-4add-9b05-b454c5ff6dd7)

![image](https://github.com/FlavianaFXT/Javascript-Tipos-variaveis-e-funcoes/assets/113718720/94d56a51-d2ee-4d71-8346-a2435b8cc8d7)





