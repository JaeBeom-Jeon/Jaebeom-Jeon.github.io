# jaebeom-jeon.github.io

Personal academic website of Jaebeom Jeon, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Where to edit

| What | File |
| --- | --- |
| Intro text, subtitle | `_pages/about.md` |
| Profile photo | `assets/img/prof_pic.jpg` |
| Publications | `_bibliography/papers.bib` |
| Social links (email, GitHub, LinkedIn, Instagram) | `_data/socials.yml` |
| Venue badge colors | `_data/venues.yml` |
| Site name, URL, general options | `_config.yml` |

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch.
GitHub Pages must be set to deploy from the `gh-pages` branch (Settings → Pages).
