---
name: solpay-blog-skyscraper
description: >
  Write comprehensive, long-form skyscraper blog posts for SolPay Server. Use this skill
  when the goal is to create the definitive resource on a topic — content that ranks for
  an entire keyword cluster, earns backlinks, and beats existing top-ranking posts in
  depth and usefulness. Triggers on: "write a skyscraper about X," "I want to dominate
  the keyword cluster for [topic]," "create the definitive guide to [topic]," "beat the
  top-ranking post on [keyword]," "write a comprehensive guide to Solana payments."
  This skill is for 2,500-4,500 word posts only. For shorter SEO posts, use blog-seo.
  Do not skip any approval gates.
---

# SolPay Server — Skyscraper Blog

A skyscraper post is not a long product post. It is the authoritative resource on a topic —
the one that makes someone think "I don't need to read anything else about this." It must
genuinely be more comprehensive, more accurate, and more useful than whatever is currently
ranking in positions 1-5.

**Before starting:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `seo-marketing/SKILL.md` — keyword clusters, intent mapping, on-page rules, LSI terms

---

## Step 1: Keyword Research and Cluster Mapping

1. Web search the topic. Identify the full keyword cluster — not just the primary keyword
   but all related terms a comprehensive post on this topic should rank for.

2. Present the cluster:

| Keyword | Est. Volume | Intent | Competition | Role |
|---|---|---|---|---|
| [primary] | | | | Primary |
| [secondary x] | | | | Secondary |

3. Check for cannibalization against existing SolPay posts.

4. **Wait for keyword cluster approval before proceeding.**

---

## Step 2: Deep Competitor Research and Gap Analysis

This is the most important step in the skyscraper workflow. The entire post strategy
depends on understanding what already exists and where it falls short.

### 2a: Fetch the top 5-7 ranking pages

Search for the primary keyword. For each of the top 5-7 results, use `web_fetch` to
retrieve the full page content. Do not skim — read the full content of each page.

For each competitor post, extract:

- **Title and H1**
- **Word count** (approximate)
- **Full H2 and H3 structure** — copy out every heading
- **Lead angle and hook** — what problem or claim opens the post
- **Every data point and statistic used** — note whether each is sourced or unsourced
- **What they cover well** — sections with real depth
- **What they cover poorly** — thin sections, vague claims, missing examples
- **What they miss entirely** — topics, audiences, questions, use cases not covered
- **How current the content is** — outdated stats, deprecated tools, old product info

### 2b: "People also ask" and SERP features

Search the primary keyword and every major secondary keyword in the cluster. Record:
- All "People also ask" questions
- Related searches
- Any featured snippets and what format they use (paragraph, list, table)
- Any knowledge panel content

### 2c: Source research

For every major claim in the competitor posts, find the original source. If the source
is better than what the competitors link to, use it. If it is outdated, find the current
version. If it does not exist (unsourced claim), note it — either find a real source or
do not make the claim.

Also proactively search for data and research that competitors have missed entirely:
- Solana Foundation reports and network data
- Stablecoin payment volume data
- Crypto merchant adoption studies
- Self-hosting and open-source payment tooling coverage

### 2d: Compile the full research brief

Present before outlining:

**Competitor analysis:**

| # | URL | Words | H2 Structure Summary | Strongest Section | Key Gaps |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**All content gaps (topics missing across all top results):**
- Gap 1
- Gap 2
- (list every gap found)

**All "People also ask" questions not fully answered:**
- Question 1
- Question 2

**Data and sources available that competitors missed:**
- Source 1: [what data it provides]
- Source 2: [what data it provides]

**Target word count:** Average of top 5 plus 25-30%. State the number.

**SolPay's differentiation angle:** The specific thesis this post owns. Must come from
the gap analysis. Must be something none of the top 5 posts say clearly.

**Wait for full research brief approval before outlining.**

---

## Step 3: Outline

A skyscraper outline is detailed because skyscrapers fail in the outline, not the draft.
Every H2 must map to a gap, a PAA question, or a keyword in the cluster. Flag which one.

Include:
- **2-3 title options** — comprehensive framing, primary keyword near front, under 70 chars
- **Meta description** — 140-160 chars, keyword, signals comprehensiveness
- **URL slug** — short, keyword-first
- **Narrative pillar** — which SolPay pillar anchors this
- **Primary audience**
- **Full Table of Contents** — every H2 and H3, annotated with:
  - Which gap or PAA question it closes
  - Which keyword it targets
  - Estimated word count for that section
- **Data and sources plan** — which claims need sourcing, which sources to use
- **Internal link plan** — 5-8 internal links with anchor text
- **CTA plan** — soft mid-post, direct at close

**Do not begin the draft without outline approval.**

---

## Step 4: Draft

### Architecture

Skyscrapers serve three searcher types in one post:
1. Reader who wants to understand (informational — top of post)
2. Reader comparing options (commercial — middle)
3. Reader ready to act (transactional — close)

Structure accordingly. Do not put the CTA at the top.

### Table of contents
Include a linked TOC at the top. Improves UX and signals comprehensiveness to Google.

### Using the research
- Where competitors use a statistic, use a better, more recent, or more specific one
- Where competitors make unsourced claims, source yours with a link to the primary source
- Where competitor structure is logical, reorganize it so the architecture is meaningfully
  different — same topics, different order and depth
- Where competitor content is outdated, flag the current state explicitly:
  "As of [year], Solana's average transaction fee is $0.00025, down from..."
- Answer every PAA question identified in Step 2 — either as a dedicated H2/H3 or woven
  into a directly relevant section
- Use tables for comparisons, numbered lists for steps, bullets for feature lists

### Writing rules
- One idea per paragraph, 2-3 sentences
- Vary paragraph and sentence length deliberately
- Each H2 section independently useful — a reader jumping in mid-post gets value
- Specific numbers throughout — "65,000 TPS theoretical capacity" not "very high throughput"
- No em dashes, no double hyphens
- No banned phrases
- Honest about trade-offs — self-hosting has real operational overhead, say it

### Links
- 5-8 internal links with descriptive anchor text
- 4-6 external links to primary authoritative sources

---

## Step 5: Pre-Publish Checklist

**Research layer:**
- [ ] Top 5-7 pages fully fetched and analyzed via web_fetch
- [ ] Every identified gap addressed in the draft
- [ ] Every PAA question answered somewhere in the post
- [ ] Every data claim sourced to a primary source
- [ ] Word count meets or exceeds target from Step 2
- [ ] SolPay's differentiation angle clear and distinct

**SEO layer:**
- [ ] Primary keyword in title, H1, URL slug
- [ ] Full H2/H3 structure covers keyword cluster naturally
- [ ] Meta description 140-160 chars
- [ ] 5-8 internal links with descriptive anchor text
- [ ] 4-6 external links to authoritative sources
- [ ] Table of contents present and linked
- [ ] Images have alt text

**Voice:**
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Paragraph lengths varied
- [ ] Opener addresses reader before mentioning SolPay
- [ ] Trade-offs covered honestly

---

## Accumulated Lessons

*Post-publish ranking data, link acquisition results, and structural improvements.*

<!-- Lessons will be appended here. None yet. -->
