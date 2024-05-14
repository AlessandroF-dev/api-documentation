# Documentação da API

## Introdução
Bem-vindo à documentação da API. Esta API permite realizar várias operações.

## Autenticação
Para autenticar, você precisa de um token de acesso. Envie o token em cada requisição usando o header `Authorization`.

## Endpoints
### GET /api/v1/resource
Retorna uma lista de recursos.

#### Parâmetros
- `limit`: Número máximo de recursos a retornar.
- `offset`: Ponto de início para a listagem de recursos.

#### Exemplo de Requisição
```bash
curl -H "Authorization: Bearer seu_token_aqui" https://api.seuservico.com/api/v1/resource