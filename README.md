# National BIM mandates: regulatory status by jurisdiction

The dataset behind the **[World BIM Mandates Map](https://solebo.org/bim-mandates/)** (Solebo). Last reviewed: 14 June 2026.

59 jurisdictions, each anchored to an **official primary source** — a government decree, law, circular, adopted standard or official programme page. No aggregators, vendors or consultancies are cited as the source of a mandate. 95 source links in total.

| File | Format |
|---|---|
| `bim-mandates.csv` | Flat table, one row per jurisdiction; source URLs joined with ` \| ` |
| `bim-mandates.json` | Full records with structured sources (title, URL, language) plus the classification scales |

## Three layers

**Mandate status** (19 mandatory · 19 partial · 21 voluntary)
- `mandatory` — BIM legally/contractually required now for a defined class of (usually public) projects
- `partial` — required by value threshold, sector, phase-in, or by a specific public agency rather than nationwide
- `voluntary` — official roadmap, strategy, declaration or recommended standard; not yet binding

**Technical schema — IFC / ISO 16739** (`ifc_level`): `required` · `adopted` · `process` · `developing` · `none`

**Professional qualification** (`qualification_level`): `standard` · `certification` · `emerging` · `none`

## Fields

`iso2`, `iso3`, `name`, `region`, `mandate_status`, `instrument`, `authority`, `effective`, `summary`, `ifc_level`, `ifc_standards`, `qualification_level`, `qualification_scheme`, `sources` (JSON) / `source_count`, `source_urls` (CSV)

## Caveats

Some government portals are geo-restricted or JavaScript-rendered and open only in a browser — a link that fails from one location may still be valid. BIM law changes fast; check `last_reviewed`.

## Corrections

Found a newer decree, a broken link or a jurisdiction we missed? Open an issue with the official source.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse freely, including commercially, as long as you credit the source.

## Cite

> Shtaer, I. (2026) *National BIM mandates: regulatory status by jurisdiction* (v1.0) [Data set]. Solebo. https://solebo.org/bim-mandates/
