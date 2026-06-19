# 🛡️ CIS Controls v8.1 — Interactive Gap Analysis Tool

> A free, browser-based security assessment tool covering all 18 CIS Controls and 153 safeguards.  
> No installation. No login. No data leaves your device.

**🔗 [Try the live tool → mrpranto.github.io/cis-gap-analysis](https://mizanpranto.github.io/cis-gap-analysis/)**

---

## What is this?

This tool lets you run a full **CIS Controls v8.1 gap assessment** directly in your browser. Built for cybersecurity consultants, IT managers, and compliance teams who need to understand their organization's security posture quickly and clearly.

It covers every safeguard from the official CIS Controls v8.1 framework, organized across 18 control domains — from asset inventory and access management to penetration testing and incident response.

---

## Features

| Feature | Description |
|---|---|
| **153 safeguards** | All CIS Controls v8.1 safeguards built in — nothing to configure |
| **Implementation Groups** | Filter to IG1 (56), IG2 (130), or IG3 (153) based on org size and risk |
| **Security function filter** | Govern · Identify · Protect · Detect · Respond · Recover |
| **Live scoring** | Per-control and overall compliance score updates in real time |
| **Notes per safeguard** | Add assessor notes to each item |
| **Detail Report** | Professional report with executive summary, gap findings, and 90-day roadmap |
| **Print / PDF export** | Save the report as a PDF directly from the browser |
| **CSV export** | Download full results as a spreadsheet |
| **Zero dependencies** | Single HTML file — works offline, no npm, no build step |

---

## How to use

### Option 1 — Live link
Open **[mrpranto.github.io/cis-gap-analysis](https://mizanpranto.github.io/cis-gap-analysis/)** in any browser.

### Option 2 — Download and run locally
1. Download [`index.html`](./index.html)
2. Open it in Chrome, Firefox, Safari, or Edge
3. No internet required

### Option 3 — Send to a client
Email `index.html` to your client. They open it locally — no account, no installation, no data sent anywhere.

---

## Running an assessment (step by step)

1. **Enter the organization name** in the Client field at the top of the sidebar
2. **Select your Implementation Group:**
   - **IG1** — Small or low-risk organizations (56 safeguards — start here)
   - **IG2** — Medium complexity (130 safeguards)
   - **IG3** — High-risk or mature enterprises (all 153 safeguards)
3. **Click a control** to expand it and review its safeguards
4. **Set the status** for each safeguard:
   - `In place` — fully implemented and documented
   - `Partial` — some implementation exists but incomplete
   - `Gap` — not implemented
   - `N/A` — not applicable
5. **Add notes** to any safeguard for context or follow-up actions
6. **Watch the score** update live — per control and overall
7. **Click "📄 Detail Report"** to generate a full professional report
8. **Print or save as PDF** to deliver to your client

---

## Understanding the score

```
Score = (In Place + Partial × 0.5) ÷ (Total − N/A) × 100
```

| Score | Risk Level |
|---|---|
| 80–100% | 🟢 Low |
| 60–79% | 🟡 Moderate |
| 40–59% | 🟠 Elevated |
| 0–39% | 🔴 High |

---

## The Detail Report includes

- **Executive Summary** — board-ready paragraph summarizing posture and risk level
- **Control-by-Control Breakdown** — all 18 controls with scores and progress bars
- **Gap Findings** — prioritized list of unimplemented safeguards (Critical / High / Medium)
- **Partial Implementations** — items that need completion
- **90-Day Remediation Roadmap** — top gaps mapped to 0–30 / 30–60 / 60–90 day phases
- **Recommended Next Steps** — standard consulting action items

---

## Tech stack

- Pure **HTML + CSS + JavaScript** — single file, zero dependencies
- No frameworks, no build tools, no CDN
- Works fully **offline** after first load
- All 153 safeguards embedded directly from the official CIS Controls v8.1 dataset

---

## Source data

Safeguards sourced from the **CIS Controls Version 8.1** spreadsheet (June 2024). IG assignments, asset types, and security function mappings match the official CIS documentation.

> CIS Controls® is a registered trademark of the Center for Internet Security, Inc.  
> This tool references the CIS Controls framework for assessment purposes in accordance with the CIS license (CC BY-NC-ND 4.0).

---

## Built by

**Mizanur Rahman Pranto**  
Cybersecurity Consultant · CIS Controls Specialist

📧 [mprantox41@gmail.com](mailto:mprantox41@gmail.com)  
💼 [linkedin.com/in/mrpranto1997](https://www.linkedin.com/in/mrpranto1997/)

> Available for freelance gap assessments, remediation roadmaps, and vCISO engagements.

---

## License

MIT — free to use, fork, and adapt.

---

*If this tool helped you, consider giving it a ⭐*
