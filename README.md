# portfolio-skz-dev

Single-page portfolio served at https://portfolio.skz.dev.

Standalone HTML — no build step. GitHub Pages serves `index.html` from `main`
and HTTPS is auto-provisioned via the `CNAME` file.

## Deploy

Edit `index.html`, push to `main`, done.

## Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```
