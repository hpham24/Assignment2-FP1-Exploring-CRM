# Prompts Used – AI Research Documentation

**Course:** ICS499 – Software Engineering and Capstone Project  
**Assignment:** Assignment 2 + FP1 – Exploring CRM Systems  

---

## Best Prompts That Produced Useful Results

### Prompt 1 – CRM Overview and History

```
Act as a software consultant writing a technical report for a client.

Explain what CRM systems are, including:
- A clear definition
- The original purpose of CRM
- The history from the 1980s to today
- How CRM has evolved with cloud computing and AI

Keep the tone professional but accessible to a non-technical reader.
```

**Why it worked:** Assigning a role ("software consultant") and specifying a target audience ("non-technical reader") produced a well-structured, appropriately pitched response. Listing specific sub-topics ensured nothing was missed.

---

### Prompt 2 – Commercial CRM Comparison Table

```
Act as a CRM consultant.

Compare Salesforce, HubSpot CRM, Zoho CRM, and Microsoft Dynamics 365
for a company with approximately 100 employees in professional services.

For each product provide:
- Target customer size
- Top 3 strengths
- Top 3 weaknesses
- Approximate pricing per user per month

Format the output as a Markdown table.
```

**Why it worked:** Specifying the company size and industry gave the AI useful context to tailor the comparison. Requesting Markdown table format directly saved reformatting time. Asking for exactly 3 strengths/weaknesses kept responses balanced and scannable.

---

### Prompt 3 – Open Source CRM Comparison

```
Compare EspoCRM, SuiteCRM, and Odoo CRM as open-source alternatives
to commercial CRM systems.

For each one, describe:
- Core features included
- Technology stack (language, database, frontend)
- Community support quality
- Ease of installation (1–5 scale with explanation)

Also identify which one you would recommend for a developer-run
small business and explain why.
```

**Why it worked:** Asking for a consistent set of attributes across all three products made comparison straightforward. The specific sub-questions (tech stack, community, ease of install) produced more actionable output than a generic "compare these CRMs" prompt.

---

### Prompt 4 – Industry-Specific CRM Use Cases

```
I am writing a technical report on CRM systems for a software engineering course.

For each of the following industries, explain one specific business problem
that existed before CRM adoption and how a CRM system solved it:

- Retail
- Healthcare
- Education
- Manufacturing
- Nonprofits

Be specific. Use real examples where possible.
Keep each industry section to 3–4 sentences.
```

**Why it worked:** The length constraint ("3–4 sentences") prevented the AI from generating bloated responses. Asking for "specific" examples with "real examples where possible" pushed the AI to produce more grounded content rather than generic descriptions.

---

### Prompt 5 – EspoCRM Evaluation Framework

```
I am about to explore EspoCRM using their online demo environment.

Generate a structured evaluation checklist I should work through, covering:
1. First impressions and UI quality
2. Core CRM modules to test
3. Features to look for that differentiate good from mediocre CRM software
4. Red flags that would make me NOT recommend this product
5. Questions I should be able to answer after 30 minutes of exploration

Format as a numbered checklist.
```

**Why it worked:** Using AI to generate an evaluation framework before starting the hands-on exploration made the 30-minute demo session much more productive. Without this prompt, the exploration would have been unfocused.

---

## AI Effectiveness Analysis

### What AI Did Well

- **Rapid domain orientation.** Within 10–15 minutes of prompting, AI provided a working understanding of CRM history, major products, and typical feature sets. Achieving the same depth through manual research would have taken several hours of reading documentation, blog posts, and review sites.
- **Structured output.** When prompted to produce Markdown tables, comparison lists, and numbered checklists, AI consistently delivered well-formatted content that could be incorporated directly into the report with minimal editing.
- **Balanced comparisons.** AI was willing to name weaknesses in well-known products (e.g., Salesforce's cost and complexity, HubSpot's pricing structure) rather than producing uniformly positive marketing-style responses.
- **Reframing problems.** When asked "what business problems does CRM solve," the AI moved naturally from abstract definitions to concrete industry-specific examples, which was exactly what was needed for Part 1.

---

### What AI Struggled With

- **Current pricing accuracy.** AI-generated pricing figures required verification. Software pricing changes frequently, and the AI's training data may lag reality by months or years. Prices were cross-checked against vendor websites before including in the report.
- **Recency.** AI tools have knowledge cutoffs and may not know about recent product launches, acquisitions, or feature updates. For example, AI was unaware of the most recent minor version of EspoCRM.
- **Nuanced product opinions.** When asked "which CRM is best overall," AI tended to hedge excessively and present all options as equally valid. Getting a clear recommendation required prompting specifically: "If you had to choose ONE, which would it be and why?"
- **Screenshot generation.** AI cannot generate real screenshots from live software — this required direct interaction with the demo environment.

---

### What Information Required Validation

| Claim | How Validated |
|-------|--------------|
| Salesforce founding year (1999) | Confirmed via Salesforce About page |
| HubSpot free tier feature limits | Verified against HubSpot pricing page |
| EspoCRM tech stack (PHP/MySQL/Vue.js) | Confirmed in EspoCRM GitHub repository README |
| SuiteCRM is a fork of SugarCRM | Confirmed via SuiteCRM official documentation |
| Salesforce market share (~20%) | Cross-checked against IDC CRM market share report |

---

### What Surprised Me

The most surprising finding was how capable AI was at generating structured technical comparisons that were largely accurate when cross-checked. The expectation was that AI would produce generic, surface-level descriptions. Instead, the product comparisons included specific technical details (e.g., EspoCRM's REST API, Odoo's use of PostgreSQL) that held up to verification.

It was also surprising how much the **quality of the prompt** affected the quality of the output. Vague prompts like "tell me about CRM" produced mediocre responses. Specific, role-assigned, format-specified prompts produced professional-grade content.

---

### What I Would Do Differently Next Time

1. **Start with a research plan prompt.** Before diving into specific questions, ask the AI: "I need to research X for a technical report. What are the 10 most important questions I should explore?" This generates a research roadmap and catches blind spots.
2. **Always specify output format upfront.** Asking for Markdown tables, bullet lists, or numbered checklists from the start saves significant reformatting time.
3. **Validate pricing immediately.** Make a habit of verifying any dollar figures from AI responses against current vendor pricing pages before including them in any document.
4. **Use multiple AI tools for cross-validation.** Using Claude as primary and ChatGPT or Perplexity as secondary verification helped catch cases where one tool's response was incomplete or slightly inaccurate.

---

### Would I Trust AI for Software Research?

**Yes, as a starting point — but not as a final source.**

AI is extremely effective for rapidly building a working understanding of an unfamiliar domain. Within an hour of prompting, it's possible to develop enough knowledge to hold an intelligent conversation about CRM systems, ask smart questions, and make basic recommendations.

However, AI-generated research should always be:
- **Verified** against primary sources (vendor documentation, academic papers, analyst reports)
- **Dated** — AI training data has cutoffs; anything time-sensitive needs external verification
- **Credited appropriately** — AI-generated content is a research aid, not a citable source

The appropriate mental model is to treat AI like a very well-read colleague who has read a lot but may be working from slightly outdated information. You'd take their input seriously but you'd still check the facts before putting them in a report.

---
