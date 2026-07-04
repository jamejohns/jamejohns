<h1 align="center">James</h1>

<p align="center">
  <strong>Security tools for TRON</strong><br>
  Read-only products · static client · credentials on the edge
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

Wallet risk, TRC-20 approvals, AML heuristics, contract signals, transaction decoding, URL reputation, vanity generation. Eight locales. No wallet connect.

Production is a static app on Cloudflare Pages; upstream APIs sit behind a Worker. Keys never ship to the browser.

[`jamejohns/tronsec`](https://github.com/jamejohns/tronsec) · MIT

</td>
</tr>
</table>

---

### How I build it

| Layer | What |
|:------|:-----|
| **Product** | Single-page security workbench — scan first, explain after, no account wall |
| **Client** | Static HTML/JS, i18n, PWA shell; heavy work (vanity search) in Web Workers |
| **Edge** | Cloudflare Worker proxy — TronGrid, TronScan, VirusTotal, rate limits, CORS |
| **Deploy** | Pages + `_redirects`, locale trees, obfuscated prod / readable OSS export |
| **Chain** | TRON mainnet — TRC-20, approvals, address & contract semantics |

---

### Contact

| | |
|:--|:--|
| **Personal** | [@tronsec_james](https://t.me/tronsec_james) |
| **Community** | [t.me/tronsec_chat](https://t.me/tronsec_chat) |
| **Product** | [tronsec.io/app](https://tronsec.io/app/) |

---

<p align="center">
  <sub>Building in public where it makes sense — core app is open source under MIT.</sub>
</p>
