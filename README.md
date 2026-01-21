# SQL ORDER BY – Interaktiver Guide

Dieses Repo enthält eine statische Website (nur HTML/CSS/JS) und ist für GitHub Pages vorbereitet.

## Lokal starten

Im Projektordner:

```bash
python3 -m http.server 8000
```

Dann im Browser öffnen: `http://localhost:8000/`

## Deployment auf GitHub Pages

1. Repo auf GitHub erstellen (z.B. `sql-orderby-guide`).
2. Dieses Projekt pushen:

```bash
git remote add origin https://github.com/<USER>/<REPO>.git
git branch -M main
git push -u origin main
```

3. Auf GitHub: **Settings → Pages**
   - **Build and deployment** → **Source**: *Deploy from a branch*
   - **Branch**: `main`
   - **Folder**: `/ (root)`
   - **Save**

Nach kurzer Zeit ist die Seite erreichbar unter:

- `https://<USER>.github.io/<REPO>/`

## Hinweise

- `.nojekyll` ist enthalten, damit GitHub Pages keine Jekyll-Verarbeitung erzwingt.
- Verwende möglichst relative Pfade (keine absoluten `/...`-Pfade), damit es unter dem Repo-Pfad funktioniert.
