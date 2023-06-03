# NodeJs-ServerLess-AWS-DynamoDB-SWAPI-ErikPinares

Repositorio sobre el uso de StarWars API desde AWS con NodeJs y Framework ServerLess


## API Referencia de uso

#### Paso 1. Importar los items de SWAPI hacia la BD DynamoDB

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

