# Huyawo Blog — Static site (design preview)

Site estático para **blog.huyawo.com**, com estética adaptada do ZIP de Huyawo Solutions fornecido como referência visual.

## Conteúdo

- `index.html` — homepage, **grid de duas colunas** com seis cards.
- `posts/<slug>/index.html` — **seis páginas completas de leitura**, com layout de título centralizado, metadados, separador, share, capa, seções e rodapé.
- `assets/site.css` — todo o sistema visual, responsivo e tipográfico.
- `assets/site.js` — menu mobile e compartilhamento.
- `assets/cover-*.svg` — seis capas abstratas de demonstração.
- `assets/huyawo-mark.png` — marca da Huyawo extraída do ZIP de referência.
- `CNAME` — domínio `blog.huyawo.com`.
- `.nojekyll`, `404.html`, `robots.txt` e `sitemap.xml` — arquivos de GitHub Pages.

## Conteúdo de exemplo

**Todos os títulos, resumos e textos dos artigos são Lorem Ipsum**: são placeholders de UI, não artigos reais nem afirmações de pesquisas feitas pela Huyawo. Remova/substitua antes do lançamento. As páginas estão com `noindex,follow` enquanto contêm Lorem Ipsum; retire a meta tag `robots` quando os artigos reais forem publicados. Não foi copiado nenhum texto do blog de Antonio V. Franco.

## Publicação no GitHub Pages

1. Crie o repositório público `OnHuyawo/huyawo-blog`.
2. Descompacte **o conteúdo deste ZIP na raiz** do repositório (sem pasta adicional).
3. Em `Settings → Pages`, selecione `Deploy from a branch`, `main`, `/ (root)`.
4. Confira que `Custom domain` está definido como `blog.huyawo.com`.
5. No DNS de `huyawo.com`, crie/valide o `CNAME` `blog` → `onhuyawo.github.io`.
6. Depois da emissão do certificado, habilite `Enforce HTTPS`.

Requer **zero dependências, compilação ou serviços externos**. Os links internos usam caminhos relativos. Os links `Huyawo` e `Solutions` apontam para os respectivos sites.

## Edição futura

- Para editar um card, altere o bloco correspondente em `index.html`.
- Para editar o texto de leitura, altere o arquivo `posts/<slug>/index.html`.
- Para adicionar um artigo, crie `posts/novo-slug/index.html`, inclua seu card em `index.html` e a URL em `sitemap.xml`.
- Todos os textos apresentados são placeholders. O site não utiliza CMS.

## Tipografia e design

Referência Solutions: marfim `#f8f8ec`, azul profundo `#07346f`, azul `#0759c7`, fundos sky/mist, cards de raio `30px`, sistema Helvetica/Arial.

Referência artigo: fundo branco, título grande centralizado em Helvetica/Arial com font-weight 400, linha separadora, metadados/Share em extremos, imagem centralizada de cantos arredondados e coluna de leitura estreita.
