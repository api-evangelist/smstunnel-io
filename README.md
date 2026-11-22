# SMSTunnel

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

SMSTunnel enables developers to send SMS messages directly from their web, desktop, or server applications using their own Android phone and SIM. By installing the SMSTunnel app on a personal device, users gain a private, end‑to‑end encrypted gateway that routes messages through their own number, avoiding shortcodes and third‑party services. The platform offers a free tier with limited daily texts and paid plans for higher volumes, includes optional encryption, and provides a dashboard for managing contacts, logs, and device settings. It supports integrations with popular automation tools and offers API documentation for programmatic access.

**Areas:** SMS · Messaging · API · Encryption · Free-tier · Company

## SMSTunnel on APIs.io

Everything profiled for SMSTunnel is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/smstunnel-io/](https://apis.io/providers/smstunnel-io/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [SMSTunnel Account API](https://apis.io/apis/smstunnel-io/smstunnel-io-account-api/) — Your plan and usage.
- [SMSTunnel Other tools' formats API](https://apis.io/apis/smstunnel-io/smstunnel-io-other-tools-formats-api/) — Send routes for tools that name the fields their own way, or expect a specific provider's request. They apply the rules of the strict send routes.
- [SMSTunnel Phones API](https://apis.io/apis/smstunnel-io/smstunnel-io-phones-api/) — Your linked phones and their end-to-end encryption keys.
- [SMSTunnel Received texts API](https://apis.io/apis/smstunnel-io/smstunnel-io-received-texts-api/) — Texts your phone received, once "Sync received texts" is on in the app.
- [SMSTunnel Scheduled texts API](https://apis.io/apis/smstunnel-io/smstunnel-io-scheduled-texts-api/) — Texts sent with `sendAt`: list, read and cancel them.
- [SMSTunnel Texts API](https://apis.io/apis/smstunnel-io/smstunnel-io-texts-api/) — Send a text or a sign-in code to one recipient, and follow its status.
- [SMSTunnel Twilio Compatible API](https://apis.io/apis/smstunnel-io/smstunnel-io-twilio-compatible-api/) — Twilio's Messages, Verify v2 and Lookup v2 at Twilio's own paths, so code written for Twilio works by changing the host to `https://api.smstunnel.io` and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [SMSTunnel Agentic Access](https://apis.io/agentic-access/smstunnel-io/smstunnel-io-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [PhoneNumberLookup](https://apis.io/schemas/smstunnel-io/smstunnel-io-phone-number-lookup/)
- [SendTextRequest](https://apis.io/schemas/smstunnel-io/smstunnel-io-send-text-request/)
- [TwilioMessage](https://apis.io/schemas/smstunnel-io/smstunnel-io-twilio-message/)
- [Usage](https://apis.io/schemas/smstunnel-io/smstunnel-io-usage/)
- [Verification](https://apis.io/schemas/smstunnel-io/smstunnel-io-verification/)
- [VerifyService](https://apis.io/schemas/smstunnel-io/smstunnel-io-verify-service/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Smstunnel Io Context](https://apis.io/jsonld/smstunnel-io/smstunnel-io-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [SMSTunnel API Rules](https://apis.io/rules/smstunnel-io/smstunnel-io-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [SMSTunnel Authentication](https://apis.io/security/smstunnel-io/smstunnel-io-authentication/)
- [SMSTunnel Domain Security](https://apis.io/security/smstunnel-io/smstunnel-io-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [SMSTunnel Plans Pricing](https://apis.io/plans/smstunnel-io/smstunnel-io-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://smstunnel.io/)
- [Documentation](https://smstunnel.io/api-reference/)
- [Pricing](https://smstunnel.io/pricing/)
- [Blog](https://smstunnel.io/blog/)
- [Terms of service](https://smstunnel.io/terms/)
- [Privacy policy](https://smstunnel.io/privacy/)

## API Evangelist rating

**Kin Score 51.2** — developing · rubric 0.28.0 · scored 2026-11-22

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 63.1 |
| Contract governance | 79.1 |
| Operational transparency | 7.1 |
| Developer ergonomics | 46.9 |
| Access clarity | 48.5 |

**Agent readiness 55.4** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 15.8** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/smstunnel-io/](https://apis.io/providers/smstunnel-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SMSTunnel: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/smstunnel-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
