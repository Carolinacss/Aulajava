# Aulajava
***Tipos de Dados do Java***
***Estrutura de repetição do java***
***Estrutura condicional do java (if. else switch case)***


*_8 tipos de dados primitivos do Java._*

Números Inteiros:

**byte**
O tipo de dado byte pode ter valores inteiros ou negativos e requer 8 bits para serem implementados. Sua faixa de valor está entre -128 até 127. Seu valor padrão é 0 (zero). Usado para salvar em memória grandes matrizes, economizando espaço porque um byte é quatro vezes menor que um número inteiro. Também pode ser usado no lugar de tipos de dados "int".
Exemplo: byte a = 10, byte b = -20


**short**
O tipo de dado short é um inteiro de complemento de dois com 16 bits, sendo seu valor padrão 0 (zero). Sua faixa de valor está entre o minímo -32.768 e máximo de 32.767.  e assim serve para economizar memória como o tipo de dado byte. O tipo short também é utilizado,por exemplo no registro da quantidade de apartamentos em um condominio. Sendo duas vezes menor que um inteiro.
Exemplo: short s = 10000, short r = -5000


**int**
O tipo de dado int é um inteiro com 4 bytes ou 32 bits e possui valor padrão 0 (zero). Sua faixa de valor está entre o minímo -2.147.483.648 e máximo de 2.147.483.647. O int geralmente é usado em certidão de óbito ou de nascimento, sendo um tipo de dado padrão para valores inteiros sem nenhum problema de memória.
Exemplo: int a  = 100000, int b = -200000

**long**
O tipo de dado long é um inteiro com valor padrão 0 (zero) de 64 bits. Sua faixa de valor está entre o minímo de -9.223.372.036.854.775.808 até seu maximo de 9.223.372.036.854.775.807. Usado quando você precisa de uma faixa de valores maior do que a fornecida por int, por exemplo: 
Exemplo: long a = 100000L, long b = -200000L


**boolean**
O tipo de dado boolean é usado para armazenar somente dois possíveis valores: verdadeiro e falso. Este tipo de dado é usado por sinalizadores simples que localizam condições verdadeira/falsa.
Especifica um bit de informação, mas o "tamanho" não pode ser especificado precisamente.
Exemplo: boolean one = false

**char**
O tipo de dado char é um único caractere unicode de 16 bits. Sua faixa de valor está entre '\u0000' (ou 0) até '\uffff' (ou 65.535 inclusive). O tipo de data char é usado para para armazenar caracteres.
Exemplo: char letraA = 'A'

**float**
O tipo de dado float é um ponto flutuante IEEE 754 de 32 bits de precisão única. Sua faixa de valor é ilimitada. É recomendado usar um ponto flutuante (em vez de double) se você precisar economizar memória em grandes arrays (matrizes) de número de ponto flutuante. O tipo de dado float nunca deve ser usado para valores precisos, como moeda. Seu valor padrão é 0.0f.
Exemplo: float f1 = 234.5f

**double**
O tipo de dado double é um ponto flutuante IEEE 754 de 64 bits de precisão dupla. Seu valor é ilimitado. O tipo de dado double é geralmente usado para valores decimais assim como float. O tipo de dado double também não deve ser usado para precisar valores, como moeda. Seu valor padrão é 0.0d.
Exemplo: double d1 = 12.3

 ***REFERENCIAS***
 https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/
 https://www.dm.ufscar.br/~waldeck/curso/java/part22.html
 https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293
 https://www.javatpoint.com/pt/tipo-de-dado-em-java