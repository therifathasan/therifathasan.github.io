# Md Rifat Hasan · Business Analytics Portfolio

A static, single-page case-study site for GitHub Pages. It has no build step and no dependencies apart from Google Fonts.

## Files

| Path | What it is |
|---|---|
| `index.html` | The portfolio page (styles, charts and interactions are inline) |
| `gt-demo.html` | Interactive replica of the live GT sales dashboard, on synthetic data |
| `img/` | Screenshots: Power BI images use sanitised data, GT images use synthetic data |
| `downloads/FMCG-Sales-Report.pbix` | Power BI report with sanitised data |
| `downloads/Haribo-Demand-Forecast.xlsx` | Haribo forecasting and ordering model (Excel), sanitised |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

1. Create a repository on GitHub, for example `portfolio`, or `<username>.github.io` if you want the site at the root address.
2. Upload everything in this folder to the repository root, including `.nojekyll`.
3. In the repository, open **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<username>.github.io/<repository>/`, or `https://<username>.github.io/` for a `<username>.github.io` repository.
