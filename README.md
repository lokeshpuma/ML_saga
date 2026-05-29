# ML_saga

Hands-on machine learning practice with Jupyter notebooks: regression, K-Means clustering, exploratory data analysis, and student performance prediction using Python, NumPy, Pandas, and scikit-learn.

**Live site:** [https://lokeshpuma.github.io/ML_saga/](https://lokeshpuma.github.io/ML_saga/)

## Repository layout

| Path | Description |
|------|-------------|
| `src/` | Static site deployed to GitHub Pages |
| `notebooks/` | Jupyter notebooks |
| `data/` | CSV datasets used by the notebooks |

## Contents

- Data analysis with CSV datasets
- Regression models
- K-Means clustering
- Student performance and success prediction
- Practice notebooks for ML fundamentals

## Run locally

```bash
git clone https://github.com/lokeshpuma/ML_saga.git
cd ML_saga
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
jupyter notebook notebooks/
```

Notebooks load data from `../data/` relative to the `notebooks/` folder.

## GitHub Pages deployment

The site in `src/` is published automatically on every push to `main` via [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml).

**One-time setup in GitHub:**

1. Open **Settings → Pages** for [lokeshpuma/ML_saga](https://github.com/lokeshpuma/ML_saga).
2. Under **Build and deployment**, set **Source** to **GitHub Actions** (not “Deploy from a branch”).
3. Push to `main`; the workflow uploads `src/` and deploys the site.

After the first successful run, the site is available at `https://lokeshpuma.github.io/ML_saga/`.
