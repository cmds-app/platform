# CMDS Docs

Developer documentation site for CMDS projects, published at **https://docs.cmds.app** via GitHub Pages.

Built with [MkDocs](https://www.mkdocs.org/) and the [Material theme](https://squidfunk.github.io/mkdocs-material/).

## Local work environment

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve --livereload
```

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve --livereload
```

Open <http://127.0.0.1:8000> — the site live-reloads on save.

## Build

```bash
mkdocs build --strict
```

Output is written to `dist/docs` (git-ignored).

## Deploying

Commits to `main` trigger `.github/workflows/docs.yml`, which builds the site and publishes to GitHub Pages. Enable **Settings → Pages → Source: GitHub Actions** on the repository, and point a `CNAME` DNS record from `docs.cmds.app` to the Pages host.

## Structure

```
docs/
├── index.md                        # Landing page
├── conventions/                    # Coding conventions
│   ├── index.md
│   └── folder-structure.md
└── projects/                       # Per-project documentation
    ├── index.md
    └── bump.md
```

Add new projects under `docs/projects/<name>.md` and register them in `mkdocs.yml`'s `nav`.
