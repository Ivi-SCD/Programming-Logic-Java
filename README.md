Language: > **PT-BR** |  [EN](https://github.com/Ivi-SCD/Logica-da-Programacao-1P/blob/main/README_EN.md)

## Lógica de Programação :computer:
#### Opa Galera! To criando esse repositório pra ajudar vocês na cadeira de **Lógica de Programação** :computer:.
Sei que muitos de vocês estão começando agora no mundo da programação e podem estar enfrentando
algumas dificuldades para entender os conceitos fundamentais. A lógica da programação é **essencial** pra
todo programador, independente da linguagem ou ferramenta utilizada e envolve desde a compreensão de como
os computadores funcionam até a interpretação dos mesmos para as informações.

Vou tentar com o decorrer do período subir neste repositório
algumas listas de exercícios sobre determinados assuntos trabalhado em sala tal como sua resolução
e outros materiais de estudo, qualquer dúvida vocês podem falar comigo pelo
meu [Whatsapp apenas clicando aqui.](https://api.whatsapp.com/send?phone=5581997053349&text=Ol%C3%A1%20Ivisson!%20Estava%20olhando%20seu%20perfil%20no%20github%20e%20gostaria%20de%20entrar%20em%20contato!!%20%F0%9F%98%80)

*Você pode selecionar aqui determinado tópico que você deseja ver:*
* [Instalação](#instalacao)
* [Sintaxe Básica](#sintaxe)
* [Tipos de dados](#datatypes)
* [Operadores](#operadores)
* [Estruturas de Controle](#estruturascontrole)
* [Arrays Unidimensionais (Vetores)](#arrays)
* [Entrada de Dados](#input)

*Listas de Exercicios:* (Para verificar as respostas entre no diretório de resoluções na pasta src logo após e selecione a dificuldade, em seguida procure a classe que mais se adepta a questão, por exemplo, a questão de número 1 na dificuldade díficil no arquivo .txt é a questão que envolve números de Mersenne, logo, sua classe será a NumerosMersenne)

* [Estruturas Condicionais](https://github.com/Ivi-SCD/Logica-da-Programacao-1P/tree/main/Listas%20de%20Exercicios/Estruturas%20Condicionais)
* [Estruturas de Repetição](https://github.com/Ivi-SCD/Programming-Logic-Java/blob/main/Listas%20de%20Exercicios/Estruturas%20de%20Repeti%C3%A7%C3%A3o/01-ListaExercicios-EstruturasRepeticao.md)
* [Arrays](https://github.com/Ivi-SCD/Programming-Logic-Java/blob/main/Listas%20de%20Exercicios/Arrays/01-ListaExercicios-arrays.md)
* [Entrada de Dados](https://github.com/Ivi-SCD/Programming-Logic-Java/blob/main/Listas%20de%20Exercicios/Entrada%20de%20Dados/01-ListaExercicios-EntradaDeDados.md)

## Vamos lá, Mão na massa!
Primeiro vamos começar falando sobre a própria linguagem que será utilizada em sala a linguagem Java, 
ela é uma linguagem de programação Orientada a Objetos, criada pela Sun Microsystems e atualmente mantida pela Oracle Corporation. 
Ela foi lançada em 1995 e se tornou uma das linguagens de programação mais populares do mundo.

### <a name= "instalacao"> Instalação </a>
Para começar a programar em Java você precisa baixar o [JDK](https://www.oracle.com/br/java/technologies/downloads/) (Java Development Kit) da Oracle. O JDK inclui o compilador Java,
que permite transformar seu código em bytecode, que pode ser executado na JVM (Java Virtual Machine). Após instalar o JDK podemos instalar a nossa IDE (Integrated Development Environment ou Ambiente de Desenvolvimento Integrado),
no nosso caso estaremos usando o [Eclipse](https://www.eclipse.org/downloads/), mas existem outras opções como o Netbeans ou o IntelliJ. Resumindo, os passos seriam estes:
* Baixar o [JDK](https://www.oracle.com/br/java/technologies/downloads/)
* Baixar e Instalar a [IDE](https://www.eclipse.org/downloads/)
* Começar a programar!

##

### <a name= "sintaxe"> Sintaxe Básica </a>
Segue abaixo um exemplo de um programa "Hello, World!" em Java:
```java
public class HelloWorld {
  public static void main(String [] args) {
      System.out.println("Hello, World!");
   }
}
```

Simples e fácil, concorda? Iremos explorar agora alguma características da linguagem, 
a medida que o curso for passando vocês compreenderam mais as palavras e sintaxe do código java,
a melhor maneira de ir aprendendo a sintaxe por enquanto é fazendo diversos programas, mesmo que simples
para seu cérebro começar a ir memorizando algumas etapas e com o tempo isso vai se tornar algo automático.

##

### Tutorial Simples de Como Criar um Projeto no Eclipse
1. Baixe e instale o Eclipse: O Eclipse pode ser baixado gratuitamente no [site oficial](https://www.eclipse.org/downloads/). 
Basta escolher a versão apropriada para o seu sistema operacional e seguir as instruções de instalação.

2. Crie um novo projeto: Abra o Eclipse e clique em "File" no menu principal. 
Em seguida, selecione "New" e "Java Project". Digite um nome para o projeto e clique em "Finish".

3. Crie uma nova classe: No Package Explorer (painel esquerdo), clique com o botão direito 
do mouse no nome do projeto que você acabou de criar. Selecione "New" e "Class". 
Digite um nome para a classe e clique em "Finish" 
* Obs: Não se esqueça de marcar o "static void main".

4. Escreva o código: Na janela principal do Eclipse, você verá um editor de texto em branco. 
É aqui que você escreverá o código Java para a sua classe.

5. Execute o código: Para executar o código, clique com o botão direito do mouse na classe 
que você acabou de criar no Package Explorer. Selecione "Run As" e "Java Application". 
Então voilá! O console do Eclipse exibirá a saída do seu programa.

##

### <a name= "datatypes"> Tipos de Dados </a>
Java tem diversos tipos de dados que podem ser divididos em dois grupos:
primitivos e as Wrapper Classes. Os tipos de dados primitivos são aqueles que armazenam
valores simples, como números inteiros, números de ponto flutuante e caractere. Já as Wrapper Classes armazenam referências a objetos. Vamos focar nos tipos primitivos
que são os que mais vão ser trabalhados em sala. Veja a seguir:

|Tipo|Tamanho|Wrapper Class|
|---|---|---
|byte|8 bits|Byte
|short|16 bits|Short
|int|32 bits|Integer
|long|64 bits|Long
|float|32 bits|Float
|double|64 bits|Double
|char|16 bits|Character
|boolean|1 bits|Boolean

Essa tabela deve ter assustado um pouco mas é super simples de entender, basicamente nela estão o tipo, o tamanho
(valor máximo que podemos atribuir a ela) e a sua representação de Wrapper Class.
Os tipos que armazenam números inteiros são os: (short, int e long) e quanto maior a quantidade de bits
maior será o valor que poderá ser armazenado neles, e os tipos que representam números com casas decimais são os:
(float e double) seguindo a mesma lógica. Já o tipo (char) serve para representar apenas caracteres como letras 
singulares ou apenas números e o tipo (boolean) serve para representar valores lógicos como true ou false, 0 ou 1.

##

Para declarar uma variável em Java utilizamos a seguinte sintaxe:
```java
tipo nomeDaVariável;
```
Por exemplo, para declarar uma variável do tipo inteiro chamada idade, usamos o seguinte código:

```java
int idade;
```

Para atribuir um valor à variável, usamos o operador de atribuição `=` :

```java
  idade = 25;

```

Podemos também declarar e inicializar uma variável em uma única linha:

```java
int idade = 25;
float numeroDecimal = 2.4F;
long numeroLong = 2L;
Double numeroDouble = 2.5;
boolean tipoBooleano = true;
char tipoCaractere = 'Y';
```
##

### <a name= "operadores"> Operadores </a>
Podemos também realizar operações matemáticas e 
lógicas no nosso código Java, segue uma tabela com os principais operadores:

|Operador|Descrição
|---|---
|+	|Adição
|-	|Subtração
|*	|Multiplicação
|/	|Divisão
|%	|Resto da divisão
|==	|Igualdade
|!=	|Diferença
|<	|Menor que
|>	|Maior que
|<=	|Menor ou igual a
|>=	|Maior ou igual a
|&&	|E lógico

Além destes operadores também temos o operador `||` que representa o OU lógico.

##

### <a name= "estruturascontrole"> Estruturas de Controle </a>
As estruturas de controle são usadas geralmente para controlar o fluxo de execução do programa. As principais estruturas de controle em Java são:

#### Estrutura condicional `if`
A estrutura condicional if é usada para executar um bloco de código **se uma determinada condição for verdadeira**. A sintaxe é a seguinte:

```java
if (condicao) {
  // bloco de código a ser executado se a condição for verdadeira
}
```

Por exemplo:

```java
int idade = 20;
if (idade >= 18) {
  System.out.println("Você é maior de idade.");
}
```
Se a idade for igual ou superior a 18, a mensagem "Você é maior de idade." será exibida na tela.

##

#### Estrutura condicional `if-else`
A estrutura condicional if-else é usada para executar um bloco de código se uma determinada condição for verdadeira e outro bloco se a condição for falsa. A sintaxe é a seguinte:

```java
if (condicao) {
  // bloco de código a ser executado se a condição for verdadeira
} else {
  // bloco de código a ser executado se a condição for falsa
}
```

Por exemplo:

```java
int idade = 16;
if (idade >= 18) {
  System.out.println("Você é maior de idade.");
} else {
  System.out.println("Você é menor de idade.");
}
```

Se a idade for igual ou superior a 18, a mensagem "Você é maior de idade." será exibida na tela. Caso contrário, a mensagem "Você é menor de idade." será exibida.

##

#### Estrutura condicional `else-if`
A estrutura condicional else-if é usada para testar várias condições em sequência. A sintaxe é a seguinte:

```java
if (condicao1) {
  // bloco de código a ser executado se a condição1 for verdadeira
} else if (condicao2) {
  // bloco de código a ser executado se a condição2 for verdadeira
} else if (condicao3) {
  // bloco de código a ser executado se a condição3 for verdadeira
} else {
  // bloco de código a ser executado se nenhuma das condições anteriores for verdadeira
}
```
Por exemplo:

```java
int nota = 8;
if (nota >= 9) {
  System.out.println("Aprovado com nota A.");
} else if (nota >= 7) {
  System.out.println("Aprovado com nota B.");
} else if (nota >= 5) {
  System.out.println("Reprovado com nota C.");
} else {
  System.out.println("Reprovado com nota D.");
}
```
Neste exemplo, o programa verifica a nota do aluno e exibe uma mensagem correspondente de acordo com a nota.

##

#### Estrutura `condicional ternária`

A estrutura condicional ternária é uma forma bem mais reduzida de escrever uma estrutura condicional 'if-else',
ela pode ser utilizada em diversas ocasiões e também ajuda a tornar o código visivelmente mais limpo, segue a sua estrutura:.

```java
variavel = (condicao) ? valorSeVerdadeiro : valorSeFalso;
```

Aqui está um exemplo real:
```java
public static void main(String [] args) {
    int valorProduto = 100;
    
    float desconto = (valorProduto > 50) ? 0.5F: 0.1F;
    
    int valorFinal = 100*desconto;
}
```
##

#### Estrutura de repetição  `while`
A estrutura de repetição `while` permite executar um bloco de código repetidamente enquanto uma condição for verdadeira. A sintaxe é a seguinte:

```java
while (condicao) {
  // bloco de codigo
}
```

O bloco de código será executado repetidamente enquanto a condição especificada for verdadeira. 
Se a condição for falsa na primeira verificação, o bloco de código não será executado.

Um exemplo de uso do while é a leitura de dados de um usuário, onde o programa pede que o usuário insira um valor e verifica se a entrada está correta antes de continuar:

```java
import java.util.Scanner;

public class ExemploWhile {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int numero = 0;
        
        while (numero <= 0) {
            System.out.print("Digite um número positivo: ");
            numero = scanner.nextInt();
        }
        
        System.out.println("O número digitado foi: " + numero);
        scanner.close();
    }
}
```

Neste exemplo, o programa solicita que o usuário digite um número positivo. 
Enquanto o número digitado não for positivo, o programa continuará solicitando que o usuário digite um número.

##

#### Estrutura de repetição  `for`
A estrutura de repetição `for` é uma estrutura de repetição que executa um bloco de código um número determinado de vezes. A sintaxe do `for` em Java é a seguinte:

```java
for (inicializacao; condicao; incremento) {
  // bloco de codigo
}
```

A inicialização é executada apenas uma vez no início do loop, a condição é verificada a cada iteração e, se for verdadeira, 
o bloco de código é executado. Após cada iteração, o incremento é executado. Por exemplo, o código abaixo imprime os números de 1 a 5 usando um for:

```java
Copy code
for (int i = 1; i <= 5; i++) {
  System.out.println(i);
}
```

Neste exemplo, a variável `i` é inicializada com o valor 1, a condição `i <= 5` é verificada a cada iteração e, se for verdadeira, o bloco de código dentro das chaves é executado, imprimindo o valor de `i`. Após cada iteração, `i` é incrementado em 1. O resultado será o mesmo que o exemplo anterior:

```bash
1
2
3
4
5
```

##

#### Estrutura de repetição `do-while`

A expressão `do-while` é uma estrutura de repetição em Java que é semelhante ao `while`, mas com a diferença de que o bloco de código dentro das chaves 
é executado pelo menos uma vez, independentemente da condição ser verdadeira ou falsa.

A sintaxe do do-while em Java é a seguinte:

```java
do {
  // bloco de codigo
} while (condicao);
```

O bloco de código dentro das chaves é executado primeiro, antes mesmo de verificar a condição. Depois, a condição é verificada. Se a condição for verdadeira, o bloco de código é executado novamente e o processo se repete. Se a condição for falsa, o loop termina e a execução continua normalmente.

A principal diferença entre o `do-while` e o `while` é que o `do-while` garante que o bloco de código seja executado pelo menos uma vez, 
enquanto o `while` pode pular a execução do bloco de código se a condição já for falsa no início.

Por exemplo, o código abaixo imprime os números de 1 a 5 usando um do-while:

```java
int i = 1;
do {
  System.out.println(i);
  i++;
} while (i <= 5);
```

Neste exemplo, o bloco de código dentro das chaves é executado primeiro, imprimindo o valor de `i` e incrementando-o em 1 a cada iteração. Depois, a condição `i <= 5` é verificada. Como `i` ainda é menor ou igual a 5, o bloco de código é executado novamente. O processo se repete até que `i` seja maior que 5. O resultado será:

```bash
1
2
3
4
5
```

É importante notar que a variável `i` é inicializada antes do loop `do-while`, pois ela precisa ter um valor antes de ser usada no bloco de código.

### <a name= "arrays"> Arrays ou Vetores Unidimensionais </a>

Arrays em Java são objetos que armazenam **uma coleção de elementos de um mesmo tipo em uma única variável**. Os elementos são acessados por meio de um índice que começa em 0 e vai até o tamanho do array menos 1 (Ou seja, quando um Array tiver o tamanho 5, o índice dele vai até [5-1]).

A declaração e criação de um array em Java segue a seguinte sintaxe:

```java
tipoDoArray[] nomeDoArray = new tipoDoArray[tamanhoDoArray];
```

Neste exemplo o `tipoDoArray` representa o tipo de dados que o array irá armazenar, `nomeDoArray` é o nome
que damos a este array e o `tamanhoDoArray` é o número de elementos que este array irá armazenar.

Um array pode ser inicializado também durante sua criação, como no exemplo abaixo:

```java
int [] numeros = {10, 20, 30, 40, 50}
```

Também podemos inicializar um array com um tamanho e atribuir valores 
aos seus elementos usando um loop for, como no exemplo abaixo:

```java
int[] numeros = new int[5];
for (int i = 0; i < numeros.length; i++) {
    numeros[i] = i * 10;
}
```

Além disso, o comprimento de um array pode ser obtido usando a propriedade length, 
como mostrado no exemplo abaixo:

```java
int tamanho = numeros.length;
```

Os elementos de um array podem ser acessados por meio de um `índice`, como veremos a seguir:


```java
int valor = numeros[1];
```

Também podemos iterar sobre os elementos de um array usando um loop for, como mostrado no exemplo abaixo:

```java
int[] numeros = {10, 20, 30, 40, 50};
for (int i = 0; i < numeros.length; i++) {
    System.out.println(numeros[i]);
}
```

Também podemos usar um loop foreach, que itera sobre todos os elementos de um array em ordem, 
como mostrado no exemplo a seguir:

```java
int[] numeros = {10, 20, 30, 40, 50};
for (int numero : numeros) {
    System.out.println(numero);
}
```

O uso de arrays em Java é bastante comum e útil em diversas situações. 
No entanto, é importante ter cuidado ao trabalhar com arrays para evitar 
exceptions (exceções) como a IndexOutOfBounds (Um erro que ocorre quando tentamos
acessar um elemento que excede o tamanho máximo do array ou em algumas outras ocasiões envolvendo
seu índice).

##

### <a name="input"></a> Entrada de Dados (Input)

Uma das tarefas mais comuns em programas Java e em qualquer outra linguagem de programação é a entrada de dados pelo usuário. 
Existem muitas maneiras de se fazer isso em Java, mas a mais comum é através da classe Scanner, que irei tratar neste tópico,
ele se encontra disponível na biblioteca padrão do Java, ou seja não precisaremos de dependências externas como baixar algo pela internet.

Pra usar a classe `Scanner`, você precisa primeiro importar a classe (Este conceito de importações você entenderá melhor
com o decorrer no tempo) no início do seu código:

```java
import java.util.Scanner;
```

Em seguida, você pode criar uma instância da classe Scanner (Que nem fizemos na seção de Arrays unidimensionais) e usar seus métodos para obter dados do usuário. 
Aqui está um exemplo bem simples que pede ao usuário para inserir seu nome e, em seguida, imprime uma saudação personalizada:

```java
import java.util.Scanner;

public class EntradaDeDados {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Digite seu nome: ");
        String nome = input.nextLine();
        
        System.out.println("Olá, " + nome + "!");
    }
}
```

Nesse exemplo, o método `nextLine()` é usado pra obter uma **linha inteira de entrada do usuário** (A função `nextLine()` 
usamos quando queremos obter `Strings`) do usuário que é armazenada na variável `nome`. 
A seguir, é impresso uma saudação personalizada na tela usando a concatenação de `String`.

Além do `nextLine()`, a classe Scanner possui vários outros métodos para obter diferentes tipos de entrada do usuário, 
incluindo `nextInt()`, `nextDouble()`, `nextBoolean()`, entre outros. Cada método é projetado para lidar com um tipo específico de dados.

É importante lembrar que a classe `Scanner` pode lançar exceções se houver problemas ao ler a entrada do usuário, 
como quando o usuário digita um valor que não pode ser convertido pro tipo esperado. Portanto, 
é uma boa prática usar as declarações `try-catch` (Trataremos mais sobre este assunto quando o repositório
de Orientação a Objetos estiver disponível) para lidar com essas exceções.
e garantir que o programa não pare de funcionar abruptamente.

##

#### Exemplos Adicionais De Entrada de Dados em Java

Para receber entrada de dados de diferentes tipos em Java, 
a classe Scanner possui métodos específicos pra cada tipo de dado. Alguns exemplos são:

`nextInt()`: lê um número inteiro;
`nextFloat()`: lê um número de ponto flutuante de precisão simples;
`nextDouble()`: lê um número de ponto flutuante de precisão dupla;
`nextBoolean()`: lê um valor booleano (true ou false);
`nextLine()`: lê uma linha completa de entrada como uma string.

Veja um exemplo de como usar o método `nextInt()` para ler um número inteiro:

```java
import java.util.Scanner;

public class EntradaDeDados {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Digite um número inteiro: ");
        int num = input.nextInt();
        
        System.out.println("O número digitado foi " + num);
    }
}
```

Este exemplo pede ao usuário para digitar um número inteiro e armazena o valor digitado na variável `num`. 
Em seguida, imprime na tela uma mensagem contendo o seu número.

Você também pode usar a classe `Scanner` para ler outros tipos de dados, 
como `float`, `double`, `boolean`, entre outros, usando os métodos correspondentes.

#### Mas... Como o Scanner funciona internamente?

O `Scanner` é uma classe da biblioteca padrão do Java que fornece métodos para ler dados do usuário ou de um arquivo 
(Sim, podemos ler dados guardados em arquivos com a classe Scanner). Confira aqui um [Artigo adicional da Alura](https://www.alura.com.br/artigos/lendo-arquivos-texto-em-java) que oferece um exemplo de como podemos usar o Scanner para ler arquivos.

Internamente, a classe Scanner usa expressões regulares para encontrar padrões de entrada e converter os dados em valores do tipo apropriado.

Quando você cria uma instância da classe `Scanner`, pode especificar a fonte de entrada de dados, 
que pode ser o sistema de entrada padrão (`System.in`) ou um arquivo.

Quando você chama um método de leitura, como `nextInt()` ou `nextLine()`, o Scanner lê a entrada até encontrar um padrão 
que corresponda ao tipo de dado solicitado. Por exemplo, ao usar o método `nextInt()`, o Scanner procura o 
próximo valor inteiro na entrada. Se encontrar um valor inteiro, converte esse valor para um inteiro e retorna esse valor.

Se a entrada não corresponder ao tipo de dado esperado, o `Scanner` lançará uma exceção do tipo `InputMismatchException`. 
Por exemplo, se você chamar o método `nextInt()` para ler um valor inteiro e a entrada contiver um 
valor de ponto flutuante, o Scanner lançará essa exceção.

Para lidar com exceções lançadas pelo Scanner, você pode usar uma declaração `try-catch`, como falei anteriormente. 
Além disso, é sempre uma boa prática verificar a entrada do usuário antes de tentar 
convertê-la pro tipo de dado desejado.

#### Buffering e Possíveis Problemas com o Scanner

O buffering é um conceito importante pra compreender a entrada e saída dos dados. Quando você lê ou escreve dados em Java, 
esses dados são armazenados em um buffer temporário antes de serem transferidos pro dispositivo de entrada ou saída.

O Scanner também usa um buffer interno para armazenar os dados de entrada antes de serem lidos pelo programa. 
Isso significa que, quando você chama um método de leitura, como `nextInt()` ou `nextLine()`, 
o `Scanner` lê dados do buffer em vez de ler diretamente da entrada.

Por isso, é bastante comum problemas ocorrerem com o Scanner devido a como este buffering funciona. 
Por exemplo, se você chamar o método `nextLine()` depois de chamar um método de leitura diferente, como `nextInt()`, 
pode ocorrer um problema de "quebra de linha". Isso ocorre porque, quando chamamos o método `nextInt()`, 
o `Scanner` deixa uma nova linha não lida no buffer. Quando você chama `nextLine()`, o Scanner lê 
essa nova linha em vez de esperar que o usuário digite uma nova entrada.

Para resolver esse problema, você pode chamar o método `nextLine()` imediatamente após chamar um método de leitura diferente, 
pra consumir a nova linha deixada pelo método anterior. Aqui está um exemplo:

```java
import java.util.Scanner;

public class EntradaDeDados {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Digite um número inteiro: ");
        int num = input.nextInt();
        input.nextLine(); // consome a nova linha deixada pelo nextInt()
        
        System.out.print("Digite uma string: ");
        String str = input.nextLine();
        
        System.out.println("Você digitou o número " + num + " e a string \"" + str + "\"");
    }
}
```

Neste exemplo, o método `nextLine()` é chamado imediatamente após o `nextInt()` para consumir a nova linha deixada pelo método anterior. 
Em seguida, o programa solicita ao usuário que digite uma string usando o método `nextLine()` e armazena a entrada em uma 
variável str. Finalmente, o programa imprime na tela os valores digitados pelo usuário.

Outro problema comum que pode ocorrer com o Scanner é o "`NoSuchElementException`". Isso ocorre quando o Scanner tenta ler dados da entrada, 
mas não há mais dados para serem lidos. Isso pode acontecer se o usuário pressionar `CTRL+Z ou CTRL+D` (dependendo do sistema operacional) 
durante a entrada de dados.

Para evitar essa exceção, você pode usar a condição `hasNext()` antes de chamar um método de leitura 
pra verificar se há mais dados para serem lidos. Aqui está um exemplo:

```java
import java.util.Scanner;

public class EntradaDeDados {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        while(input.hasNext()) {
            String line = input.nextLine();
            System.out.println("Você digitou: " + line);
        }
    }
}
```

Nesse exemplo, o programa usa um loop para ler as linhas de entrada até que não haja mais dados para serem lidos. 
O método `hasNext()` (TEM PROXIMO?) é usado pra verificar se existe um próximo dado, se houver, o loop continua executando. 
Dentro do loop, o programa lê cada linha de entrada usando o método nextLine() e imprime na tela a 
String "Você digitou: " seguida pela linha digitada pelo usuário.

Com isso, você pode garantir que o programa não vai tentar ler mais dados do que o usuário inseriu, evitando o `NoSuchElementException`.
