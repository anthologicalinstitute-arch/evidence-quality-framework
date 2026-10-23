# Methodology: Evidence Quality Framework

## 1. Purpose

This document describes the proposed methodology for the Evidence Quality Framework developed by the Anthological Institute for Research & Governance.

The framework is intended to organize the assessment of evidence across multiple dimensions. It explores whether a composite score can provide a useful summary while preserving transparency about the underlying judgments and uncertainties.

**Research status: Exploratory — not validated.**

The methodology, component definitions, scoring scales, and aggregation rule are proposals for evaluation. They must not be treated as an established measurement instrument.

## 2. Proposed Model

The current proposed equation is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Where:

- \(Q_e\) = proposed evidence-quality composite
- \(q_s\) = source reliability score
- \(q_t\) = freshness and temporal relevance score
- \(q_c\) = corroboration score
- \(q_p\) = provenance and completeness score

For illustrative calculations, each component is assigned a value between 0 and 1.

The use of this normalized scale is a modeling choice. It does not establish that the dimensions can already be measured objectively, that equal numerical increments have equivalent meaning, or that multiplication is the appropriate aggregation method.

## 3. Component Definitions

### 3.1 Source Reliability (\(q_s\))

This dimension concerns the quality and suitability of the source for the specific claim under review.

Potential considerations include:

- The source's relevant expertise and authority.
- The transparency of its methods and supporting evidence.
- The distinction between firsthand reporting and secondary interpretation.
- The source's track record in the relevant domain.
- Potential conflicts of interest or incentives.
- Whether the source is appropriate for the type of claim being assessed.

A source's institutional reputation alone is insufficient to establish the reliability of every statement it makes.

### 3.2 Freshness and Temporal Relevance (\(q_t\))

This dimension concerns whether the evidence remains current and appropriate for the time period relevant to the claim.

Potential considerations include:

- The date the information was produced.
- The date of the events or observations it describes.
- The rate at which the underlying subject changes.
- Whether the claim is historical or time-sensitive.
- Whether more recent evidence supersedes earlier information.

Older evidence is not necessarily weaker. Historical claims may require historical sources, while rapidly changing subjects may require current information.

### 3.3 Corroboration (\(q_c\))

This dimension concerns the extent to which a claim is supported by additional relevant evidence.

Potential considerations include:

- Whether independent sources support the same claim.
- Whether the sources rely on separate observations or a shared original source.
- Whether the sources use different methods.
- Whether credible contradictory evidence exists.
- Whether the corroborating sources are relevant to the exact claim.

Multiple publications repeating the same unsupported assertion should not automatically count as independent corroboration.

### 3.4 Provenance and Completeness (\(q_p\))

This dimension concerns whether the origin, context, and relevant documentation of evidence can be traced and assessed.

Potential considerations include:

- Identification of the original source.
- Availability of dates, authorship, and contextual information.
- Documentation of transformations or analytical steps.
- Availability of supporting records or methods.
- Missing information that materially affects interpretation.
- Integrity and traceability of the evidence record.

Provenance and completeness are related but distinct concepts. Future revisions should evaluate whether combining them into a single component is methodologically justified.

## 4. Scoring Assumptions

The current proposal assumes that:

1. Each component can be assigned a score on a common normalized scale.
2. Higher component values represent more favorable assessments under the relevant scoring criteria.
3. Component values can be multiplied to produce a composite.
4. The resulting composite is sufficiently useful to warrant reporting.
5. The dimensions can be defined well enough to reduce arbitrary scoring.
6. The component scores and final output can be interpreted consistently within a stated assessment context.

These assumptions have not been established empirically.

Before formal use, each component requires explicit scoring anchors, guidance for ambiguous cases, rules for missing information, and a procedure for documenting reviewer judgments.

## 5. Assumptions Behind Multiplicative Aggregation

Multiplication is the current proposed aggregation method. It is not yet justified as superior to alternatives.

The formula has several mathematical consequences:

- If any component equals zero, the composite equals zero.
- A low value in one component can substantially reduce the total.
- Increasing one component has a larger absolute effect when the product of the other components is larger.
- The composite is sensitive to the assigned component values.
- The same composite may arise from different combinations of component scores.

The formula does not independently establish that the four dimensions are statistically independent, conceptually distinct, equally important, or measured on equivalent scales.

The model also assumes that treating the dimensions multiplicatively is appropriate for the intended use. This requires theoretical justification and empirical evaluation.

## 6. Illustrative Calculation

Suppose an example assessment assigns:

- \(q_s = 0.90\)
- \(q_t = 0.80\)
- \(q_c = 0.75\)
- \(q_p = 1.00\)

The proposed calculation is:

\[
Q_e = 0.90 \times 0.80 \times 0.75 \times 1.00 = 0.54
\]

The output is 0.54 under the proposed formula and illustrative inputs.

This result does not demonstrate that the evidence is 54% reliable, that a claim has a 54% probability of being true, or that the score has any validated interpretation outside the arithmetic of the example.

The inputs are illustrative assignments, not measurements derived from a validated scoring instrument.

Additional examples are provided in [`worked-examples.md`](worked-examples.md).

## 7. Missing Information and Zero Values

The framework must distinguish between a genuine low score and an inability to assess a component.

A score of zero should not be assigned automatically when information is unavailable. Doing so would conflate a negative assessment with missing data.

Future scoring guidance must define how to handle:

- Missing source information.
- Unavailable corroborating evidence.
- Incomplete documentation.
- Components that cannot reasonably be assessed.
- Evidence that is inapplicable to a particular dimension.

Possible approaches include marking the assessment incomplete, reporting the component as unknown, or defining a justified alternative procedure. No single missing-data policy is established by this draft.

## 8. Evaluation Plan

The proposed model should be evaluated through the following stages.

### Stage 1: Operational Definitions

Define each component, its scope, scoring anchors, evidence requirements, and treatment of ambiguous cases.

### Stage 2: Reviewer Consistency

Have multiple reviewers independently assess the same evidence using the documented criteria. Compare their scores and document sources of disagreement.

### Stage 3: Sensitivity Analysis

Vary the component scores systematically to determine how the composite changes. Identify which dimensions exert the greatest influence under different input conditions.

### Stage 4: Alternative Aggregation

Compare the multiplicative model with reasonable alternatives, including presenting the four component scores separately. Any alternative composite should have a clear rationale.

### Stage 5: Robustness and Context

Examine performance across different evidence types, claim categories, and decision contexts. Determine whether the same criteria remain appropriate or require contextual adaptation.

### Stage 6: Independent Review

Seek review of the definitions, assumptions, evaluation design, and interpretation rules by people who were not responsible for developing the model.

### Stage 7: Documentation

Record methods, data, results, disagreements, revisions, and negative or inconclusive findings. Do not claim validation merely because examples produce consistent arithmetic.

## 9. Reporting Requirements

Any future assessment using the framework should document:

- The claim or evidence item being assessed.
- The assessment date and relevant context.
- The source material reviewed.
- Each component score and its justification.
- Missing information and unresolved uncertainty.
- The composite calculation, if used.
- The known limitations of the assessment.
- Whether the score was assigned by one reviewer or multiple reviewers.

Component scores should be reported alongside the composite so that readers can see what drives the result.

## 10. Methodological Status

The Evidence Quality Framework is an exploratory proposal. Its component definitions, scoring procedures, aggregation method, and practical usefulness have not been empirically validated.

The equation is a candidate model for investigation, not a validated measure of truth, confidence, or evidence reliability.

Any future claim of validity must be supported by an explicit evaluation design and documented findings.
