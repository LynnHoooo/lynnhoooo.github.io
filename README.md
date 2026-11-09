# Lynn’s Little Lab

Personal homepage of Lynn Hu, built with [Fuwari](https://github.com/saicaca/fuwari) and Astro.

Live site: https://lynnhoooo.github.io/

## Repository layout
- Repository root: built static website for the existing GitHub Pages branch deployment.
- `site-source/`: editable Fuwari/Astro project and original MIT license.
- `site-source/src/config.ts`: profile, navigation, and site settings.
- `site-source/src/content/`: English project articles and About page.
- `site-source/public/images/`: anime avatar and generated starry banner.

## Development
Use Node.js 22 and pnpm. From `site-source/`, run `pnpm install`, then `pnpm dev`.

To update the published site, run `pnpm build` and copy the contents of `site-source/dist/` to the repository root before committing. Keep `.nojekyll` in the root.

The linked one-page PDF resume remains in its original language. All website text is English.

Theme: Fuwari by saicaca, MIT license; attribution retained in the footer and source license.
