# cloud-itonami-lei-5493003bzyyycdio0r13

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by ソフトバンクグループ株式会社.**

This repository archives the publicly published Privacy Policy of **ソフトバンクグループ株式会社** (SoftBank Group Corp.), with
source-url and retrieval-date provenance, per ADR-2607110300 (`cloud-itonami-lei-corporate-tos-catalog`,
`com-junkawasaki/root`). Read-only reference/archive repository — not a governed Advisor/Governor actor.

Part of the **worldwide-scope extension** of the cloud-itonami-lei catalog (batch JP-UTIL-1, 2026-07-19).

## Company identity

- **Legal name**: ソフトバンクグループ株式会社 (SoftBank Group Corp.)
- **LEI (ISO 17442)**: [5493003BZYYYCDIO0R13](https://search.gleif.org/#/record/5493003BZYYYCDIO0R13) (GLEIF entity-verified, JP)
- **Jurisdiction**: JP
- **Website**: https://www.softbankgroup.com
- **Ticker**: 9984 (TSE Prime)
- **ISIC Rev.5**: 6120

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of the archived Privacy Policy.
  ⚠ Its recorded `:tos/source-url` (`https://www.softbankgroup.com/en/privacy`) now
  redirects to the homepage; the current policy lives at
  `https://group.softbank/en/privacy` — see the drift note in `facts/catalog.edn`.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.
- `facts/catalog.edn` — 38 live-checked citations across five independent
  authorities (GLEIF, Japan NTA corporate-number site, METI gBizINFO, US SEC
  EDGAR, the issuer), each with a `:cite/row-kind` stating what it does and
  does not prove.
- `tools/verify_citations.cljs` — the gate: every citation must answer HTTP 2xx
  and carry its expected substring. Run
  `nbb tools/verify_citations.cljs facts/catalog.edn --min 13`
  (exit 0 = all checked and clean, 1 = drift, 2 = could not answer).

## Design rationale

See ADR-2607110300 and the worldwide-scope extension ledger (`2607110300-cloud-itonami-lei-corporate-tos-catalog.worldwide-progress.edn`) in `com-junkawasaki/root` (`90-docs/adr/`).
