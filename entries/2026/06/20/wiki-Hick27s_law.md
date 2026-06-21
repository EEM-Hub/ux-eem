---
source: sources/wiki-Hick27s_law.md
source_url: https://en.wikipedia.org/wiki/Hick%27s_law
---

## Hick's Law: Decision Time and Number of Choices

Hick's law (Hick–Hyman law) describes how the time a person takes to make a decision increases logarithmically with the number of available choices. Named after psychologists William Edmund Hick and Ray Hyman, the law is rooted in information theory and has direct implications for interface design: more options slow users down, but the slowdown is sub-linear — doubling the choices does not double decision time.

## Key Concepts

- **Logarithmic relationship**: Decision time grows as log₂ of the number of choices, not linearly. Each additional option adds less incremental delay than the previous one.
- **Binary subdivision**: The logarithmic form arises because people categorize choices and eliminate roughly half the remaining options at each cognitive step (analogous to binary search), rather than evaluating each option sequentially.
- **Rate of gain of information**: The amount of time taken to process a certain number of bits — essentially a measure of cognitive information processing speed.
- **Information-theoretic entropy**: When choices have unequal probabilities, the generalized form uses entropy (H) rather than simple log₂(n), weighting each option by its probability.
- **Stimulus–response compatibility**: Decision time is also affected by how naturally the response maps to the stimulus (e.g., turning a steering wheel to turn wheels). Compatible mappings reduce reaction time.
- **Exceptions exist**: Hick's law does not apply universally — verbal responses to familiar stimuli, saccadic eye movements, and randomly ordered word lists all violate the expected pattern. The predictability–reaction-time relationship may be sigmoid rather than linear-logarithmic.

## Commands and Syntax

**Core formula (equally probable choices):**

```
T = b · log₂(n + 1)
```

- `T` = average reaction/decision time
- `n` = number of equally probable choices
- `b` = empirically determined constant (slope of fitted line)
- `+1` accounts for uncertainty about whether to respond at all

**Generalized formula (unequal probabilities):**

```
T = b · H

where H = Σ pᵢ · log₂(1/pᵢ + 1)
```

- `H` = information-theoretic entropy of the decision
- `pᵢ` = probability of the i-th alternative

**IQ/processing speed variant (Roth, 1964):**

```
Reaction Time = Movement Time + log₂(n) / Processing Speed
```

## Relationships

- **Fitts's Law**: Similar logarithmic form but governs motor movement time (pointing/reaching) rather than cognitive decision time. Together they model the two main bottlenecks in interaction: deciding what to select and physically selecting it.
- **Information Theory**: Hick's law is grounded in Shannon's information theory; the choice set is treated as a source of information measured in bits.
- **Power Law of Practice**: Relates to how repeated practice reduces task time — complementary to Hick's law when considering expert vs. novice performance with menus.
- **The Paradox of Choice** (Barry Schwartz): The psychological phenomenon that too many choices can lead to decision paralysis — a broader framing of the problem Hick's law quantifies.
- **Menu Design**: Directly applicable to navigation structures, but only when users can employ a subdivision strategy (e.g., alphabetical ordering). Random ordering forces linear scanning and Hick's law does not apply.

## Exam-Relevant Points

- The relationship between number of choices and decision time is **logarithmic, not linear** — this is the single most tested fact.
- The formula includes **n + 1** (not just n) to account for the "no response" option.
- Hick's law **does not apply** to randomly ordered lists (linear scanning required) — it requires a structure that supports subdivision (e.g., categorized or alphabetical menus).
- For **unequal probabilities**, use the entropy-based generalization, not the simple log₂(n+1) form.
- **Stimulus–response compatibility** modulates the effect — compatible mappings reduce choice reaction time independent of the number of options.
- Key design implication: reducing the number of choices presented at each level (e.g., through progressive disclosure or hierarchical menus) reduces decision time, but the marginal benefit of removing one option decreases as the set gets smaller.
- Hick's law and Fitts's law are **complementary**, not competing — one models cognitive decision time, the other models motor execution time.
- Exceptions include **saccadic eye movements** (which can show an anti-Hick's effect) and **familiar verbal responses** (no significant increase with more options).
