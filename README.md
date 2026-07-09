# A Church Prepared for Revival — A Pilot Proposed

**Read the book:** https://jgtittle-ministries.github.io/a-church-prepared-for-revival-a-pilot-proposed/

A proposal offered to a church asking two questions: *Do you want a revival? And if yes, what might it take to prepare the soil?* Four movements — the question, the soil, the preparation, the keeping — with a Reference section pointing into [*Intentional Journey of the Heart*](https://jgtittle-ministries.github.io/Intentional-Journey-of-the-Heart/) as the foundation base and [*Fellowship of the Heart*](https://jgtittle-ministries.github.io/fellowship-of-the-heart-pilot-at-cca/) as the leadership-formation pilot it leans on.

This is the published edition. Working drafts and revisions land first in [`a-church-prepared-for-revival-a-pilot-proposed-dev`](https://github.com/jgtittle-ministries/a-church-prepared-for-revival-a-pilot-proposed-dev) and are mirrored here on the author's review.

## Repo mechanics

- Static markdown reader (same engine as the sibling books): `index.html` redirects into `reader.html`, which renders `docs/**/*.md` per `manifest.js`.
- `manifest.js` and `search-index.json` are **generated** — do not hand-edit:
  - `node tools/build-manifest.mjs`
  - `node tools/build-search-index.mjs`

## License

Text and materials © John G. Tittle, licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
