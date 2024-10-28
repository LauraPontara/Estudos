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
