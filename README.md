# China Industry Atlas — chinaindustryatlas.com

Static site on GitHub Pages. No build step. Leaflet from cdnjs (unpkg fallback); tiles from CARTO.

/ ............................ main atlas
/prd/ ........................ Pearl River Delta industry-cluster map
/yrd/ ........................ Yangtze River Delta industry-cluster map
/huaqiangbei/ ................ Huaqiangbei building map (Shenzhen)
/yiwu/ ....................... Yiwu district & floor map
China-Industry-Atlas-2026.pdf  downloadable guide
*_data.json .................. canonical data per page
CNAME, .nojekyll, robots.txt, sitemap.xml

## Update the live deploy
    git add -A
    git commit -m "Add Yangtze River Delta industry-cluster map"
    git push
