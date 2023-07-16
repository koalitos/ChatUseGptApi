
# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é


## Rodando localmente

node -v v16.14.2

Clone o projeto

Entre no diretório do Back-end

```bash
  cd server
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run start
```

Depois ta na hora de iniciar o Front,
Entre no diretório Front

```bash
  cd web
```

Instale as dependências

```bash
  npm install
```
Inicie o react

```bash
  npm start
```
## Diretorios

- Server: back-end node que comunica com api da openai e faz autenticação
- Web: front-end em react 


## Documentação da API

#### Retorna todos os itens

```http
  Post /api/prompt
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `OPENAI_API_KEY` | `string` | **Obrigatório**. A chave da sua API https://platform.openai.com/account/api-keys |



## Screenshots

[![chat-image.png](https://i.postimg.cc/brjdNXFk/chat-image.png)](https://postimg.cc/Pp2d27H5)
