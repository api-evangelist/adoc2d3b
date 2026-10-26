# Adoc (Viva Innovation)

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

Adoc is the corporate web presence of Viva Innovation Inc. (주식회사 비바이노베이션), a Seoul, South Korea health-technology company founded in January 2018 and based in Gangnam-gu, which operates the health-checkup and medical-records platform 착한의사 (Chakan Uisa / Kindoc). Consumers use the Kindoc mobile and web apps to pull scattered personal medical records into one place, run an AI symptom check against personal and Health Insurance Review and Assessment Service data, compare hospital examination packages and their costs, and book discounted health screenings; employers buy the same screenings as corporate checkup programs, and partner hospitals join through a hospital-affiliation program. For providers the company sells a medical cloud — Kindoc Care CMS and Kindoc Care PMS for checkup centres — alongside a medical AI line it splits into Preventive AI (test-item recommendation, plain-language result explanation, biomarker and biological-age analysis), Clinical AI (comprehensive findings generation, abnormal-finding triage, follow-up test recommendation) and Decision Support AI (disease-risk analysis from repeated checkup results, endoscopy anaesthesia-risk prediction, real-time endoscopic polyp detection), plus a generative "주치의 AI" assistant published as Dr.Patch at chat.kindoc.ai and a research arm, Kindoc Labs. Everything the company ships is a consumer app, a partner landing page or hospital-side software: as of this profile it publishes no developer portal, no API reference, no SDK and no machine-readable API contract on any host it operates.

## Links

- [Website](https://www.adoc.co.kr/)
- [About](https://www.adoc.co.kr/1738bf80b49d8013b8d6fc1ebe7b5c6c)
- [Solutions](https://www.adoc.co.kr/solution)
- [Products](https://www.adoc.co.kr/kindoccare-cms)
- [Careers](https://www.adoc.co.kr/recruit)
- [Blog](https://post.naver.com/my.naver?memberNo=45438006)
- [Support](https://n481v.channel.io/support-bots/71968)
- [TermsOfService](https://team.adoc.co.kr/services)
- [PrivacyPolicy](https://team.adoc.co.kr/privacy-policy)
- [LinkedIn](https://kr.linkedin.com/company/%EC%A3%BC-%EB%B9%84%EB%B0%94%EC%9D%B4%EB%85%B8%EB%B2%A0%EC%9D%B4%EC%85%98-vivainnovation)
- [SecondaryMarket](https://equityzen.com/company/adoc2d3b/)
- [Compliance](https://kindoclabs.adoc.co.kr/)

## What this profile contains

This company publishes no API. The artifacts in this repository record that measurement rather than
an API surface: `well-known/` holds the full `/.well-known/` probe across six company hosts (every
path a 404, plus the catch-all and negative-control findings), `conformance/` captures the
certifications the company does publish (ISO 13485, ISO 27001, ISO 27701, GS Grade 1, K-GMP, MFDS
device classes I/II/III) alongside the recorded absence of each API standard, `packages/`,
`plans/`, `rate-limits/` and `mcp/` record honest zeros with the searches behind them, and
`security/` holds the live TLS/DNS probe. See `x-coverage` in `apis.yml` for why this profile is
thin.
