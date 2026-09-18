# Lab 3: Generate and Validate a Keyword Universe

**Mapping:** LO2 · A1 · K2 · K8  
**Objective:** Use AI to expand and validate search terms without inventing metrics  
**Deliverable:** Validated keyword universe and topic-hub webpage  
**Primary source:** https://support.google.com/google-ads/answer/7337243

## Scenario

AI can expand, normalise and group language, but search volume, competition and current SERP evidence must come from supplied or verified data.

EcoDesk needs a content plan spanning recycled stationery, ergonomic accessories and sustainable workplace practices.

## Training assumptions and guardrails

- Keyword metrics are synthetic and dated 16 August 2026.
- Missing volume and difficulty must remain unknown, never estimated by the model.
- Search intent requires manual SERP validation before publishing.
- Singapore is the primary market and English is the primary language.

## Questions

1. Which seeds come from real customer language?
2. Which expansions are relevant but unsupported by demand data?
3. Which queries reveal local, comparison or purchase intent?
4. Which terms should be excluded for weak fit or compliance risk?

## Detailed step-by-step procedure

### Step 1: Review inputs

Inspect the synthetic Search Console, planner and customer-language rows; record source and date.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Create seed sets

Group seeds by product, problem, audience, location and desired outcome.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Run expansion prompt

Require the AI to return phrase, inferred intent, rationale and source seed without metrics.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Normalise

Remove duplicates, spelling noise and meaningless variations while preserving useful language differences.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Join metrics

Merge only the supplied metrics by exact keyword; leave unmatched values blank.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Validate samples

Manually inspect representative SERPs and record observed result types and competing intent.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Filter

Remove irrelevant, misleading, unsupported or very low-value terms.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Build hub

Add the selected themes and questions to keyword-hub.html as crawler-readable static content.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] No metric is AI-invented; every retained keyword has a source, intent, cluster candidate, validation status and business-fit rationale.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
