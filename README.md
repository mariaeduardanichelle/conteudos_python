# Conteúdos Python  ![](/src/images/iconpython.ico)
## Tipos primitivos
|Tipo   |                                          |
|-------|------------------------------------------|
| int   | números inteiros                         |
| float | números reais/números de ponto flutuantes|
| bool  | valores lógicos/booleanos (True/False)   |
| str   | valores caracteres/string                |
|complex| números complexos                        |

### Convertendo um tipo
##### No Python é possível alterar o tipo de um dado como nos exemplos a seguir:
int para float:
```shell
float(9)
```
float para int
```shell
int(9.0)
```
str para int
```shell
int('9')
```
### Checando os tipos
##### Para checar o tipo de um dado pode-se usar:
```shell
ti = input('Digite algo: ')
print(f'O tipo primitivo desse valor é: {type(ti)}')
```
##### Para checar o tipo de um dado temos os seguintes métodos:
(Retorna True se o dado for, se não for retorna False)
```shell
ti = input('Digite algo: ')
print(f'É alfabético? {ti.isalpha()}')
print(f'É um alfabético numérico? {ti.isalnum()}')
print(f'É um decimal? {ti.isdecimal()}')
print(f'É um digito? {ti.isdigit()}')
print(f'É ASCII? {ti.isascii()}')
print(f'É identificador? {ti.isidentifier()}')
print(f'É minúsculo? {ti.islower()}')
print(f'É numérico? {ti.isnumeric()}')
print(f'É printable? {ti.isprintable()}')
print(f'Só tem espeaços? {ti.isspace()}')
print(f'Está capitalizada? {ti.istitle()}')
print(f'É maiúsculo? {ti.isupper()}')
```
## Operadores aritméticos
|Operador         | Sinal |
|-----------------|-------|
|adicão           |   +   |
|subtração        |   -   |
|multiplicação    |   *   |
|divisão          |   /   |
|potência         |  **   |
|divisão inteira  |  //   |
|resto da divisão |   %   |
### Ordem de procedência
**1°**: ( )

**2°**: **

**3°**: *, /, //, %

**4°**: +, -

## Funções embutidas (built-in); abs, round, pow, len)
*Absoluto*
```shell
abs(8)
```
*Arredondando 3 casas após a virgula*
```shell
round(3.14151922,3)
```
*Arredondando para o inteiro mais próximo*
```shell
round(2.5)
```
*Potência*
```shell
pow(2, 10)
```
*Comprimento*
```shell
len('IFC')
```

## Variáveis
*As variáveis servem para armazenar dados.

*As variáveis não precisam ser declaradas, pois o Python a tipagem é dinâmica. Ou seja, elas são criadas na primeira atribuição, e a Python descobre os tipos dessa variável por si só.

*O nome das variáveis não podem conter caracteres especiais (!.,/\+*=), não podem conter espaços (podem conter _), devem começar por uma letra (A-Z ou a-z), após a primeira letra pode conter letras, números e underscore.

*Podem receber valores diferentes com o passar do tempo (valor antigo é desconsiderado).

*Apenas um único valor é armazenado nela.

*Podem conter vários tipos de dados.

### Palavras reservadas em Python
As seguintes palavras não podem ser usadas para nomear uma variável:

|False |def |if    |raise  |
|------|----|------|-------|
|None  |del |import| return|
|True  |elif|in    | try   |
|and   |else|is    | while |
|as    |except|lambda|with |
|assert|finally|nonlocal|yield|
|break|for|not|class|
|form|or|continue|global|
|pass|-|-|-|

### Variáveis e operadores
Atribuindo o valor 1 à variável var_test:
```shell
var_test = 1
```
Imprimindo o valor da variável
```shell
print(var_test)
```

### Declaração múltipla
```shell
pessoa1, pessoa2, pessoa3 = 'Maria', 'José', 'Tobias'
print(pessoa1)
print(pessoa2)
print(pessoa3)
```

### Concatenação de variáveis
```shell
nome = 'Steve'
sobrenome = 'Jobs'
fullname = nome + ' ' + sobrenome
print(fullname)
```
