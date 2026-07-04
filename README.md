<h1 align="center">James</h1>

<p align="center">
  <strong>Blockchain security · TRON ecosystem</strong><br>
  Product builder behind TRONSEC
</p>

<p align="center">
  <a href="https://tronsec.io/">tronsec.io</a>
  &nbsp;·&nbsp;
  <a href="https://t.me/tronsec_james">@tronsec_james</a>
</p>

---

### TRONSEC

<table>
<tr>
<td width="64" valign="top">
<img src="https://tronsec.io/assets/brand/logo-mark-readme.svg" width="56" alt="TRONSEC">
</td>
<td valign="top">

**[TRONSEC](https://tronsec.io/app/)** — on-chain security terminal for TRON.

Wallet risk, TRC-20 approvals, AML screening, contract audit, transaction decoding, URL reputation, vanity generation. Eight locales. No wallet connect.

Production: static client on Cloudflare Pages, upstream APIs behind a Worker — **credentials never ship to the browser**.

[`jamejohns/tronsec`](https://github.com/jamejohns/tronsec) · MIT · [`SECURITY.md`](https://github.com/jamejohns/tronsec/blob/main/SECURITY.md)

</td>
</tr>
</table>

---

### Security practice

| Domain | Focus |
|:-------|:------|
| **On-chain analysis** | TRON wallets, TRC-20 flows, allowance / drainer risk, address hygiene |
| **Smart contracts** | Privileged functions, proxy & upgrade patterns, TRON bytecode signals |
| **AML & fraud** | Transaction screening, counterparty exposure, concentration & behaviour heuristics |
| **Threat intelligence** | Phishing URLs, typosquatting, homoglyphs, multi-source reputation (VirusTotal) |
| **Pre-sign safety** | Calldata decoding, approval visibility, scam-pattern warnings before users sign |

**Architecture principles** — zero-custody UI, least-privilege read-only surface, server-side API keys on the edge, responsible disclosure, OSS export with automated secret scanning.

**Frameworks applied in product design** — OWASP secure-client practices · FATF-informed AML red-flag logic · defence-in-depth verification (TronGrid + TronScan + reputation feeds).

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
