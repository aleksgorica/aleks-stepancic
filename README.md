# Aleks Stepančič


Personal website, published with GitHub Pages.


Website: https://aleks-stepancic.github.io/


- `index.html`: prose homepage with About me navigation.
- `cv/`: separate CV-style layout.
- `courses/`: all 47 courses.
- `taste/`: alternative prose typography and matching course page.


The website is static HTML and CSS. No server or installation is required. GitHub Pages publishes the root of the `main` branch; `.nojekyll` disables Jekyll processing. All links and assets use relative paths so the site also works under the repository URL.


To update from the original local workspace, rebuild the portfolio and run:


```sh
node aleks-personal/scripts/build-github-pages.mjs
```


Then commit and push the changes in this repository. The export includes only the public site pages and the assets they use. The Newsreader license is in `assets/fonts/Newsreader-OFL.txt`.

