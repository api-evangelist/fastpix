# FastPix (fastpix)

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

FastPix is a developer-first video platform offering APIs for video on-demand (upload, ingest, encoding, playback), live streaming, simulcasting, secure and DRM playback, in-video AI (transcription, summaries, chapters, moderation), and video views analytics. A Mux-style, pay-per-minute video infrastructure with a single REST API at api.fastpix.io/v1 using Basic auth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fastpix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fastpix/refs/heads/main/apis.yml)

## Tags

- Video
- Streaming
- Live Streaming
- Video on Demand
- Encoding
- Playback
- Video Analytics

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### FastPix On-Demand API

Upload or import video files, then encode, store, and manage on-demand media assets, tracks, MP4 downloads, source access, and clips.

- **Human URL:** [https://docs.fastpix.io/reference](https://docs.fastpix.io/reference)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- Video on Demand
- Upload
- Encoding
- Media

#### Properties

- [Documentation](https://docs.fastpix.io/docs/get-started-in-5-minutes)
- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FastPix Live Streaming API

Create and manage live streams over RTMPS and SRT, control reconnect windows and stream state, and record live streams to on-demand assets with generated live clips.

- **Human URL:** [https://docs.fastpix.io/docs/get-started-with-live-streaming](https://docs.fastpix.io/docs/get-started-with-live-streaming)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- Live Streaming
- RTMP
- SRT
- Low Latency

#### Properties

- [Documentation](https://docs.fastpix.io/docs/get-started-with-live-streaming)
- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FastPix Simulcast API

Restream a single live stream to multiple third-party RTMP destinations such as YouTube, Twitch, and Facebook simultaneously.

- **Human URL:** [https://docs.fastpix.io/reference](https://docs.fastpix.io/reference)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- Simulcast
- Restream
- RTMP

#### Properties

- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FastPix Playback & Signing Keys API

Manage playback IDs for media and live streams, and create RSA signing keys used to mint JWTs for tokenized, private, and DRM-protected playback.

- **Human URL:** [https://docs.fastpix.io/reference](https://docs.fastpix.io/reference)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- Playback
- Signing Keys
- JWT
- DRM
- Security

#### Properties

- [Documentation](https://docs.fastpix.io/docs/secure-playback-with-signed-urls)
- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FastPix In-Video AI API

Enrich media with AI - auto-generated subtitles and translations, summaries, chapters, named-entity extraction, and content moderation - via flags on the media update endpoint and subtitle generation.

- **Human URL:** [https://docs.fastpix.io/docs/overview-of-in-video-ai-features](https://docs.fastpix.io/docs/overview-of-in-video-ai-features)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- AI
- Transcription
- Summaries
- Chapters
- Moderation

#### Properties

- [Documentation](https://docs.fastpix.io/docs/overview-of-in-video-ai-features)
- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FastPix Data & Views API

Query video views, quality-of-experience metrics, dimensions, playback errors, timeseries, and breakdowns for viewer engagement and delivery analytics.

- **Human URL:** [https://docs.fastpix.io/reference](https://docs.fastpix.io/reference)
- **Base URL:** `https://api.fastpix.io/v1`

#### Tags

- Video Analytics
- Views
- Metrics
- QoE

#### Properties

- [Documentation](https://docs.fastpix.io/docs/video-data-overview)
- [API Reference](https://docs.fastpix.io/reference)
- [OpenAPI](openapi/fastpix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fastpix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fastpix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/FastPix)
- [LinkedIn](https://www.linkedin.com/company/fastpix)
- [Website](https://www.fastpix.io/)
- [Documentation](https://docs.fastpix.io)
- [Plans](plans/fastpix-plans-pricing.yml)
- [Rate Limits](rate-limits/fastpix-rate-limits.yml)
- [Fin Ops](finops/fastpix-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
