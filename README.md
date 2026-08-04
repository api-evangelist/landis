# Landis

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

Landis Technologies Inc. is a rent-to-own homeownership company that helps renters become homeowners. A client applies for free, Landis underwrites them and issues an approved home budget, the client shops for a home with a real estate agent, and Landis buys that home all cash and rents it back to them while a dedicated Homeownership Coach works a tailored mortgage-readiness plan covering credit score, debt-to-income ratio, and down-payment savings. When the client is mortgage-eligible they buy the home back.

Landis operates in 8 states and runs two web portals — **Path** for clients (`path.landis.com`) and **Ally** for real estate agents (`ally.landis.com`) — plus referral programs for agents, lenders, and homebuilders.

Backed by: GV, Sequoia, Roc Nation — https://www.landis.com/

## API surface

Landis publishes **no public developer API, SDK, developer portal, or API documentation**. `developer.landis.com` and `api.landis.com` do not resolve; `docs.landis.com` redirects to an inactive placeholder. The portals are single-page apps over private backends. This repo therefore carries identity, compliance, and security artifacts only.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/landis-llms.txt` | searched (verbatim, AIOSEO-generated) |
| Trust center / compliance | `security/landis-trust-center.yml` | searched — SOC 2 Type 2 |
| Vulnerability disclosure | `security/landis-vulnerability-disclosure.yml` | searched — `security@landis.com` |
| Domain security | `security/landis-domain-security.yml` | probed |
| Well-known probe | `well-known/landis-well-known.yml` | searched — no documents published |
