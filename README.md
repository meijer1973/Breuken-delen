# Delen met Breuken

Een simpele statische webapp om het delen met breuken te oefenen. De app is geschikt voor GitHub Pages en bevat een workflow om automatisch te publiceren zodra de repository op GitHub staat en GitHub Pages is ingeschakeld.

## Lokaal openen

Open `index.html` direct in je browser of start een simpele webserver:

```bash
python3 -m http.server 8000
```

Ga daarna naar <http://localhost:8000>.

## GitHub Pages

Zodra deze map naar een GitHub-repository is gepusht:

1. Open **Settings → Pages**.
2. Kies **GitHub Actions** als bron.
3. De workflow in `.github/workflows/pages.yml` publiceert daarna automatisch de site.

De verwachte URL wordt meestal:

```text
https://<github-gebruikersnaam>.github.io/<repo-naam>/
```
