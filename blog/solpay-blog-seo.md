---
name: solpay-blog-seo
description: >
  Write SEO-optimized blog posts for SolPay Server. Use this skill when the primary goal
  is search ranking — targeting a specific keyword or keyword cluster to bring in organic
  traffic. Triggers on: "write an SEO blog about X," "I want to rank for [keyword],"
  "write a blog targeting [search term]," "help me rank for Solana payment gateway,"
  "create content for [keyword] traffic." Also use when building topic cluster content
  or pillar pages around SolPay's core keyword themes. Runs the full workflow: keyword
  research → outline approval → draft → publish checklist. Do not skip approval gates.
---

# SolPay Server — SEO Blog

**Before starting:** Load and internalize:
- `product-marketing/SKILL.md` — brand voice, pillars, audience segments, banned phrases
- `seo-marketing/SKILL.md` — keyword clusters, on-page rules, intent mapping, LSI terms

Apply everything in those references throughout this workflow. They override defaults
where they conflict.

---

## Blog Type Selection

**Short-form SEO post:** 800-1,400 words. Targets one specific long-tail keyword.
Informational or commercial intent. Best for: how-to content, feature explanations
targeting specific search queries.

**Standard SEO post:** 1,400-2,000 words. Targets a primary keyword plus 3-5 secondaries.
Covers a topic with enough depth to satisfy a broader search query.

**Skyscraper post:** 2,500-4,500 words. Dominates a keyword cluster. Comprehensive,
linkable, meant to become the reference post for a topic. Use the dedicated
`blog-skyscraper` skill for this type.

If the type is not specified, ask: "Is this a focused short post targeting one keyword,
or a comprehensive long-form piece covering a keyword cluster?"

---

## Step 1: Keyword Research and Intent Mapping

1. Review the keyword clusters in `seo-marketing/SKILL.md` first. If the target keyword
   already maps to an existing cluster, use those benchmarks rather than researching from scratch.

2. Web search for the target topic to understand:
   - What's currently ranking in positions 1-10
   - What word count, format, and depth the top posts use
   - What questions or angles the top posts miss (content gap = opportunity)
   - Related search queries and "People also ask" patterns

3. Identify and present:

| Keyword | Est. Volume | Intent | Competition | Recommendation |
|---|---|---|---|---|
| [primary] | | Informational / Commercial / Transactional | Low / Med / High | Primary target |
| [secondary 1] | | | | Secondary |
| [secondary 2] | | | | Secondary |
| [LSI term 1] | | | | Semantic layer |

4. Check for cannibalization: does SolPay already have a post targeting this primary keyword?
   If yes, recommend updating the existing post rather than creating a new one.

5. **Wait for keyword approval before proceeding.**

---

## Step 2: Outline

Build the outline from the approved keyword set and the content gap identified in Step 1.

Present the following:

- **2-3 title options** — primary keyword near the front, under 65 characters, benefit or
  framing hook, no clickbait
- **Meta description draft** — 140-160 chars, primary keyword, soft CTA
- **URL slug** — short, hyphenated, keyword-first
- **Narrative pillar** (from product-marketing skill) — which pillar anchors this post
- **Target audience segment** — who is this primarily for
- **H2 and H3 structure** — each H2 is a major section, H3s go inside
- **Suggested word count per section**
- **Internal link placements** — 3-6 links with anchor text suggestions
- **CTA placement** — mid-post and end

**Do not write the draft until the outline is approved.**

---

## Step 3: Draft

Write the full post following all rules below.

### Structural rules
- Open with the problem or the searcher's context, not with the product. The first
  paragraph should make the reader feel understood before SolPay is mentioned.
- Introduce SolPay naturally, as the answer to the problem, not as the subject of a
  product pitch.
- One idea per paragraph. Two to three sentences is usually enough.
- Vary sentence length. Short. Then a longer one that builds on what came before. Then
  short again.
- Every H2 section should deliver standalone value. If someone reads only that section,
  they should get something useful.
- End with a CTA that matches the intent of the post. Informational posts get a soft CTA
  ("learn more," "join the community"). Commercial posts get a direct CTA ("try it,"
  "install the plugin").

### Keyword usage
- Primary keyword in the first 100 words, naturally
- Primary keyword appears roughly once per 300-400 words after that
- Secondary keywords and LSI terms woven in where they read naturally
- Never force a keyword into a sentence where it sounds unnatural — rewrite the sentence
  instead

### Voice (from product-marketing skill)
- No em dashes, no double hyphens
- No banned phrases
- Write like a knowledgeable operator explaining something to a peer
- Be specific: exact numbers, specific features, real use cases
- Acknowledge trade-offs honestly (self-hosting has a learning curve — say that)

### Links
- 3-6 internal links with descriptive anchor text
- 2-4 external links to authoritative sources (Solana docs, academic references,
  reputable publications)
- Every external link opens in a new tab

---

## Step 4: Pre-Publish Checklist

Run before presenting the draft for review:

**SEO layer:**
- [ ] Primary keyword in title tag, H1, and URL slug
- [ ] Meta description 140-160 chars with keyword and CTA
- [ ] H2 and H3 structure uses secondary and LSI keywords naturally
- [ ] Primary keyword appears naturally every 300-400 words (no stuffing)
- [ ] 3-6 internal links with descriptive anchor text
- [ ] 2-4 external links to credible sources
- [ ] All images have descriptive alt text with keyword where natural
- [ ] Word count appropriate for post type

**Voice and quality:**
- [ ] No em dashes or double hyphens
- [ ] No banned phrases from product-marketing skill
- [ ] Opener addresses the reader's problem before mentioning SolPay
- [ ] Specific numbers and details throughout (not vague claims)
- [ ] Trade-offs acknowledged honestly at least once
- [ ] CTA matches the intent of the post

**Technical:**
- [ ] URL slug is short, hyphenated, keyword-first
- [ ] Does not cannibalize an existing SolPay post

---

## Step 5: Accumulated Lessons

*Keyword performance data, structural changes, and writing adjustments from published posts.*

<!-- Lessons will be appended here after each post review. None yet. -->
