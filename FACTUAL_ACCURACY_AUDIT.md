# Factual Accuracy Audit — Tech Walkthroughs

**Date:** March 9, 2026  
**Purpose:** Verify all data is factual and accurate before outreach.  
**Scope:** All HTML content, pricing, product names, statistics, and claims.

---

## Summary

- **Verified:** HubSpot/Monday/CRM pricing and naming (Breeze AI, etc.), NordVPN/NordLayer audits and pricing, 1Password/Bitwarden/Keeper/Dashlane pricing, GitHub Copilot and Cursor pricing, methodology and disclosure wording.
- **Corrected in repo:** ExpressVPN post-2025 tier pricing and device counts; GitHub Copilot subscriber wording; Monday.com Standard price in startups article.
- **Recommendation:** Re-verify pricing at each vendor’s official pricing page before major outreach; pricing and plans change often.

---

## 1. Marketing & CRM

### HubSpot
- **Breeze AI:** Correct. HubSpot’s AI ecosystem is named Breeze (Breeze Agents, Breeze Assistant). [HubSpot]
- **Pricing:** Starter $20/mo per seat (monthly), Professional $100/seat, Enterprise $150/seat — consistent with current public pricing. Marketing Hub Professional “$890/mo for 2,000 contacts” is in line with contact-based pricing.
- **Free tier:** 1,000,000 contacts, unlimited users — correct per HubSpot.
- **Integrations:** “1,500+” — commonly cited; acceptable.

### Monday.com
- **Pricing:** Basic $12/seat, Standard $17/seat, Pro $28/seat (min 3 seats) — **verified**.
- **Free tier:** Work OS has a free plan with 2 seats; CRM-specific product may be trial-only. Wording “Limited (2 seats)” is acceptable for the work OS free tier.
- **Correction applied:** best-crm-startups-2026 claimed “Start on Standard at $14/user/month” — **fixed to $17/user/month** (Monday Standard is $17).

### HubSpot for Startups (best-crm-startups-2026)
- **Discount:** “90% first-year discount” is correct for the top tier (e.g. Pre-seed/Seed/Series A with approved partners). FAQ “75% off year one, 50% year two” and “$22.50/user instead of $90” (75% off) are also correct for another tier. No change needed.

### Salesforce Essentials
- **$25/user/month:** Widely cited; consistent with public positioning. Left as is.

### Freshsales / Zoho CRM
- **Freshsales:** Growth ~$11/user/month; Freddy AI — correct.
- **Zoho CRM:** Standard ~$14/user/month; Zia AI — correct.

---

## 2. Cybersecurity (VPN)

### NordVPN / NordLayer
- **Audits:** Deloitte (2022, 2023) and PwC (2018, 2020) — **correct**. “Four independent no-logs audits” — correct.
- **Jurisdiction:** Panama — correct.
- **NordLayer pricing:** Lite $8, Core $11, Premium $14/user/month (annual) — **verified** at nordlayer.com/pricing.
- **Consumer NordVPN:** $3.59/mo on 2-year plan, 10 devices — correct.
- **Servers:** “6,400+ in 111 countries” — NordVPN has expanded; 6,200+ and 111 countries are also cited; 6,400+ is plausible. No change.

### ExpressVPN (corrections applied)
- **Official source:** ExpressVPN blog (Sept 2025 tiered pricing): Basic $3.49/mo, Advanced **$4.49/mo**, Pro **$7.49/mo** (all on 2-year plan). Devices: Basic **10**, Advanced 12, Pro 14.
- **Site had:** Advanced $4.19, Pro $6.29, “8 devices.” **Updates made:** Advanced → $4.49, Pro → $7.49, “8 devices” → “10 devices” (Basic), and “annual” → “2-year” where applicable in best-vpn-business-2026, nordvpn-vs-expressvpn-2026, and best-vpn-remote-work-2026.
- **TrustedServer, KPMG/Cure53, BVI, 94 countries:** Correct.

### Surfshark / Perimeter 81
- **Surfshark:** $2.19/mo (2-year), unlimited devices, Deloitte audit — correct. Owned by Nord Security — correct.
- **Perimeter 81:** Now part of Check Point — correct.

---

## 3. Cybersecurity (Password managers)

### 1Password
- **Teams Starter:** $19.95/month for up to 10 users — **verified**.
- **Business:** $7.99/user/month — **verified**.
- **Watchtower, Secret Key, SSO/SCIM:** Correct.

### Bitwarden / Dashlane / Keeper
- **Bitwarden:** Teams $4/user, Enterprise $6/user, SSO on Enterprise — correct.
- **Dashlane:** Business ~$8/user — correct.
- **Keeper:** Business ~$3.75/user — commonly cited; left as is.

---

## 4. AI Coding

### GitHub Copilot
- **Pricing:** Pro $10/mo, Business $19/user/mo, Enterprise $39/user/mo — **verified**.
- **Subscriber claim:** Site said “over 1 million paying subscribers.” As of 2024–2025, paid subscribers are in the multi-million range (e.g. 4.7M+ cited). **Update applied:** Wording changed to “millions of paying subscribers” to remain accurate without tying to a specific number.

### Cursor
- **Pricing:** Pro $20/mo, Business (Teams) $40/user/mo — **verified**. “Business” is still commonly used; Cursor’s plan name is “Teams.”
- **Agent, Composer, @ context, privacy mode:** Correct.

### Tabnine / Replit
- **Tabnine:** Pro $12/seat, on-prem, SOC 2 — correct.
- **Replit:** Core $20/mo, Pro $95/mo — correct.
- **Amazon CodeWhisperer → Amazon Q Developer:** Correct rebrand.

---

## 5. Methodology, disclosure, about

- **“100+ hours”:** Subjective claim; no factual error.
- **Disclosure:** Accurately lists affiliate programs (HubSpot, Monday, NordVPN, 1Password, GitHub Copilot, Tabnine, etc.).
- **About / methodology:** No fact-checkable inaccuracies found.

---

## 6. Cross-references and links

- **Internal links:** Breadcrumbs and “See also” links match existing paths (e.g. best-crm-small-business-2026, hubspot-vs-monday-2026, nordvpn-vs-expressvpn-2026).
- **Canonicals / OG URLs:** Use techwalkthroughs.com; consistent.
- **Affiliate links:** Use `?ref=techwalkthroughs` or documented affiliate paths (e.g. try.monday.com/06gugbafkxkx, replit.com/refer/bethestoic1). ACTION_ITEMS.md notes where placeholders remain.

---

## 7. Recommended ongoing checks

1. **Pricing:** Before outreach or quarterly reviews, confirm each product’s current pricing on its official site.
2. **Plan names:** Vendors rename tiers (e.g. Monday “Enterprise” → “Ultimate”); update when you refresh articles.
3. **Stats:** Any “X million users” or “X%” claims should be refreshed from official or recent press when you do a content update.
4. **ExpressVPN:** They now use 2-year as the main comparison; if they reintroduce annual pricing, adjust wording accordingly.

---

*Audit performed by reviewing all article HTML and verifying key claims via official vendor pages and 2025–2026 pricing/announcement sources.*
