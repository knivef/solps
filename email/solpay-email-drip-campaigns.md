---
name: solpay-email-drip
description: >
  Write email drip campaigns and onboarding sequences for SolPay Server. Use this skill
  for building multi-email sequences: new user onboarding, post-install nurture, merchant
  activation, re-engagement campaigns, and any multi-touch email workflow. Triggers on:
  "write an onboarding email sequence," "create a drip campaign for [goal]," "build a
  nurture sequence for new signups," "write the welcome series," "draft the activation
  emails for new merchants." Always reads the product-marketing and email-marketing
  skills first.
---

# SolPay Server — Email Drip Campaigns and Sequences

Each email in a drip has one job. A sequence that tries to do everything in every email
is worse than a short sequence where each email lands cleanly.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `email-marketing/SKILL.md` — subject strategy, structure rules, tone by segment

---

## Step 1: Audience and Friction Research

Before mapping out a sequence, understand what the target segment actually experiences.

### For onboarding sequences
- Fetch SolPay Server's GitHub issues and discussions — what setup problems do new
  users report most often?
- Fetch the SolPay documentation to understand where the setup flow has the most steps
  or the most technical complexity
- Identify the 2-3 most common drop-off points between install and first live transaction

### For merchant nurture sequences
- Web search for: "how to accept crypto payments merchant concerns," "crypto payment
  gateway objections," "why merchants don't accept crypto"
- Use `web_fetch` on the most relevant results to understand real objections —
  not assumed ones
- These objections become the specific topics each email in the nurture sequence addresses

### For re-engagement sequences
- Identify what value has been added since the subscriber last engaged
- Find the most compelling recent development to lead with

**State before mapping the sequence:**
- The 2-3 biggest friction points or objections for this segment
- Which email in the sequence addresses each one

---

## Core Sequences

### Sequence 1: Developer Onboarding (Post-Install or GitHub Star)
**Trigger:** User installs SolPay or stars the GitHub repo
**Goal:** First live transaction processed
**Length:** 4 emails over 10 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "You installed SolPay — here's how to get it live" | First activation |
| 2 | Day 2 | "The one config thing most people get wrong" | Reduce top friction point |
| 3 | Day 5 | "Your first live transaction on Solana" | First real payment |
| 4 | Day 10 | "What's next: webhooks, plugins, and going further" | Unlock advanced usage |

### Sequence 2: Merchant Evaluation Nurture
**Trigger:** Merchant signs up but has not installed
**Goal:** Move from evaluating to installing
**Length:** 5 emails over 14 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "What SolPay Server actually does (plain language)" | Honest product explainer |
| 2 | Day 3 | "How much are you actually paying in card fees?" | Surface the cost problem |
| 3 | Day 7 | "A store owner's first month on SolPay — what they said" | Social proof |
| 4 | Day 10 | "The 3 questions merchants ask before switching" | Address objections |
| 5 | Day 14 | "Ready to try it? Here's the easiest starting point" | Direct install CTA |

### Sequence 3: Post-Install Merchant Activation
**Trigger:** Merchant installs but no live transaction after 7 days
**Goal:** First live payment processed
**Length:** 3 emails over 7 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 7 | "You installed SolPay — are you stuck anywhere?" | Surface friction |
| 2 | Day 10 | "The fastest path from install to live payments" | Simplified activation |
| 3 | Day 14 | "Here if you want a hand" | Human help offer |

### Sequence 4: Re-Engagement
**Trigger:** No open or click in 90 days
**Goal:** Re-engage or clean the list
**Length:** 2 emails

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "Still interested in self-hosted Solana payments?" | Re-engage with value hook |
| 2 | Day 7 | "Last one from us — unless you want to stay" | Final send, list hygiene |

---

## Step 2: Sequence Map

Produce a sequence map for approval before writing:

```
Sequence: [Name]
Trigger: [What starts it]
Segment: [Who receives it]
Key friction points addressed: [from Step 1 research]

Email 1 — [Timing]
  Subject: [Draft]
  Preview: [Draft]
  Job: [One sentence]
  Friction addressed: [Which one]
  CTA: [Specific action]

Email 2 — [Timing]
  [Same structure]
```

**Wait for sequence map approval before drafting emails.**

---

## Step 3: Draft Each Email

**Per-email rules:**
- Each email is complete and useful standalone
- One primary CTA only
- Short paragraphs
- Subject line earns the open independently — no "SolPay Update #3" sequencing
- Reference the previous email only when it genuinely adds context

**Subject line variety across a sequence:**
- Question format: "Are you stuck on the webhook setup?"
- Benefit format: "Accepting live Solana payments in the next 20 minutes"
- Honest check-in: "You haven't processed a transaction yet — is something off?"
- Curiosity format: "The config most new installs get wrong"

---

## Checklist (Per Email)

- [ ] Friction or objection from Step 1 research addressed
- [ ] Subject line under 55 chars, not sequentially numbered
- [ ] Preview text 60-90 chars
- [ ] Opens with substance, not a greeting
- [ ] One primary CTA only
- [ ] Useful standalone without the prior emails
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Correct segment

---

## Accumulated Lessons

*Sequence open rates, click data, drop-off points, and improvements.*

<!-- Lessons will be appended here. None yet. -->
