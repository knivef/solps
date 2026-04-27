---
name: solpay-social-reddit
description: >
  Write Reddit content for SolPay Server — posts and comments across relevant subreddits.
  Use this skill for: submitting project posts to r/solana or r/selfhosted, writing
  comparison or discussion posts, drafting helpful comments in threads where SolPay is
  relevant, and answering technical questions on Reddit. Triggers on: "write a Reddit
  post about SolPay," "help me respond to this thread on r/solana," "draft something
  for r/selfhosted," "write a post for r/ecommerce about crypto payments." Always reads
  product-marketing and social-media-marketing skills first. Never writes content that
  looks promotional without disclosure.
---

# SolPay Server — Reddit Content

Reddit communities have high collective intelligence and strong antibodies against
promotional content. The SolPay Reddit strategy is built on being genuinely useful first.
Product mentions are earned, not assumed.

**Before writing any copy:** Load:
- `product-marketing/SKILL.md` — voice, pillars, positioning, banned phrases
- `social-media-marketing/SKILL.md` — community norms, Reddit-specific rules

---

## Subreddit Map

| Subreddit | Audience | Best Content Type | Promotional Tolerance |
|---|---|---|---|
| r/solana | Solana developers and users | Technical posts, project announcements | Medium — disclose affiliation |
| r/selfhosted | Open-source self-hosting enthusiasts | Project posts, setup guides, comparisons | High if genuinely useful |
| r/btcpayserver | BTCPay community | Comparison posts, Solana alternative angle | Medium — must add real value |
| r/cryptocurrency | General crypto | Industry discussion, broad payment posts | Low — avoid direct promotion |
| r/ecommerce | Online merchants | Payment alternative guides, cost comparisons | Low — educational framing only |
| r/entrepreneur | Small business owners | Use case stories, cost savings framing | Low — no direct pitching |

---

## Step 1: Subreddit and Thread Research

Before writing anything, research the target community and context.

### For new posts
- Browse the target subreddit's top posts from the past month (web search:
  `site:reddit.com/r/[subreddit] [topic]`)
- Use `web_fetch` on the most relevant existing threads to understand:
  - What questions this community already asks about payments or self-hosting
  - What tools they currently use and what pain they express
  - What tone and format earn upvotes vs. what gets flagged as spam
  - Whether a similar SolPay post already exists (avoid reposting)
- Check the subreddit's rules — fetch the sidebar or rules page if available

### For comment responses
- Use `web_fetch` on the full thread being responded to
- Read every existing comment — do not suggest something already covered
- Understand exactly what the person asking needs before drafting a response

### Research output
State before drafting:
- The specific community context (what this sub cares about, current tone)
- Whether a similar post or comment already exists
- The exact gap or question this content fills
- Any subreddit rules relevant to this post type

---

## Step 2: Post Type Selection

### Project Post (Show Reddit style)
Announcing SolPay or a major release to a community.

- Title: specific and honest. "I built a self-hosted Solana payment gateway —
  open source, here's how it works" beats "The future of payments is here."
- Body: what it is, why it was built, what problem it solves, GitHub link
- Always include: current stability stage, honest limitations, invitation for feedback
- Never start with benefits — start with the problem

**Disclosure rule:** Always disclose affiliation. "I'm one of the builders behind this."

### Comparison Post
Positioning SolPay within the landscape.

- Include genuine trade-offs — if SolPay requires more setup, say so
- If the plugin ecosystem is smaller than BTCPay, say so
- Credibility on Reddit comes from honesty about weaknesses

### Technical How-To Post
Sharing useful technical content where SolPay is the tool used.

The post is about the how-to. SolPay is the tool in the example, not the subject.
This format earns the most organic upvotes and links.

### Discussion Post
Starting a conversation where SolPay has a relevant perspective.

Do not disclose affiliation in discussion posts. Post as a genuine community member.
Do not steer aggressively toward SolPay in the comments.

### Comment Response
Answering questions in existing threads.

**The 90-10 rule:** 90% of the comment answers the question or adds value without
mentioning SolPay. 10% (one sentence, at the end if at all) mentions SolPay as an
option — only when it directly and specifically answers what the person asked.

---

## Step 3: Draft

### Title rules (for posts)
What works:
- Specific and informational: "Self-hosted Solana payment gateway — open source, MIT
  license, SPL token support"
- First-person honest: "I switched from hosted crypto checkout to self-hosted —
  here's what I learned after 3 months"
- Genuine question: "What are people actually using for Solana merchant payments right now?"

What fails:
- Hype: "Revolutionary self-hosted Solana payments"
- Vague: "New crypto payment option"
- Obviously promotional: "SolPay Server: the best way to accept Solana payments"

### Body rules
- First paragraph: why this is relevant to this community
- Middle: the substance, specific technical details, code blocks where applicable
- Trade-offs section: what it does not do, what the setup costs in time and effort
- GitHub link prominently
- Short paragraphs — Reddit reads on mobile

### Comment rules
- Answer the actual question before mentioning SolPay
- Match the technical depth of the thread
- If SolPay is not a direct answer to the question, do not force it in
- Never: "Great question! SolPay Server is perfect for this..."
- Always: answer first, then optionally: "There's also SolPay Server if you want a
  fully self-hosted option — [link]"

---

## Disclosure Standards

| Situation | Required Disclosure |
|---|---|
| Project post | Always: "I'm one of the builders" |
| Comparison post featuring SolPay | Always if affiliated |
| Comment recommending SolPay | Always: "Disclosure: I'm involved with this project" |
| Discussion post (not pitching SolPay) | Not required |
| How-to post (SolPay as example tool) | Preferred |

---

## Quality Checklist

- [ ] Target subreddit researched — existing posts and rules reviewed
- [ ] Full thread read via web_fetch before writing a comment
- [ ] No duplicate post on same topic in the subreddit recently
- [ ] Title is specific and honest — no hype
- [ ] Affiliation disclosed where required
- [ ] Trade-offs acknowledged in project and comparison posts
- [ ] GitHub link included
- [ ] No em dashes or banned phrases
- [ ] Comment follows the 90-10 rule

---

## Accumulated Lessons

*Upvote data, community reception notes, and format adjustments.*

<!-- Lessons will be appended here. None yet. -->
