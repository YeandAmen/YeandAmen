<p align="center">
  <img src="assets/profile-banner.svg" alt="YeandAmen — software and security research" width="100%" />
</p>

I’m **Alfredrick**, also known as **YeandAmen**. I build software and research security in code and AI systems.

[HackenProof](https://hackenproof.com/hackers/YeandAmen) &nbsp; / &nbsp; [X](https://x.com/yeandamen) &nbsp; / &nbsp; [Telegram](https://t.me/yeandamen)

<br />

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<h3>Tinker</h3>
<p><sub>VIDEO PRODUCTION</sub></p>
<p>I got tired of copying prompts and assembling YouTube videos by hand. Tinker puts scripts, characters, scenes and video exports in one studio. A Chrome extension handles image generation through Google Flow.</p>
</td>
<td width="50%" valign="top">
<h3>Reclaim</h3>
<p><sub>CONTRACTS &amp; BILLING</sub></p>
<p>Compares retainer contracts with invoices to find missing bills, underbilling and overdue balances. Each finding shows the clause and calculation behind it, so someone can check the evidence before acting.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>Idea Economy</h3>
<p><sub>IDEAS &amp; LICENSING</sub></p>
<p>A place to publish original ideas, set usage terms and find someone to build them. I’m developing pricing around views and likes, measured over 15 days with a buyer-agreed spending cap.</p>
</td>
<td width="50%" valign="top">
<h3>Axil</h3>
<p><sub>FLIGHT PRICES</sub></p>
<p>Compares fares, follows routes and tracks price changes. Search, price history and alerts are built. Live flight-provider access is still being set up.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>Underdog</h3>
<p><sub>ACCESS &amp; THREAT INVESTIGATION</sub></p>
<p>Helps office teams see who has access to their systems and investigate suspicious activity. Access checks, alerts, evidence and reports sit in the same workspace.</p>
</td>
<td width="50%" valign="top">
<h3>Radwave</h3>
<p><sub>OPPORTUNITY SEARCH</sub></p>
<p>Collects jobs, scholarships, grants and fellowships from scattered sources. Search them, keep a shortlist and track deadlines. It includes the ingestion work from my earlier X Opportunity Scraper.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>Sinnogram</h3>
<p><sub>ROUTE PLANNING</sub></p>
<p>Plans the order of stops around Abuja to cut down on backtracking. Compare driving routes, keep an itinerary and open each leg in your maps app.</p>
</td>
<td width="50%" valign="top">
<h3>SOC Playground</h3>
<p><sub>SECURITY LAB</sub></p>
<p>A Splunk lab for practising attack detection with Windows and Kali telemetry. It includes attack simulations, detections and a console for following the traces.</p>
</td>
</tr>
</table>

<br />

## Security research

Selected disclosures from my work on AI systems and blockchain infrastructure.

### Grok / xAI

Python startup-hook persistence after execution of an uploaded archive. **Fixed — researcher-reported.**

[Read the write-up](disclosures/grok-python-startup-persistence/README.md) · [Recorded demonstration](https://github.com/user-attachments/assets/50032307-699f-472e-ad1b-dfbbdacb85d8)

### MultiversX

Unbounded Kad-DHT public-key record storage and memory growth. **Fixed in communication library v1.4.1; included in node v2.1.7.**

[Report](https://gist.github.com/YeandAmen/fd4431b5b22222dcb3f266dd7464f5a8) · [Fix](https://github.com/multiversx/mx-chain-communication-go/commit/6820c97770587a13f288bb3591028a95101e4b8e) · [Pull request](https://github.com/multiversx/mx-chain-communication-go/pull/76)

<details>
<summary>Disclosure timeline</summary>

All times UTC. Report gist created **12 August 2026 at 16:17:47**; fix commit dated **14 August 2026 at 13:08:45**; associated PR merged into `main` **7 September 2026 at 07:44:22**. The fix disables value-record operations in both affected DHT discoverers.

</details>

### Osmosis

Unrecovered panic in MEV bundle processing. **Acknowledged; fix private.**

[Read the report](https://gist.github.com/YeandAmen/0cbd7a9df6d573c0080854f53cbb3caf)

<br />

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
