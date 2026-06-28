# N. Knowledge Infrastructure, Artifacts & Assistant Governance - The Execution Layer of the Semantic-Semiotic Intelligence Canon

The culmination of the Semantic-Semiotic Intelligence (SSI) canon necessitates a transition from theoretical frameworks—those of instability layers, transfer discipline, and diagnostic pathology—into a functional, operational execution layer. Report N serves as this transition, defining the parameters through which a knowledge infrastructure is designed not as a static repository of semantic records, but as a dynamic environment of reusable lenses and minimal metadata hooks. The core thesis of this final report is that semantic intelligence reaches the level of infrastructure when meanings, claims, sources, senses, symbols, and pathologies can be selectively retrieved and tested at runtime.1 This avoids the pitfalls of semantic bureaucracy, wherein the act of interpretation is transformed into a cumbersome administrative burden, and instead focuses on assistant protocols that activate specific interpretive lenses only when justified by the complexity of the query or the risk of the domain.4

## **The Principle of Ontological Minimalism and Active Metadata**

In traditional knowledge management, the tendency is toward the "mass production" of semantic records—a sprawling, multi-year academic effort to model the entire enterprise. Within the SSI canon, such an approach is rejected in favor of ontological minimalism. This principle dictates that a formal, machine-readable framework should define concepts, relationships, and rules only within specific, high-priority domains where an AI assistant’s judgment is actively engaged.1 An ontology in this context is the structural layer between raw metadata and intelligent action, allowing the system to move beyond statistical pattern matching to logical inference.1

The implementation of this layer begins with the identification of 3–5 priority domains—such as financial metrics, customer entities, or product hierarchies—where AI agents are most active.1 Rather than constructing these from scratch, the SSI execution layer advocates for bootstrapping from existing semantic assets. Current research indicates that approximately 40–60% of an organization’s ontology is already scattered across business glossaries, semantic models, and schema documentation.1 The infrastructure’s task is consolidation, not creation.

| Ontology Construction Phase | Operational Objective | Semantic Artifact Generated |
| :---- | :---- | :---- |
| Priority Domain Selection | Narrow the focus to active AI use cases (e.g., Q3 spending analysis). | Domain Boundary Definitions 1 |
| Semantic Asset Audit | Inventory existing glossaries and lineage in disconnected apps. | Consolidation Map 1 |
| Class and Property Definition | Identify core entities (T-Box) and their attributes (e.g., Currency). | T-Box Schema 1 |
| Relationship Mapping | Define logic (e.g., "Revenue includes Subscription_Revenue"). | Constraint Graph 1 |
| Metadata Connectivity | Link ontology classes to physical tables and columns. | Lineage-Backed Graph 1 |

This consolidation must account for the reality of semantic fragmentation. With organizations averaging nearly 900 applications and only 28% being integrated, meanings are frequently lost in the technical silos.1 The knowledge infrastructure serves as the unifying "meaning plane," ensuring that a concept like "Revenue" is consistently understood across different data pipelines.2 When this infrastructure is linked to live metadata through column-level lineage, it transforms from a theoretical model into a set of operational signals that the assistant can query during inference.1

### **The T-Box and A-Box Distinction in Assistant Reasoning**

A critical component of avoiding semantic bureaucracy is the rigorous separation of the terminological component (T-Box) and the assertional component (A-Box). The T-Box defines "what things are"—the categories and classes—while the A-Box contains "what things do"—the specific instances and facts.1 For an AI assistant, the T-Box acts as the "lens" that defines the scope of valid operations and inferences. For example, a T-Box rule might specify that "a Customer must have exactly one primary Account," which the assistant then uses as a logical constraint when processing specific customer data in the A-Box.1

This distinction allows the knowledge infrastructure to remain lightweight. The assistant does not need to load the entire graph of instances; it only needs to activate the relevant slice of the T-Box schema to guide its reasoning. This selective activation is the primary mechanism of the "reusable lens." When the assistant identifies that a user is asking about "Subscription Revenue," it retrieves the class "Revenue" and its associated properties and constraints, providing a structured context that reduces the risk of hallucination.4

### **Operationalizing Logic and Constraints**

The move from statistical recall to logical reasoning requires the encoding of rich lateral connections and business rules. Teams that define explicit cardinality constraints within their ontology reduce downstream data quality incidents by significant margins.1 In the SSI canon, these constraints are not merely documentation; they are active gating mechanisms. If an assistant attempts to generate a report that violates a cardinality rule—such as attributing a single revenue stream to two conflicting fiscal periods—the infrastructure’s control plane flags the inconsistency before the output reaches the user.2

The use of W3C standards like RDF (Resource Description Framework) and OWL (Web Ontology Language) ensures that these definitions are interoperable and machine-readable.1 RDF represents facts as triples (Subject-Predicate-Object), which allows the assistant to traverse the knowledge graph to find non-obvious relationships.4 OWL adds expressive logic, allowing the system to derive implied facts through inference, such as recognizing that if "Machine A has Sensor Temp1" and "Sensor Temp1 detects Overheat," then "Machine A is at risk of Overheat Failure".2

## **The Orchestration Layer: Semantic Routing and Intent Disambiguation**

The activation of interpretive lenses is governed by the orchestration layer, which utilizes semantic routing to determine the best course of action for a given input. This process separates the "thinking" (planning) from the "doing" (execution), a pattern that has been shown to significantly increase accuracy in multi-step workflows.8

### **Semantic Routing Cues and Linguistic Features**

Routing is what separates a static script from an adaptive assistant. Instead of following a linear pipeline, the assistant analyzes the situation to decide which specialist or tool is required.5 A semantic router matches user prompts with a set of existing "utterances"—sample inputs that map to specific routes—using vector embeddings.10 This allows the system to bypass expensive and latent LLM-based decision-making for routine tasks. For instance, a request to "check the weather" or "schedule a meeting" can be routed directly to an API, reducing processing time from 5,000 milliseconds to just 100 milliseconds.10

| Routing Method | Operational Context | Capability and Performance |
| :---- | :---- | :---- |
| LLM-based Routing | Complex, ambiguous queries requiring high reasoning. | High accuracy, high latency and cost 5 |
| Embedding-based Routing | Matching queries to predefined semantic categories. | Fast, utilizes vector similarity for intent 5 |
| Rule-based Routing | Highly predictable, deterministic tasks. | Instantaneous, lowest flexibility 5 |
| Small Model (SLM) Routing | Specific task delegation (e.g., classification). | Low cost, efficient local processing 10 |

The semantic router functions by decoupling decision-making from the core model. This separation allows the assistant to scale without sacrificing performance, handling thousands of specialized tools or sub-agents simultaneously.10 In the SSI infrastructure, routing cues are derived from linguistic features, including discourse markers and modality.11

### **Modality and Intent in Specialized Domains**

In high-stakes sectors such as legal or medical policy, the assistant’s ability to distinguish between "mandatory" and "permissive" language is vital. Research into legal benchmarks like LegalBench indicates that general-purpose models often fail to recognize the difference between "must" and "should," leading to incorrect summaries of regulatory requirements.11 The SSI execution layer addresses this by activating a "Regulatory Lens" whenever modal verbs indicating requirement or permission are detected.

This lens triggers deeper audit structures, such as mandatory cross-encoder re-ranking. While a basic bi-encoder architecture might retrieve relevant documents based on vector similarity, a cross-encoder evaluates the precise relationship between tokens in the query and the candidate document, improving faithfulness by as much as 27%.11 This is the "Behavior Change Test" in action: the presence of modal language in the prompt triggers a change in the retrieval architecture to ensure higher fidelity.11

### **Managing Polysemy and Ambiguity**

Language is inherently underdetermined, particularly when words possess multiple related senses (polysemy). Words like "head," "fork," or "pig" can be interpreted literally or metaphorically depending on the context.14 The SSI infrastructure manages this through a combination of prior sentential context and extralinguistic cues, such as the speaker’s background or speech style.15

Semantic intelligence becomes infrastructure when it can resolve these ambiguities without manual intervention. The "Sense-Aware" retrieval layer uses external semantic knowledge to explicitly model the different meanings of a polysemous word.16 By measuring the "gap" between different semantic fusion results and the original sentence, the system can predict the intended meaning with higher accuracy than baseline models.16 This is particularly critical in requirements engineering and policy analysis, where an ambiguous term in a document can cascade into systemic failure.2

## **Symbolic Charge and Ideological Governance**

One of the most profound instability layers identified in Volume IV is the "symbolic charge" and ideological framing inherent in language. AI systems often replicate and even amplify these biases, particularly in militarized metaphors or lexical choices that reflect a specific cultural or political outlook.17 Infrastructure for the SSI canon must therefore include a "Diagnostic Lens" for ideological discourse.

### **Critical Discourse Analysis as Operational Control**

The execution layer incorporates techniques from Critical Discourse Analysis (CDA), such as Van Dijk’s "ideological square" and Fairclough’s three-dimensional model.17 These techniques analyze how AI language employs modality, nominalization, and the passive voice to normalize dominant ideologies under the guise of neutrality.18

For example, the use of passive voice—"decisions were made"—can obscure agency and individual responsibility, a common strategy in corporate and technological discourses.19 The SSI infrastructure detects these markers and triggers a "Transparency Protocol" that requires the assistant to identify the agents involved in a given activity or to explain the ideological underpinnings of a generated response.18

| Ideological Marker | Linguistic Strategy | Infrastructure Response |
| :---- | :---- | :---- |
| Nominalization | Transforming actions into abstract concepts. | De-nominalization protocol to identify agents 18 |
| Passive Voice | Obscuring the performer of an action. | Transformation into active voice for clarity 18 |
| Interdiscursive Blending | Mixing scientific and political registers. | Separation of registers for auditability 18 |
| Militarized Metaphors | Using combat language for non-combat tasks. | Bias reduction and neutralization filter 17 |

By integrating CDA-informed training and evaluation, the SSI infrastructure moves toward "Ethically Responsible AI." This is not just a policy requirement but a functional one: if an assistant cannot decipher the ideological indicators in a declassified security document or a public health policy, it cannot provide an objective or accurate summary.17 The behavior change here is the assistant's ability to offer a "balanced" view by recognizing and neutralizing the biases of its training data and source documents.17

## **The Evidence Plane: Provenance and Citation Faithfulness**

The cornerstone of the SSI implementation is the "evidence plane," which ensures that every claim is traceable to an authoritative source. This is achieved through the integration of standard ontologies for provenance and citation typing, which allow the assistant to reason about the *validity* and *intent* of the information it uses.

### **Source Provenance and the PROV-O Standard**

The PROV-O ontology provides the foundation for interchange of provenance information across heterogeneous systems.20 In the SSI infrastructure, every interaction is modeled as a set of core classes:

* **prov:Entity**: The specific piece of information or data asset.  
* **prov:Activity**: The process of retrieval, generation, or modification.  
* **prov:Agent**: The person, institution, or AI model responsible for the activity.22

This allows for the "Intent-to-Runtime" lineage, connecting a high-level requirement to the specific contract, test, and deployment that satisfies it.2 When an assistant provides an answer, it must be able to justify that answer by pointing to the prov:wasDerivedFrom relationship, which links the response back to the original entity in the database.22 This is particularly important for mitigating hallucinations; if the lineage is broken or ambiguous, the infrastructure's control plane flags the output as "unreliable".13

### **Citation Typing and Rhetorical Support with CiTO**

Traditional citation systems treat every reference as a neutral "link." The SSI execution layer utilizes the Citation Typing Ontology (CiTO) to capture the *citation intent*.25 This allows the assistant to distinguish between a source that is cited as an authority (cito:citesAsAuthority), one that is being critiqued (cito:critiques), or one that is simply being used for background information (cito:obtainsBackgroundFrom).25

| CiTO Property | Rhetorical Connotation | Operational Implication for Assistant |
| :---- | :---- | :---- |
| cito:supports | Positive | High-confidence grounding for the claim 25 |
| cito:refutes | Negative | Conflict detected; assistant must surface the disagreement 27 |
| cito:usesMethodIn | Neutral | Technical grounding; relevant for process queries 25 |
| cito:disagreesWith | Negative | High-risk citation; requires human-in-the-loop review 28 |
| cito:extends | Positive | Building upon previous work; shows cumulative knowledge 25 |

By reifying citations as objects (cito:Citation), the infrastructure can store metadata about the *frequence* and *context* of the citation.25 An assistant can thus "reason with evidence" by identifying when a hypothesis is being amplified by bias—where papers supporting a hypothesis are cited in preference to those refuting it—or when "unfounded authority" is being established.27 This level of insight allows the assistant to warn the user: "This claim is widely cited but frequently critiqued in recent literature".27

## **Dynamic Governance: Evaluation Rubrics and Pathology Feedback**

The governance layer of the SSI canon is not a checklist but a continuous feedback loop. It utilizes a series of evaluation rubrics to test the system's performance and feed failures back into the development cycle. This satisfies the "Behavior Change Test" by ensuring that every implementation detail has a measurable impact on assistant reliability.

### **The SHACL Validation Engine**

The Shapes Constraint Language (SHACL) is the primary tool for "closed-world" validation within the knowledge graph.2 While ontologies like OWL are used for open-world inference, SHACL is used to enforce specific conditions that the data must meet. For example, a SHACL shape can mandate that every "Review" must have a "rating" between 1 and 5, or that every "Employee" must have a unique ID.7

In the context of assistant governance, SHACL shapes are used to validate the output against business policies. If a generated response fails to meet a required constraint—such as a mandatory disclosure in a financial advice scenario—the SHACL engine generates a "validation report".30 This report can be processed by the assistant in a "Reflective Pattern," where it switches into "critic mode" to assess and correct its own work before the user ever sees it.8

### **Fine-Grained Factuality and the FactScore Metric**

Traditional metrics like BLEU or ROUGE are inadequate for evaluating semantic intelligence because they rely on surface-level n-gram matching rather than meaning.32 The SSI execution layer adopts the FactScore metric, which breaks long-form text into a series of atomic facts and computes the percentage of those facts supported by a reliable source.34

The FactScore formula is formalized as:

FactScore = (ns / N) * 100%

where ns is the number of supported atomic facts and N is the total number of atomic facts extracted.36 This metric allows for a nuanced, fine-grained analysis of outputs that may contain a mixture of supported and unsupported information. In practice, models like ChatGPT have been shown to achieve FactScores as low as 58%, highlighting the need for this level of scrutiny in production environments.34

### **ALCE and Citation Faithfulness**

The ALCE (Automatic LLMs' Citation Evaluation) benchmark complements FactScore by focusing specifically on citation quality.37 It evaluates three dimensions of system responses:

1. **Fluency**: Measured using the MAUVE metric to ensure the text is coherent.  
2. **Correctness**: Ensuring the answer is accurate and comprehensive.  
3. **Citation Quality**: Using Natural Language Inference (NLI) models to verify that every citation actually supports the statement it is attached to.38

This rigorous evaluation ensures that the "Evidence Plane" is not just a decorative addition but a functional guarantee of faithfulness. If an assistant provides an answer with citations, but those citations do not entail the generated claims, the ALCE score drops, triggering a feedback loop to refine the retrieval and grounding strategies.38

## **Assistant Protocols and the Human-in-the-Loop Gateway**

The final component of the SSI infrastructure is the set of protocols that govern when an assistant can act autonomously and when it must escalate to a human gatekeeper. This is particularly critical in "agentic" systems that don't just provide information but execute multi-step tasks in the real world.40

### **High-Stakes Decision Support and Risk Thresholds**

The SSI canon implements a "Tiered Oversight" model based on risk thresholds. For routine, low-risk tasks, the assistant may operate under "Human-on-the-Loop" (HOTL) supervision, where humans monitor progress via dashboards and intervene only when anomalies arise.40 However, for high-stakes, irreversible decisions—such as financial disbursements or medical inquiries—the "Human-in-the-Loop" (HITL) Gateway is mandatory.8

In a HITL workflow, the assistant generates a recommendation and a justification, but the action is paused at a defined checkpoint until a qualified human provides an explicit sign-off.8 This builds trust and ensures accountability in regulated industries.8

| Oversight Strategy | Risk Context | Operational Mechanism |
| :---- | :---- | :---- |
| HITL Gateway | High-risk, high-stakes decisions. | Mandatory "Approve/Edit" checkpoint before execution 8 |
| HOTL Dashboard | Medium-risk, high-volume tasks. | Automated action with human monitoring for drift 41 |
| Confidence-Based Routing | Dynamic, context-dependent risk. | Auto-escalation to human when confidence < threshold 42 |
| Shadow Reflection | Low-stakes, exploratory tasks. | Internal "Critic" loop for quality control 8 |

### **Confidence-Based Routing and Escalation Triggers**

The infrastructure operationalizes governance through "escalation triggers." These triggers use a combination of confidence scores, semantic checks, and contextual flags to determine when an assistant's output is not reliable enough to act upon.13 For example, a "Confidence-Based Routing" protocol evaluates the assistant's certainty on every interaction; if the certainty falls below a defined threshold (e.g., 0.85), the interaction is routed to a human reviewer with the full context of the conversation.42

This approach has been shown to achieve high routing accuracy, with some organizations reporting up to 96% success in identifying which queries require human expertise.42 The "Behavior Change Test" here is staffing: the architecture dictates how many human reviewers are needed based on the escalation rates and the complexity of the domain.

## **Levels of Implementation: From Lightweight to Graph-Mesh**

The SSI execution layer is designed for modularity, allowing organizations to start with minimal infrastructure and scale as their needs evolve. This progression ensures that the system provides value from the first day without requiring a monolithic upfront investment.

### **Phase 1: Lightweight Implementation (Bootstrap)**

The first level of implementation focuses on "Plan-Then-Execute" patterns and bi-encoder RAG.8 The knowledge base consists of a set of indexed document chunks and a simple business glossary. Evaluation is done through basic accuracy metrics, and governance is handled through keyword-based guardrails. This phase targets low-complexity, high-volume tasks where the goal is to improve the consistency of responses without adding significant technical overhead.

### **Phase 2: Graph-Powered Determinism**

The second level introduces the "Meaning Plane" through RDF/OWL ontologies and property graphs.2 Retrieval is now a hybrid process of vector search and graph traversal, allowing the assistant to follow explicit relationships and business logic.4 SHACL shapes are implemented to enforce data quality and policy compliance at runtime.7 This phase is appropriate for specialized domains like technical knowledge management or smart manufacturing, where the precision of relationships is paramount.6

### **Phase 3: The Semantic Mesh and Federated Governance**

The most mature level of implementation is the "Semantic Mesh," which decentralizes not just data ownership but AI reasoning across semantically connected agents.43 In this mesh, multiple specialized graphs coexist, aligned through shared semantics and standardized metadata protocols like the Model Context Protocol (MCP).4 This architecture supports "Multi-Agent Orchestration," where a manager agent delegates sub-tasks to specialized researchers, writers, and auditors.8 Governance is federated, with every agent providing "on-policy negative feedback" to optimize the routing and retrieval strategies for the entire mesh.44

## **Conclusion: The Functional Closing of the Canon**

The Semantic-Semiotic Intelligence canon concludes not with a static set of rules, but with a blueprint for a living, adaptive knowledge infrastructure. By focusing on the execution layer—the reusable lenses, minimal metadata, and assistant protocols—we avoid the bureaucratic trap of excessive documentation while ensuring that the assistant remains grounded in reality.2

Semantic intelligence becomes infrastructure when it is integrated into the delivery lifecycle, where every change in business meaning or model performance is captured, validated, and fed back into the system.2 The ultimate measure of success for Report N is the "Behavior Change Test": the ability of the AI assistant to refuse a biased query, to identify a conflicting citation, and to provide a justified, faithful response in the most ambiguous of contexts.17 This is the realization of the SSI vision—a system where technology does not replace human judgment, but provides the disciplined structure necessary for human-machine collaboration to thrive in the face of complexity.40

#### **Works cited**

1. Ontology in AI: Components, Standards & Agent Applications - Atlan, accessed May 14, 2026, [https://atlan.com/know/what-is-ontology-in-ai/](https://atlan.com/know/what-is-ontology-in-ai/)  
2. Ontology-Driven Enterprise Architecture for AI-Powered Software Delivery | by Prof. Mamdouh Alenezi | Medium, accessed May 14, 2026, [https://medium.com/@malenezi/ontology-driven-enterprise-architecture-for-ai-powered-software-delivery-58d6bfa38b3a](https://medium.com/@malenezi/ontology-driven-enterprise-architecture-for-ai-powered-software-delivery-58d6bfa38b3a)  
3. Semantic AI and Knowledge Graphs | Data Reply, accessed May 14, 2026, [https://www.reply.com/data-reply/en/semantic-ai-and-knowledge-graphs](https://www.reply.com/data-reply/en/semantic-ai-and-knowledge-graphs)  
4. Combining Knowledge Graphs With LLMs | Complete Guide - Atlan, accessed May 14, 2026, [https://atlan.com/know/combining-knowledge-graphs-llms/](https://atlan.com/know/combining-knowledge-graphs-llms/)  
5. Routing for AI Agents: Building Adaptive and Context-Aware Systems | by NivaLabs AI, accessed May 14, 2026, [https://medium.com/@nivalabs.ai/routing-for-ai-agents-building-adaptive-and-context-aware-systems-d5044bc267ca](https://medium.com/@nivalabs.ai/routing-for-ai-agents-building-adaptive-and-context-aware-systems-d5044bc267ca)  
6. Building Your First Ontology-Powered AI Agent (Step-by-Step) | by Nihal Parmar - Medium, accessed May 14, 2026, [https://itznihal.medium.com/building-your-first-ontology-powered-ai-agent-step-by-step-e98c0ef1b7c8](https://itznihal.medium.com/building-your-first-ontology-powered-ai-agent-step-by-step-e98c0ef1b7c8)  
7. What Is SHACL?| Graphwise Fundamentals, accessed May 14, 2026, [https://graphwise.ai/fundamentals/what-is-shacl/](https://graphwise.ai/fundamentals/what-is-shacl/)  
8. Architecting Autonomy: Modern Design Patterns for AI Assistants : r/artificial - Reddit, accessed May 14, 2026, [https://www.reddit.com/r/artificial/comments/1qcvi7y/architecting_autonomy_modern_design_patterns_for/](https://www.reddit.com/r/artificial/comments/1qcvi7y/architecting_autonomy_modern_design_patterns_for/)  
9. 7 Must-Know Agentic AI Design Patterns - MachineLearningMastery.com, accessed May 14, 2026, [https://machinelearningmastery.com/7-must-know-agentic-ai-design-patterns/](https://machinelearningmastery.com/7-must-know-agentic-ai-design-patterns/)  
10. Semantic Router and Its Role in Designing Agentic Workflows - The New Stack, accessed May 14, 2026, [https://thenewstack.io/semantic-router-and-its-role-in-designing-agentic-workflows/](https://thenewstack.io/semantic-router-and-its-role-in-designing-agentic-workflows/)  
11. Chunking, Retrieval, and Re-ranking: An Empirical Evaluation of RAG Architectures for Policy Document Question Answering - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.15457v1](https://arxiv.org/html/2601.15457v1)  
12. Unpacking Ambiguity: The Interaction of Polysemous Discourse Markers and Non-DM Signals - ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.codi-1.2.pdf](https://aclanthology.org/2025.codi-1.2.pdf)  
13. How to Build Human-in-the-Loop Oversight for Production AI Agents - Galileo AI, accessed May 14, 2026, [https://galileo.ai/blog/human-in-the-loop-agent-oversight](https://galileo.ai/blog/human-in-the-loop-agent-oversight)  
14. Polysemy (Chapter 6) - Cognitive Linguistics and Second Language Acquisition of Chinese, accessed May 14, 2026, [https://www.cambridge.org/core/books/cognitive-linguistics-and-second-language-acquisition-of-chinese/polysemy/5D00E442CB63ABE0B38F0C02A179C874](https://www.cambridge.org/core/books/cognitive-linguistics-and-second-language-acquisition-of-chinese/polysemy/5D00E442CB63ABE0B38F0C02A179C874)  
15. Speaker-Specific Cues Influence Semantic Disambiguation - PMC - NIH, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9579068/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9579068/)  
16. Detecting Semantic-level Polysemy Ambiguity by Fusing External Semantic Knowledge, accessed May 14, 2026, [https://pure.ecnu.edu.cn/en/publications/detecting-semantic-level-polysemy-ambiguity-by-fusing-external-se/](https://pure.ecnu.edu.cn/en/publications/detecting-semantic-level-polysemy-ambiguity-by-fusing-external-se/)  
17. Translating ideology: AI rendering of US intelligence discourse on the Arab–Israeli conflict, accessed May 14, 2026, [https://www.researchgate.net/publication/400921306_Translating_ideology_AI_rendering_of_US_intelligence_discourse_on_the_Arab-Israeli_conflict](https://www.researchgate.net/publication/400921306_Translating_ideology_AI_rendering_of_US_intelligence_discourse_on_the_Arab-Israeli_conflict)  
18. Critical Discourse Analysis Of Ideological Interdiscursivity In Selected Artificial Intelligence English Extracts - International Journal of Environmental Sciences, accessed May 14, 2026, [https://theaspd.com/index.php/ijes/article/download/1513/1226/2956](https://theaspd.com/index.php/ijes/article/download/1513/1226/2956)  
19. Article - Critical Discourse Analysis Of Ideological Interdiscursivity In Selected Artificial Intelligence English Extracts - Digital Repository, accessed May 14, 2026, [https://repository.uobaghdad.edu.iq/articles/nUKij5sBMeyNPGM3gN1y?page=2824](https://repository.uobaghdad.edu.iq/articles/nUKij5sBMeyNPGM3gN1y?page=2824)  
20. About PROV - Open Provenance, accessed May 14, 2026, [https://openprovenance.org/service/about.html](https://openprovenance.org/service/about.html)  
21. PROV-O: The PROV Ontology - Research Explorer - The University of Manchester, accessed May 14, 2026, [https://research.manchester.ac.uk/en/publications/prov-o-the-prov-ontology/](https://research.manchester.ac.uk/en/publications/prov-o-the-prov-ontology/)  
22. PROV-O: The PROV Ontology - W3C, accessed May 14, 2026, [https://www.w3.org/TR/prov-o/](https://www.w3.org/TR/prov-o/)  
23. GenProve: Learning to Generate Text with Fine-Grained Provenance - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.04932v2](https://arxiv.org/html/2601.04932v2)  
24. Tracing the Data Trail: A Survey of Data Provenance, Transparency and Traceability in LLMs, accessed May 14, 2026, [https://www.researchgate.net/publication/399965419_Tracing_the_Data_Trail_A_Survey_of_Data_Provenance_Transparency_and_Traceability_in_LLMs](https://www.researchgate.net/publication/399965419_Tracing_the_Data_Trail_A_Survey_of_Data_Provenance_Transparency_and_Traceability_in_LLMs)  
25. CiTO - SPAR Ontologies, accessed May 14, 2026, [https://www.sparontologies.net/ontologies/cito](https://www.sparontologies.net/ontologies/cito)  
26. (PDF) CiTO, the Citation Typing Ontology - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/45184167_CiTO_the_Citation_Typing_Ontology](https://www.researchgate.net/publication/45184167_CiTO_the_Citation_Typing_Ontology)  
27. CiTO, the Citation Typing Ontology - PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC2903725/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2903725/)  
28. CiTO, the Citation Typing Ontology, accessed May 14, 2026, [https://sparontologies.github.io/cito/current/cito.html](https://sparontologies.github.io/cito/current/cito.html)  
29. Support for CiTO (Citation Typing Ontology) · quarto-dev · Discussion #4176 - GitHub, accessed May 14, 2026, [https://github.com/orgs/quarto-dev/discussions/4176](https://github.com/orgs/quarto-dev/discussions/4176)  
30. SHACL - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/SHACL](https://en.wikipedia.org/wiki/SHACL)  
31. SHACL validation — GraphDB 11.3 documentation, accessed May 14, 2026, [https://graphdb.ontotext.com/documentation/11.3/shacl-validation.html](https://graphdb.ontotext.com/documentation/11.3/shacl-validation.html)  
32. LLM Evaluation Metrics: The Ultimate LLM Evaluation Guide - Confident AI, accessed May 14, 2026, [https://www.confident-ai.com/blog/llm-evaluation-metrics-everything-you-need-for-llm-evaluation](https://www.confident-ai.com/blog/llm-evaluation-metrics-everything-you-need-for-llm-evaluation)  
33. 7 Key LLM Metrics to Enhance AI Reliability | Galileo, accessed May 14, 2026, [https://galileo.ai/blog/llm-performance-metrics](https://galileo.ai/blog/llm-performance-metrics)  
34. FactScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation | Research - AI at Meta, accessed May 14, 2026, [https://ai.meta.com/research/publications/factscore-fine-grained-atomic-evaluation-of-factual-precision-in-long-form-text-generation/](https://ai.meta.com/research/publications/factscore-fine-grained-atomic-evaluation-of-factual-precision-in-long-form-text-generation/)  
35. FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation - ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2023.emnlp-main.741/](https://aclanthology.org/2023.emnlp-main.741/)  
36. FActScore: Metric for Factual Precision in LLMs - Emergent Mind, accessed May 14, 2026, [https://www.emergentmind.com/topics/factscore](https://www.emergentmind.com/topics/factscore)  
37. ALCE | Notion, accessed May 14, 2026, [https://openrag.notion.site/ALCE-6917fd66148f43bca3cec6982071887e](https://openrag.notion.site/ALCE-6917fd66148f43bca3cec6982071887e)  
38. [2305.14627] ALCE: An Automatic Benchmark for Large Language Model Generations with Citations - ar5iv, accessed May 14, 2026, [https://ar5iv.labs.arxiv.org/html/2305.14627](https://ar5iv.labs.arxiv.org/html/2305.14627)  
39. Towards Fine-Grained Citation Evaluation in Generated Text: A Comparative Analysis of Faithfulness Metrics - ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2024.inlg-main.35.pdf](https://aclanthology.org/2024.inlg-main.35.pdf)  
40. Human-in-the-Loop: A 2026 Guide to AI Oversight That Actually Works - Strata Identity, accessed May 14, 2026, [https://www.strata.io/blog/agentic-identity/practicing-the-human-in-the-loop/](https://www.strata.io/blog/agentic-identity/practicing-the-human-in-the-loop/)  
41. HITL vs. HOTL: Enterprise AI Oversight Implementation Guide 2026 - Synvestable, accessed May 14, 2026, [https://www.synvestable.com/human-in-the-loop.html](https://www.synvestable.com/human-in-the-loop.html)  
42. Human-in-the-loop AI in CX explained - Parloa, accessed May 14, 2026, [https://www.parloa.com/knowledge-hub/human-in-the-loop-ai/](https://www.parloa.com/knowledge-hub/human-in-the-loop-ai/)  
43. Will the Future of Agentic AI rely on Knowledge Graphs? - Artefact, accessed May 14, 2026, [https://www.artefact.com/blog/will-the-future-of-agentic-ai-rely-on-knowledge-graphs/](https://www.artefact.com/blog/will-the-future-of-agentic-ai-rely-on-knowledge-graphs/)  
44. VoltAgent/awesome-ai-agent-papers - GitHub, accessed May 14, 2026, [https://github.com/VoltAgent/awesome-ai-agent-papers](https://github.com/VoltAgent/awesome-ai-agent-papers)  
45. Centaur Evaluations - Stanford Digital Economy Lab, accessed May 14, 2026, [https://digitaleconomy.stanford.edu/project/ai-centaur-benchmarks/](https://digitaleconomy.stanford.edu/project/ai-centaur-benchmarks/)

---