<h1 align="center">James</h1>

<p align="center">
  Independent security product engineer — TRON ecosystem<br>
  On-chain risk analysis · financial crime signals · secure client architecture
</p>

<p align="center">
  <a href="https://tronsec.io/">tronsec.io</a>
  &nbsp;·&nbsp;
  <a href="https://t.me/tronsec_james">@tronsec_james</a>
</p>

---

## Primary work — TRONSEC

<table>
<tr>
<td width="64" valign="top">
<img src="https://tronsec.io/assets/brand/logo-mark-readme.svg" width="56" alt="TRONSEC">
</td>
<td valign="top">

**[TRONSEC](https://tronsec.io/app/)** is a read-only security terminal for TRON Mainnet.

It gives users a structured risk picture **before** they connect a wallet or sign a transaction: wallet intelligence, TRC-20 approval exposure, AML-style screening, contract review, calldata decoding, URL reputation, and local vanity generation. Eight locales. No accounts. No custody.

Production runs as a static client on Cloudflare Pages; third-party APIs are reached through an edge Worker. **Credentials stay server-side** — the browser bundle contains no API keys.

Application source: [`jamejohns/tronsec`](https://github.com/jamejohns/tronsec) (MIT) · [Security policy](https://github.com/jamejohns/tronsec/blob/main/SECURITY.md) · [Architecture](https://github.com/jamejohns/tronsec/blob/main/ARCHITECTURE.md)

</td>
</tr>
</table>

---

## Expertise

### On-chain wallet intelligence
End-to-end address profiling on TRON: portfolio and stablecoin exposure, stake and resource posture, security flags, and activity reconstruction when native TRX traffic alone is insufficient. Risk scoring synthesises multiple public signals into actionable tiers rather than raw ledger dumps.

### Allowance governance & drainer mitigation
Systematic discovery of active TRC-20 approvals; classification of unlimited grants and anomalous spenders; reconciliation across independent indexers. Output is prioritised for the approvals that materially change loss exposure if exercised.

### AML & illicit-finance analytics
Heuristic screening over bounded transaction windows: counterparty concentration, flow symmetry, velocity anomalies, and peer-network context. Designed to accelerate manual review and investigation — explicit disclaimers, not a substitute for licensed compliance adjudication.

### Smart-contract risk assessment
Interface-driven review of privileged operations, ownership models, pause/blacklist/mint surfaces, and proxy or upgrade paths. Emphasis on pre-interaction context for tokens and DeFi contracts on TRON.

### Transaction forensics & pre-sign review
Decoding of TRON transactions into human-readable transfers, approvals, and contract calls; fee and resource accounting; pattern matching for common scam and drainer behaviours at the moment of user decision.

### Web & social-engineering defence
Reputation and structural analysis of domains and URLs: multi-engine verdicts, typosquat and homoglyph detection, young-domain heuristics, and TRON-specific phishing motifs — triage before wallet connection.

### Security architecture & delivery
Non-custodial product boundaries; read-only client with no signing path; edge-proxied secrets; CORS and rate limiting at the Worker; split between readable OSS export and hardened production artefacts; CI secret scanning on the public tree.

---

## Practice standards

Work is structured around **defence in depth**, **zero trust in the browser**, and **corroboration across data sources** where chain indices disagree. Client surfaces follow **OWASP** hardening principles; on-chain screening applies **FATF-informed red-flag logic** to public ledger data only. Heuristic outputs are labelled; conservative defaults are preferred over silent automation.

---

<p align="center">
  <sub>
    <a href="https://tronsec.io/app/"><b>Open TRONSEC</b></a>
    &nbsp;·&nbsp;
    <a href="https://github.com/jamejohns/tronsec">Source</a>
    &nbsp;·&nbsp;
    <a href="https://t.me/tronsec_chat">Community</a>
  </sub>
</p>
