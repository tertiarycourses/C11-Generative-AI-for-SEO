# Lab 9: Analyse Search Console and GA4 Data with AI

**Mapping:** LO5 · A3 · A4 · K3 · K4 · K9  
**Objective:** Evaluate SEO performance across channels using defined metrics  
**Deliverable:** Evidence-backed SEO performance review and experiment plan  
**Primary source:** https://support.google.com/analytics/answer/14731736

## Scenario

Search Console describes Google search visibility and clicks; GA4 describes user/session behaviour after arrival. Their scopes and counts need not match.

EcoDesk impressions rose while clicks and enquiries fell. Management wants an explanation and action plan, not a confident AI story.

## Training assumptions and guardrails

- All metrics are synthetic and contain a planned tracking change in week 5.
- No causal claim may be made from correlation alone.
- AI calculations must be checked against spreadsheet formulas.
- Search features and seasonality are plausible alternative causes.

## Questions

1. Which metrics changed materially and at what page/query level?
2. Could definition or tracking changes explain the pattern?
3. Which hypotheses fit all available evidence?
4. What test would distinguish competing explanations?

## Detailed step-by-step procedure

### Step 1: Define metrics

Create a dictionary for impression, click, CTR, position, user, session, engaged session and key event.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Quality-check data

Inspect date ranges, missing rows, duplicates, aggregation and the week-5 tracking note.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Calculate baseline

Compute weekly and page-level changes with spreadsheet formulas.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Prompt for diagnosis

Provide the dictionary and tables; require calculations, evidence rows, alternatives and confidence. For any high-impression low-CTR page, run the CTR-rescue template and record the diagnosis as a hypothesis with a three-week test window.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Verify

Recalculate samples and reject any unsupported causal statement.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Segment

Compare landing page, query intent, device and channel to find hidden differences.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Design experiment

Choose one coherent change with target pages, guardrails, window and decision rule.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Publish review

Present the KPI tree, evidence, hypotheses and experiment on a static dashboard page.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] Every conclusion traces to supplied data, metric scopes are correct, alternative explanations are considered and the recommended test has a baseline and decision rule.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
