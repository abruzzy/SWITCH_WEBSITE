# Switch Website

Switch end-user website: buy/sell USDT, cash pickup, wallet payments.

## Run

Serve the folder over HTTP (opening the file directly from disk blocks the imports):

```
npx serve .
# or
python3 -m http.server 8080
```

Then open `index.html` (redirects to `Switch Exchange End User.dc.html`).

Works as-is on GitHub Pages: Settings → Pages → deploy from the main branch root.

## Files

- `Switch Exchange End User.dc.html` — main entry
- `support.js` — runtime (required)
- `brand/` — logos and wallet-provider marks
- `index.html` — redirect to the main entry
