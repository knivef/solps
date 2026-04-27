---
name: solpay-blog-seo
description: >
  Write SEO-optimized blog posts for SolPay Server. Use this skill when the primary goal
  is search ranking — targeting a specific keyword or keyword cluster to bring in organic
  traffic. Triggers on: "write an SEO blog about X," "I want to rank for [keyword],"
  "write a blog targeting [search term]," "help me rank for Solana payment gateway,"
  "create content for [keyword] traffic." Also use when building topic cluster content
  or pillar pages around SolPay's core keyword themes. Runs the full workflow: keyword
  research → SERP research → competitor analysis → outline approval → draft → publish
  checklist. Do not skip approval gates.
---

# SolPay Server — SEO Blog

**Before starting:** Load and internalize:
- `product-marketing/SKILL.md` — brand voice, pillars, audience segments, banned phrases
- `seo-marketing/SKILL.md` — keyword clusters, on-page rules, intent mapping, LSI terms

Apply everything in those references throughout this workflow.

---

## Blog Type Selection

**Short-form SEO post:** 800-1,400 words. Targets one specific long-tail keyword.

**Standard SEO post:** 1,400-2,000 words. Targets a primary keyword plus 3-5 secondaries.

**Skyscraper post:** 2,500-4,500 words. Use the dedicated `blog-skyscraper` skill instead.

If unclear, ask: "Is this a focused short post or a comprehensive long-form piece?"

---

## Step 1: Keyword Research and Intent Mapping

1. Review keyword clusters in `seo-marketing/SKILL.md` first.

2. Web search the topic. Identify what ranks in positions 1-10, word count and format
   of top posts, content gaps, related searches, and "People also ask" patterns.

3. Present findings:

| Keyword | Est. Volume | Intent | Competition | Recommendation |
|---|---|---|---|---|
| [primary] | | Informational / Commercial / Transactional | Low / Med / High | Primary target |
| [secondary 1] | | | | Secondary |
| [secondary 2] | | | | Secondary |
| [LSI term 1] | | | | Semantic layer |

4. Check for cannibalization against existing SolPay posts.

5. **Wait for keyword approval before proceeding.**

---

## Step 2: SERP and Competitor Research

This step is mandatory. Do not skip it. Writing without reading what already ranks means
repeating the same angles, missing the same gaps, and losing to the same posts.

### 2a: Fetch and analyze top-ranking pages

Search for the approved primary keyword. Identify the top 5 ranking URLs. For each one,
use `web_fetch` to retrieve the full page content and extract:

- **Title and H1** — how they frame the topic
- **Approximate word count**
- **H2 structure** — what sections they cover and in what order
- **Lead angle** — what unique hook or perspective they open with
- **Data and sources used** — specific statistics and claims made
- **What they miss** — unanswered questions, underserved audiences, thin sections,
  outdated information, missing depth

### 2b: "People also ask" and related searches

Record all "People also ask" questions and related searches shown in the SERP for the
primary keyword. These are explicit signals of searcher intent. Every question the
top-ranking posts do not fully answer is a content opportunity.

### 2c: Research brief

Present before outlining:

**Top 5 competitor summary:**

| # | URL | Approx. Words | Lead Angle | Key Gaps |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |

**Content gaps across all top results:**
- Gap 1: [specific topic or angle not covered]
- Gap 2: [specific question left unanswered]
- Gap 3: [audience segment not addressed]

**"People also ask" questions not fully answered by top results:**
- Question 1
- Question 2

**Target word count:** Average of top 5 results plus 15-20%. State the number.

**SolPay's differentiation angle:** The specific angle this post owns that none of the
top results do. This must come from the gap analysis — not from a generic product pitch.

**Wait for research brief approval before writing the outline.**

---

## Step 3: Outline

Build from the approved keyword set and research brief. Every H2 section must map to
a gap identified in Step 2 or a "People also ask" question. Sections that do neither
should be cut.

Include:
- **2-3 title options** — primary keyword near front, under 65 chars, no clickbait
- **Meta description** — 140-160 chars, keyword, soft CTA
- **URL slug** — short, hyphenated, keyword-first
- **Narrative pillar** — which SolPay pillar anchors this post
- **Target audience segment**
- **H2 and H3 structure** — each H2 annotated with which gap or PAA question it addresses
- **Suggested word count per section**
- **Internal link placements** — 3-6 links with anchor text
- **CTA placement** — mid-post and end

**Do not write the draft without outline approval.**

---

## Step 4: Draft

### Opening
Never open with the product. Open with the reader's situation or pain. The first
paragraph earns attention. The second brings in SolPay as the answer.

### Using the research
- Where competitors cite a statistic, use a better or more recent one, or add context
  that theirs lacks
- Where competitors make unsourced claims, source yours
- Do not mirror competitor structure — reorganize so the information architecture is
  meaningfully different
- Where competitor content is outdated (old Solana stats, deprecated tooling), explicitly
  note the current state
- Answer every "People also ask" question from Step 2, either as a dedicated section or
  woven naturally into a relevant section

### Writing rules
- One idea per paragraph, 2-3 sentences
- Vary sentence length deliberately
- Primary keyword in first 100 words, then naturally every 300-400 words after
- Secondary keywords and LSI terms woven in where they read naturally
- No em dashes, no double hyphens
- No banned phrases from product-marketing skill
- Specific numbers over vague claims — "400ms finality" not "very fast"
- Acknowledge trade-offs honestly

### Links
- 3-6 internal links with descriptive anchor text
- 2-4 external links to authoritative sources (Solana docs, reputable publications)

---

## Step 5: Pre-Publish Checklist

**Research layer:**
- [ ] Top 5 ranking pages fetched and fully analyzed via web_fetch
- [ ] All identified content gaps addressed in the draft
- [ ] All "People also ask" questions answered somewhere in the post
- [ ] SolPay's differentiation angle is clear and distinct from competitors
- [ ] Word count meets or exceeds the target set in Step 2

**SEO layer:**
- [ ] Primary keyword in title, H1, and URL slug
- [ ] Meta description 140-160 chars with keyword and CTA
- [ ] H2 and H3 structure uses secondary and LSI keywords naturally
- [ ] 3-6 internal links with descriptive anchor text
- [ ] 2-4 external links to credible sources
- [ ] All images have alt text

**Voice and quality:**
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Opener addresses reader's problem before mentioning SolPay
- [ ] Specific numbers and details throughout
- [ ] Trade-offs acknowledged at least once
- [ ] CTA matches post intent

---

## Accumulated Lessons

*Keyword performance data, structural changes, and writing adjustments from published posts.*

<!-- Lessons will be appended here after each post review. None yet. -->
