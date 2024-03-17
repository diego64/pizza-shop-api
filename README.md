# Pizza Shop | API

Esta API foi desenvolvida com o objetivo de ser a fonte de dados de uma aplicação Front-end que tem como objetivo gerenciar restaurantes observando dados como a quantidade de **pedidos recebidos**, **pedidos cancelados**, **faturamento mensal e anual** bem como suas **comparações com meses anteriores** proporcionado uma melhor analise do administartor do restaurante.

> Esse projeto foi desenvolvido utilizando [bun](https://bun.sh/), [ElysiaJS](https://elysiajs.com/), [Docker](https://www.docker.com/), [PostgreSQL](https://www.postgresql.org/), [Drizzle](https://orm.drizzle.team/) e [JWT](https://jwt.io/).

> Este projeto visa manter o tempo de execução agnóstico, isso significa que deve funcionar em Bun, Node, Cloudflare Workers ou qualquer tempo de execução compatível com API Web Standard.

## Rodando a aplicação

```sh
bun i
docker compose up -d
bun migrate
bun seed
bun dev
```
## Funcionalidades

- [x]  Autenticação do usuáio
- [x]  Listagem de perfil do usuário
- [x]  Listagem de produtos
- [x]  Métricas de faturamento mensal
- [x]  Métricas de faturamento anual