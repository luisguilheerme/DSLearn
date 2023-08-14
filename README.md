# DSLearn
Projeto DSLearn com modelo de domínio complexo, desenvolvido durante o curso Java Spring Ultimate.

## ESPECIFICAÇÃO - Sistema DSLearn:
Visão geral do sistema DSLearn
O sistema consiste em uma plataforma de ensino que mantém informações de cursos, suas turmas e alunos. Os atores do sistema podem ser alunos e professores. 
Há também usuários administradores, que são os únicos autorizados a cadastrar cursos e turmas.
Um curso é composto de vários “recursos”, que são grupos de conteúdos. Estes recursos podem ser trilhas de aprendizado, bônus, links externos, e o próprio fórum de perguntas e respostas do curso. 
Cada recurso pode conter seções, e estas seções por sua vez é que vão conter as aulas, que podem ser conteúdos em vídeo e/ou texto, ou tarefas para serem entregues pelos alunos.
Uma tarefa pode ter um peso, uma data de entrega, um número de questões e a quantidade mínima de acertos necessários para ser aceita. 
Quando um aluno entrega a tarefa, esta fica aguardando pelo feedback do professor, e ela pode ser aceita ou rejeitada.
Cada nova turma do curso corresponde a uma oferta ou edição deste curso, que possui uma data de início e fim. 
Diferentes ofertas do mesmo curso podem ter pequenas variações no conteúdo, conforme a necessidade de customização para cada turma.


### Modelo Conceitual
![Modelo conceitual]([https://github.com/luisguilheerme/assets/blob/main/dscommerce/modelo_conceitual.png](https://github.com/luisguilheerme/assets/blob/main/dslearn/modelo-conceitual.png))

### Tecnologias utilizadas
-Java

-Spring Boot

-JPA / Hibernate

-Maven

