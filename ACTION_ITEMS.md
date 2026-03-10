# Tech Walkthroughs — Action Items

Use this list to get the site live and earning. Check off as you go.

---

## 1. Affiliate programs to sign up for

Sign up for these **in order of impact** (recurring $ and content already live). Use your **Tech Walkthroughs URL** and describe the site as a software comparison / review site.

| # | Program | Where to sign up | Commission (typical) | Use your link in |
|---|---------|-------------------|----------------------|------------------|
| 1 | **HubSpot** | [hubspot.com/partners/affiliates](https://www.hubspot.com/partners/affiliates) | 30% recurring up to 12 months | Best CRM article, Marketing hub |
| 2 | **Monday.com** | [monday.com/affiliate-program](https://monday.com/affiliate-program) (PartnerStack) | 10–20% tiered, up to 2 years | Best CRM article, Marketing hub |
| 3 | **NordVPN** | [nordvpn.com/affiliate](https://nordvpn.com/affiliate/) | 40%+ new, 30% recurring on renewals | Best VPN article, Cybersecurity hub |
| 4 | **1Password** | [1password.com/affiliate](https://1password.com/affiliate) (or via CJ if directed) | $2 per signup + 25% first year | Best VPN article (secondary CTA), future Password Manager article |
| 5 | **Tabnine** | [tabnine.com/partners/apply](https://tabnine.com/partners/apply) | Apply; partner/affiliate terms from them | Best AI Coding article, AI Coding hub |
| 6 | **GitHub Copilot** | Check [github.com/features/copilot](https://github.com/features/copilot/plans) or GitHub Partner Program / contact sales | Varies; no clear public affiliate program | Best AI Coding article (use referral link if/when you get one) |
| 7 | **Replit** | [replit.com/refer](https://replit.com/refer) — get your referral link from account (paid plan to earn) | $10 credits you + referred user when they pay; tiers at 10/100 referrals | Best AI Coding article, AI Coding hub |
| 8 | **ExpressVPN** | [expressvpn.com/affiliates](https://www.expressvpn.com/affiliates) | CPA ~$36 / $22 / $13 by plan (one-time) | NordVPN vs ExpressVPN article (secondary CTA) |

**Notes:**

- **HubSpot & Monday:** Get your tracking links and add them to the two CTAs in `marketing-crm/best-crm-small-business-2026/index.html`.
- **NordVPN & 1Password:** Add links to the two CTAs in `cybersecurity/best-vpn-business-2026/index.html`.
- **Tabnine:** Apply at the link above; once approved, add your link to `ai-coding/best-ai-coding-assistant-2026/index.html`. For **GitHub Copilot**, use an official referral/partner link if the program offers one; otherwise keep a “Try Copilot” CTA to the main Copilot signup page (no affiliate) until you have a link.
- **Replit:** Get your referral link from [replit.com/refer](https://replit.com/refer) (account settings; paid plan required to earn credits). Replace the "Try Replit" CTA in `ai-coding/best-ai-coding-assistant-2026/index.html` with your referral URL.
- **Cursor:** No referral/affiliate program. Replied with [Ambassadors](https://cursor.com/ambassadors) (community/events, no referral links). Keep existing CTA (cursor.com + ref) in `ai-coding/github-copilot-vs-cursor-2026/index.html`; replace with referral link only if Cursor launches one later.

**Status (applications in progress):**

- **HubSpot** — Declined — minimum 1,000 monthly visitors required. Keep CRM CTAs as placeholder; reapply when site reaches ~1k+ monthly visitors (check Search Console).
- **Monday.com** — Approved; referral link added. CTAs updated in `marketing-crm/best-crm-small-business-2026/index.html` and `marketing-crm/hubspot-vs-monday-2026/index.html` (try.monday.com/06gugbafkxkx).
- **NordVPN (Nord Security)** — Approved; affiliate link live site-wide. See note below for links and PPC rules.
- **ExpressVPN** — Declined — low reach (traffic/followers). Keep ExpressVPN CTAs as placeholder in NordVPN vs ExpressVPN and best VPN articles; reapply when traffic/reach grows.
- **Netlify** — Applied via PartnerStack; application pending.
- **Cursor** — No referral program. Cursor replied with Ambassadors link (community program, no affiliate links). Keep current CTA as-is unless they launch a referral program later.

**Declined — reapply when:**

- **HubSpot:** Site reaches ~1k+ monthly visitors (verify in Google Search Console).
- **ExpressVPN:** Traffic and/or followers grow; then reapply via expressvpn.com/affiliates.

**Nord Security (NordVPN) — links and rules:**

- **NordVPN link (live):** `https://go.nordvpn.net/aff_c?offer_id=15&aff_id=142839&url_id=902`
- **NordPass link (for future use):** `https://go.nordpass.io/aff_c?offer_id=488&aff_id=142839&url_id=9356` — use when you add password-manager or NordPass-focused content.
- **PPC:** No branded PPC (Google Ads, Bing Ads, etc.) on “NordVPN”, “NordPass”, “Nord”, or variations. Comply with promotion rules in the partner dashboard.

---

## 2. Replace official URLs with your affiliate links (when ready)

All article and hub CTAs use **official product URLs + ref placeholder** (`?ref=techwalkthroughs`) so links still work and you can track. When you have **affiliate or referral URLs**, replace the full `href` (or just the ref value) per program. Search for `ref=techwalkthroughs` to find all placeholder links.

| File | Button 1 (primary) | Button 2 (secondary) | Button 3 (if any) |
|------|--------------------|------------------------|---------------------|
| `marketing-crm/best-crm-small-business-2026/index.html` | Try HubSpot free → | Try Monday.com → | — |
| `marketing-crm/hubspot-vs-monday-2026/index.html` | Try HubSpot free → | Try Monday.com → | — |
| `cybersecurity/best-vpn-business-2026/index.html` | Get NordVPN for Business → | Try 1Password Teams → | — |
| `cybersecurity/nordvpn-vs-expressvpn-2026/index.html` | Get NordVPN for Business → | Try ExpressVPN → | — |
| `cybersecurity/best-password-manager-teams-2026/index.html` | Try 1Password Teams → | — | — |
| `ai-coding/best-ai-coding-assistant-2026/index.html` | Try GitHub Copilot → | Try Tabnine → | Try Replit → (use your referral link) |
| `ai-coding/github-copilot-vs-cursor-2026/index.html` | Try GitHub Copilot → | Try Cursor → | — |

Keep `rel="nofollow"` on those links unless a program’s terms say otherwise.

---

## 3. Optional: replace hub CTAs with your affiliate links

The category hubs (`marketing-crm/`, `cybersecurity/`, `ai-coding/`) now have one top-pick CTA each (HubSpot, NordVPN, GitHub Copilot). NordVPN hub CTA uses affiliate link; replace HubSpot and Copilot when you have those links.

---

## 4. Deploy and submit

- [ ] Push to GitHub so the site builds (e.g. GitHub Pages with custom domain).
- [ ] In Google Search Console, add the property and submit [sitemap](https://techwalkthroughs.com/sitemap.txt) (or your sitemap URL).
- [ ] In Bing Webmaster Tools, add the site and submit the sitemap (optional but recommended).

---

## 5. Phase 2 content (when ready)

After the above is done, add the next articles in this order for max recurring $ + SEO:

1. **HubSpot vs Monday 2026** — Two recurring affiliates on one page.
2. **GitHub Copilot vs Cursor 2026** — High volume; add Copilot (and Cursor if they have a program).
3. **Best Password Manager for Teams 2026** — 1Password recurring.
4. **NordVPN vs ExpressVPN 2026** — Strong “vs” intent for NordVPN.

Details and more ideas are in `CONTENT_ROADMAP.md`.

---

## Quick checklist

- [ ] Sign up: Monday (done — link live), NordVPN (done — link live), 1Password, Tabnine; HubSpot and ExpressVPN declined — reapply at 1k+ visitors / when reach grows
- [ ] Apply: Tabnine; check GitHub for Copilot referral/partner link; get Replit referral link (replit.com/refer, paid plan to earn); Cursor (no referral program — Ambassadors only; keep CTA as-is)
- [ ] Replace official CTA URLs with your affiliate/referral links where applicable
- [ ] Deploy and submit sitemap (Google, optionally Bing)
- [ ] (Optional) Add one CTA per category hub to your top affiliate
- [ ] Plan Phase 2 articles when you have capacity

---

## 6. Backlinks & outreach (do this now — #1 ranking accelerator)

Without backlinks, new domains typically take 6–12 months to rank. Even 5–10 quality links in the first 30 days compresses that to ~3 months.

### Quick wins (this week)

- [ ] **Reddit — answer real questions, link to your article**
  - `r/smallbusiness` — CRM questions (HubSpot, Monday, "what CRM should I use")
  - `r/sysadmin` / `r/cybersecurity` — VPN and password manager threads
  - `r/webdev` / `r/programming` — AI coding tool debates (Copilot vs Cursor etc.)
  - Rule: write a genuinely helpful answer first, then cite your article — don't just drop a link
- [ ] **Hacker News** — post a "Show HN" or link post (e.g. *"I spent 100 hours testing the best CRMs for small business in 2026"*). HN links carry real SEO weight.
- [ ] **Quora** — search for CRM, VPN, AI coding questions; write solid answers and cite your articles. Nofollow but drives referral traffic that can lead to natural backlinks.

### Medium effort (next 2–4 weeks)

- [ ] **Product Hunt launch** — submit the site as a product. Frame it as a tool for making software decisions. A decent launch can get 20–50 upvotes and media pickup.
- [ ] **Directory submissions**
  - [AlternativeTo.net](https://alternativeto.net) — list tools you review; mention your site in comments
  - [There's An AI For That](https://theresanaiforthat.com) — for the AI coding section
  - [Indie Hackers](https://www.indiehackers.com) — create a project page and document your journey
- [ ] **HARO / Qwoted / Featured.com** — sign up for journalist query services. When a reporter needs a quote on "best CRM for startups" or "VPN for remote teams," reply fast. One Forbes/TechCrunch mention = major domain boost.

### Higher effort (ongoing)

- [ ] **Reach out to the tools you review** — once you're an approved affiliate, ask HubSpot, Monday, NordVPN if they link to comparison articles from their resource/partner pages. Some do.
- [ ] **Guest posts** — write one article for a SaaS or SMB blog (Zapier Blog, Buffer Blog, Indie Hackers) that references your comparisons. One guest post on a DA 60+ site > 50 directory submissions.

### Avoid
- Paid link schemes / link farms → Google penalty risk
- Generic low-quality directory spam → zero SEO value
