
# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é

## Docker

Para iniciar o container

```bash
  docker-compose up --build 
```
Para finalizar o container

```bash
  docker-compose down
```




## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Deploy

Para fazer o deploy desse projeto rode

```bash
  npm run deploy
```

