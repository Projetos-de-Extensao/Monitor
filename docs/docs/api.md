# Api

## Proposta de conteúdo mock

Abaixo segue um exemplo de como o conteúdo da API pode ser
estruturado. Essa estrutura pode ser alterada ao longo do
desenvolvimento da API para melhor se adequare às necessidades
do sistema.

### Requisição

#### Exemplo de requisição

```json
{
    "method": "GET",
    "endpoint": "/api/v1/endpoint"
}
```

### Resposta

#### Exemplo de resposta

```json
{
    "status": 200,
    "data": {
        "id": 1,
        "name": "John Doe"
    }   
}
