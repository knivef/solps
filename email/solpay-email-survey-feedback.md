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

Survey emails fail when they feel like work. They succeed when they feel like a
straightforward ask from someone who genuinely wants the answer. SolPay survey emails
are short, specific, and honest about why the feedback is being requested.

**Before writing:** Load:
- `product-marketing/SKILL.md` — voice, banned phrases
- `email-marketing/SKILL.md` — subject strategy, tone by segment

---

## Survey Email Types

| Type | When | Goal | Format |
|---|---|---|---|
| **Post-install check-in** | 7-14 days after install | Identify setup friction and common blockers | 1 open question via reply |
| **Feature feedback** | After releasing a new feature | Understand adoption and pain points | 2-3 specific questions, link to form |
| **NPS / satisfaction** | Every 3-6 months | Gauge overall satisfaction, get promoter quotes | 1 rating question, 1 open question |
| **User research** | Before building something new | Understand the problem space | 3-5 targeted questions, link to Typeform/Tally |
| **Exit / churn** | When a user stops engaging or uninstalls | Understand why, recover where possible | 1 direct question via reply |

---

## Step 1: Confirm Scope

Before drafting, confirm:
- What decision or problem is this survey serving?
- Who is receiving it (segment)?
- How long should it take? (Under 2 minutes is the threshold for high completion.)
- Where do responses go (reply to email / Typeform / Tally / Google Form)?
- What will be done with the responses (this goes in the email — transparency increases completion)?

---

## Step 2: Draft the Survey Email

### Subject line for survey emails
Be honest about what this is. "Quick question" outperforms "Important survey — take 5 minutes."

Patterns that work:
- "One question about your SolPay setup"
- "2 minutes: what's working and what isn't with SolPay?"
- "Quick question about [specific feature]"
- "Did you get stuck anywhere?" (post-install)

Patterns that do not work:
- "We'd love your feedback!" (vague, low urgency)
- "Customer Satisfaction Survey — Q2 2025" (sounds like corporate admin)
- "Your opinion matters to us" (used so often it has no meaning)

### Body structure

**Line 1:** What you're asking and why. One sentence. Be honest.
"We're deciding whether to build a native Shopify integration, and we want to hear
from merchants who've tried the current workaround."

**Lines 2-3:** The actual question(s). Direct. Specific.
"Two questions:
1. Are you currently using SolPay with Shopify? If yes, how did you set it up?
2. What is the most annoying part of that setup right now?"

**Line 4:** How long it takes and what you'll do with the answers.
"Takes 2 minutes. Responses will directly influence what we build next."

**CTA:** Reply directly (for one-question emails) or link to form (for multi-question).

**Sign-off:** From a real person. Offer to reply.

### For longer surveys (form link)

Do not put all the questions in the email. The email's job is to get them to the form.
Mention the number of questions and the estimated time. That is all.

"We have 5 questions about how you're using SolPay for high-volume invoicing. Takes
about 3 minutes. Your answers will shape what we prioritize in Q3."

[Take the survey]

---

## Step 3: The Actual Survey Questions

If asked to draft the survey questions themselves (for use in a form), follow these rules:

- **Maximum 7 questions** for any survey. If you need more, run two separate surveys.
- Mix of question types: 1-2 rating or scale questions, 2-4 open text questions, 1
  multiple choice at most
- Each question asks one thing only. "How easy was the setup and how would you rate
  the documentation?" is two questions.
- Open questions are more useful than multiple choice for product decisions. Use them.
- Always include one "Is there anything else you want us to know?" at the end.
- Never include leading questions: "How much do you love the new dashboard?" is not neutral.

### NPS format (if requested)

Question 1: "On a scale of 0-10, how likely are you to recommend SolPay Server to
another developer or merchant?"

Question 2 (conditional on score):
- Score 9-10: "What's the main reason you'd recommend SolPay?"
- Score 7-8: "What would make SolPay more valuable for you?"
- Score 0-6: "What's the biggest thing holding you back from recommending SolPay?"

---

## Checklist

- [ ] Subject line specific and honest about what's being asked
- [ ] Opens with why the feedback is being requested
- [ ] Questions are specific and answerable
- [ ] Time estimate is accurate (and short)
- [ ] What will be done with responses is mentioned
- [ ] CTA is clear: reply or link to form
- [ ] No em dashes or double hyphens
- [ ] No banned phrases or corporate survey language
- [ ] Sent from a real person who can receive replies

---

## Accumulated Lessons

*Append completion rate data, response quality notes, and question format improvements here.*

<!-- Lessons will be appended here. None yet. -->
