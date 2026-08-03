# B612

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

B612 is a consumer selfie and beauty camera application for iOS and Android, published globally by SNOW
Corporation and operated in mainland China as B612咔叽 (B612 Kaji) by Yiruike Information Technology
(Beijing) Co., Ltd. The app combines a real-time beauty camera, AR stickers and scene effects,
user-created and creator-published filters, and photo and video editing tools, and has been distributed
through the Apple App Store and Google Play since 2014.

Backed by: hongshan

## API surface

B612 is a mobile end-user product rather than an API provider. As of the 2026-07-20 enrichment pass it
publishes no developer portal, no API documentation or reference, no SDKs, no CLI, no webhooks, and no
machine-readable API artifacts. No `/.well-known/` discovery documents are served on any B612 host.

## Artifacts in this repo

| Artifact | Path | Method |
|---|---|---|
| Domain security posture | `security/b612-domain-security.yml` | probed |
| Well-known discovery probe | `well-known/b612-well-known.yml` | searched (no documents found) |
| llms.txt | `llms/b612-llms.txt` | generated |
