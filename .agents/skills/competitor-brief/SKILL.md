---
name: competitor-brief
description: Researches a startup's direct and indirect competitors, competitive positioning, business models, funding, strengths, weaknesses, and market opportunities. Produces a source-backed competitor intelligence report for VC investment research.
---

# Competitor Brief

## Purpose

Act as a venture capital competitive intelligence analyst.

Research the competitive landscape of a startup to understand:
- Who its actual competitors are.
- How competing products and businesses operate.
- What differentiates the target startup.
- Where competitive threats and market opportunities exist.

The objective is to help an investment analyst understand whether a startup has a defensible competitive position.

## Input

Accept the following information:

- Startup name (required)
- Startup website (optional)
- Industry or sector (optional)
- Product description (optional)
- Target geography (optional)

If only the startup name is provided, research the company before identifying competitors.

## Research Workflow

### 1. Understand the Target Startup

Research:
- Core product and services.
- Problem being solved.
- Target customers.
- Business model.
- Target geography.
- Product positioning.
- Current stage of development.

Establish what the company actually does before identifying competitors.

### 2. Identify Competitors

Identify:

**Direct competitors**
- Companies solving the same problem.
- Companies targeting similar customers.
- Companies offering comparable products.

**Indirect competitors**
- Alternative solutions to the same customer problem.
- Existing tools or workflows that could replace the startup's product.
- Established companies entering the same market.

**Emerging competitors**
- Early-stage startups entering the category.
- New technologies that could disrupt the business.
- Adjacent companies expanding into the target market.

Aim for 5–10 relevant competitors when sufficient evidence is available. Do not add irrelevant companies just to meet a numerical target.

### 3. Research Each Competitor

For every relevant competitor, investigate:

- Company overview.
- Website and product.
- Founding year.
- Founders.
- Headquarters.
- Target customers.
- Core features.
- Pricing (if publicly available).
- Business model.
- Funding rounds and investors.
- Market positioning.
- Recent product developments.

Use publicly available information only.

### 4. Competitive Comparison

Create a comparison table:

| Parameter | Target Startup | Competitor A | Competitor B |
|---|---|---|---|
| Product | | | |
| Target customers | | | |
| Business model | | | |
| Pricing | | | |
| Key features | | | |
| Funding | | | |
| Differentiation | | | |

Only include information that can be supported by evidence. Mark unavailable information as Not Disclosed.

### 5. Competitive Positioning

Evaluate:

- What does the target startup do differently?
- Is its product genuinely differentiated?
- Does it have a technology advantage?
- Does it serve an underserved customer segment?
- Is its pricing competitive?
- Does it have distribution or partnership advantages?
- Could an established competitor replicate its offering?

Do not automatically assume that a startup has a competitive moat.

### 6. Strengths and Weaknesses

Identify:

**Potential strengths**
- Product differentiation.
- Technical capabilities.
- Distribution.
- Customer relationships.
- Cost advantages.
- Network effects.
- Proprietary technology.

**Potential weaknesses**
- Limited product maturity.
- Strong incumbent competition.
- High customer acquisition costs.
- Weak differentiation.
- Dependence on third-party infrastructure.
- Lack of defensibility.

Distinguish demonstrated advantages from potential advantages.

### 7. Market Gaps and Opportunities

Identify:
- Underserved customer segments.
- Missing product capabilities.
- Geographic opportunities.
- Pricing gaps.
- Emerging market requirements.
- Opportunities for differentiation.

Explain whether these opportunities are supported by evidence or are hypotheses requiring validation.

### 8. Competitive Threat Assessment

Evaluate:
- Threat from established players.
- Threat from new entrants.
- Substitute products.
- Pricing pressure.
- Technology disruption.
- Customer switching costs.

Use Low, Medium or High threat ratings and explain each rating.

## Output Format

Generate a Markdown report with the following structure:

# Competitor Intelligence Report: [Startup Name]

### 1. Executive Summary
Concise overview of the competitive landscape.

### 2. Target Startup Overview
What the startup does, its customers and positioning.

### 3. Competitor Landscape
Separate direct, indirect and emerging competitors.

### 4. Competitor Profiles
Detailed research on each relevant competitor.

### 5. Competitive Comparison
A structured comparison table.

### 6. Competitive Positioning
Where the startup stands relative to competitors.

### 7. Strengths and Weaknesses
Evidence-backed competitive assessment.

### 8. Market Gaps and Opportunities
Potential areas for differentiation.

### 9. Competitive Threat Assessment
Major threats and their severity.

### 10. VC Analyst Takeaways
Answer:
- Is this a crowded market?
- Is the startup meaningfully differentiated?
- What is its potential competitive advantage?
- What could prevent it from winning?
- What should an investor investigate further?

### 11. Sources and Research Limitations
Provide source names, URLs and publication dates where available.

## Evidence and Research Rules

1. Prioritize company websites, official announcements, investor websites, regulatory filings and reputable publications.
2. Verify funding information against reliable sources such as company announcements or investor announcements.
3. Do not invent revenue, customer counts, market share or pricing.
4. Separate facts, estimates and analyst interpretations.
5. Include direct source URLs for important claims.
6. Use recent sources for current product and company information.
7. Flag outdated or conflicting information.
8. If information cannot be verified, explicitly state that it is unavailable.
9. Do not confuse companies operating in the same broad industry with genuine competitors.
10. Do not recommend an investment solely because the startup has fewer competitors.

## Final Instruction

Produce an objective, evidence-backed competitive intelligence report suitable for a venture capital analyst.

The report must help an investor understand the startup's competitive position, potential defensibility and risks.

Save the completed report as:

reports/[startup-name]-competitor-brief.md

Do not overwrite existing reports without explicit permission.