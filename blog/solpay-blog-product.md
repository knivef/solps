---
name: solpay-blog-product
description: >
  Write product blog posts for SolPay Server. Use this skill for feature announcements,
  integration guides, use case walkthroughs, onboarding content, and any post where the
  primary goal is educating readers about what SolPay Server does and how to use it.
  Triggers on: "write a blog about the [feature]," "announce the new [integration],"
  "create a walkthrough for [use case]," "write something about how merchants use SolPay,"
  "draft a post about the WooCommerce plugin," "explain how [X] works in SolPay."
  Runs the full workflow: keyword anchor → outline approval → draft → checklist.
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

Choose the right type before outlining:

| Type | When to Use | Length |
|---|---|---|
| **Feature Announcement** | New feature shipped. Explain what it does, why it was built, and how to use it. | 600-1,200 words |
| **Integration Guide** | SolPay now works with X. Walk through the setup end to end. | 1,000-2,000 words |
| **Use Case Post** | Explain how a specific audience type uses SolPay to solve a specific problem. | 800-1,500 words |
| **How-To / Walkthrough** | Step-by-step instructions for a common task. | 800-1,600 words |
| **Onboarding Explainer** | Help new users understand what SolPay is and how to get started. | 600-1,000 words |

If the type is unclear, ask before proceeding.

---

## Step 1: Anchor Keyword

Product blogs still benefit from keyword anchoring even if ranking is secondary.

1. Identify 1-3 candidate product-intent keywords for the topic:
   - "SolPay Server WooCommerce" (navigational-ish but searchable)
   - "how to accept USDC on Solana" (instructional with real volume)
   - "self-hosted Solana payment gateway setup" (competitive but relevant)

2. Check the keyword clusters in `seo-marketing/SKILL.md` for overlapping targets.

3. Choose one anchor keyword. This goes in the title, URL, and H1.

4. Identify 2-3 secondary keywords to weave in naturally.

5. Do not wait for keyword approval on product posts — unless there is ambiguity,
   proceed with a reasonable selection and note it in the outline.

---

## Step 2: Outline

Present the outline before writing. Include:

- **Title options (2)** — keyword near the front, benefit-led framing, under 65 chars
- **Meta description** — 140-160 chars, anchor keyword, what the reader gets
- **Narrative pillar** — which of the three pillars this post anchors to
- **Target audience segment** — developer / merchant-evaluating / merchant-active / high-risk
- **Opening hook** — the specific pain or context this post opens with (not the product)
- **H2 structure** — each section listed with a one-line description of what it covers
- **Internal links** — 2-4 suggested links with anchor text
- **CTA** — primary CTA for the post

**Do not write the draft without outline approval.**

---

## Step 3: Draft

### Opening rule
Never open with the product. Open with the reader's context.

Good: "If you've tried to accept Bitcoin payments and spent 20 minutes watching an
unconfirmed transaction spin, you know the UX problem."

Bad: "SolPay Server is a powerful self-hosted payment solution for Solana merchants."

The first paragraph earns the reader's attention. The second paragraph brings in SolPay
as the answer.

### For how-to and integration posts
- Number the steps
- Each step is one action with one expected outcome
- Include code blocks where relevant (actual commands, not pseudocode)
- Tell the reader what they should see after each step
- Acknowledge common failure points ("If you see this error, it usually means X")

### For feature announcement posts
- Lead with what changed and why it matters to the reader, not why the team is proud of it
- Include a concrete example: who uses this feature and what does it let them do
- Link to the docs or changelog for technical details
- Keep it short — feature posts should not try to be comprehensive guides

### For use case posts
- Open with the specific audience and their specific pain
- Walk through how SolPay solves it step by step
- Use specific, plausible numbers (order volume, transaction count, fee comparison)
- Close with what the reader can do today to get this working

### Voice (from product-marketing skill)
- No em dashes, no double hyphens
- No banned phrases
- Contractions preferred
- Short paragraphs: 2-3 sentences
- One idea per paragraph
- Honest about setup complexity — do not oversell ease

---

## Step 4: Pre-Publish Checklist

**Content:**
- [ ] Opener addresses reader context before SolPay is mentioned
- [ ] No em dashes or double hyphens anywhere
- [ ] No banned phrases from product-marketing skill
- [ ] Specific numbers and real use cases throughout
- [ ] Trade-offs or complexity acknowledged (not oversold)
- [ ] Code blocks accurate and tested where applicable

**SEO:**
- [ ] Anchor keyword in title, H1, and URL slug
- [ ] Meta description 140-160 chars
- [ ] H2 structure uses secondary keywords naturally
- [ ] 2-4 internal links with descriptive anchor text
- [ ] 2-3 external links to Solana docs or credible references
- [ ] Images have alt text

**CTA:**
- [ ] Primary CTA is present and matches the post type
- [ ] CTA language does not include banned phrases

---

## Accumulated Lessons

*Append lessons from published product posts here: what resonated, what missed, what CTAs worked.*

<!-- Lessons will be appended here. None yet. -->
