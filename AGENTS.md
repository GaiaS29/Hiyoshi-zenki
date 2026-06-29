# Hiyoshi-zenki

## Cursor Cloud specific instructions

This repository is a **static document site**, not a code project. It contains:

- `index.html` — a large Japanese research document (CSW61 country research). Note: despite the `.html` extension, the file currently holds Markdown-style content with no HTML tags/scripts/styles, so browsers render it as plain text.
- `README.md` — a one-line title.

There are no dependencies, package manager, build step, automated tests, or linters. Nothing needs to be installed (Python 3 ships with the VM).

### Run (development)

Serve the static files with Python's built-in server from the repo root:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html`.

### Lint / Test / Build

Not applicable — there is no lint, test, or build tooling in this repo.
