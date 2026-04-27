---
name: solpay-email-marketing
description: >
  Email strategy and writing reference for SolPay Server. Load this skill when writing
  any email content: product emails, drip campaigns, onboarding sequences, survey emails,
  or newsletter content. Covers list segmentation, subject line strategy, email structure,
  deliverability basics, and the tone rules that keep SolPay emails from sounding like
  a SaaS marketing team. Always read the product-marketing skill first, then load this.
---

# SolPay Server — Email Marketing Reference

SolPay Server email is direct. The list is earned — developers who installed the software,
merchants who signed up for updates, and community members who opted in. Every email should
treat that trust seriously: get to the point, say something useful, and do not pad.

---

## List Segmentation

Segment the email list into these primary buckets. Content should be adapted per segment.

| Segment | Who They Are | Primary Interest |
|---|---|---|
| **Developers** | Installed SolPay or starred on GitHub, technical users | New features, API changes, integration guides, security updates |
| **Merchants (active)** | Running SolPay on a live store | Uptime, new payment options, performance updates, case studies |
| **Merchants (evaluating)** | Signed up but not deployed | Setup help, comparison content, what's possible |
| **Community** | Newsletter subscribers, Discord/Telegram members | Ecosystem news, project updates, community highlights |
| **High-risk operators** | Merchants who joined from high-risk or deplatforming-related content | Sovereignty features, permissionless framing, no-fluff updates |

When in doubt about which segment applies, default to writing for developers + active
merchants combined — they are the core audience.

---

## Subject Line Strategy

The subject line is the only thing that determines whether the email gets opened. Every
other word in the email is conditional on the subject line working.

### What makes SolPay subject lines work
- Specific over vague: "SolPay 0.4 is out — here's what changed" beats "Big update this month"
- Curiosity or useful tension: "Why we removed the fee estimator (and what we did instead)"
- Honest urgency: "Heads up: breaking change in the webhook format"
- Direct benefit: "Accept USDT on Solana in 10 minutes with the new plugin"

### Format options
- **Product update:** `[Version] is live — [biggest change in plain language]`
- **How-to:** `How to [do the thing they want to do]`
- **Announcement:** `[Feature name]: [what it does in one clause]`
- **Insight / narrative:** `[Specific claim or honest observation]`
- **Survey:** `Quick question about [topic] — 2 minutes`

### Subject line rules
- Under 55 characters preferred (mobile preview cutoff)
- No emoji unless the segment and tone clearly support it (developers: no)
- No "RE:" tricks or fake reply chains
- Never "Just checking in" or "Touching base"
- No all-caps

### Preview text
- Always set preview text — it extends the subject line in the inbox
- Should add information, not repeat the subject line
- 60-90 characters

---

## Email Structure

### For product and announcement emails
1. **One-line opener** — state what this email is about immediately
2. **The substance** — what changed, what's new, what the reader needs to know
3. **Why it matters** — brief, specific, tied to a real use case
4. **What to do next** — one primary CTA, optionally one secondary
5. **Sign-off** — short, human, from a person (not "The SolPay Team")

### For how-to / educational emails
1. **The problem** — name the pain point the reader has
2. **What you're going to show them** — set expectations in one sentence
3. **The steps** — numbered, concise, each step actionable
4. **What happens when they're done** — the payoff
5. **CTA** — usually a link to docs or a direct install link

### For drip / nurture emails
Follow the sequence structure defined in each campaign. General principle: each email in
a drip has one job. Do not try to do everything in one email.

---

## Email Writing Rules

### Voice
- Write from a person. "I" or "we" — pick one per email, be consistent.
- SolPay emails from a founder or contributor, not from a brand account.
- Direct. "Here's what changed." Not "We are pleased to inform you of recent developments."
- Honest about limitations. If something is rough around the edges, say so.

### Structure rules
- Short paragraphs: 2-3 sentences max
- Use bullets for lists of 3 or more items
- Bold the most important phrase in a section if it needs to stand out
- One primary CTA per email. Secondary CTA is optional and must be clearly lower priority.
- No walls of text. If a section runs past 4 sentences, break it up.

### Tone calibration by segment
- **Developers:** technical, peer-level, no hand-holding, specific details welcome
- **Merchants (evaluating):** reassuring, practical, benefit-focused, reduce complexity
- **High-risk operators:** direct, no-fluff, acknowledge their skepticism, earn trust fast
- **Community:** conversational, slightly warmer, can have more personality

### Things to never write
- "We are excited to announce"
- "Game changer," "industry-leading," "cutting-edge"
- Em dashes or double hyphens
- Multiple exclamation points
- Passive voice throughout (occasional passive is fine, habitual is not)
- "Please don't hesitate to reach out"
- "As always, thank you for your support"

---

## CTA Framework for Emails

| Email Type | Primary CTA | Secondary CTA |
|---|---|---|
| Product update | "See what's new" / "Read the changelog" | "Update your instance" |
| How-to | "Follow the guide" / "View in docs" | "Join the community if you get stuck" |
| Onboarding (early) | "Start the setup" | "Read the quickstart" |
| Onboarding (mid) | "Configure your first invoice" | "Join Discord for help" |
| Survey | "Take the survey (2 min)" | None |
| Newsletter | "Read the full post" | "Reply with thoughts" |

---

## Deliverability Basics

These are operational but worth flagging in content planning:

- Avoid spam trigger words: "free," "guaranteed," "no risk," "act now," "winner"
  (especially relevant for high-risk segment emails about permissionless payments)
- Plain text version should always accompany HTML
- Unsubscribe link is mandatory and must be one click
- From address should be a real person address where possible, not `noreply@`
- SPF, DKIM, and DMARC records must be configured on the sending domain

---

## Accumulated Email Lessons

*Append open rate data, CTA click patterns, and segment-specific learnings after each campaign.*

<!-- Email lessons will be appended here. None yet. -->
