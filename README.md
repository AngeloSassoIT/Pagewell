# diario-site

Sito statico di **Pagewell Nightjar** (app iOS), pronto per GitHub Pages.

## Pubblicazione

```sh
# crea il repository su GitHub (es. diario-site), poi:
cd ~/diario-site
git remote add origin https://github.com/<tuo-utente>/diario-site.git
git push -u origin main
```

Su GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / (root)** → Save.
Il sito sarà su `https://<tuo-utente>.github.io/diario-site/`.

## Pagine

- `index.html` — landing page (italiano)
- `privacy.html` — privacy policy (URL da inserire in App Store Connect)
- `support.html` — supporto/FAQ (URL assistenza per App Store Connect)
- `en/` — versione inglese delle tre pagine (per la localizzazione EN della scheda ASC:
  `…/diario-site/en/privacy.html` e `…/diario-site/en/support.html`)

Quando l'app è approvata, sostituisci l'`href="#"` del bottone in `index.html`
con il link App Store (`https://apps.apple.com/app/idXXXXXXXXX`).
