![YeandAmen — Security research · Web3 · AI engineering](assets/yeandamen-banner.svg)

I’m Alfredrick, also known as **YeandAmen**, founder of Fyield. I build software and research security in AI systems and smart contracts.

[HackenProof](https://hackenproof.com/hackers/YeandAmen) · [X](https://x.com/yeandamen) · [Telegram](https://t.me/yeandamen) · [GitHub](https://github.com/YeandAmen)

## Things I build

Here’s what I’ve been building.

| Project | What it does |
| :--- | :--- |
| **Fyield** | We visit farms and keep verified records of production, costs, sales and repayment. The aim is to give lenders a clearer picture of a farmer’s business. We’re preparing to fund our pilot farmers ourselves and follow the results across seasons. |
| **Tinker** | I got tired of copying prompts, generating images and assembling YouTube videos by hand. Tinker brings the script, characters, scenes and export into one studio, with a Chrome extension to handle image generation through Google Flow. |
| **Reclaim** | Compares retainer contracts with invoices to find missing bills, underbilling and overdue balances. Each finding includes the clause and calculation behind it, so someone can check the evidence before acting. |
| **Idea Economy** | A place to publish original ideas, set usage terms and work with someone who wants to build them. I’m developing pricing around the views and likes an idea earns, with a 15-day window and a spending cap agreed by the buyer. |
| **Axil** | A flight-price tool for comparing fares, following routes and tracking price changes. Search, history and alerts are built; live flight-provider access is still being set up. |
| **Underdog** | Helps office teams see who has access to their systems and investigate suspicious activity. Access checks, alerts, evidence and reports sit in the same workspace. |
| **Radwave** | Collects jobs, scholarships, grants, fellowships and other opportunities from scattered sources. People can search them, keep a shortlist and track deadlines. It also includes the ingestion work from my earlier X Opportunity Scraper. |
| **Sinnogram** | Plans the order of stops around Abuja to cut down on backtracking. It compares driving routes, keeps an itinerary and lets you open each leg in your maps app. |
| **ALPHA DUKE** | A toolkit I use for smart contract research. It gathers contract code and context, screens for vulnerability patterns and prepares material for deeper analysis and exploit testing. |
| **SOC Playground** | A Splunk lab for practising attack detection using Windows and Kali telemetry. It includes attack simulations, detections and a console for following the traces. |

## Selected disclosures

| Project | Finding | Status | Read more |
| :--- | :--- | :--- | :--- |
| **Grok / xAI** | Python startup-hook persistence after execution of an uploaded archive | Fixed — researcher-reported | [Write-up](disclosures/grok-python-startup-persistence/README.md) |
| **MultiversX** | Unbounded Kad-DHT public-key record storage and memory growth | Fixed in communication library v1.4.1; included in node v2.1.7 | [Report](https://gist.github.com/YeandAmen/fd4431b5b22222dcb3f266dd7464f5a8) · [Fix](https://github.com/multiversx/mx-chain-communication-go/commit/6820c97770587a13f288bb3591028a95101e4b8e) · [PR](https://github.com/multiversx/mx-chain-communication-go/pull/76) |
| **Osmosis** | Unrecovered panic in MEV bundle processing | Acknowledged; fix private | [Report](https://gist.github.com/YeandAmen/0cbd7a9df6d573c0080854f53cbb3caf) |

### Grok · recorded demonstration

https://github.com/user-attachments/assets/50032307-699f-472e-ad1b-dfbbdacb85d8

<details>
<summary>MultiversX disclosure timeline</summary>

All times UTC. Report gist created **12 August 2026 at 16:17:47**; fix commit dated **14 August 2026 at 13:08:45**; associated PR merged into `main` **7 September 2026 at 07:44:22**. The fix disables value-record operations in both affected DHT discoverers.

</details>

## Findings portfolio

I also document smart contract vulnerabilities found through group research on protocols and DeFi systems.

| Total | Critical | High | Medium | Low | Info | Unclassified |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **47** | 6 | 15 | 12 | 11 | 2 | 1 |

<details>
<summary>Explore contests, audits, and disclosures</summary>

### Contests

| Contest Name                 | Critical | High | Medium | Low | Visibility     | Platform    |
|-----------------------------|----------|------|--------|-----|----------------|-------------|
| BELONG Smart Contract Audit | 1        | -    | 1      | -   | Public Contest | Immunefi    |
| Blackhole                   | -        | -    | -      | 1   | Public Contest | Code4rena   |
| Blockz Smart Contract Audit | -        | -    | -      | 3   | Public Contest | HackenProof |
| Index Fun Order Book        | -        | -    | 1      | -   | Public Contest | Sherlock    |
| DCA Smart Contract Audit    | -        | 1    | 1      | -   | Public Contest | Sherlock    |
| Alignerz 4                  | -        | 3    | 1      | -   | Public Contest | Dualguard   |

**Total Contest Findings: 10 (plus 1 Critical) — HackenProof excluded**

### First-Flight Audits

| Project Name     | High | Medium | Low | Platform     |
|-----------------|------|--------|-----|--------------|
| Weather_Witness | 3    | -      | -   | First-Flight |

**Total First-Flight Findings: 3**

### Private Audits

| Project Name  | Critical | High | Medium | Low | Info | Visibility   |
|---------------|----------|------|--------|-----|------|--------------|
| ODDSHOT V1    | -        | 2    | 2      | 2   | 2    | Public Audit |
| PowerProtocol | 2        | 2    | 4      | 2   | -    | Public Audit |

**Total Private Audit Findings: 18**

### Vulnerability Disclosure

| Platform     | Findings | Visibility |
|-------------|----------|------------|
| HackenProof | 11       | Hidden     |

Profile: https://hackenproof.com/hackers/YeandAmen


Private audit details are summarized to respect confidentiality.

</details>
