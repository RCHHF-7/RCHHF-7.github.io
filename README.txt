UPLOAD INSTRUCTIONS

Upload both items to the website root while preserving this exact structure:

index.html
assets/
  ai-strategy-map.svg

The page uses this portable relative path:
./assets/ai-strategy-map.svg

Because the path is relative to index.html, it works on the live GitHub Pages site, custom domains, staging folders, and local previews as long as the assets folder remains beside index.html.

The SVG is a true vector asset. It contains no embedded PNG and requires no JavaScript fallback.
