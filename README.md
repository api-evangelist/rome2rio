# Rome2Rio (rome2rio)

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
