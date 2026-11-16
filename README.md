# DuoFlow Project Page

English project page for **DuoFlow: Towards Synchronized Speech and Motion Generation with Fine-Grained Control**.

- Live website: https://jundong-dev.github.io/DuoFlow-project-page/
- Source repository: https://github.com/JunDong-dev/DuoFlow-project-page

## Contents

`index.html` contains the page, styles, prompt comparisons and demo controls. `assets/` contains the 3 figures and 96 video files referenced by the page. All media paths are relative. This repository publishes the English website only.

## Local use

Open `index.html` in a modern browser. If local media loading is restricted, run the following command from the repository directory and visit `http://localhost:8000/`:

```sh
python3 -m http.server 8000
```

## Updating the website

Edit `index.html` and its referenced assets, then commit and push the changes to `main`. GitHub Pages publishes the repository root. The `.nojekyll` file preserves the static files without a Jekyll build.

```sh
git add index.html assets README.md .nojekyll .gitignore
git commit -m "Update project page"
git push origin main
```
