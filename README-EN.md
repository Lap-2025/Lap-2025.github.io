# Linguagens e Ambientes de Programação (2025 Edition)

(Para ler esta página em português, clique [aqui](README.md))

The curriculum of this course covers the fundamentals of programming language design, using functional programming in OCaml as a vehicle for a broader understanding of the concepts.

Corrections and suggestions are very much welcomed. (e-mail: i.chirica \<at> campus.fct.unl.pt)

## Announcements

Important announcements and changes to this page will be posted in this section.


## Referências

The primary reference for the course is the book "OCaml Programming: Correct + Efficient + Beautiful" by Michael R. Clarkson and others. The book is freely available online at OCaml Programming: [OCaml programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook/). In addition to the course materials, instructors encourage reading the book and completing the exercises it proposes. The book also includes lecture videos from Cornell University's CS3110 course, recorded during the pandemic.

During lectures, references will be made to materials from other books freely available online from the [Books On OCaml](https://ocaml.org/books) page. Namely:

* "OCaml from the Very Beginning" by John Whitington. The book is freely available online at [OCaml From the Very Beginning](https://ocaml-book.com/).

* "Introduction to OCaml" by Jason Hickey. The book is freely available online at [Introduction to OCaml](http://courses.cms.caltech.edu/cs134/cs134b/book.pdf).

* "Real World OCaml" by Yaron Minsky, Anil Madhavapeddy, and Jason Hickey. The book is freely available online at [Real World OCaml](https://dev.realworldocaml.org/).

## Instructors Office Hours

Office hours will be held by appointment via email the day before at the following locations and contacts:

| Teacher              | Office hours                | E-mail                              |
|----------------------|-----------------------------|-------------------------------------|
| João Costa Seco      | Monday 17h30 (P2/1-II)      | joao.seco \<at> fct.unl.pt          |
| Carla Ferreira       | Friday 10h (P2/14-II)       | carla.ferreira \<at> fct.unl.pt     |
| Artur Miguel Dias    | Wednesday 16h (room 120-II) | amd \<at> fct.unl.pt                |
| Ana Catarina Ribeiro | Tuesday 14h (TBD)           | acm.ribeiro \<at> campus.fct.unl.pt |
| Hugo Pereira         | Wednesday 09h (TBD)         | hg.pereira \<at> campus.fct.unl.pt  |
| Tomás Galvão         | Wednesday 11h (TBD)         | t.galvao \<at> campus.fct.unl.pt    |


## Syllabus

The plan for the theoretical classes is as follows: (This may change anytime without warning):

(The dates for the english version correspond to the lecture T1, and lab P1.)

|Week|Date|Theoretical|Practical|Materials|
|----|----|-----------|---------|---------|
|1|5/3|[Introduction. Logistics and evaluation.](slides/en/lec0.pdf) [The history and future of programming languages.](slides/en/lec1.pdf)|||
|1|P|||No labs. Though, we recommend you follow the [installation guide](praticas/en/lab1/installation.md).||
|2|11/3|[Functional programming. The OCaml language. Expressions, Variables, and Types. Library functions. Basic Input/Output.](slides/en/lec2.pdf)|||
|2|12/3|[Name declaration; function declaration, with and without parameters; Expression evaluation by substitution; Functions as values (first time); Partial function evaluation.](slides/en/lec3.pdf)|||
|2|P|Kick the tires: Tool installation. OCaml, Jupyter, VSCode + plugin.|[Kick the tires](praticas/en/lab1/lab1_kick_the_tires(1).ipynb) / [Exercises](praticas/en/lab1/lab1_exp_vars_types(2).ipynb)|[Installation guide](praticas/en/lab1/installation.md)|
|3|18/3|[Functions as values. Composition. Polymorphism. Type inference.](slides/en/lec4.pdf)|||
|3|19/3|[Function type; Polymorphism; Type inference.](slides/en/lec5.pdf)|||
|3|P|Exercises|[Exercises 1](praticas/en/lab2/lab2_basic_functions(1).ipynb) / [Exercises 2](praticas/en/lab2/lab2_io_unit_rec(2).ipynb)||
|4|25/3|[Recursive functions on natural numbers. Inductive vs. Iterative thinking.](slides/en/lec6.pdf)|||
|4|26/3|[Structured types: products and records. Exercises.](slides/en/lec7.pdf)|||
|4|P|Exercises|[Exercises](praticas/en/lab3/lab3_typeinf_comp_corr_inductive.ipynb)||
|5|1/4|[Structured types: Lists and recursive functions on lists. Exercises.](slides/en/lec8.pdf)|||
|5|2/4|Structured types: Higher-order programming: map and fold. Exercises. Presentation of the First Assignment.|| [Bullseye](handouts/bullseye.pdf)|
|5|P|Exercises|[Exercises](praticas/en/lab4/lab4_prod_sum_types_recs_lists.ipynb)||
|6|8/4|[Algebraic types, pattern matching.](slides/en/lec9.ipynb)|[Exercises](slides/en/lec9.ipynb)||
|6|9/4|[Inductive types. Inductive functions on inductive types.](slides/en/lec10.ipynb)|[Exercises](slides/en/lec10.ipynb)||
|6|P|Exercises|[Exercises](praticas/en/lab5/lab5_comb_higer_order_fun.ipynb)||
|7|14/4|Q&A|[Midterm example](tests/t1/en/teste_modelo_2324.ipynb)/[Midterm 2024](tests/t1/en/t1-2324.ipynb)|[Midterm 2024 (Solution)](tests/t1/en/solutions/t1-2324-solutions.ipynb)|
|7|16/4|||||
|7|16/4|First Test (40%)|[Test Solutions](slides/en/t1-2425.ipynb)||
|7|P|||||
|8|22/4|[Examples of inductive types: Binary search trees, N-ary trees.](slides/en/lec12.ipynb)|||
|8|23/4|||||
|8|P|||||
|8|27/4||Submission of the First Assignment||
|9|29/4|[Module System.](slides/en/lec12.pdf)|||
|9|30/4|(No Lecture - Expo FCT)|||
|9|P|||[Exercises](praticas/en/lab7/lab7_pairing_heap.ipynb)||
|10|6/5|Presentation of the Second and Third Assignments.||[Petri nets](handouts/petrinets.pdf)|
|10|7/5|[Data mutability. Memoization.](slides/en/lec14.pdf)|[More Memoization](slides/en/memoization.ipynb)||
|10|P|||[Exercises](praticas/en/lab8/lab8_pairing_heap_HO.ipynb)||
|11|13/5|[Asynchronous IO, Concurrency, Promises](slides/en/LAP%202025-Modules-EN.pdf)|[More concurrency](slides/en/concurrency.ipynb)||
|11|14/5|(No lecture)|||
|11|P|||[Exercises](praticas/en/lab9/lab_8_functor_pairing_heap.ipynb)||
|12|20/5|[Interpreters](slides/en/lec16.pdf)|||
|12|21/5|[Interpreters](slides/en/Interpreters.ipynb)|||
|12|-|||||
|13|27/5|Functional Reactive Programming.|||
|13|28/5|Q&A|||
|11|28/5||Submission of the Second and Third Assignments||
|13|30/5|Second Test (60%)|[Sample test](tests/t2/teste_en.pdf)||
|13|-|||||
|14|3/6|||||
|14|4/6|||||
|14|-|||||

