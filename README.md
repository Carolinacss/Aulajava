# Aulajava
***Tipos de Dados do Java***
***Estrutura de repetição do java***
***Estrutura condicional do java (if. else switch case)***
***Tipo de elementos visuais do Android Visual studio***


* Dados primitivos do Java.*

***Números Inteiros***

**byte**

O tipo de dado byte pode ter valores inteiros ou negativos e requer 8 bits para serem implementados. Sua faixa de valor está entre -128 até 127. Seu valor padrão é 0 (zero). Usado para salvar em memória grandes matrizes, economizando espaço porque um byte é quatro vezes menor que um número inteiro. Também pode ser usado no lugar de tipos de dados "int".
```
Exemplo: byte a = 10, byte b = -20 ou
"\nMenor Byte: " + Byte.MIN_VALUE + ou
"\nMaior Byte: " + Byte.MAX_VALUE +
```
**short**

O tipo de dado short é um inteiro de complemento de dois com 16 bits, sendo seu valor padrão 0 (zero). Sua faixa de valor está entre o minímo -32.768 e máximo de 32.767.  e assim serve para economizar memória como o tipo de dado byte. O tipo short também é utilizado,por exemplo no registro da quantidade de apartamentos em um condominio. Sendo duas vezes menor que um inteiro.
```
Exemplo: short s = 10000, short r = -5000 ou
"\nMenor Short Int: " + Short.MIN_VALUE + ou
"\nMaior Short Int: " + Short.MAX_VALUE + 
```

**int**

O tipo de dado int é um inteiro com 4 bytes ou 32 bits e possui valor padrão 0 (zero). Sua faixa de valor está entre o minímo -2.147.483.648 e máximo de 2.147.483.647. O int geralmente é usado em certidão de óbito ou de nascimento, sendo um tipo de dado padrão para valores inteiros sem nenhum problema de memória.
```
Exemplo: int a  = 100000, int b = -200000 ou
"\nMenor Int: " + Integer.MIN_VALUE + ou
"\nMaior Int: " + Integer.MAX_VALUE +
```

**long**

O tipo de dado long é um inteiro com valor padrão 0 (zero) de 64 bits. Sua faixa de valor está entre o minímo de -9.223.372.036.854.775.808 até seu maximo de 9.223.372.036.854.775.807. Usado quando você precisa de uma faixa de valores maior do que a fornecida por int, por exemplo, contar todos os mosquitos do Pantanal Matogrossense. 
```
"\nMenor Long: " + Long.MIN_VALUE + ou
"\nMaior Long:" + Long.MAX_VALUE +
```

***Números Bolleanos***

**boolean**

As variáveis booleanas são tipicamente empregadas para sinalizar alguma condição ou a ocorrência de algum evento em um programa Java, sendo usado para armazenar somente dois possíveis valores: verdadeiro e falso. 
Especifica um bit de informação, mas o "tamanho" não pode ser especificado precisamente.
```
Exemplo: boolean fim_do_arquivo = false;
```
 

***Tipo Caracter***

**char**

O tipo de dado char é um único caractere unicode de 16 bits. Sua faixa de valor está entre '\u0000' (ou 0) até '\uffff' (ou 65.535 inclusive). O char é usado para para armazenar caracteres como por exemplo o sexoPessoa, cujos valores são ‘F’ – feminino ou ‘M’ – masculino.
```
Exemplo: char tipoChar = 'C'; 
System.out.println("Valor do tipoChar = " + tipoChar); 
```

***Tipo Ponto Flutuante***

**float**

O tipo de dado float é de 32 bits de precisão única, sendo sua faixa de valor ilimitada. É recomendado utiliza-lo em vez de double, para caso você precise economizar memória em grandes arrays (matrizes) de número de ponto flutuante. O float nunca deve ser usado para valores precisos, como moeda. Seu valor padrão é 0.0f.
```
Exemplo: float f1 = 234.5f ou
"\nMenor Float: " + Float.MIN_VALUE + ou
"\nMaior Float: " + Float.MAX_VALUE +
```

**double**

O tipo de dado double é de 64 bits de precisão dupla, sendo valores ilimitados. Este dado é geralmente usado para valores decimais assim como float. O duble não deve ser usado para valores precisos, como moeda. Seu valor padrão é 0.0d.
```
Exemplo: double d1 = 12.3 ou
"\nMenor Double: " + Double.MIN_VALUE + ou
"\nMaior Double: " + Double.MAX_VALUE +
```
*_não primitivo_*

**classes** 


**interfaces**



**arrays**

O tipo de dado array armazena mais de um valor em uma variável, ou seja, é um conjunto de variáveis, onde cada um tem a sua posição, assim armazenando sem precisar declarar cada uma para um valor.

Sintaxe:
```
tipo do objeto, como String, Integer, etc. [] nome de nosso array
```

 ***REFERENCIAS***
 
https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/
 https://www.dm.ufscar.br/~waldeck/curso/java/part22.html
 https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293
 https://www.javatpoint.com/pt/tipo-de-dado-em-java
 https://blog.betrybe.com/java/java-array/
 https://www.javaprogressivo.net/2012/08/java-o-tipo-char-armazenando-e.html
 https://www.jdevtreinamento.com.br/os-tipos-char-e-string-de-caracteres/