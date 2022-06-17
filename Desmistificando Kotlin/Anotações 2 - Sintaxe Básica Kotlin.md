# Olá Mundo e Tipos de dados

Link Importante para testar alguns codigos online sem baixar o android studio

[Playground Kotlin](https://play.kotlinlang.org)



# Tipos de dados

- Int 
- Long
- Float
- Double
- Array
- Boolean
- Char
- Byte
- Short
- Null!



1) println**(Int**.MAX_VALUE**)**

2) println**(Float**.MAX_VALUE**)**

3) println**(Long**.MAX_VALUE)

4) println**(Byte**.MAX_VALUE)

5) println**(Short**.MAX_VALUE)

​	

**Conversão de dados**

1) toByte**( )**
2) toShort**( )**
3) toInt**( )**
4) toLong**( )**
5) toFloat**( )**
6) toDouble**( )**
7) toChar**( )**





# Declarando Variáveis 



**Var**

Variável que pode ter o valor alterado durante o código

**var** currentAge **=** 22

**var** currentAge**:Int?**

currentAge **=** null ou 22

**Valor definido e alterado durante a execução**



**Val**

Variável que terá seu valor atribuido.

**val** currentAge **=** 22

**val** currentAge**:Int?**

currentAge **=** null ou 22

**Valor definido durante a execução**



**Const Val**

Constante que é atribuido durante a compilação e esse valor só poderá ser consultado no código.

**const val** MIN_AGE **=** 16

**const val** MAX_AGE **=** 68

**Valor definido durante a compilação**



# Possíveis erros na Declaração de Variáveis



**var** currentAge

currentAge **=** 22 //ERRO!

Uma variável **não pode** ser declarada **sem tipo e sem atribuição.**



**var** currentYear **= **"Ano"

currentYear **=** 2021 //ERRO!

Uma **variável com inferência de tipo** só receberá **valores do mesmo tipo que a sua primeira atribuição.**



# Null e Operadores aritméticos básicos



- Qualquer tipo pode ser nulo, porém deve ser explicitado através da interrogação (?)
- A inferência de tipo não atribui nullability



# Operadores Aritméticos



![operadores aritméticos](C:\Users\Desenvolvedor\Desktop\operadores aritméticos.png)





# Operadores Comparativos



![operadores comparativos](C:\Users\Desenvolvedor\Desktop\operadores comparativos.png)





# Operadores Lógicos e Operadores In e Range



![lógicos](C:\Users\Desenvolvedor\Desktop\lógicos.png)



### In e Range



![in e range](C:\Users\Desenvolvedor\Desktop\in e range.png)





# Manipulando Strings

- Possuem diversos métodos associados

  indexação, concatenação, comparação, formatação

### Indexação

- Stringo como array
- First(), last(), String.length, String[index]



![image-20220615153542167](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615153542167.png)



### Concatenação



![image-20220615153711001](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615153711001.png)



### Formatação



![image-20220615154449297](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615154449297.png)







# Qual a diferença entre Empty e Blank



São métodos de comparação que retorna booleano se o método estiver correto.



Empty se estiver vazia

Blank se estiver em branco



**Se o tamanho da string (s.length) for 0 está empty e Blank**

**Se o tamanho for > 0 mas todos os caracteres são espaçoes em branco, está em blank mas não empty**



# Introdução a Funções



- Prefixo **Fun nomeDaFunção(nome:Tipo):TipoRetorno{}**
- Funções anônimas, single-line, line, extensões, Lambdas, ordem superior



### Simplificando uma função



![image-20220615155929100](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615155929100.png)

Todas as linhas de códigos retornam a mesma função, somente foi de uma forma simplificada para reduzir de 3 para 1 linha de código sem interferir em nada na funcionalidade do mesmo.



# Funções de Ordem Superior

- Recebem outra função ou lambda por parâmetro
- Bastante úteis para a generalização de funções e tratamento de erros

![image-20220615160413705](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615160413705.png)



# Single-line e Funções/extensões



- Prefixo **Fun nomeDaFuncao(nome:Tipo) = retorno**
- Função de uma única linha
- Infere o tipo de retorno



![image-20220615162142941](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615162142941.png)



### Extensões 

- Prefixo **Fun Tipo.nomeDaFuncao()**

- Cria uma função que só pode ser chamada por um tipo especifico, cujo o valor pode ser referenciado dentro da função através da palavra **this**

  

![image-20220615162346242](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615162346242.png)



Somente a String.



# Estruturas de Controle



- if/else, when, elvis operator
- Pode ser utilizado tanto para controle quanto para atribuição
- Pode ser encadeado com multiplas estruturas 

![image-20220615162850129](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615162850129.png)



# Atribuições, when e Elvis operator



### Atribuição



- O valor atribuido tem que estar na ultima linha do bloco

- A condicional não pode usar chaves se só fizer a atribuição

  

![image-20220615163156602](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615163156602.png)



### When

- Equivalente ao switch de outras linguagens
- Aceita tanto valores quanto condicionais
- Aceita range como case

![image-20220615163635944](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615163635944.png)



### Elvis Operator

- O mais próximo que a linguagem possui de um operador ternário
- Verifica se um valor é nulo e apresenta uma opção caso seja
- Pode ser encadeado 

![image-20220615163834883](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615163834883.png)



# Estrututra de Repetição



- While, do..while, for e forEach
- Aceita os comandos **in, range, until, downTo** e **step**

![image-20220615164738932](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615164738932.png)



![image-20220615165631486](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615165631486.png)



# Certificado de CONCLUSÃO



![image-20220615170732432](C:\Users\Desenvolvedor\AppData\Roaming\Typora\typora-user-images\image-20220615170732432.png)