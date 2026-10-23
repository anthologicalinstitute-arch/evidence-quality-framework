# Evidence Quality Framework

**Research project:** Anthological Institute for Research & Governance  
**Status:** Exploratory — not validated  
**Research area:** Evidence assessment, data quality, information provenance, and analytical methodology

## Overview

The Evidence Quality Framework is a proposed analytical approach for examining the characteristics that affect the usability and reliability of evidence.

It organizes assessment around four dimensions:

- Source reliability
- Freshness and temporal relevance
- Corroboration
- Provenance and completeness

The framework explores whether these dimensions can be combined into a useful composite indicator. Its definitions, scoring rules, and mathematical structure remain subject to research, critical review, and empirical evaluation.

## Proposed Composite Equation

The current exploratory formulation is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Where:

- \(Q_e\) = proposed evidence-quality composite
- \(q_s\) = source reliability score
- \(q_t\) = freshness and temporal relevance score
- \(q_c\) = corroboration score
- \(q_p\) = provenance and completeness score

Each component is intended to be represented by a score on a normalized scale from 0 to 1. The operational definitions, scoring anchors, and appropriate use of that scale require further specification and evaluation.

The equation is a research proposal, not an established or validated measurement method.

## Interpretation and Research Safeguards

**The composite is not the probability that a claim is true.**

A numerical result represents only the output of the proposed calculation under the selected inputs and assumptions. It does not, by itself, establish factual accuracy, causal validity, statistical confidence, or the probability that a claim is correct.

The composite must not be presented as a validated measure of truth, a calibrated confidence estimate, or a universal ranking of evidence.

In particular:

- Scores depend on the definitions and judgments used to assign component values.
- Multiplication can substantially reduce the composite when any component is low.
- A zero component forces the composite to zero, regardless of the other components.
- The dimensions may overlap or depend on one another.
- A precise numerical output can create a misleading impression of objectivity.
- Different evidence types and decision contexts may require different assessment criteria.

These issues are central research questions, not resolved properties of the framework.

## Research Objectives

The project aims to:

1. Define each evidence-quality dimension in operational terms.
2. Develop transparent and reproducible scoring criteria.
3. Examine whether the four dimensions are sufficiently distinct.
4. Evaluate the mathematical assumptions behind multiplicative aggregation.
5. Test sensitivity to component scores and alternative scoring approaches.
6. Assess consistency between independent reviewers.
7. Document uncertainty, counterarguments, and limitations.
8. Determine whether a composite adds value beyond reporting component scores separately.

## Repository Documents

- [`methodology.md`](methodology.md) — Proposed model, definitions, assumptions, and evaluation plan.
- [`worked-examples.md`](worked-examples.md) — Illustrative calculations and interpretation guidance.
- [`limitations.md`](limitations.md) — Known risks, unresolved questions, and potential failure modes.
- [`references.md`](references.md) — Research sources, source limitations, and corroboration requirements.

## Methodological Principles

The project follows these principles:

- **Transparency:** State assumptions, definitions, and scoring procedures explicitly.
- **Traceability:** Connect methodological choices to documented sources or identify them as institute proposals.
- **Reproducibility:** Make calculations and examples independently repeatable.
- **Critical review:** Investigate weaknesses and counterarguments, not only supporting evidence.
- **Proportionate interpretation:** Do not make stronger claims than the available evidence warrants.
- **Revision:** Update the framework when research reveals defects or better approaches.

## Research and Validation Plan

The proposed model requires further work before its validity or practical utility can be established.

Planned evaluation includes:

1. Reviewing the literature relevant to evidence quality and data assessment.
2. Defining component scales and scoring anchors.
3. Examining overlap and dependence between dimensions.
4. Comparing multiplicative aggregation with alternative approaches.
5. Conducting sensitivity and robustness analyses.
6. Testing inter-reviewer consistency.
7. Documenting findings, including negative or inconclusive results.
8. Obtaining independent methodological review where practicable.

No validation outcome is claimed at this stage.

## Contributions and Review

Research contributions should identify their assumptions, sources, methods, and limitations. Suggested changes should explain the problem being addressed and provide a rationale for the proposed solution.

Material changes to the equation, component definitions, or scoring procedures should be documented so that prior versions and examples can be interpreted correctly.

## Current Status

**Exploratory — not validated.**

The Evidence Quality Framework is a proposed research model. Its composite equation and operational scoring system must undergo
