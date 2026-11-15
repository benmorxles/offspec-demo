# OffSpec demo (static build)

The OffSpec web console, built as static files and served by GitHub Pages. It has no
API behind it, so it shows the bundled sample reports and says "Sample data: the API is
offline". Source: https://github.com/Firkenol/HackPrincetonRepo (folder `web/`).

Rebuilt with: `STATIC_EXPORT=1 BASE_PATH=/offspec-demo npm run build` in `web/`.
