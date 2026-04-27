---
name: solpay-email-product
description: >
  Write product and announcement emails for SolPay Server. Use this skill for feature
  release emails, changelog announcements, integration launch emails, and any email that
  tells the subscriber list about something new. Triggers on: "write an email announcing
  [feature]," "draft the release email for [version]," "email subscribers about the new
  [integration]," "announce [X] to the list." Always reads the product-marketing and
  email-marketing skills first.
---

# SolPay Server — Product and Announcement Email

Product emails have one job: get the right subscribers to understand what changed and
take the next step. Short, direct, and respectful of the reader's time.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, pillars, audience, banned phrases
- `email-marketing/SKILL.md` — subject line strategy, structure, tone by segment

---

## Step 1: Research and Fact Verification

Before drafting, verify all claims about the feature or update being announced.

- Fetch the relevant SolPay changelog entry, GitHub release notes, or pull request
- Confirm: what exactly changed, what the new behavior is, what the old behavior was
- For integration announcements: fetch the third-party platform's documentation to
  confirm compatibility details are accurate
- For breaking changes: confirm exactly what the user needs to do and in what order

Do not draft an announcement email from memory or a brief summary. Factual errors in
product emails damage trust and generate support tickets.

**State before drafting:**
- Feature or change: [confirmed description from source]
- Affected segment: [who this email goes to]
- One required action (if any): [specific step the reader must take]
- Link destination: [changelog, docs, or GitHub release URL]

---

## Step 2: Draft

### Subject line
`[What changed, specifically] — [why it matters or what to do]`

Examples:
- "SolPay 0.5 is live — webhook format changed, here's what to update"
- "WooCommerce plugin v1.2: SPL token support added"
- "New: accept USDT directly in your SolPay instance"

Preview text: adds detail the subject line leaves out. 60-90 characters.

### Body structure

**Line 1:** State what happened. "SolPay Server 0.5 shipped today."
No "We are excited to announce." No "Great news."

**Lines 2-4:** What changed, specifically. Use the verified details from Step 1.

**One paragraph:** Why it matters — connect the change to a real use case.

**One primary action:** "Update your instance," "Install the plugin," "Check the
migration guide." One link. Make it obvious.

**Optional secondary link:** Changelog or docs for readers who want more detail.

**Sign-off:** Short. From a person.

### For breaking change emails
Lead with the impact, not the feature name. The reader needs to know action is required.

> **Heads up: this update changes the webhook format.**
> If you are on SolPay 0.4.x, update your webhook handler before upgrading.
> Here is what changed and how to update.

Do not bury breaking changes in a list of improvements.

---

## Step 3: Checklist

- [ ] Feature details verified from changelog, GitHub, or official docs
- [ ] Subject line under 55 characters, specific
- [ ] Preview text 60-90 characters, adds new info
- [ ] Email opens with the announcement, not a filler opener
- [ ] No em dashes or double hyphens
- [ ] No banned phrases
- [ ] One primary CTA with one link
- [ ] Breaking changes flagged prominently if applicable
- [ ] Sent from a person, not "The SolPay Team"
- [ ] Segment matches the content

---

## Accumulated Lessons

*Open rate data, CTA performance, and segment response notes.*

<!-- Lessons will be appended here. None yet. -->
