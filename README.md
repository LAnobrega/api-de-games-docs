# API de Games
Esta API é utilizada para fazer ...
## Endpoints
### GET /games
Este endpoint é responsavel por retornar a listagem de todos os games cadastrados no banco de dados.
#### Parametros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposta acontecer você vai receber a listagem de todos os games
##### Falha na autenticação! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de requisição. Motivos: Token inválido, Token expirado.
