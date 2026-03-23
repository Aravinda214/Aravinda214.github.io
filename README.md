# Aravinda Boovaraghavan Portfolio

Personal portfolio site built with Hugo Blox and Tailwind CSS.

## Stack

- Hugo `0.148.2`
- Hugo Blox modules
- Tailwind CSS v4
- Netlify and GitHub Pages deployment workflows

## Repo Structure

- `config/_default/`
  Site-wide Hugo, menu, language, and theme configuration.
- `content/_index.md`
  Homepage sections and landing-page composition.
- `content/authors/admin/_index.md`
  Primary profile data: bio, education, work history, skills, awards, and social links.
- `content/experience.md`
  Experience page configuration using the author profile data.
- `content/projects.md`
  Projects landing page configuration.
- `content/project/`
  Individual project pages.
- `content/publication/`
  Publication entries, PDFs, featured images, and BibTeX files.
- `assets/media/`
  Custom images and organization logos.
- `layouts/partials/hooks/head-end/github-button.html`
  Small custom head injection for GitHub button support.

## Common Content Updates

- Update personal details, education, work history, skills, and awards in `content/authors/admin/_index.md`.
- Edit homepage sections in `content/_index.md`.
- Add or update publications in `content/publication/<slug>/`.
- Add or update projects in `content/project/<slug>/`.
- Update navigation in `config/_default/menus.yaml`.

## Local Development

Install the required tools first:

- Hugo extended `0.148.2`
- Node.js
- pnpm

Then run:

```bash
pnpm install
hugo server --disableFastRender
```

For a production build:

```bash
hugo --minify
```

## Deployment

- `netlify.toml` builds the site on Netlify and generates a Pagefind index.
- `.github/workflows/deploy.yml` builds and deploys the site to GitHub Pages.

## Notes

- The site is no longer using the starter project placeholder content.
- Publication entries currently double as the most detailed source of truth for linked research projects.
- If you add Hugo or Tailwind features later, this repo is already set up for that workflow, but the required binaries need to exist on the machine or CI runner.
