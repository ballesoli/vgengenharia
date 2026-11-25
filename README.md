# VG Engenharia e Soluções Metálicas — Site moderno

Site institucional moderno da **VG Engenharia e Soluções Metálicas**, com todo o conteúdo do site original (vgsolucoesmetalicas.com.br), otimizado para SEO, AEO (Answer Engine Optimization) e GEO (Generative Engine Optimization / Geossignal).

## Estrutura
- `index.html` — página única, responsiva, com HTML5 semântico e CSS/JS inline
- `assets/` — imagens otimizadas em WebP + fallbacks JPEG + favicon
- `site.webmanifest` — manifesto PWA
- `robots.txt` — diretivas para crawlers
- `sitemap.xml` — sitemap com imagens

## Otimizações aplicadas
- **SEO**: title/description otimizados, Open Graph, Twitter Card, canonical, hreflang pt-BR, sitemap, robots, favicon, semantic HTML, lazy loading, WebP, alt texts descritivos.
- **AEO**: seção FAQ com 8 perguntas + JSON-LD `FAQPage`, respostas diretas e estruturadas.
- **GEO**: `LocalBusiness` com endereço, geo (lat/lng), área atendida, horários; meta tags `geo.region`, `geo.position`, `ICBM`; mapa Google embed; conteúdo localizado (Ribeirão Preto e cidades da região).
- **Schema.org**: `LocalBusiness` + `GeneralContractor`, `Service` (x5), `FAQPage`, `BreadcrumbList`, `WebSite`, `aggregateRating`.
- **Performance**: fontes com `display=swap`, preload do hero, preconnect, imagens WebP com lazy loading.
- **Acessibilidade**: navegação por teclado, ARIA labels, foco, `prefers-reduced-motion`.

## Deploy (GitHub Pages)
1. O site é publicado em `https://ballesoli.github.io/vgengenharia/`.
2. Para usar o domínio próprio `vgsolucoesmetalicas.com.br`:
   - No GitHub: Settings → Pages → Custom domain → `vgsolucoesmetalicas.com.br`
   - No DNS do domínio: apontar um registro `CNAME` (ou ALIAS/ANAME) para `ballesoli.github.io`
   - Atualizar as URLs canônicas/OG/sitemap/robots em `index.html`, `sitemap.xml` e `robots.txt` para `https://www.vgsolucoesmetalicas.com.br/`
