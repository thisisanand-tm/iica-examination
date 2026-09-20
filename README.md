# IICA Examination - Director Mock India

Dedicated home of the exam application migrated from `thisisanand-tm/sudoku`.

Test site: https://thisisanand-tm.github.io/iica-examination/

Sudoku game: https://thisisanand-tm.github.io/sudoku/

## Preserved application

The migration preserves all application code, all 501 active questions and their IDs, all source licences, audit records, candidate datasets, icons and maintenance scripts. Question content and exam scoring have not been changed or revalidated by this migration. The bank metadata records its existing 16 September 2026 review.

Browser history keys (`directorMock.history.v2` and related keys) remain unchanged. Both paths use the same GitHub Pages origin, so existing results remain available in the same browser profile. The service worker is isolated to this application and does not delete Sudoku caches.

## Deployment

The active `migrate-and-publish.yml` workflow validates and publishes changes to `main`. GitHub Pages must use GitHub Actions as its publishing source.

## Historical maintenance workflows

All original workflow definitions are preserved byte-for-byte in `maintenance/legacy-workflows/`. They are archived, not active: several are one-time migrations with old branch names or hard-coded historical bank sizes. Their supporting scripts remain in `scripts/`. Do not run an old promotion script against the live bank without reviewing its preconditions.

## Provenance

See `migration/source-manifest.json` for original and migrated file hashes, `SOURCES.md` and `QUESTION_BANK_LICENSE.md` for attribution, and `audit/` for historical validation evidence.
