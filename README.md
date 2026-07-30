# Landis

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
