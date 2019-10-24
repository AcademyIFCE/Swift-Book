# Swift Book

Esse projeto tem como objetivo traduzir e disponibilizar gratuitamente em português o livro *The Swift Programming Language (swift 5.1)*. 

## O que já pode ser traduzido

O livro em inglês está lentamente sendo migrado para o formato de *Markdown*  antes de ser traduzido. A seguintes *Sessões* já estão em formato *Markdown* e já podem ser traduzidas através de Pull Requests:

- [x] About Swift
- [x] Version Compatibility
- [x] A Swift Tour
  - [x] Intro
  - [x] Simple Values
  - [x] Control Flow
  - [x] Functions and Closures
  - [x] Objects and Classes
  - [x] Enumerations and Structures
  - [x] Protocols and Extensions
  - [x] Error Handling
  - [x] Generics
- [ ] The Basics
  - [ ] Intro
  - [ ] Constants and Variables
  - [ ] Floating-Point Numbers
  - [ ] Type Safety and Type Inference
  - [ ] Numeric Type Conversion
  - [ ] Assertions and Preconditions
- [x] Basic Operators
  - [x] Intro
  - [x] Terminology
  - [x] Assignment Operator
  - [x] Arithmetic Operators
  - [x] Compound Assignment Operators
  - [x] Comparison Operators
  - [x] Ternary Conditional Operator
  - [x] Nil-Coalescing Operator
  - [x] Range Operators
  - [x] Logical Operators
- [ ] Strings And Characters
  - [ ] Intro
  - [ ] String Literals
  - [ ] Initializing an Empty String
  - [ ] String Mutability
  - [ ] Strings Are Value Types
  - [ ] Working with Characters
  - [ ] Concatenating Strings and Characters
  - [ ] String Interpolation
  - [ ] Unicode
  - [ ] Counting Characters
  - [ ] Accessing and Modifying a String
  - [ ] Substrings
  - [ ] Unicode
  - [ ] Comparing Strings
  - [ ] Unicode Representations of Strings
- [ ] Collection Types
  - [ ] Intro
  - [ ] Mutability of Collections
  - [ ] Arrays
  - [ ] Sets
  - [ ] Performing Set Operations
  - [ ] Dictionaries
- [ ] Control Flow
  - [ ] Intro
  - [ ] For-In Loops
  - [ ] While Loops
  - [ ] Conditional Statements
  - [ ] Control Transfer Statements
  - [ ] Early Exit
  - [ ] Checking API Availability
- [ ] Closures
  - [X] Intro
  - [X] Closure Expressions
  - [ ] Trailing Closures
  - [ ] Capturing Values
  - [ ] Closures Are Reference Types
  - [ ] Escaping Closures
  - [ ] Autoclosures
- [ ] Enumerations
  - [ ] Intro
  - [ ] Enumeration Syntax
  - [ ] Matching Enumeration Values with a Switch Statement
  - [ ] Iterating over Enumeration Cases
  - [ ] Associated Values
  - [ ] Raw Values
  - [ ] Recursive Enumerations
- [ ] Structures and Classes
  - [ ] Intro
  - [ ] Comparing Structures and Classes
  - [ ] Structures and Enumerations Are Value Types
  - [ ] Classes Are Reference Types
- [ ] Methods
  - [ ] Intro
  - [ ] Instance Methods
  - [ ] Type Methods
- [ ] Optional Chaining
  - [ ] Intro
  - [ ] Optional Chaining as an Alternative to Forced Unwrapping
  - [ ] Defining Model Classes for Optional Chaining
  - [ ] Accessing Properties Through Optional Chaining
  - [ ] Calling Methods Through Optional Chaining
  - [ ] Accessing Subscripts Through Optional Chaining
  - [ ] Linking Multiple Levels of Chaining
  - [ ] Chaining on Methods with Optional Return Values
- [ ] Nested Types
  - [ ] Intro
  - [ ] Nested Types in Action
  - [ ] Referring to Nested Types
- [ ] Generics
  - [x] Intro
  - [x] The Problem That Generics Solve
  - [x] Generic Functions
  - [ ] Type Parameters
  - [ ] Naming Type Parameters
  - [ ] Generic Types
  - [ ] Extending a Generic Type
  - [ ] Type Constraints
  - [ ] Associated Types
  - [ ] Generic Where Clauses
  - [ ] Extensions with a Generic Where Clause
  - [ ] Associated Types with a Generic Where Clause 
  - [ ] Generic Subscripts
- [ ] Access Control
  - [ ] Intro
  - [ ] Modules and Source Files
  - [ ] Access Levels
  - [ ] Access Control Syntax
  - [ ] Custom Types
  - [ ] Subclassing
  - [ ] Constants, Variables, Properties, and Subscripts 
  - [ ] Initializers
  - [ ] Protocols
  - [ ] Extensions
  - [ ] Generics
  - [ ] Type Aliases
- [ ] Adavanced Operators
  - [ ] Intro
  - [ ] Bitwise Operators
  - [ ] Overflow Operators
  - [ ] Precedence and Associativity
  - [ ] Operator Methods
  - [ ] Custom Operators

Cada item dessa lista terá uma Issue. **Antes de pegar um desses items para traduzir, verifique a Issue e descubra se alguém já não está traduzindo**. Quando alguém pegar uma dessas `sessao/topico` para traduzir, terá o nome atribuído a Issue.

## Convenções

Para facilitar o processo de revisão e diminuir as inconsistências entre traduções, quem contribuir deverá seguir algumas convenções:

* Não traduzir palavras reservadas.
* Na dúvida entre traduzir ou não determinado termo, deixar o termo em inglês.
* Criar Branches no padrão `sessao/topico`  e traduzir por *Sessao* e *Tópico* (textos mais internos dentro da *Sessão*).
* *Pull Requests* devem ser feitos para `master`, marcando a Issue que resolvem.

## Criação de Branches

A tradução deverá ser feita através de Forks, com branches nomeadas por sessão e tópico, com letras minúsculas, seguindo o seguinte padrão:

`nome-da-sessao/nome-do-topico`

Exemplo:
`a-swift-tour/control-flow`

Caso não existam tópicos para determinada sessão, a branch deve ter somente o nome da sessão:
`nome-da-sessao`

## Pull Requests

Os Pull Requests devem ser feitos diretamente para a branch `master`, e marcar a Issue que está resolvendo. A revisão será feita avaliando a tradução em si, a coerência do texto da tradução, e a coerência com as traduções anteriores.

## Começe Agora! 🎉  

Existe pouco ou nenhum material gratuito em português de Swift / Desenvolvimento iOS básico. Contribuindo com a tradução desse livro, você pode estar ajudando alguém que não tem $$$ para comprar material a estudar. Além disso, você mesmo estará estudando, revisando, e aprendendo recursos da linguagem que você talvez não conheça.

Com esforço coletivo, conseguiremos finalizar a tradução e facilitar o aprendizado de desenvolvimento iOS para quem não sabe inglês. 
