# Privacy Policy — Victoria Girls Currency Converter

**Last updated: May 2026**

---

## Overview

Victoria Girls Currency Converter is a free Chrome extension that helps users instantly convert foreign currency prices (KRW, JPY, USD, TWD) to Hong Kong Dollar (HKD) while browsing any website.

---

## Data Collection

**We do not collect any personal data.**

Victoria Girls Currency Converter does not:

- Collect, store, or transmit any personal information
- Track your browsing history or the websites you visit
- Record which prices or currencies you convert
- Share any information with third parties
- Use cookies or any tracking technologies
- Require account registration or login

---

## Permissions Explained

The extension requests the following Chrome permissions solely to provide its core functionality:

| Permission | Why it is needed |
|---|---|
| `storage` | Saves live exchange rates locally on your device for up to 1 hour to reduce unnecessary network requests |
| `activeTab` | Reads the visible text on the current page to detect currency amounts |
| `scripting` | Injects the price highlight style and HKD conversion tooltip into the page |
| `host_permissions` | Allows the extension to work on any website you visit, since currency prices can appear on any shopping site |

All data stays **on your device only**. Nothing is sent to any external server owned by this extension.

---

## Exchange Rate API

To display live exchange rates, the extension fetches publicly available rate data from:

- [cdn.jsdelivr.net](https://cdn.jsdelivr.net) — a free public CDN
- Your own Cloudflare Worker (if configured) — a proxy you control entirely

These requests contain no personal information — they are simple public API calls identical to visiting a webpage.

---

## Changes to This Policy

If this privacy policy changes, the updated version will be posted at this URL with a revised date at the top.

---

## Contact

If you have any questions about this privacy policy, please open an issue on the GitHub repository or contact us at:

**[your-email@example.com]**

---

*Victoria Girls Currency Converter is a free, open-source Chrome extension built for Hong Kong K-pop fans and online shoppers.*
