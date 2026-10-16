# Rodrigo Sant'Ana — site estático (GitHub Pages)

Portfólio de produtor/diretor (página única, 2 idiomas). Mirror estático do
WordPress (Elementor), sem PHP.

- `/` — homepage (conteúdo EN; equivale ao `/eng/` da produção, que redireciona para cá)
- `/pt/` — homepage em português
- `/eng/` — redireciona para `/`
- `404.html` — página de erro leve

## Testar localmente

```powershell
npx --yes serve .
```

Abrir `http://localhost:3000/` (não usar duplo-clique no `index.html`).

## Estrutura

`wp-content/` contém apenas assets estáticos necessários: uploads referenciados,
bundles minificados do WP-Optimize (`cache/wpo-minify/...`) e fontes de ícones do
Elementor/FontAwesome (`plugins/elementor/assets/lib/...`).
