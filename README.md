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
| João Costa Seco      | 4ª-feira 17h (Gab. P2/1-II) | joao.seco \<arroba> fct.unl.pt          |
| Carla Ferreira       |                             | carla.ferreira \<arroba> fct.unl.pt     |
| Artur Miguel Dias    | 4ª-feira 16h (sala 120-II)  | amd \<arroba> fct.unl.pt                |
| Ana Catarina Ribeiro | 3ª-feira 14h (TBD)          | acm.ribeiro \<arroba> campus.fct.unl.pt |
| Hugo Pereira         | 4ª-feira 09h (TBD)          | hg.pereira \<arroba> campus.fct.unl.pt  |
| Tomás Galvão         | 4ª-feira 11h (TBD)          | t.galvao \<arroba> campus.fct.unl.pt  |


## Programa

O plano tentativo para as aulas é o seguinte (pode haver mudanças a
qualquer altura):

| Semana | Data | Teóricas                                                                                                                                                                      | Práticas                                                                                                         | Materiais |
|--------|------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-----------|
| 1      | 6/3  | Apresentação. Logística e avaliação. A história e o futuro das linguagens de programação.                                                                                     |                                                                                                                  |           |
| 1      | P    |                                                                                                                                                                               | Não há aulas práticas. No entanto a [instalação das ferramentas](praticas/pt/install.md) é recomendada.          |           |
| 2      | 10/3 | Programação funcional. A linguagem OCaml. Expressões, Variáveis e tipos. Funções biblioteca. Input/Output básico.                                                             |                                                                                                                  |           |
| 2      | 13/3 | Declaração de nomes; declaração de funções, com e sem parâmetros; Avaliação de expressões por substituição; Funções como valores (primeira vez); Avaliação parcial de funções |                                                                                                                  |           |
| 2      | P    |                                                                                                                                                    Kick the tires: Instalação das ferramentas. OCaml, Jupyter, VSCode + plugin. | [Kick the tires](praticas/pt/kick_the_tires.ipynb) / [Exercícios](praticas/pt/basic.ipynb) |     [Instruções de instalação](praticas/pt/install.md)    |
| 3      | 17/3 | Funções como valores. Composição. Polimorfismo. Inferência de tipos.                                                                                                          |                                                                                                                  |           |
| 3      | 20/3 | Tipo função; Polimorﬁsmo; Inferência de tipos.                                                                                                                                |                                                                                                                  |           |
| 3      | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 4      | 24/3 | Funções recursivas sobre naturais. Pensamento Indutivo vs. pensamento Iterativo.                                                                                              |                                                                                                                  |           |
| 4      | 27/3 | Tipos estruturados: produtos e registos. Exercícios.                                                                                                                          |                                                                                                                  |           |
| 4      | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 5      | 31/3 | Tipos estruturados: Listas e funções recursivas sobre listas. Exercícios.                                                                                                     |                                                                                                                  |           |
| 5      | 3/4  | Tipos estruturados: Programação de ordem superior: map e fold. Exercícios. Apresentação Primeiro Trabalho.                                                                    |                                                                                                                  |           |
| 5      | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 6      | 7/4  | Tipos algébricos, pattern matching.                                                                                                                                           |                                                                                                                  |           |
| 6      | 10/4 | Tipos indutivos. Funções indutivas sobre tipos indutivos.                                                                                                                     |                                                                                                                  |           |
| 6      | P    |                                                                                                                                                                               | Exercícios de Tipos algébricos, pattern matching                                                                 |           |
| 7      | 14/4 | Q&A                                                                                                                                                                           |                                                                                                                  |           |
| 7      | 16/4 | Primeiro Teste (40%)                                                                                                                                                                 |                                                                                                                  |           |
| 7      | 17/4 | (Férias Páscoa)                                                                                                                                                      |                                                                                                                  |           |
| 7      | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 8      | 21/4 | (Férias Páscoa)                                                                                                                                                               |                                                                                                                  |           |
| 8      | 24/4 | Exemplos de tipos indutivos: Árvores binárias de pesquisa, Árvores n-árias.                                                                                                   |                                                                                                                  |           |
| 8      | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 8      | 27/4 |                                                                                                                                                                               | Entrega Primeiro Trabalho                                                                                        |           |
| 9      | 28/4 | Apresentação do segundo trabalho                                                                                                                                              |                                                                                                                  |           |
| 9      | 30/4 | Expo FCT                                                                                                                                                                      |                                                                                                                  |           |
| 9      | 1/5  | (Feriado)                                                                                                                                                                     |                                                                                                                  |           |
| 9      | -    |                                                                                                                                                                               |                                                                                                                  |           |
| 10     | 5/5  | Sistema de Módulos                                                                                                                                                            |                                                                                                                  |           |
| 10     | 8/5  | Mutabilidade de dados. Memoization                                                                                                                                            |                                                                                                                  |           |
| 10     | -    |                                                                                                                                                                               |                                                                                                                  |           |
| 11     | 12/5 | I/O Assíncrono, Concorrência, Promessas                                                                                                                                       |                                                                                                                  |           |
| 11     | 15/5 | Functional Reactive Programming                                                                                                                                               |                                                                                                                  |           |
| 11     | P    |                                                                                                                                                                               |                                                                                                                  |           |
| 11     | 18/5 |                                                                                                                                                                               | Entrega Segundo Trabalho                                                                                         |           |
| 12     | 19/5 | Apresentação do terceiro trabalho                                                                                                                                             |                                                                                                                  |           |
| 12     | 22/5 | Interpretadores                                                                                                                                                               |                                                                                                                  |           |
| 12     | -    |                                                                                                                                                                               |                                                                                                                  |           |
| 13     | 26/5 | Interpretadores                                                                                                                                                               |                                                                                                                  |           |
| 13     | 29/5 | Q&A                                                                                                                                                                           |                                                                                                                  |           |
| 13     | 30/5 | Segundo Teste (60%)                                                                                                                                                           |                                                                                                                  |           |
| 13     | -    |                                                                                                                                                                               |                                                                                                                  |           |
| 14     | 2/6  |                                                                                                                                                                               | Entrega Terceiro Trabalho                                                                                        |           |
| 14     | 5/6  |                                                                                                                                                                               |                                                                                                                  |           |
| 14     | -    |                                                                                                                                                                               |                                                                                                                  |           |

(As datas dos trabalhos e testes são provisórias e podem ser
alteradas.)
