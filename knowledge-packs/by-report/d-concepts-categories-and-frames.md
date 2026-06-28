# D. Concepts, Categories & Frames

The architecture of Semantic-Semiotic Intelligence (SSI) reaches its functional maturity at the level of concept-cartography and category-governance. While preceding phases of the SSI canon—Reports A, B, and C—focused on the structural anatomy of signs, the lexical precision of terms, and the logical validity of propositions and claims, Report D addresses the vital interstitial layer where these units coalesce into navigable conceptual neighborhoods. In this domain, meaning is no longer a static mapping between a signifier and a signified; it becomes a dynamic, multidimensional space where categories acquire centers and edges, frames supply roles and expectations, and institutions enforce boundaries to ensure that information remains usable for high-stakes reasoning. The movement of an AI assistant from the processing of structured claims into these conceptual neighborhoods represents the transition from a purely syntactic machine to a semiotic agent capable of managing the blurring, stabilization, and drift of meaning across diverse contexts.

## **The Geometry of Conceptual Neighborhoods: Prototype and Exemplar Dynamics**

The foundational challenge of categorization lies in the tension between cognitive economy and the inherent complexity of the perceived world. Traditional Aristotelian models, which defined categories through necessary and sufficient features, have proven inadequate for modeling natural human language and cognition.1 Semantic-Semiotic Intelligence adopts a Roschian paradigm, recognizing that natural categories are organized around graded internal structures rather than rigid binary boundaries.

### **Prototype Theory and the Principle of Cognitive Economy**

At the heart of conceptual clustering is the principle of cognitive economy, which asserts that an organism’s category system should provide maximum information about its environment while conserving finite mental resources. Eleanor Rosch’s prototype theory transformed cognitive psychology by demonstrating that category membership is a matter of degree.1 A prototype acts as the mental benchmark—the most central or representative member of a category—against which all other potential members are compared.1 For instance, within the category of "bird," a robin is rated as highly prototypical because it embodies features such as flight, feathers, and a specific size, whereas a penguin or an ostrich occupies the periphery.

These "prototype effects" are not merely psychological curiosities; they dictate the efficiency of information retrieval and inference. Prototypical members are categorized faster, generated more frequently as examples, and learned earlier in development. In the context of an AI assistant, recognizing the "birdiness" of a robin versus the marginal status of a platypus allows the system to prioritize expected inferences. This graded structure is maintained by a "web of interlocking categories" that overlap at their edges, creating "fuzzy boundaries" where terms like "cup" and "bowl" or "red" and "orange" may blur depending on the situational context.

| Feature | Classical (Aristotelian) | Prototype (Roschian) | Exemplar (Medin/Schaffer) |
| :---- | :---- | :---- | :---- |
| **Structure** | Definitional, binary | Central tendency, graded | Collection of specific instances |
| **Boundaries** | Sharp, invariant | Fuzzy, context-dependent | Determined by similarity to stored cases |
| **Mechanism** | Logical feature checking | Similarity to abstract ideal | Comparison to remembered examples |
| **Typicality** | Not recognized (all members equal) | Essential to organization | Result of high frequency/similarity |
| **SSI Application** | Rule-based verification | Heuristic retrieval and ranking | Case-based reasoning and few-shot learning |

### **The Basic Level: The Privileged Cut in Information Space**

Within any taxonomic hierarchy, there is a psychologically privileged level known as the "basic level".3 This level—exemplified by terms like "dog," "chair," or "car"—represents the optimal balance between informativeness and distinctiveness.1 Superordinate categories (e.g., "animal," "furniture") are often too abstract to provide a single mental image or consistent motor interactions, while subordinate categories (e.g., "golden retriever," "rocking chair") provide specific details that add little to general-purpose reasoning.

The basic level is characterized by high cue validity, where the presence of certain attributes strongly predicts category membership. For Semantic-Semiotic Intelligence, identifying the basic-level cut is crucial for grounding agentic action. Humans interact with the world at this level; we sit in "chairs" rather than in "furniture" or "Eames Lounge Chairs" in neutral contexts. An AI navigating conceptual neighborhoods must prioritize these basic-level nodes to maintain alignment with human intent and expectations.

### **Exemplar Models and Case-Based Generalization**

While prototype theory relies on an abstract "average" of a category, exemplar theory suggests that humans store specific instances of category members in memory. When a new entity is encountered, it is categorized by its similarity to these stored exemplars rather than a single idealized prototype.4 This approach allows for greater cognitive flexibility, as the system can adapt to new experiences by adding new exemplars to its "neighborhood".4

Research in computational modeling, such as the Generalized Context Model (GCM), formalizes this by calculating weighted distances in a multidimensional feature space.5 The similarity between a stimulus i and an exemplar j is often expressed as an exponential decay function of their distance: eta_ij = e^(-d_ij) where d_ij = C * [ sum over k=1 to N of w_k * |x_ik - x_jk| ] represents the weighted distance across N dimensions.5 For an AI, this mathematical substrate explains why a system might switch between prototype-based heuristics during early learning and exemplar-based precision as it matures into an expert domain.5

## **Frame Semantics: The Scaffolding of Expectation and Role-Binding**

Moving beyond simple clustering, the meaning of a term is often defined by its role within a larger conceptual structure. Charles Fillmore’s Frame Semantics provides the primary framework for understanding how words evoke "scenes" or "frames" that organize our knowledge of typical situation types.6 A frame is a "package of connected expectations" that allows an agent to make sense of the participants and actions within an event.7

### **The Commercial Transaction Frame: A Core Semantic Neighborhood**

Fillmore's seminal example is the Commercial Transaction frame, which links a set of seemingly disparate verbs—buy, sell, pay, cost, and charge—into a unified conceptual neighborhood.7 To understand any one of these words, an agent must have access to the entire frame, which includes roles such as Buyer, Seller, Goods, and Money.6

Linguistic framing allows for the foregrounding of different perspectives on the same underlying event.7 For instance, using the verb "sell" focuses the listener's attention on the Seller and the Goods, while "buy" shifts the focus to the Buyer.6 This perspective-taking is a vital component of Semantic-Semiotic Intelligence, as it allows an AI to interpret not just what is said, but how the speaker is orienting themselves toward the event.6

| Frame Element | Role Description | Example Lexical Units (LUs) |
| :---- | :---- | :---- |
| **Buyer** | The entity that provides money to acquire goods. | Buy, Purchase, Acquire |
| **Seller** | The entity that provides goods in exchange for money. | Sell, Vendor, Retailer |
| **Goods** | The object or service being exchanged. | Item, Merchandise, Service |
| **Money** | The medium of exchange. | Price, Cost, Fee, Currency |
| **Payment** | The act of transferring money for goods. | Pay, Remit, Settle |

7

### **Scripts, Schemas, and the REVENGE Frame**

Beyond commercial events, frames can model complex social interactions and sequences. The "REVENGE" frame, for example, identifies an Avenger, an Injured Party, an Offender, and an Injury.8 For an AI to reason about a sentence like "He settled the score," it must recognize the underlying REVENGE frame, even if the "Injury" or "Offender" are not explicitly named in the text.7

This connects to Roger Schank’s concept of "scripts," which are temporal sequences of events—such as a "Shopping Script".7 A shopping script provides a default sequence: entering the store, searching for an item, asking for help, buying the item, and leaving.5 These scripts allow an AI to handle "null instantiations"—omitted information that is taken for granted by human speakers.7 If a user says, "I went to the store and found the perfect shoes," the AI uses its "shopping script" to infer that a transaction likely took place, money was exchanged, and the user has now left the store.5

### **AI Frames and Procedural Attachments**

The concept of a "frame" in AI, as proposed by Marvin Minsky, adds a layer of computational utility to these linguistic structures.4 Minskyan frames are data structures that provide slots for information and "default values" that the system can use when data is missing.4 A key innovation in AI frames is the use of "procedural attachments".4 These are sub-routines triggered by specific actions:

* **IF-NEEDED**: A procedure that runs only when a value for a slot is required but missing (deferred evaluation).  
* **IF-ADDED**: A procedure that runs when a new piece of information is placed in a slot, potentially updating linked information or triggering external actions.4

This mechanism allows frames to function as active agents in a reasoning system. When an AI "fills" a slot in a Commercial Transaction frame, an "IF-ADDED" procedure might automatically calculate the sales tax or check the buyer's credit limit.4 This moves the system from passive understanding to active, governed reasoning.

## **Semantic Field Organization: Lexical Relations as Navigational Aids**

Conceptual neighborhoods are organized by a set of formal lexical relations that define how meanings contrast and generalize. For Semantic-Semiotic Intelligence, these relations—hyponymy, meronymy, synonymy, and antonymy—act as the primary coordinates for navigation.9

### **Taxonomies and Partonomies: Hyponymy and Meronymy**

Hyponymy is the "type-of" relation that builds hierarchies (taxonomies).9 "Fruit" is the hypernym of "apple," and "apple" is the hyponym of "fruit".9 This relation is fundamentally transitive: if a Granny Smith is a kind of apple, and an apple is a kind of fruit, then a Granny Smith is a kind of fruit.9 However, linguistic transitivity can fail at conceptual boundaries; while a "car-seat" is a type of "seat," and a "seat" is a type of "furniture," humans are reluctant to classify a "car-seat" as "furniture" because it belongs to a different functional neighborhood (automotive vs. domestic).12

Meronymy is the "part-whole" relation, forming partonomies.9 "Engine," "wheels," and "body" are meronyms of "car" (the holonym).9 Meronymy is distinct from hyponymy because a wheel is not a "kind of" car, but a "part of" one.9 For an AI, distinguishing between these relations is critical for decompositional reasoning—knowing that fixing an engine (meronymy) is part of repairing a car, while classifying a truck as a vehicle (hyponymy) is a matter of generalization.9

### **Synonymy, Antonymy, and Semantic Contrast**

Meaning is also defined through contrast within a semantic field. Antonymy provides the "edges" of conceptual neighborhoods.10

* **Gradable Antonyms**: Exist on a scale, such as *hot* and *cold*, allowing for intermediate states like *lukewarm*.9  
* **Complementary Antonyms**: Exhaustive binaries, such as *true* and *false*, where there is no middle ground.9  
* **Relational (Converse) Antonyms**: Express the same relationship from opposite poles, such as *doctor* and *patient* or *lend* and *borrow*.9

Synonymy—the relation of "near sameness"—rarely involves absolute identity.9 Words like "big" and "large" or "brave" and "courageous" may share a denotation but differ in connotation, register, or collocation.9 For instance, a person might be a "big baby" (meaning immature), but they are rarely described as a "large baby" in the same sense.12 An AI must navigate these nuances by understanding "synsets"—groups of words that can be substituted in certain contexts but carry different stylistic weights.

## **The Blur and the Fog: Semantic Similarity vs. Conceptual Identity**

As an AI moves from signs to neighborhoods, it often encounters a "fog" created by the limitations of its own representation systems. Modern Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems primarily use high-dimensional vector embeddings to organize information by semantic similarity. However, similarity in vector space is not the same as conceptual identity.

### **The Interference Theorem in Vector Retrieval**

A fundamental tension exists in semantically organized retrieval. When information is organized by meaning, semantically related items sit near each other in the representation space.13 While this enables generalization and analogy, it also creates "interference," where semantic neighbors compete for the same retrieval slot.13 A theorem concerning "semantically continuous kernel-threshold memories" suggests that as the volume of information increases, the "false alarm rate" and "forgetting" are bounded away from zero.13

This interference explains common AI failures: a query for a specific product (e.g., "iPhone 15 Pro Max") may retrieve a document about "smartphones" generally because the "basic level" neighbor has a higher density in the training data. To combat this, SSI architectures utilize hybrid retrieval, combining the "fuzziness" of semantic search with the "crispness" of lexical keyword matching (BM25) and re-ranking to ensure conceptual identity is maintained.

### **Testing Conceptual Boundaries: The CK-Arena**

To measure an AI's ability to navigate these neighborhoods, researchers have developed benchmarks like "CK-Arena," which uses the "Undercover" game to test boundary knowledge.14 In this game, an agent must describe a concept (e.g., *basketball*) while being aware of a closely related distractor concept (e.g., *volleyball*).14

* If the agent identifies itself as the "Undercover," it must strategically suppress the unique features of its word to blend in with the majority.  
* If it is a "Civilian," it must highlight those unique features to signal its identity to allies.14 This requires the agent to not only know the prototype of the category but to understand the "slight differences" and "distinguishing features" that define the edges of the conceptual neighborhood.14

## **Category Governance: Institutional Authority and Evidentiary Boundaries**

In human society, categories are not just mental clusters; they are governed by institutions that enforce boundaries using specific evidence. For Semantic-Semiotic Intelligence to operate in domains like law, medicine, or finance, it must understand how categories are established and maintained by authority.

### **Medical and Legal Membership as Governed Categories**

Hospital governance provides a stark example of how "membership" is a strictly governed category. A practitioner’s inclusion in the "Medical Staff" is not a matter of degree or similarity to a prototype; it is a binary state granted by a governing body based on specific "evidence of qualifications and competencies". This evidence includes current work practice, special training, licensure, and adherence to medical staff rules.

Similarly, the Social Security Administration (SSA) defines "Categories of Evidence" for evaluating disability claims.15 Here, "Evidence" is anything submitted that relates to a claim, and it is categorized into objective medical evidence (laboratory findings), medical opinions (statements about limitations), and evidence from nonmedical sources.15 For an AI assistant, navigating these neighborhoods requires a shift from "semantic similarity" to "probative value," where the source and type of information determine its weight in the reasoning process.15

| Governance Entity | Category | Evidence Required for Membership/Validation | Authority Mechanism |
| :---- | :---- | :---- | :---- |
| **Hospital Governing Body** | Medical Staff Membership | Licensure, special training, peer review, clinical skills | Bylaws and Board Approval |
| **Social Security Admin** | Disability Status | Objective medical signs, laboratory findings, medical opinions | Federal Regulations (Section 416.913) |
| **NYS Dept. of Taxation** | Sandwich (for tax) | Starch-based conveyance, portability, ready-to-eat status | Tax Law/Administrative Code |
| **Joint Commission** | Clinical Privileges | Ongoing monitoring of medical judgment and professional behavior | Accreditation Standards |
| **National Cyber Agency** | Electronic Agent (AI) | Automated information processing capacity | ITE Law (Indonesia) |

### **The Sandwichness Wars: Authority vs. Ordinary Meaning**

The ongoing cultural and legal debate over whether a "hot dog is a sandwich" illustrates the conflict between different modes of category-governance.16

* **Lexicographical Authority**: Merriam-Webster defines a sandwich as meat between slices of bread or a split roll, thus including the hot dog.18  
* **Industrial Authority**: The National Hot Dog and Sausage Council (NHDSC) rejects the "sandwich" label, arguing that the hot dog has "evolved to become an entirely new entity"—much as the Dalai Lama is more than "just a guy".16  
* **Legal Authority**: The New York State Department of Taxation and Finance (NYSDTF) explicitly lists "hot dogs" in its definition of sandwiches to ensure they remain taxable.16

This "sandwich ontology" reveals that categories are often "negotiated" rather than "discovered".17 In law, the "Ordinary Meaning Canon" assumes words bear their meaning in common parlance, whereas the "Plain Meaning Rule" enforces the text as written, even if it deviates from everyday usage.1 For an AI, the "correct" category depends on which "governance plane" is active: a culinary AI might follow the NHDSC, while a tax-compliance AI must follow the NYSDTF.16

## **Dynamic Cartography: Drift, Versioning, and Stabilization**

Conceptual neighborhoods are not static; they exist in a state of constant evolution. Semantic drift occurs when the virtual representation of a category (the ontology or model) loses synchronization with the real-world environment it is supposed to mirror.21

### **Types of Semantic Drift in Digital Twins**

In the management of "Digital Twins"—virtual replicas of physical systems—drift can occur at multiple layers.21

* **Data Drift**: Changes in the properties of incoming data (e.g., sensor degradation) that reduce model accuracy.21  
* **Structural Drift**: Changes in the physical environment (e.g., adding a new sensor or changing units from Fahrenheit to Celsius) that require a change in the metamodel.21  
* **Technical Conceptual Drift**: Occurs when models or algorithms change over time, creating inconsistencies between the model and its metamodel.21  
* **Knowledge Conceptual Drift**: The most abstract form, where the ontological description of a system becomes outdated because of new stakeholder needs or cultural shifts.21

Managing this drift requires "model management mechanisms" such as migration, evolution, and, most importantly, versioning.21

### **Ontology Engineering as the Semantic Operating System**

For an enterprise, ontology engineering acts as the "Semantic Operating System" that stabilizes meaning.22 As AI moves from retrieval to autonomous action, the cost of semantic ambiguity increases exponentially.22 If an agent makes an offer to a "customer" based on a "hallucinated" definition of eligibility, the error happens at machine speed.22

Stabilization is achieved through deliberate versioning of ontologies.23 Using the Semantic Versioning (SEMVER) standard allows organizations to communicate the nature of changes 24:

* **Major updates** signal breaks in backwards compatibility (e.g., changing the fundamental definition of "Transaction").  
* **Minor updates** add functionality (e.g., a new field for "Crypto-Wallet ID") without breaking existing integrations.24

This versioning ensures that while the "context graph" (the operational data network) updates continuously, the "ontology" (the formal rules and vocabulary) remains a stable reference point for agent reasoning.23

## **The Boundaries of Intelligence: A Contested Category**

The most poignant example of category-governance in the current era is the debate over the term "Artificial Intelligence" itself.25 The conceptual boundary of "intelligence" is currently being redrawn, with some arguing that current LLMs are "extraordinarily capable tools" but neither conscious nor intelligent in the biological sense.25

Proposed governance frameworks suggest a "staged scale of intelligence" analogous to the SAE levels of driving automation 25:

1. **Instrumental Systems**: Non-conscious tools optimizing external objectives.  
2. **Minimal Consciousness**: Persistent internal dynamics but no strategic reasoning.  
3. **Experiential Learning**: Strategic intelligence capable of evaluating futures.  
4. **Meta-Intelligence**: The capacity to redesign the intelligence itself.25

As AI systems are increasingly classified as "Electronic Agents" in legal frameworks (e.g., in Indonesia’s ITE Law), they are assigned rights, responsibilities, and liabilities.27 This illustrates the final step in the SSI concept-cartography layer: when a concept moves from a "fuzzy neighborhood" into a "governed category," it becomes a legal and social actor, subject to the same pressures of evidence and authority as any other member of the neighborhood.27

## **Synthesis: Navigating the Semantic-Semiotic Landscape**

The fourth research report for the Semantic-Semiotic Intelligence canon has established that the move from signs and claims to conceptual neighborhoods is a transition from isolated data points to an integrated, navigable, and governable landscape. Meaning is clustered through prototypes and exemplars, scaffolded by frames and scripts, and organized through hierarchical and contrastive lexical relations. However, this internal cognitive map must be anchored by external category-governance to remain useful for reasoning in the real world.

Navigating this landscape requires an AI to manage the "fog" of semantic similarity through hybrid retrieval and boundary testing. It requires the system to respect the institutional boundaries of law and medicine, where membership is a matter of evidence rather than similarity. And finally, it requires the AI to recognize that the map itself is dynamic, necessitating a rigorous practice of ontology engineering and versioning to handle the inevitable drift of human knowledge. By mastering this layer of concept-cartography and category-governance, Semantic-Semiotic Intelligence achieves the stability and trust required for autonomous action at the enterprise and societal scale.

#### **Works cited**

1. Ordinary Meaning and Plain Meaning - Virginia Law Review, accessed May 14, 2026, [https://virginialawreview.org/articles/ordinary-meaning-and-plain-meaning/](https://virginialawreview.org/articles/ordinary-meaning-and-plain-meaning/)  
2. Testing Ordinary Meaning - Harvard Law Review, accessed May 14, 2026, [https://harvardlawreview.org/print/vol-134/testing-ordinary-meaning/](https://harvardlawreview.org/print/vol-134/testing-ordinary-meaning/)  
3. Cognition and Categorization - Rice Computer Science, accessed May 14, 2026, [https://www.cs.rice.edu/~vo9/recognition/2016/slides/lecture07/CognitionAndCategorization.pdf](https://www.cs.rice.edu/~vo9/recognition/2016/slides/lecture07/CognitionAndCategorization.pdf)  
4. Frame (artificial intelligence) - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Frame_(artificial_intelligence)](https://en.wikipedia.org/wiki/Frame_(artificial_intelligence))  
5. Frame Semantics, accessed May 14, 2026, [https://www.flf.vu.lt/dokumentai/Gawron_new_frames_intro.pdf](https://www.flf.vu.lt/dokumentai/Gawron_new_frames_intro.pdf)  
6. Bridging Text and Knowledge with Frames - Google Research, accessed May 14, 2026, [https://research.google.com/pubs/archive/43016.pdf](https://research.google.com/pubs/archive/43016.pdf)  
7. Charles J. Fillmore | Computational Linguistics - MIT Press Direct, accessed May 14, 2026, [https://direct.mit.edu/coli/article/40/3/725/1472/Charles-J-Fillmore](https://direct.mit.edu/coli/article/40/3/725/1472/Charles-J-Fillmore)  
8. Untitled, accessed May 14, 2026, [http://web.vu.lt/flf/g.judzentyte/files/2014/01/freimu-semantika.pdf](http://web.vu.lt/flf/g.judzentyte/files/2014/01/freimu-semantika.pdf)  
9. 2.2 Lexical relations: synonymy, antonymy, hyponymy, and meronymy - Fiveable, accessed May 14, 2026, [https://fiveable.me/introduction-semantics-pragmatics/unit-2/lexical-relations-synonymy-antonymy-hyponymy-meronymy/study-guide/AoGPGe3OVV1wOIPF](https://fiveable.me/introduction-semantics-pragmatics/unit-2/lexical-relations-synonymy-antonymy-hyponymy-meronymy/study-guide/AoGPGe3OVV1wOIPF)  
10. Lexical semantics - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Lexical_semantics](https://en.wikipedia.org/wiki/Lexical_semantics)  
11. 6 Lexical and semantic relations - Cambridge University Press & Assessment, accessed May 14, 2026, [https://resolve.cambridge.org/core/services/aop-cambridge-core/content/view/502A933E8B05B7686DA6C4DB944E3A14/9780511780684c6_p108-132_CBO.pdf/lexical-and-semantic-relations.pdf](https://resolve.cambridge.org/core/services/aop-cambridge-core/content/view/502A933E8B05B7686DA6C4DB944E3A14/9780511780684c6_p108-132_CBO.pdf/lexical-and-semantic-relations.pdf)  
12. Lexical relations - Brandeis Users' Home Pages, accessed May 14, 2026, [https://people.brandeis.edu/~smalamud/ling130/lex_rel.pdf](https://people.brandeis.edu/~smalamud/ling130/lex_rel.pdf)  
13. The Price of Meaning: Why Every Semantic Memory System Forgets - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2603.27116v1](https://arxiv.org/html/2603.27116v1)  
14. Is Your LLM Really Mastering the Concept? A Multi-agent Benchmark - OpenReview, accessed May 14, 2026, [https://openreview.net/forum?id=WNHNfkulYA](https://openreview.net/forum?id=WNHNfkulYA)  
15. 20 CFR § 416.913 - Categories of evidence. - Cornell Law School, accessed May 14, 2026, [https://www.law.cornell.edu/cfr/text/20/416.913](https://www.law.cornell.edu/cfr/text/20/416.913)  
16. Is a hot dog a sandwich? The world may never know.: 2018-2019: Archive, accessed May 14, 2026, [https://iujur.iu.edu/features/archives/2018-2019/hot-dog.html](https://iujur.iu.edu/features/archives/2018-2019/hot-dog.html)  
17. What is the Cube Rule of Food Identification Theory? - wikiHow, accessed May 14, 2026, [https://www.wikihow.com/Cube-Rule-of-Food](https://www.wikihow.com/Cube-Rule-of-Food)  
18. Is a hot dog a sandwich? An extended meditation on the nature of America | Jeb Lund, accessed May 14, 2026, [https://www.theguardian.com/commentisfree/2014/jul/03/is-a-hot-dog-a-sandwich-nature-america](https://www.theguardian.com/commentisfree/2014/jul/03/is-a-hot-dog-a-sandwich-nature-america)  
19. Words and Distinctions for the Common Good: Practical Reason in the Logic of Social Science - Chapter 1 - Imgix, accessed May 14, 2026, [https://pup-assets.imgix.net/onix/images/9780691247069/9780691247069.pdf?fm=pdf](https://pup-assets.imgix.net/onix/images/9780691247069/9780691247069.pdf?fm=pdf)  
20. Extended Abstract Out of the Ordinary: Common Use Arguments in Legislative Classification, accessed May 14, 2026, [https://journals.lib.washington.edu/index.php/nasko/article/view/15881](https://journals.lib.washington.edu/index.php/nasko/article/view/15881)  
21. Semantic drift evaluation in language and data-specific digital twin ..., accessed May 14, 2026, [https://orbilu.uni.lu/bitstream/10993/66954/1/_fgcs-drift-evaluation.pdf](https://orbilu.uni.lu/bitstream/10993/66954/1/_fgcs-drift-evaluation.pdf)  
22. Ontology Engineering as the Semantic Operating System of the AI-First Enterprise | by Gaurav Agarwaal | Apr, 2026, accessed May 14, 2026, [https://gauravagg2016.medium.com/ontology-engineering-as-the-semantic-operating-system-of-the-ai-first-enterprise-e8db15bc0957](https://gauravagg2016.medium.com/ontology-engineering-as-the-semantic-operating-system-of-the-ai-first-enterprise-e8db15bc0957)  
23. Context Graph vs. Ontology: Differences, Roles & Use Cases - Atlan, accessed May 14, 2026, [https://atlan.com/know/context-graph-vs-ontology/](https://atlan.com/know/context-graph-vs-ontology/)  
24. Top 5 Tips for Managing and Versioning an Ontology - Enterprise Knowledge, accessed May 14, 2026, [https://enterprise-knowledge.com/top-5-tips-for-managing-and-versioning-an-ontology/](https://enterprise-knowledge.com/top-5-tips-for-managing-and-versioning-an-ontology/)  
25. (PDF) Is AI Intelligent? Wrong Question? - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/398870396_Is_AI_Intelligent_Wrong_Question](https://www.researchgate.net/publication/398870396_Is_AI_Intelligent_Wrong_Question)  
26. From intelligence to autopoiesis: rethinking artificial intelligence through systems theory, accessed May 14, 2026, [https://www.researchgate.net/publication/391863323_From_intelligence_to_autopoiesis_rethinking_artificial_intelligence_through_systems_theory](https://www.researchgate.net/publication/391863323_From_intelligence_to_autopoiesis_rethinking_artificial_intelligence_through_systems_theory)  
27. AI Exploitation in Social-Media Against Public Figure: Indonesian Legal Perspectives, accessed May 14, 2026, [https://lenkasia.com/ejustice/article/download/9/2/64](https://lenkasia.com/ejustice/article/download/9/2/64)

---