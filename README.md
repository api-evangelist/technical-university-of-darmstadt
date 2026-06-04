# Technical University of Darmstadt (technical-university-of-darmstadt)

The Technical University of Darmstadt (Technische Universitat Darmstadt, TU Darmstadt) is a public research university in Darmstadt, Germany, ranked #241 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) profile. TU Darmstadt has no single central developer portal; its documented APIs are concentrated in the university and state library (ULB) scholarly-infrastructure stack — the TUdatalib research-data repository (DSpace 8.1) and the TUbiblio and tuprints EPrints repositories.

APIs.json: https://raw.githubusercontent.com/api-evangelist/technical-university-of-darmstadt/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=technical-university-of-darmstadt-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Access, Library, OAI-PMH, DSpace, Germany

## APIs

- **TUdatalib DSpace REST API** — REST API of the TUdatalib research-data repository (DSpace 8.1). Base: `https://tudatalib.ulb.tu-darmstadt.de/server/api`. Docs: https://tudatalib.ulb.tu-darmstadt.de/docs/en/faq/
- **TUdatalib OAI-PMH** — OAI-PMH 2.0 metadata harvesting for TUdatalib. Base: `https://tudatalib.ulb.tu-darmstadt.de/server/oai/request`. Docs: https://tudatalib.ulb.tu-darmstadt.de/docs/en/faq/
- **TUbiblio OAI-PMH (EPrints)** — OAI-PMH metadata for the TU Darmstadt publication bibliography. Base: `https://tubiblio.ulb.tu-darmstadt.de/cgi/oai2`. Docs: https://tubiblio.ulb.tu-darmstadt.de/
- **tuprints OAI-PMH (EPrints)** — OAI-PMH metadata for the tuprints open-access repository. Base: `https://tuprints.ulb.tu-darmstadt.de/cgi/oai2`. Docs: https://tuprints.ulb.tu-darmstadt.de/

## Plans / Rate Limits / FinOps

- Plans: [plans/technical-university-of-darmstadt-plans-pricing.yml](plans/technical-university-of-darmstadt-plans-pricing.yml)
- Rate Limits: [rate-limits/technical-university-of-darmstadt-rate-limits.yml](rate-limits/technical-university-of-darmstadt-rate-limits.yml)
- FinOps: [finops/technical-university-of-darmstadt-finops.yml](finops/technical-university-of-darmstadt-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tu-darmstadt.de/index.en.jsp
- GitHub: https://github.com/TU-Darmstadt
- LinkedIn: https://www.linkedin.com/school/tu-darmstadt/
- Authentication (SSO): https://www.hrz.tu-darmstadt.de/sso

## Notes

All entries reflect what was verifiable during review (2026-06-03). The TUdatalib REST API and OAI-PMH endpoints were confirmed live (HTTP 200, valid responses). The tuprints repository root resolved (200) but its OAI path returned 403 to a plain client (likely requires a standard harvester user-agent). The TUbiblio host applied bot/TLS filtering and could not be curl-verified directly, though it loads in a browser. The official-named GitHub org `TU-Darmstadt` exists but currently has no public repositories. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
