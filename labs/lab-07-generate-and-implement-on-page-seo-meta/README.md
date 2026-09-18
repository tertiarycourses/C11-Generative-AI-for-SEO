# Lab 7: Generate and Implement On-Page SEO Meta

**Mapping:** LO3 · A2 · K10  
**Objective:** Use prompts to create and implement accurate on-page elements  
**Deliverable:** Optimised static product page and metadata decision log  
**Primary source:** https://developers.google.com/search/docs/appearance/title-link

## Scenario

Titles and snippets should accurately represent visible content. Structured data must match the page and does not guarantee a rich result.

The EcoDesk product page is useful but generic. The team needs stronger search clarity without inventing prices, ratings, stock or environmental claims.

## Training assumptions and guardrails

- Product names and descriptions are fictional.
- No reviews, aggregate rating or certification markup may be added.
- The canonical URL is a training placeholder and must be changed before real deployment.
- Title and description lengths are editorial guidance, not ranking rules.

## Questions

1. Which page facts can safely appear in metadata?
2. Which generated option best matches intent and brand?
3. Which structured-data type is eligible and visible?
4. Which internal links reduce user effort?

## Detailed step-by-step procedure

### Step 1: Extract page facts

Create a fact table from visible product content and approved business information.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 2: Generate options

Run Template 1 (single page) from the prompt pack for five titles and descriptions with rationale, distinct angle and prohibited-claim check, then Template 3 (local intent) to test whether a Singapore or trust signal is honestly available.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 3: Select and edit

Choose one option, improve natural language and confirm it matches the page.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 4: Implement head elements

Add title, description, canonical, robots, Open Graph and social-card metadata, verifying each length in a pixel-width checker rather than trusting the model count.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 5: Improve structure

Use one clear H1, descriptive sections, useful copy and accessible image attributes.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 6: Add internal links

Connect the page to the pillar, blog and enquiry path with descriptive anchors.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 7: Add JSON-LD

Use eligible visible product/organisation facts only and keep JSON valid.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

### Step 8: Validate

Inspect source, HTML, mobile layout and structured data; record limitations.

**Checkpoint:** Save the evidence, file or decision produced before continuing.

## Use the shared EcoDesk website

**Live site:** https://tertiarycourses.github.io/C11-Generative-AI-for-SEO/

1. Keep this activity folder open for its prompts and evidence files.
2. From the repository root, run: `python3 -m http.server 8000 --directory activities/ecodesk-demo-website`
3. Open http://localhost:8000/ or use the live site above.
4. Apply this activity to the same shared website used in every other activity.
5. Test at desktop and mobile widths.

## Acceptance criteria

- [ ] Metadata is unique and accurate, visible content and JSON-LD agree, links work, images are accessible and no unsupported rating, price or guarantee is present.
- [ ] All links, forms, assistant and mobile navigation work.
- [ ] Work is applied to the one shared EcoDesk website, not a separate copy.
- [ ] AI output is reviewed and the decision log is complete.
