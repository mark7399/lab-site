# Jiazhou Chen Lab Website (MkDocs + Material)

## Quick Start
1. Create a GitHub repo (e.g., `lab-site`) and push these files to `main`.
2. GitHub Actions will build and deploy to `gh-pages` automatically.
3. Visit `https://<your-username>.github.io/lab-site/` (set in `mkdocs.yml`).

## Editing Content
- Pages live in `docs/*.zh.md` and `docs/*.en.md` (bilingual).
- Publications: add BibTeX to `docs/assets/refs.bib`.
- Add member photos to `docs/assets/people/` and link them from `people.zh.md` / `people.en.md`.

## Collaboration
- Recommend collaborators use branches + Pull Requests.
- You can add CODEOWNERS to require review by maintainers.

## Next Steps (Phase 2)
- Add interactive charts (Plotly/ECharts) in Markdown.
- If you need a database-backed service, plan a FastAPI + PostgreSQL stack and link from the site.
