## Os diagramas foram desenvolvidos para revisar e reforçar conceitos aprendidos na disciplina de Modelagem de Software. 


##


### Diagrama de Atividades da escrita de um livro

- O diagrama representa as etapas da escrita de um livro, possuindo quatro atores: escritor, editor, revisor e a impressora. 

- O mesmo foi separado em raias, onde cada ator possui seu espaço, visando separar as ações de cada um. 

- O círculo preto indica o início do diagrama, e os que possuem uma faixa branca, o final. 

- As setas mostram o percurso do processo e os retângulos, as ações. 

- O losango indica uma condição, que pode ser seguida por dois ou mais caminhos. 


![Diagrama de atividades](https://github.com/EnzoFerreiraAguiar/UML/blob/master/Imagens_Dos_Diagramas/Diagrama_De_Atividades_Escrita_De_Livro.jpeg)

##

### Diagrama de Caso de Uso de uma Hotelaria

- Apresenta o funcionamento do processo de reserva no lugar. 

- Primeiramente, começa com a solicitação do serviço, feita pelo hóspede e efetuada pelo funcionário. 

- Porém, antes da reserva do quarto, o funcionário realiza o cadastro do hóspede. 

- Depois, o hóspede faz a quitação da diária para o funcionário, onde inclui o consumo e serviços (podem ser opcionais).

- O encerramento da estadia é feita por parte do hóspede. 


![Diagrama de Caso de Uso](https://github.com/EnzoFerreiraAguiar/UML/blob/master/Imagens_Dos_Diagramas/Diagrama_De_Caso_De_Uso_Hotelaria.jpeg)

##

### Diagrama de Modelo Conceitual de um acervo

- É separado por classes, onde cada uma tem seu nome e atributos.

- É focado em relações entre as classes (conceitos).

- Se inicia com o Distribuidor, que pode pode fornecer 0 ou mais títulos, enquanto 1 título pode ser fornecido apenas por um Distribuidor. 

- Entre Item e Título, o item é um título e possui apenas um, mas um título possui um ou vários itens. 

- Já entre Título e Classe, o título pertence a uma classe, e uma classe pertence a 0 ou vários títulos.


![Diagrama de Modelo Conceitual](https://github.com/EnzoFerreiraAguiar/UML/blob/master/Imagens_Dos_Diagramas/Diagrama_De_Modelo_Conceitual_Acervo.jpeg)

##

### Diagrama de Sequência de um aplicativo

- Possui 3 atores: o usuário, o aplicativo e o Servidor. 

- A primeira mensagem enviada pelo usuário contém seu nome, a segunda, com o apelido e a terceira com o avatar, e a quarta é o submit (Enviar).

- O Enviar determina o usuário no Servidor.

- Depois, o Servidor manda a resposta dizendo que o usuário foi registrado.


![Diagrama de Sequência](https://github.com/EnzoFerreiraAguiar/UML/blob/master/Imagens_Dos_Diagramas/Diagrama_De_Sequ%C3%AAncia_Aplicativo.jpeg)

##

### Diagrama de Classes de uma escola

- Possui 4 classes: Aluno, Professor, Turma e Disciplina. 

- As relações de Associação e Herança foram usadas. 

- A classe aluno e professor são sub-classes da classe pessoa. 

- As relações se iniciam quando um aluno tem que estar em uma turma, e a mesma pode ter 1 ou vários alunos.

- Depois, vai para o professor, que pode ministrar uma ou várias disciplinas, e uma disciplina pode ter um ou vários professores. 

- O professor pode ministrar aula em pelo menos uma turma e no máximo várias, já a turma pode ter um ou vários professores. 

- E a turma tem no mínimo várias e no máximo várias disciplinas. 


![DIagrama de Classes](https://github.com/EnzoFerreiraAguiar/UML/blob/master/Imagens_Dos_Diagramas/Diagramas_De_Classes_Escola.jpeg)


