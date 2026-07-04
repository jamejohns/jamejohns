<h1 align="center">James</h1>

<p align="center">
  Security product engineer · TRON ecosystem<br>
  On-chain risk · financial crime signals · secure client architecture
</p>

<p align="center">
  <a href="https://tronsec.io/">tronsec.io</a>
  &nbsp;·&nbsp;
  <a href="https://t.me/tronsec_james">@tronsec_james</a>
</p>

---

## Background

**7+ years** across application security, payment-fraud operations, and blockchain incident work — mostly on problems where users lose funds *before* anyone files a ticket: unlimited TRC-20 approvals, drainer dApps, blind-signed transactions, and stablecoin flows into high-risk corridors.

Earlier focus: high-velocity payment abuse, account takeover and mule networks, domain/phishing takedown workflows, and manual on-chain tracing when exchanges or victims needed a fast picture of exposure. That work shaped how I design products — **verdict first, evidence second**, conservative defaults, no custody.

**2025 — present** · Founder & lead engineer of **[TRONSEC](https://tronsec.io/app/)** — read-only security terminal for TRON Mainnet (architecture, heuristics, edge proxy, i18n, OSS).

---

## Primary work — TRONSEC

<table>
<tr>
<td width="64" valign="top">
<img src="https://tronsec.io/assets/brand/logo-mark-readme.svg" width="56" alt="TRONSEC">
</td>
<td valign="top">

End-to-end platform for pre-transaction risk: wallet intelligence, TRC-20 approval monitoring, AML-style screening, contract review, calldata decoding, URL reputation, vanity generation, live network context.

**Shipped:** 9 security modules · 8 locales · PWA · production on Cloudflare Pages + Worker · MIT [open-source app](https://github.com/jamejohns/tronsec)

**Model:** static client, **API credentials server-side only**, published [security](https://github.com/jamejohns/tronsec/blob/main/SECURITY.md) & [architecture](https://github.com/jamejohns/tronsec/blob/main/ARCHITECTURE.md) docs, CI secret scanning on public export.

</td>
</tr>
</table>

---

## Expertise

| Area | Depth |
|:-----|:------|
| **Wallet intelligence** | TRON address profiling — portfolio, TRC-20 exposure, resources, flags, activity when TRX-native history is thin; composite risk tiers |
| **Allowance & drainer risk** | Active approval discovery, unlimited-grant detection, spender prioritisation; cross-index reconciliation (TronGrid / TronScan) |
| **AML & illicit finance** | Bounded-window screening — concentration, velocity, peer graphs; investigation-grade exports with explicit non-compliance disclaimers |
| **Smart contracts** | Privileged ops, ownership, pause/mint/blacklist surfaces, proxy paths; pre-interaction context for tokens & DeFi on TRON |
| **Transaction forensics** | Calldata & event decoding, approval extraction, fee accounting, pre-sign warnings for known scam patterns |
| **Web & phishing** | Multi-engine URL reputation, typosquat/homoglyph checks, domain-age heuristics, TRON-themed lure detection |
| **Secure delivery** | Non-custodial boundaries, edge-proxied secrets, CORS/rate limits, OSS vs hardened prod split, responsible disclosure |

---

## How I work

**Defence in depth** · **zero trust in the browser** · **corroborate across independent indexers** when sources disagree.

Client hardening aligned with **OWASP** practice for browser-delivered apps. On-chain screening applies **FATF-informed red-flag logic** to public ledger data. Heuristic outputs are labelled; automation stops where a human decision belongs.

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
