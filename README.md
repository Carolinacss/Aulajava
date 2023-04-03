# Tipos de Dados do Java

***Tipo de elementos visuais do Android Visual studio***



## *_Primitivos_*
 > ***Números Inteiros***

+ **byte**

O tipo de dado byte pode ter valores inteiros ou negativos e requer 8 bits para serem implementados. Sua faixa de valor está entre -128 até 127. Seu valor padrão é 0 (zero). Usado para salvar em memória grandes matrizes, economizando espaço porque um byte é quatro vezes menor que um número inteiro. Também pode ser usado no lugar de tipos de dados "int". 
```
Exemplo: 

byte a = 10, byte b = -20 ou
"\nMenor Byte: " + Byte.MIN_VALUE + ou
"\nMaior Byte: " + Byte.MAX_VALUE +
```
**short**

O tipo de dado short é um inteiro de complemento de dois com 16 bits, sendo seu valor padrão 0 (zero). Sua faixa de valor está entre o minímo -32.768 e máximo de 32.767.  e assim serve para economizar memória como o tipo de dado byte. O tipo short também é utilizado,por exemplo no registro da quantidade de apartamentos em um condominio. Sendo duas vezes menor que um inteiro.
```
Exemplo: 

short s = 10000, short r = -5000 ou
"\nMenor Short Int: " + Short.MIN_VALUE + ou
"\nMaior Short Int: " + Short.MAX_VALUE + 
```

**int**

O tipo de dado int é um inteiro com 4 bytes ou 32 bits e possui valor padrão 0 (zero). Sua faixa de valor está entre o minímo -2.147.483.648 e máximo de 2.147.483.647. O int geralmente é usado em certidão de óbito ou de nascimento, sendo um tipo de dado padrão para valores inteiros sem nenhum problema de memória.
```
Exemplo: 

int a  = 100000, int b = -200000 ou
"\nMenor Int: " + Integer.MIN_VALUE + ou
"\nMaior Int: " + Integer.MAX_VALUE +
```

**long**

O tipo de dado long é um inteiro com valor padrão 0 (zero) de 64 bits. Sua faixa de valor está entre o minímo de -9.223.372.036.854.775.808 até seu maximo de 9.223.372.036.854.775.807. Usado quando você precisa de uma faixa de valores maior do que a fornecida por int, por exemplo, contar todos os mosquitos do Pantanal Matogrossense. 
```
Exemplo:

"\nMenor Long: " + Long.MIN_VALUE + ou
"\nMaior Long:" + Long.MAX_VALUE +
```


> ***Números Bolleanos***


**boolean**

As variáveis booleanas são tipicamente empregadas para sinalizar alguma condição ou a ocorrência de algum evento em um programa Java, sendo usado para armazenar somente dois possíveis valores: verdadeiro e falso. 
Especifica um bit de informação, mas o "tamanho" não pode ser especificado precisamente.
```
Exemplo: 

boolean fim_do_arquivo = false;
```
 

> ***Tipo Caracter***

**char**

O tipo de dado char é um único caractere unicode de 16 bits. Sua faixa de valor está entre '\u0000' (ou 0) até '\uffff' (ou 65.535 inclusive). O char é usado para para armazenar caracteres como por exemplo o sexoPessoa, cujos valores são ‘F’ – feminino ou ‘M’ – masculino.
```
Exemplo: 

char tipoChar = 'C'; 
System.out.println("Valor do tipoChar = " + tipoChar); 
```

> ***Tipo Ponto Flutuante***

**float**

O tipo de dado float é de 32 bits de precisão única, sendo sua faixa de valor ilimitada. É recomendado utiliza-lo em vez de double, para caso você precise economizar memória em grandes arrays (matrizes) de número de ponto flutuante. O float nunca deve ser usado para valores precisos, como moeda. Seu valor padrão é 0.0f.
```
Exemplo: 

float f1 = 234.5f ou
"\nMenor Float: " + Float.MIN_VALUE + ou
"\nMaior Float: " + Float.MAX_VALUE +
```

**double**

O tipo de dado double é de 64 bits de precisão dupla, sendo valores ilimitados. Este dado é geralmente usado para valores decimais assim como float. O duble não deve ser usado para valores precisos, como moeda. Seu valor padrão é 0.0d.
```
Exemplo: 

 d1 = 12.3 ou
"\nMenor Double: " + Double.MIN_VALUE + ou
"\nMaior Double: " + Double.MAX_VALUE +
```
---
## *_Não primitivos_*

**classes**

O tipo de dado classes é representar objetos do mundo real, onde dentro dele declara atributos e métodos, representando as características e comportamentos desse objeto.
```
Sintaxe:

<modificador de acesso> class NomeDaClasse {

  // Local onde atributos, construtores e métodos são criados

}
```

**interfaces**

o Tipo de dado interfaces tem somente métodos e propriedades como assinaturas, cabendo à classe ultilizada a realizar a implementação delas, dando comportamentos práticos aos métodos.
```
Sintaxe:

public class nome_classe implements nome_interface
```

**arrays**

O tipo de dado array armazena mais de um valor em uma variável, ou seja, é um conjunto de variáveis, onde cada um tem a sua posição, assim armazenando sem precisar declarar cada uma para um valor.
```
Sintaxe:

tipo do objeto, como String, Integer, etc. [] nome de nosso array
```
---

# Estrutura de repetição do java
**For**

O for é uma estrutura de repetição, tambem chamada na tradução literal para a língua portuguesa “para”, que o mesmo permite que uma variável auxilie o controle da quantidade de repetições a serem executadas, sendo essas informações declarada no primeiro comando. Em seguida define até quando o for sera executado, onde normalmente é uma condição booleana em cima da variável de controle. Após isso indica o quanto a variável de controle será modificada no final de cada execução dentro do for.


```
Sintaxe:

for (bloco de inicialização; expressão booleana de validação; bloco de atualização)
{
     // comando que será executado até que a 
     // expressão de validação torne-se falsa 
}
```

**While**

O While é uma estrutura de repetição, tambem chamada na tradução literal para a língua portuguesa “enquanto”, onde utilizamos quando não sabemos exatamente quantas vezes o código será repetido até que seja valido. Essa condição deve-se ser uma expressão booleana e, enquanto ela for verdadeira, esta estrutura continuará executando as instruções contidas no seu corpo.

```
Sintaxe:

while (expressão booleana de validação) {
    // Trecho de código a ser repetido
}
```

**Do While**

O laço do / while é uma estrutura de repetição, tambem chamada na tradução literal para a língua portuguesa “faça…enquanto”, a condição somente é avaliada após executar o código pela primeira vez, assim, mesmo que a condição desse laço seja inválida antes de ele iniciar, suas instruções serão executadas pelo menos uma vez.

```
Sintaxe:

do
{
    // comando que será executado até que a 
     // expressão de validação torne-se falsa 
}
while (expressão booleana de validação);
```
___

# Estrutura condicional do java 

**if. else**

O if/else é uma estrutura de condição em que uma expressão booleana é analisada. Quando a condição que estiver dentro do if for verdadeira, ela é executada. Já o else é utilizado para definir o que é executado quando a condição analisada pelo if for falsa. Caso o if seja verdadeiro e, consequentemente executado, o else não é executado.

O if pode ser utilizado em conjunto com o else ou até mesmo sozinho, caso necessário.

Abaixo, temos um exemplo onde o if é utilizado em conjunto com o else.

```
package br.com.treinaweb;

public class Exemplo {
	
    public static void main(String[] args) {
        int resposta = 10;
        if (resposta == 10) {
            // Se a variável for igual a 10, a frase abaixo será escrita
            System.out.println(“Você acertou!”);
        } else {
            // Caso contrário, a frase abaixo será escrita
            System.out.println(“Você errou!”);
        }
    }
	
}
```




As condicionais if/else tem o comportamento booleano, ou seja, sempre teremos dois caminhos a seguir, um verdadeiro e outro falso. Desse modo, a palavra “if” significa “se” e a palavra “else” significa “senão”. Logo, é possível concluir em quais situações podemos usar as estruturas condicionais. Veja o exemplo a seguir:

Nesse primeiro exemplo, temos uma condição de que a variável idade seja maior do que 18. Se isso ocorre, a mensagem “A entrada é permitida” é printada no console. Caso essa condição não seja atendida, nada irá acontecer.

Já para o segundo exemplo, a situação é semelhante, porém, caso a condição não seja atendida, a mensagem “Entrada negada” será printada no console.






**switch case**

A palavra “switch” significa troca e a palavra “case” significa “caso”. Sendo assim ele compara o valor de cada caso, com uma variável ou uma expressão que seja avaliada em um valor primitivo e para evitar que as comparações continuem a ser executadas, o código é finalizado com a palavra-chave break, que encerra a execução da estrutura onde ele se encontra. Caso a variável não corresponda a nenhum dos casos testados, o último bloco será executado, chamado de default.

```
Exemplo:

package br.com.treinaweb;

public class Exemplo {
	
    public static void main(String[] args) {
        int mes = 2;
        switch (mes) {
            case 1:
                System.out.println(“O mês é janeiro”);
                break;
            case 2:
                System.out.println(“O mês é fevereiro”);
                break;
            case 3:
                System.out.println(“O mês é março”);
                break;
            default:
                System.out.println(“Mês inválido”);
                break;
        }
    }
	
}
```



 # REFERENCIAS
 
https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/

 https://www.dm.ufscar.br/~waldeck/curso/java/part22.html

 https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293

 https://www.javatpoint.com/pt/tipo-de-dado-em-java

 https://blog.betrybe.com/java/java-array/

 https://www.javaprogressivo.net/2012/08/java-o-tipo-char-armazenando-e.html

 https://www.jdevtreinamento.com.br/os-tipos-char-e-string-de-caracteres/

 https://www.devmedia.com.br/java-declaracao-e-utilizacao-de-classes/38374#:~:text=Uma%20classe%20%C3%A9%20um%20elemento,caracter%C3%ADsticas%20e%20comportamentos%20desse%20objeto

https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java#:~:text=Estruturas%20de%20repeti%C3%A7%C3%A3o%2C%20tamb%C3%A9m%20conhecidas,o%20for%20e%20o%20while.

https://productoversee.com/java-estruturas-de-repeticao/

https://glysns.gitbook.io/java-basico/controle-de-fluxo/estruturas-de-repeticao

https://glysns.gitbook.io/java-basico/controle-de-fluxo/estruturas-condicionais

https://comoprogramarjava.com.br/frameworks/java-base/if-else-java-estruturas-condicionais/