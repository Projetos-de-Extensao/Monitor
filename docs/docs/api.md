# Api


Abaixo segue um exemplo de como o conteúdo da API pode ser
estruturado. Essa estrutura pode ser alterada ao longo do
desenvolvimento da API para melhor se adequar às necessidades
do sistema.

## Requisição

```json
{
    "method": "GET",
    "endpoint": "/api/v1/endpoint"
}
```

## Resposta

```json
{
    "status": 200,
    "data": {
        "id": 1,
        "name": "John Doe"
    }   
}
```
