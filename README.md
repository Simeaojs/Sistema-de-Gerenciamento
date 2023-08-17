# Sistema de Gerenciamento de Tarefas e Projetos

Este é um sistema de API para gerenciamento de tarefas, projetos e usuários, desenvolvido em Java com o uso do Spring Framework.

## Funcionalidades

- Cadastro, listagem, atualização e exclusão de usuários.
- Cadastro, listagem, atualização e exclusão de projetos.
- Cadastro, listagem, atualização e exclusão de tarefas.
- Associação de tarefas a projetos e usuários.
- Consulta de tarefas por projeto e por usuário.
- Consulta de tarefas filtradas por projeto e usuário.

#  
## Tecnologias Utilizadas

- Java
- Spring Framework
- Spring Data JPA
- Banco de Dados (MySQL)
- Gerenciador de Dependências Maven
- Postman Para Requisições
- IDE Visual Studio Code
#
## 🪛Configuração 

1. Clone o repositório para o seu ambiente local.
  + git clone ```https://github.com/Simeaojs/Sistema-de-Gerenciamento.git```
3. Configure as dependências do projeto (Maven).
4. Configure as informações do banco de dados no arquivo de configuração (`application.properties` ou `application.yml`).
5. Execute a aplicação.
#

## Exemplos de Requisições

**Cadastro de Usuário**

```http
POST /usuarios

{
  "nome": "Sandra",
  "sobrenome": "Maria",
  "email": "sandra@example.com",
  "senha": "987654",
  "genero": "FEMININO"
}
```
## Para fazer essa chamada pelo Postman:

1.Abra o Postman.

2.Selecione o método POST.

3.Insira a URL: ```http://localhost:8080/usuarios.```

4.Selecione o tipo de corpo (```body```) como JSON (clique em "```Body```" e escolha "```raw```" e "JSON (```application/json```)").

5.Cole o JSON do exemplo acima no corpo da solicitação.

6.Clique no botão "```Send```" para fazer a solicitação.
#

**Listar o Usuario Salvo**

```http
GET /projetos

{
"idUsuario": 1,
"nome": "Sandra",
"sobrenome": "Maria",
"email": "usuario@example.com",
"senha": "senha123",
"genero": "FEMININO",
}

```

**Para fazer essa chamada pelo Postman:**

1.Abra o Postman.

2.Selecione o método GET.

3.Insira a URL: ```http://localhost:8080/usuarios```.

4.Clique no botão "Send" para fazer a solicitação.

## Contribuição

Contribuições são bem-vindas! Se você identificar problemas ou melhorias, sinta-se à vontade para abrir um pull request.


## Licença
Este projeto está licenciado sob a Licença XYZ - veja o arquivo **LICENSE** para mais detalhes.

*Projeto Desenvolvido no Curso Da Treina Recife, Java WEB + Spring Boot!*
