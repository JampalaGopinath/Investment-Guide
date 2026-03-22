# Investment Guide: Grandparents → Grandchildren

> A practical, book-style guide to building and protecting wealth for minor grandchildren  
> using safe, government-backed Indian investment schemes (SBI FD · NSC · Post Office TD · SCSS).

**Live site:** https://JampalaGopinath.github.io/Investment-Guide/

---

## About this guide

This guide helps **grandparents** invest safely for their **minor grandchildren** over a 5–10 year horizon.  
It compares four government-backed options and provides a clear, recommended strategy.

All figures are based on **March 2026 rates**. Always check current rates at your bank or post office before investing.

---

## Running locally

### Prerequisites

- Python 3.9 or higher
- pip

### Install dependencies

```bash
pip install -r requirements.txt
```

### Serve the site locally

```bash
mkdocs serve
```

Then open http://127.0.0.1:8000 in your browser.

### Build the static site

```bash
mkdocs build
```

The output will be in the `site/` directory.

---

## Deployment

The site is deployed automatically to **GitHub Pages** using the workflow in  
`.github/workflows/deploy-mkdocs.yml`.

**How it works:**

1. On every push to the `main` branch, the workflow runs.
2. It installs Python dependencies from `requirements.txt`.
3. It builds the MkDocs site with `mkdocs build --strict`.
4. It uploads the built `site/` directory as a GitHub Pages artifact.
5. It deploys the artifact to the `github-pages` environment.

**One-time setup (done once by a repo admin):**

1. In the repository → **Settings → Pages**
2. Set **Source** to `GitHub Actions`
3. Push to `main` — the workflow deploys automatically

---

## Repository structure

```
.
├── mkdocs.yml                          # MkDocs configuration (Material theme)
├── requirements.txt                    # Python dependencies
├── docs/
│   ├── index.md                        # Home page
│   ├── assets/
│   │   └── stylesheets/
│   │       └── extra.css              # Book-style + side heading CSS
│   └── chapters/
│       ├── 01-goal-scenario.md
│       ├── 02-options-overview.md
│       ├── 03-sbi-fd.md
│       ├── 04-nsc.md
│       ├── 05-po-td.md
│       ├── 06-po-td-loophole.md
│       ├── 07-scss.md
│       ├── 08-interest-strategy.md
│       ├── 09-auto-renew.md
│       ├── 10-documents.md
│       ├── 11-nominee-guardian.md
│       ├── 12-death-case.md
│       ├── 13-five-vs-ten.md
│       ├── 14-maturity-comparison.md
│       ├── 15-2l-comparison.md
│       ├── 16-recommended-plan.md
│       └── 17-master-summary.md
└── .github/
    └── workflows/
        └── deploy-mkdocs.yml          # GitHub Pages deployment workflow
```

---

*Educational only. Consult your bank, post office, or a registered financial advisor before investing.*  
*Last updated: March 2026*
