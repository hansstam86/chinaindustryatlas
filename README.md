# China Industry Atlas — chinaindustryatlas.com

Static site on GitHub Pages. No build step. Leaflet loads from cdnjs (unpkg fallback); tiles from CARTO.

/ ............................ main atlas
/prd/ ........................ Pearl River Delta industry-cluster overview map
/huaqiangbei/ ................ Huaqiangbei building map
/yiwu/ ....................... Yiwu district & floor map
China-Industry-Atlas-2026.pdf  downloadable guide
atlas_data.json / prd_data.json / hqb_data.json / yiwu_data.json  canonical data
CNAME, .nojekyll, robots.txt, sitemap.xml

## Update the live deploy
    git add -A
    git commit -m "Add PRD industry-cluster overview map"
    git push
