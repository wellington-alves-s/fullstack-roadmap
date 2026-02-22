✅ O que é REST?

REST (Representational State Transfer) é um estilo de arquitetura usado no desenvolvimento de aplicações web e web services que se comunicam via protocolo HTTP. Ele define um conjunto de boas práticas para troca de dados entre cliente e servidor.

🧠 Conceitos principais

Representação de estado: quando o cliente faz um pedido, o servidor retorna uma representação dos dados solicitados (por exemplo, json com informações de um perfil).

REST não armazena estado entre requisições — cada pedido é independente.

📡 HTTP e métodos usados pelo REST

REST usa os métodos do HTTP para manipular recursos:

Método  O que faz
GET     Consultar/recuperar dados
POST    Criar novos dados
PUT     Atualizar dados existentes
DELETE  Excluir dados

Isso lembra bastante CRUD, que são as operações básicas de um sistema.

🌐 Identificação e formato dos recursos

Os recursos são identificados por URIs (endereços).

O REST usa tipos de conteúdo (como JSON, XML, HTML) para enviar e receber dados.

Hoje, o JSON é o formato mais usado.

📊 Códigos de status HTTP

Os códigos de resposta HTTP indicam se a requisição foi bem-sucedida ou não:

Código Significado
200    OK Tudo certo
201    Created Recurso criado com sucesso
204    No Content Sucesso, mas sem retorno
401    Unauthorized Falha de autenticação
404    Not Found Recurso não encontrado
405    Method Not Allowed Método HTTP não permitido

🧾 Por que usar REST?

Permite comunicação eficiente entre aplicações.

Aproveita todos os recursos do HTTP.

Facilita que outros desenvolvedores entendam e usem a sua API pelo padrão comum.
