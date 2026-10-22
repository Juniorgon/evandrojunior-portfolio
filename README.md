# Evandro Junior — Portfólio

Portfólio pessoal em um único arquivo HTML. O CSS e o JavaScript ficam incorporados no próprio `public/index.html`.

## Estrutura

- `wrangler.jsonc`: configuração do Cloudflare Workers para publicar os arquivos estáticos da pasta `public/`. O nome `portfolio` mantém o Worker que corresponde ao endereço `portfolio.goncalves-jrrg.workers.dev`.
- `public/index.html`: página completa (HTML, CSS e JavaScript no mesmo arquivo).

## Publicar na Cloudflare

1. Envie `wrangler.jsonc`, `README.md` e a pasta `public/` para a raiz do repositório GitHub.
2. Nas configurações de build do Cloudflare Workers, use o comando de deploy `npx wrangler deploy`.
3. Não configure build command adicional. Como não há etapa de build, não é preciso gerar `dist/` ou `build/`.
4. Faça um novo deploy.

O arquivo inicial precisa chamar-se `index.html` para ser servido na raiz do domínio.
