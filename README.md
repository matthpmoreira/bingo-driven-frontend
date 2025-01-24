# Front-end para o Bingo Driven

## Deploy

https://bingo-driven-frontend.vercel.app/

## Repositório do back-end

https://github.com/arzcbnh/bingo-driven-backend

## Como realizar o deploy

### Deploy remoto via Vercel (sem `docker-compose`)

[Não é possível fazer o deploy de imagens Docker no Vercel.](https://vercel.com/guides/does-vercel-support-docker-deployments) Uma das alternativas possíveis de deploy é fazer um fork deste repositório e criar um novo projeto no Vercel usando o fork como base. Ao realizar o deploy, é necessário armazenar a URL do back-end na variável de ambiente `VITE_BACKEND`.

### Deploy local (com `docker-compose`)

1. Crie um arquivo `docker-compose.yml` e configure o serviço conforme desejar.
    * É necessário passar a URL do back-end pela variável de ambiente `VITE_BACKEND`.
    * O arquivo [`docker-compose.yml`](./docker-compose.yml) do repositório pode ser copiado e usado como referência.
2. Execute o comando `docker compose up` no diretório do arquivo.
