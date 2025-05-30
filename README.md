# Linguagens e Ambientes de Programação (Edição 2025)

(to read this page in English, click [here](README-EN.md))

O programa desta unidade curricular cobre os fundamentos do desenho
das linguagens de programação utilizando a programação funcional em
OCaml como veículo para a compreensão alargada dos conceitos.

Correções e sugestões são bem-vindas. (e-mail: i.chirica \<arroba> campus.fct.unl.pt)

## Avisos

Nesta seção serão colocados os avisos importantes, e alterações a esta
página.

## Referências

A principal referência para a unidade curricular é o livro "OCaml
programming: Correct + Efficient + Beautiful" de Michael R. Clarkson e
outros. O livro está disponível online de forma gratuita em [OCaml
programming: Correct + Efficient +
Beautiful](https://cs3110.github.io/textbook/). Os docentes encorajam
a leitura do livro e a realização dos exercícios propostos no mesmo,
para além dos propostos nos materiais desta unidade curricular. O
livro também dispõe de vídeos das aulas na universidade de Cornell que
foram filmadas para o curso de CS3110, durante a pandemia.

Haverá referências durante as aulas a materiais de outros livros
disponíveis de forma gratuita online a partir da página [Books On
OCaml](https://ocaml.org/books). Nomeadamente:

- "OCaml From the Very Beginning" de John Whitington. O livro está
  disponível online de forma gratuita em [OCaml From the Very
  Beginning](https://ocaml-book.com/).

- "Introduction to OCaml" de Jason Hickey. O livro está disponível
  online de forma gratuita em [Introduction to
  OCaml](http://courses.cms.caltech.edu/cs134/cs134b/book.pdf).

- "Real World OCaml" de Yaron Minsky, Anil Madhavapeddy e Jason
  Hickey. O livro está disponível online de forma gratuita em [Real
  World OCaml](https://dev.realworldocaml.org/).

## Atendimento Docente

O Atendimento em horário de dúvidas será feito com marcação prévia por e-mail no dia anterior nos seguintes locais e usando os respetivos contatos:

| Docente              | Horário                     | E-mail                                 |
|----------------------|-----------------------------|----------------------------------------|
| João Costa Seco      | 2ª-feira 17h30 (P2/1-II)    | joao.seco \<arroba> fct.unl.pt          |
| Carla Ferreira       | 6º-feira 10h (P2/14-II)      | carla.ferreira \<arroba> fct.unl.pt     |
| Artur Miguel Dias    | 4ª-feira 16h (sala 120-II)  | amd \<arroba> fct.unl.pt                |
| Ana Catarina Ribeiro | 3ª-feira 14h (TBD)          | acm.ribeiro \<arroba> campus.fct.unl.pt |
| Hugo Pereira         | 4ª-feira 09h (TBD)          | hg.pereira \<arroba> campus.fct.unl.pt  |
| Tomás Galvão         | 4ª-feira 11h (TBD)          | t.galvao \<arroba> campus.fct.unl.pt  |


## Programa

O plano tentativo para as aulas é o seguinte (pode haver mudanças a
qualquer altura):

|Semana|Data|Teóricas|Práticas|Materiais|
|------|----|--------|--------|---------|
|1|6/3|[Apresentação. Logística e avaliação.](slides/pt/aula0.pdf) [A história e o futuro das linguagens de programação.](slides/pt/aula1.pdf)|||
|1|P|||Não há aulas práticas. No entanto a [instalação das ferramentas](praticas/pt/lab1/installation.md) é recomendada.|
|2|10/3|[Programação funcional. A linguagem OCaml. Expressões, Variáveis e tipos. Funções biblioteca. Input/Output básico.](slides/pt/aula2.pdf)|||
|2|13/3|[Declaração de nomes; declaração de funções, com e sem parâmetros; Avaliação de expressões por substituição; Funções como valores (primeira vez); Avaliação parcial de funções](slides/pt/aula3.pdf)|||
|2|P|Kick the tires: Instalação das ferramentas. OCaml, Jupyter, VSCode + plugin.|[Kick the tires](praticas/pt/lab1/lab1_kick_the_tires(1).ipynb) / [Exercícios](praticas/pt/lab1/lab1_exp_vars_types(2).ipynb)|[Instruções de instalação](praticas/pt/lab1/installation.md)|
|3|17/3|[Funções como valores. Composição. Polimorfismo. Inferência de tipos.](slides/pt/aula4.pdf)|||
|3|20/3|[Tipo função; Polimorfismo; Inferência de tipos.](slides/pt/aula5.pdf)|||
|3|P|Exercícios|[Exercícios 1](praticas/pt/lab2/lab2_basic_functions(1).ipynb) / [Exercícios 2](praticas/pt/lab2/lab2_io_unit_rec(2).ipynb)||
|4|24/3|[Funções recursivas sobre naturais. Pensamento Indutivo vs. pensamento Iterativo.](slides/pt/aula6.pdf)|||
|4|27/3|[Tipos estruturados: produtos e registos. Exercícios.](slides/pt/aula7.pdf)|||
|4|P|Exercícios|[Exercícios](praticas/pt/lab3/lab3_typeinf_comp_corr_inductive.ipynb)||
|5|31/3|[Tipos estruturados: Listas e funções recursivas sobre listas. Exercícios.](slides/pt/aula8.pdf)|||
|5|3/4|Tipos estruturados: Programação de ordem superior: map e fold. Exercícios. Apresentação Primeiro Trabalho.||[Bullseye](handouts/bullseye.pdf)|
|5|P|Exercícios|[Exercícios](praticas/pt/lab4/lab4_prod_sum_types_recs_lists.ipynb)||
|6|7/4|[Tipos algébricos, pattern matching.](slides/pt/aula9.ipynb)|[Exercícios](slides/pt/aula9.ipynb)||
|6|10/4|[Tipos indutivos. Funções indutivas sobre tipos indutivos. Exemplos de tipos indutivos: Árvores binárias de pesquisa, Árvores n-árias](slides/pt/aula10.ipynb)|[Exercícios](slides/pt/aula10.ipynb)||
|6|P|Exercícios|[Exercícios](praticas/pt/lab5/lab5_comb_higer_order_fun.ipynb)||
|7|14/4|Q&A|[Teste modelo](tests/t1/pt/teste_modelo_2324.ipynb)/[Primeiro teste 2024](tests/t1/pt/t1-2324.ipynb)|[Resolução do primeiro teste 2024](tests/t1/pt/solutions/t1-2324-solutions.ipynb)|
|7|16/4|Primeiro Teste (40%)|[Teste Resolvido](slides/en/t1-2425.ipynb)||
|7|17/4|(Férias Páscoa)|||
|7|P|||||
|8|21/4|(Férias Páscoa)|||
|8|24/4|[Exemplos de tipos indutivos: Árvores binárias de pesquisa, Árvores n-árias.](slides/pt/aula10.ipynb)|||
|8|P|||||
|8|27/4||Entrega Primeiro Trabalho||
|9|28/4|Não houve aula|||
|9|30/4|Expo FCT|||
|9|1/5|(Feriado)|||
|9|P|||[Exercícios](praticas/pt/lab7/lab7_pairing_heap.ipynb)||
|10|5/5|Resolução do Teste. Apresentação do segundo e terceiro trabalho. [Continuação das Árvores binárias de pesquisa, Árvores n-árias.](slides/pt/aula12.ipynb)||[Petri nets](handouts/petrinets.pdf)|
|9|P|[Funções de ordem superior em estruturas de dados funcionais.](slides/pt/aula12.ipynb). [Módulos](slides/pt/aula12.pdf)||[Exercícios](praticas/pt/lab8/lab8_pairing_heap_HO.ipynb)|
|10|8/5| [Mutabilidade de dados. Memoization](slides/pt/aula14.pdf) |||
|10|-|||||
|11|12/5|[Sistema de Módulos.](slides/pt/aula15_.pdf)|||
|11|P|Functores - Estruturas de Dados Modulares|[Exercícios](praticas/pt/lab9/lab9_functor_pairing_heap.ipynb)||
|11|15/5|[I/O Assíncrono, Concorrência, Promessas](slides/pt/aula15_.pdf)|[Mais concorrência](slides/en/concurrency.ipynb)||
|11|P|||||
|12|19/5|[Interpretadores](slides/pt/aula16.pdf)|||
|12|P|Apoio aos Projectos.|[Petri nets](handouts/petrinets.pdf)|
|12|22/5|[Interpretadores](slides/pt/Interpreters.ipynb)|||
|12|-|||||
|13|26/5||||
|11|28/5||Entrega Segundo e Terceiro Trabalhos||
|13|29/5|Q&A|||
|13|30/5|Segundo Teste (60%)|[Sample test](tests/t2/teste_en.pdf)||
|13|-|||||
|14|5/6|||||
|14|-|||||
