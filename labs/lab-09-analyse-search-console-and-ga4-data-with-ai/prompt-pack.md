# Prompt Pack — Lab 9: Analyse Search Console and GA4 Data with AI

Replace bracketed fields with verified inputs. Never paste personal, confidential, licensed or credential data into a tool without authority.

## Prompt 1 — CONTEXT task prompt

> **Context:** You support EcoDesk, a fictional Singapore sustainable-office-products business. Audience: [role]. Page/task: [page]. Brand facts: [verified facts only].  
> **Objective:** [one measurable outcome].  
> **Necessary inputs:** [paste source text/data with source and date].  
> **Task steps:** Analyse supplied Search Console and GA4 tables using the metric dictionary. Show calculations, evidence rows, alternatives, confidence and a testable next action.  
> **Evidence:** Cite the exact supplied row, page element or source for every material conclusion. Separate observation, inference and recommendation.  
> **eXclusions:** No invented metrics, rankings, citations, testimonials, prices, certifications, environmental benefits or legal claims. No keyword stuffing, link schemes or private data.  
> **Template:** Return findings/options, evidence, uncertainty, recommendation, human checks and acceptance checklist.

## Prompt 2 — Adversarial quality review

> Act as a critical SEO editor. Review intent, accuracy, originality, clarity, brand, accessibility, Google Search policies and the lab acceptance test. Return issue, severity, evidence, correction and reviewer decision.

## Prompt 3 — Human approval summary

> Prepare a change preview. Show affected files/fields, before/after meaning, evidence, limitations, tests, risks, rollback and an approve/revise/reject recommendation. Do not publish.

## Field-tested prompt templates

Published templates from [AI Prompts for SEO Meta Tags & LinkedIn Posts (Templates)](https://www.tertiarycourses.com.sg/blog/ai-prompts-seo-meta-linkedin-posts). Search Console impressions and CTR are the inputs; the rewrite is the testable next action.

Every template follows the same five-part skeleton — it is the skeleton, not the tool, that does the work:

| Part | What it does |
|---|---|
| Role | Tell the model what it is ("you are an SEO copywriter"), which sets vocabulary and priorities. |
| Context | The page, audience, keyword and differentiator. The model cannot know your business; feed it. |
| Constraints | Character limits, banned phrases, tone rules. Constraints are what separate usable output from slop. |
| Format | Ask for a table or labelled options so the output drops straight into your workflow. |
| Guardrail | An explicit instruction not to invent facts, and to ask when information is missing. |

Replace the [BRACKETED] fields with verified inputs before running any template below.

### Template 1 — Rescuing a page with high impressions but low CTR

Pull the numbers from Google Search Console first — this prompt turns a reporting insight into a rewrite, which is the single fastest SEO win available to most sites.

```text
Here is Google Search Console data for one page (last 3 months):

Query: [TOP QUERY]  Impressions: [N]  Clicks: [N]
CTR: [N]%  Average position: [N]

Current meta title: [TITLE]
Current meta description: [DESCRIPTION]

The page ranks well but searchers skip it. Diagnose the likely reason
in 2 sentences, then write 3 alternative title/description pairs for
the same query: one leading with a number, one leading with the
outcome, one leading with a question. Max 60 / 155 characters.
```

**What to check:** The diagnosis is a hypothesis, not a fact. Ship one variant, wait three weeks, and compare CTR in Search Console before rolling the pattern out.

**In this lab:** Use the supplied synthetic Search Console rows only. Record the diagnosis as an inference with a stated confidence level and a three-week measurement window — never as a finding.

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
