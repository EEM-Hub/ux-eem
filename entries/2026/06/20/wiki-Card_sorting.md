---
source: sources/wiki-Card_sorting.md
source_url: https://en.wikipedia.org/wiki/Card_sorting
---

## Card Sorting as a UX Research Method

Card sorting is a knowledge elicitation technique where participants organize items into categories according to given or self-determined criteria. It is a foundational method in user experience design, information architecture, and cognitive psychology used to understand how users mentally model and categorize information. Results inform the design of navigation structures, menu hierarchies, workflows, and content organization for websites and applications.

## Key Concepts

- **Core purpose**: Reveals how target users categorize and relate items in a domain, exposing their mental models rather than relying on designer assumptions or first principles
- **Participants**: Subject experts or representative users sort labeled index cards/Post-it notes into groups, either individually or collaboratively (focus groups)
- **Dendrogram/folksonomy output**: Results are synthesized into category trees (dendrograms) or user-generated taxonomies (folksonomies)
- **When to use**: Most valuable when no accepted taxonomy exists, when items are difficult to categorize cleanly, or when audience segments disagree on groupings
- **Sample size**: Literature discusses appropriate numbers of users needed for trustworthy results (Jakob Nielsen has written specifically on this)
- **Two analysis paradigms**: Semantic analysis (examines participant labels and descriptions) vs. syntactic analysis (examines structural placement and card relationships)

## Variants

- **Open card sort** (generative): Participants create their own category names. Reveals both classification logic and preferred terminology. Used to discover organizational patterns.
- **Closed card sort** (evaluative): Participants sort cards into predetermined categories. Measures agreement on category assignments. Used to validate an existing structure.
- **Reverse card sort / tree testing** (evaluative): Users navigate an existing hierarchy to complete tasks. Tests findability within a structure in isolation from visual design and navigation aids.
- **Modified-Delphi card sort**: Iterative method where each participant refines the previous participant's sort rather than starting fresh. Builds consensus faster with fewer participants.

## Commands and Syntax

No CLI commands; this is a manual/facilitated research method. Procedural steps:

1. Identify key concepts from the domain and write each on an index card
2. Have a representative participant group the cards logically and name each group
3. Repeat across multiple participants
4. Analyze results for patterns across participants

**Remote/online variant**: Web-based card sorting tools exist that reach larger participant pools at lower cost, with built-in analysis, though they sacrifice the qualitative insights from in-person interaction.

## Analysis Methods

- **Semantic methods**:
  - *Gist analysis*: Identify group labels from different participants that refer to the same concept
  - *Superordinate analysis*: Identify the overarching classification rules each participant used
- **Syntactic methods**:
  - *Card-based*: Similarity/dissimilarity matrices counting co-placement frequency; feed into hierarchical clustering to produce dendrograms, or into multidimensional scaling for scatter plot visualization
  - *Sort-based*: Edit distance (minimum card moves to transform one sort into another, computed via the Hungarian algorithm); orthogonality (measures distinctness across a set of sorts using minimum spanning tree of pairwise edit distances); k-neighborhoods and k-cliques (clustering around a probe sort)
  - *Jaccard distance*: Proportion of differing card pairings between two sorts relative to total possible pairings

## Relationships

- **Information architecture**: Card sorting is a primary research input for IA decisions; IA is the field concerned with structuring information that card sorting helps validate
- **User experience design**: Card sorting sits within the broader UX research toolkit alongside usability testing, interviews, and surveys
- **Tree testing**: The evaluative counterpart to generative card sorting; tests an existing hierarchy rather than generating one
- **Cluster analysis / hierarchical clustering**: Statistical methods used to analyze card sort results and produce dendrograms
- **Taxonomy**: Card sorting is most needed when no standard taxonomy exists; when one does, it may be applied directly
- **Folksonomy**: User-generated categorization schemes that can emerge from open card sort results
- **Focus groups**: Collaborative card sorts use focus group methodology
- **Cognitive psychology**: Card sorting originates as a knowledge elicitation technique in cognitive science
- **Delphi method**: The Modified-Delphi variant adapts this consensus-building technique

## Exam-Relevant Points

- **Open = generative, Closed = evaluative, Reverse = evaluative** — know which variant serves which purpose
- Card sorting cannot be determined from first principles; it requires empirical user input
- Reverse card sorting is more commonly known as **tree testing** and isolates structure from visual design
- **Similarity matrices** feed hierarchical clustering to produce dendrograms; **dissimilarity matrices** also work with multidimensional scaling
- **Edit distance** between card sorts uses the **Hungarian algorithm** for efficient computation
- **Orthogonality** measures distinctness of card sorts using the minimum spanning tree of pairwise edit distances
- Semantic analysis has two sub-methods: **gist analysis** (label equivalence) and **superordinate analysis** (overall classification rules)
- Modified-Delphi method builds consensus with fewer participants through iterative refinement
- Remote card sorting trades richer qualitative insight for larger sample sizes and lower cost
