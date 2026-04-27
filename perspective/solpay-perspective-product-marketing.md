---
name: solpay-product-marketing
description: >
  Core product marketing reference for SolPay Server. Load this skill whenever creating
  any content for SolPay Server — blogs, social posts, emails, or copy. It provides the
  brand positioning, narrative pillars, audience segments, voice rules, competitive context,
  and messaging guardrails that every other SolPay content skill builds on. Do not write
  a single piece of SolPay content without reading this first.
---

# SolPay Server — Product Marketing Reference

SolPay Server is a self-hosted, open-source Solana payment gateway. Merchants and
individuals run it on their own servers and own their entire payments stack: private keys,
transaction history, settlement logic, and customer data. No middleman. No custodial risk.
No platform-level surveillance.

Think BTCPay Server, rebuilt for the speed and cost structure of Solana.

---

## What SolPay Server Actually Does

- Accepts SOL, USDC, USDT, and other SPL tokens natively
- Generates unique deposit addresses per transaction (no address reuse)
- Self-hosted: the merchant controls the node, the keys, the data
- Integrates with e-commerce platforms (WooCommerce, Shopify via API, custom stacks)
- Provides a payment gateway interface with invoices, payment buttons, and webhooks
- Supports Lightning-fast finality: Solana confirmations in under 2 seconds
- No percentage fees taken by SolPay itself — merchant pays only Solana network fees
- Open source: the code is auditable and forkable

---

## Narrative Pillars

Every piece of SolPay content anchors to one of these three pillars. Choose the primary
one based on the audience and topic, then weave the secondary in lightly.

### Pillar 1: Sovereignty and Self-Custody
**Core idea:** When you use a hosted payment gateway, you're a tenant. When you run SolPay
Server, you own the building. Your keys, your rails, your rules.

**Relevant keyword territory:** "self-hosted crypto payments," "non-custodial payment
gateway," "self-custody Solana payments," "own your payment stack," "BTCPay Server Solana
alternative"

**Audience resonance:** Cypherpunks, privacy-conscious merchants, operators who've been
deplatformed, crypto-native developers, libertarian-leaning solopreneurs.

### Pillar 2: Speed and Cost on Solana
**Core idea:** Bitcoin payments have finality in 10 minutes and fees that spike with
congestion. Solana settles in under 2 seconds for fractions of a cent. SolPay puts that
infrastructure in your hands.

**Relevant keyword territory:** "Solana payment gateway," "fast crypto payments," "low fee
crypto checkout," "USDC payments Solana," "accept SPL tokens," "Solana merchant payments"

**Audience resonance:** E-commerce merchants who've tried BTC payments and hated the UX,
developers building on Solana, DeFi users familiar with Solana's throughput.

### Pillar 3: Permissionless Commerce
**Core idea:** Stripe, PayPal, and Square decide who gets to sell. SolPay Server is code.
It does not have a Terms of Service enforcement department. High-risk verticals, global
merchants, and anyone who's been told "no" by a payment processor should know this exists.

**Relevant keyword territory:** "accept crypto without KYC," "payment gateway for high risk
merchants," "permissionless payments," "no payment processor approval needed," "crypto
checkout for restricted categories"

**Audience resonance:** High-risk merchants (iGaming, CBD, adult, firearms, supplements),
globally distributed sellers, merchants in countries underserved by card networks.

---

## Audience Segments

### Crypto-Native Developers
- **Pain:** Existing payment integrations are clunky, custodial, and centralized. They
  want to build with real Solana tooling, not a wrapper that abstracts away the chain.
- **Message:** Open-source, webhook-driven, full API access. Set it up, fork it, break it.
  It's yours.
- **Tone:** Technical, peer-level, no hand-holding. Respect the intelligence.

### E-Commerce Merchants (Crypto-Curious)
- **Pain:** Card processor fees (2.9% + $0.30), chargebacks, fund freezes, monthly costs.
  They've heard crypto payments are faster and cheaper but don't know where to start.
- **Message:** Self-hosted means no ongoing fees to SolPay. Solana means settlement in
  seconds, not days. USDC means no volatility. WooCommerce plugin takes 20 minutes.
- **Tone:** Practical, benefit-first, low on jargon.

### High-Risk and Deplatformed Merchants
- **Pain:** They've been turned down by Stripe. Or had their accounts frozen. Or operate
  in a country that's geo-blocked. They need infrastructure that doesn't ask questions.
- **Message:** SolPay Server is software. It doesn't approve or deny applications. It
  doesn't freeze accounts. If you can run a server, you can accept payments.
- **Tone:** Direct, honest, no glossing over the reality. This audience has been burned
  before and has a low tolerance for marketing speak.

### Solopreneurs and Indie Builders
- **Pain:** Monthly SaaS fees for payment gateways add up. They want to own the stack
  without paying per-transaction fees to a third party.
- **Message:** Run it on a $5/month VPS. Accept USDC directly. Zero SolPay cut.
- **Tone:** Builder-to-builder, pragmatic, occasionally irreverent.

### Web3 / DeFi Projects
- **Pain:** Their users are already on Solana. They need native payment tooling that
  doesn't route through a bank or a CEX.
- **Message:** Native SPL token support, unique deposit addresses, webhook-driven
  architecture. Plugs directly into Solana ecosystem tooling.
- **Tone:** Technical, ecosystem-aware, assumes familiarity with wallets and DeFi.

---

## Competitive Context

SolPay Server competes in two ways: directly and by category.

### Direct Competitors
- **BTCPay Server:** The spiritual predecessor. Bitcoin-based, self-hosted. SolPay's
  pitch is Solana's speed advantage and SPL token ecosystem.
  *Do not name BTCPay negatively. Frame as: "If you know BTCPay, SolPay is the same
  philosophy on a faster chain."*
- **Coinbase Commerce / BitPay / NOWPayments:** Hosted, custodial, fee-taking services.
  Frame the contrast structurally: "hosted gateways that take a cut and hold your keys."
- **Helio / Solana Pay:** Solana-based but hosted/managed. SolPay's differentiation is
  self-hosting and full control.

### Framing Rules
- Never name hosted competitors in published content unless explicitly approved.
- Use structural framing: "hosted gateways that take custody of your funds," "platforms
  that can deactivate your account."
- BTCPay can be named neutrally as a reference point for the self-hosted model, not as
  an inferior product.

---

## Brand Voice

### What SolPay Sounds Like
- Founder-to-founder, not brand-to-customer
- Technically confident without being condescending
- Honest about trade-offs (self-hosting has operational overhead — say that)
- Opinionated about sovereignty, neutral about hype
- Conversational but not casual to the point of sloppiness

### What to Never Sound Like
- A press release ("We are excited to announce")
- A crypto hype account ("This is going to be huge")
- A vendor trying to close a deal ("Best-in-class solution")
- An AI assistant that hedges everything

### Grammar and Style Rules
- No em dashes. Rewrite sentences so they read cleanly without them.
- No double hyphens as em dash substitutes.
- Contractions preferred. "It's" not "it is."
- Short sentences. Then one longer one for rhythm. Then short again.
- Specific numbers over vague ones. "400ms finality" beats "very fast."
- Oxford comma always.
- "Onchain" not "on-chain." "Self-hosted" with a hyphen. "SPL tokens" capitalized.

### Banned Phrases
- "Game changer," "revolutionary," "cutting-edge," "innovative"
- "Excited to announce," "thrilled to share," "proud to introduce"
- "Seamless," "robust," "frictionless," "best-in-class"
- "Anonymous payments" (say "privacy-preserving" or "no KYC requirement")
- "Crypto payments are the future" (show it, don't say it)
- "Unstoppable" (overused in crypto, sounds like a slogan)
- Em dashes or double hyphens in any form

---

## Proof Points and Data

Use these to ground claims. Do not manufacture statistics.

- Solana average transaction fee: ~$0.00025
- Solana average finality: under 2 seconds (often 400-800ms)
- Solana TPS capacity: 65,000+ (theoretical); real-world sustained TPS has exceeded 2,000
- USDC on Solana: one of the largest USDC liquidity pools outside Ethereum
- BTCPay Server comparison: Bitcoin average confirmation time 10 minutes, fees variable
- Stripe standard fee: 2.9% + $0.30 per transaction
- Self-hosted advantage: zero ongoing software cost to SolPay

*Always verify current Solana network stats before publishing. Network conditions change.*

---

## CTA Framework

| Audience / Context | Primary CTA | Secondary CTA |
|---|---|---|
| Developers | "Deploy in 15 minutes" / "Read the docs" | "Star on GitHub" |
| Merchants (discovery) | "See how it works" | "Read the setup guide" |
| Merchants (ready) | "Install SolPay Server" | "Join the community" |
| High-risk segment | "Try it — no application required" | "Join the Telegram" |
| Community content | "Join us on Discord/Telegram" | "Share this" |

UTM structure for all links:
`?utm_source=[platform]&utm_medium=[channel]&utm_campaign=[campaign-slug]&utm_content=[post-slug]`

---

## Feature Verification Rule

Before asserting that SolPay Server supports a specific token, integration, or capability,
verify it in the SolPay Server documentation or GitHub repository. Do not publish
unverified feature claims. If unsure, flag for review before publishing.

---

## Accumulated Product Context

*Add product updates, positioning shifts, and new proof points here as SolPay evolves.*

<!-- Product updates will be appended here. None yet. -->
