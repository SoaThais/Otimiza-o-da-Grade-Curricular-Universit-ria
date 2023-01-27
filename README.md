# Otimização da Grade Curricular Universitária

Trabalho desenvolvido para a disciplina DCC163 - Pesquisa Operacional por:
* Maria Eduarda Ribeiro Facio
* Thaís de Jesus Soares

Nos cursos de graduação, comumente é disponibilizado aos discentes uma grade curricular que pode ser empregada como um guia de quais matérias pegar a cada período. Essa grade, entretanto, é feita de forma geral e estática, ou seja, não se adapta à evolução acadêmica de cada aluno individualmente.

Com isso em mente, o problema proposto foi desenvolver um modelo que, com base em parâmetros de entrada informados pelo usuário, retorne uma solução ótima acerca do planejamento de disciplinas por período.

Ainda, tendo por objetivo tornar o modelo uma representação fidedigna da realidade, de forma a obter resultados confiáveis, foram considerados os seguintes pontos:

* Existem matérias oferecidas somente em períodos pares, matérias oferecidas somente em períodos ímpares e matérias oferecidas em ambos os períodos.
* Cada matéria deve ser designada para um período no máximo.
* Cada matéria possui um grau de dificuldade e uma carga horária. 
* Existe, para cada período, um grau de dificuldade máximo e uma carga horária máxima.
* Se uma disciplina possui um ou mais pré-requisitos, esses devem ser cursados em período anterior ao da mesma.
* Existem disciplinas que são co-requisitos uma da outra, ou seja, devem ser cursadas de forma conjunta.
