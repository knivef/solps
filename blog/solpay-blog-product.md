---
name: solpay-blog-product
description: >
  Write product blog posts for SolPay Server. Use this skill for feature announcements,
  integration guides, use case walkthroughs, onboarding content, and any post where the
  primary goal is educating readers about what SolPay Server does and how to use it.
  Triggers on: "write a blog about the [feature]," "announce the new [integration],"
  "create a walkthrough for [use case]," "write something about how merchants use SolPay,"
  "draft a post about the WooCommerce plugin," "explain how [X] works in SolPay."
  Runs the full workflow: keyword anchor → competitor research → outline approval → draft
  → checklist.
---

# SolPay Server — Product Blog

Product blogs educate, not market. The goal is to give developers and merchants something
genuinely useful: a clear explanation of a feature, a real use case that applies to them,
or a walkthrough they can follow to get something working.

Secondary goal: rank for product-intent keywords. Treat SEO as a natural layer, not
something bolted on at the end.

**Before starting:** Load and internalize:
- `product-marketing/SKILL.md` — brand voice, narrative pillars, audience, banned phrases
- `seo-marketing/SKILL.md` — keyword rules, on-page requirements, LSI terms

---

## Product Blog Types

| Type | When to Use | Length |
|---|---|---|
| **Feature Announcement** | New feature shipped | 600-1,200 words |
| **Integration Guide** | New plugin or platform integration live | 1,000-2,000 words |
| **Use Case Post** | Specific audience solving a specific problem with SolPay | 800-1,500 words |
| **How-To / Walkthrough** | Step-by-step instructions for a common task | 800-1,600 words |
| **Onboarding Explainer** | Help new users understand and get started | 600-1,000 words |

---

## Step 1: Keyword Anchor

1. Identify 1-3 candidate product-intent keywords for the topic.
2. Check the keyword clusters in `seo-marketing/SKILL.md` for overlaps.
3. Choose one anchor keyword for the title, URL, and H1.
4. Identify 2-3 secondary keywords to weave in naturally.

---

## Step 2: Competitor and Reference Research

Even for product posts, understanding what already exists on the topic sharpens the
angle and ensures the post is not just repeating what others have already said.

### 2a: Search for existing content on the topic

Search for the anchor keyword and 2-3 related queries. Use `web_fetch` to retrieve
the top 3-5 results. For each, extract:

- **What angle they take** — how do they explain this topic or feature?
- **What they do well** — sections worth learning from structurally
- **What they miss or do poorly** — thin explanations, missing use cases, outdated
  tooling, no code examples, no honest discussion of trade-offs
- **How they position competing tools** — useful context for how SolPay should
  differentiate

### 2b: Check official documentation and changelogs

For integration guides and how-to posts, always fetch the relevant official docs:
- SolPay Server GitHub and documentation
- The third-party platform's documentation (WooCommerce, Shopify, etc.)
- Solana developer documentation for any chain-level claims

This ensures all technical claims are accurate before the draft is written.

### 2c: Research brief (lightweight)

For product posts, this does not need to be as comprehensive as the SEO or skyscraper
brief. Present:

- **What existing content covers** (2-3 sentences)
- **What it misses** (the gap this post fills)
- **Key technical details confirmed** from official docs
- **SolPay's angle** — what makes this post worth reading alongside or instead of
  what already exists

No approval gate needed here unless the research surfaces something that changes the
post direction. Flag it if so.

---

## Step 3: Outline

Present the outline before writing. Include:

- **Title options (2)** — keyword near the front, benefit-led framing, under 65 chars
- **Meta description** — 140-160 chars, anchor keyword, what the reader gets
- **Narrative pillar** — which of the three SolPay pillars this post anchors to
- **Target audience segment**
- **Opening hook** — the specific pain or context this post opens with (not the product)
- **H2 structure** — each section with a one-line description of what it covers
- **Internal links** — 2-4 suggested links with anchor text
- **CTA** — primary CTA for the post

**Do not write the draft without outline approval.**

---

## Step 4: Draft

### Opening rule
Never open with the product. Open with the reader's context or pain. The first paragraph
earns attention. The second brings in SolPay as the answer.

Good: "If you've tried to accept Bitcoin payments and spent 20 minutes watching an
unconfirmed transaction spin, you know the UX problem."

Bad: "SolPay Server is a powerful self-hosted payment solution for Solana merchants."

### For how-to and integration posts
- Number the steps
- Each step is one action with one expected outcome
- Include accurate code blocks (verified against official docs in Step 2)
- Tell the reader what they should see after each step
- Acknowledge common failure points ("If you see this error, it usually means X")

### For feature announcement posts
- Lead with what changed and why it matters to the reader, not why the team is proud
- Include a concrete example of who uses this and what it lets them do
- Keep it short — feature posts are not comprehensive guides

### For use case posts
- Open with the specific audience and their specific pain
- Walk through how SolPay solves it with specific, plausible details
- Close with what the reader can do today

### Voice
- No em dashes, no double hyphens
- No banned phrases
- Contractions preferred
- Short paragraphs: 2-3 sentences
- Honest about setup complexity — do not oversell ease

---

## Step 5: Pre-Publish Checklist

**Research layer:**
- [ ] Top 3-5 existing posts on this topic fetched and reviewed
- [ ] Official documentation checked for technical accuracy
- [ ] Post angle is clearly differentiated from what already exists
- [ ] All code blocks verified against current documentation

**Content:**
- [ ] Opener addresses reader context before SolPay is mentioned
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Specific numbers and real use cases throughout
- [ ] Trade-offs or complexity acknowledged

**SEO:**
- [ ] Anchor keyword in title, H1, and URL slug
- [ ] Meta description 140-160 chars
- [ ] 2-4 internal links with descriptive anchor text
- [ ] Images have alt text

---

## Accumulated Lessons

*Lessons from published product posts: what resonated, what missed, what CTAs worked.*

<!-- Lessons will be appended here. None yet. -->
