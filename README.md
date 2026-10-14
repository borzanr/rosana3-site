# rosana3.borzanti.com — versão alternativa com vídeo no hero

Igual ao rosana2, com sombras de folhas em movimento no fundo do hero (Seedance 2.5, loop de 4,4 s, versão com balanço mais visível).
Gerado de `D:\Sites\rosana-alt` com:

    cd D:\Sites\rosana-alt\app
    STATIC_EXPORT=1 VITE_VARIANT=video VITE_SITE_URL=https://rosana3.borzanti.com bunx --bun vite build

Depois: copiar `app/dist/client` para cá (sem `presets`) e os vídeos de `refs/video/` para `assets/`
(`hero-folhas-web.mp4` como `hero-folhas.mp4` e `hero-folhas-celular.mp4`). Versão de avaliação: noindex.
