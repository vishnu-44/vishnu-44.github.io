# Portfolio Prototype

This folder contains a static prototype portfolio site built from your resume content.

## 1) Conda environment

```bash
conda activate portfolio-prototype
```

If needed, recreate it:

```bash
conda create -n portfolio-prototype -y python=3.11
```

## 2) Run locally

```bash
python -m http.server 8000
```

Open: `http://127.0.0.1:8000`

## 3) Files

- `index.html`: content and page structure
- `styles.css`: layout and visual design
- `environment.yml`: minimal env spec

## 4) Deploy to GitHub Pages

1. Create repo: `yourusername.github.io`
2. Push these files to the repo root
3. In GitHub, go to `Settings > Pages`
4. Set source to `Deploy from branch`, branch `main`, folder `/ (root)`
5. Your site will appear at `https://yourusername.github.io/`
