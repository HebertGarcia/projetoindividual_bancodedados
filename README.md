# projetoindividual_bancodedados
Novo sistema de acompanhamento - módulo 4


⇨ Existem outras entidades além dessas três? <br>
Foi criado mais uma entidade, tabela (turnos).<br>

⇨ Quais são os principais campos e tipos?<br>
Foram criados dois tipos de campos. (campo 1 = cursos) e (campo 2 = alunos).<br>

CAMPO 1 > CURSOS<br>
turmas = INT<br>
cursos = VARCHAR<br>
turnos = VARCHAR<br>

CAMPO 2 > ALUNOS<br>
alunos front-end = VARCHAR, INT e DATE<br>
alunos back-end = VARCHAR, INT e DATE<br>
alunos full stack = VARCHAR, INT e DATE<br>

⇨ Como essas entidades estão relacionadas?<br>
cursos (front-end; back-end e full stack) 1:1 para cada dados dos alunos para cada tipo de curso (front-end; back-end e full stack).<br>
cursos (front-end; back-end e full stack) n:m para cada curso tem três tipos de turmas (201,202 e 203).<br>
cursos (front-end; back-end e full stack) n:m para cada curso tem três tipos de turnos (manhã,tarde e noite).<br>
