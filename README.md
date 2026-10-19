# Vela Laboratories website

Static technical site for velalaboratories.com. The page is intentionally buildless: deploy the repository root as a static site.

## Content provenance

Architecture and trust-boundary copy was checked against the Vela exchange repository, especially `docs/security/trust-model.mdx`, `docs/architecture/matcher-ledger-commit.md`, the engine, API, committer, and zkVM crates. The benchmark values come from `paper/rebenchmark-summary.json` and `paper/README.md` in the exchange repository. The public report is linked on the page.

The older 2.5M ops/s Apple M3 result is explicitly labeled historical. The October 2026 in-process, HTTP, and sustained figures retain their separate timing boundaries and failure counts. This is a concluded testnet research project, not a production exchange.
