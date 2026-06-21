---
source: sources/wiki-Cognitive_walkthrough.md
source_url: https://en.wikipedia.org/wiki/Cognitive_walkthrough
---

## Cognitive Walkthrough: A Task-Based Usability Inspection Method

The cognitive walkthrough is a usability inspection method that evaluates how easily new users can learn to accomplish tasks with an interactive system. Unlike heuristic evaluation (which takes a holistic view), cognitive walkthroughs are task-specific, stepping through each action a user must take and asking whether the interface guides them correctly. The method is grounded in the principle that users prefer learning by doing rather than reading manuals.

## Key Concepts

- **Definition**: A usability inspection method focused on learnability — how easily new or infrequent users can accomplish tasks on first use
- **Core assumption**: Users prefer to learn systems by using them to accomplish tasks, not by studying documentation
- **Task-specific vs. holistic**: Cognitive walkthroughs evaluate specific task flows, whereas heuristic evaluation catches broader usability issues
- **Low cost, early application**: Can be performed before any code is written, using mockups or prototypes — cheaper and faster than usability testing with real participants
- **Not a user test**: Evaluators walk through the optimal action sequence themselves; real users are not involved
- **Four key questions** asked at each step of a task:
  1. Will the user try to achieve the effect that this subtask has? (Goal formation)
  2. Will the user notice that the correct action is available? (Visibility)
  3. Will the user understand that the correct action achieves the desired subtask? (Label/affordance comprehension)
  4. Does the user get appropriate feedback after performing the action? (Feedback)
- **Streamlined version** (Spencer, 2000): Reduced to two questions per step with less documentation overhead, designed to work within real software development constraints
- **Cognitive Jogthrough** (Rowley & Rhoades, 1992): An earlier simplified variant that influenced the streamlined approach

## Commands and Syntax

**Streamlined Cognitive Walkthrough Procedure:**

1. **Define inputs**:
   - Identify target users and their characteristics
   - Create sample tasks representative of real usage
   - Produce action sequences (step-by-step paths through the interface)
   - Prepare the interface or prototype for evaluation

2. **Convene the walkthrough**:
   - State goals, scope, and ground rules
   - Ground rules: no designing during the session, no defending designs, no debating cognitive theory
   - Usability specialist leads the session
   - Assign roles to participants

3. **Walk through each action sequence**:
   - For each subtask, ask the four questions (goal, visibility, comprehension, feedback)
   - Record usability problems as they are discovered

4. **Record findings**:
   - Learnability problems
   - Design ideas and gaps
   - Problems with the task analysis itself

5. **Revise the interface** based on walkthrough findings

## Relationships

- **Parent category**: Usability inspection methods — cognitive walkthrough is one of several discount evaluation techniques
- **Complementary to heuristic evaluation**: Heuristic evaluation catches issues the task-specific walkthrough misses; best used together
- **Alternative to usability testing**: Faster and cheaper, but does not involve real users — less ecological validity
- **Depends on task analysis**: A prerequisite; the walkthrough evaluates the task sequences produced by task analysis
- **Related to cognitive dimensions**: A separate framework for evaluating interface elements that affect usability
- **Historical context**: Published in Jakob Nielsen's "Usability Inspection Methods" (1994); developed by Wharton, Rieman, Lewis, and Polson
- **Extended for the web**: Blackmon et al. (2002, 2003) adapted the method specifically for web usability evaluation

## Exam-Relevant Points

- Cognitive walkthroughs focus specifically on **learnability for new users**, not expert performance or efficiency
- The method evaluates the **optimal action sequence**, not how a confused user might stumble through the interface — a common misunderstanding
- The **four questions** (goal, visibility, comprehension, feedback) are the core analytical framework and must be memorized
- Key distinction: cognitive walkthrough is **task-specific**; heuristic evaluation is **holistic** — they are complementary, not interchangeable
- The method **does not test real users** — evaluators simulate a new user's perspective; it will often find more problems than a single user test session
- Can be applied **early in design** before coding begins, which is a major advantage over usability testing
- **Social constraints** that undermine walkthroughs: time pressure, lengthy design discussions during the session, and design defensiveness from creators
- Spencer's **streamlined version** (CHI 2000) addressed practical barriers by reducing questions to two per step and minimizing documentation
- Gray and Salzman's **"Damaged Merchandise"** (1998) challenged the validity of studies comparing usability inspection methods — important methodological caveat
- Originally designed for **walk-up-and-use systems** (kiosks, ATMs, museum exhibits) but has been successfully applied to complex software (CAD tools, development environments)
