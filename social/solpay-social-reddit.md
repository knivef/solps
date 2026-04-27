---
name: solpay-social-reddit
description: >
  Write Reddit content for SolPay Server — posts and comments across relevant
  subreddits. Use this skill for: submitting project posts to r/solana or r/selfhosted,
  writing "Show HN" style posts, creating comparison or discussion posts, drafting
  helpful comments in threads where SolPay is relevant, answering technical questions
  on Reddit, and building organic community presence. Triggers on: "write a Reddit post
  about SolPay," "help me respond to this thread on r/solana," "draft something for
  r/selfhosted," "write a post for r/ecommerce about crypto payments," "create a
  community post about [topic]." Always reads product-marketing and social-media-marketing
  skills first. Never writes content that looks promotional without disclosure.
---

# SolPay Server — Reddit Content

Reddit communities are not a broadcast channel. They are conversations with high
collective intelligence and strong antibodies against promotional content. The SolPay
Reddit strategy is built on being genuinely useful first. Product mentions are earned,
not assumed.

**Before writing any copy:** Load:
- `product-marketing/SKILL.md` — voice, pillars, positioning, banned phrases
- `social-media-marketing/SKILL.md` — community norms, Reddit-specific rules

---

## Subreddit Map

| Subreddit | Audience | Best Content Type | Promotional Tolerance |
|---|---|---|---|
| r/solana | Solana developers and users | Technical posts, project announcements, comparisons | Medium — disclose affiliation |
| r/selfhosted | Open-source self-hosting enthusiasts | Project posts, setup guides, comparisons with hosted alternatives | High if genuinely useful |
| r/btcpayserver | BTCPay community | Comparison posts, "Solana alternative" angle | Medium — must add genuine value |
| r/cryptocurrency | General crypto | Industry discussion, broad payment posts | Low — avoid direct promotion |
| r/ecommerce | Online merchants | Payment alternative guides, cost comparison | Low — educational framing only |
| r/entrepreneur | Small business owners | Use case stories, cost savings framing | Low — no direct pitching |
| r/fintech | Fintech enthusiasts | Infrastructure and technical angle | Medium — analytical tone |

---

## Content Types

### Project Post (Show Reddit style)
For: announcing SolPay Server to a relevant community for the first time, or announcing
a major release.

Format:
- Title: specific, honest, no hype. "I built a self-hosted Solana payment gateway —
  here's how it works" beats "The future of payments is here"
- Body: what it is, why you built it, what problem it solves, link
- Always include: what stage it's at (early, stable, production-ready), where to find
  it (GitHub), and an invitation for feedback
- Never start with product benefits. Start with the problem.

**Disclosure rule:** Always disclose affiliation in project posts. "I'm one of the builders
behind this" or "Full disclosure: I built this." Reddit will surface it if you don't.

### Comparison Post
For: positioning SolPay within the self-hosted or Solana payment landscape.

Example angles:
- "Self-hosted Solana payments: what your options actually are in 2025"
- "Tried three Solana payment gateways — here's the honest comparison"
- "Why I moved from [hosted solution] to SolPay Server"

**Rule:** Include genuine trade-offs. If SolPay requires more setup than a hosted
alternative, say that. If it has a smaller plugin ecosystem than BTCPay, say that.
Credibility on Reddit comes from honesty about weaknesses, not from puffing strengths.

### Technical How-To Post
For: sharing genuinely useful technical content that mentions SolPay as the tool used.

Example: "How to set up a self-hosted USDC payment gateway on a $5 VPS — step by step"

The post is about the how-to, not about SolPay. SolPay is the tool used in the example.
This is the highest-value Reddit content type for SolPay — it earns upvotes and organic
links.

### Discussion / Question Post
For: starting a conversation about a topic where SolPay has a relevant perspective.

Example: "Has anyone else noticed how few good self-hosted payment options there are for
Solana? Curious what others are using."

Do not disclose affiliation in discussion posts. Post as a genuine community member.
Do not steer aggressively toward SolPay in the comments. Let it come up naturally.

### Comment (Response to Existing Thread)
For: answering questions or adding value in threads where SolPay is relevant.

**The 90-10 rule for comments:** 90% of the comment answers the question or adds value
without mentioning SolPay. 10% (one sentence, at the end if at all) mentions SolPay
as an option — only when it directly addresses what the person asked about.

Example thread: someone asks "Are there any self-hosted Solana payment processors?"
Correct response: answer their question fully, explain the landscape, mention SolPay as
one of the options with a link. Do not write a sales pitch.

---

## Step 1: Post Type and Subreddit Selection

1. Identify the post type from the options above
2. Select the subreddit based on the map (do not post the same content to multiple
   subreddits on the same day — this is considered spam)
3. Check the subreddit's posting rules (some require flair, some have link restrictions)
4. Confirm there is not already a recent SolPay post in that subreddit (avoid flooding)

---

## Step 2: Draft

### Title rules
Reddit titles are critical — they determine upvotes before anyone reads the post.

What works:
- Specific and informational: "Self-hosted Solana payment gateway with SPL token support
  — open source, MIT license"
- Honest and first-person: "I switched from Stripe to a self-hosted setup for my store —
  here's what I learned after 3 months"
- Question format that invites genuine discussion: "What are people actually using for
  Solana merchant payments right now?"

What never works:
- Hype: "Revolutionary self-hosted payment solution for Solana"
- Vague: "New crypto payment option"
- Obvious promotional framing: "SolPay Server: the best way to accept Solana payments"

### Body rules
- First paragraph: the context or problem. Why is this relevant to this community?
- Middle: the substance. What does it do? How does it work? Specifics.
- Code blocks where relevant — Reddit developers love them
- Trade-offs section: what it does not do, what the setup costs in time and effort
- Link to GitHub prominently — open source credibility matters in self-hosted communities
- Short paragraphs. Reddit reads on mobile.
- Do not use em dashes or banned phrases even here.

### Comment rules
- Answer the actual question before mentioning SolPay
- Match the technical level of the thread
- If SolPay is not a direct answer to the question being asked, do not force it in
- Never: "Great question! SolPay Server is perfect for this..."
- Always: answer first, then optionally: "There's also [SolPay Server] if you want a
  fully self-hosted Solana option — link here"

---

## Disclosure Standards

| Situation | Required Disclosure |
|---|---|
| Project post | Always: "I'm one of the builders" or "full disclosure: I built this" |
| Comparison post featuring SolPay | Always if you're affiliated |
| Comment recommending SolPay | Always: "Disclosure: I'm involved with this project" |
| Discussion post (not pitching SolPay) | Not required |
| How-to post (SolPay as example tool) | Disclosure preferred but not always required |

Failing to disclose gets the content flagged as spam and damages the project's reputation
in communities. Always disclose when in doubt.

---

## Quality Checklist

- [ ] Subreddit rules checked
- [ ] No same-day cross-posting to multiple subs
- [ ] Title is specific and honest — no hype
- [ ] Affiliation disclosed where required
- [ ] Trade-offs acknowledged in the post
- [ ] GitHub link included
- [ ] No em dashes or banned phrases
- [ ] Comment follows the 90-10 rule (value first, SolPay mention is the 10%)
- [ ] Link to SolPay is to the actual project page, not a marketing landing page

---

## Accumulated Lessons

*Append upvote data, community reception notes, and format adjustments here.*

<!-- Lessons will be appended here. None yet. -->
