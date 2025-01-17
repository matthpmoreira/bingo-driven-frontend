# Front-end para o Bingo Driven

## Deploy

https://bingo-driven-frontend.vercel.app/

## Como realizar o deploy

### Deploy remoto via Vercel

[Não é possível fazer o deploy de imagens Docker no Vercel.](https://vercel.com/guides/does-vercel-support-docker-deployments) Ao realizar o deploy, é necessário armazenar a URL do back-end na variável de ambiente `VITE_BACKEND`.

### Deploy local

1. Crie um arquivo `docker-compose.yml` e configure o serviço conforme desejar.
    * É necessário passar a URL do back-end pela variável de ambiente `VITE_BACKEND`.
    * O arquivo [`docker-compose.yml`](./docker-compose.yml) do repositório pode ser copiado e usado.
2. Execute o comando `docker compose up` no diretório do arquivo.
