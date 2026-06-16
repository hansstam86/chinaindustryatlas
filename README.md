# China Industry Atlas — chinaindustryatlas.com

Static site on GitHub Pages. No build step.

/ ................................ main atlas
/huaqiangbei/ .................... Huaqiangbei building map (real Leaflet map + directory)
/huaqiangbei/leaflet.js|.css ..... self-hosted Leaflet 1.9.4 (basemap tiles load from CARTO at runtime)
China-Industry-Atlas-2026.pdf .... downloadable guide
og-image.png ..................... social preview card
atlas_data.json, hqb_data.json ... canonical data
CNAME, .nojekyll, robots.txt, sitemap.xml

## Update the live deploy
    git add -A
    git commit -m "Real Huaqiangbei map (Leaflet, true coordinates)"
    git push
