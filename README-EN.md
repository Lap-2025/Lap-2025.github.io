# Linguagens e Ambientes de Programação (Edição 2025)

(Para ler esta página em português, clique [aqui](README.md))

The curriculum of this course covers the fundamentals of programming language design, using functional programming in OCaml as a vehicle for a broader understanding of the concepts.


## Announcements

Important announcements and changes to this page will be posted in this section.


## Referências

The primary reference for the course is the book "OCaml Programming: Correct + Efficient + Beautiful" by Michael R. Clarkson and others. The book is freely available online at OCaml Programming: [OCaml programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook/). In addition to the course materials, instructors encourage reading the book and completing the exercises it proposes. The book also includes lecture videos from Cornell University's CS3110 course, recorded during the pandemic.

During lectures, references will be made to materials from other books freely available online from the [Books On OCaml](https://ocaml.org/books) page. Namely:

"OCaml from the Very Beginning" by John Whitington. The book is freely available online at [OCaml From the Very Beginning](https://ocaml-book.com/).

"Introduction to OCaml" by Jason Hickey. The book is freely available online at [Introduction to OCaml](http://courses.cms.caltech.edu/cs134/cs134b/book.pdf).

"Real World OCaml" by Yaron Minsky, Anil Madhavapeddy, and Jason Hickey. The book is freely available online at [Real World OCaml](https://dev.realworldocaml.org/).

## Instructors Office Hours

Office hours will be held by appointment via email at the following locations and contacts:

| Docente | Horário | E-mail |
| -------- | -------- | -------- |
| João Costa Seco | 4ª-feira 17h (Gab. P2/1-II) | joao.seco@fct.unl.pt |
| Carla Ferreira |  | carla.ferreira@fct.unl.pt |
| Artur Miguel Dias |  | amd@fct.unl.pt |

## Syllabus

The plan for the theoretical classes is as follows: (This may change anytime without warning):

| Semana | Data | Teóricas | Práticas | Materiais |
| -------- | -------- | -------- | -------- | -------- |
| 1 | 5/3 | Apresentação. Logística e avaliação. A história e o futuro das linguagens de programação. | | 
| 1 |  P  | | Não há aulas práticas | 
|
| 2 | 11/3 | Programação funcional. A linguagem OCaml. Expressões, Variáveis e tipos. Funções biblioteca. Input/Output básico. | |
| 2 | 12/3 | Declaração de nomes; declaração de funções, com e sem parâmetros; Avaliação de expressões por substituição; Funções como valores (primeira vez); Avaliação parcial de funções |  |
| 2 | P  | | Kick the tyres: Instalação das ferramentas. OCaml, Jupyter, VSCode + plugin. | 
|
| 3 | 18/3 | Funções como valores. Composição. Polimorfismo. Inferência de tipos. | |
| 3 | 19/3 | Tipo função; Polimorﬁsmo; Inferência de tipos. | |
| 3 | P  | | |
|
| 4 | 25/3 | Funções recursivas sobre naturais. Pensamento Indutivo vs. pensamento Iterativo. | |
| 4 | 26/3 | Tipos estruturados: produtos e registos. Exercícios. | |
| 4 | P  | | |
|
| 5 | 1/4 | Tipos estruturados: Listas e funções recursivas sobre listas. Exercícios. | |
| 5 | 2/4 | Tipos estruturados: Programação de ordem superior: map e fold. Exercícios. Apresentação Primeiro Trabalho. | |
| 5 | P  | | |
|
| 6 | 8/4 | Tipos algébricos, pattern matching. | |
| 6 | 9/4 | Tipos indutivos. Funções indutivas sobre tipos indutivos. | |
| 6 | P  | | Exercícios de Tipos algébricos, pattern matching |
|
| 7 | 15/4 | Q&A | |
| 7 | 16/4 |  | |
| 7 | 15/4, ou 16/4  | Primeiro Teste (40%) | |
| 7 | P  | | |
|
| 8 | 22/4 |  | |
| 8 | 23/4 | Exemplos de tipos indutivos: Árvores binárias de pesquisa, Árvores n-árias. | |
| 8 | P  | | |
| 8 | 27/4  | | Entrega Primeiro Trabalho |
|
| 9 | 29/4 | Apresentação do segundo trabalho | |
| 9 | 30/4 | (No Lecture - Expo FCT) | |
| 9 | -  | | |
|
| 10 | 6/5 | Sistema de Módulos | |
| 10 | 7/5 | Mutabilidade de dados. Memoization | |
| 10 | -  | | |
|
| 11 | 13/5 | I/O Assíncrono, Concorrência, Promessas | |
| 11 | 14/5 | Functional Reactive Programming | |
| 11 | P  | | |
| 11 | 18/5  | | Entrega Segundo Trabalho |
|
| 12 | 20/5 | Apresentação do terceiro trabalho | |
| 12 | 21/5 | Interpretadores | |
| 12 | -  | | |
|
| 13 | 27/5 | Interpretadores | |
| 13 | 28/5 | Q&A | |
| 13 | 30/5 ou 31/5 | Segundo Teste (60%) | |
| 13 | -  | | |
|
| 14 | 3/6 | | | 
| 14 | 4/6 | | |
| 14 | 2/6 | | Entrega Terceiro Trabalho | 
| 14 | -   | | |


(As datas dos trabalhos e testes são provisórias e podem ser alteradas.)


| Week| Date| Theoretical| Practical| Materials
| -------- | -------- | -------- | -------- | -------- |
| 1|5/3|Introduction. Logistics and evaluation. The history and future of programming languages.||
| 1|P||No practical classes|
| 2|11/3|Functional programming. The OCaml language. Expressions, Variables, and Types. Library functions. Basic Input/Output.||
2|12/3|Name declaration; function declaration, with and without parameters; Expression evaluation by substitution; Functions as values (first | time); Partial function evaluation.||
| 2|P||Kick the tyres: Tool installation. OCaml, Jupyter, VSCode + plugin.|
| 3|18/3|Functions as values. Composition. Polymorphism. Type inference.||
| 3|19/3|Function type; Polymorphism; Type inference.||
| 3|P|||
| 4|25/3|Recursive functions on natural numbers. Inductive vs. Iterative thinking.||
| 4|26/3|Structured types: products and records. Exercises.||
| 4|P|||
| 5|1/4|Structured types: Lists and recursive functions on lists. Exercises.||
| 5|2/4|Structured types: Higher-order programming: map and fold. Exercises. Presentation of the First Assignment.||
| 5|P|||
| 6|8/4|Algebraic types, pattern matching.||
| 6|9/4|Inductive types. Inductive functions on inductive types.||
| 6|P||Exercises on Algebraic types, pattern matching.|
| 7|15/4|Q&A||
| 7|16/4|||
| 7|15/4, or 16/4|First Test (40%)||
| 7|P|||
| 8|22/4|||
| 8|23/4|Examples of inductive types: Binary search trees, N-ary trees.||
| 8|P|||
| 8|27/4||Submission of the First Assignment|
| 9|29/4|Presentation of the Second Assignment||
| 9|30/4|(No Lecture - Expo FCT)||
| 9|-|||
| 10|6/5|Module System||
| 10|7/5|Data mutability. Memoization.||
| 10|-|||
| 11|13/5|Asynchronous I/O, Concurrency, Promises.||
| 11|14/5|Functional Reactive Programming.||
| 11|P|||
| 11|18/5||Submission of the Second Assignment|
| 12|20/5|Presentation of the Third Assignment||
| 12|21/5|Interpreters||
| 12|-|||
| 13|27/5|Interpreters||
| 13|28/5|Q&A||
| 13|30/5 or 31/5|Second Test (60%)||
| 13|-|||
| 14|3/6|||
| 14|4/6|||
| 14|2/6||Submission of the Third Assignment|
| 14|-|||

(The assignment and test dates are provisional and may be subject to change.)