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
  Do not skip any approval gates — skyscrapers take research investment and a bad outline
  wastes hours.
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

## What Makes a Skyscraper Earn Its Position

A skyscraper wins by doing at least three of the following that the top-ranking posts do not:

1. Covering the topic from more angles (more use cases, more audience types)
2. Including verifiable data that other posts skip or approximate
3. Going deeper on the technical layer (actual commands, architecture details)
4. Acknowledging trade-offs honestly (the top-ranking posts often oversell their topic)
5. Organizing the information better (table of contents, clear H2/H3 hierarchy, scannable)
6. Answering the "People also ask" questions that competitors leave unanswered
7. Being more current (updated data, recent Solana developments)

Identify the gaps in Step 1 and make sure the outline closes every one of them.

---

## Step 1: Competitive Research and Gap Analysis

1. Search for the primary keyword. Pull the top 5 ranking results.

2. For each, analyze:
   - Approximate word count and depth
   - H2 structure (what topics do they cover?)
   - What claims do they make? Are they sourced?
   - What do they NOT cover that a searcher with this query would want?
   - What is outdated?

3. Search for "People also ask" questions related to the primary keyword.
   These are explicit content gaps — questions that need to be answered in the post.

4. Identify keyword cluster:
   - Primary keyword (the anchor the post is optimized for)
   - 4-8 secondary keywords within the same cluster
   - 6-10 LSI and semantic terms to weave throughout

5. Present the gap analysis and keyword cluster:

**Keyword cluster:**
| Keyword | Volume | Intent | Competition | Role |
|---|---|---|---|---|
| [primary] | | | | Primary |
| [secondary x] | | | | Secondary |

**Content gaps in top 5 results:**
- Gap 1: [what they miss]
- Gap 2: [what they miss]
- (etc.)

**"People also ask" questions to answer:**
- Question 1
- Question 2
- (etc.)

**Wait for gap analysis approval before outlining.**

---

## Step 2: Outline

A skyscraper outline is detailed because skyscrapers fail in the outline, not the draft.

Present:

- **2-3 title options** — comprehensive framing, primary keyword near front, under 70
  characters
  Examples: "The Complete Guide to Self-Hosted Solana Payments (2025)" or
  "Solana Payment Gateway: How to Accept SOL and SPL Tokens Without a Middleman"

- **Meta description** — 140-160 chars, primary keyword, signals comprehensiveness

- **URL slug** — short, keyword-first

- **Narrative pillar** — which SolPay pillar anchors this post

- **Primary audience** — who is this post most for

- **Full Table of Contents** — every H2 and H3, annotated with:
  - Which content gap it closes
  - Which keyword or question it targets
  - Estimated word count for that section

- **Data and sources plan** — which claims need sourcing, where those sources come from

- **Internal link plan** — 5-8 internal links with anchor text

- **CTA plan** — soft CTA mid-post, direct CTA at close, and what each CTA leads to

**Do not begin the draft without outline approval.**

---

## Step 3: Draft

### Architecture
Skyscrapers satisfy three types of searcher in one post:
- The reader who wants to understand the topic (informational — serve them at the top)
- The reader comparing options (commercial — serve them in the middle)
- The reader ready to act (transactional — serve them at the close)

Structure the post accordingly:
1. **Open** with the problem or context (informational, sets the stage)
2. **Explain the landscape** (what options exist, why self-hosted matters)
3. **Go deep on SolPay** (the product sections — features, setup, use cases)
4. **Address objections and trade-offs** (builds credibility, reduces bounce)
5. **Close with action** (transactional CTA, clear next step)

### Table of contents
Include a linked table of contents at the top. It improves UX and signals to Google
that the post is comprehensive.

### Writing rules for long-form
- Vary paragraph length. Two short paragraphs then one medium one, not endless identical blocks.
- Each H2 section should be independently useful — a reader jumping to a section mid-post
  should get value without reading what came before.
- Use tables for comparisons, numbered lists for steps, bullets for feature lists.
  Do not use bullets for prose.
- Every data point needs a source in the text. Do not make unsourced claims in a post
  that's supposed to be the definitive resource.
- Include at least one code block or technical example if the topic is developer-facing.

### Voice
- No em dashes or double hyphens
- No banned phrases
- Honest about trade-offs: "self-hosting means you're responsible for uptime and security —
  that's a real operational cost, and it's worth knowing before you start"
  (note: rewrite that without the em dash — use a period or restructure)
- Specific and verifiable: "$0.00025 per transaction" beats "very low fees"

---

## Step 4: Pre-Publish Checklist

**Content:**
- [ ] Covers all identified content gaps from Step 1
- [ ] Answers all "People also ask" questions
- [ ] Every data claim is sourced
- [ ] Trade-offs covered honestly at least once
- [ ] Table of contents present and linked
- [ ] Each H2 section provides standalone value

**SEO:**
- [ ] Primary keyword in title, H1, URL slug
- [ ] Meta description 140-160 chars
- [ ] Full H2/H3 structure covers keyword cluster naturally
- [ ] 5-8 internal links with descriptive anchor text
- [ ] 3-6 external links to authoritative sources
- [ ] Word count 2,500-4,500 (check against the gap analysis — beat the average of top 5)
- [ ] Images have alt text with keywords where natural

**Voice:**
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Paragraph lengths varied
- [ ] Opener addresses the reader before mentioning SolPay

---

## Accumulated Lessons

*Add post-publish ranking data, link acquisition results, and structural improvements here.*

<!-- Lessons will be appended here. None yet. -->
