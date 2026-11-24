# Meu roteiro em Londres

Página estática pronta para publicar no GitHub Pages.

1. O token público do Mapbox já está configurado no `index.html`. Restrinja seu uso ao endereço do GitHub Pages no [painel do Mapbox](https://account.mapbox.com/access-tokens/).
2. O roteiro está na lista `itinerary` do script em `index.html`; cada ponto contém nome, horário, descrição e coordenadas `[longitude, latitude]`.
3. As fotos são carregadas ao abrir cada popup a partir da Wikipédia; se uma página não tiver miniatura, o popup continua mostrando título e descrição.
4. No GitHub, abra **Settings → Pages** e publique a branch principal, pasta `/ (root)`.

O token público fica visível no site. Configure as restrições de URL permitidas no painel do Mapbox para o endereço do GitHub Pages.
