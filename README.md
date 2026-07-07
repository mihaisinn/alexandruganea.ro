# Asociația Alexandru Ganea - website static

Acest repo este pregătit pentru publicare automată cu **GitHub Pages** prin GitHub Actions.

## Publicare
1. În GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
2. Fă push pe branch-ul pe care lucrezi (workflow-ul rulează acum pe orice branch).
3. După ce workflow-ul `Deploy static site to GitHub Pages` rulează cu succes, site-ul va fi disponibil la:

- `https://<username>.github.io/<repo>/`

Pentru acest repo public menționat (`mihaisinn/alexandruganea.ro`), URL-ul va fi:

- `https://mihaisinn.github.io/alexandruganea.ro/`


## Debug rapid pentru 404
- Verifică în tab-ul **Actions** că workflow-ul `Deploy static site to GitHub Pages` a rulat cu status verde.
- Verifică în **Settings → Pages** că `Source` este `GitHub Actions`.
- Dacă ai făcut commit pe un branch diferit, fă push încă o dată (workflow-ul rulează acum pe orice branch).
