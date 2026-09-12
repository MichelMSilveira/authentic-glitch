# STATUS

## Estado atual
O projeto possui um site estatico funcional concentrado em `index.html`, com assets em `images/`.

## Publicacao e indexacao
- GitHub Pages publicado em `https://michelmsilveira.github.io/authentic-glitch/` a partir da branch `main`.
- `robots.txt`, `sitemap.xml`, URL canonica, metadados de compartilhamento e JSON-LD adicionados ao site.
- O endpoint publicado responde `200` e nao havia bloqueio `noindex`; a ausencia de `robots.txt` e `sitemap.xml` foi corrigida.

## Bloqueio conhecido
- O login com Google usa o projeto Supabase `tfzpnaasdgxwnjykeqgj`, cujo dominio nao existe no DNS publico.
- O codigo agora trata a falha sem quebrar a pagina, mas restaurar o login exige um projeto Supabase valido e a configuracao de OAuth/redirect no painel do provedor.

## Estrutura de contexto
- `AGENTS.md` criado;
- `PROJECT.md` criado;
- este arquivo passa a ser o ponto principal de retomada.

## Proximo passo recomendado
Auditar o `index.html` atual e registrar:
- secoes existentes;
- itens pendentes de conteudo;
- ajustes visuais desejados;
- estado de publicacao/deploy.

## Pendencias
- confirmar hosting e dominio atuais;
- registrar fluxo de deploy;
- revisar `docs/SESSION.md` ao encerrar a próxima sessão relevante.
