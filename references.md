# References and Source Register

## 1. Purpose

This document records sources relevant to the development, critical review, and future evaluation of the Evidence Quality Framework maintained by the Anthological Institute for Research & Governance.

The register identifies each source's contribution, limitations, and intended application. It supports research traceability, methodological transparency, and independent review.

Inclusion in this register does not mean that a source endorses the framework or validates its proposed equation.

## 2. Research Status

The Evidence Quality Framework is **exploratory — not validated**.

Its current proposed composite is:

\[
Q_e = q_s \times q_t \times q_c \times q_p
\]

The sources below inform related research concepts and practices. They do not, by themselves, validate the proposed component definitions, scoring scales, multiplicative structure, or interpretation.

The composite must not be interpreted as the probability that a claim is true.

## 3. Source Register

### Source 1 — Data Quality Dimensions

**Title:** Beyond Accuracy: What Data Quality Means to Data Consumers

- **Authors:** Richard Y. Wang and Diane M. Strong
- **Publication year:** 1996
- **Publication venue:** Journal of Management Information Systems, 12(4), 5–33
- **URL or DOI:** https://doi.org/10.1080/07421222.1996.11518099
- **Date accessed:** Record the date the original publication was actually consulted.
- **Relevant claim or method:** Examines data quality from the perspective of data consumers and develops a multidimensional view of quality beyond accuracy alone.
- **Relevance to this framework:** Provides conceptual context for assessing several characteristics of evidence rather than relying on a single quality criterion.
- **Source limitations:** The study concerns data quality and consumer requirements. It does not establish that the four dimensions proposed by this framework are sufficient, independent, or suitable for multiplication.
- **Independent corroboration:** Compare relevant concepts with the FAIR Guiding Principles and other data-quality research. Verify whether each comparison supports the same specific claim.
- **Status of application:** Conceptual reference; the framework's own operational definitions remain to be developed and evaluated.

### Source 2 — Information Provenance

**Title:** PROV-O: The PROV Ontology

- **Issuing organization:** World Wide Web Consortium (W3C)
- **Publication date:** April 30, 2013
- **Document type:** W3C Recommendation
- **URL:** https://www.w3.org/TR/prov-o/
- **Date accessed:** Record the date the original document was actually consulted.
- **Relevant claim or method:** Provides an ontology for representing provenance, including entities, activities, and agents involved in producing or transforming information.
- **Relevance to this framework:** Informs the documentation of information origins, transformations, and traceability.
- **Source limitations:** A provenance representation does not by itself establish that a source is credible, a claim is accurate, or a record is complete.
- **Independent corroboration:** Compare with established research-data management guidance and other applicable provenance standards.
- **Status of application:** Technical reference for provenance representation; no evidence-quality scoring method is validated by its inclusion.

### Source 3 — AI Risk Governance

**Title:** Artificial Intelligence Risk Management Framework (AI RMF 1.0)

- **Issuing organization:** National Institute of Standards and Technology (NIST)
- **Publication date:** January 26, 2023
- **Publication identifier:** NIST AI 100-1
- **URL:** https://doi.org/10.6028/NIST.AI.100-1
- **Framework information:** https://www.nist.gov/itl/ai-risk-management-framework
- **Date accessed:** Record the date the original publication was actually consulted.
- **Relevant claim or method:** Provides a voluntary framework for managing risks associated with AI systems and addressing trustworthiness throughout relevant system activities.
- **Relevance to this framework:** Offers governance context for documenting assumptions, risks, intended use, limitations, and responsible interpretation.
- **Source limitations:** The NIST framework addresses AI risk management broadly. It does not prescribe or validate this repository's proposed evidence-quality equation.
- **Independent corroboration:** Compare with other authoritative AI governance guidance, noting differences in scope and purpose.
- **Status of application:** Governance reference; not validation of the composite model.

### Source 4 — Quantitative Uncertainty

**Title:** Evaluation of Measurement Data — Guide to the Expression of Uncertainty in Measurement

- **Issuing organization:** Joint Committee for Guides in Metrology (JCGM)
- **Publication year:** 2008
- **Publication identifier:** JCGM 100:2008
- **URL or DOI:** https://doi.org/10.59161/JCGM100-2008E
- **Date accessed:** Record the date the original publication was actually consulted.
- **Relevant claim or method:** Provides principles for evaluating and expressing uncertainty associated with measurement results.
- **Relevance to this framework:** Offers methodological context for discussing uncertainty, assumptions, and the limits of quantitative interpretation.
- **Source limitations:** The guide concerns measurement uncertainty. Its direct applicability to qualitative evidence judgments and this proposed composite has not been established.
- **Independent corroboration:** Consult relevant guidance on uncertainty propagation, sensitivity analysis, and quantitative modeling. Document which methods are applicable and why.
- **Status of application:** Methodological reference for further investigation; it does not validate the proposed component scores or their multiplication.

### Source 5 — Research Data Stewardship

**Title:** The FAIR Guiding Principles for Scientific Data Management and Stewardship

- **Authors:** Mark D. Wilkinson et al.
- **Publication date:** March 15, 2016
- **Publication venue:** Scientific Data, 3, Article 160018
- **URL or DOI:** https://doi.org/10.1038/sdata.2016.18
- **Date accessed:** Record the date the original publication was actually consulted.
- **Relevant claim or method:** Presents principles for making research data findable, accessible, interoperable, and reusable.
- **Relevance to this framework:** Informs research documentation, discoverability, traceability, preservation, and reuse.
- **Source limitations:** FAIR data principles do not guarantee the accuracy of data, the credibility of a source, or the validity of conclusions drawn from information.
- **Independent corroboration:** Compare with W3C PROV-O and relevant research-data stewardship guidance.
- **Status of application:** Research-data stewardship reference; not validation of the proposed scoring model.

## 4. Cross-Source Synthesis

The sources address different but complementary concerns.

| Research concern | Source | Intended contribution |
|---|---|---|
| Multidimensional data quality | Wang and Strong (1996) | Inform the conceptualization of quality beyond accuracy |
| Provenance and traceability | W3C PROV-O (2013) | Inform structured representation of information origins and transformations |
| AI risk governance | NIST AI RMF 1.0 (2023) | Inform risk documentation and responsible use |
| Quantitative uncertainty | JCGM 100:2008 | Inform investigation of uncertainty and quantitative interpretation |
| Research-data stewardship | Wilkinson et al. (2016) | Inform discoverability, accessibility, interoperability, and reuse |

These sources should not be treated as interchangeable evidence for the same claim. Each should be cited in the methodology only where its content supports the specific statement being made.

## 5. Independent Corroboration

Independent corroboration must be assessed for the specific claim or method under review.

Two sources are not necessarily independent merely because they have different titles or publishers. They may rely on the same underlying data, publication, or original assertion.

For important methodological claims, the research process should:

1. State the claim precisely.
2. Identify sources that directly address it.
3. Determine whether their evidence is independent.
4. Compare methods, scope, and relevant limitations.
5. Document conflicting findings or interpretations.
6. Record **Not yet identified** when suitable corroboration has not been located.

Do not describe a claim as independently corroborated until the relevant evidence has been examined.

## 6. Research Questions Not Resolved by These Sources

The references do not establish:

- That the four proposed dimensions adequately capture evidence quality.
- That each dimension can be scored reliably on a scale from 0 to 1.
- That the component scores are comparable across different evidence types.
- That the dimensions are independent or free from substantial overlap.
- That multiplication is the appropriate aggregation rule.
- That a particular composite threshold corresponds to a meaningful level of evidence quality.
- That the composite predicts factual accuracy or the truth of a claim.

These questions require separate theoretical development, operational definitions, and appropriate empirical evaluation.

## 7. Source Verification and Maintenance

Before treating an entry as fully reviewed:

- Consult the original publication or authoritative issuing source.
- Verify the title, authorship, publication details, and link.
- Record the actual access date.
- Confirm that the cited material supports the stated relevance.
- Document any important qualification or disagreement.
- Update the entry if subsequent review changes the interpretation.

A source identified for future review should be labeled as pending rather than described as fully evaluated.

## 8. Research Integrity

The register must distinguish among:

- Established findings reported by a source.
- Guidance or standards issued by an organization.
- Interpretations made by the institute.
- Proposed methods that remain untested.
- Empirical findings generated by future evaluation.

References must not be used to imply endorsement or validation that the original source does not provide.

## 9. Current Assessment

These five sources provide an initial literature foundation for research into data quality, provenance, AI governance, uncertainty, and research-data stewardship.

They provide context for developing the Evidence Quality Framework, but they do not validate its proposed composite equation.

**Current status: Exploratory — not validated.**

Further literature review, operational specification, sensitivity analysis, reviewer-consistency testing, and independent methodological assessment are needed before the framework's validity or practical utility can be established.
