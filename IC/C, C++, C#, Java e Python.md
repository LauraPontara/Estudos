# Linguagens de Programação C, C++, C#, Java e Python

### C :
* Orientada a Procedimentos
  
Hello World!
```c
#include <stdio.h>

int main(){
  printf("Hello World!\n");
  return 0;
}
```

#### Tipos de dados primitivos:

| *Tipo*  | *Obs* |
| --------| ----- |
| char  | Caractere  |
| int  | Inteiro  |
| float | Ponto Flutuante |
| double | Ponto Flutuante  |
| char[] | Cadeia de caracteres |

#### Comandos de entrada e saída:
* Saída = `printf()`
* Entrada principal = `scanf(tipo da variável, &nome da variável)` ou `scanf(tipo da variável, nome do array)`
# 
### c++ :
* Oferece suporte para programação Orientada a Procedimentos
* Orientada a Objetos
  
Hello World!
```c++
#include <iostream>

int main(){
  std::cout << "Hello World!\n";
  return 0;
}
```
```c++
#include <iostream>
using namespace std;

int main(){
  cout << "Hello World!\n";
  return 0;
}
```
#### Tipos de dados primitivos:

| *Tipo*  | *Obs* |
| --------| ----- |
| char  | Caractere  |
| int  | Inteiro  |
| float | Ponto Flutuante |
| double | Ponto Flutuante  |
| bool | Booleano |
| char[] | Cadeia de caracteres |

#### Comandos de entrada e saída:

* Saída/Impressão de dados = `cout <<` direção da seta indica para os dados estão saindo em direção ao objeto
* Entrada de dados = `cin >>` direção das setas indica para qual var os dados irão
```c++
#include <iostream> // Biblioteca necessária para entrada e saída
using namespace std;

int main() {
    // Comando de saída
    cout << "Olá! Qual é o seu nome? ";

    string nome; // Declara uma variável para armazenar o nome
    // Comando de entrada
    cin >> nome; // Lê o nome fornecido pelo usuário

    // Saída personalizada
    cout << "Prazer em te conhecer, " << nome << "!" << endl;

    return 0; // Indica que o programa terminou com sucesso
}
```
#

### C# :
* Toda orientada a objetos
* Nome de MÉTODOS começam com letra maiúscula
* Necessária a declaração de uma classe no começo do código
* Funções são métodos

Hello World!
```c#
using System;

class MainClass { //nome da classe
  public static void Main (string[] args) { //Declaração do método Main
    Console.WriteLine ("Hello World!"); 
  }
}
```
#### Tipos de dados primitivos:

| *Tipo*  | *Obs* |
| --------| ----- |
| char  | Caractere  |
| int, sbyte, short e long  | Inteiro com sinal  |
| byte, ushort, uint e ulong | Inteiro sem Sinal |
| double, float e decimal | Ponto Flutuante |
| bool | Booleano |
| String | Cadeia de caracteres |

#### Comandos de entrada e saída:

* Saída = `Console.Write()` ou `Console.WriteLine()`
    - Console.WriteLine() muda de linha após a impressão dos dados que estão dentro dos parênteses
  
* Entrada de dados = `Console.ReadLine()`
    - Lê dados e SEMPRE retorna em formato de STRING
```c#
using System;

class Program
{
    public static void Main(string[] args)
    {
        string nome;
        int idade;

        Console.Write("Qual é o seu nome? ");
        nome = Console.ReadLine(); // Lê o nome do usuário

        Console.Write("Qual é a sua idade? ");
        idade = int.Parse(Console.ReadLine()); // Lê e converte a idade para inteiro

        // Imprime uma frase com os dados fornecidos
        Console.WriteLine("Olá, "+nome+"! Você tem "+idade+" anos.");
    }
}
```
# 

### Java:
* Orientada a Objetos
* Iniciamos declarando uma classe
* Métodos com letras minúsculas

Hello World!
```java
class MainClass { //nome da classe
  public static void main (String[] args) { //Declaração do método main
    System.out.println ("Hello World!"); 
  }
}
```
#### Tipos de dados primitivos:

| *Tipo*  | *Obs* |
| --------| ----- |
| int, byte, short e long  | Inteiro |
| double, float | Ponto Flutuante |
| char | Caractere | 
| boolean | Booleano |
| classe String | Cadeia de caracteres |

#### Comandos de entrada e saída:

* Saída = `System.out.print()` ou `System.out.println()`
  - `System.out.println()` ao final da impressão, muda de linha
* Entrada =
  ```java
  import java.util.Scanner; // Importa a classe Scanner
  class Main {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in); // Cria um objeto Scanner

        System.out.print("Qual é o seu nome? ");
        String nome = entrada.nextLine(); // Lê uma linha de texto

        System.out.print("Qual é a sua idade? ");
        int idade = entrada.nextInt(); // Lê um inteiro

        // Imprime uma frase com os dados fornecidos
        System.out.println("Olá, " + nome + "! Você tem " + idade + " anos.");

        entrada.close(); // Fecha o scanner para evitar vazamentos de recursos
    }
  }

  
#

### Python :
* Orientada a objetos
  
Hello World!
```python
print("Hello World!")
```
#### Tipos de dados primitivos:

| *Tipo*  | *Obs* |
| --------| ----- |
| int | Inteiro |
| float | Ponto Flutuante |
| bool | Booleano |
| str | Cadeia de caracteres |

#### Comandos de entrada e saída:

* Saída = `print()`
* Entrada de dados = `input()`
    - Retorna o dado lido em formato de string
    - Para ler dados numéricos: `valor = int/float(input("Digite um valor: "))`

```python
# Solicita o nome do usuário
nome = input("Qual é o seu nome? ")

# Solicita a idade do usuário
idade = input("Qual é a sua idade? ")

# Imprime uma frase com os dados fornecidos
print(f"Olá, {nome}! Você tem {idade} anos.")
```
```python
nome = input("Digite seu primeiro nome: ")
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura: "))
print("{0} tem {1} anos de idade e mede {2}m.".format(nome, idade, altura)) #Por POSIÇÃO DAS VARIÁVEIS
print(nome,"tem",idade,"anos de idade e mede",altura,"m.")
```
 A f-string (f"...") permite incorporar variáveis diretamente na string.
 
 ## Operadores aritméticos e relacionais:

<img src="https://github.com/user-attachments/assets/3b75fe68-8b42-424c-a1ef-d2fc0dd2d0b0"  width="450">

<img src="https://github.com/user-attachments/assets/8388c518-5961-4a7d-8f65-ca384b509353"  width="450">

Exemplo em C:
```c
#include <stdio.h>

int main(void) {
  int a = 5, b = 3;
  int soma, subt, mult, quoc, resto, inc, dec;
  float divi;
  
  soma = a+b;
  printf("%d + %d = %d\n", a, b, soma);
  subt = a-b;
  printf("%d - %d = %d\n", a, b, subt);  
  mult = a*b;
  printf("%d * %d = %d\n", a, b, mult);  
  divi = (float)a/b;  //Dá resultado 4.5
  printf("%f / %d = %f\n", (float)a, b, divi);  
  quoc = a/b; // dá resultado 4 (divisão inteira)
  printf("%d / %d = %d\n", a, b, quoc);  
  resto= a%b;
  printf("%d %% %d = %d\n", a, b, resto);  
  inc = a;
  printf("Antes do incremento o valor da variavel inc = %d.\n", inc);
  inc++;
  printf("Apos o incremento o valor da variavel inc = %d.\n", inc);  
  dec = b;
  printf("Antes do decremento o valor da variavel dec = %d.\n", dec);
  dec--;
  printf("Apos o decremento o valor da variavel dec = %d.\n", dec);
  return 0;
}
```

Exemplo em C++:
```c++
#include <iostream>
using namespace std;

int main(void) {
  int a = 5, b = 3;
  int soma, subt, mult, quoc, resto, inc, dec;
  float divi;
  
  soma = a+b;
  cout << a << " + " << b << " = " << soma << "\n";
  subt = a-b;
  cout << a << " - " << b << " = " << subt << "\n";
  mult = a*b;
  cout << a << " * " << b << " = " << mult << "\n";
  divi = (float)a/b;
  cout << a << " / " << b << " = " << divi << "\n";
  quoc = a/b;
  cout << a << " / " << b << " = " << quoc << "\n";
  resto= a%b;
  cout << a << " % " << b << " = " << resto << "\n";
  inc = a;
  cout << "Antes do incremento o valor da variavel inc = " << inc << ".\n";
  inc++;
  cout << "Apos do incremento o valor da variavel inc = " << inc << ".\n";
  dec = b;
  cout << "Antes do decremento o valor da variavel inc = " << dec << ".\n";
  dec--;
  cout << "Apos o decremento o valor da variavel inc = " << dec << ".\n";
  return 0;
}
```

Exemplo em C#:
```c#
using System;

class MainClass {
  public static void Main (string[] args) {
    int a = 5, b = 3;
    int soma, subt, mult, quoc, resto, inc, dec;
    float divi;
  
    soma = a+b;
    Console.WriteLine(a+" + "+b+" = "+soma);
    subt = a-b;
    Console.WriteLine(a+" - "+b+" = "+subt);
    mult = a*b;
    Console.WriteLine(a+" * "+b+" = "+mult);
    divi = (float)a/b;
    Console.WriteLine((float)a+" / "+b+" = "+divi);
    quoc = a/b;
    Console.WriteLine(a+" / "+b+" = "+quoc);
    resto= a%b;
    Console.WriteLine(a+" % "+b+" = "+resto);
    inc = a;
    Console.WriteLine("Antes do incremento o valor da variavel inc = "+inc);
    inc++;
    Console.WriteLine("Apos o incremento o valor da variavel inc = "+inc);  
    dec = b;
    Console.WriteLine("Antes do decremento o valor da variavel dec = "+dec);
    dec--;
    Console.WriteLine("Apos o decremento o valor da variavel dec = "+dec);
  }
}
```

Exemplo em Java:
```java
class Main {
  public static void main(String[] args) {
    int a = 5, b = 3;
    int soma, subt, mult, quoc, resto, inc, dec;
    float divi;
  
    soma = a+b;
    System.out.println(a+" + "+b+" = "+soma);
    subt = a-b;
    System.out.println(a+" - "+b+" = "+subt);
    mult = a*b;
    System.out.println(a+" * "+b+" = "+mult);
    divi = (float)a/b;
    System.out.println((float)a+" / "+b+" = "+divi);
    quoc = a/b;
    System.out.println(a+" / "+b+" = "+quoc);
    resto= a%b;
    System.out.println(a+" % "+b+" = "+resto);
    inc = a;
    System.out.println("Antes do incremento o valor da variavel inc = "+inc);
    inc++;
    System.out.println("Apos o incremento o valor da variavel inc = "+inc);  
    dec = b;
    System.out.println("Antes do decremento o valor da variavel dec = "+dec);
    dec--;
    System.out.println("Apos o decremento o valor da variavel dec = "+dec);
  }
}
```

Exemplo em Python:
```python
a = 5 #Não há necessidade de tipigem de variáveis 
b = 3
   
soma = a+b
print(a," + ",b," = ",soma)
subt = a-b
print(a," - ",b," = ",subt)
mult = a*b
print(a," * ",b," = ",mult)
divi = a/b  #Divisão exata com casa decimal
print(a," / ",b," = ",divi)
quoc = a//b #Divisão inteira
print(a," // ",b," = ",quoc)
resto = a%b  #Resto
print(a," % ",b," = ",resto)
inc = a
print("Antes do incremento o valor da variavel inc = ",inc)
inc += 1 #Incremento
print("Apos o incremento o valor da variavel inc = ",inc)
dec = b
print("Antes do decremento o valor da variavel dec = ",dec)
dec -= 1
print("Apos o decremento o valor da variavel dec = ",dec)
```

## Comandos de fluxo de código

#### IF:
* Em python, os blocos de comandos de cada if são identificado pela identação, sem necessidade de chaves
<img src="https://github.com/user-attachments/assets/770cdac6-cc74-458e-b32c-54ff3dad6778"  width="300">

```python

if condição:
        <bloco de comandos>

if condição:
        <bloco de comandos>
else:
        <bloco de comandos>

if condição:
        <bloco de comandos>
elif condição:
        <bloco de comandos>
...
elif condição:     #Tipo de else if
  <bloco de comandos>
else:
    <bloco de comandos> 
```

Exemplos:

<img src="https://github.com/user-attachments/assets/b9185c35-2430-4be6-8123-d8ffdabcd089"  width="300">
<img src="https://github.com/user-attachments/assets/10d85d6c-6b28-4277-81de-c98a54585929"  width="300">
<img src="https://github.com/user-attachments/assets/6c3bdc98-b3ed-4c35-a2f6-605de0561762"  width="300">
<img src="https://github.com/user-attachments/assets/1bb42093-469a-4d47-a6bd-a0d516b643e3"  width="300">
<img src="https://github.com/user-attachments/assets/0faedede-fadb-45d3-a0a7-4c475cae2c19"  width="300">

## Comandos de Repetição:

<img src="https://github.com/user-attachments/assets/7ef6711e-4aa4-4bee-9f90-7e4dbe98975f"  width="300">
<img src="https://github.com/user-attachments/assets/dac81209-24d3-436b-8979-ab3e3cfbef96"  width="300">
<img src="https://github.com/user-attachments/assets/db82f831-53cb-45e0-a9f5-35321f18073e"  width="300">
<img src="https://github.com/user-attachments/assets/97a1d19b-d403-49eb-943e-29ca440944e7"  width="300">
<img src="https://github.com/user-attachments/assets/8a5422c7-a0a7-47e3-8f4b-eb9d4470825e"  width="300">


