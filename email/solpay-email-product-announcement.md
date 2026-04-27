---
name: solpay-email-product
description: >
  Write product and announcement emails for SolPay Server. Use this skill for feature
  release emails, changelog announcements, integration launch emails, and any email that
  tells the subscriber list about something new. Triggers on: "write an email announcing
  [feature]," "draft the release email for [version]," "email subscribers about the new
  [integration]," "announce [X] to the list," "write a product update email." Always
  reads the product-marketing and email-marketing skills first.
---

# SolPay Server — Product and Announcement Email

Product emails have one job: get the relevant subset of the list to understand what
changed and take the next step. They are not newsletters. They are not blog posts.
They are short, direct, and respectful of the reader's time.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `email-marketing/SKILL.md` — subject line strategy, structure, tone by segment

---

## Email Types Covered by This Skill

| Type | When | Length |
|---|---|---|
| **Feature release** | New feature shipped to users | 200-400 words |
| **Version / changelog email** | Version bump with multiple changes | 300-500 words |
| **Integration launch** | New plugin or platform integration live | 250-450 words |
| **Critical update / breaking change** | Something users must act on | 150-300 words |
| **Milestone announcement** | Significant community or product milestone | 200-400 words |

---

## Step 1: Email Brief

Before drafting, confirm:
- What is being announced?
- Who is receiving this (segment: developers / merchants / full list)?
- What should the reader do after reading?
- Is there a deadline or urgency (breaking change, limited beta, etc.)?
- Link to changelog, docs, or GitHub release?

---

## Step 2: Draft

### Subject line
Follow the subject line strategy from `email-marketing/SKILL.md`.

For product emails, the format is almost always:
`[What changed, specifically] — [why it matters or what to do]`

Examples:
- "SolPay 0.5 is live — webhook format changed, here's what to update"
- "WooCommerce plugin v1.2: SPL token support added"
- "New: accept USDT directly in your SolPay instance"

**Preview text:** adds the detail the subject line leaves out. 60-90 characters.

### Email body structure

**Line 1:** State what happened. "SolPay Server 0.5 shipped today."
No "We are excited to announce." No "Great news."

**Lines 2-4:** What changed or what is new. Be specific.
"This release adds support for USDT on Solana, a new invoice expiry UI, and fixes
the webhook retry bug reported in issue #147."

**Section: Why it matters**
One short paragraph connecting the change to a real use case or problem it solves.
Write this for the reader, not for the product.

**Section: What to do**
One primary action. "Update your instance," "Install the plugin," "Check the migration guide."
One link. Make it obvious.

**Optional secondary action:** Link to changelog or docs if the reader wants details.

**Sign-off:** Short. From a person. "Thanks for using SolPay. [Name]" or
"Happy to answer questions in the Discord. [Name]"

### For breaking change emails

Lead with the impact, not the feature. The reader needs to know this requires action.

Format:
> **Heads up: this update changes the webhook format.**
> If you are on SolPay 0.4.x, you will need to update your webhook handler before
> upgrading. Here is what changed and how to update.

Do not bury breaking changes in a list of other improvements.

---

## Step 3: Checklist

- [ ] Subject line under 55 characters, specific, no hype
- [ ] Preview text 60-90 characters, adds info not already in subject
- [ ] Email opens with the announcement, not a filler opener
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] One primary CTA with one link
- [ ] Breaking changes flagged prominently if applicable
- [ ] Sent from a person, not "The SolPay Team"
- [ ] Segment matches the content (developers for technical changes, merchants for
  merchant-facing features, full list for major milestones)

---

## Accumulated Lessons

*Append open rate data, CTA performance, and segment response notes here.*

<!-- Lessons will be appended here. None yet. -->
