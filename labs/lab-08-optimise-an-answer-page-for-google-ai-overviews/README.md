# Lab 8: Optimise an Answer Page for Google AI Overviews

**Mapping:** LO3 · A2 · K4 · K10  
**Objective:** Apply foundational SEO and answer-first content for generative search  
**Deliverable:** Answer-first guide and AI-feature eligibility checklist  
**Primary source:** https://developers.google.com/search/docs/fundamentals/ai-optimization-guide

## Scenario

Google says existing SEO best practices remain relevant for AI features, pages need no special AI markup, and inclusion is never guaranteed.

EcoDesk wants to answer a complex planning query while avoiding inflated promises about appearing in AI Overviews or AI Mode.

## Training assumptions and guardrails

- The page targets Singapore SME office managers.
- The guide uses public general information and synthetic EcoDesk examples.
- FAQ structured data is omitted unless current eligibility and visible-content requirements are met.
- No llms.txt or special AI-only schema is presented as a Google ranking factor.

## Questions

1. What direct answer should appear first?
2. Which follow-up subqueries might query fan-out retrieve?
3. What original evidence or experience improves the page?
4. Which technical controls could accidentally remove eligibility?

## Detailed step-by-step procedure

### Step 1: Define the complex query

State audience, decision and boundaries; list comparison and follow-up needs.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Use query fan-out prompt

Generate related subquestions as hypotheses, then validate relevance manually.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Build answer units

Write concise self-contained answers followed by explanation, table, steps or evidence.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Add information advantage

Include an original workplace checklist and specific Singapore implementation considerations.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Cite and qualify

Place sources near material claims and state limitations clearly.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Check technical eligibility

Confirm crawl, index, snippet, canonical, text availability, internal links and mobile experience.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Reject myths

Document why special AI markup, citation guarantees and inauthentic mentions are excluded.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Publish and test

Open source, check links, headings, visible text and responsive layout.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] The page is indexable, resolves the main and follow-up intents with unique value, cites evidence and makes no guarantee of AI Overview inclusion.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
