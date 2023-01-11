A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem e responder algumas perguntas com nosso modelo:

⇨ Existem outras entidades além dessas três?

⇨ Quais são os principais campos e tipos?

⇨ Como essas entidades estão relacionadas?

Vamos tentar pensar em 2 registros para cada entidade para checar o preenchimento das informações no nosso modelo.


Resposta: 

1. Sim, assim que fiz as ligações outras tabelas foram se abrindo.


2. Na tabela alunos: Nome e sobrenome é VARCHAR. Idade é INT.
   Turmas e cursos: Back, fron e banco de dados é VARCHAR.
   
3. Alunos pra Curso é muitos pra muitos. Muitos Aluno podem ter muitos cursos.
  Alunos pra turmas é muitos pra muitos. Muitos Aluno podem ter muitas turmas.
  Alunos pra Dados é 1 pra muitos. Cada aluno vai ter várias informações.

