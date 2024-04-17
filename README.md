# Sistema-de-Gerenciamento-de-Tarefas-em-ABAP

Documentação da Web API
Descrição
A Web API ZDBB_API é responsável por fornecer acesso aos dados da tabela ZDBB no sistema SAP. Essa tabela é parte do sistema de gerenciamento de tarefas e armazena informações sobre as tarefas atribuídas aos membros da equipe.

Tecnologias Utilizadas
SAP ABAP: A linguagem de programação utilizada para desenvolver a lógica de negócios da Web API.
SAP NetWeaver Application Server: O ambiente de execução utilizado para implantar a Web API no sistema SAP.
ABAP Development Tools (ADT): A ferramenta de desenvolvimento utilizada para criar e gerenciar os objetos ABAP no sistema SAP.
Recursos da Web API
A Web API ZDBB_API fornece os seguintes recursos:

Listagem de Tarefas

Endpoint: /api/tasks
Método: GET
Descrição: Retorna uma lista de todas as tarefas armazenadas na tabela ZDBB.
Detalhes da Tarefa

Endpoint: /api/tasks/{task_id}
Método: GET
Parâmetros:
{task_id}: O ID da tarefa desejada.
Descrição: Retorna os detalhes da tarefa correspondente ao ID fornecido.
Criação de Tarefa

Endpoint: /api/tasks
Método: POST
Corpo da Requisição: Os dados da nova tarefa a ser criada.
Descrição: Cria uma nova tarefa na tabela ZDBB com base nos dados fornecidos.
Atualização de Tarefa

Endpoint: /api/tasks/{task_id}
Método: PUT
Parâmetros:
{task_id}: O ID da tarefa a ser atualizada.
Corpo da Requisição: Os novos dados a serem atualizados na tarefa.
Descrição: Atualiza os dados da tarefa correspondente ao ID fornecido.
Exclusão de Tarefa

Endpoint: /api/tasks/{task_id}
Método: DELETE
Parâmetros:
{task_id}: O ID da tarefa a ser excluída.
Descrição: Exclui a tarefa correspondente ao ID fornecido da tabela ZDBB.
