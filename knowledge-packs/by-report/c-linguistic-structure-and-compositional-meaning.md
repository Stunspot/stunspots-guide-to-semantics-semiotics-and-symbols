# C. Linguistic Structure & Compositional Meaning

The evolution of Semantic-Semiotic Intelligence (SSI) demands a robust mechanical bridge between the semiotic sign-vehicle and the logical reasoning object. While the preceding frameworks established the constitution of representation and the engine of semiosis, the current investigation focuses on the structural machinery of linguistic composition. The central thesis is that linguistic structure is the generative system by which sign-vehicles are arranged into compositional meanings: morphemes form words, words form phrases, phrases form propositions, propositions become claims, and claims become reasoning objects. Linguistic intelligence, therefore, is defined as the ability to preserve this multi-layered structure during the processes of interpretation, retrieval, summarization, and inference. In the context of advanced artificial intelligence and retrieval-augmented generation (RAG), the failure to respect these structural constraints—such as the collapse of quantifier scope or the erasure of negation—results in the degradation of structured meaning into a "bag of keywords," fundamentally undermining the logical fidelity of the assistant. 1

## **Inherited Foundations from Reports A and B**

This report functions as a continuation of the SSI canon, inheriting the discipline of representation established in Report A and the sign-relational engine established in Report B. From Report A, **Reality, Representation & Abstraction**, this framework maintains that the word is not the thing and the map is not the territory; every linguistic abstraction necessarily omits details, and logical form must be treated as a specialized layer for disciplined reasoning rather than a primary reflection of reality. 4 It upholds the requirement for indexing and dating referents and maintains the strict separation between claims and evidence. 6

From Report B, **Sign-Relations, Codes & Semiosis**, this report inherits the understanding of linguistic units as sign-vehicles operating within codes. It views signs as relation-events rather than meaning-containers, stabilized by interpretive communities and codes that govern syntactics, semantics, and pragmatics. 1 Within the semiosis chain, the user prompt, retrieved document chunks, metadata, and the assistant’s generated output are all treated as signs whose interpretation is constrained by structural rules. While Report A disciplined representation and Report B explained signs, Report C explains the structural machinery by which linguistic forms compose into structured propositions and how those structures constrain downstream inference. 1

## **Executive Orientation**

Linguistic structure serves as the scaffolding of cognitive intelligence, transforming linear sequences of symbols into hierarchical and multi-dimensional meaning objects. For a future AI assistant, structural awareness is not an aesthetic preference but an operational necessity. The ability to distinguish between "X killed Y" and "Y killed X" is a trivial syntactic task, but the ability to distinguish between "X may cause Y" and "X causes Y unless Z is present" requires a sophisticated understanding of how modality, negation, and conditionals interact within a propositional frame. 9

In high-stakes environments—specifically law, medicine, and technical safety—the structural "grenades" hidden in natural language are numerous. A single misread of the word "shall" as "may," or the failure to recognize that a negation scopes over a permission rather than an action, can lead to catastrophic failures in reasoning and compliance. 9 Current Large Language Models (LLMs) frequently exhibit "negation blindness" and "scope collapse," treating complex sentences as mere collections of relevant topics rather than structured logical commitments. 3 This report provides the structural doctrine required to mitigate these failures, ensuring that retrieved claims are extracted, aligned, and reasoned upon with their logical integrity intact. 6

## **Foundational Thesis of Report C**

The foundational thesis of Report C posits that linguistic structure is the primary system of constraint that prevents the dissipation of meaning into entropy. Linguistic signs do not exist in isolation; they are organized through a pipeline of increasing abstraction. Morphemes provide the atomic units of meaning; lexemes and wordforms stabilize identity; phrases and clauses establish event-level relationships; propositions formulate truth-evaluable content; and claims represent the committed assertion of that content by a source. 1 Linguistic intelligence is the capacity to track a sign-vehicle through these layers, ensuring that the structural commitments made at the morphological or syntactic level are not lost when the information is converted into a reasoning object. To preserve structure is to preserve the inferential license of the text. 15

## **Intellectual Genealogy**

The formalization of linguistic structure as a grammar-to-logic bridge began with Gottlob Frege, the foundational figure of formal semantics. Frege’s **Principle of Compositionality** states that the meaning of a complex expression is a function only of the meanings of its parts and the manner of their combination. 1 In his 1879 *Begriffsschrift*, Frege introduced a formal system to surpass earlier logical frameworks, establishing the distinction between **sense** (Sinn) and **reference** (Bedeutung). 5 This distinction allowed for the analysis of how expressions with the same referent (e.g., "Morning Star" and "Evening Star") could convey different cognitive content and truth conditions. 5

The early 20th century saw the analytic tradition, represented by Bertrand Russell, Alfred Tarski, and Rudolf Carnap, further refine the logical structure of language. Tarski’s development of a rigorous theory of truth for formal languages and his analysis of truth conditions provided the cornerstone for model-theoretic semantics. 2 Carnap extended these ideas into intensional semantics, treating meanings as functions from possible worlds to denotations, thereby allowing logic to handle modal and temporal expressions. 4

The linguistic revolution of the mid-20th century, led by Noam Chomsky, introduced **generative grammar**, which posited that surface word order is not the whole structure. Chomsky’s work emphasized recursion and hierarchy, suggesting that the brain uses a finite set of rules to generate an infinite class of sentences. 2 This was synthesized with formal logic by Richard Montague in the late 1960s. **Montague grammar** treated natural language as a formal system with mathematical rigor, using higher-order logic and lambda-calculus to uniformly interpret noun phrases as generalized quantifiers. 4 Barbara Partee was instrumental in popularizing Montague’s insights, famously noting that "lambdas changed my life" as they provided the mechanism for parts of sentences to contribute systematically to their truth-values. 17

Simultaneously, Donald Davidson developed **event semantics**, arguing that action sentences should be analyzed as existential quantifications over event variables. 4 This allowed for the treatment of adverbial modifiers as additional predicates of the event. For example, "Jones buttered the toast slowly" is interpreted as "There is an event e such that e is a buttering, the agent of e is Jones, the patient of e is the toast, and e was slow". 19 The **Neo-Davidsonian** approach expanded this by treating even the main arguments (subject and object) as thematic role predicates of the event, which today forms the basis for computational **Semantic Role Labeling (SRL)**. 14

Modern computational semantics has evolved to include annotation schemes like **Abstract Meaning Representation (AMR)**, which provides a rooted, directed acyclic graph representing "who is doing what to whom" while abstracting away from surface syntactic variation. 16 While formal approaches focus on compositionality, **Construction Grammar** and usage-based linguistics remind us that some meaning is carried by fixed linguistic patterns (idioms, formulaic expressions) that are not strictly compositional. 1 This historical trajectory from Frege to modern AMR informs the structural doctrine of the SSI canon.

## **Core Linguistic-Structural Ontology**

To facilitate operational intelligence, the SSI canon adopts a standardized ontology for linguistic structure. These terms serve as the primitive objects for claim extraction and reasoning.

| Term | Definition | Contrast | Assistant-Use Note | Downstream Report |
| :---- | :---- | :---- | :---- | :---- |
| **Morpheme** | Smallest unit of meaning (e.g., *un-*, *break*, *-able*). | **Lexeme**: The abstract dictionary entry. | Critical for detecting negation or tense markers at the word level. 1 | Report D |
| **Lexeme** | The abstract unit of the lexicon (e.g., *RUN*). | **Wordform**: The specific instance (*running*, *ran*). | Essential for normalizing events and tracking entities across inflections. 1 | Report D |
| **Phrase** | A group of words acting as a single unit (e.g., "the large car"). | **Clause**: A group containing a subject and a predicate. | Use to preserve modifier boundaries; avoid "bag-of-words" drift. 24 | Report K |
| **Predicate** | The part of a clause that expresses an action or state. | **Argument**: The entities involved in the predicate. | The core "anchor" of a claim; usually a verb or adjective. 14 | Report E |
| **Proposition** | The underlying logical content of a sentence that is truth-evaluable. | **Claim**: A proposition asserted as true by a source. | Different sentences can express the same proposition (e.g., active vs. passive). 2 | Report E |
| **Modality** | Linguistic markers of possibility, necessity, or obligation. | **Factuality**: The assertion of what is actually the case. | "May" is not "shall"; "could" is not "did." Preserving modal strength is vital. 9 | Report F |
| **Scope** | The domain over which an operator (e.g., *not*, *every*) applies. | **Linear Order**: The sequence of words in a string. | Scope ambiguity determines truth conditions in complex sentences. 28 | Report K |
| **Thematic Role** | The semantic relationship between a predicate and its arguments (e.g., Agent). | **Syntactic Role**: The grammatical position (e.g., Subject). | "Who did what to whom" relies on thematic, not syntactic, roles. 14 | Report E |

## **From Form to Claim: The Linguistic Structure Pipeline**

The transition from raw text to an answerable reasoning object follows a rigorous pipeline. Each stage adds structural information while introducing potential points of failure.

### **1. The Sub-Lexical and Lexical Layer**

Meaning begins at the **Morpheme** level. Inflectional morphology (e.g., *-s* for plural, *-ed* for past) and derivational morphology (e.g., *un-* for negation) provide the initial constraints on the lexeme. AI assistants must be "morphologically competent" to recognize that "un-helmeted" is a negative state, whereas a naive model might focus on the "helmet" token and infer the presence of safety gear. 3 The **Lexeme** and **Wordform** layers stabilize the identity of the sign, ensuring that different forms of the same word are linked to a single concept. 1

### **2. The Phrasal and Clausal Layer**

Words combine into **Phrases** based on hierarchical constituent structure. The phrase is the primary unit of modification; a prepositional phrase ("with a beard") must be attached to the correct head ("the man" vs. "the car") to preserve meaning. 25 **Clauses** introduce the **Predicate-Argument Structure**, which identifies the event and its participants. This layer answers the primary question: "Who did what to whom?". 14

### **3. The Propositional Layer**

A **Proposition** is the logical representation of a clause, stripped of surface syntactic variation. "The dog chased the cat" and "The cat was chased by the dog" result in the same proposition: Chase(Agent: Dog, Patient: Cat). This is the level at which truth conditions are assigned. 2

### **4. The Claim and Reasoning Layer**

A **Claim** is a proposition situated within a context of assertion. It includes **Modality** (the degree of certainty or obligation), **Tense/Aspect** (the temporal boundary), and **Attribution** (who is making the claim). Finally, the **Reasoning Object** is the result of aligning multiple claims into a coherent structure. At this stage, the assistant must distinguish between "Source X says P" and "P is true." Failure to maintain this distinction results in the "attribution stripping" hallucination, where a reported claim is mistaken for an objective fact. 6

## **Morphology and Word-Level Meaning**

Morphology is the structural system of word internalities. In morphologically rich languages (e.g., Polish, Finnish, Turkish), much of the work English does through word order is performed through suffixes and prefixes. 32

### **Inflection, Derivation, and Agreement**

Inflectional systems handle tense, number, and case. **Case marking** is particularly crucial; it labels the grammatical function of a noun regardless of its position in the sentence. Neural models optimized for English often fail to recognize morphology as the primary indicator of syntax in these languages, over-relying on word order and lexical semantics. 32 **Agreement** (e.g., subject-verb agreement) provides a redundant but necessary structural check to ensure arguments are correctly linked to their predicates. 33

### **Negation and Evidentiality**

Morphological negation (e.g., *non-*, *a-*, *ir-*) is as powerful as sentential negation (*not*). Assistants must recognize these markers to avoid polarity reversal. 27 Some languages also possess **Evidentiality** markers—mandatory morphological suffixes that indicate the source of the information (e.g., "I saw it" vs. "I heard it" vs. "I inferred it"). 35 While English lacks these as a grammatical requirement, an AI assistant should treat them as "structural gold" when they appear in cross-linguistic retrieval, as they provide an explicit warrant for the claim's validity. 36

## **Phrase Structure, Dependency, and Predicate-Argument Relations**

To understand complex information, an assistant must map the relationships between verbs and their arguments.

### **Constituency vs. Dependency**

**Constituency Parsing** models language as a nested hierarchy of phrases. It is highly effective for identifying scope (e.g., what the word "only" applies to). 2 **Dependency Parsing** models language as binary relations between words (heads and dependents). Universal Dependencies (UD) have become a standard because they provide a cross-lingually consistent way to extract relations like "subject" and "object," which are essential for identifying the core participants in an event. 15

### **Semantic Role Labeling (SRL)**

SRL moves beyond grammatical roles (subject/object) to semantic roles (Agent/Patient). In the sentences "John broke the window" and "The window was broken by John," John is the Agent and the window is the Patient in both cases. 14 This shallow semantic representation allows an assistant to answer "Was the window broken?" regardless of whether the retrieved text is active or passive. 14

### **Event Structure and Modification**

Davidsonian event semantics treats verbs as predicates of events. This allows for "stackable" modifiers. In a medical report, "The patient experienced pain (event e) in the chest (location) during exercise (condition)," each modifier is a separate predicate of e.

exists e

This structure prevents the assistant from misattributing the "during exercise" condition to a different event in the document. 19

## **Compositional Semantics and Its Limits**

The **Principle of Compositionality** allows humans (and ideally AI) to understand an infinite variety of sentences by combining familiar parts. 1 However, this principle is constrained by several factors:

* **Idioms and Formulaic Language**: The meaning of "kick the bucket" is not compositional. Assistants must recognize these as single semantic units. 1  
* **Constructional Meaning**: Specific syntactic patterns can carry meaning that the individual words do not. For example, the "X is Y away from Z" construction implies distance, even if Y is not a unit of measurement. 1  
* **Coercion and Context**: In "I finished the book," the meaning of "finished" is coerced by the object "book" to mean "finished *reading* or *writing*." This requires world knowledge (Report D) and context (Report F) to supplement the compositional structure. 4

## **Logical Form, Operators, and Scope**

Logical form (LF) is the level where the inferential commitments of a sentence are finalized. Operators such as negation, quantifiers, and modals act as functions that transform the truth conditions of the proposition.

### **Negation and the "Pink Elephant"**

Negation is a fundamental challenge for LLMs. Models often suffer from "negation blindness" (the NO syndrome), where they recognize the topic (e.g., "elephant") but fail to process the negative operator ("no elephant"), leading to the generation of the very thing being denied. 3 This is particularly dangerous in medical contexts (e.g., "No evidence of tumor" being read as "Evidence of tumor"). 27

### **Quantifiers and Scope Ambiguity**

Quantifiers (e.g., *all*, *some*, *no*, *most*) create scope ambiguities.

* **Sentence**: "Every farmer owns a donkey."  
* **Reading 1 (Surface Scope)**: For every farmer x, there exists a donkey y such that x owns y. (Each farmer has their own donkey).  
* **Reading 2 (Inverse Scope)**: There exists a specific donkey y such that every farmer x owns y. (One shared donkey). 28

Most LLMs prefer surface scope, which can lead to errors when the inverse scope is the intended meaning in technical or legal documents. 28

### **Modality and Tense/Aspect**

Modality distinguishes between what is possible (*may*), necessary (*must*), or permitted (*can*).

* **Epistemic Modality**: "The drug *may* cause nausea" (possibility).  
* **Deontic Modality**: "The patient *must* take the drug" (obligation).

Assistants must preserve these distinctions. Strengthening a modal (turning "may" into "will") or weakening a modal (turning "shall" into "can") changes the legal or medical commitment of the claim. 9

| Operator Type | Examples | Structural Risk |
| :---- | :---- | :---- |
| **Quantifiers** | all, some, no, most, exactly one | Scope collapse; universal/generic confusion. 28 |
| **Negation** | not, never, un-, non-, without | Polarity reversal; "negation blindness". 3 |
| **Modality** | may, must, shall, could, potentially | Modal strengthening/weakening. 9 |
| **Conditionals** | if, unless, provided that, only if | Antecedent detachment (treating conditional as absolute). 9 |
| **Comparatives** | more than, less than, better, worse | Degree/Scale errors; direction reversal. 39 |

## **Structural Ambiguity and Its Diagnostics**

Ambiguity is a persistent feature of natural language. Structural intelligence requires identifying ambiguity and deploying diagnostics to resolve or flag it.

* **Attachment Ambiguity**: Modifier applies to multiple possible heads.  
  * *Example*: "I saw the man with the telescope." (Who had the telescope?). 25  
* **Coordination Ambiguity**: Conjunction scopes over different segments.  
  * *Example*: "Put the butter in the bowl and the pan on the towel." (Is the pan to be moved or is it a location?). 24  
* **Anaphora/Coreference Ambiguity**: Pronouns or referring expressions have multiple candidates.  
  * *Example*: "The contractor told the client that his report was late." (Whose report?). 41  
* **Scope Ambiguity**: Interaction between negation and quantifiers.  
  * *Example*: "Every employee did not complete the training." (None did, or some did not?). 28  
* **Garden Path Sentences**: Early false syntactic analysis.  
  * *Example*: "The horse raced past the barn fell". 25

### **Diagnostic Protocol**

An AI assistant should use "Minimal Pair" evaluation to test its own understanding. 34 If two interpretations are structurally valid, the assistant must generate **Clarified Questions** (e.g., "By 'with the telescope,' do you mean the man was holding it, or you used it to see him?") rather than guessing. 39

## **Entailment, Contradiction, and Claim Discipline**

Linguistic structure determines what an assistant is *licensed* to infer. This is the core of **Natural Language Inference (NLI)**.

* **Entailment**: Relationship where the truth of P guarantees the truth of Q.  
  * *Structure*: "John killed the cat" leads to "The cat is dead."  
* **Contradiction**: Relationship where P and Q cannot both be true.  
  * *Structure*: "No students passed" and "Some students passed."  
* **Factivity and Attribution**:  
  * **Factive**: "The study *knows* X" leads to X is likely true.  
  * **Non-Factive**: "The study *claims* X" does not imply X is true. 4  
* **Conditionals and "Unless"**:  
  * "X is true unless Y" leads to "If Y is false, X is true."  
  * **Assistant Error**: Assuming X is true without checking the status of Y. 9

### **Claim Normalization Rules**

To avoid "keyword mush," extracted claims must be normalized into a predicate-argument frame while preserving **Attribution** and **Modality**.

* **Original**: "Studies suggest the drug might be associated with reduced risk."  
* **Normalized**: Attribution: Studies; Modal: might; Predicate: associated_with(Drug, ReducedRisk).  
* **False Entailment to Avoid**: Cause(Drug, ReducedRisk). 7

## **Morphology and Cross-Linguistic Structure**

AI assistants must recognize that English-centric structural assumptions (e.g., fixed SVO word order) do not apply universally.

* **Projective vs. Non-Projective**: English is highly projective (fixed order); German and Czech are non-projective (flexible order). LLMs reason more accurately in projective languages. 3  
* **Syncretism and High Fusion**: In languages like Polish, a single morphological form can have multiple grammatical functions (syncretism). Models often fail to resolve these, leading to subject-object confusion. 32  
* **Topic-Prominence**: In languages like Chinese, the "Topic" is marked first, which is not always the "Subject." Assistants must distinguish between the topic of the sentence and the agent of the action. 28

## **Structural Doctrine for LLM/RAG Assistants**

Retrieved text chunks are not bags of words; they are structured claims. The assistant must follow these operational rules:

1. **Identify the Predicate-Argument Frame**: Answer "who did what to whom" before summarizing.  
2. **Preserve Polarity**: Never drop a negation marker (not, un-, no). 3  
3. **Maintain Modal Strength**: Do not strengthen "may" to "will" or weaken "shall" to "can". 9  
4. **Track the Scope of Operators**: Identify if a "not" applies to a word, a phrase, or the whole sentence. 27  
5. **Anchor Anaphora**: Resolve pronouns before extracting the claim as a standalone object. 43  
6. **Respect Conditionals**: Treat "if/unless" as the boundaries of the claim's validity. 12  
7. **Preserve Source Attribution**: Distinguish between an objective fact and a reported claim. 6  
8. **Reject Flattening**: If a summary requires removing the structure (e.g., "X is associated with Y" becoming "X causes Y"), flag it as a lossy paraphrase.

## **RAG-Ready Knowledge Artifacts**

To support these doctrines, retrieved data must be enriched with structural metadata.

### **Structural Metadata Schema**

| Field | Description | Example |
| :---- | :---- | :---- |
| claim_id | Unique identifier for the atomic claim. | C-1024 |
| predicate | The central action/relation. | eligibility |
| agent | The entity performing the action. | User |
| patient | The entity receiving the action. | Refund |
| modality | Degree of certainty/obligation. | not_eligible |
| condition | Exceptions or requirements. | unless_defective |
| attribution | The source of the claim. | RefundPolicy_V2 |
| scope_flag | Warning for potential scope ambiguity. | True |
| logical_form | Normalized proposition. | NOT(Eligible(User, Refund)) IF NOT(Defective(Item)) |

### **Claim Extraction Templates**

| Original Sentence | Normalized Claim | What Can Be Inferred | False Entailment to Avoid |
| :---- | :---- | :---- | :---- |
| "The system must not delete data unless consent is recorded." | MUST_NOT(Delete(Data)) UNLESS(Recorded(Consent)) | Data deletion requires recorded consent. | "The system deletes data." 48 |
| "The drug is associated with reduced risk in adults over 65." | Associated_With(Drug, ReducedRisk) FILTER(Age > 65) | There is a correlation for seniors. | "The drug *causes* reduced risk in everyone." 45 |
| "The contractor denied that the report proved negligence." | Attribution(Contractor, DENY(Prove(Report, Negligence))) | The contractor rejects the report's conclusion. | "The report proved negligence." 6 |

### **Structural Crosswalk Tables**

| Report A Term | Report C Term | Relationship |
| :---- | :---- | :---- |
| **Map/Territory** | **Surface/Logical Form** | Surface form is the map; Logical form is the territory-adjacent structure. |
| **Abstraction** | **Phrase/Clause** | Phrasal grouping is a level of abstraction over word-level tokens. |
| **Dating/Indexing** | **Tense/Aspect** | Tense/Aspect provides the linguistic index for temporal dating. |

| Report B Term | Report C Term | Relationship |
| :---- | :---- | :---- |
| **Sign-Vehicle** | **Morpheme/Lexeme** | Morphemes and Lexemes are the basic linguistic sign-vehicles. |
| **Syntactics** | **Grammar/Dependency** | Syntax is the internal rule-set of the code. |
| **Semiosis** | **Compositionality** | Compositionality is the recursive engine of linguistic meaning. |

## **Assistant Imitation Patterns**

### **Case 1: Legal Constraint Parsing**

* **User/Source**: "International orders are eligible for refunds, not exchanges."  
* **Naive Interpretation**: "You can get a refund or exchange for international orders."  
* **Structural Diagnosis**: Negation scopes over "exchanges" but not "refunds."  
* **Disciplined Reinterpretation**: "International orders are eligible for refunds. However, exchanges are explicitly prohibited."

### **Case 2: Medical Speculation vs. Fact**

* **User/Source**: "No CT evidence of large infarct. Suggest MRI to exclude hyperacute infarct."  
* **Naive Interpretation**: "The CT scan shows there is no infarct. An MRI is needed to confirm."  
* **Structural Diagnosis**: Sentential negation of "evidence" is not negation of the "infarct." "Suggest" introduces a speculative recommendation, not a factual finding.  
* **Disciplined Reinterpretation**: "The CT scan found no evidence of a large infarct, but it did not rule out a hyperacute infarct. An MRI has been recommended specifically to investigate that possibility". 27

### **Case 3: Conditional Exception**

* **User/Source**: "The system must not delete user data unless consent is recorded."  
* **Naive Interpretation**: "The system won't delete your data."  
* **Structural Diagnosis**: Deontic modality ("must not") is negated by the exception ("unless").  
* **Disciplined Reinterpretation**: "The system is prohibited from deleting user data as a default. However, if consent is recorded, deletion may occur". 9

## **Structural Failure Modes**

| Failure Mode | Definition | Example | Detection Cue |
| :---- | :---- | :---- | :---- |
| **Negation Blindness** | Ignoring a negative operator. | "not recommended" leads to "recommended" | Look for "no," "not," or negative prefixes. 3 |
| **Modal Strengthening** | Turning a possibility into a fact. | "may cause" leads to "causes" | Look for "may," "might," "could". 9 |
| **Attribution Stripping** | Removing the source of a claim. | "X claims P" leads to "P is true" | Look for attitude verbs (claims, says, believes). 6 |
| **Scope Collapse** | Misapplying a quantifier/modifier. | "Only users with admin" leads to "All users" | Look for "only," "even," "all," "none". 28 |
| **Exception Loss** | Dropping the "unless" or "except" clause. | "Refunds except annual" leads to "Refunds for all" | Look for "unless," "except," "but not". 9 |
| **Agency Distortion** | Swapping Agent and Patient. | "X was sued by Y" leads to "X sued Y" | Check passive voice/case markings. 14 |

## **What Report C Owns vs. What Later Reports Deepen**

| Concept/Distinction | Report C Treatment | Later Report Deepening | Boundary Warning |
| :---- | :---- | :---- | :---- |
| **Morpheme/Lexeme** | Internal structure/negation. | **Report D** (Category boundaries). | C owns the *form*; D owns the *concept*. |
| **Proposition** | Logical form/Truth conditions. | **Report E** (Grounding/Evidence). | C owns the *logic*; E owns the *truth*. |
| **Assertion/Claim** | Structural extraction. | **Report F** (Pragmatics/Intent). | C owns the *literal*; F owns the *implied*. |
| **Ambiguity** | Structural/Syntactic types. | **Report K** (Contextual modulation). | C owns the *parse*; K owns the *shift*. |
| **Translation** | Morphosyntactic diversity. | **Report L** (Cross-cultural jargon). | C owns the *grammar*; L owns the *domain*. |

## **Source Conflict and Debate Map**

* **Generative Syntax vs. Construction Grammar**: Generative models (Chomsky) optimize for universal rules and recursion. Construction models (Goldberg) optimize for fixed, non-compositional patterns (idioms). **SSI Integration**: Use Generative rules for novel claims; use Construction libraries for fixed legal/medical formulas. 1  
* **Constituency vs. Dependency**: Constituency captures hierarchical grouping (useful for scope). Dependency captures direct word-to-word relations (useful for "who did what"). **SSI Integration**: Use Dependencies for claim extraction; use Constituency for scope/negation resolution. 15  
* **Compositionality vs. Context-Update**: Formal semantics (Montague) calculates meaning from parts. Dynamic semantics (Heim/Kamp) treats meaning as a "context update". 4 **SSI Integration**: Compositionality provides the *potential* meaning; context-update provides the *active* reasoning object.  
* **Neural vs. Symbolic Structure**: Debate over whether LLMs genuinely learn syntax or just shallow heuristics. 50 **SSI Integration**: Treat LLM output as a "sign-vehicle" that requires symbolic verification (e.g., cross-encoders or RAG verifiers) to ensure structural integrity. 53

## **Doctrine Capsule: Linguistic-Structural Operating Rules**

1. **Grammar is a Logical Constraint**: Syntax is not "flavor"; it is the set of rules that license inference.  
2. **Negation is a Hard Boundary**: A claim with a "not" is the logical inverse of a claim without one. Never treat them as similar.  
3. **Preserve Modal Intensity**: "May," "Should," and "Must" are separate logical categories. Do not translate between them.  
4. **Identify the Agent/Patient**: Always identify the actor and the affected entity. Swapping them is a total failure of meaning.  
5. **Scope Governs Truth**: The order of quantifiers and negation determines the world in which the sentence is true.  
6. **Attribution is Part of the Claim**: A claim is never "naked"; it is always "Source says P."  
7. **Conditionals are Guards**: An "if" or "unless" is a gatekeeper. If the condition is not met, the claim does not exist.  
8. **Ambiguity is a Signal**: When a structure has two parses, the meaning is unresolved. Flag it; do not guess.  
9. **Normalizing is Not Flattening**: When converting to a database, preserve the operators (negation, modals) as first-class fields.  
10. **Linguistic Diversity is Real**: Word order is only one way to mark structure. Look for case, agreement, and evidentiality.  
11. **Keyword Relevance does not equal Claim Relevance**: A document about "refunds" that says they are "prohibited" is relevant to the topic but provides the opposite answer.  
12. **The Pipeline is One-Way**: Errors at the morphological or syntactic level propagate and multiply at the reasoning level.

## **What Report C Gives the Canon**

Report C contributes the canon's **Linguistic-Structural Ontology**, the **Morphology-to-Proposition Pipeline**, and the **Logical-Form Discipline** necessary for operational AI assistance. It provides the **Structural Ambiguity Catalogue** and **Claim-Extraction Machinery** that prevent the assistant from collapsing structured meaning into keyword entropy. By establishing the "grammar-to-logic bridge," Report C ensures that every reasoning object generated by the assistant is structurally warranted by its source, preserving the truth conditions of the semiotic signs it processes. It transforms the assistant from a "stochastic parrot" into a structurally-aware reasoning agent capable of high-fidelity logical performance in complex domains. 1

#### **Works cited**

1. (PDF) The Principle of Semantic Compositionality - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/225899934_The_Principle_of_Semantic_Compositionality](https://www.researchgate.net/publication/225899934_The_Principle_of_Semantic_Compositionality)  
2. Lecture 1: Introduction to Formal Semantics and Compositionality, accessed May 14, 2026, [http://people.umass.edu/partee/NZ_2006/NZ1.pdf](http://people.umass.edu/partee/NZ_2006/NZ1.pdf)  
3. Negation: A Pink Elephant in the Large Language Models' Room? - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2503.22395v2](https://arxiv.org/html/2503.22395v2)  
4. Formal semantics (natural language) - Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Formal_semantics_(natural_language)](https://en.wikipedia.org/wiki/Formal_semantics_(natural_language))  
5. Bridging Thought and Reality: Frege's Enduring Impact on Philosophy of Language - DergiPark, accessed May 14, 2026, [https://dergipark.org.tr/en/download/article-file/4476991](https://dergipark.org.tr/en/download/article-file/4476991)  
6. Add claim extraction and alignment substrate for qualitative deep ..., accessed May 14, 2026, [https://github.com/monarch-initiative/deep-research-client/issues/43](https://github.com/monarch-initiative/deep-research-client/issues/43)  
7. The Detection of Contradictory Claims in Biomedical Abstracts - White Rose eTheses Online, accessed May 14, 2026, [https://etheses.whiterose.ac.uk/id/eprint/15893/1/FinalThesis-Alamri.pdf](https://etheses.whiterose.ac.uk/id/eprint/15893/1/FinalThesis-Alamri.pdf)  
8. Compositionality - Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/compositionality/](https://plato.stanford.edu/entries/compositionality/)  
9. How to shrink your contracts — so that your business booms - Write ..., accessed May 14, 2026, [https://writegroup.io/shrink-contracts-business-booms/](https://writegroup.io/shrink-contracts-business-booms/)  
10. Automated Detection of Dosing Errors in Clinical Trial Narratives: A Multi-Modal Feature Engineering Approach with LightGBM - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2604.19759v1](https://arxiv.org/html/2604.19759v1)  
11. 3.2.1: MEDICAL RECORDS – Documentation, Electronic Health Records, Access, and Retention - NC Medical Board, accessed May 14, 2026, [https://www.ncmedboard.org/resources-information/professional-resources/laws-rules-position-statements/position-statements/medical-records-documentation-electronic-health-records-access-and-retentio](https://www.ncmedboard.org/resources-information/professional-resources/laws-rules-position-statements/position-statements/medical-records-documentation-electronic-health-records-access-and-retentio)  
12. Qatary Legal Portal | Legislations | Law no (22) of 2004 Regarding Promulgating the Civil Code - Al Meezan, accessed May 14, 2026, [https://www.almeezan.qa/LawArticles.aspx?LawTreeSectionID=2158&LawID=2559&language=en](https://www.almeezan.qa/LawArticles.aspx?LawTreeSectionID=2158&LawID=2559&language=en)  
13. Language models are not naysayers: an analysis of language models on negation benchmarks - ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2023.starsem-1.10/](https://aclanthology.org/2023.starsem-1.10/)  
14. Semantic Role Labeling - Stanford University, accessed May 14, 2026, [https://web.stanford.edu/~jurafsky/slp3/21.pdf](https://web.stanford.edu/~jurafsky/slp3/21.pdf)  
15. Evaluating Universal Dependency Parser Recovery of Predicate Argument Structure via CompChain Analysis - ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2021.starsem-1.11.pdf](https://aclanthology.org/2021.starsem-1.11.pdf)  
16. Semantic Bridge: Universal Multi-Hop Question Generation via AMR-Driven Graph Synthesis - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2508.10013v1](https://arxiv.org/html/2508.10013v1)  
17. Montague semantics - Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/montague-semantics/](https://plato.stanford.edu/entries/montague-semantics/)  
18. On the history of the question of whether natural language is “illogical”, accessed May 14, 2026, [https://hiphilangsci.net/2013/05/01/on-the-history-of-the-question-of-whether-natural-language-is-illogical/](https://hiphilangsci.net/2013/05/01/on-the-history-of-the-question-of-whether-natural-language-is-illogical/)  
19. EVENT-BASED SEMANTICS Peter N. Lasersohn University of Illinois Department of Linguistics Urbana, Illinois 61801, U.S.A. Abstrac, accessed May 14, 2026, [https://semanticsarchive.net/Archive/jFhNWM2M/eventbasedsemantics.pdf](https://semanticsarchive.net/Archive/jFhNWM2M/eventbasedsemantics.pdf)  
20. 34. Event semantics, accessed May 14, 2026, [https://d-nb.info/1161944222/34](https://d-nb.info/1161944222/34)  
21. NEO-DAVIDSONIAN EVENT SEMANTICS "Strange goings on! Jones did it slowly, deliberately, in the bath, accessed May 14, 2026, [https://www.tau.ac.il/~landman/Online%20Class%20Notes/2%20ADVANCED%20SEMANTICS/8%20Neo-davidsonian%20event%20semantics.pdf](https://www.tau.ac.il/~landman/Online%20Class%20Notes/2%20ADVANCED%20SEMANTICS/8%20Neo-davidsonian%20event%20semantics.pdf)  
22. Neo-Davidsonian Event Semantics - Emergent Mind, accessed May 14, 2026, [https://www.emergentmind.com/topics/neo-davidsonian-event-semantics](https://www.emergentmind.com/topics/neo-davidsonian-event-semantics)  
23. Abstract Meaning Representation Parsing - Michtom School of Computer Science, accessed May 14, 2026, [https://www.cs.brandeis.edu/~cwang24/files/thesis-wang.pdf](https://www.cs.brandeis.edu/~cwang24/files/thesis-wang.pdf)  
24. Processing Coordination Ambiguity | Ferreira Lab, accessed May 14, 2026, [https://ferreiralab.faculty.ucdavis.edu/wp-content/uploads/sites/222/2015/05/Engelhardt-Ferreira-2010_CoordinationAmbiguity_Lang-Speech.pdf](https://ferreiralab.faculty.ucdavis.edu/wp-content/uploads/sites/222/2015/05/Engelhardt-Ferreira-2010_CoordinationAmbiguity_Lang-Speech.pdf)  
25. Processing ambiguities in attachment and pronominal reference | Glossa, accessed May 14, 2026, [https://www.glossa-journal.org/article/id/5325/](https://www.glossa-journal.org/article/id/5325/)  
26. EP0413132A2 - A computer method for identifying predicate-argument structures in natural language text - Google Patents, accessed May 14, 2026, [https://patents.google.com/patent/EP0413132A2/en](https://patents.google.com/patent/EP0413132A2/en)  
27. Deep Learning Approach for Negation and Speculation Detection ..., accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10170361/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10170361/)  
28. Quantifier Scope Interpretation in Language Learners and LLMs - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/395527573_Quantifier_Scope_Interpretation_in_Language_Learners_and_LLMs](https://www.researchgate.net/publication/395527573_Quantifier_Scope_Interpretation_in_Language_Learners_and_LLMs)  
29. Scope Ambiguities in Large Language Models - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2404.04332v1](https://arxiv.org/html/2404.04332v1)  
30. Semantic Role Labeling, accessed May 14, 2026, [https://people.engr.tamu.edu/huangrh/Fall18-638/l15_srl.pdf](https://people.engr.tamu.edu/huangrh/Fall18-638/l15_srl.pdf)  
31. Artificial Intelligence Can Not Yet Reliably Read and Extract Information from Clinical Notes in Medical Records, accessed May 14, 2026, [https://www.publichealth.columbia.edu/news/artificial-intelligence-can-not-yet-reliably-read-extract-information-clinical-notes-medical-records](https://www.publichealth.columbia.edu/news/artificial-intelligence-can-not-yet-reliably-read-extract-information-clinical-notes-medical-records)  
32. Morphological competence in neural natural language processing - Apollo, accessed May 14, 2026, [https://www.repository.cam.ac.uk/items/d8bfc0c7-09e9-4144-a0a6-b3bf9299b3c0](https://www.repository.cam.ac.uk/items/d8bfc0c7-09e9-4144-a0a6-b3bf9299b3c0)  
33. Cross-Lingual Morphological Tagging for Low-Resource Languages - Google Research, accessed May 14, 2026, [https://research.google.com/pubs/archive/45387.pdf](https://research.google.com/pubs/archive/45387.pdf)  
34. Evaluating the Cross-Lingual Syntactic Capabilities of Language Models - Suchir Salhan, accessed May 14, 2026, [https://suchirsalhan.github.io/assets/tripos/L95/L95_Salhan_xBLiMP_25_26.pdf](https://suchirsalhan.github.io/assets/tripos/L95/L95_Salhan_xBLiMP_25_26.pdf)  
35. The Semantics of Evidentials in Questions | Request PDF - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/344609448_The_Semantics_of_Evidentials_in_Questions](https://www.researchgate.net/publication/344609448_The_Semantics_of_Evidentials_in_Questions)  
36. Linguistics Today: Facing A Greater Challenge, accessed May 14, 2026, [https://coehuman.uodiyala.edu.iq/uploads/Coehuman%20library%20pdf/English%20library%D9%83%D8%AA%D8%A8%20%D8%A7%D9%84%D8%A7%D9%86%D9%83%D9%84%D9%8A%D8%B2%D9%8A/linguistics/Linguistics%20Today%20Facing%20A%20Greater%20Challenge.pdf](https://coehuman.uodiyala.edu.iq/uploads/Coehuman%20library%20pdf/English%20library%D9%83%D8%AA%D8%A8%20%D8%A7%D9%84%D8%A7%D9%86%D9%83%D9%84%D9%8A%D8%B2%D9%8A/linguistics/Linguistics%20Today%20Facing%20A%20Greater%20Challenge.pdf)  
37. Quantifier Scope Interpretation in Language Learners and LLMs - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2509.10860v1](https://arxiv.org/html/2509.10860v1)  
38. OCR-Mediated Modality Dominance in Vision-Language Models ..., accessed May 14, 2026, [https://www.medrxiv.org/content/10.64898/2026.02.22.26346828v1.full-text](https://www.medrxiv.org/content/10.64898/2026.02.22.26346828v1.full-text)  
39. MARCH: Evaluating the Intersection of Ambiguity Interpretation and Multi-hop Inference, accessed May 14, 2026, [https://arxiv.org/html/2509.22750v4](https://arxiv.org/html/2509.22750v4)  
40. Examining the Application of Artificial Intelligence Techniques in Enabling Syntactic Ambiguity such as Attachment Ambiguity amo - Journal of Information Systems Engineering and Management, accessed May 14, 2026, [https://jisem-journal.com/index.php/journal/article/download/8312/3777/13824](https://jisem-journal.com/index.php/journal/article/download/8312/3777/13824)  
41. ARTIFICIAL INTELLIGENCE-ENABLED AUTOMATION FOR AMBIGUITY HANDLING AND QUESTION ANSWERING IN NATURAL- LANGUAGE REQUIREMENTS - ORBilu, accessed May 14, 2026, [https://orbilu.uni.lu/bitstream/10993/52045/1/Saad_Ezzini_PhD_Thesis.pdf](https://orbilu.uni.lu/bitstream/10993/52045/1/Saad_Ezzini_PhD_Thesis.pdf)  
42. Can LLMs handle ambiguity in language? - Milvus, accessed May 14, 2026, [https://milvus.io/ai-quick-reference/can-llms-handle-ambiguity-in-language](https://milvus.io/ai-quick-reference/can-llms-handle-ambiguity-in-language)  
43. Extending Nocuous Ambiguity Analysis for Anaphora in Natural Language Requirements, accessed May 14, 2026, [https://www.researchgate.net/publication/224195450_Extending_Nocuous_Ambiguity_Analysis_for_Anaphora_in_Natural_Language_Requirements](https://www.researchgate.net/publication/224195450_Extending_Nocuous_Ambiguity_Analysis_for_Anaphora_in_Natural_Language_Requirements)  
44. Detecting Ambiguities to Guide Query Rewrite for Robust Conversations in Enterprise AI Assistants - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2502.00537v1](https://arxiv.org/html/2502.00537v1)  
45. CIP: A Plug-and-Play Causal Prompting Framework for Mitigating Hallucinations under Long-Context Noise - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2512.11282v1](https://arxiv.org/html/2512.11282v1)  
46. [2503.22395] Negation: A Pink Elephant in the Large Language Models' Room? - arXiv, accessed May 14, 2026, [https://arxiv.org/abs/2503.22395](https://arxiv.org/abs/2503.22395)  
47. Anaphora Ambiguity Detection Method Based on Cross-domain Pronoun Substitution, accessed May 14, 2026, [https://pure.ecnu.edu.cn/en/publications/anaphora-ambiguity-detection-method-based-on-cross-domain-pronoun/](https://pure.ecnu.edu.cn/en/publications/anaphora-ambiguity-detection-method-based-on-cross-domain-pronoun/)  
48. CONTRACT SUMMARY SHEET - City of Los Angeles, accessed May 14, 2026, [https://cityclerk.lacity.org/onlinecontracts/2022/C-137261_c_10-14-22.pdf](https://cityclerk.lacity.org/onlinecontracts/2022/C-137261_c_10-14-22.pdf)  
49. Contract Law in the Age of Agentic AI: Who's Really Clicking “Accept”? - Insights - Proskauer, accessed May 14, 2026, [https://www.proskauer.com/blog/contract-law-in-the-age-of-agentic-ai-whos-really-clicking-accept](https://www.proskauer.com/blog/contract-law-in-the-age-of-agentic-ai-whos-really-clicking-accept)  
50. Large Language Model Reasoning Failures - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2602.06176v1](https://arxiv.org/html/2602.06176v1)  
51. (PDF) Large Language Model Reasoning Failures - ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/400583007_Large_Language_Model_Reasoning_Failures](https://www.researchgate.net/publication/400583007_Large_Language_Model_Reasoning_Failures)  
52. From Frege to chatGPT: Compositionality in language, cognition, and deep neural networks, accessed May 14, 2026, [https://arxiv.org/html/2405.15164v1](https://arxiv.org/html/2405.15164v1)  
53. 8 Advanced RAG Techniques & How to Implement Them in Production - Intuz, accessed May 14, 2026, [https://www.intuz.com/blog/advanced-rag-techniques](https://www.intuz.com/blog/advanced-rag-techniques)  
54. Entropic Claim Resolution: Uncertainty-Driven Evidence Selection for RAG - arXiv, accessed May 14, 2026, [https://arxiv.org/html/2603.28444v1](https://arxiv.org/html/2603.28444v1)

---

