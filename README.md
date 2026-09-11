# Owen-Yang-18.github.io

Source for [owen-yang-18.github.io](https://owen-yang-18.github.io), built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template (v1.2).

## Where things are

The site is a single page.

| What                                                                     | File                            |
| ------------------------------------------------------------------------ | ------------------------------- |
| The page: bio, education, work experience, teaching experience, services | `_pages/about.md`               |
| Publications (every entry is listed on the page)                         | `_bibliography/papers.bib`      |
| Menu (each item jumps to a section of the page)                          | `_data/navigation.yml`          |
| Profile photo                                                            | `assets/img/prof_pic.jpg`       |
| Resume (linked from the CV icon)                                         | `assets/pdf/Yi_Yang_Resume_2026.pdf` |
| Social links                                                             | `_data/socials.yml`             |
| Site settings                                                            | `_config.yml`                   |

`_includes/header.liquid` overrides al-folio's header so that the menu links jump to sections of the page instead of separate pages.

## Preview locally

On the DGX machine, Ruby, ImageMagick and Node live in a micromamba environment named `jekyll`:

```bash
export MAMBA_ROOT_PREFIX=~/.local/share/mamba
~/.local/bin/micromamba run -n jekyll bundle exec jekyll serve
```

Then open http://localhost:4000. Elsewhere, follow al-folio's [install guide](https://github.com/alshedivat/al-folio/blob/main/docs/INSTALL.md).

## Deploy

Pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch. In the repository settings, Pages must deploy from the `gh-pages` branch.
