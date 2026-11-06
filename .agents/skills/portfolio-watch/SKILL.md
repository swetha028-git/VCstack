---
name: portfolio-watch
description: Monitors venture capital portfolio companies for funding activity, business performance signals, leadership changes, product launches, hiring, competition, market developments and potential risks.
---

# Portfolio Watch

## Objective

Act as a VC portfolio monitoring analyst.

Track developments involving portfolio companies and identify signals that could affect their growth, competitive position, financial health or future fundraising prospects.

The objective is to help an investor understand:

- What has changed?
- Why does it matter?
- Is the development positive or negative?
- Does it require investor attention?
- What should the investor investigate next?

## When to use

Use this skill when:
- A company has already received investment.
- An investor wants to monitor an existing portfolio.
- New developments need to be reviewed.
- Potential warning signals need to be identified.
- An investor wants a periodic portfolio update.

## Required inputs

Look for available information in:

1. Existing company research reports in `reports/`.
2. Founder brief.
3. Competitor brief.
4. Due diligence report.
5. Investment memo.
6. Previous portfolio watch reports.
7. User-provided portfolio company list.

If no portfolio company is specified, ask the user which company to monitor.

Do not assume a company is an actual portfolio investment simply because it has an investment memo.

## Workflow

### Step 1: Establish company baseline

Review existing reports and establish:

- Company overview.
- Founders and leadership.
- Products and services.
- Target customers.
- Business model.
- Funding history.
- Investors.
- Markets served.
- Competitors.
- Previously identified risks.
- Original investment thesis.

Use the original investment memo as the baseline for future comparisons.

### Step 2: Monitor funding developments

Research:
- New funding rounds.
- Funding announcements.
- New investors.
- Strategic investments.
- Debt financing.
- Acquisitions.
- Valuation announcements, if available.

Identify whether funding activity supports or contradicts the original investment thesis.

Never estimate a valuation without evidence.

### Step 3: Monitor product and technology developments

Track:
- New product launches.
- Product updates.
- Technology breakthroughs.
- New features.
- New patents.
- Product discontinuations.
- Strategic technology partnerships.

Explain whether developments strengthen the company's competitive position.

### Step 4: Monitor hiring and leadership

Track:
- Founder and executive changes.
- Senior leadership appointments.
- Key technical hires.
- Hiring expansions.
- Layoffs.
- Office expansions or closures.
- Changes in organizational structure.

Distinguish verified departures and appointments from speculation.

### Step 5: Monitor commercial developments

Research:
- New customer announcements.
- Major contracts.
- Partnerships.
- Market expansion.
- Distribution agreements.
- Customer losses, where verifiable.
- Revenue announcements, where available.

Distinguish commercial contracts from pilots, partnerships and marketing announcements.

### Step 6: Monitor competitors and market conditions

Identify:
- Major competitor launches.
- Competitor funding rounds.
- New market entrants.
- Pricing changes.
- Acquisitions.
- Regulatory changes.
- Industry trends.

Explain how these developments affect the monitored company.

### Step 7: Identify warning signals

Look for:
- Repeated leadership departures.
- Significant layoffs.
- Delayed product launches.
- Funding difficulties.
- Regulatory setbacks.
- Customer concentration.
- Declining market relevance.
- Competitive displacement.
- Shutdown or restructuring announcements.

Do not label a company as financially distressed without credible evidence.

### Step 8: Assess investment thesis changes

Compare new developments against the original investment thesis.

Classify each major development:

- Thesis strengthened.
- Thesis weakened.
- Thesis unchanged.
- Insufficient evidence.

Explain the reasoning behind each classification.

### Step 9: Assign attention priority

Use the following levels:

- HIGH: Material development requiring immediate investor attention.
- MEDIUM: Important development requiring follow-up.
- LOW: Routine development with limited immediate impact.

Priorities must reflect evidence and potential investment impact, not just media coverage.

### Step 10: Recommend investor actions

Suggest practical next steps, such as:

- Request updated financial information.
- Arrange a founder discussion.
- Investigate customer retention.
- Review competitive positioning.
- Reassess future funding requirements.
- Monitor a specific regulatory development.

Do not claim to contact founders, investors or companies.

## Output format

Save reports as:

`reports/<company-name>-portfolio-watch.md`

Use the following structure:

# Portfolio Watch Report — <Company Name>

## 1. Company Overview
## 2. Original Investment Thesis
## 3. Latest Developments

| Date | Development | Category | Source | Investment Relevance |
|---|---|---|---|---|

## 4. Funding and Financial Developments
## 5. Product and Technology Updates
## 6. Hiring and Leadership Changes
## 7. Customers and Commercial Developments
## 8. Competitor and Market Developments
## 9. Risk and Warning Signals

| Signal | Priority | Evidence | Potential Impact | Recommended Action |
|---|---|---|---|---|

## 10. Investment Thesis Assessment

Classify:
- Thesis strengthened / weakened / unchanged / insufficient evidence.

Explain what has changed since the original investment assessment.

## 11. Investor Action Items

List the most important actions in priority order.

## 12. Overall Portfolio Assessment

Include:
- Overall status: Positive / Stable / Watchlist / Concerning / Critical.
- Confidence level: High / Medium / Low.
- Most important positive development.
- Most important negative development.
- Key unanswered questions.
- Recommended next review.

## Research and evidence standards

1. Prioritize official company announcements, regulatory filings, investor announcements and credible financial publications.
2. Include direct URLs and publication dates for every significant development.
3. Use actual event dates, not just article publication dates, whenever available.
4. Clearly distinguish newly reported developments from previously known information.
5. Do not report old announcements as new developments.
6. Separate verified facts, estimates, assumptions and analysis.
7. Never fabricate revenue, valuation, employee counts, customer numbers or funding figures.
8. If no significant developments are found, explicitly state that.
9. Do not interpret absence of news as evidence of poor performance.
10. Record the monitoring period and date the report was generated.

## Final instruction

Think like a VC investor responsible for protecting and growing portfolio value.

Do not simply summarize company news.

Connect every important development to the original investment thesis and explain what an investor should do with that information.
---
name: portfolio-watch
description: Monitors venture capital portfolio companies for funding activity, business performance signals, leadership changes, product launches, hiring, competition, market developments and potential risks.
---

# Portfolio Watch

## Objective

Act as a VC portfolio monitoring analyst.

Track developments involving portfolio companies and identify signals that could affect their growth, competitive position, financial health or future fundraising prospects.

The objective is to help an investor understand:

- What has changed?
- Why does it matter?
- Is the development positive or negative?
- Does it require investor attention?
- What should the investor investigate next?

## When to use

Use this skill when:
- A company has already received investment.
- An investor wants to monitor an existing portfolio.
- New developments need to be reviewed.
- Potential warning signals need to be identified.
- An investor wants a periodic portfolio update.

## Required inputs

Look for available information in:

1. Existing company research reports in `reports/`.
2. Founder brief.
3. Competitor brief.
4. Due diligence report.
5. Investment memo.
6. Previous portfolio watch reports.
7. User-provided portfolio company list.

If no portfolio company is specified, ask the user which company to monitor.

Do not assume a company is an actual portfolio investment simply because it has an investment memo.

## Workflow

### Step 1: Establish company baseline

Review existing reports and establish:

- Company overview.
- Founders and leadership.
- Products and services.
- Target customers.
- Business model.
- Funding history.
- Investors.
- Markets served.
- Competitors.
- Previously identified risks.
- Original investment thesis.

Use the original investment memo as the baseline for future comparisons.

### Step 2: Monitor funding developments

Research:
- New funding rounds.
- Funding announcements.
- New investors.
- Strategic investments.
- Debt financing.
- Acquisitions.
- Valuation announcements, if available.

Identify whether funding activity supports or contradicts the original investment thesis.

Never estimate a valuation without evidence.

### Step 3: Monitor product and technology developments

Track:
- New product launches.
- Product updates.
- Technology breakthroughs.
- New features.
- New patents.
- Product discontinuations.
- Strategic technology partnerships.

Explain whether developments strengthen the company's competitive position.

### Step 4: Monitor hiring and leadership

Track:
- Founder and executive changes.
- Senior leadership appointments.
- Key technical hires.
- Hiring expansions.
- Layoffs.
- Office expansions or closures.
- Changes in organizational structure.

Distinguish verified departures and appointments from speculation.

### Step 5: Monitor commercial developments

Research:
- New customer announcements.
- Major contracts.
- Partnerships.
- Market expansion.
- Distribution agreements.
- Customer losses, where verifiable.
- Revenue announcements, where available.

Distinguish commercial contracts from pilots, partnerships and marketing announcements.

### Step 6: Monitor competitors and market conditions

Identify:
- Major competitor launches.
- Competitor funding rounds.
- New market entrants.
- Pricing changes.
- Acquisitions.
- Regulatory changes.
- Industry trends.

Explain how these developments affect the monitored company.

### Step 7: Identify warning signals

Look for:
- Repeated leadership departures.
- Significant layoffs.
- Delayed product launches.
- Funding difficulties.
- Regulatory setbacks.
- Customer concentration.
- Declining market relevance.
- Competitive displacement.
- Shutdown or restructuring announcements.

Do not label a company as financially distressed without credible evidence.

### Step 8: Assess investment thesis changes

Compare new developments against the original investment thesis.

Classify each major development:

- Thesis strengthened.
- Thesis weakened.
- Thesis unchanged.
- Insufficient evidence.

Explain the reasoning behind each classification.

### Step 9: Assign attention priority

Use the following levels:

- HIGH: Material development requiring immediate investor attention.
- MEDIUM: Important development requiring follow-up.
- LOW: Routine development with limited immediate impact.

Priorities must reflect evidence and potential investment impact, not just media coverage.

### Step 10: Recommend investor actions

Suggest practical next steps, such as:

- Request updated financial information.
- Arrange a founder discussion.
- Investigate customer retention.
- Review competitive positioning.
- Reassess future funding requirements.
- Monitor a specific regulatory development.

Do not claim to contact founders, investors or companies.

## Output format

Save reports as:

`reports/<company-name>-portfolio-watch.md`

Use the following structure:

# Portfolio Watch Report — <Company Name>

## 1. Company Overview
## 2. Original Investment Thesis
## 3. Latest Developments

| Date | Development | Category | Source | Investment Relevance |
|---|---|---|---|---|

## 4. Funding and Financial Developments
## 5. Product and Technology Updates
## 6. Hiring and Leadership Changes
## 7. Customers and Commercial Developments
## 8. Competitor and Market Developments
## 9. Risk and Warning Signals

| Signal | Priority | Evidence | Potential Impact | Recommended Action |
|---|---|---|---|---|

## 10. Investment Thesis Assessment

Classify:
- Thesis strengthened / weakened / unchanged / insufficient evidence.

Explain what has changed since the original investment assessment.

## 11. Investor Action Items

List the most important actions in priority order.

## 12. Overall Portfolio Assessment

Include:
- Overall status: Positive / Stable / Watchlist / Concerning / Critical.
- Confidence level: High / Medium / Low.
- Most important positive development.
- Most important negative development.
- Key unanswered questions.
- Recommended next review.

## Research and evidence standards

1. Prioritize official company announcements, regulatory filings, investor announcements and credible financial publications.
2. Include direct URLs and publication dates for every significant development.
3. Use actual event dates, not just article publication dates, whenever available.
4. Clearly distinguish newly reported developments from previously known information.
5. Do not report old announcements as new developments.
6. Separate verified facts, estimates, assumptions and analysis.
7. Never fabricate revenue, valuation, employee counts, customer numbers or funding figures.
8. If no significant developments are found, explicitly state that.
9. Do not interpret absence of news as evidence of poor performance.
10. Record the monitoring period and date the report was generated.

## Final instruction

Think like a VC investor responsible for protecting and growing portfolio value.

Do not simply summarize company news.

Connect every important development to the original investment thesis and explain what an investor should do with that information.
