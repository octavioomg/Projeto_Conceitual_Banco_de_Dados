# Projeto Conceitual Banco de Dados

### Desenvolvimento inicial para modelos de Banco de Dados Conceitual:
- Ordem de Serviço;
- Universidade;
- E-commerce.

Cada um dos modelos foram aplicados conceitos envolvendo modelagem de dados, utilizando a ferramenta MySQL - Workbench, para criação das entidades de relacionamento.

## 
### Modelo BD - Ordem de Serviço

Contexto:
- Dentro de uma empresa os clientes demandam ao helpdesk algumas ações;
- Essas ações são convertidas em ordem de serviço;
- Os clientes realizam um pedido;
- O pedido é convertido em ordem de serviço caso possa ser realizado;
- O técnico executa a ordem de serviço. Após sua finalização a mesma é arquivada.

### Esquema conceitual:

![Modelo_Ordem_Servico](https://github.com/user-attachments/assets/f428021a-5131-4f54-a749-83a6d5263185)


## 
### Modelo BD - Universidade

Contexto:
- A universidade possui diversos alunos que podem estar matriculados em mais de um curso (graduação);
- Os alunos podem fazer cursos extras fornecidos externa e internamente (universidade) para contar como horas complementares;
- Não há restrição quanto ao número de matérias puxadas se não houver sobreposição de horário;
- Os alunos são submetidos a duas provas por semestre para cada disciplina;
- Eventuais trabalhos devem ser tratados pelo professor para compor a nota da prova;
- Cada disciplina é fornecida por um professor. Restrição: apenas por este professor;
- Algumas disciplinas possuem pré-requisitos. Um mesmo pré-requisito pode ser associado a mais de uma disciplina;
- As disciplinas podem ser comuns a cursos distintos;
- O ciclo de vida da disciplina é semestral;
- Os professores que ministram as disciplinas estão associados as coordenações de seus respectivos cursos.

### Esquema conceitual:

![Modelo_Universidade](https://github.com/user-attachments/assets/6688dc4f-e475-440a-badb-b07fdd28883a)


## 
### Modelo BD - E-commerce

Contexto:
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
- Cada produto possui um fornecedor;
- Um ou mais produtos podem compor um pedido;
- O cliente pode se cadastrar no site com seu CPF ou CNPJ;
- O Endereço do cliente irá determinar o valor do frete;
- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto;
- O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
- Um produto ou mais compõem o pedido;
- O pedido pode ser cancelado;
- Estoque possui localização definida, com produtos e fornecedores.

### Esquema conceitual:

![Modelo_Ecommerce](https://github.com/user-attachments/assets/27a7e3c5-a372-4aa3-b1d6-3794b8e96850)


##





