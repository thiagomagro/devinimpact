# devinimpact

Conteúdos públicos para compartilhar com clientes. Cada conteúdo é uma página
estática autocontida (HTML + CSS + JS inline, sem dependências externas), então
basta abrir o link no navegador.

## Site publicado

- Índice: https://thiagomagro.github.io/devinimpact/
- PDLC / AIDLC: https://thiagomagro.github.io/devinimpact/pdlc/

## Adicionar um novo conteúdo

1. Crie uma pasta na raiz com um slug curto (ex: `roi-devin/`).
2. Coloque o arquivo dentro dela como `index.html`, autocontido.
3. Adicione um item na lista de `index.html` na raiz apontando para `slug/`.

## Publicação (GitHub Pages)

O site é servido pelo GitHub Pages a partir da branch default, pasta raiz. Se o
Pages ainda não estiver ativo, ative em
**Settings > Pages > Source: Deploy from a branch > main > /(root)**.

Para revisar localmente:

```bash
python3 -m http.server 8000
# http://localhost:8000
```
