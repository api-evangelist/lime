# Lime (lime)

Lime is a San Francisco–based shared electric vehicle company that operates e-scooters and e-bikes across more than 280 cities in 30+ countries. Riders unlock and pay for vehicles through the Lime mobile app; cities and transit agencies receive operational data via standardized public feeds. Lime publishes per-city public GBFS (General Bikeshare Feed Specification) 2.2 feeds covering system information, station information, station status, free (dockless) bike status, and vehicle types under the Lime Public GBFS Terms. Lime also publishes MDS Extensions on GitHub — an open-source aggregation layer that sits on top of the MDS Provider standard for sharing k-anonymized operational data with regulators. There is no public, commercially licensable rider/booking API; the rider-facing endpoints at web-production.lime.bike are private to the Lime app. Integrations with trip-planning surfaces (Google Maps, Uber, Moovit, Citymapper) and city permit dashboards are delivered through the GBFS and MDS feeds.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lime/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lime/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Shared Mobility
- Micromobility
- Electric Scooters
- Electric Bikes
- E-Bikes
- E-Scooters
- Transportation
- Urban Mobility
- GBFS
- MDS
- Smart Cities
- Transit

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Lime GBFS Public Feed

Public GBFS 2.2 feed exposing the real-time location, vehicle type, battery level, and rental URLs for Lime's free-floating e-scooters and e-bikes per operating city. Each city system has its own auto-discovery endpoint at /api/partners/v2/gbfs/{city}/gbfs.json, which lists the sub-feeds — system_information, station_information, station_status, free_bike_status, and vehicle_types. Use is governed by the Lime Public GBFS Terms. 46+ city systems are registered in the MobilityData GBFS index, including Paris, London, Berlin, Hamburg, Rome, Madrid, Vienna, Tel Aviv, Calgary, Ottawa, Vancouver, Atlanta, Arlington, and others.

- **Human URL:** [https://www.li.me/legal/public-gbfs-terms](https://www.li.me/legal/public-gbfs-terms)

#### Tags

- GBFS
- Shared Mobility
- Micromobility
- Real Time

#### Properties

- [Documentation](https://www.li.me/legal/public-gbfs-terms)
- [Documentation](https://github.com/MobilityData/gbfs/blob/master/gbfs.md)
- [OpenAPI](openapi/lime-gbfs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lime-gbfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lime-gbfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Discovery](https://data.lime.bike/api/partners/v2/gbfs/paris/gbfs.json)

## Common Properties

- [Website](https://www.li.me)
- [About](https://www.li.me/about)
- [Newsroom](https://www.li.me/newsroom)
- [Careers](https://www.li.me/careers)
- [Contact](https://www.li.me/contact-us)
- [Support](https://help.li.me)
- [Terms of Service](https://www.li.me/legal/user-agreement)
- [Privacy Policy](https://www.li.me/legal/privacy-policy)
- [G B F S Terms](https://www.li.me/legal/public-gbfs-terms)
- [Sustainability](https://www.li.me/sustainability)
- [Safety](https://www.li.me/safety)
- [GitHub Organization](https://github.com/limebike)
- [Data Sharing](https://github.com/limebike/data-sharing)
- [LinkedIn](https://www.linkedin.com/company/limebike)
- [Twitter](https://twitter.com/limebike)
- [Instagram](https://www.instagram.com/li.me)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
