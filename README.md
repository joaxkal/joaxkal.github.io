# Joanna Kaleta — personal research website

Static portfolio website, ready for GitHub Pages.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a public repository named `joaxkal.github.io` on GitHub.
2. From this `webpage` directory, run:

```bash
git init
git add .
git commit -m "Launch personal research website"
git branch -M main
git remote add origin https://github.com/joaxkal/joaxkal.github.io.git
git push -u origin main
```

3. In the repository settings, open **Pages** and set the source to **Deploy from a branch**, using `main` and `/ (root)`.

The site will be available at `https://joaxkal.github.io/`.

Only publish the contents of this directory. The parent application folder contains private documents and should never be added to the repository.
