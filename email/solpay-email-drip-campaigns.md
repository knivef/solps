---
name: solpay-email-drip
description: >
  Write email drip campaigns and onboarding sequences for SolPay Server. Use this skill
  for building multi-email sequences: new user onboarding, post-install nurture,
  merchant activation sequences, re-engagement campaigns, and any multi-touch email
  workflow. Triggers on: "write an onboarding email sequence," "create a drip campaign
  for [goal]," "build a nurture sequence for new signups," "write the welcome series,"
  "draft the activation emails for new merchants." Always reads the product-marketing
  and email-marketing skills first.
---

# SolPay Server — Email Drip Campaigns and Sequences

Drip campaigns work when each email has one job and that job connects logically to the
next email in the sequence. A sequence with six emails trying to do everything is worse
than a sequence with three emails that each land.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `email-marketing/SKILL.md` — subject strategy, structure rules, tone by segment

---

## Core Sequences

### Sequence 1: Developer Onboarding (Post-Install or GitHub Star)
**Trigger:** User installs SolPay or stars the GitHub repo
**Segment:** Developers
**Goal:** Get them to a working instance accepting a test transaction
**Length:** 4 emails over 10 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "You installed SolPay — here's how to get it live" | First activation: from install to working instance |
| 2 | Day 2 | "The one config thing most people get wrong" | Reduce setup friction on the most common stumbling block |
| 3 | Day 5 | "Your first live transaction on Solana" | Get them to process a real payment |
| 4 | Day 10 | "What's next: webhooks, plugins, and going further" | Unlock advanced usage, invite to community |

### Sequence 2: Merchant Evaluation Nurture
**Trigger:** Merchant signs up to newsletter or downloads a guide without installing
**Segment:** Merchants (evaluating)
**Goal:** Move them from evaluating to installing
**Length:** 5 emails over 14 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "What SolPay Server actually does (plain language)" | Clear, honest product explainer. No jargon. |
| 2 | Day 3 | "How much are you actually paying in card fees?" | Surface the cost problem. No CTA beyond thinking about it. |
| 3 | Day 7 | "A store owner's first month on SolPay — what they said" | Social proof / case study |
| 4 | Day 10 | "The 3 questions merchants ask before switching to crypto payments" | Address objections |
| 5 | Day 14 | "Ready to try it? Here's the easiest starting point" | Direct install CTA |

### Sequence 3: Post-Install Merchant Activation
**Trigger:** Merchant installs SolPay but has not processed a live transaction after 7 days
**Segment:** Merchants (active but stuck)
**Goal:** Get them to a live, revenue-generating setup
**Length:** 3 emails over 7 days

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 7 | "You installed SolPay — are you stuck anywhere?" | Check in, surface friction, link to help |
| 2 | Day 10 | "The fastest path from install to live payments" | Simplified activation guide |
| 3 | Day 14 | "Here if you want a hand" | Human offer of help, Discord invite |

### Sequence 4: Re-Engagement
**Trigger:** Subscriber has not opened or clicked in 90 days
**Segment:** Full inactive list
**Goal:** Either re-engage or clean the list
**Length:** 2 emails, then remove if no response

| Email | Timing | Subject | Job |
|---|---|---|---|
| 1 | Day 0 | "Still interested in self-hosted Solana payments?" | Re-engage with a relevant value hook |
| 2 | Day 7 | "Last one from us — unless you want to stay" | Final send, clear unsubscribe, list hygiene |

---

## Step 1: Sequence Selection and Customization

1. Identify which sequence applies, or confirm a custom sequence is needed
2. Confirm the trigger event and the subscriber segment
3. Confirm the primary goal (activation, conversion, re-engagement)
4. Adjust timing if needed (faster for urgent product moments, slower for nurture)

---

## Step 2: Draft Each Email

Follow the structure from `email-marketing/SKILL.md` for each email:

**Per-email brief:**
- What is the one job of this email?
- What does the reader know at this point in the sequence?
- What objection or friction does this email address?
- What is the one primary CTA?

**Writing rules across all drip emails:**
- Each email is complete and useful on its own — a subscriber who missed email 2 can
  still benefit from email 3
- No em dashes or double hyphens
- No banned phrases
- Short paragraphs
- One primary CTA per email, no more
- Reference the previous email only if it is genuinely useful context — do not make
  reading all emails a prerequisite

### Subject line approach for sequences
Each subject line must earn the open independently. Sequences where every subject line
starts with "SolPay Update #3" train readers to ignore them.

Vary the approach:
- Question format: "Are you stuck on the webhook setup?"
- Benefit format: "Accepting live Solana payments in the next 20 minutes"
- Honest check-in: "You haven't processed a transaction yet — is something off?"
- Curiosity format: "The config most new installs get wrong"

---

## Step 3: Sequence Map

For any sequence (new or from the library above), produce a sequence map before writing:

```
Sequence: [Name]
Trigger: [What starts it]
Segment: [Who receives it]
Goal: [What success looks like]

Email 1 — [Timing]
  Subject: [Draft]
  Preview: [Draft]
  Job: [One sentence]
  CTA: [Specific action]

Email 2 — [Timing]
  [Same structure]

...
```

**Wait for sequence map approval before drafting emails.**

---

## Checklist for Each Email in the Sequence

- [ ] Subject line under 55 chars, specific, not sequential-sounding
- [ ] Preview text 60-90 chars, adds new info
- [ ] Opens with substance, not a filler greeting
- [ ] One primary CTA only
- [ ] Useful standalone even if the reader missed earlier emails
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] Correct segment (do not send developer content to merchants)

---

## Accumulated Lessons

*Append sequence open rates, click data, drop-off points, and improvements here.*

<!-- Lessons will be appended here. None yet. -->
