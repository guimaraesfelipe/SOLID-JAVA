# Princípios de SOLID para POO

<div align="center">
  <img src="https://user-images.githubusercontent.com/64509839/182949415-8556d997-38b7-4af4-8fce-f7877031ed27.png">
</div><br />

Os princípios SOLID são cinco princípios de design de código orientado a objeto que basicamente tem os seguintes objetivos: 
Tornar o código mais entendível, claro e conciso;
Tornar o código mais flexível e tolerante a mudanças;
Aumentar a adesão do código aos princípios da orientação a objetos (Coesão, Encapsulamento, Acoplamento).

## 1º Princípio: Single Responsibility Principle (SRP)
Uma classe (ou módulo, função, etc) deve ter um e apenas um motivo para mudar. by Uncle Bob
###### *Implementado no commit "applying SRP"*

## 2º Princípio: Open Closed Principle (OCP)
Entidades de software (classes, módulos, funções, etc) devem estar abertas para extensão, porém fechadas para modificação. by Bertrand Meyer
###### *Implementado no commit "applying OCP"*

## 3º Princípio: Liskov Substitution Principle (LSP)
Se q(x) é uma propriedade demonstrável dos objetos x de tipo T, então q(y) deve ser verdadeiro para objetos y de tipo S, onde S é subtipo de T. by Barbara Liskov
Em outras palavras, ao utilizar ações como herança em seu sistema, precisamos nos atentar para que atributos e/ou métodos que não fazem sentido, não sejam herdados pela subclasse, optando em algumas vezes por aplicar uma composição de classes em seu código no lugar da herança.
###### *Implementado no commit "applying LSP"*

## 4º Princípio: Interface Segregation Principle (ISP)
Uma classe não deveria ser forçada a depender de métodos que não utilizará. by Uncle Bob
###### *Implementado no commit "applying ISP"*

## 5º Princípio: Dependency Inversion Principle (DIP)
Abstrações não devem depender de implementações. Implementações devem depender de abstrações. by Uncle Bob
No projeto, como utilizamos as abstrações, interfaces e polimorfismo durante a implementação do principio OCP (Open Closed Principle) acabamos diretamente implementando o DIP (Dependency Inversion Principle).
###### *Implementado no commit "applying OCP"*
