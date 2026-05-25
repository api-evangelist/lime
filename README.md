# lime

Lime — shared electric vehicles (e-scooters and e-bikes) across 280+ cities globally. Publishes public GBFS 2.2 feeds per city under the Lime Public GBFS Terms.

## APIs

- **Lime GBFS Public Feed** — `https://data.lime.bike/api/partners/v2/gbfs/{city}/gbfs.json`
  - System Information, Station Information, Station Status, Free Bike Status, Vehicle Types
  - GBFS 2.2 (some cities exposed via partner aggregators at GBFS 2.3 / 3.0)
  - 46+ city systems registered in the MobilityData GBFS index

## Artifacts

- `apis.yml` — provider profile and API inventory
- `openapi/lime-gbfs-openapi.yml` — OpenAPI 3.1 description of the public GBFS feed endpoints

## Links

- Website: https://www.li.me
- GBFS Terms: https://www.li.me/legal/public-gbfs-terms
- GitHub: https://github.com/limebike
- MDS Extensions (agency data sharing): https://github.com/limebike/data-sharing
