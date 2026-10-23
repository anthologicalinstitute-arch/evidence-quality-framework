# Limitations and Risks: Evidence Quality Framework

## 1. Purpose and Status

This document identifies the principal limitations, assumptions, and potential failure modes of the proposed Evidence Quality Framework.

Its purpose is to prevent the model from being interpreted more strongly than the current research supports and to establish priorities for critical evaluation.

**Current status: Exploratory — not validated.**

The proposed equation, component definitions, scoring rules, and practical usefulness have not been empirically validated.

## 2. No Validated Measure of Truth

The composite score is not the probability that a claim is true.

A high score does not establish that a claim is correct. A low score does not establish that a claim is false. The composite is an output of a proposed calculation based on assigned component values.

The framework does not currently provide:

- A calibrated probability of truth.
- A validated confidence estimate.
- A guarantee of factual accuracy.
- A substitute for domain-specific verification.
- A universally applicable measure of evidence quality.

Any future attempt to connect the composite to an external outcome would require a separately specified and tested validation procedure.

## 3. Subjectivity in Component Scoring

The four component values may depend on reviewer judgment.

Without detailed scoring anchors, two reviewers may assign different values to the same evidence. Terms such as source reliability, sufficient corroboration, freshness, and completeness can be interpreted differently across domains.

**Potential failure mode:** The apparent precision of the composite conceals inconsistent or subjective inputs.

**Mitigation:** Develop operational definitions, explicit scoring criteria, documented examples, and independent reviewer testing. Report disagreements and uncertainty rather than concealing them.

## 4. Unvalidated Aggregation Rule

The proposed equation is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Multiplication is a modeling choice, not an established property of evidence quality.

The current proposal has not demonstrated that multiplicative aggregation is superior to alternatives, including reporting each dimension separately.

**Potential failure mode:** The model produces a numerical result that appears authoritative even though the aggregation rule lacks sufficient theoretical or empirical support.

**Mitigation:** Explain the rationale for the equation, compare it with plausible alternatives, and evaluate whether the composite improves interpretation or decision-making.

## 5. Zero and Near-Zero Values

Multiplication makes any composite equal to zero when any component is zero. A very low component can also substantially reduce the product.

However, a zero value might represent different conditions, including:

- A genuinely unfavorable assessment.
- An absence of supporting evidence.
- A contradictory finding.
- Missing information.
- A component that cannot be assessed.

These conditions are not necessarily equivalent.

**Potential failure mode:** Missing or unassessed information is treated as proof of a complete failure of evidence quality.

**Mitigation:** Define explicit rules for zero values, unknown values, missing information, and inapplicable components. Do not automatically assign zero when a component cannot be assessed.

## 6. Dependence and Overlap Between Dimensions

The proposed dimensions may not be independent.

For example, incomplete provenance can make independent corroboration difficult. Source reliability judgments may already incorporate methodological transparency or the quality of supporting documentation.

**Potential failure mode:** Related characteristics are counted more than once, causing the composite to penalize some evidence disproportionately.

**Mitigation:** Define the boundaries between dimensions, examine their conceptual and empirical relationships, and evaluate whether any dimensions should be separated, combined, or reported independently.

The framework must not assume statistical independence merely because the equation multiplies the scores.

## 7. False Precision and Interpretation Risk

A composite such as 0.5376 may look more precise than the underlying judgments justify.

The number of decimal places does not establish measurement precision, repeatability, or validity.

**Potential failure mode:** Readers compare scores as if small numerical differences represent meaningful differences in evidence quality.

**Mitigation:** Report appropriate precision, preserve the underlying component scores, explain uncertainty, and avoid rankings that the evaluation evidence does not justify.

## 8. Context Sensitivity

The relevance of each dimension depends on the claim and intended use.

Freshness may be critical for current market conditions but less relevant for a historical event. A primary source may be essential for one question, while a high-quality synthesis may be more appropriate for another.

**Potential failure mode:** One scoring scheme is applied indiscriminately across different subjects, evidence types, or decisions.

**Mitigation:** Define the assessment context, explain how each component applies, and evaluate whether context-specific scoring guidance is needed.

## 9. Source Reputation and Corroboration Risks

A reputable organization can publish an incorrect statement. Multiple sources can repeat the same underlying error. A lack of corroboration does not automatically mean a claim is false.

**Potential failure modes:**

- Institutional prestige substitutes for claim-level verification.
- Repeated reporting is mistaken for independent confirmation.
- Contradictory evidence is overlooked.
- Absence of corroboration is interpreted as proof of falsity.

**Mitigation:** Assess the specific claim and its supporting evidence. Trace sources to their origins where practicable, distinguish independent evidence from repetition, and record material counterevidence.

## 10. Temporal Relevance Risks

Freshness is not the same as accuracy.

Older evidence can remain authoritative for historical claims or stable findings. Recent information can be incomplete, unreliable, or superseded.

**Potential failure mode:** Recent evidence is automatically favored over older evidence without considering the nature of the claim.

**Mitigation:** Evaluate temporal relevance in relation to the claim, relevant event dates, the rate of change in the subject, and the availability of updated evidence.

## 11. Incomplete or Unreliable Provenance

A traceable source may still be wrong. Conversely, an incomplete record does not necessarily make every statement in it false.

**Potential failure mode:** The provenance score is interpreted as a direct measure of truth or as a guarantee of source integrity.

**Mitigation:** Separate traceability from factual correctness where possible. Document missing information, source transformations, and unresolved authenticity concerns.

## 12. Selection and Confirmation Bias

Researchers may unintentionally choose evidence that supports an existing hypothesis or favor sources that fit prior expectations.

**Potential failure mode:** Component scores reflect the reviewer's preferences rather than consistent assessment criteria.

**Mitigation:** Document search and selection procedures, include credible contradictory evidence, define assessment criteria before scoring where practicable, and use independent reviewers.

## 13. Generalizability

The framework has not been shown to perform consistently across different domains, source types, or decision contexts.

A procedure that appears useful in one setting may be unsuitable in another.

**Potential failure mode:** Findings from a narrow set of examples are generalized to all forms of evidence.

**Mitigation:** Test the framework across varied use cases and document where it works, where it does not, and where additional criteria are necessary.

## 14. Composite Information Loss

Different component profiles can produce the same or similar composite values.

A single score may conceal whether an assessment is limited by freshness, corroboration, source reliability, or provenance.

**Potential failure mode:** Decision-makers rely on the composite without inspecting its underlying components.

**Mitigation:** Report component scores and rationales alongside the composite. Evaluate whether the composite provides enough additional value to justify its use.

## 15. Validation Requirements

Before the framework can be represented as validated, a documented evaluation program should address:

1. **Construct definition:** Specify what the framework is intended to measure and what it is not intended to measure.
2. **Operational scoring:** Define each component and provide consistent scoring anchors.
3. **Reviewer consistency:** Assess agreement between independent reviewers.
4. **Sensitivity analysis:** Determine how changes in input scores affect the composite.
5. **Aggregation comparison:** Compare multiplication with plausible alternative approaches.
6. **Missing-data handling:** Define procedures for unknown, unavailable, and inapplicable components.
7. **Context testing:** Evaluate performance across different evidence types and claim categories.
8. **External evaluation:** Where a suitable independent criterion exists, examine whether the framework's assessments correspond to it.
9. **Independent review:** Obtain critical methodological review where practicable.
10. **Transparent reporting:** Publish procedures, findings, uncertainties, failures, and revisions.

No single test automatically establishes validity. The evaluation must be appropriate to the intended interpretation and use of the framework.

## 16. Conditions for Responsible Use

At its current stage, the framework may be used for exploratory analysis, discussion, and testing of proposed assessment procedures.

It should not be used as the sole basis for consequential decisions, presented as a validated scientific instrument, or used to imply that a numerical result establishes the truth of a claim.

Any exploratory application should preserve the component scores, document reviewer judgments, and state the framework's limitations.

## 17. Review and Revision

This document should be revised when research identifies new limitations, when component definitions change, or when evaluation results reveal unexpected behavior.

Changes to the equation or scoring rules should be reflected consistently in the methodology, worked examples, and repository README.

## 18. Current Assessment

The Evidence Quality Framework is a proposed analytical model whose measurement properties and practical value remain undetermined.

Its principal unresolved questions concern scoring consistency, dimension overlap, temporal and contextual relevance, missing information, mathematical aggregation, and empirical usefulness.

**Final status: Exploratory — not validated.**
