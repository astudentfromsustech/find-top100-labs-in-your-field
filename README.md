# Top labs by field

Interactive lab rankings derived from the published literature (OpenAlex), one page per field:

- **Genome assembly** — `genome-assembly.html`
- **Assembly curation & QC** — `assembly-curation.html`
- **3D genomics** — `3d-genomics.html`

Open the site: **https://<user>.github.io/<repo>/**

Every page is self-contained HTML — no CDN, no build step. Sliders re-weight the composite live so
you can see how stable the order is, and **clicking a lab opens its own page**: profile and ORCID
links, research topics, the indicators behind its rank, and its most recent papers in that field with
abstracts and DOI links.

## How the roster is built

Every work matching the field query (2019–2026) is walked and each paper's **first and last author**
is counted — the PI signal — so the roster is the field, not a shortlist. Seven bibliometric
indicators are log-transformed, z-scored and weighted; GitHub stars are displayed but weighted 0 by
default. Method and limitations: see the site's Overview page.

## Rebuilding

Rankings are recomputed periodically. Last build: 2026-09-23.
