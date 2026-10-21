# evandrojunior-portfolio
Portfólio pessoal de Evandro Junior, apresentando projetos, competências técnicas e minha trajetória em desenvolvimento de software.

# Portfólio — Evandro Junior

Landing page pessoal estática feita com HTML, CSS e JavaScript puro. Não exige Node.js, compilação, framework ou instalação de dependências.

## Executar localmente

1. Extraia a pasta do projeto.
2. Abra `index.html` no navegador.

Para testar usando um servidor local, entre nesta pasta e execute:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Personalizar antes de publicar

Abra `script.js` e ajuste o objeto `SITE_CONFIG` no início do arquivo:

```js
const SITE_CONFIG = {
  github: "https://github.com/Juniorgon",
  linkedin: "https://www.linkedin.com/in/seu-usuario/",
  email: "contato@seudominio.com.br",
};
```

- `github`: perfil do GitHub que será exibido nos links de contato e no rodapé.
- `linkedin`: URL pública do LinkedIn. Deixe `""` para ocultar os links enquanto não estiver configurado.
- `email`: e-mail de contato. Deixe `""` para ocultar os links enquanto não estiver configurado.

O repositório LabSoft/FestVer está configurado para `https://github.com/jsaranda/LabSoft`, conforme a referência usada na descrição do projeto. Confira se é o link que deseja publicar.

## Arquivos

- `index.html` — conteúdo semântico, seções e metadados SEO/social.
- `styles.css` — identidade visual, componentes, animações e layouts responsivos.
- `script.js` — menu móvel acessível, ano automático, configuração de contato e animações sutis.
- `favicon.svg` — ícone vetorial da página.

## Antes de publicar

- Confirme o endereço público do GitHub pessoal e do repositório LabSoft/FestVer.
- Preencha e-mail e LinkedIn em `SITE_CONFIG`.
- Se possível, inclua links ou capturas de tela dos projetos que estejam publicamente demonstráveis.
- Revise a descrição de cada projeto para refletir exatamente o estado atual do código.

A página não possui formulário de contato nem coleta dados pessoais. O contato é feito por links para perfis e e-mail.
