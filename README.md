# China Industry Atlas — chinaindustryatlas.com

Static site on GitHub Pages. No build step. Leaflet from cdnjs (unpkg fallback); tiles from CARTO.

/ ............................ main atlas
/prd/ ........................ Pearl River Delta industry-cluster map
/yrd/ ........................ Yangtze River Delta industry-cluster map
/bohai/ ...................... Bohai Rim industry-cluster map
/guangdong/ .................. Guangdong province industry-cluster map (all 21 prefectures)
/shandong/ ................... Shandong province industry-cluster map (all 16 prefectures)
/jiangsu/ .................... Jiangsu province industry-cluster map
/zhejiang/ ................... Zhejiang province industry-cluster map
/fujian/ ..................... Fujian province industry-cluster map
/guangzhou/ .................. Guangzhou wholesale-market map
/huaqiangbei/ ................ Huaqiangbei building map (Shenzhen)
/yiwu/ ....................... Yiwu district & floor map
China-Industry-Atlas-2026.pdf  downloadable guide
*_data.json .................. canonical data per page
CNAME, .nojekyll, robots.txt, sitemap.xml

## Update the live deploy
    git add -A
    git commit -m "Add Shandong province industry-cluster map"
    git push
