![YeandAmen — Security research · Web3 · AI engineering](assets/yeandamen-banner.svg)

I'm **YeandAmen**. I research security across AI systems and Web3, build useful software, and share what I learn.

[HackenProof](https://hackenproof.com/hackers/YeandAmen) · [X](https://x.com/yeandamen) · [Telegram](https://t.me/yeandamen) · [GitHub](https://github.com/YeandAmen)

## Selected disclosures

| Project | Finding | Status | Read more |
| :--- | :--- | :--- | :--- |
| **Grok / xAI** | Python startup-hook persistence after execution of an uploaded archive | Fixed — researcher-reported | [Write-up](disclosures/grok-python-startup-persistence/README.md) |
| **MultiversX** | Unbounded Kad-DHT public-key record storage and memory growth | Fixed in communication library v1.4.1; included in node v2.1.7 | [Report](https://gist.github.com/YeandAmen/fd4431b5b22222dcb3f266dd7464f5a8) · [Fix](https://github.com/multiversx/mx-chain-communication-go/commit/6820c97770587a13f288bb3591028a95101e4b8e) · [PR](https://github.com/multiversx/mx-chain-communication-go/pull/76) |
| **Osmosis** | Unrecovered panic in MEV bundle processing | Acknowledged; fix private | [Report](https://gist.github.com/YeandAmen/0cbd7a9df6d573c0080854f53cbb3caf) |

<details>
<summary>MultiversX disclosure timeline</summary>

All times UTC. Report gist created **12 August 2026 at 16:17:47**; fix commit dated **14 August 2026 at 13:08:45**; associated PR merged into `main` **7 September 2026 at 07:44:22**. The fix disables value-record operations in both affected DHT discoverers.

</details>

## Findings portfolio

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

## Things I build

| Project | What it does |
| :--- | :--- |
| [Tinker](https://tinker-video.vercel.app) | A workspace for turning scripts into storyboards and videos. |
| [SOC Playground](https://github.com/YeandAmen/SOC-Playground) | A reproducible security lab with attack simulations and detection workflows. |
| [Audit Findings](https://github.com/YeandAmen/Audit-Findings-) | A collection of smart contract security findings. |
| [Radwave](https://github.com/YeandAmen/radwave) | A Go project for discovering opportunities from public sources. |
