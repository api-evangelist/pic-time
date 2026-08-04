# Pic-Time (pic-time)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Pic-Time is an online gallery, proofing, and print-sales delivery platform for professional photographers - client galleries, slideshows, an integrated print store, and studio-management integrations. **Pic-Time does not publish a public developer API, API reference, or OpenAPI specification.** Automation is limited to a Zapier integration (three triggers - New Gallery Visitor, New Order Placed, Main Client Gallery Invite Sent - and one action, Create New Gallery) plus private, bilaterally-arranged partner integrations (HoneyBook, Studio Ninja, Light Blue, StyleCloud, the Pic-Time Connect WordPress plugin) that are not documented for third-party developers. No API keys, endpoints, or SDKs are published for general developer use.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pic-time/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pic-time/refs/heads/main/apis.yml)

## Tags

- Photography
- Client Galleries
- Photo Proofing
- Print Sales
- Photo Delivery
- No Public API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Public API Status

This is an honest stub, not a full API catalog entry. Research on the review date found:

- No API reference, developer portal, published base URL, or self-service API key mechanism on pic-time.com or help.pic-time.com.
- No SDKs or API clients under Pic-Time's GitHub organization (github.com/pic-time), which holds a single unrelated fork of the Exiv2 image-metadata library.
- A Zapier integration exposing three triggers (New Gallery Visitor, New Order Placed, Main Client Gallery Invite Sent) and one action (Create New Gallery) - documented by Zapier, not by Pic-Time.
- Private, bilaterally-arranged partner integrations (Light Blue, HoneyBook, Studio Ninja, StyleCloud, the Pic-Time Connect WordPress plugin). Light Blue's documentation, for example, describes an OAuth-style consent flow against Pic-Time, but Light Blue issues its own API key and the mechanics are not published for arbitrary third-party developers.

Because no real endpoints exist, `apis.yml` records `apis: []` rather than modeling fabricated ones, and no `openapi/`, `asyncapi/`, `rate-limits/`, or `finops/` directories were created. A `plans/` directory was added because Pic-Time's subscription pricing is real and publicly published.

See [`review.yml`](review.yml) for the full WebSocket-API review and sourcing.

## Plans

Pic-Time sells four subscription tiers (storage and feature-gated, not API-usage-metered):

- **Free** - $0/mo, 10GB photo / 1GB video storage, basic galleries and print store.
- **Beginner** - $8/mo ($7/mo yearly), 20GB photo / 5GB video, custom branding, studio-management integrations.
- **Professional** - $25/mo ($21/mo yearly), 100GB photo / 30GB video, premium galleries, slideshows, blogs, smart search.
- **Advanced** - $50/mo ($42/mo yearly), unlimited photo / 60GB video, multi-brand support, face/selfie search, lowest store commission.

Details: [plans/pic-time-plans-pricing.yml](plans/pic-time-plans-pricing.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/pic-time-ltd)
- [Website](https://www.pic-time.com/)
- [Plans](plans/pic-time-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
