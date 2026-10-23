# References and Source Register

## 1. Purpose

This document records sources relevant to the development, methodological design, critical review, and future evaluation of the Anthological Institute for Research & Governance's Evidence Quality Framework.

The register identifies the contribution and limitations of each source. It is intended to support research traceability, methodological transparency, independent review, and reproducibility.

Inclusion in this register does not imply that a source endorses the framework or validates its proposed scoring model.

## 2. Research Status

The Evidence Quality Framework is exploratory and has not been empirically validated.

Its proposed composite equation is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Where:

- \(q_s\) = source reliability
- \(q_t\) = freshness and temporal relevance
- \(q_c\) = corroboration
- \(q_p\) = provenance and completeness

The sources listed below provide relevant foundations for selected concepts and research practices. They do not, by themselves, establish the validity of this equation, its scoring scales, its multiplicative structure, or its interpretation.

The resulting score must not be interpreted as the probability that a claim is true.

## 3. Source Register

### Source 1 — Data Quality Dimensions

**Title:** Beyond Accuracy: What Data Quality Means to Data Consumers

- **Author or issuing organization:** Richard Y. Wang and Diane M. Strong
- **Publication date:** 1996
- **URL or DOI:** https://doi.org/10.1080/07421222.1996.11518099
- **Date accessed:** October 23, 2026, if confirmed against the institute's research record
- **Relevant claim or method:** Provides a framework for examining data quality beyond accuracy, including contextual relevance, representation, and accessibility. It informs the broader principle that quality assessments should consider multiple dimensions rather than a single accuracy criterion.
- **Source limitations:** The article addresses data quality and consumer requirements. It does not validate the Evidence Quality Framework's proposed dimensions, scoring rules, or multiplicative equation.
- **Independent corroboration:** Compare its data-quality dimensions with the FAIR Guiding Principles and other established data-quality research.
- **Framework application:** Inform the conceptual definition of evidence quality and the identification of dimensions requiring explicit operational definitions.

### Source 2 — Information Provenance

**Title:** PROV-O: The PROV Ontology

- **Author or issuing organization:** World Wide Web Consortium (W3C)
- **Publication date:** April 30, 2013
- **URL or DOI:** https://www.w3.org/TR/prov-o/
- **Date accessed:** October 23, 2026, if confirmed against the institute's research record
- **Relevant claim or method:** Defines an ontology for representing provenance, including entities, activities, and agents involved in producing or transforming information.
- **Source limitations:** PROV-O supports the representation and exchange of provenance information. It does not independently establish whether a source is credible, a claim is correct, or a provenance record is complete.
- **Independent corroboration:** Compare with the FAIR Guiding Principles and other applicable provenance and research-data documentation standards.
- **Framework application:** Inform the documentation of source origins, information transformations, and traceability requirements.

### Source 3 — Artificial Intelligence Risk Governance

**Title:** Artificial Intelligence Risk Management Framework (AI RMF 1.0)

- **Author or issuing organization:** National Institute of Standards and Technology (NIST)
- **Publication date:** January 26, 2023
- **URL or DOI:** https://www.nist.gov/itl/ai-risk-management-framework
- **Date accessed:** October 23, 2026, if confirmed against the institute's research record
- **Relevant claim or method:** Provides a voluntary framework for identifying, assessing, and managing risks associated with AI systems. It offers a governance context for evaluating trustworthiness, documenting limitations, and integrating risk considerations into system development and use.
- **Source limitations:** The framework addresses AI risk management broadly. It does not prescribe or validate the Evidence Quality Framework's equation or individual scoring dimensions.
- **Independent corroboration:** Compare with other authoritative AI governance guidance and applicable technical standards.
- **Framework application:** Inform documentation of risks, assumptions, intended use, limitations, and review procedures when evidence assessments support AI-related decisions.

### Source 4 — Quantitative Uncertainty

**Title:** Evaluation of Measurement Data — Guide to the Expression of Uncertainty in Measurement (JCGM 100:2008)

- **Author or issuing organization:** Joint Committee for Guides in Metrology (JCGM)
- **Publication date:** 2008
- **URL or DOI:** https://doi.org/10.59161/JCGM100-2008E
- **Date accessed:** October 23, 2026, if confirmed against the institute's research record
- **Relevant claim or method:** Establishes principles for evaluating and expressing uncertainty associated with measurement results.
- **Source limitations:** The guide concerns measurement uncertainty. Applying its methods to qualitative evidence judgments or a composite evidence-quality score requires separate justification and may not be directly appropriate without a defined measurement model.
- **Independent corroboration:** Review relevant supplementary guidance on uncertainty propagation, sensitivity analysis, and quantitative modeling.
- **Framework application:** Inform the documentation of uncertainty, assumptions, sensitivity to inputs, and limitations on numerical interpretation.

### Source 5 — Research Data Stewardship

**Title:** The FAIR Guiding Principles for Scientific Data Management and Stewardship

- **Author or issuing organization:** Mark D. Wilkinson et al.
- **Publication date:** March 15, 2016
- **URL or DOI:** https://doi.org/10.1038/sdata.2016.18
- **Date accessed:** October 23, 2026, if confirmed against the institute's research record
- **Relevant claim or method:** Presents principles for making research data and other research objects findable, accessible, interoperable, and reusable.
- **Source limitations:** FAIR principles concern data stewardship and reuse. They do not guarantee that data are accurate, that sources are trustworthy, or that conclusions drawn from the data are valid.
- **Independent corroboration:** Compare with W3C PROV-O and established research data management guidance.
- **Framework application:** Inform research documentation, source discoverability, preservation, and reproducibility practices.

## 4. Cross-Source Synthesis

The five sources address complementary aspects of the framework's proposed research design:

| Research concern | Relevant source | Intended contribution |
|---|---|---|
| Multidimensional data quality | Wang and Strong (1996) | Inform the conceptualization of quality beyond accuracy |
| Provenance and traceability | W3C PROV-O (2013) | Inform the representation of information origins and transformations |
| AI risk and governance | NIST AI RMF 1.0 (2023) | Inform risk documentation and responsible use |
| Quantitative uncertainty | JCGM 100:2008 | Inform uncertainty analysis and cautious numerical interpretation |
| Research-data stewardship | Wilkinson et al. (2016) | Inform discoverability, accessibility, interoperability, and reuse |

These sources should be treated as complementary references, not as interchangeable evidence for the same claim. Each source must be connected to the specific design decision or methodological statement it informs.

## 5. Independent Corroboration and Critical Review

Independent corroboration must be assessed at the level of the individual claim or method, rather than inferred merely because two publications discuss a related topic.

For each important methodological claim, future revisions should:

1. Identify the exact claim being evaluated.
2. Locate independent sources that directly address that claim.
3. Determine whether the sources use independent evidence or rely on the same underlying publication.
4. Record material disagreements, scope restrictions, and methodological differences.
5. Distinguish established findings from interpretations or proposals introduced by the institute.
6. Record **Not yet identified** when suitable independent corroboration has not been located.

A source should not be described as independently corroborating a claim until its relevance and independence have been assessed.

## 6. Implications for the Proposed Composite Equation

The cited literature provides conceptual and methodological context, but additional research is required to assess the proposed equation:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

Future evaluation should explicitly investigate:

- Whether each component has a clear operational definition.
- Whether its scoring scale is meaningful, consistent, and reproducible.
- Whether the components measure distinct aspects of evidence quality or overlap.
- Whether multiplication is theoretically justified.
- How zero or near-zero component scores affect the composite.
- How component scores and the composite respond to changes in assumptions.
- Whether different reviewers produce comparable assessments.
- Whether the composite adds useful information beyond reporting the individual dimensions separately.
- Whether the framework performs adequately across different evidence types and decision contexts.

Empirical testing, documented evaluation criteria, and independent review are necessary before claims of validation are warranted.

## 7. Research Integrity and Maintenance

The source register should be maintained as a living research document.

Contributors must:

- Verify publication details, authorship, dates, and links.
- Record actual access dates rather than assuming a date of review.
- Consult the original publication or authoritative issuing source whenever practicable.
- Connect references to specific statements or methods in the framework.
- Describe source limitations fairly and accurately.
- Distinguish original research, standards, guidance, and secondary commentary.
- Record conflicting evidence and material revisions.
- Avoid presenting a reference as validation when it supports only a related concept.
- Update this register when sources materially change the framework's assumptions or methodology.

## 8. Current Assessment

The five sources establish an initial reference base for examining data quality, provenance, AI governance, quantitative uncertainty, and research-data stewardship.

They do not establish that the proposed Evidence Quality Framework is empirically validated.

**Current framework status: Exploratory — not validated.**

The next research phase is to examine these sources in greater depth, link their specific contributions to the framework's methodology and limitations, identify relevant counterarguments, and develop a documented evaluation plan.
