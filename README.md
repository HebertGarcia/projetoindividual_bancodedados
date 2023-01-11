# projetoindividual_bancodedados
Novo sistema de acompanhamento - módulo 4


⇨ Existem outras entidades além dessas três?
Foi criado mais uma entidade, tabela (turnos).

⇨ Quais são os principais campos e tipos?
Foram criados dois tipos de campos. (campo 1 = cursos) e (campo 2 = alunos).

CAMPO 1 > CURSOS
turmas = INT
cursos = VARCHAR
turnos = VARCHAR

CAMPO 2 > ALUNOS
alunos front-end = VARCHAR, INT e DATE
alunos back-end = VARCHAR, INT e DATE
alunos full stack = VARCHAR, INT e DATE

⇨ Como essas entidades estão relacionadas?
cursos (front-end; back-end e full stack) 1:1 para cada dados dos alunos para cada tipo de curso (front-end; back-end e full stack).
cursos (front-end; back-end e full stack) n:m para cada curso tem três tipos de turmas (201,202 e 203) e cada turma tem todos os turnos.
cursos (front-end; back-end e full stack) n:m para cada curso tem três tipos de turnos (manhã,tarde e noite) e cada turno tem todos as turmas.
