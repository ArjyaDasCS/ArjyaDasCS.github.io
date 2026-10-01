# arjyadas.github.io

Personal academic website of Arjya Das, built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT).

## Where things live

| Page         | Edit                                                                                   |
| ------------ | -------------------------------------------------------------------------------------- |
| About (home) | `_pages/about.md`, photo at `assets/img/prof_pic.jpg`                                  |
| News         | one file per item in `_news/`                                                          |
| Research     | one file per project in `_projects/`, images in `assets/img/projects/`                 |
| Publications | `_bibliography/papers.bib`                                                             |
| Teaching     | `_pages/teaching.md`                                                                   |
| CV           | `_data/cv.yml`; PDF at `assets/pdf/cv.pdf` (then uncomment `cv_pdf` in `_pages/cv.md`) |
| Social links | `_data/socials.yml`                                                                    |
| Site config  | `_config.yml`                                                                          |

## Deploy

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and pushes it to the `gh-pages` branch.
One-time setup in the repo's **Settings**:

1. **Actions → General → Workflow permissions:** Read and write.
2. **Pages → Build and deployment:** Deploy from a branch, `gh-pages` / `(root)` (the branch appears after the first workflow run).

## Local preview (optional)

```bash
bundle install && bundle exec jekyll serve   # http://localhost:4000
```

Theme docs: `docs/CUSTOMIZE.md`.
