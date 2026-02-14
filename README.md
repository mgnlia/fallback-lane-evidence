# Fallback Lane Evidence Table — Non-DeFi Alternatives

> **Task:** `i_J3Mgq5obz-ci0rKy4ch` — Shortlist 3 non-DeFi alternatives  
> **Date:** 2026-02-14  
> **Status:** Review-ready

---

## Executive Summary

| # | Lane | Verdict | Actionability |
|---|------|---------|---------------|
| 1 | **AsyncAPI Bounties** | ✅ STRONG — Active, funded, verified payouts | **Best fallback** |
| 2 | **Golem Bounties/GEF** | ⚠️ UNCERTAIN — Rewards program dormant; GEF grants pending | Monitor only |
| 3 | **Cloudflare AI Hackathon** | ❌ BLOCKED — No open remote hackathon; next is in-person Oct 2025 | Not viable now |

**Recommendation:** If the Automation/FlowPilot primary lane blocks, pivot to **AsyncAPI Bounty Program** as the sole ready-to-execute fallback. Golem and Cloudflare should remain on the monitor list for future rounds.

---

## 1. AsyncAPI Bounty Program

### Canonical URLs
| Resource | URL |
|----------|-----|
| Program Rules | https://www.asyncapi.com/docs/community/010-contribution-guidelines/bounty_program |
| 2026 Issue Submission | https://github.com/orgs/asyncapi/discussions/2279 |
| Open Collective (budget/payouts) | https://opencollective.com/asyncapi/projects/asyncapi-bounty-program |

### Hard Deadlines (with timezone)
- **Issue Submission Window (March 2026 round):** 2026-02-09 00:00:00 UTC+12:00 → 2026-02-15 23:59:59 UTC-12:00
- **March round execution:** Entire month of March 2026
- **Cadence:** Monthly rounds, submissions during 2nd full calendar week of preceding month
- **Weekly update requirement:** Must update Draft PR and/or Bounty Issue every Monday (last activity ≤4 calendar days)

### Payout Mechanics
- **Budget:** $21,400/year → **$1,600/month** per round
- **Medium Bounty:** $200 USD
- **Advanced Bounty:** $400 USD
- **4–8 bounties per round** (depending on complexity mix)
- **Payment method:** Open Collective → wire/PayPal/other via Open Source Collective fiscal host
- **Commission:** ~$400/year for fiscal host fees

### Payout History Proof
| Date | Issue | Amount | Status |
|------|-------|--------|--------|
| 2026-02-09 | training#52 | $400 | ✅ Paid |
| 2026-02-03 | generator#1720 | $400 | ✅ Paid |
| Total raised | — | $34,150 | — |
| Total disbursed | — | $12,021.86 | — |
| **Current balance** | — | **$22,128.14** | — |

### Collision / Competition Signal
- **March 2026 round:** 4 Advanced issues submitted, budget fully allocated (1600/1600)
- **Participant priority:** Maintainers first → Regular contributors (3+ merged PRs) → Others
- **Non-maintainers wait 3 calendar days** after bounty label before assignment
- **Competition level:** MODERATE — small pool of regular contributors, but maintainers have priority
- **Entry barrier for newcomers:** Need to build contributor history first (3+ merged PRs for priority 2)

### 24h Launch Plan
1. **Hour 0–2:** Review all open AsyncAPI repos; identify issues tagged `bounty` or likely candidates for April round
2. **Hour 2–4:** Submit 3+ small PRs to AsyncAPI repos (docs fixes, test improvements) to start building contributor history
3. **Hour 4–8:** Study the codebase of repos with upcoming bounty issues (cli, generator, parser, training)
4. **Hour 8–12:** Draft solutions for likely April bounty candidates; prepare working branches
5. **Hour 12–24:** Monitor the 2026 Discussion #2279 for April submission window announcement; prepare issue-specific proposals
6. **Ongoing:** Maintain weekly updates on any claimed bounty; target Medium ($200) issues first for faster completion

---

## 2. Golem Network (GLM Rewards / Ecosystem Fund)

### Canonical URLs
| Resource | URL |
|----------|-----|
| Community/Rewards Page | https://www.golem.network/community |
| Golem Ecosystem Fund | https://ecosystem.golem.network |
| Blog (latest updates) | https://blog.golem.network |
| Discord | https://chat.golem.network |

### Hard Deadlines
- **GLM Rewards Program:** ⚠️ No published deadline. Last monthly update blog post: **September 2021**. Program page still listed on golem.network/community but appears dormant.
- **Golem Ecosystem Fund (GEF):** Blog post (Oct 10, 2025) states "new application rounds with dedicated tracks" coming "soon." **No concrete date announced.**

### Payout Mechanics
- **GLM Rewards (historical):** ~20,000 GLM/month distributed across 8–10 community slots
  - Feedback Masters: 500 GLM each
  - Tech Supporters: 2,000 GLM each
  - Application Creation: 2,250 GLM each
  - GLM ≈ $0.29 USD (current) → ~$5,800/month historically
- **GEF Grants:** Milestone-based, multi-month grants (e.g., Web3 Pi had 15 milestones). Amounts not publicly disclosed per milestone.
- **Payment:** GLM tokens (ERC-20 on ETH/Polygon). KYC required for rewards program.

### Payout History Proof
- **GLM Rewards:** Blog documented monthly payouts from July 2020 – September 2021 (250K+ GLM total over 13 months). **No evidence of payouts after 2021.**
- **GEF:** 6 projects funded (Web3 Pi, Satori, Keccak Research, Clan, L3 Explorer, Vanity Market). Milestone completions documented in Oct 2025 blog. Payout amounts not publicly itemized.

### Collision / Competition Signal
- **GLM Rewards:** If still active, competition is LOW (small community). But program may be effectively dead.
- **GEF:** Application-based grants with review process. Competition level UNKNOWN for upcoming rounds.

### 24h Launch Plan
1. **Hour 0–2:** Join Golem Discord; ask in #general about current status of GLM Rewards Program and GEF application timeline
2. **Hour 2–6:** If GEF applications open, draft a proposal for an AI/GPU tool on Golem Network (aligns with their roadmap)
3. **Hour 6–12:** Build a minimal PoC using golem-js SDK to demonstrate capability
4. **Hour 12–24:** Submit GEF application if window is open; otherwise, contribute to existing Golem repos to build visibility
5. **Contingency:** If Discord confirms rewards program is dead and GEF not accepting, **abandon this lane**

---

## 3. Cloudflare AI Hackathon

### Canonical URLs
| Resource | URL |
|----------|-----|
| Cloudflare Connect 2025 | https://events.cloudflare.com/connect/2025/overview |
| Hackathon Session | https://events.cloudflare.com/connect/2025/sessions/3344407 |
| DEV.to AI Challenge (expired) | https://dev.to/page/cloudflare-ai-challenge-contest-rules |
| Developer Track | https://events.www.cloudflare.com/connect2025/developers |

### Hard Deadlines
- **DEV.to Cloudflare AI Challenge:** April 3–14, 2024 — **EXPIRED**
- **Cloudflare Connect 2025 Hackathon:** Oct 14, 2025, 4:30 PM – 11:30 PM PT — **IN-PERSON ONLY** (Las Vegas, ARIA Resort)
- **Online/remote hackathon:** ❌ **None announced for 2025 or 2026**

### Payout Mechanics (historical reference only)
- **DEV.to Challenge (2024):** $3,000 total
  - Prompt Winner: $1,500 gift card
  - Multiple Models Winner: $750 gift card
  - Triple Task Types Winner: $750 gift card
- **Connect Hackathon:** Prizes + swag (amounts not disclosed), sponsored by Neon

### Payout History Proof
- DEV.to challenge had verified winners in April 2024
- Connect hackathon prizes distributed at in-person events

### Collision / Competition Signal
- **Not applicable** — no open competition to enter

### 24h Launch Plan
- ❌ **Cannot execute.** No remote/online hackathon available.
- **Monitor action:** Watch Devpost and DEV.to for future Cloudflare-sponsored challenges
- **Alternative:** Use Cloudflare Workers AI as a tech stack for other hackathon submissions (e.g., Cloudflare is a sponsor at HackHarvard, Technica, etc.)

---

## Risk Matrix

| Factor | AsyncAPI | Golem | Cloudflare |
|--------|----------|-------|------------|
| **Currently open?** | ✅ Yes (2026 active) | ⚠️ Unclear | ❌ No |
| **Verified payouts?** | ✅ Feb 2026 | ⚠️ Last 2021 | ✅ Apr 2024 (expired) |
| **Remote participation?** | ✅ Yes | ✅ Yes | ❌ In-person only |
| **Entry barrier** | Medium (need PR history) | Low (Discord activity) | N/A |
| **Payout speed** | ~30 days post-completion | Unknown | N/A |
| **USD value per unit** | $200–$400 | ~$145–$650 (GLM volatile) | N/A |
| **Recurring?** | ✅ Monthly | ❓ Unknown | ❌ Annual event |

---

## Final Recommendation

1. **Primary fallback: AsyncAPI Bounty Program** — Only lane with verified, active, funded bounties. Start building contributor history immediately. Target April 2026 round.
2. **Monitor: Golem GEF** — Check Discord for GEF application window. Could be high-value if grants open but timeline is unpredictable.
3. **Deprioritize: Cloudflare** — No actionable opportunity. Use their tech stack in other hackathons instead.

---

*Research completed 2026-02-14. Sources cross-referenced across GitHub, Open Collective, official docs, and blog posts.*
