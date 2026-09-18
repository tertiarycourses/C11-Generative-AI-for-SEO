# Prompt Pack — Lab 6: Generate Image, Video and LinkedIn Assets

Replace bracketed fields with verified inputs. Never paste personal, confidential, licensed or credential data into a tool without authority.

## Prompt 1 — CONTEXT task prompt

> **Context:** You support EcoDesk, a fictional Singapore sustainable-office-products business. Audience: [role]. Page/task: [page]. Brand facts: [verified facts only].  
> **Objective:** [one measurable outcome].  
> **Necessary inputs:** [paste source text/data with source and date].  
> **Task steps:** Create an image brief, six-scene video storyboard, transcript outline and LinkedIn post. Avoid logos, creator imitation, manipulated backlinks and unsupported claims.  
> **Evidence:** Cite the exact supplied row, page element or source for every material conclusion. Separate observation, inference and recommendation.  
> **eXclusions:** No invented metrics, rankings, citations, testimonials, prices, certifications, environmental benefits or legal claims. No keyword stuffing, link schemes or private data.  
> **Template:** Return findings/options, evidence, uncertainty, recommendation, human checks and acceptance checklist.

## Prompt 2 — Adversarial quality review

> Act as a critical SEO editor. Review intent, accuracy, originality, clarity, brand, accessibility, Google Search policies and the lab acceptance test. Return issue, severity, evidence, correction and reviewer decision.

## Prompt 3 — Human approval summary

> Prepare a change preview. Show affected files/fields, before/after meaning, evidence, limitations, tests, risks, rollback and an approve/revise/reject recommendation. Do not publish.

## Field-tested prompt templates

Published templates from [AI Prompts for SEO Meta Tags & LinkedIn Posts (Templates)](https://www.tertiarycourses.com.sg/blog/ai-prompts-seo-meta-linkedin-posts). Off-page reach is earned with standalone value; these four cover the post types this lab produces.

Every template follows the same five-part skeleton — it is the skeleton, not the tool, that does the work:

| Part | What it does |
|---|---|
| Role | Tell the model what it is ("you are an SEO copywriter"), which sets vocabulary and priorities. |
| Context | The page, audience, keyword and differentiator. The model cannot know your business; feed it. |
| Constraints | Character limits, banned phrases, tone rules. Constraints are what separate usable output from slop. |
| Format | Ask for a table or labelled options so the output drops straight into your workflow. |
| Guardrail | An explicit instruction not to invent facts, and to ask when information is missing. |

Replace the [BRACKETED] fields with verified inputs before running any template below.

### Template 1 — Turn an article into a LinkedIn post

The most common repurposing job. The two rules that matter most: the hook must survive the "…see more" fold, and the post must contain one concrete number so it reads like experience rather than content marketing.

```text
Turn the article below into a LinkedIn post for my company page.

Structure:
- Hook: the first 2 lines must work before the "...see more" fold -
  no throat-clearing
- Body: 3-5 short paragraphs, one idea each, plain English
- Include one concrete example or number from the article
- CTA: one line inviting readers to the full article at [URL]
- 3-5 hashtags: one broad, the rest niche

Rules: no emojis in the first line, never open with "I'm excited to
share", 150-220 words total.

[PASTE ARTICLE OR KEY POINTS]
```

**What to check:** The concrete number must come from the article, not from the model. If the article has no number, the honest fix is to add one to the article first.

**In this lab:** Feed it the EcoDesk guide page. The post must seek earned attention only — no reciprocal-link request, no paid placement, no engagement pod.

### Template 2 — A first-person post from something you learned

Personal posts outperform company posts on LinkedIn, and the guardrail line here is the difference between authentic and invented.

```text
Write a first-person LinkedIn post based on this experience:

What happened: [1-3 SENTENCES ON WHAT YOU DID OR LEARNED]
Who it helps: [AUDIENCE]
The takeaway: [THE ONE THING READERS SHOULD REMEMBER]

Rules:
- Open with the moment of surprise or failure, not the lesson
- Short lines, generous white space, max 3 hashtags
- Do NOT invent details - if a fact is missing, ask me instead
- End with a genuine question that invites comments, not "thoughts?"
- 120-180 words
```

**What to check:** "Do NOT invent details — ask me instead" is the line to test. If the model fills a gap silently instead of asking, the prompt failed and the output is unusable.

**In this lab:** Use your own real experience from this lab as the input. A first-person post attributed to a person must not be built from fictional EcoDesk events.

### Template 3 — Announcing a course run, webinar or event

Announcement posts die when they lead with the thing instead of the problem. This template forces the order right.

```text
Write a LinkedIn post announcing this course run for a company page.

Course: [COURSE NAME]
Date and format: [DATE, CLASSROOM / ONLINE]
Who it is for: [AUDIENCE]
Registration link: [URL]

Rules:
- Lead with the problem the course solves, not the course name
- One line on what participants build or walk away with
- Single CTA line with the link, under 150 words, max 4 hashtags
```

**What to check:** Every concrete claim in the post must be verifiable against the live page before posting.

**In this lab:** Adapt it to the EcoDesk guide launch instead of a course. Any figure you cannot evidence from the page is an invented claim.

### Template 4 — One article, five posts — a week of content

Repurposing is where consistency comes from. Asking the model to vary the format across the week stops your feed reading like a template.

```text
Take the article below and plan 5 LinkedIn posts from it, one per
weekday.

For each post give: the angle, the opening hook line, and 2-3 bullet
points of body content. Vary the format across the week: one how-to,
one contrarian take, one mini case study, one list post, one question
post. Never repeat the same hook structure twice.

Flag which single post you would put paid spend behind, and why.

[PASTE ARTICLE]
```

**What to check:** The paid-spend recommendation is a judgement, not a finding — the model has no performance data. Treat it as one hypothesis to test against your own past post metrics.

**In this lab:** The "mini case study" slot is the trap: EcoDesk has no customer results, so that post must be reframed as a worked example or dropped with a reason recorded.

## Pre-publish checklist

Whatever the prompt produced, it goes through the same 60-second review before it ships.

| Check | Why it matters |
|---|---|
| Character/pixel limits verified in a real checker | Models miscount; Google truncates at pixel width, not characters. |
| Every number and claim confirmed true | Fabricated specifics are the most common AI failure — and the most damaging. |
| Primary keyword present and early | The one on-page signal a meta rewrite must never lose. |
| Reads differently from your last five outputs | Repeated AI phrasing across pages and posts is what "thin content" looks like at scale. |
| A named human edited it | Generation is a drafting step, not a publishing pipeline. |

These templates are model-agnostic: the same wording works in ChatGPT, Claude, Gemini and Copilot.

## Prompt usage record

| Field | Record |
|---|---|
| Tool/model | |
| Date/time | |
| Prompt version | v15.0 |
| Input sources | |
| Reviewer | |
| Decision | Approve / Revise / Reject |
| Human changes | |
