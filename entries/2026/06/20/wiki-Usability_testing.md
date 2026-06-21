---
source: sources/wiki-Usability_testing.md
source_url: https://en.wikipedia.org/wiki/Usability_testing
---

## Usability Testing: Methods, Participants, and Limitations

Usability testing is a user-centered design technique that evaluates a product by observing real users attempting to complete tasks with it. Unlike usability inspection (expert-driven) or market research (opinion-gathering), usability testing requires systematic observation of actual use under controlled or semi-controlled conditions. It is considered irreplaceable because it reveals how real users interact with a system, exposing design flaws that experts and surveys miss.

## Key Concepts

- **Core distinction**: Usability testing observes people *using* a product for its intended purpose — it is not gathering opinions (market research) or expert evaluation (usability inspection).
- **Origins**: Emerged from 1940s machine-use studies (WWII airplane controls); formalized in HCI during the 1980s; dedicated usability labs appeared in the 1990s; expanded to remote/online testing in the 2000s–2010s.
- **Usability labs**: Purpose-built spaces with controlled conditions, equipment, and formatting flexibility for structured testing.
- **Think aloud protocol**: Participants verbalize their thought process while performing tasks, revealing mental models and confusion points.
- **Co-discovery learning**: Two participants work together, naturally verbalizing their reasoning.
- **Eye tracking**: Measures where users look, revealing attention patterns and missed interface elements.
- **Nielsen's 10 usability heuristics**: Visibility of system status; match between system and real world; user control and freedom; consistency and standards; error prevention; recognition rather than recall; flexibility and efficiency of use; aesthetic and minimalist design; help users recognize/diagnose/recover from errors; help and documentation.
- **Curb-cut effect**: Designs solving problems for users with disabilities (extreme/edge users) often improve usability for all users.
- **WEIRD bias**: Usability research over-represents Western, Educated, Industrialized, Rich, Democratic populations (~12% of global population but ~96% of behavioral research participants).

## Commands and Syntax

No CLI commands. Key procedural frameworks:

**Standard usability test setup:**
1. Create realistic task scenarios
2. Recruit representative participants
3. Brief participants on environment and rules
4. Observe task performance (do not intervene)
5. Collect data via observation, questionnaires, click streams, logs
6. Analyze and iterate on design

**Nielsen/Landauer discovery formula:**
```
U = 1 - (1 - p)^n
```
Where `U` = proportion of problems uncovered, `p` = probability one user finds a specific problem, `n` = number of test participants. Produces an asymptotic curve — diminishing returns as n increases.

**Testing methods by type:**

| Method | Description | Best For |
|--------|-------------|----------|
| Lab testing | Controlled environment, direct observation | Deep qualitative insight |
| Guerrilla/hallway | Quick informal tests in public spaces | Early-stage, low-budget validation |
| Remote synchronous | Moderated via video conferencing (e.g., WebEx) | Geographically distributed users, accessibility |
| Remote asynchronous | Unmoderated, auto-logged click streams and self-reported data | Large sample sizes, cost efficiency |
| A/B testing | Compare two versions differing by one variable | Optimizing specific conversion metrics |
| Heuristic evaluation | Expert review against established principles | Quick assessment without user recruitment |
| Automated expert review | Rule-based program evaluation | Consistency and speed at scale |

## Relationships

- **User-centered design**: Usability testing is a core practice within this broader methodology.
- **Usability inspection methods**: Complementary expert-driven approaches (heuristic evaluation, cognitive walkthrough) that do not involve users.
- **Accessibility testing**: Testing with users with disabilities is a subset that reveals issues affecting all users; compliance with accessibility guidelines alone does not guarantee usability.
- **A/B testing**: Quantitative counterpart — measures behavioral outcomes at scale rather than observing individual task performance.
- **Cognitive pretesting**: Related survey methodology technique focused on comprehension rather than interaction.
- **Digital rhetoric**: Scholars argue usability testing for online writing instruction is necessary but insufficient without rhetorical theory.
- **Market/qualitative research**: Distinct from usability testing (opinions vs. observed behavior) but often used in combination.

## Exam-Relevant Points

- **Five-user rule (Nielsen)**: Testing with 5 users per round, fixing issues, then testing again with 5 new users is more effective than one test with 10 users. The recommendation is iterative small tests, not a single test of 5. Over a project lifecycle, 50–100 users may be tested total.
- **Five-user critique**: The formula assumes constant detection probability across users and problems. Empirical studies show groups of 5 found between 55%–95% of problems (high variance). Groups of 20 never found fewer than 95%.
- **Guerrilla testing is convenience sampling** — results are potentially biased and should be paired with other methods.
- **Remote synchronous vs. asynchronous**: Synchronous preserves moderator-participant interaction but sacrifices environmental control; asynchronous scales better and is more cost-effective but loses the ability to probe in real-time.
- **Disability inclusion**: ~16% of global population has significant disability; testing with disabled users reveals a wider range of issues than testing with non-disabled users alone; compliance ≠ usability.
- **Body language observation** (Apple 1982 example): 95% of stumbling blocks are found by watching body language, not by asking — users blame themselves, not the software, and will not report problems.
- **A/B testing scope**: Tests one variable at a time between two versions; multivariate/bucket testing compares more than two versions simultaneously.
- **Heuristic evaluation** uses Nielsen's 10 heuristics as the evaluation framework — know the list.
- **Industry practice**: Most organizations recruit 5–10 participants per test round.
