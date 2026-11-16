# Pipou — site institucional

O site está em [`institucional/`](institucional/README.md).

Para rodar localmente:

```sh
cd institucional
npm run dev
```

Acesse http://127.0.0.1:4173.

Para hospedar, use `institucional` como diretório base e `dist` como diretório de publicação. O site é estático e não precisa de build ou instalação de dependências.

## Vercel

Importe o repositório com Root Directory `./` e preset Other. O `vercel.json` da raiz publica `institucional/dist`, sem instalação ou build. Pushes em `main` atualizam o site conectado na Vercel.

## Domínio oficial

Endereço principal: https://www.pipou.net/. O domínio https://pipou.net/ redireciona permanentemente para www. O registro e os servidores DNS permanecem na GoDaddy. O projeto na Vercel é `pipou-site`.
