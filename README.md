# Technical University of Darmstadt

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Technical University of Darmstadt (Technische Universitaet Darmstadt, TU Darmstadt) is a public technical research university in Darmstadt, Hesse, Germany, founded in 1877 and registered as ROR 05n911h24. It operates no central developer portal, publishes no OpenAPI description of its own, and its GitHub organization (TU-Darmstadt) is live but holds zero public repositories. What it does operate, and what makes this profile non-empty, is scholarly and identity infrastructure on its own domain: TUdatalib, the institutional research-data repository, runs DSpace 9.3 and exposes both a live HAL/JSON REST API and an OAI-PMH 2.0 interface; a DBRepo deployment at dbrepo.ulb.tu-darmstadt.de serves a live JSON API for research databases; and the Hochschulrechenzentrum (HRZ) runs the university's own Shibboleth SAML 2.0 identity provider, whose metadata is publicly retrievable and published into the German DFN-AAI federation and eduGAIN. TUbiblio and tuprints run on EPrints with OAI-PMH endpoints that are WAF-protected. The ULB is a DataCite consortium member (provider HLQC) registering DOIs for six repositories. TUjournals is real, machine-readable and busy, but it is a tenancy on Janeway shared hosting, not TU Darmstadt engineering. Every surface below is labelled with who actually operates it.

**Areas:** Education · Higher Education · University · Technical University · Germany · Research Data · Open Access · Scholarly Publishing · Library · OAI-PMH · DSpace · Identity Federation

## Technical University of Darmstadt on APIs.io

Everything profiled for Technical University of Darmstadt is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/technical-university-of-darmstadt/](https://apis.io/providers/technical-university-of-darmstadt/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [TUdatalib DSpace REST API](https://apis.io/apis/technical-university-of-darmstadt/tudatalib-rest/) — REST API of TUdatalib, the institutional research-data repository of TU Darmstadt. Verified live 2026-09-01: the API root returns HAL/JSON with dspaceName…
- [TUdatalib OAI-PMH](https://apis.io/apis/technical-university-of-darmstadt/tudatalib-oai/) — OAI-PMH 2.0 metadata harvesting interface for TUdatalib. Verified live 2026-09-01: Identify returns repositoryName "TUdatalib System", protocolVersion 2.0,…
- [TU Darmstadt Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/technical-university-of-darmstadt/shibboleth-idp/) — The university's own SAML 2.0 identity provider, operated by the Hochschulrechenzentrum (HRZ). Verified live 2026-09-01 (HTTP 200, 15,371 bytes of XML):…
- [DFN-AAI federation membership (eduGAIN)](https://apis.io/apis/technical-university-of-darmstadt/dfn-aai/) — TU Darmstadt's identity provider is published in DFN-AAI, the German research-and-education identity federation run by DFN, and is reachable through eduGAIN…
- [DBRepo API (research database repository)](https://apis.io/apis/technical-university-of-darmstadt/dbrepo/) — A DBRepo deployment run by the Universitaets- und Landesbibliothek for publishing and querying research databases. Hosted on the institution's own…
- [TUjournals REST API (Janeway tenancy)](https://apis.io/apis/technical-university-of-darmstadt/tujournals-janeway/) — TUjournals is TU Darmstadt's open-access journal platform, publisher of record "Universitaets- und Landesbibliothek Darmstadt". It runs a live, fully…
- [DataCite membership (provider HLQC)](https://apis.io/apis/technical-university-of-darmstadt/datacite-membership/) — TU Darmstadt registers DOIs through DataCite. Verified live 2026-09-01 via api.datacite.org/providers/hlqc: provider HLQC, "Universitaets- und…
- [ROR registration](https://apis.io/apis/technical-university-of-darmstadt/ror/) — TU Darmstadt is registered in the Research Organization Registry as https://ror.org/05n911h24, established 1877, domain tu-darmstadt.de, with GRID…
- [tuprints OAI-PMH (EPrints)](https://apis.io/apis/technical-university-of-darmstadt/tuprints-oai/) — tuprints is the open-access publication repository of TU Darmstadt, on the institution's own host and registered with DataCite as client hlqc.jslnah. It…
- [TUbiblio OAI-PMH (EPrints)](https://apis.io/apis/technical-university-of-darmstadt/tubiblio-oai/) — TUbiblio is the publication bibliography of TU Darmstadt, on the institution's own host (tubiblio18.ulb.tu-darmstadt.de, 130.83.152.163), running EPrints…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Technical University Of Darmstadt Context](https://apis.io/jsonld/technical-university-of-darmstadt/technical-university-of-darmstadt-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Technical University Of Darmstadt Authentication](https://apis.io/security/technical-university-of-darmstadt/technical-university-of-darmstadt-authentication/)
- [Technical University Of Darmstadt Domain Security](https://apis.io/security/technical-university-of-darmstadt/technical-university-of-darmstadt-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Technical University Of Darmstadt Plans Pricing](https://apis.io/plans/technical-university-of-darmstadt/technical-university-of-darmstadt-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Technical University Of Darmstadt Rate Limits](https://apis.io/rate-limits/technical-university-of-darmstadt/technical-university-of-darmstadt-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Technical University Of Darmstadt Finops](https://apis.io/finops/technical-university-of-darmstadt/technical-university-of-darmstadt-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tu-darmstadt.de/index.en.jsp)
- [Support](https://www.tu-darmstadt.de/kontakt_1/index.en.jsp)
- [Blog](https://www.tu-darmstadt.de/universitaet/aktuelles_meldungen/index.en.jsp)
- [Terms of service](https://www.tu-darmstadt.de/impressum/index.en.jsp)
- [Privacy policy](https://www.tu-darmstadt.de/datenschutzerklaerung)

## API Evangelist rating

**Kin Score 24.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/technical-university-of-darmstadt/](https://apis.io/providers/technical-university-of-darmstadt/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Technical University of Darmstadt: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/technical-university-of-darmstadt/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
