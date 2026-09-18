# Prompt Pack — Lab 7: Generate and Implement On-Page SEO Meta

Replace bracketed fields with verified inputs. Never paste personal, confidential, licensed or credential data into a tool without authority.

## Prompt 1 — CONTEXT task prompt

> **Context:** You support EcoDesk, a fictional Singapore sustainable-office-products business. Audience: [role]. Page/task: [page]. Brand facts: [verified facts only].  
> **Objective:** [one measurable outcome].  
> **Necessary inputs:** [paste source text/data with source and date].  
> **Task steps:** Generate five accurate title/meta-description pairs from visible facts. Include rationale and prohibited-claim check, then draft matching social metadata and eligible JSON-LD.  
> **Evidence:** Cite the exact supplied row, page element or source for every material conclusion. Separate observation, inference and recommendation.  
> **eXclusions:** No invented metrics, rankings, citations, testimonials, prices, certifications, environmental benefits or legal claims. No keyword stuffing, link schemes or private data.  
> **Template:** Return findings/options, evidence, uncertainty, recommendation, human checks and acceptance checklist.

## Prompt 2 — Adversarial quality review

> Act as a critical SEO editor. Review intent, accuracy, originality, clarity, brand, accessibility, Google Search policies and the lab acceptance test. Return issue, severity, evidence, correction and reviewer decision.

## Prompt 3 — Human approval summary

> Prepare a change preview. Show affected files/fields, before/after meaning, evidence, limitations, tests, risks, rollback and an approve/revise/reject recommendation. Do not publish.

## Field-tested prompt templates

Published templates from [AI Prompts for SEO Meta Tags & LinkedIn Posts (Templates)](https://www.tertiarycourses.com.sg/blog/ai-prompts-seo-meta-linkedin-posts). On-page metadata is this lab's core deliverable, at single-page, section and local-intent scale.

Every template follows the same five-part skeleton — it is the skeleton, not the tool, that does the work:

| Part | What it does |
|---|---|
| Role | Tell the model what it is ("you are an SEO copywriter"), which sets vocabulary and priorities. |
| Context | The page, audience, keyword and differentiator. The model cannot know your business; feed it. |
| Constraints | Character limits, banned phrases, tone rules. Constraints are what separate usable output from slop. |
| Format | Ask for a table or labelled options so the output drops straight into your workflow. |
| Guardrail | An explicit instruction not to invent facts, and to ask when information is missing. |

Replace the [BRACKETED] fields with verified inputs before running any template below.

### Template 1 — Meta title and description for a single page

The workhorse. Asking for three options in a table forces variety and makes the character counts checkable at a glance.

```text
You are an SEO copywriter. Write 3 meta title options (max 60
characters each) and 3 meta description options (max 155 characters
each) for the page below.

Page topic: [WHAT THE PAGE IS ABOUT]
Primary keyword: [KEYWORD] - it must appear near the start of each title
Audience: [WHO SEARCHES FOR THIS]
Differentiator: [WHY THIS PAGE - e.g. price, range, location]

Rules:
- No clickbait and no claims the page cannot back up
- Include one concrete number or specific detail in each description
- End each description with a soft call to action
- Return a table: option, title, title characters, description,
  description characters
```

**What to check:** The model counts characters unreliably — paste the winner into a pixel-width checker before shipping, and confirm every claim is actually true on the page.

**In this lab:** Run it on the EcoDesk product page. Every claim must trace to visible page content; EcoDesk has no published price, rating, certification or environmental result to cite.

### Template 2 — Bulk metas for a whole section of the site

Where AI genuinely changes the economics: a hundred course or product pages that would take a week by hand take an afternoon with review.

```text
You are an SEO assistant. I will paste a table of URLs with columns:
URL, page type, primary keyword, current meta title.

For each row write a new meta title (max 60 chars) and meta
description (max 155 chars).

Rules:
- Keep each row's primary keyword in the first half of the title
- Never reuse the same opener twice - vary the phrasing across rows
- Append " | [BRAND]" only where it still fits the limit
- Flag any two rows that target the same query (cannibalisation risk)
- Return one table I can paste into a spreadsheet

[PASTE YOUR TABLE]
```

**What to check:** Spot-check ten rows, not two. Bulk runs fail in patterns — if the model drifts into a repeated formula halfway down, regenerate from that row with "vary the openers" restated.

**In this lab:** Paste the EcoDesk page inventory (index, products, guide, article, thank-you). The cannibalisation flag is the graded output: two EcoDesk pages chasing one query is a clustering defect, not a copy defect.

### Template 3 — Local-intent metas for Singapore searches

Singapore searchers respond to local trust signals the way other markets respond to discounts — but only claim them where they are true.

```text
Write meta titles and descriptions for this page targeting searchers
in Singapore.

Page: [PAGE TOPIC]
Primary keyword: [KEYWORD] singapore

Rules:
- Mention Singapore naturally in the title, not bolted on
- Include one trust signal in the description, e.g. a credential,
  guarantee or independent rating, ONLY if true for this page
- Max 60 / 155 characters
- Give 3 pairs ranked by expected click-through rate, with one line
  explaining your ranking
```

**What to check:** Trust claims are regulated territory — verify every credential, guarantee and rating against the live page before publishing. A wrong claim in a meta description is a complaint waiting to happen.

**In this lab:** EcoDesk is a fictional product retailer with no credential or certification of any kind, so the correct learner output is to strike the trust-signal rule and say why. Reinstating it is a quality failure.

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
