# API de Gerenciamento de Projetos

Essa é uma API RESTful para gerenciamento de projetos e tarefas, com suporte aos verbos HTTP GET, POST, PUT e DELETE.
Recursos Disponíveis

## A API possui os seguintes recursos:

    Projeto: representando um projeto a ser gerenciado pela API
    Tarefa: representando uma tarefa que faz parte de um projeto
    Usuário: representando um usuário que pode ser atribuído a uma tarefa ou a um projeto

## Endpoints Disponíveis

A API possui os seguintes endpoints:
### Projetos

    GET /projetos: retorna uma lista de todos os projetos
    POST /projetos: cria um novo projeto
    GET /projetos/{id}: retorna os detalhes de um projeto específico
    PUT /projetos/{id}: atualiza um projeto existente
    DELETE /projetos/{id}: exclui um projeto existente

### Tarefas

    GET /projetos/{id}/tarefas: retorna uma lista de todas as tarefas de um projeto
    POST /projetos/{id}/tarefas: cria uma nova tarefa para um projeto específico
    GET /projetos/{id}/tarefas/{id}: retorna os detalhes de uma tarefa específica de um projeto
    PUT /projetos/{id}/tarefas/{id}: atualiza uma tarefa específica de um projeto existente
    DELETE /projetos/{id}/tarefas/{id}: exclui uma tarefa específica de um projeto existente

### Usuários

    GET /usuarios: retorna uma lista de todos os usuários
    POST /usuarios: cria um novo usuário
    GET /usuarios/{id}: retorna os detalhes de um usuário específico
    PUT /usuarios/{id}: atualiza um usuário existente
    DELETE /usuarios/{id}: exclui um usuário existente

## Utilização

Para utilizar a API, é necessário enviar requisições HTTP aos endpoints disponíveis. As requisições podem ser feitas utilizando ferramentas como o curl, ou através de uma interface gráfica, como o Postman.