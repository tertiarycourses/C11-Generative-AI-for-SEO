# Lab 10: Build a Governed Agentic SEO Workflow

**Mapping:** LO1–LO5 · A1–A6 · K1–K10  
**Objective:** Design a monitored AI SEO workflow with approvals and rollback  
**Deliverable:** Governed agentic SEO capstone and monitoring plan  
**Primary source:** https://developers.google.com/search/docs/essentials/spam-policies

## Scenario

Agentic SEO can coordinate multi-step research, audit and monitoring, but high-risk actions need scoped permissions, approvals, logs and rollback.

EcoDesk wants a weekly agent to inspect synthetic Search Console data and the static site, recommend refreshes and draft pull-request-ready changes without publishing them.

## Training assumptions and guardrails

- The agent has read-only access to analytics and repository content.
- It cannot publish, send outreach, edit robots/canonicals or expose secrets.
- Every recommendation must cite a page, metric row or policy source.
- A human owner approves, edits and implements accepted changes.

## Questions

1. What is the bounded goal and stop condition?
2. Which tools and data does the agent actually need?
3. Which actions need preview, approval or prohibition?
4. How will quality, drift, value and incidents be measured?

## Detailed step-by-step procedure

### Step 1: Set goal and scope

Define the weekly outcome, included pages, excluded actions and measurable success.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Map inputs

List site files, metrics, prompt versions, policy sources and their data classification.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Design stages

Connect research, audit, prioritisation, draft recommendation, validation and approval.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Assign permissions

Use least privilege; mark read, suggest, draft, approve, publish and rollback rights.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Write prompt contract

Require evidence, confidence, policy check, change preview, tests and a no-action option.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Build approval gates

Place human decisions before content, technical, outreach and publication actions.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Create audit log

Record run ID, inputs, model, prompt, findings, reviewer, decision, changes and rollback.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Run tabletop

Simulate hallucinated traffic data and a proposed noindex change; verify the workflow stops safely.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 9: Plan monitoring

Track accepted recommendations, false positives, time saved, outcome change and incidents for 30 days.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 10: Publish governance page

Present the bounded workflow, permissions and review cadence in the capstone website.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] The workflow is evidence-bound, read-only by default, blocks high-risk autonomous actions, records decisions and demonstrates a successful stop/rollback tabletop.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
