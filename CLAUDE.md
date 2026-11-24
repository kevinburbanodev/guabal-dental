# CLAUDE.md

- `npm run dev` starts Vite, `npm run build` type-checks with `vue-tsc -b` and builds. No tests or linter; unused locals fail the build.
- Single page, no router, no backend. `src/data.ts` holds all content (illustrative), `src/booking.ts` the form state, `src/demo.ts` the link to the services page.
- **Tile grid** (`src/style.css`): `--t` and `--pitch` use `cqw`, so `.wall` must stay inside `.wallbox`. Murals draw their grout with `--pitch`; if a row grows past `--t` the grout drifts.
- Appointment dates are computed from today; Saturdays only offer morning hours and Sundays none.
- The clinic does not exist: no testimonials, reviews, awards, credentials or years in business, keep the demo notice, never connect the form to a real third party. See `PRODUCT.md`.
