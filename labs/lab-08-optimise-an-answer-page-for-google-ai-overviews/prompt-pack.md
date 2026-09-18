# Prompt Pack — Lab 8: Optimise an Answer Page for Google AI Overviews

Replace bracketed fields with verified inputs. Never paste personal, confidential, licensed or credential data into a tool without authority.

## Prompt 1 — CONTEXT task prompt

> **Context:** You support EcoDesk, a fictional Singapore sustainable-office-products business. Audience: [role]. Page/task: [page]. Brand facts: [verified facts only].  
> **Objective:** [one measurable outcome].  
> **Necessary inputs:** [paste source text/data with source and date].  
> **Task steps:** Create a query-fan-out hypothesis and answer-unit outline for Google AI features. Use foundational SEO; promise no citations and propose no special AI-only markup.  
> **Evidence:** Cite the exact supplied row, page element or source for every material conclusion. Separate observation, inference and recommendation.  
> **eXclusions:** No invented metrics, rankings, citations, testimonials, prices, certifications, environmental benefits or legal claims. No keyword stuffing, link schemes or private data.  
> **Template:** Return findings/options, evidence, uncertainty, recommendation, human checks and acceptance checklist.

## Prompt 2 — Adversarial quality review

> Act as a critical SEO editor. Review intent, accuracy, originality, clarity, brand, accessibility, Google Search policies and the lab acceptance test. Return issue, severity, evidence, correction and reviewer decision.

## Prompt 3 — Human approval summary

> Prepare a change preview. Show affected files/fields, before/after meaning, evidence, limitations, tests, risks, rollback and an approve/revise/reject recommendation. Do not publish.

## Field-tested prompt templates

Published templates from [AI Prompts for SEO Meta Tags & LinkedIn Posts (Templates)](https://www.tertiarycourses.com.sg/blog/ai-prompts-seo-meta-linkedin-posts). An answer page still needs a snippet that states the answer honestly before the click.

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
