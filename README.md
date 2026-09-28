# Authentic Glitch

Site estático e portfólio visual para apresentar trabalhos, serviços de fotografia e canais de contato da Authentic Glitch.

## Estrutura

- `index.html`: página principal e experiência do portfólio;
- `images/`: fotografias e assets organizados por coleção/evento;
- `PROJECT.md`: identidade, escopo e regras de autenticidade;
- `docs/`: estado e histórico do projeto.

## Executar localmente

Como o projeto é estático, basta abrir `index.html` no navegador. Para uma experiência mais próxima da publicação, use qualquer servidor HTTP local, por exemplo:

```bash
python -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000).

## Direção do projeto

O portfólio deve apresentar a linguagem visual e editorial própria da Authentic Glitch. Trabalhos, clientes, serviços e informações institucionais devem ser confirmados pelo responsável antes da publicação.

## Status

Site estático funcional em evolução. O [`STATUS`](docs/STATUS.md) registra uma publicação anterior no GitHub Pages; a disponibilidade atual, um eventual domínio próprio e o fluxo de publicação ainda precisam ser revalidados antes de uma entrega ao cliente. O acesso por provedor externo tem uma limitação conhecida descrita no STATUS e não deve ser anunciado como funcional até novo teste.

## Segurança

Não versionar credenciais, tokens, dados privados ou arquivos temporários. Evitar publicar imagens ou informações de clientes sem autorização.
