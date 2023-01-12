# Modelagem-de-Dados-Projeto-M4
Projeto de banco de dados, modulo 4 resilia.

Além das 3 entidades achei interessante aplicar mais duas entidades sendo elas: Professores e endereço.

O principal campo foi a chave primaria para cada entidade possibilitando o relacionamento entre as entidades, outros campos principais foram nome, telefone, cpf, email, materia, horario de aula, cep.

As entidades estão relacionadas da seguinte forma:

Cursos - Alunos: (n:m) pois varios alunos podem ter diversos cursos e diversos cursos podem ter varios alunos

Cursos - Turmas: (1:n) pois um curso pode ter diversas turmas mas uma turma não pode fazer varios cursos.

Turmas - Professores: (n:m) pois ha a possibilidade de um professor fazer parte de varias turmas e uma turma ter varios professores.

Turmas - Alunos: (n:m): uma turma pode ter varios alunos e um aluno pode ter varias turmas em cursos diferentes.

Professores - Endereço: (n:m): um professor para um endereço apenas

Alunos - Endereço: (1:1) cada aluno tem apenas um endereço

