# Rome2Rio (rome2rio)

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

Rome2Rio is a multi-modal travel planning platform founded in Melbourne, Australia in 2011, and part of the Omio Group since 2019. It covers 240+ countries, 10 million+ locations, and 20,000+ transport operators, enabling door-to-door route discovery across flights, trains, buses, ferries, and driving. Developers can access route search, geocoding, and autocomplete capabilities through the Rome2Rio REST API, which returns JSON responses covering routes, segments, duration, and operator information for any two points worldwide.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rome2rio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rome2rio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Travel
- Multi-Modal
- Transportation
- Routes
- Transit
- Flights
- Trains
- Buses
- Ferries
- Navigation

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Rome2Rio Search API

The Rome2Rio Search API returns multi-modal door-to-door travel routes between any origin and destination worldwide. Given origin and destination as place names or coordinates, it returns a ranked list of routes covering flights, trains, buses, ferries, and driving, with segment details, durations, operators, and indicative pricing information. Responses are JSON over HTTP. The API covers 700+ airlines and 2 million surface routes.

- **Human URL:** [https://www.rome2rio.com/documentation/1-4/search/](https://www.rome2rio.com/documentation/1-4/search/)
- **Base URL:** `http://free.rome2rio.com/api/1.4`

#### Tags

- Travel
- Routes
- Multi-Modal
- Transportation
- Transit
- Flights
- Trains
- Buses
- Ferries

#### Properties

- [Documentation](https://www.rome2rio.com/documentation/1-4/search/)

### Rome2Rio Autocomplete API

The Rome2Rio Autocomplete API provides place-name suggestions as a user types, returning a ranked list of matching locations (cities, airports, train stations, addresses) that can be passed as origin or destination to the Search API. Responses are JSON and the endpoint is hosted on the same free.rome2rio.com base.

- **Human URL:** [https://www.rome2rio.com/documentation/1-4/autocomplete/](https://www.rome2rio.com/documentation/1-4/autocomplete/)
- **Base URL:** `http://free.rome2rio.com/api/1.4`

#### Tags

- Autocomplete
- Places
- Geocoding
- Travel

#### Properties

- [Documentation](https://www.rome2rio.com/documentation/1-4/autocomplete/)

### Rome2Rio Geocode API

The Rome2Rio Geocode API resolves a place-name or address string to a canonical Rome2Rio place record with geographic coordinates, place type, and country, enabling precise origin and destination inputs for the Search API. Responses are JSON.

- **Human URL:** [https://www.rome2rio.com/documentation/1-4/geocode/](https://www.rome2rio.com/documentation/1-4/geocode/)
- **Base URL:** `http://free.rome2rio.com/api/1.4`

#### Tags

- Geocoding
- Places
- Coordinates
- Travel

#### Properties

- [Documentation](https://www.rome2rio.com/documentation/1-4/geocode/)

## Common Properties

- [Website](https://www.rome2rio.com/)
- [About](https://www.rome2rio.com/about/)
- [Documentation](https://www.rome2rio.com/documentation/1-4/search/)
- [Blog](https://www.rome2rio.com/blog/)
- [Support](https://help.rome2rio.com/en/support/tickets/new)
- [HelpCenter](https://help.rome2rio.com/)
- [PrivacyPolicy](https://www.rome2rio.com/privacy/)
- [TermsOfService](https://www.rome2rio.com/about/terms/)
- [GitHub](https://github.com/rome2rio)
- [LinkedIn](https://www.linkedin.com/company/rome2rio)
- [Advertise](https://www.rome2rio.com/advertise/)
- [GetListed](https://www.rome2rio.com/get-listed/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
