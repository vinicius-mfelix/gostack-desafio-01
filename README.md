# GoStack - Desafio 01 (Node.js)

Desenvolvimento do primeiro projeto em Node.js para CRUD de repositórios.

Obrigado para você que está corrigindo! Você poderia estar fazendo outra coisa mas separou este tempo para corrigir meu trabalho! <3


## Execução do projeto

Para execução do projeto, considerar o arquivo *requests.rest* disposta na pasta raíz do projeto para as requisições para o **app.js**.


## Sugestão de uso do arquivo requests.rest:

Este arquivo tem por finalidade facilitar a correção do desafio.

Adicione a extensão REST Client ao seu VS Code (caso ainda não possua).

As requests estão organizadas da seguinte maneira no arquivo REST:

|      Método         |                         Ação                         |
|---------------------|------------------------------------------------------|
|GET                  | Recupera todos os repositórios (array vazio).        |
|POST - Repositórios  | Adiciona um registro de repositórios ao array.       |
|POST - Likes         | Adiciona um like à um determinado repo selecionado.  |
|PUT                  | Atualiza um registro de repositório existente.       |
|GET                  | Recupera todos os repositórios (array com um item).  |
|DELETE               | Remove um registro de repositório existente.         |
|GET                  | Recupera todos os repositórios (array vazio).        |

Após executar o primeiro POST para adição de um repositório, você pode substituir a váriavel ```@repoId``` pelo ID atual do repositório. Alterando esta variável, não será necessário adicionar o valor do ID as demais requests subsequentes.

As linhas com três cerquilhas seguidas (###) são utilizadas para separar requests.

**Obrigado!**

