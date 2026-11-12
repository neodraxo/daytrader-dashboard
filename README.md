# daytrader-dashboard

Publishes the DayTrader status page (password-protected) to GitHub Pages.

This repo is public but holds no data: the workflow in `.github/workflows/publish.yml` builds the page from two private repos, encrypts it with StatiCrypt, and publishes only the encrypted page. The builder and its documentation live in the private `daytrader` repo under `dashboard/`.
