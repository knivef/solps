---
name: solpay-email-survey
description: >
  Write survey emails for SolPay Server. Use this skill for feedback surveys, NPS emails,
  user research requests, post-install check-ins, and any email that asks subscribers or
  users for input. Triggers on: "write a survey email for [goal]," "create an NPS survey
  email," "draft an email asking users about [topic]," "write a feedback request email,"
  "I want to ask merchants about [X]." Always reads the product-marketing and
  email-marketing skills first.
---

# SolPay Server — Survey and Feedback Emails

Survey emails succeed when they feel like a direct ask from someone who genuinely wants
the answer. They fail when they feel like corporate admin.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, banned phrases
- `email-marketing/SKILL.md` — subject strategy, tone by segment

---

## Step 1: Research What to Ask

Before writing the email or the survey questions, understand what decisions the
survey is meant to inform.

- If the goal is to improve the setup experience: fetch SolPay's GitHub issues and
  discussions to identify what problems already come up repeatedly — these become
  the specific questions, not vague "how was your experience?" prompts
- If the goal is to understand merchant objections: web search for "why merchants
  don't accept crypto payments" and similar queries — understand what objections
  already exist in the broader market before asking your own users
- If the goal is NPS or satisfaction: identify the 1-2 most important product moments
  to ask about — not generic satisfaction, but specific to what matters for SolPay
  (e.g., time from install to first live payment)

**State before drafting:**
- The decision this survey informs: [specific product or content decision]
- The 2-3 highest-value questions based on the research above
- What will be done with the responses (this goes in the email)

---

## Step 2: Draft the Survey Email

### Subject line
Be honest about what this is.

Works:
- "One question about your SolPay setup"
- "2 minutes: what's working and what isn't with SolPay?"
- "Quick question about [specific feature]"
- "Did you get stuck anywhere?" (post-install)

Does not work:
- "We'd love your feedback!"
- "Customer Satisfaction Survey — Q2 2025"
- "Your opinion matters to us"

### Body structure

**Line 1:** What you're asking and why. One sentence. Be honest.
"We're deciding whether to build a native Shopify integration and want to hear from
merchants who've tried the current workaround."

**Lines 2-3:** The actual questions. Direct and specific. Based on the research in Step 1.

**Line 4:** How long it takes and what you'll do with the answers.
"Takes 2 minutes. Responses go directly into our Q3 roadmap."

**CTA:** Reply directly (for single-question emails) or link to form.

**Sign-off:** From a real person. Offer to reply.

### For longer surveys (form link)
Do not put all the questions in the email. The email's job is to get them to the form.
Mention the number of questions and estimated time only.

---

## Step 3: Survey Questions (If Requested)

Rules for the actual form questions:
- Maximum 7 questions
- Mix: 1-2 rating/scale, 2-4 open text, 1 multiple choice at most
- Each question asks one thing only
- Open questions are more useful than multiple choice for product decisions
- Always end with "Is there anything else you want us to know?"
- No leading questions

### NPS format
Question 1: "On a scale of 0-10, how likely are you to recommend SolPay Server to
another developer or merchant?"

Question 2 (conditional):
- Score 9-10: "What's the main reason you'd recommend SolPay?"
- Score 7-8: "What would make SolPay more valuable for you?"
- Score 0-6: "What's the biggest thing holding you back from recommending SolPay?"

---

## Checklist

- [ ] Research done — questions are grounded in real friction or known decisions
- [ ] Subject line specific and honest
- [ ] Email states why the feedback is being requested
- [ ] Questions are specific and answerable
- [ ] Time estimate accurate and short
- [ ] What will be done with responses is stated
- [ ] CTA is clear: reply or form link
- [ ] No em dashes or double hyphens
- [ ] No corporate survey language
- [ ] Sent from a real person

---

## Accumulated Lessons

*Completion rate data, response quality notes, and question format improvements.*

<!-- Lessons will be appended here. None yet. -->
