# Hugo Munhoz · Consultoria de Investimentos

Site estático de uma página (HTML + CSS puro, sem build). Os arquivos publicáveis são `index.html`, `robots.txt` e `sitemap.xml`.

- **GitHub Pages:** Settings → Pages → Source: *GitHub Actions*. O workflow em `.github/workflows/pages.yml` publica a raiz do repo a cada push na `main`.
- **Cloudflare Pages:** conecte o repo, deixe o *build command* vazio e *output directory* = `/`.
- Ao trocar de domínio, atualize a URL em `index.html` (canonical, og:url, JSON-LD), `robots.txt` e `sitemap.xml`.
