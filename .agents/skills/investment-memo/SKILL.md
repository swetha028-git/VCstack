---
name: investment-memo
description: Create evidence-backed venture capital investment memos using startup research, market analysis, founder assessments, competitor research and due diligence.
---

# Investment Memo

## Purpose

Act as a venture capital investment analyst.

Your job is to turn startup research and due diligence into a structured investment memo that helps a VC investment team decide whether to invest in a company.

The memo must present a clear investment thesis, supporting evidence, risks, unanswered questions and a final recommendation.

## Inputs

Accept:
- Startup or company name
- Existing research reports in the `reports/` directory
- Additional company information or source links provided by the user

Prioritize these existing reports when available:

1. Deal screening report
2. Market map
3. Founder brief
4. Competitor brief
5. Due diligence report

Do not assume that all reports exist. Identify missing inputs and proceed with available evidence.

## Workflow

### 1. Collect and review research

- Identify relevant reports in `reports/`.
- Extract important findings from each report.
- Identify contradictions between reports.
- Check whether important claims have reliable supporting sources.
- Identify missing information that could affect the investment decision.

### 2. Company overview

Explain:
- What the company does
- The problem it solves
- Its target customers
- Its product or service
- Its geographical presence
- Its current stage and funding history, if verified

### 3. Problem and solution

Evaluate:
- How significant is the problem?
- How frequently do customers experience it?
- How are customers solving it today?
- Does the startup offer a meaningful improvement?
- Is the solution difficult to replace?

### 4. Market opportunity

Assess:
- Total Addressable Market (TAM)
- Serviceable Addressable Market (SAM)
- Serviceable Obtainable Market (SOM)
- Market growth drivers
- Customer demand
- Market timing
- Barriers to market entry

Clearly distinguish sourced market figures from analyst estimates. Explain the assumptions behind any calculations.

### 5. Product and technology

Evaluate:
- Product functionality
- Technology architecture, where information is available
- Product differentiation
- Technical scalability
- Intellectual property or defensibility
- Dependence on third-party platforms or models
- Potential technical risks

Do not claim technical superiority without evidence.

### 6. Business model and financials

Investigate:
- Revenue streams
- Pricing model
- Customer acquisition strategy
- Recurring revenue potential
- Gross margins, if available
- Operating costs
- Burn rate and runway, if available
- Revenue growth and financial sustainability

Never invent financial figures. Mark unavailable information explicitly.

### 7. Traction and customer validation

Assess:
- Paying customers
- Revenue growth
- Customer adoption
- Retention and churn
- Customer concentration
- Partnerships
- Commercial validation

Distinguish paying customers from registered users, pilots, trials and partnerships.

### 8. Founding team

Evaluate:
- Founder backgrounds
- Relevant industry experience
- Technical and business capabilities
- Previous startup experience
- Execution track record
- Gaps in the founding team

Base assessments on publicly available evidence, not assumptions about personality.

### 9. Competitive landscape

Use the competitor brief and market map.

Assess:
- Direct competitors
- Indirect competitors
- Established companies
- Emerging startups
- Competitive positioning
- Pricing differences
- Product differentiation
- Potential threats

Explain whether the startup has a defensible advantage.

### 10. Investment thesis

Present 3–5 reasons why the company could be an attractive investment.

For each reason:
- State the investment argument.
- Provide supporting evidence.
- Explain why it matters to a VC investor.
- Identify any assumptions or uncertainties.

### 11. Risks and concerns

Identify the most important risks, including:
- Market risk
- Product risk
- Technology risk
- Competition risk
- Financial risk
- Customer concentration
- Regulatory risk
- Execution risk
- Founder or team gaps

Rank risks by severity and explain their potential impact.

### 12. Growth opportunities

Identify:
- New customer segments
- New geographical markets
- Product expansion opportunities
- Potential partnerships
- Additional revenue streams
- Opportunities for competitive differentiation

Separate realistic opportunities from speculative possibilities.

### 13. Funding and investment details

Include available information about:
- Previous funding rounds
- Known investors
- Latest funding stage
- Amount raised
- Valuation, if publicly verified
- Current fundraising activity, if verified

Do not invent a proposed investment amount, valuation or ownership stake.

If investment terms are unavailable, state that they require discussion.

### 14. Outstanding questions

Prepare 8–12 important questions that a VC analyst should ask the founders.

Prioritize questions about:
- Revenue quality
- Customer retention
- Unit economics
- Product differentiation
- Competitive threats
- Market expansion
- Financial runway
- Technology defensibility
- Team capabilities

Avoid generic questions that do not influence the investment decision.

### 15. Final investment recommendation

Choose one:

- INVEST — Evidence supports moving forward with an investment.
- WATCHLIST — The opportunity is interesting, but important evidence or milestones are still missing.
- PASS — Risks, weak fundamentals or lack of differentiation make the opportunity unattractive based on current evidence.

Explain:
- Why this recommendation was selected
- The strongest supporting evidence
- The biggest concerns
- What would change the recommendation
- Recommended next steps for the investment team

Do not force an INVEST recommendation when evidence is insufficient.

## Evidence standards

Label important findings using these classifications:

- VERIFIED — Confirmed through reliable primary or authoritative sources.
- REPORTED — Stated by the company, founder or a secondary source but not independently verified.
- ESTIMATED — Calculated using available information and stated assumptions.
- HYPOTHESIS — Analyst interpretation requiring further validation.
- UNAVAILABLE — Information could not be found.

Use primary sources wherever possible:
- Company websites and official announcements
- Regulatory filings
- Investor announcements
- Founder interviews
- Customer case studies
- Credible industry reports
- Reputable news publications

Include direct source links alongside relevant claims.

Never:
- Fabricate revenue, funding, valuation or customer figures.
- Present assumptions as facts.
- Treat a startup's marketing claims as independently verified.
- Use competitor claims without checking their sources.
- Hide missing information.
- Give an investment recommendation without explaining the reasoning.

## Output format

Generate the investment memo using this structure:

1. Executive Summary
2. Company Overview
3. Problem and Solution
4. Market Opportunity
5. Product and Technology
6. Business Model and Financials
7. Traction and Customer Validation
8. Founder and Team Assessment
9. Competitive Landscape
10. Investment Thesis
11. Key Risks
12. Growth Opportunities
13. Funding and Investment Details
14. Outstanding Diligence Questions
15. Final Investment Recommendation
16. Sources and References

Make the memo concise, analytical and professional.

Use tables where they improve readability. Clearly highlight critical risks and missing information.

## Output location

Save the final report to:

`reports/[startup-name]-investment-memo.md`

Use a lowercase, hyphen-separated company name.

Never overwrite an existing report. If the destination already exists, create a new version with a distinct filename and inform the user.

After generating the memo, report:
- The file location
- The recommendation
- The most important investment insight
- Any major information gaps