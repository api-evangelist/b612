# B612

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
