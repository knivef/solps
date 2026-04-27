---
name: solpay-social-twitter
description: >
  Write Twitter/X content for SolPay Server. Use this skill for any tweet, thread,
  Twitter Article, or Twitter content planning. Triggers on: "draft a tweet about X,"
  "write a thread on [topic]," "write a Twitter Article about [topic]," "what should
  we post on X this week," "write something punchy about [feature]," "react to [crypto
  news] on Twitter," "write a hot take about [topic]," "plan this week's Twitter content."
  Quick single-post requests skip straight to copy. Full content planning follows the
  complete workflow. Always reads product-marketing and social-media-marketing skills first.
---

# SolPay Server — Twitter / X Content

**Before writing any copy:** Load:
- `product-marketing/SKILL.md` — voice, pillars, banned phrases
- `social-media-marketing/SKILL.md` — platform strategy, content mix, engagement rules

SolPay on Twitter sounds like a Solana developer and payments nerd who built something
real and wants to talk about it honestly. Not a brand account. Not a hype account.

---

## Quick Mode vs Full Workflow

**Quick mode** — specific tweet or thread requested:
Run Step 1 (topic research) for the specific topic, then skip to Step 4 (Copy Writing).
Do not skip the research even in quick mode — a tweet based on a misread story or stale
data is worse than no tweet.

**Full workflow** — weekly planning, content calendar, or "what should we post":
Follow all steps in order.

---

## Step 1: Topic Research

Before writing any copy, research the topic. This applies to both quick mode and full
workflow.

### For trend or news-based posts
- Web search the topic or news item
- Use `web_fetch` to retrieve the full source article or announcement — do not write
  from a headline or snippet
- Confirm the facts: what actually happened, what the real numbers are, what the
  official source says
- Identify what the mainstream crypto Twitter take already is — then find the angle
  that adds something different

### For product or feature posts
- Confirm the current state of the feature from SolPay documentation or GitHub
- Do not assert capabilities that have not been verified

### For industry commentary posts
- Search for 2-3 credible sources on the topic
- Use `web_fetch` on the most relevant one to get the full context
- Note the specific data point or quote that anchors the take

### Research output (quick, not formal)
Before writing, state in one sentence:
- What the source says (the fact)
- What the SolPay angle is (the take)

Example: "Stripe announced fee increases on international cards averaging 1.5%.
SolPay angle: self-hosted Solana payments have no platform fee layer."

---

## Step 2: Weekly Trend Pulse (Full Workflow Only)

Search for what is moving this week in:
- Solana network and ecosystem
- Stablecoin news and regulation
- Crypto payment and merchant adoption
- Payment processor policy changes (Stripe, PayPal, Coinbase Commerce)
- Open-source and self-hosted software
- High-risk merchant deplatforming events

Use `web_fetch` on the most relevant stories — not just headlines. Present 5-7 trending
topics with enough substance to build real takes:

| Topic | What's Actually Happening | SolPay Angle | Urgency |
|---|---|---|---|
| [topic] | 2-3 sentences of real detail | Specific tweet or thread concept | Hot / Warm / Evergreen |

Ask which trends to engage before planning content.

---

## Step 3: Content Calendar (Full Workflow Only)

Default cadence: 5-7 posts per week.

Content mix: 35% opinion/narrative, 25% product, 25% ecosystem, 15% community.

| Day | Format | Topic | Narrative Pillar | Research Source | Visual Needed | CTA |
|---|---|---|---|---|---|---|
| | | | | URL or "internal" | Yes / No | |

**Wait for calendar approval before writing copy.**

---

## Step 4: Copy Writing

For each post, deliver:
1. Ready-to-post copy with character count noted
2. Thread continuation tweets if applicable (numbered: 1/ 2/ etc.)
3. Visual direction if needed
4. Hashtags (1-3 max)
5. Suggested posting time

---

## Twitter Content Formats

### Short Tweet (under 200 characters)
For: hot takes, quick stats, product one-liners, reaction to news.
Every word earns its place. If the source has a specific number, use it.

### Medium Tweet (200-280 characters)
For: punchy takes that need more setup, feature hooks, questions to the audience.

### Thread (4-10 tweets)
For: explainers, walkthroughs, case studies, narrative arcs.

**Thread rules:**
- Write the hook tweet last, after the full thread is done
- Hook tweet must work standalone
- Each tweet in the thread: one idea, full stop
- Final tweet: CTA or callback to the opening
- Number format: 1/ 2/ 3/ — only in the post body
- Base every factual claim in the thread on the source researched in Step 1

### Twitter Article
For: long-form thought leadership that exceeds thread format (500-1,500 words).

**Article structure:**
- Headline: specific and honest
- Opening: the tension or problem in 1-2 sentences
- Body: organized with subheadings, short paragraphs
- Closing: clear position or call to action
- Also write the companion short tweet that promotes the article

### Quote Tweet with Commentary
For: reacting to ecosystem news, positioning without naming competitors.

**Rule:** Lead with the SolPay angle before quoting. Add something the original does not.
Never just agree.

### Poll
For: audience research, debate framing. Max once per week.
Options must be genuinely interesting — not asymmetric or leading.

---

## Writing Rules

### Voice
- No em dashes or double hyphens
- No banned phrases ("excited to announce," "game changer," etc.)
- Take a position — hedged takes die on Twitter
- Short sentences. Vary length deliberately.
- Contractions preferred
- Do not start posts with "At SolPay," "We are," or "As a self-hosted..."

### The hook rule
The hook determines whether anyone reads anything. Write it last for threads.
It must do one of:
- Surface a counterintuitive or specific fact (from the research)
- Name a pain the audience has actually felt
- Make a claim that earns a challenge or a click
- Open a loop the reader wants closed

### Numbers and specifics
Always use the actual number from the source. "Stripe raised international card fees
by 1.5%" is better than "Stripe raised fees." "$0.00025 per transaction" beats "very
low fees." Specificity signals that the take is researched, not generated.

### Hashtags
1-3 max. `#Solana` for technical posts. `#crypto` or `#payments` for merchant posts.
`#selfhosted` for sovereignty posts. Skip entirely on well-performing thread topics.

---

## CTA and UTM

All links:
`?utm_source=twitter&utm_medium=social&utm_campaign=[slug]&utm_content=[post-slug]`

| Content type | Primary CTA | Secondary |
|---|---|---|
| Product feature | "Deploy in 15 minutes" | "Read the docs" |
| Setup / install | "Get started" | "Star on GitHub" |
| Industry post | "What's your take?" | "Read the full breakdown" |
| Community | "Join the Discord" | "Follow for updates" |

---

## Visual Direction Format

For posts requiring visuals:
- **Concept:** what the image should show
- **Format:** static / GIF / screenshot / infographic
- **Text overlay:** exact copy (5-10 words max)
- **Style:** clean technical / data visual / typographic / product UI screenshot
- **Alt text:** written out

No crypto-cliche visuals (no rockets, moons, handshakes over blockchains).

---

## Quality Checklist

- [ ] Topic researched via web search and web_fetch before writing
- [ ] Every factual claim verified against source
- [ ] No em dashes or double hyphens
- [ ] No banned phrases or filler openers
- [ ] Hook earns the read (written last for threads)
- [ ] Each thread tweet works standalone
- [ ] Hashtags within limit
- [ ] UTM on every link
- [ ] Visual direction provided where needed

---

## Accumulated Lessons

*Engagement data, format performance, and tone adjustments after each review cycle.*

<!-- Lessons will be appended here. None yet. -->
