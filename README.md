# SEO SEAL Method

> A structured, data-driven framework for comprehensive keyword research and organic growth.

Visit the [SEO SEAL Method guide](https://www.nidacademy.org/seo-seal-method/) for full details.

---

## Introduction

Ranking in today’s competitive search landscape requires more than random keyword selection. The **[SEO SEAL Method](https://www.nidacademy.org/seo-seal-method/)**—**S**eed → **E**xpand → **A**nalyze → **L**ong-Tail—provides a systematic process to discover, evaluate, and implement keywords that drive targeted traffic and conversions.

This repository includes:
- A detailed guide (`README.md`)
- Spreadsheet templates (`/templates/seed-template.xlsx`, `/templates/analysis-matrix.xlsx`)
- Workflow checklists (`/docs/workflow.md`)

## Table of Contents

- [Phases](#phases)
- [Example Data](#example-data)
- [Workflow](#workflow)
- [Recommended Toolstack](#recommended-toolstack)
- [Cross-Team Collaboration](#cross-team-collaboration)
- [Getting Started](#getting-started)
- [License](#license)

---

## Phases

### 1. Seed: Identifying Core Keywords

- **Objective**: Generate 10–30 foundational keywords representing your primary offerings.
- **Process**:
  1. Brainstorm business topics (products, services, pain points).
  2. Translate industry terms into customer language.
  3. Validate with volume (500–5,000/mo) and difficulty (≤50) using tools.
- **Output**: Seed keyword list in `seed-template.xlsx`.
- Learn more in the [Seed phase section](https://www.nidacademy.org/seo-seal-method/#seed) of the guide.

### 2. Expand: Growing Your Keyword Universe

- **Objective**: Scale seed list by 10×–100× with related and question-based terms.
- **Process**:
  1. Scrape Google Autocomplete & People Also Ask.
  2. Run bulk-suggestion exports (Ahrefs, SEMrush).
  3. Perform competitor gap analysis.
  4. Aggregate, dedupe, and tag by source.
- **Output**: Master list in `/templates/expanded-keywords.csv`.
- Detailed steps at [Expand phase](https://www.nidacademy.org/seo-seal-method/#expand).

### 3. Analyze: Prioritizing Keywords

- **Objective**: Narrow down to high-impact terms via data-driven metrics and intent.
- **Process**:
  1. Plot Volume × Difficulty matrix (thresholds: high ≥1,000/mo; low ≤500/mo).
  2. Classify intent: Informational, Navigational, Transactional, Commercial.
  3. Filter for brand relevance and conversion potential.
  4. Assign Tier levels with timelines and resource planning.
- **Output**: Priority matrix in `analysis-matrix.xlsx`.
- Explore the [Analyze phase](https://www.nidacademy.org/seo-seal-method/#analyze) for full guidance.

### 4. Long-Tail: Targeting Specific Queries

- **Objective**: Capture niche, high-conversion phrases overlooked by competitors.
- **Process**:
  1. Generate with AnswerThePublic, AlsoAsked, forums.
  2. Create question- and qualifier-based modifiers.
  3. Optimize on-page elements (title, URL, headings).
  4. Monitor and iterate based on performance metrics.
- **Output**: Long-tail keyword sheet in `/templates/long-tail.csv`.
- For examples, visit the [Long-Tail section](https://www.nidacademy.org/seo-seal-method/#long-tail).

---

## Example Data

### Sample Seed Keyword Sheet

| Seed Keyword       | Volume (mo) | Difficulty (%) | Current Rank | CPC (USD) | Tag      |
|--------------------|-------------|----------------|--------------|-----------|----------|
| "home gym"        | 4,200       | 35             | —            | 1.20      | awareness|
| "treadmill"       | 9,800       | 60             | 18           | 2.45      | decision |
| "best dumbbells"  | 2,300       | 40             | 9            | 1.80      | consideration|

### Sample Volume × Difficulty Matrix

```text
                Difficulty
                  Low       |       High
Volume   High   [QW1, QW2]  |  [LT1, LT2]
         -----------+-----------------------
         Low    [SW1, SW2]  |  [AV1, AV2]
```

- **QW**: Quick Wins (High Volume, Low Difficulty)
- **LT**: Long-Term (High Volume, High Difficulty)
- **SW**: Supplementary Wins (Low Volume, Low Difficulty)
- **AV**: Avoid (Low Volume, High Difficulty)

For more examples, see [Example Data](https://www.nidacademy.org/seo-seal-method/#example-data).

---

## Workflow

1. **Week 1 (Seed)**: Brainstorm → research → validate → document.
2. **Weeks 2–3 (Expand)**: Autocomplete → tool exports → competitor gaps → clean & tag.
3. **Weeks 4–5 (Analyze)**: Matrix plotting → intent mapping → filtering → tier planning.
4. **Ongoing (Long-Tail)**: Discover → implement → monitor → refine.

Full workflow descriptions in [`/docs/workflow.md`](./docs/workflow.md) or online at [Workflow](https://www.nidacademy.org/seo-seal-method/#workflow).

---

## Recommended Toolstack

| Phase     | Tools                                                                                         | Notes                                 |
|-----------|-----------------------------------------------------------------------------------------------|---------------------------------------|
| Seed      | Google Keyword Planner, Ahrefs, SEMrush, Google Trends                                         | Validate volumes and difficulty       |
| Expand    | Keywords Everywhere, AnswerThePublic, AlsoAsked, Ahrefs/Moz/SEMrush                            | Export and tag with source metadata   |
| Analyze   | Excel/Google Sheets, Keyword Cupid, Datawrapper (matrix plotting), SERP analysis tools        | Visualize priority and map intent     |
| Long-Tail | AnswerThePublic, AlsoAsked, Reddit/Quora mining, Google Search Console, rank trackers         | Iterate based on performance data     |

See full tool recommendations at [Toolstack](https://www.nidacademy.org/seo-seal-method/#tools).

---

## Cross-Team Collaboration

- **Content**:  Provide keyword intent labels, priority tiers, and briefs for writers.
- **Development**:  Implement URL structures, schema markup, and site architecture aligned with keyword hierarchy.
- **Analytics**:  Set up Google Analytics/Search Console dashboards for keyword and conversion tracking.

Recommend bi-weekly syncs using the `/docs/collaboration-agenda.md` template or online at [Collaboration](https://www.nidacademy.org/seo-seal-method/#collaboration).

---

## Getting Started

1. **Clone** this repo:
   ```bash
   git clone https://github.com/your-org/seo-seal-method.git
   ```
2. **Open** `/templates/seed-template.xlsx` and start listing your 10–30 core seeds from the [Seed guide](https://www.nidacademy.org/seo-seal-method/#seed).
3. **Follow** `docs/workflow.md` step-by-step to expand, analyze, and long-tail phases, or navigate the [online guide](https://www.nidacademy.org/seo-seal-method/).
4. **Report** progress via `/templates/status-report.md` to stakeholders.

---

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
