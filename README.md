# VCstack

**An open-source AI-powered toolkit for venture capital research and investment workflows.**

VCstack is a collection of specialised AI agent skills designed to support the venture capital research process — from understanding startups and mapping markets to conducting due diligence and preparing investment memos.

Instead of relying on a single general-purpose AI prompt, VCstack breaks the VC research process into focused, reusable workflows. Each skill handles a specific part of the investment research lifecycle and produces structured, actionable outputs.

The goal is simple: make venture capital research more systematic, accessible, and repeatable.

---

## Why VCstack?

Evaluating a startup involves much more than looking at its website or funding history.

Investors need to understand the founding team, market opportunity, competitive landscape, business model, risks, and potential for growth before making an investment decision.

These activities often involve fragmented research across multiple sources and require a structured evaluation process.

VCstack aims to bring these workflows together through specialised AI agent skills that can:

- Structure startup research and founder evaluation.
- Identify competitors and assess market positioning.
- Screen investment opportunities against defined criteria.
- Organise due diligence and identify potential risks.
- Generate structured investment memos.
- Challenge assumptions before investment decisions.
- Track markets and portfolio developments.

## Skills

VCstack currently includes eight specialised VC research skills.

| Skill | Purpose |
|---|---|
| **Founder Brief** | Researches founders, their backgrounds, previous ventures, experience, and founder-market fit. |
| **Competitor Brief** | Identifies competitors, compares positioning, products, business models, and differentiation. |
| **Deal Screen** | Evaluates a startup against investment criteria and identifies initial opportunities and concerns. |
| **Due Diligence** | Investigates a startup across its market, product, team, traction, business model, and risks. |
| **Investment Memo** | Converts research findings into a structured investment recommendation. |
| **Market Map** | Organises companies within a market by category, positioning, and competitive landscape. |
| **IC Challenger** | Challenges investment assumptions, identifies weaknesses, and surfaces counterarguments before an investment decision. |
| **Portfolio Watch** | Monitors portfolio companies for relevant developments, milestones, risks, and changes. |

## How It Works

VCstack uses modular skills, with each skill defining a specific research workflow, instructions, and expected output.

A typical workflow looks like this:

**Startup → Research → Evaluation → Investment Decision**

1. **Startup identification:** Provide the name and available information about a startup.
2. **Initial screening:** Use Deal Screen to assess its investment potential.
3. **Founder research:** Use Founder Brief to understand the founding team.
4. **Competitive research:** Use Competitor Brief and Market Map to understand the market.
5. **Deeper evaluation:** Use Due Diligence to investigate the opportunity and identify risks.
6. **Investment documentation:** Use Investment Memo to consolidate findings.
7. **Critical evaluation:** Use IC Challenger to challenge the investment thesis.
8. **Ongoing monitoring:** Use Portfolio Watch to track developments.

Skills can also be used independently depending on the research requirement.

## Repository Structure

```text
VCstack/
│
├── .agents/
│   └── skills/
│       ├── founder-brief/
│       │   └── SKILL.md
│       ├── competitor-brief/
│       │   └── SKILL.md
│       ├── deal-screen/
│       │   └── SKILL.md
│       ├── due-diligence/
│       │   └── SKILL.md
│       ├── investment-memo/
│       │   └── SKILL.md
│       ├── market-map/
│       │   └── SKILL.md
│       ├── ic-challenger/
│       │   └── SKILL.md
│       └── portfolio-watch/
│           └── SKILL.md
│
├── docs/
│
├── reports/
│
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Getting Started

### Prerequisites

- An AI coding environment that supports agent skills.
- Access to web research capabilities for workflows requiring external information.
- Git (for cloning and contributing).

### 1. Clone the repository

```bash
git clone https://github.com/swetha028-git/VCstack.git
```

```bash
cd VCstack
```

### 2. Open the project

Open the repository in a compatible agent environment that supports the `.agents/skills/` directory.

### 3. Explore the skills

Each skill contains a `SKILL.md` file defining its purpose, instructions, research approach, and expected output.

### 4. Run a skill

Start with a specific startup and ask your AI agent to use the relevant skill.

For example:

```text
Use the Deal Screen skill to evaluate
Broccoli AI as a potential investment opportunity.

Research the company using available public information.
Assess its market, product, traction, competitors,
business model, and potential risks.

Produce a structured deal screening report.
Clearly distinguish verified information
from assumptions and information gaps.
```

You can then use other skills to continue the research.

## Design Principles

VCstack is being developed around a few principles:

- **Modularity:** Each skill should solve a distinct VC research problem.
- **Reusability:** Workflows should be reusable across different companies and markets.
- **Structured research:** Outputs should follow consistent frameworks rather than unstructured AI responses.
- **Evidence-based analysis:** Research should distinguish sourced facts, assumptions, and unknowns.
- **Extensibility:** New skills and research capabilities should be easy to add.

## Example Use Cases

- Screening early-stage startups for potential investment.
- Preparing founder background research before a meeting.
- Mapping competitors within an emerging technology market.
- Identifying risks before an investment decision.
- Preparing investment committee documentation.
- Monitoring developments across a portfolio.

## Roadmap

VCstack is actively evolving. Planned areas of development include:

- [ ] Central workflow orchestration across the eight skills.
- [ ] Consistent report templates and output schemas.
- [ ] Source attribution and research verification.
- [ ] More comprehensive startup and market intelligence workflows.
- [ ] Expanded investment analysis frameworks.
- [ ] Sample reports and reproducible test cases.
- [ ] Additional integrations with public research sources and data tools.

## Contributing

VCstack is an open-source project, and contributions are welcome.

You can contribute by:

- Building new VC research skills.
- Improving existing research frameworks.
- Adding sample reports and test cases.
- Improving documentation.
- Suggesting integrations and new capabilities.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## License

VCstack is released under the [MIT License](LICENSE).

---

**Built to make venture capital research more structured, systematic, and accessible.**

