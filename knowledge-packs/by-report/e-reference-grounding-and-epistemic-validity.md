# E. Reference, Grounding & Epistemic Validity - The Architecture of Warranted Semantic Action

This report closes Volume I of the Semantic-Semiotic Intelligence (SSI) canon. Reports A–D built the meaning-machine: representation, signs, linguistic structure, and conceptual organization. Report E evaluates whether those meanings are actually grounded, warranted, scoped, sourced, and reliable enough to guide belief or action.

**Thesis**: Epistemic validity is the disciplined evaluation of the relation between a claim, its referent, its truth conditions, its evidence, its source, its grounding path, and the confidence warranted by that relation. Semantic intelligence becomes trustworthy when it can distinguish meaning from truth, citation from support, source statement from settled fact, retrieval from grounding, plausibility from warrant, and confidence from certainty.

The report orbits one central question: **What does this expression or source claim, what would make it true, what grounds it, who says so, by what method, under what scope, and with what warranted confidence may it be used?**

## **1. The Epistemic Ontology**

To prevent semantic wobble in later reports, the following primitives are established as the canonical vocabulary of warrant:

| Primitive | Definition |
| :---- | :---- |
| Claim | A specific assertive act putting forward a proposition as true.1 |
| Referent | The object, state, or entity in reality to which a term or claim "hooks".3 |
| Proposition | The abstract meaning or content capable of being true or false.5 |
| Truth Condition | The specific state of the world required for a proposition to be true.5 |
| Evidence | Information (data, testimony, records) used to support a claim.8 |
| Source | The entity (witness, researcher, sensor) providing the evidence.10 |
| Source Relation | The proximity, competence, and incentive structure of a source.10 |
| Grounding Path | The traceable chain of justification from claim to referent.13 |
| Warrant | The degree of positive epistemic status or justification possessed by a claim.1 |
| Defeater | Information that cancels or downgrades a claim's justification.1 |
| Confidence | An internal rating of the strength of the evidence and logic.16 |
| Uncertainty | The recognized gap between current warrant and certainty.12 |
| Permissible Use | The bounded domain where a claim may legitimately guide action.19 |

## **2. Reference Theory and Truth Conditions**

Meaning begins with the referential hook. Proper names (e.g., Barack Obama) serve as rigid designators, while descriptions pick out referents by their properties.3 Indexicals (I, here, now) shift reference based on context.22 Without map/territory discipline and context-awareness, RAG systems often suffer from indexical collapse—treating a statement like "the policy was updated yesterday" as a permanent truth.24

Truth-conditional and model-theoretic semantics clarify that to understand a claim is to know what world-state would satisfy it.6 A proposition is satisfied within a model (e.g., a simulation or an AI's internal representation), but it only attains epistemic validity when grounded in the world-state it purports to describe.6

## **3. Grounding Modes and Evidence Ecology**

Grounding converts meaning into warranted belief. The canon recognizes eleven primary modes:

* **Perceptual**: Direct sensory observation; vulnerable to "barn facade" scenarios.1  
* **Measurement**: Quantitative data from sensors; requires construct validity and operationalization.28  
* **Documentary**: Persistence in records; depends on provenance and metadata.19  
* **Testimonial**: Reliance on others' reports; requires evaluating the source's reliability and ability to deceive.10  
* **Institutional**: Warrant derived from authoritative bodies (e.g., WHO, courts).30  
* **Legal**: Defined by specific standards of proof (e.g., preponderance of evidence).32  
* **Statistical**: Aggregated data patterns; prone to inflating association into causation.34  
* **Causal**: Established mechanisms (e.g., randomized controlled trials).13  
* **Computational/Model-based**: Outputs from algorithms; must be distinguished from direct observation.36  
* **Operational**: Verification of system performance against specifications.37  
* **Social-Recognition**: Common ground established via communal norms or shared history.39

### **Evidence Ecology**

There is no universal hierarchy. Clinical trials (Level 1) ground medical efficacy 41, while statutes and court rulings ground legal claims.32 Software traces and formal proofs (EAL7) ground security claims.42 Expert opinion (Level 5) is useful for rare cases but remains the weakest grounding for empirical facts.41

## **4. Claim-Type / Warrant-Standard Matrix**

| Claim Type | Appropriate Evidence Standard | Common Overclaim | Posture |
| :---- | :---- | :---- | :---- |
| Empirical | Measurement/Observation | "Fact" based on single anecdote | Demand replication 35 |
| Causal | Level 1 RCT / Meta-analysis | "Causes" based on association | Mark as association 34 |
| Legal | Statute / Binding Precedent | Allegation as settled truth | Attribute to source 32 |
| Medical | Peer-reviewed systematic review | Generalizing from case report | Note scope limits 41 |
| Software | Formal proof / V&V artifacts | "Secure" based on unit test | Identify test gaps 37 |
| Forecast | Model-based probabilistic data | "Will happen" (certainty) | Use WEP terms 16 |
| Evaluative | Expert consensus (Level 4) | Opinion as empirical finding | Label as judgment 43 |

## **5. Source Relation and the Citation Support Test**

A source’s proximity to the referent (primary vs. secondary) and its incentive structure (advocate vs. neutral regulator) determine warrant.10 Expert status in one domain (e.g., physics) does not grant warrant in another (e.g., policy).12

**The Citation Support Test**:

1. **Same Proposition?** Does the source actually state the claim? 9  
2. **Same Scope?** Does the source support the claim for the same population/time? 36  
3. **Same Modality?** Does the source say "will" or just "may"? 12  
4. **Same Boundary?** Does the source use the same category definitions? 45

## **6. RAG-Ready Artifacts for the Omnibus**

### **Claim-Warrant Record (CWR)**

A structured log for chaque critical claim: | | [Grounding Mode] | | | [Confidence] | [Permissible Use].

### **RAG Answer-Support Taxonomy**

Used to classify retrieved context relative to a generated answer:

* **Direct Support**: Citation explicitly confirms the claim.30  
* **Inferential Support**: Claim is logically implied by the citation.8  
* **Weak Support**: Citation discusses the topic but does not ground the claim.28  
* **No Support**: Citation is irrelevant to the specific claim.9  
* **Contradicted**: Citation denies the claim.1  
* **Attribution Stripped**: Claim is correct but lacks the required pointer to a source.24

### **Defeater Scan**

A mandatory check for rebutting defeaters (reasons to believe not-p) and undercutting defeaters (reasons to doubt the connection between evidence and claim).15

## **7. Failure Modes and Repair Moves**

| Failure Mode | Description | Repair Move |
| :---- | :---- | :---- |
| Citation-Support Mismatch | Citation is topically relevant but doesn't support the answer 9 | Narrow the claim to match the citation |
| Attribution Stripping | Presenting an expert opinion as an objective fact 24 | Re-insert attribution: "According to X..." |
| Authority Laundering | Hiding a biased source behind a neutral-sounding AI 51 | Reveal the source's name and incentives |
| Fake Precision | Using numbers (91% certain) for qualitative warrant 1 | Revert to WEP: "Highly Likely" 18 |
| Retrieval as Grounding | Mistaking "I found a document" for "The claim is true" 36 | Mark as "retrieved claim" |
| Association to Causation | Inflating an observed link into a causal law 13 | Downgrade to "associated with" |
| Stale Source | Using a superseded policy or outdated measurement 8 | Check dating discipline (Report A) |

## **8. Before and After: Epistemically Disciplined Behavior**

* **Scenario: Stale Policy**  
  * *Naive*: "The company policy is to provide 20 days of vacation."  
  * *Disciplined*: "The 2022 Employee Handbook states 20 days, but this source is stale. According to a 2024 HR memo, the policy has been updated to 25 days. Confidence: High."  
* **Scenario: Association vs. Causation**  
  * *Naive*: "Studies prove that eating apples causes weight loss."  
  * *Disciplined*: "Observational studies show a statistical association between apple consumption and weight loss. However, these studies do not establish causation. Confidence: Moderate."  
* **Scenario: Authority for Definitions**  
  * *Naive*: "The law says fraud is common in this industry."  
  * *Disciplined*: "The statute provides the legal definition of fraud. While an industry report claims fraud is common, the statute itself is authoritative for definitions, not for empirical frequency. Confidence: Low."

## **What Report E Gives the Canon**

Report E turns Volume I from a theory of meaning into a disciplined architecture for warranted semantic action. It ensures that semantic intelligence can say:

* "This source states the claim, but does not prove it."  
* "The evidence supports a narrower claim."  
* "This is an attributed allegation, not an established fact."  
* "The retrieved chunk is topically relevant but not claim-supportive."

By integrating Reports A–D, Report E provides the **Warrant Discipline** necessary to prevent meaning-machines from becoming misinformation-machines. Volume I is now complete.

#### **Works cited**

1. Defeaters in Epistemology | Internet Encyclopedia of Philosophy, accessed May 14, 2026, [https://iep.utm.edu/defeaters-in-epistemology/](https://iep.utm.edu/defeaters-in-epistemology/)  
2. Gettier problem - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Gettier_problem](https://en.wikipedia.org/wiki/Gettier_problem)  
3. Reference (Stanford Encyclopedia of Philosophy), accessed May 14, 2026, [https://plato.stanford.edu/entries/reference/](https://plato.stanford.edu/entries/reference/)  
4. Reference (Stanford Encyclopedia of Philosophy/Fall 2018 Edition), accessed May 14, 2026, [https://plato.stanford.edu/archives/fall2018/entries/reference/](https://plato.stanford.edu/archives/fall2018/entries/reference/)  
5. Truth-conditional semantics - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Truth-conditional_semantics](https://en.wikipedia.org/wiki/Truth-conditional_semantics)  
6. 7. Model-theoretic semantics | Request PDF - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/331226825_7_Model-theoretic_semantics](https://www.researchgate.net/publication/331226825_7_Model-theoretic_semantics)  
7. Carston: Truth-conditional semantics - John Benjamins Publishing Company, accessed May 14, 2026, [https://benjamins.com/online/hop/articles/tru1](https://benjamins.com/online/hop/articles/tru1)  
8. Evaluating Answer Quality in RAG Systems: Precision, Recall, and Faithfulness - Cobbai, accessed May 14, 2026, [https://cobbai.com/blog/evaluate-rag-answers](https://cobbai.com/blog/evaluate-rag-answers)  
9. RAG evaluation metrics: How to evaluate your RAG pipeline with Braintrust - Articles, accessed May 14, 2026, [https://www.braintrust.dev/articles/rag-evaluation-metrics](https://www.braintrust.dev/articles/rag-evaluation-metrics)  
10. Epistemology of Testimony | Internet Encyclopedia of Philosophy, accessed May 14, 2026, [https://iep.utm.edu/ep-testi/](https://iep.utm.edu/ep-testi/)  
11. Impacts of Adversarial Use of Generative AI on Homeland Security, accessed May 14, 2026, [https://www.dhs.gov/sites/default/files/2025-01/25_0110_st_impacts_of_adversarial_generative_aI_on_homeland_security_0.pdf](https://www.dhs.gov/sites/default/files/2025-01/25_0110_st_impacts_of_adversarial_generative_aI_on_homeland_security_0.pdf)  
12. Words of Estimative Probability, Analytic Confidences, and Structured Analytic Techniques, accessed May 14, 2026, [https://www.cisecurity.org/ms-isac/services/words-of-estimative-probability-analytic-confidences-and-structured-analytic-techniques](https://www.cisecurity.org/ms-isac/services/words-of-estimative-probability-analytic-confidences-and-structured-analytic-techniques)  
13. RAG Evaluation in Practice: Faithfulness, Context Recall & Answer Relevancy - Kinde, accessed May 14, 2026, [https://kinde.com/learn/ai-for-software-engineering/best-practice/rag-evaluation-in-practice-faithfulness-context-recall-answer-relevancy/](https://kinde.com/learn/ai-for-software-engineering/best-practice/rag-evaluation-in-practice-faithfulness-context-recall-answer-relevancy/)  
14. A complete guide to RAG evaluation: metrics, testing and best practices - Evidently AI, accessed May 14, 2026, [https://www.evidentlyai.com/llm-guide/rag-evaluation](https://www.evidentlyai.com/llm-guide/rag-evaluation)  
15. Defeasible reasoning with variable degrees of justification - John Horty, accessed May 14, 2026, [http://www.horty.umiacs.io/courses/readings/pollock-2001-var-deg-just.pdf](http://www.horty.umiacs.io/courses/readings/pollock-2001-var-deg-just.pdf)  
16. Words of estimative probability - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Words_of_estimative_probability](https://en.wikipedia.org/wiki/Words_of_estimative_probability)  
17. Analytic Standards - ODNI, accessed May 14, 2026, [https://www.dni.gov/files/documents/ICD/ICD-203.pdf](https://www.dni.gov/files/documents/ICD/ICD-203.pdf)  
18. The Generative AI Paradox: GenAI and the Erosion of Trust, the Corrosion of Information Verification, and the Demise of Truth - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.00306v1](https://arxiv.org/html/2601.00306v1)  
19. What is ISO 27001 Labelling of Information? - High Table, accessed May 14, 2026, [https://hightable.io/iso-27001-glossary-of-terms/labelling-of-information/](https://hightable.io/iso-27001-glossary-of-terms/labelling-of-information/)  
20. ISO 27001 Data Labeling Guidelines - Cycore Secure, accessed May 14, 2026, [https://www.cycoresecure.com/blogs/iso-27001-data-labeling-guidelines](https://www.cycoresecure.com/blogs/iso-27001-data-labeling-guidelines)  
21. Grounding Theory in Digital Data: A Methodological Approach for a Reflective Procedural Framework - Cultural Analytics, accessed May 14, 2026, [https://culturalanalytics.org/article/1296/galley/664/download/](https://culturalanalytics.org/article/1296/galley/664/download/)  
22. Indexicals - Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/indexicals/](https://plato.stanford.edu/entries/indexicals/)  
23. Demonstratives and Indexicals | Internet Encyclopedia of Philosophy, accessed May 14, 2026, [https://iep.utm.edu/demonstratives-and-indexicals/](https://iep.utm.edu/demonstratives-and-indexicals/)  
24. Detecting Hallucinations in Retrieval-Augmented Generation via Semantic-level Internal Reasoning Graph - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.03052v1](https://arxiv.org/html/2601.03052v1)  
25. Truth-Conditional Semantics Overview | PDF - Scribd, accessed May 14, 2026, [https://www.scribd.com/document/948022332/Truth-Conditional-Theory](https://www.scribd.com/document/948022332/Truth-Conditional-Theory)  
26. Formal Methods - Electrical and Computer Engineering, accessed May 14, 2026, [https://users.ece.cmu.edu/~koopman/des_s99/formal_methods/](https://users.ece.cmu.edu/~koopman/des_s99/formal_methods/)  
27. Computational Grounded Cognition: a new alliance between grounded cognition and computational modeling - PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC3551279/](https://pmc.ncbi.nlm.nih.gov/articles/PMC3551279/)  
28. Types of Measurement Validity - Research Methods Knowledge Base - Conjointly, accessed May 14, 2026, [https://conjointly.com/kb/measurement-validity-types/](https://conjointly.com/kb/measurement-validity-types/)  
29. Chapter 3 Operational Definitions & Measurement | Research Methods Course Pack, accessed May 14, 2026, [https://www.davidschuster.info/books/methods/operational-definitions-measurement.html](https://www.davidschuster.info/books/methods/operational-definitions-measurement.html)  
30. RAG Evaluation Metrics: Assessing Answer Relevancy, Faithfulness, Contextual Relevancy, And More - Confident AI, accessed May 14, 2026, [https://www.confident-ai.com/blog/rag-evaluation-metrics-answer-relevancy-faithfulness-and-more](https://www.confident-ai.com/blog/rag-evaluation-metrics-answer-relevancy-faithfulness-and-more)  
31. “Indirect” Information: The Debate on Testimony in Social Epistemology and Its Role in the Game of “Giving and Asking for Reasons” - MDPI, accessed May 14, 2026, [https://www.mdpi.com/2078-2489/10/3/101](https://www.mdpi.com/2078-2489/10/3/101)  
32. Understanding Legal Standards of Proof - Nolo, accessed May 14, 2026, [https://www.nolo.com/legal-encyclopedia/legal-standards-proof.html](https://www.nolo.com/legal-encyclopedia/legal-standards-proof.html)  
33. Legal vs. Quantified Definitions of Standards of Proof - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/226790981_Legal_vs_Quantified_Definitions_of_Standards_of_Proof](https://www.researchgate.net/publication/226790981_Legal_vs_Quantified_Definitions_of_Standards_of_Proof)  
34. What Should I Cite? A RAG Benchmark for Academic Citation Prediction - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.14949v2](https://arxiv.org/html/2601.14949v2)  
35. Levels of Scientific Evidence Guide - Michigan OPEN, accessed May 14, 2026, [https://michigan-open.org/resource/levels-of-scientific-evidence-guide/](https://michigan-open.org/resource/levels-of-scientific-evidence-guide/)  
36. Facet-Level Tracing of Evidence Uncertainty and Hallucination in RAG - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2604.09174v1](https://arxiv.org/html/2604.09174v1)  
37. Software verification and validation - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Software_verification_and_validation](https://en.wikipedia.org/wiki/Software_verification_and_validation)  
38. Software Testing Methodologies Guide: A High-Level Overview - Parasoft, accessed May 14, 2026, [https://www.parasoft.com/blog/software-testing-methodologies-guide-a-high-level-overview/](https://www.parasoft.com/blog/software-testing-methodologies-guide-a-high-level-overview/)  
39. Social Epistemology - Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/epistemology-social/](https://plato.stanford.edu/entries/epistemology-social/)  
40. Computational Grounding: An Overview of Common Ground Applications in Conversational Agents - OpenEdition Journals, accessed May 14, 2026, [https://journals.openedition.org/ijcol/890](https://journals.openedition.org/ijcol/890)  
41. Understanding the Levels of Evidence in Medical Research - PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12064251/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12064251/)  
42. Formal verification - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Formal_verification](https://en.wikipedia.org/wiki/Formal_verification)  
43. R25-1161 The Hierarchy of Health Research Evidence, accessed May 14, 2026, [https://content.leg.colorado.gov/sites/default/files/r25-1161-the-hierarchy-of-health-research-evidence-accessible.pdf](https://content.leg.colorado.gov/sites/default/files/r25-1161-the-hierarchy-of-health-research-evidence-accessible.pdf)  
44. Benchmarking LLM Faithfulness in RAG with Evolving Leaderboards - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2505.04847v2](https://arxiv.org/html/2505.04847v2)  
45. Prediction Laundering: The Illusion of Neutrality, Transparency, and Governance in Polymarket - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2602.05181v1](https://arxiv.org/html/2602.05181v1)  
46. Benchmarking LLM Hallucinations : r/datascience - Reddit, accessed May 14, 2026, [https://www.reddit.com/r/datascience/comments/1sy6tzq/benchmarking_llm_hallucinations/](https://www.reddit.com/r/datascience/comments/1sy6tzq/benchmarking_llm_hallucinations/)  
47. [2603.10143] Reason and Verify: A Framework for Faithful Retrieval-Augmented Generation, accessed May 14, 2026, [https://arxiv.org/abs/2603.10143](https://arxiv.org/abs/2603.10143)  
48. Grounding for a Computational Model of Place - MIT Media Lab, accessed May 14, 2026, [https://www.media.mit.edu/publications/grounding-for-a-computational-model-of-place/](https://www.media.mit.edu/publications/grounding-for-a-computational-model-of-place/)  
49. The Evolution of Defeaters: A Taxonomy - ScholarWorks@UARK, accessed May 14, 2026, [https://scholarworks.uark.edu/cgi/viewcontent.cgi?article=5871&context=etd](https://scholarworks.uark.edu/cgi/viewcontent.cgi?article=5871&context=etd)  
50. Evaluating Faithfulness in Agentic RAG Systems for e-Governance Applications Using LLM-Based Judging Frameworks - MDPI, accessed May 14, 2026, [https://www.mdpi.com/2504-2289/9/12/309](https://www.mdpi.com/2504-2289/9/12/309)  
51. Laundering AI Authority with Adversarial Examples - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2605.04261v1](https://arxiv.org/html/2605.04261v1)  
52. Formal verification of software, as the article acknowledges, relies heavily on ... - Hacker News, accessed May 14, 2026, [https://news.ycombinator.com/item?id=42656639](https://news.ycombinator.com/item?id=42656639)  
53. RAG Evaluation Metrics: Answer Relevancy, Faithfulness, and Real-World Accuracy, accessed May 14, 2026, [https://deepchecks.com/rag-evaluation-metrics-answer-relevancy-faithfulness-accuracy/](https://deepchecks.com/rag-evaluation-metrics-answer-relevancy-faithfulness-accuracy/)

---