---
source: sources/wiki-Fitts27s_law.md
source_url: https://en.wikipedia.org/wiki/Fitts%27s_law
---

## Fitts's Law: Predictive Model of Pointing Movement Time

Fitts's law is a foundational predictive model in human-computer interaction and ergonomics that quantifies the time required to move to and select a target as a function of the target's distance and size. Originally developed by Paul Fitts in 1954 using an information-theory analogy, the law has become a primary tool for evaluating input devices, designing user interfaces, and understanding the speed-accuracy tradeoff in human motor behavior.

## Key Concepts

- **Index of Difficulty (ID)**: Quantifies task difficulty in bits using the ratio of distance (D) to target width (W). Higher ID means harder targeting tasks.
- **Movement Time (MT)**: The dependent variable — the time to complete a pointing movement. Predicted as a linear function of ID: `MT = a + b · ID`.
- **Index of Performance / Throughput (IP/TP)**: The ratio ID/MT, measured in bits per second. Used to compare input devices against each other (higher is better).
- **Two-phase movement model**: A pointing movement consists of (1) a fast, imprecise ballistic phase covering distance, and (2) a slower, precise corrective phase to acquire the target. Distance has a greater impact on total time than target size.
- **Shannon formulation**: The most widely used variant in HCI: `ID = log₂(D/W + 1)`. Named for its resemblance to the Shannon-Hartley theorem. Adopted by ISO 9241.
- **Effective target width (Wₑ)**: Replaces nominal W with observed accuracy — computed as `Wₑ = 4.133 × SDₓ` from actual selection coordinates. If error rate equals 4%, Wₑ = W. This adjustment incorporates the speed-accuracy tradeoff into the model.
- **Welford's model**: A two-factor variant that separates D and W into independent terms (`MT = a + b₁·log₂(D) + b₂·log₂(W)`), providing better predictive power, especially when control-display gain varies.
- **Temporal pointing**: Extension to time-domain targets (blinking/moving targets) where temporal distance Dₜ and temporal width Wₜ replace spatial parameters.
- **Regression parameters a and b**: Constants determined empirically. Parameter `a` represents a startup delay (y-intercept); `b` represents movement speed scaling (slope). Lower `b` indicates a faster input device.
- **Robustness**: The law holds across limbs (hands, feet, lips, head), environments (including underwater), populations (young, old, impaired), and input devices.

## Commands and Syntax

**Original Fitts formulation (1954):**
```
ID = log₂(2D / W)
```

**Shannon formulation (most common in HCI, ISO 9241):**
```
ID = log₂(D/W + 1)
```

**Movement time prediction:**
```
MT = a + b · log₂(D/W + 1)
```

**Throughput calculation:**
```
TP = IDₑ / MT
```

**Effective target width (accuracy adjustment):**
```
Wₑ = 4.133 × SDₓ
IDₑ = log₂(D/Wₑ + 1)
```

**Welford's two-factor model:**
```
MT = a + b₁·log₂(D) + b₂·log₂(W)
```

**Welford-Shannon with angle parameter k (Kopper et al. 2010):**
```
MT = a + b·log₂((D + W) / W^k)
```
Reduces to Shannon form when k = 1. Models can be compared using F-test of nested models.

**2D target width methods:**
- Status quo: horizontal width only
- Sum model: W = height + width
- Area model: W = height × width
- Smaller-of model: W = min(height, width)
- W-model: effective width in direction of movement

## Relationships

- **Hick's Law**: Companion law governing decision time for choosing among alternatives (choice reaction time). Fitts's law governs the physical movement after the decision.
- **Accot-Zhai Steering Law**: Derived from Fitts's law for constrained path-following tasks (e.g., navigating through hierarchical menus or tunnel-like widgets).
- **Shannon-Hartley Theorem**: The information-theoretic foundation — distance maps to signal strength, target width maps to noise. The Shannon formulation of Fitts's law is directly inspired by this.
- **ISO 9241-9**: International standard for evaluating pointing devices that codifies the Shannon formulation and throughput calculation using effective target width.
- **Speed-accuracy tradeoff**: Fitts's law is the primary quantitative model of this fundamental human performance principle. The Wₑ adjustment explicitly accounts for it.
- **Information theory**: Fitts's law frames motor performance as information processing — pointing transmits information measured in bits.

## Exam-Relevant Points

- **The core relationship**: Movement time increases logarithmically with distance and decreases logarithmically with target width. MT = a + b · log₂(D/W + 1).
- **Shannon vs. original formulation**: Shannon form uses `D/W + 1` (never yields negative ID); original uses `2D/W`. Shannon form is the ISO standard and empirically preferred.
- **Card, English, and Burr (1978)**: First HCI application of Fitts's law — compared mouse, joystick, and step keys. The mouse won. This research contributed to the mouse's commercial adoption by Xerox.
- **Effective target width**: Wₑ = 4.133 × SDₓ, spanning 96% of a normal distribution. When error rate = 4%, Wₑ equals nominal W.
- **UI design implications from Fitts's law**:
  - Make targets as large as possible (optimize W)
  - Cluster related functions together (minimize D)
  - **Rule of infinite edges**: Screen edges act as infinitely large targets in one dimension (e.g., macOS menu bar pinned to screen top)
  - **Magic corners**: Four screen corners are effectively infinite in two dimensions (e.g., Windows Start button)
  - **Prime pixel / magic pixel**: Context menus at cursor position eliminate travel distance (D ≈ 0)
  - **Radial menus**: Equal distance from center for all items, but handedness affects difficulty (left items harder for right-handed users)
- **Model limitation**: Predictive power degrades when both D and W vary widely, because ID depends only on the ratio — implying arbitrary rescaling wouldn't affect MT, which is physically impossible.
- **Two-phase movement**: Fast ballistic approach + slow corrective acquisition. This is why distance dominates total time more than target width.
- **Temporal pointing**: The law extends to time-domain targets using temporal ID: `IDₜ = log₂(Dₜ/Wₜ)`, predicting error rate for blinking or moving targets.
- **Throughput (TP)** is the preferred performance metric for comparing input devices, calculated as IDₑ/MT with the accuracy adjustment included.
