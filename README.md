![LiveFuller, Oliver Žaigla. A black crystal mask with a silver streak, with the Prague skyline behind it.](assets/livefuller-obsidian.webp)

<p align="center">
  <a href="https://www.zaigla.com/en"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=900&color=8B949E&center=true&vCenter=true&width=720&lines=Building+Waygo+in+Prague.;AI+agents%2C+MCP+tooling+and+automation.;Web+apps+that+ship." alt="Building Waygo in Prague. AI agents, MCP tooling and automation. Web apps that ship." /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=LiveFuller&style=flat-square&color=grey&label=PROFILE+VIEWS" alt="Profile views" />
</p>

I’m Oliver, a developer based in Prague. I work on **Waygo**, a marketplace for local experiences, and **Leadora**, the company developing Nomo.

[Featured work](#user-content-selected-work) · [Open source](#user-content-open-source) · [Build notes](#user-content-behind-the-build) · [Client work](#user-content-client-work) · [Code & data](#user-content-code-and-data) · [Live on GitHub](#user-content-live-on-github) · [Contact](#user-content-contact)

<a name="selected-work"></a>

## ![Selected work](assets/section-work.webp)

| **Waygo** · Marketplace | **Leadora.cz** · Parent company |
| :--- | :--- |
| [![The Waygo mobile catalogue and hotel QR card over a black-and-white Prague skyline](assets/waygo-showcase-mono.webp)](https://www.waygo.cz/) | [![Leadora lettering beside two black crystal towers on a shared base](assets/leadora-showcase.webp)](https://www.leadora.cz/) |
| **What can we do in Prague today?** A hotel guest scans a QR code, browses local experiences and requests a booking from their phone. | Leadora brings together SiteSpot, its digital studio, and Nomo, an agent identity and control product in development. |
| [Explore Waygo ↗](https://www.waygo.cz/) | [Explore Leadora ↗](https://www.leadora.cz/) |

<a name="open-source"></a>

## Open source

Code I publish for anyone to read, run and reuse. More lands here as it ships.

<p align="center">
  <a href="https://github.com/LiveFuller/rainmaker"><img src="https://github-readme-stats.vercel.app/api/pin/?username=LiveFuller&repo=rainmaker&theme=transparent&hide_border=true&title_color=8B949E&text_color=8B949E&icon_color=8B949E" alt="rainmaker — the open-source AI salesman" /></a>
  <a href="https://github.com/LiveFuller/ideal-tribble"><img src="https://github-readme-stats.vercel.app/api/pin/?username=LiveFuller&repo=ideal-tribble&theme=transparent&hide_border=true&title_color=8B949E&text_color=8B949E&icon_color=8B949E" alt="ideal-tribble — dbt and ClickHouse starter" /></a>
</p>

### rainmaker · An outbound rep that never sleeps

Plug in your offer and a CSV of leads. rainmaker scores each lead against your ideal customer profile, writes a first touch in your voice, follows up on a cadence, classifies replies by intent and hands you the meetings. Approval mode by default — nothing sends without a human yes.

[Read the code ↗](https://github.com/LiveFuller/rainmaker) · [Try the one-minute demo ↗](https://github.com/LiveFuller/rainmaker#try-it-in-one-minute--no-keys-no-network)

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

<a name="live-on-github"></a>

## Live on GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LiveFuller/LiveFuller/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LiveFuller/LiveFuller/output/github-contribution-grid-snake.svg" />
    <img alt="A snake eating through the contribution grid" src="https://raw.githubusercontent.com/LiveFuller/LiveFuller/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LiveFuller&theme=transparent&hide_border=true&ring=8B949E&fire=8B949E&currStreakLabel=8B949E&sideLabels=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=6E7681" alt="GitHub contribution streak" />
</p>

### Recent activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

## Contact

Working on a booking flow, internal tool or data pipeline? Tell me where it starts and who needs the result.

[Email](mailto:oliver@zaigla.com) · [Portfolio ↗](https://www.zaigla.com/en) · [LinkedIn ↗](https://www.linkedin.com/in/zaigla/)
