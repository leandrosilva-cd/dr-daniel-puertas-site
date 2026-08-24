# Dr. Daniel Puertas — Site Institucional

Landing page de página única (`index.html`) para o consultório do Dr. Daniel Puertas, oftalmologista especialista em catarata.

## Estrutura

- `index.html` — página única com todo o HTML, CSS e JavaScript do site.
- `.github/workflows/static.yml` — workflow do GitHub Actions que publica o conteúdo estático no GitHub Pages a cada push na branch `main`.

## Rodando localmente

Não há build nem dependências. Basta abrir o arquivo diretamente no navegador:

```bash
start index.html
```

Ou, se preferir servir por HTTP (recomendado para testar links âncora e formulários):

```bash
npx serve .
```

## Deploy

O deploy é automático: qualquer push na branch `main` dispara o workflow `Deploy static content to Pages`, que publica o conteúdo do repositório no GitHub Pages.
