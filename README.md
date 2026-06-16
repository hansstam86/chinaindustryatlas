# China Industry Atlas — chinaindustryatlas.com

Static single-page site hosted on GitHub Pages. No build step.

## Files
- index.html ...................... the site (data + map embedded)
- China-Industry-Atlas-2026.pdf ... the downloadable guide (footer links to it)
- og-image.png .................... social link-preview card
- CNAME ........................... binds the custom domain (chinaindustryatlas.com)
- .nojekyll ....................... serve files as-is, skip Jekyll
- robots.txt / sitemap.xml ........ SEO

## Push it (new repo)
    git init -b main
    git add .
    git commit -m "China Industry Atlas"
    git remote add origin git@github.com:hansstam86/chinaindustryatlas.git
    git push -u origin main

## Enable Pages
Repo -> Settings -> Pages -> Build and deployment:
  Source = "Deploy from a branch", Branch = main, Folder = / (root) -> Save.
The CNAME file sets the custom domain automatically. Tick "Enforce HTTPS"
once the certificate is issued.

## DNS at your registrar
Apex (chinaindustryatlas.com) -> four A records:
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
Optional IPv6 -> AAAA records:
  2606:50c0:8000::153  2606:50c0:8001::153  2606:50c0:8002::153  2606:50c0:8003::153
www -> CNAME -> hansstam86.github.io
