# A³BS GIMP 3 Documentation

Public documentation for A Cubed's GIMP 3 automation tools and plugins. Expectations include structured, versioned documentation for the GIMP 3 Python plugin ecosystem created by **A Cubed Business Solutions** (A³BS).

## 📂 Structure

```plaintext
a3bs-public/
└── gimp/
└── docs/
├── index.md         # Main landing page for GitHub Pages
├── docs/
│   ├── gimp-arch/   # Auto-documented GIMP classes
│   ├── install/     # GIMP 3 install guides
│   └── overviews/   # Plugin overviews and summaries
└── manifest.log     # Tracks cleaned file revisions
```

## 🔄 Workflow

- All changes originate in the `a3bs-dirty/` folder.
- Only explicitly cleaned or verified files are moved to `a3bs-clean/`.
- Unchanged files are moved (not copied).
- Cleaned files are committed as part of Baseline 0 and beyond.

## 🛠️ Jekyll Setup

This site is deployed via GitHub Pages using the [Minima](https://github.com/jekyll/minima) theme.
Ensure the following exists at the repo root:

- `_config.yml` with `theme: minima`
- `index.md` as your site landing page

## 🧼 Current Status

Baseline 0 committed. `a3bs-clean/` is fully synchronized and documented.


📄 View the live docs site: ![GitHub Pages](https://img.shields.io/github/deployments/aaabscom/a3bs-gimp-docs/github-pages?label=docs&logo=github)

---

This repo contains:

- Class documentation
- Plugin introspection utilities
- Batch workflows and image tools

---

Built with care by **D & G**.
