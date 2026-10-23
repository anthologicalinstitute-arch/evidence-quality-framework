# Worked Examples: Evidence Quality Framework

## 1. Purpose and Status

This document demonstrates how the proposed Evidence Quality Framework equation behaves under illustrative inputs.

**All scores and scenarios in this document are hypothetical. They are not empirical findings, validated ratings, or assessments of real sources.**

The examples demonstrate arithmetic and model behavior only.

The framework remains exploratory and unvalidated. A calculated composite must not be interpreted as the probability that a claim is true.

## 2. Proposed Equation

The current proposed composite is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Where:

- \(q_s\) = source reliability score
- \(q_t\) = freshness and temporal relevance score
- \(q_c\) = corroboration score
- \(q_p\) = provenance and completeness score

For these examples, each component is assigned a hypothetical value between 0 and 1.

The examples do not establish how actual evidence should be scored. Operational scoring criteria remain to be developed and evaluated.

## 3. Example A — Illustrative Baseline

Assume the following hypothetical inputs:

| Component | Illustrative value |
|---|---:|
| Source reliability (\(q_s\)) | 0.90 |
| Freshness (\(q_t\)) | 0.80 |
| Corroboration (\(q_c\)) | 0.75 |
| Provenance and completeness (\(q_p\)) | 1.00 |

Calculation:

\[
Q_e = 0.90 \times 0.80 \times 0.75 \times 1.00
\]

\[
Q_e = 0.54
\]

**Result:** The proposed formula produces a composite of 0.54.

**Interpretation:** This is the arithmetic result of the selected hypothetical inputs. It does not mean that the evidence is 54% reliable or that the claim has a 54% probability of being true.

The calculation does not establish whether the input values are appropriate, whether the dimensions are sufficiently distinct, or whether the composite is useful for decision-making.

## 4. Example B — Lower Freshness Score

Suppose the only change is a lower hypothetical freshness score:

| Component | Illustrative value |
|---|---:|
| Source reliability (\(q_s\)) | 0.90 |
| Freshness (\(q_t\)) | 0.50 |
| Corroboration (\(q_c\)) | 0.75 |
| Provenance and completeness (\(q_p\)) | 1.00 |

Calculation:

\[
Q_e = 0.90 \times 0.50 \times 0.75 \times 1.00
\]

\[
Q_e = 0.3375
\]

**Result:** The composite decreases from 0.54 to 0.3375.

This demonstrates how lowering one component changes the product while the other inputs remain constant.

It does not establish that the evidence has become less accurate. The significance of freshness depends on the claim, the underlying subject, and the time period being assessed.

## 5. Example C — A Zero Component

Suppose one component is assigned a value of zero:

| Component | Illustrative value |
|---|---:|
| Source reliability (\(q_s\)) | 0.90 |
| Freshness (\(q_t\)) | 0.80 |
| Corroboration (\(q_c\)) | 0.00 |
| Provenance and completeness (\(q_p\)) | 1.00 |

Calculation:

\[
Q_e = 0.90 \times 0.80 \times 0.00 \times 1.00 = 0
\]

**Result:** The composite equals zero.

This is a mathematical consequence of multiplication, not proof that the underlying claim is false or that all evidence associated with it is worthless.

It also raises a methodological question: should a zero corroboration score represent no corroboration, contradictory evidence, or an inability to locate additional sources? These conditions should not automatically receive the same score.

The framework requires explicit rules for distinguishing low values from unknown or unassessed components.

## 6. Example D — Different Inputs, Same Composite

Consider two hypothetical assessments.

**Assessment 1**

\[
0.90 \times 0.80 \times 0.75 \times 1.00 = 0.54
\]

**Assessment 2**

\[
0.90 \times 0.90 \times 0.80 \times 0.8333 \approx 0.54
\]

Both produce approximately the same composite, despite having different component profiles.

This illustrates a limitation of composite scores: the final value can conceal important differences between assessments.

For this reason, component scores and their justifications should be reported alongside any composite. The composite alone is insufficient to explain the quality or limitations of an evidence item.

## 7. Example E — Illustrative Sensitivity to One Component

Return to the baseline inputs:

\[
Q_e = 0.90 \times 0.80 \times 0.75 \times 1.00 = 0.54
\]

Now change the source reliability input from 0.90 to 0.70 while holding the other components constant:

\[
Q_e = 0.70 \times 0.80 \times 0.75 \times 1.00 = 0.42
\]

The composite changes from 0.54 to 0.42.

This demonstrates sensitivity to the selected source reliability value. It does not establish whether 0.70 is a defensible assessment or whether the resulting change is meaningful in practice.

A proper sensitivity analysis should examine a broader range of inputs and document why those ranges were selected.

## 8. Interpretation Rules

When using these examples:

1. Treat all component values as hypothetical.
2. Verify each calculation independently.
3. Do not interpret the composite as a probability, confidence interval, or validated measure of truth.
4. Do not assume that a higher composite guarantees a more accurate conclusion.
5. Examine component scores separately to identify strengths and weaknesses.
6. Distinguish missing information from evidence that warrants a low score.
7. Consider whether the scoring criteria fit the claim and decision context.
8. Document the assumptions behind every assessment.

## 9. Questions for Further Research

The examples identify questions that require evaluation:

- Can reviewers assign component scores consistently?
- Are the four dimensions sufficiently distinct?
- Does multiplication impose an appropriate penalty on low component values?
- How should missing or unassessed information be handled?
- Does the composite provide useful information beyond the component scores?
- Are some dimensions more important than others in specific contexts?
- Do the scoring rules work consistently across different evidence types?
- How should contradictory evidence affect the corroboration component?
- Can a defensible evaluation procedure demonstrate practical value?

These questions should guide future research rather than be treated as resolved conclusions.

## 10. Status

**Exploratory — not validated.**

The examples illustrate mathematical behavior under hypothetical assumptions. They do not validate the scoring system, the composite equation, or any claim assessed using the framework.
