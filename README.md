# China Industry Atlas — chinaindustryatlas.com

Static site on GitHub Pages. No build step.

/ ................................ main atlas
/huaqiangbei/ .................... Huaqiangbei building map (Leaflet, real coords)
/yiwu/ .......................... Yiwu district & floor map (Leaflet, real coords)
China-Industry-Atlas-2026.pdf .... downloadable guide
atlas_data.json / hqb_data.json / yiwu_data.json ... canonical data
CNAME, .nojekyll, robots.txt, sitemap.xml

Leaflet loads from cdnjs (with an unpkg fallback); basemap tiles from CARTO. No local JS deps.

## Update the live deploy
    git add -A
    git commit -m "Load Leaflet from CDN (fix L is not defined)"
    git push
