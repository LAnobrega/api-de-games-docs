# API de Games
Esta API é utilizada para fazer ...
## Endpoints
### GET /games
Este endpoint é responsavel por retornar a listagem de todos os games cadastrados no banco de dados.
#### Parametros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposta acontecer você vai receber a listagem de todos os games.

Exemplo de resposta:
```

[
    {
        "id": 23,
        "title": "War",
        "year": 2020,
        "price": 60
    },
    {
        "id": 65,
        "title": "Sea of thieves",
        "year": 2019,
        "price": 70
    },
    {
        "id": 2,
        "title": "Minecraft",
        "year": 2012,
        "price": 100
    }
]

```
##### Falha na autenticação! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de requisição. Motivos: Token inválido, Token expirado.

Exemplo de resposta:

```
{
    "err": "Token inválido!"
}
```
