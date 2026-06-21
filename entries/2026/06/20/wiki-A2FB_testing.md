---
source: sources/wiki-A2FB_testing.md
source_url: https://en.wikipedia.org/wiki/A%2FB_testing
---

## A/B Testing: Methodology, Statistics, and Applications

A/B testing (also called bucket testing, split-run testing, or split testing) is a user-experience research method based on randomized controlled experiments. It compares two or more variants of a single variable to determine which performs better against a defined, measurable outcome. The method applies statistical hypothesis testing to user behavior data and is foundational to evidence-based product design and optimization.

## Key Concepts

- **Core mechanism**: Randomly assign users to variant A or variant B, measure a pre-defined metric, and use statistical tests to determine which variant performs better.
- **Multivariate testing**: Tests more than two versions simultaneously or uses more controls; distinct from simple A/B tests.
- **A/B tests are not valid** for observational, quasi-experimental, or non-experimental situations (e.g., survey data, offline data).
- **Defined outcome required**: Every test must have a measurable goal (conversions, clickthrough rate, registration rate). Different metrics can yield different "winners" from the same experiment.
- **Segmentation effects**: A variant that wins overall may lose within a specific user segment (e.g., by gender, age). This is a form of Simpson's paradox. Segmented strategies can significantly improve outcomes (e.g., 30% lift in the example given).
- **Representative sampling**: When segmented results are expected, the test must be designed to distribute participants evenly across key attributes to avoid bias.
- **CUPED (Controlled Experiment Using Pre-Experiment Data)**: Microsoft-originated technique that uses pre-experiment variance to reduce the sample size needed for statistical significance.
- **Sample size sensitivity**: A/B tests require large sample sizes to reduce standard error and produce statistically significant results. Low-traffic products face difficulty here.

## Commands and Syntax

No CLI commands per se, but the key statistical procedures are:

| Data Distribution | Use Case | Primary Test | Alternative |
|---|---|---|---|
| Gaussian | Average revenue per user | Welch's t-test | Student's t-test |
| Binomial | Click-through rate | Fisher's exact test | Barnard's test |
| Poisson | Transactions per paying user | E-test | C-test |
| Multinomial | Product purchase counts | Chi-squared test | G-test |
| Unknown | — | Mann-Whitney U test | Gibbs sampling |

**Choosing a test**: Welch's t-test is the most commonly used because it assumes the least about the data. Fisher's exact test is specifically for comparing two binomial distributions (e.g., conversion rates).

## Relationships

- **Statistical hypothesis testing**: A/B testing is an applied form of two-sample hypothesis testing; understanding null hypotheses, p-values, and significance levels is prerequisite.
- **Purchase funnel optimization**: A/B testing is the primary method for identifying friction points and improving conversion at each funnel stage in e-commerce.
- **User experience research**: A/B testing is one method in the broader UX research toolkit; it answers "which performs better" but not "why."
- **Multi-armed bandit**: An alternative approach that dynamically allocates traffic to better-performing variants rather than waiting for a fixed-duration test to conclude.
- **Randomized controlled trials**: A/B testing is the digital equivalent; shares the same experimental design principles.
- **HTTP routing / feature flags**: In engineering, A/B tests are implemented via reverse proxies or feature-flag systems that route n% of traffic to a new variant, enabling controlled rollouts.
- **Between-subjects design**: A/B testing is structurally identical to this well-established research design.

## Exam-Relevant Points

- **Welch's t-test is the default** for comparing means in A/B tests because it makes the fewest assumptions.
- **Fisher's exact test** is the correct choice for comparing two binomial proportions (e.g., click-through rates).
- **Statistical significance must be established** — a raw difference in conversion rates is insufficient to declare a winner; you must rule out chance.
- **Segmentation can reverse results**: The overall winner may be the loser in a specific segment. Always check segment-level results.
- **A/B tests require random assignment** — they are invalid for observational or quasi-experimental data.
- **CUPED reduces required sample size** by accounting for pre-experiment variance, a key technique at scale.
- **The test outcome depends on the metric chosen** — the same experiment can yield different conclusions depending on whether you optimize for clicks, conversions, or revenue.
- **Google ran 7,000+ A/B tests in 2011**; major companies now run over 10,000 annually — scale of experimentation is a competitive differentiator.
- **Top industry challenges** (per 2018 summit with Airbnb, Amazon, Google, Microsoft, Netflix, etc.): analysis, engineering and culture, deviations from traditional A/B tests, and data quality.
- **Historical origin**: First randomized double-blind trial was 1835; Google's first A/B test was in 2000; the practice bridges Claude Hopkins's early-20th-century advertising experiments with modern statistical methods developed by Gosset (Student's t-test, 1908).
