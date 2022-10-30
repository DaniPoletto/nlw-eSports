# Next Level Week - eSports - 2022

Esse projeto foi desenvolvido durante a [next level week](https://lp.rocketseat.com.br/nlw) promovida pela Rocketseat. Durante uma semana é lançada 1 aula por dia com o intuito de desenvolver uma aplicação web e mobile. Neste projeto é apresentada a API criada durante o evento. 

# Tecnologias usadas
- NodeJS
- Sqlite

# Inicialização

1) Instalar dependencias
```
npm install
```

2) Subir servidor
Na pasta server:
```
npm run dev
```

# Rotas
## Retornar discord apartir de anúncio
| Método | Rota | Descrição | BODY PARAMS | QUERY PARAMS |
| --- | --- | --- | --- | --- |
|GET | ads/{id}/discord | Retornar discord apartir do id do anuncio | - | - |

![Imagem](https://github.com/DaniPoletto/nlw-eSports/blob/main/get_discord_by_ad.jpg)

## Criar anúncio

## Listar jogos

## Listar anúncios por jogos
 
## Instalar pacote express pra node
```
npm install @types/express -D
```

```
npm i ts-node-dev -D
```

```
npm create vite@latest
```

## Prisma ORM
### Instalar prisma ORM

> https://www.prisma.io/

```
npm i prisma -D
```

### Criar banco com sqlite
```
npx prisma init --datasource-provider sqlite 
```

### Rodar migrations
```
npx prisma migrate dev
```

### Abrir painel prisma
```
npx prisma studio
```

### Algumas instalações necessárias
```
npm i @prisma/client
```

```
npm i cors
```

```
npm i @types/cors -D
``` 
