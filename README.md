API de Patrimônios

Requisitos

Utilizar o sqlite como banco de dados
Entidades:

User
Item
User

ID
Name [String]
Email [String][Unique]
Password [String]
Role [String]
Birth [Date]
Item

Name [String]
Category [String]
UserId [String]
/users Casos de Uso do Usuário

Criar um usuário criptografando a senha
Visualizar um usuário por Email
Listar usuário com paginação
Deletar um usuário com a técnica softdelete
/items Casos de Uso do Item

Criar um item relacionado a um usuário
Visualizar todos ítems de um usuário
Remover um item do usuário
[x] - Config database [x] - Config Swagger [x] - Config Validator Dto
