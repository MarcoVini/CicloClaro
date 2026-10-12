CICLO CLARO — PUBLICAR NO GITHUB PAGES

1. Extraia este ZIP.
2. No repositório GitHub, coloque index.html, app.js, styles.css,
   manifest.webmanifest, sw.js, icon.svg e .nojekyll na RAIZ publicada.
   Não deixe esses arquivos dentro de uma pasta ciclo-claro-pwa.
3. No GitHub: Settings > Pages.
4. Em Build and deployment, selecione Deploy from a branch.
5. Escolha a branch (por exemplo, main) e a pasta /(root), depois Save.
6. Aguarde o deploy e abra a URL exibida em Settings > Pages.
7. Se já havia uma versão antiga instalada/cacheada, feche o app e recarregue
   o site. Se persistir, limpe os dados do site no navegador e abra novamente.

A PWA requer HTTPS; GitHub Pages fornece HTTPS. O app salva os dados no
armazenamento local do navegador, sem sincronização em nuvem.
