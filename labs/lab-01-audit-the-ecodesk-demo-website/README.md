# Lab 1: Audit the EcoDesk Demo Website

**Mapping:** LO1 · A6 · K1 · K6  
**Objective:** Evaluate a website's current SEO and internet-marketing strategy  
**Deliverable:** Completed baseline audit, five-item priority backlog and preserved original website  
**Primary source:** https://developers.google.com/search/docs/essentials

## Scenario

EcoDesk is a fictional training business. The baseline intentionally contains realistic SEO strengths and weaknesses so learners can inspect code, content and user experience safely.

EcoDesk wants more qualified enquiries from Singapore SMEs but cannot explain which pages, queries or technical issues should be prioritised.

## Training assumptions and guardrails

- All business names, addresses, prices, testimonials and analytics are synthetic.
- No live Search Console or customer data is required.
- The audit must distinguish observed evidence from an AI inference.
- The AI may recommend but must not edit files automatically in this lab.

## Questions

1. Which issues affect crawl/index eligibility, relevance, trust or conversion?
2. Which current strengths should be preserved?
3. Which recommendation has the highest impact-to-effort ratio?
4. What evidence is missing before implementation?

## Detailed step-by-step procedure

### Step 1: Open and inventory

Serve the sample website locally, list every page and asset, and record the page purpose and intended audience.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Inspect source

Check title, description, canonical, robots directive, headings, links, images, scripts and structured data in the HTML.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Review experience

Test navigation, mobile layout, forms, readability, image loading and keyboard access.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Run the audit prompt

Provide only the copied source and audit criteria to the AI. Require observed evidence, severity, confidence and suggested verification.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Challenge the output

Reject invented facts, unsupported ranking claims and advice that conflicts with the visible source.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Prioritise

Score impact, effort, risk and dependency; select the first five actions.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Capture baseline

Save the original files and the completed scorecard before any edits.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Peer review

Exchange audits and reconcile disagreements by pointing to source evidence.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] Every finding cites observable evidence, separates fact from inference, includes a verification method and maps to a business or user outcome.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
