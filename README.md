![LiveFuller, Oliver Žaigla. A black crystal mask with a silver streak, with the Prague skyline behind it.](assets/livefuller-obsidian.webp)

I’m Oliver, a developer based in Prague. I work on **Waygo**, a marketplace for local experiences, and **Leadora**, the company developing Nomo.

[Featured work](#user-content-selected-work) · [Build notes](#user-content-behind-the-build) · [Client work](#user-content-client-work) · [Code & data](#user-content-code-and-data) · [Contact](#user-content-contact)

<a name="selected-work"></a>

## ![Selected work](assets/section-work.webp)

| **Waygo** · Marketplace | **Leadora.cz** · Parent company |
| :--- | :--- |
| [![A Waygo QR card in front of the mobile catalogue, with Prague in the background](assets/waygo-showcase.webp)](https://www.waygo.cz/) | [![Leadora lettering beside two black crystal towers on a shared base](assets/leadora-showcase.webp)](https://www.leadora.cz/) |
| **What can we do in Prague today?** A hotel guest scans a QR code, browses local experiences and requests a booking from their phone. | Leadora brings together SiteSpot, its digital studio, and Nomo, an agent identity and control product in development. |
| [Explore Waygo ↗](https://www.waygo.cz/) | [Explore Leadora ↗](https://www.leadora.cz/) |

<a name="behind-the-build"></a>

## ![Behind the build](assets/section-build.webp)

### Waygo · The handoff starts at reception

A guest asks what to do in Prague. The front desk shows them a QR code that opens the catalogue on their phone. The guest requests a booking and receives a voucher after confirmation.

[See the front-desk flow ↗](https://www.waygo.cz/partner/reception) · [Browse experiences ↗](https://www.waygo.cz/discover)

### Leadora · Building Nomo

Leadora shares strategy and resources across its ventures. Its current focus is developing Nomo, an identity and control layer for teams whose AI agents use MCP tools.

[Leadora ↗](https://www.leadora.cz/) · [Explore Nomo ↗](https://nomo-web.vercel.app/)

<a name="client-work"></a>

## ![Client work](assets/section-client.webp)

### RT Likvidace · Turn a service search into a quote request

[![RT Likvidace’s Prague clearance service page with a request-a-quote button](assets/rt-likvidace-preview.webp)](https://rychlevyklizenipraha.cz/)

I built the public website for a Prague clearance company. It gives visitors a place to check what the team handles, see how pricing works and request a quote.

[See the site ↗](https://rychlevyklizenipraha.cz/) · [See pricing ↗](https://rychlevyklizenipraha.cz/cenik)

<a name="code-and-data"></a>

## ![Code and data](assets/section-code.webp)

### zaigla.com · An agent response you can check

Try the order-approval scenario in this interactive demo. It uses sample orders. Four pass the CRM check and two stay in review because the billing addresses don’t match. The response cites the ERP approval queue.

[Try the agent demo ↗](https://www.zaigla.com/en#demo)

### dbt + ClickHouse · A lookup table with schema checks

A public starter that exposes NYC taxi zones as a staging view and defines checks for missing or duplicate location IDs.

| Read the code | What it does |
| :--- | :--- |
| [Source definitions](https://github.com/LiveFuller/ideal-tribble/blob/main/models/staging/sources.yml) | Declares the raw taxi tables and zone lookup. |
| [Staging SQL](https://github.com/LiveFuller/ideal-tribble/blob/main/models/staging/stg_taxi_zones.sql) | Turns fields such as `LocationID` and `Zone` into `location_id` and `zone_name`. |
| [Schema checks](https://github.com/LiveFuller/ideal-tribble/blob/main/models/staging/schema.yml) | Defines the uniqueness and non-null checks on the zone ID. |

[Browse the starter ↗](https://github.com/LiveFuller/ideal-tribble)

## Contact

Working on a booking flow, internal tool or data pipeline? Tell me where it starts and who needs the result.

[Email](mailto:oliver@zaigla.com) · [Portfolio ↗](https://www.zaigla.com/en) · [LinkedIn ↗](https://www.linkedin.com/in/zaigla/)
