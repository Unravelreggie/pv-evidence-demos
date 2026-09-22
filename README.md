# Evidence Lab — PV portfolio demos

[Open the live demo](https://unravelreggie.github.io/pv-evidence-demos/)

Three interactive, browser-only demonstrations of evidence-centered software design:

1. **PV workflow:** stage-specific evidence and human review gates.
2. **Data quality:** deterministic checks with named rules and row-level flags.
3. **Source retrieval:** local search across clearly invented passages with section locators.

Open `index.html` locally or use the published GitHub Pages site. There are no dependencies, accounts, API calls, cookies, analytics, or server-side components. English and Chinese interfaces are included.

## Data and scope

All record IDs, dates, documents, passages, and workflows are fabricated for this portfolio. No company source code, production records, patient information, licensed terminology, or genuine legal requirements are included. Search results illustrate traceability; they do not provide regulatory advice. The quality rules are examples and are not validated for operational use.

## Local preview

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — accessible content and demo structure
- `styles.css` — responsive presentation
- `app.js` — local interactions and synthetic examples
- `.nojekyll` — direct GitHub Pages publishing

## Verification

On 2026-09-22, the Mac mini checkout passed JavaScript syntax and Git whitespace checks. DOM interaction checks covered four workflow stages, five synthetic records, quality flags, language switching, and source search. The published Pages site was opened and checked in desktop and mobile viewports.
