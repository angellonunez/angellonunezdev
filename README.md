# Angello Nuñez — Portfolio

Personal portfolio at angellonunez.dev, built with Astro, Tailwind CSS, and locally hosted Onest fonts. The public site is in English.

## Development

- `npm ci`
- `npm run dev` — local preview at http://localhost:4321
- `npm run build` — static production output in `dist/`
- `npm run preview` — serve the production build
- `npm run deploy` — builds and publishes to GitHub Pages (only run when publishing is intended)

## Content and design

- `src/data/projects.ts`: featured projects, descriptions, and destinations.
- `src/components/Hero.astro`: introduction and project badges.
- `src/components/AboutMe.astro`: personal story.
- `src/components/Experience.astro` and `Education.astro`: existing career and education history. Dates marked “Present” are inherited from the previous portfolio and should be confirmed by Angello.
- `src/styles/global.css`: responsive visual design and reduced-motion behavior.
- `src/layouts/Layout.astro`: language, SEO metadata, and favicon declarations.

The alternative alpaca favicon and Peruanify artwork come from the owner's existing asset collection. Shopperpic is a generated 3D interpretation of the existing green viewfinder mark. Zelandaware's black robotic hand was generated for this portfolio. Optimized transparent WebP assets and PNG favicons are stored in `public/`.

Shopperpic currently uses an email inquiry link: its domain could not be reached and its repository returned 404 for unauthenticated visitors during verification. Replace the destination when its public site is available.

## Verification

Production build and browser checks passed at 1440, 768, 390, and 320 pixels: no horizontal overflow, broken images, missing anchor targets, or page JavaScript errors. The project navigation and component gallery were checked. External service availability is outside the scope of local UI checks.

Compatible dependency updates reduced npm audit findings from 22 to 8. The remaining report includes Astro and build/deployment tooling and requires a separate major-version compatibility review; this is not a claim that every advisory is exploitable in this static site. Run `npm audit` for the current report.

Zenzeito and Emprezus use generated 3D versions of their existing capybara and gold geometric brand marks. Angello’s original portfolio photos are served locally in the header, introduction, and biography. The sunglasses alpaca is retained as an unused alternative. Favicons and the touch icon now show a generated 3D portrait of Angello using a laptop, based on his original photo.

Lecthur and Spendo have transparent 3D icons based on their App Store artwork, displayed in the introduction and app links. The navbar includes the personal 3D logo and “My portfolio”. A flow-root on the body prevents the header margin from exposing a differently colored strip above the page.

The mobile app collection includes Lecthur, Spendo, DateSpots, PetSnack, AI Resume Builder, and AI Logo Maker. Names, descriptions, and App Store destinations are based on the local Zelandaware product catalog. New 3D badges preserve the corresponding app icon identities.
