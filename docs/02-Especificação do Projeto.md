# Especificações do Projeto

## Personas

**Rachel**

 Rachel é uma leitora ávida, com uma coleção crescente de livros físicos e digitais. Ela valoriza a organização e a praticidade, buscando otimizar seu tempo livre. Rachel aprecia ferramentas que simplifiquem suas escolhas de leitura e que permitam manter um controle rigoroso de seus livros. 

**Natália**

 Natália, 27 anos, é graduada em Letras e trabalha como editora em uma editora independente. Apaixonada por leitura, ela está sempre procurando formas eficientes de organizar sua coleção. Para ela, a organização dos livros é fundamental tanto em sua vida pessoal quanto profissional. 


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|    EU COMO...      |                                    QUERO/PRECISO ...                                |                             PARA ...                           |
|--------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------|
|Usuário do sistema  | Organizar minha biblioteca de livros físicos e digitais                             | Possuir maior organização e controle sobre a coleção de livros |
|Usuário do sistema  | Visualizar quais livros emprestei a amigos | Permitir que possam administrar contas | Acompanhar e lembrar dos livros emprestados                    |
|Usuário do sistema  | Visualizar quais livros já foram lidos e quais ainda não                            | Facilitar a tomada de decisão sobre a próxima leitura          |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID   |                                           Descrição do Requisito                                                 | Prioridade |
|------|------------------------------------------------------------------------------------------------------------------|------------|
|RF-001| Permitir que o usuário cadastre, altere e exclua seus livros                                                     | ALTA       | 
|RF-002| Permitir que o usuário crie, altere e exclua seu perfil                                                          | ALTA       |
|RF-003| Permitir alterar o status dos livros para "emprestado", incluindo informações do amigo que recebeu o empréstimo  | ALTA       | 
|RF-004| Possuir filtros para facilitar a busca por livros cadastrados                                                    | MÉDIA      |
|RF-005| Permitir a criação de listas de leitura                                                                          | MÉDIA      | 
|RF-006| Permitir a adição de notas aos livros cadastrados                                                                | BAIXA      |


### Requisitos não Funcionais

|ID     |                             Descrição do Requisito                              | Prioridade |
|-------|---------------------------------------------------------------------------------|------------|
|RNF-001| O sistema deve ser responsivo para funcionar em dispositivos móveis e desktop   | ALTA       | 
|RNF-002| Seguir boas práticas de UX (experiência do usuário) e UI (interface do usuário) | MÉDIA      | 
|RNF-003| Processar requisições de usuário em no máximo 3 segundos                        | BAIXA      | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID|                  Restrição                                             |
|--|------------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do ano de 2025.              |
|02| O desenvolvimento do backend deve ser feito utilizando a linguagem C#  |
|03| O sistema deverá ser desenvolvido para ambiente web                    |
|04| A aplicação deve ser integrada a um banco de dados relacional          |
