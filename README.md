# FastPix (fastpix)

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
