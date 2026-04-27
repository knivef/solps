---
name: solpay-blog-industry
description: >
  Write industry and trend blog posts for SolPay Server. Use this skill for posts about
  broader crypto payments landscape, Solana ecosystem developments, stablecoin trends,
  regulatory changes, and fintech movements that contextualize why SolPay Server exists.
  Triggers on: "write a blog about the stablecoin market," "cover the latest Solana
  payment trends," "write a thought leadership post about self-hosted payments,"
  "create a post about [industry development] and what it means for merchants,"
  "we should write something about [regulatory news]." These posts build authority and
  organic reach without being product-first. SolPay appears as context, not the subject.
---

# SolPay Server — Industry and Trend Blog

Industry posts build authority and attract top-of-funnel readers who are not yet looking
for SolPay specifically but are thinking about the problems SolPay solves.

The rule: SolPay is mentioned as relevant context, not as the subject. If SolPay is the
hero of every sentence, this is a product post — use `blog-product` instead. Industry
posts earn credibility by being genuinely informative first.

**Before starting:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `seo-marketing/SKILL.md` — keyword rules, on-page requirements

---

## Step 1: Topic and Angle Selection

1. If the topic is given, proceed. If vague, ask for the specific event or trend to cover.

2. **Web search the topic broadly first.** Before deciding the angle, understand what
   coverage already exists:
   - Search the topic and fetch the top 5 results with `web_fetch`
   - Search for the topic on major crypto and fintech publications
     (The Block, Decrypt, CoinDesk, Blockworks, Payments Dive)
   - Search for any primary sources: official announcements, regulatory filings,
     foundation reports, company blog posts

3. From the existing coverage, identify what is missing:
   - The merchant or developer consequence that nobody has spelled out
   - The data point that exists but nobody has cited
   - The counterpoint to the dominant narrative
   - The "what does this mean for self-hosted infrastructure" framing that
     mainstream crypto coverage always skips

4. Identify a target keyword. Industry posts often target informational keywords:
   - "stablecoin payments 2025"
   - "Solana merchant adoption"
   - "self-hosted payment gateway benefits"

5. Present the angle and keyword for approval before outlining.

---

## Step 2: Deep Source Research

Before outlining, build an evidence base from primary sources.

### 2a: Primary source search

Search for and fetch:
- Official reports: Solana Foundation, Chainalysis, Circle, Visa/Mastercard crypto
  reports, government regulatory filings, central bank publications
- Company announcements: official blog posts, press releases, GitHub releases
- Academic and research papers if relevant to the topic
- Data aggregators with primary methodology: Dune Analytics, DeFiLlama, Messari

For each source, note:
- The specific data point or claim it provides
- The publication date (flag anything over 18 months old as potentially stale)
- The direct URL for linking

### 2b: Existing coverage analysis

For the top 5 pieces of existing coverage on this topic (fetched in Step 1):
- What claims do they make?
- Which claims are sourced and which are asserted without evidence?
- What data are they using and how current is it?
- What perspective or consequence are they missing?

### 2c: Research brief

Present before outlining:

**Existing coverage summary:**
- What the mainstream narrative says about this topic (2-3 sentences)
- What angle most coverage takes
- What most coverage misses

**Primary sources confirmed:**
| Source | Data Point | Date | URL |
|---|---|---|---|
| | | | |

**SolPay's unique angle:** The specific lens this post applies that existing coverage
does not. Must be grounded in a real gap in the research above, not a generic
"we're different" claim.

**Wait for research brief approval before outlining.**

---

## Step 3: Outline

- **2-3 title options** — specific, informational framing, keyword near front
- **Meta description** — 140-160 chars, informational, what the reader learns
- **Opening hook** — the specific data point, event, or tension this post opens with
- **H2 structure** — each section annotated with which source it draws from
- **SolPay mention plan** — where SolPay appears and how (context, not pitch)
  Maximum 3 mentions total.
- **CTA** — soft and relevant (newsletter, related post, learn about self-hosted payments)

**Wait for outline approval before drafting.**

---

## Step 4: Draft

### The SolPay mention rule
SolPay appears in 1-3 places maximum:
- Once as context in the body ("self-hosted infrastructure like SolPay Server is
  built for exactly this environment")
- Once in the CTA at the close
- Optionally once in the intro if the post's angle directly concerns a problem SolPay
  addresses

Never more than three mentions. The post is about the industry.

### Source and data rules
- Every statistic cited must link to its primary source in the text
- State the publication date of any data used ("According to Chainalysis's 2024 report...")
- If a primary source cannot be found for a statistic, do not use it
- Where existing coverage cites stale data, cite the current version and note the update

### Voice
- Analytical and editorial — take a position on the trend
- Acknowledge competing interpretations where they genuinely exist
- No em dashes, no banned phrases, no hype

---

## Step 5: Pre-Publish Checklist

**Research layer:**
- [ ] Top 5 existing pieces on this topic fetched and reviewed
- [ ] Primary sources fetched and verified (not secondhand citations)
- [ ] Every statistic has an in-text source with link and date
- [ ] Post takes an original angle not already covered by existing content

**Content:**
- [ ] SolPay mentioned no more than 3 times, all contextual
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Post takes a clear position, not just a summary of what others said

**SEO:**
- [ ] Target keyword in title, H1, and URL slug
- [ ] Meta description 140-160 chars
- [ ] 2-4 internal links to related SolPay content
- [ ] Soft CTA at close fits the informational tone

---

## Accumulated Lessons

*Topic performance data, link acquisition results, and angle adjustments.*

<!-- Lessons will be appended here. None yet. -->
