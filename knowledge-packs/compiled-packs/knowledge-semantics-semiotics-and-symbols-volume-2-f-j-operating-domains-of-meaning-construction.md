# Volume 2. F-J Operating Domains of Meaning Construction

- [F. Context, Intention & Pragmatic Inference](#f-context-intention--pragmatic-inference)
- [G. Metaphor, Embodiment & Cognitive Models](#g-metaphor-embodiment--cognitive-models)
- [H. Discourse, Narrative & Social Reality](#h-discourse-narrative--social-reality)
- [I. Symbolic Culture, Myth, Ritual & Memetics](#i-symbolic-culture-myth-ritual--memetics)
- [J. Multimodal Signs & Interface Symbolics](#j-multimodal-signs--interface-symbolics)

---

# F. Context, Intention & Pragmatic Inference

The transition from Volume I to Volume II of the Semantic-Semiotic Intelligence (SSI) canon marks a fundamental shift in the unit of analysis. While Volume I established the constitutive mechanics of meaning—representation, sign-relations, linguistic composition, conceptual framing, and epistemic grounding—Volume II moves from the abstract potential of language to its concrete realization in live interaction. Report F introduces the pragmatic layer, defining the operating domain where a structured, concept-bearing expression is transformed into a situated action. The governing thesis of this report is that pragmatic meaning is not a secondary addition to semantics but is the emergent property of communication itself. Semantic intelligence only achieves interactional competence when it can move beyond the literal decoding of sentences to the interpretation of utterances as moves within a social or institutional game. This requires a rigorous ability to distinguish sentence meaning from utterance meaning, locutionary content from illocutionary force, entailment from implicature, and presupposition from assertion. The central inquiry of Report F orbits the essential coordination problem of any agent: determining what a specific utterance is doing here, between these specific participants, under these shared assumptions, through this specific channel, and what response would satisfy the actual communicative move.1

## **The Ontology of the Utterance: From Saying to Doing**

The foundational distinction in pragmatic intelligence is the move from the sentence—a grammatical abstraction studied in Report C—to the utterance—a unique historical event involving the production of signs in a specific context. J.L. Austin’s rejection of the "descriptive fallacy" established that language does more than report facts; it performs actions.2 Within the SSI framework, every utterance is analyzed as a three-dimensional event: the locutionary act (the production of meaningful sounds or text), the illocutionary act (the action performed in saying something, such as requesting or promising), and the perlocutionary effect (the actual impact on the listener’s thoughts or behaviors).2

The illocutionary force of an utterance determines its "direction of fit" between words and the world. Interactional competence requires identifying whether an utterance aims to make the world match the words (as in directives and commissives) or to make the words match the world (as in assertives). Recent scholarship in 2024 has refined this by distinguishing between representational force—the presentation of a proposition as true—and illocutionary force—the social-communicative significance of the act.8 A failure to distinguish these leads to "literalist failure," where an agent interprets the representational content but misses the social move. For example, a user asking "Can you look this over?" provides a representational inquiry into capacity, but the illocutionary move is a directive requesting action. A pragmatically disciplined system recognizes the directive as the primary target for uptake.10

### **Taxonomy of Illocutionary Acts and Directions of Fit**

The following table operationalizes Searle’s taxonomy for AI interpretation, mapping act types to their logical directions of fit and typical institutional realizations.

| Speech Act Category | Direction of Fit | Illocutionary Point | Examples in Documentation/HCI |
| :---- | :---- | :---- | :---- |
| **Assertives** | Word-to-World (↓) | Commit speaker to the truth of p. | Reports, citations, factual claims. |
| **Directives** | World-to-Word (↑) | Get addressee to do action A. | Instructions, prompts, policy mandates. |
| **Commissives** | World-to-Word (↑) | Commit speaker to future action A. | Service level agreements, guarantees. |
| **Expressives** | None (Presupposed) | Express psychological state toward p. | Apologies, greetings, user feedback. |
| **Declarations** | Both (↕) | Change reality by uttering the act. | Authorizations, system state changes. |

2

## **The Mechanics of Inference: Implicature and Relevance**

Because the literal content of an utterance rarely exhausts its communicative intent, agents rely on pragmatic inference to bridge the gap. H.P. Grice’s Cooperative Principle provides the baseline expectation that participants will contribute what is required for the accepted purpose of the talk exchange.2 This principle is operationalized through maxims of Quantity (informativeness), Quality (truthfulness), Relation (relevance), and Manner (clarity). Implicatures arise when these maxims are either observed or "flouted"—deliberately and obviously violated to signal a deeper, non-literal meaning.2

A critical distinction for the SSI canon is between generalized conversational implicature (GCI) and particularized conversational implicature (PCI). GCIs are triggered by specific linguistic forms regardless of context, such as the scalar implicature where "some" implicates "not all".2 PCIs, however, depend entirely on the shared situation; "The station is around the corner" only implicates "You can get fuel there" if the previous move was "I’m out of fuel".2 Modern dialogue systems often struggle with PCIs because they lack the "situational knowledge" to link disparate turns into a coherent inferential chain.

### **Relevance Theory and Cognitive Efficiency**

Sperber and Wilson’s Relevance Theory offers a more cognitively grounded alternative to Gricean maxims. It suggests that human communication is governed by the Principle of Relevance: every act of ostensive communication carries a presumption of its own optimal relevance.20 Relevance is a function of the ratio between positive cognitive effects (the revision or addition of assumptions) and the processing effort required to achieve them.20

Relevance \= Cognitive Effects / Processing Effort

In this framework, the "first interpretation to satisfy the hearer’s expectation of relevance" is the one the speaker intended. Interactionally competent intelligence must therefore optimize its outputs to minimize user processing effort while maximizing information gain.15 For RAG systems, this means prioritizing "explicature"—the pragmatic enrichment of retrieved snippets—so the user does not have to manually resolve references or disambiguate terms.20

## **Common Ground and the Logic of Joint Action**

Meaning construction is fundamentally a joint activity, not a unilateral transmission of information. Herbert Clark and Robert Stalnaker established that successful communication depends on "common ground"—the body of information that is presumed to be shared by the parties to a discourse.1 Common ground functions as a "container" for mutually recognized propositions or, in more sophisticated "mentalist" views, as a structure of shared mental states.1

### **The Grounding Process**

The accumulation of common ground occurs through "grounding," a collaborative process where participants provide evidence of understanding.27 This process is essential for human-AI collaboration, as agents must track what has been "accepted" into the shared context versus what remains private or contested.29

| Type of Common Ground | Basis for Sharing | Pragmatic Role |
| :---- | :---- | :---- |
| **Communal** | Shared membership in a community (e.g., medical, legal). | Establishes default terminology and norms. |
| **Personal** | Joint interactional history between specific agents. | Allows for elliptical reference and "shorthand." |
| **Initial** | Presuppositions at the start of an activity. | Provides the "vocabulary" and starting premises. |
| **Current state** | The immediate goal and focus of the joint action. | Determines the relevance of the next move. |

26

A failure in grounding leads to "common-ground mismatch," where the AI assumes a level of shared knowledge the user lacks, or vice versa. This often manifests in RAG when the system retrieves a technical snippet that relies on communal common ground (e.g., specific industry jargon) not shared by the non-expert user.33 Interactional intelligence requires active "responsibility tracking" to record who asserted which premise and whether it was successfully grounded.29

### **Presupposition Accommodation and Epistemic Vigilance**

Presuppositions are the propositions that an utterance takes for granted. For example, "The policy update failed" presupposes that a policy update was attempted.35 Because presuppositions are "not-at-issue," they are typically accommodated—silently accepted to maintain conversational flow.36

However, LLMs frequently fall into the "presupposition accommodation trap," where they accept false or harmful premises smuggled into a loaded question (e.g., "Why did the company hide its 2023 losses?"). Research in 2025 indicates that models default to accommodation due to insufficient "epistemic vigilance," effectively endorsing misinformation.35 Pragmatic intelligence requires the ability to signal a "grounding conflict" and reject a false presupposition rather than silently proceeding with a task based on a flawed premise.36

## **Deixis: Anchoring Meaning in Contextual Coordinates**

Deictic expressions are linguistic elements whose referents are determined by the context of the utterance. Words like *I, you, here, now, this, that, next, yesterday,* and *above* act as indexical artifacts that require context coordinates to be resolved.3 David Kaplan’s seminal theory distinguishes between the "character" of an indexical (its stable linguistic rule) and its "content" (its referent in a specific context).3 For instance, the character of "now" is "the time of utterance," but its content shifts with every second.

### **Dimensions of Deictic Anchoring**

Interactional competence requires a multi-dimensional resolution of deictic centers (the "origo").

1. **Person Deixis:** Mapping participant roles (speaker, addressee) to specific entities.39  
2. **Place Deixis:** Resolving spatial references relative to the speaker’s location.39  
3. **Time Deixis:** Anchoring temporal references to the moment of utterance.39  
4. **Social Deixis:** Identifying the relative power, status, or distance between participants, which determines politeness expectations.42  
5. **Discourse Deixis:** Referencing prior or upcoming segments of the talk exchange (e.g., "that last point").3  
6. **Document Deixis:** Resolving internal references within a text (e.g., "the section below," "attached policy").45

In RAG pipelines, "deictic collapse" is a primary failure mode. When a sentence is retrieved as an isolated chunk (e.g., "The policy was updated yesterday"), the indexical "yesterday" is stripped of its anchoring coordinate. Without the document’s publication date and version history, the "yesterday" is uninterpretable or, worse, interpreted relative to the current system time.34 SSI doctrine mandates "Contextual Retrieval"—passing chunks alongside their full document metadata—to ensure every indexical is re-anchored before generation.47

## **Social Navigation: Face, Footing, and Politeness**

Communication is a social risk. Erving Goffman and later Brown and Levinson theorized that interlocutors manage "face"—their public self-image.43 Politeness is the set of strategies used to mitigate "face-threatening acts" (FTAs), such as making a request, giving a critique, or disagreeing.50

### **Positive and Negative Face**

* **Positive Face:** The desire to be liked, validated, and seen as competent. Positive politeness strategies include compliments, claiming common ground, and showing interest.50  
* **Negative Face:** The desire for autonomy and freedom from imposition. Negative politeness strategies include hedging, indirectness, and apologizing for the intrusion.43

Research in 2025 reveals a "pragmatic misalignment" in LLMs: they disproportionately rely on negative politeness (hedging) even in positive contexts where humans expect rapport-building.53 This over-reliance on "distancing" strategies can create an interpretive cost for users, who may misread the hedging as hidden negative evaluation or system uncertainty.53 Interactionally competent agents must adapt their "footing"—the alignment they take toward their utterance and the user—based on the social distance, relative power, and degree of imposition in the task.43

## **Sequential Meaning and Conversation Analysis**

Pragmatic meaning is inherently sequential. Conversation Analysis (CA) demonstrates that talk is organized into "turns" and "adjacency pairs," where the first part of a pair (e.g., a question) sets a normative expectation for the second part (e.g., an answer).56

### **Preference Organization and Uptake**

The "uptake" of an utterance is determined by how it is treated in the next turn. Responses are categorized as "preferred" (aligning with the expected move) or "dispreferred" (diverging from it).57 Dispreferred responses are structurally marked by delays, hesitations, and mitigations. For example, "I guess we're doing it that way" is a dispreferred agreement, signaling underlying resistance or doubt.59

| First Pair Part (FPP) | Preferred Second Part (SPP) | Dispreferred SPP (Marked) |
| :---- | :---- | :---- |
| **Invitation** | Acceptance | Refusal (with reason/delay). |
| **Request** | Compliance | Rejection (with apology). |
| **Assessment** | Agreement | Disagreement (with mitigation). |
| **Question** | Answer | Non-answer/Clarification. |

56

### **Repair: Detecting and Resolving Trouble**

Conversational repair is the process of fixing problems in speaking, hearing, or understanding.61 It is the primary evidence for communicative success; how participants fix misalignments reveals their true intent.61 In human-agent dialogue, "incremental repair" or "prompt scaffolding" allows users to layer in clarifications over multiple turns to refine an underspecified request.62 Interactional intelligence requires the system to initiate repair when it detects "pragmatic leakage" or high-stakes ambiguity.64

## **Pragmatic Drift in Digital and Platform Ecologies**

The shift from face-to-face to platform-mediated communication has introduced novel pragmatic norms and "platform-specific indexicality".66 Interlocutors use contextualization cues—emojis, hashtags, tone indicators (e.g., "/s" for sarcasm), and meme syntax—to frame their intent in the absence of vocal tone or gesture.66

### **Meme-Coded Indirectness and "Memesis"**

Internet memes function as multimodal enthymemes—arguments where a premise is left unstated because it is part of the "referential knowledge" of the subculture.68 On platforms like TikTok, users engage in "memesis"—the collective creative rewriting of templates to signal group cohesion or "playful patriotism".70 Interpretation of these moves requires more than semantic decoding; it requires access to the "rhizomatic assemblages" of affect and identity that memes represent.73

Pragmatic drift across platforms means that a phrase like "Let’s circle back" is a professional directive in Slack but may be a mock performative in a YouTube comment.66 AI systems must be "genre-aware," identifying the communicative ecology of the platform to avoid "genre blindness"—treating a stylized status signal as a factual assertion.66

## **Operational SSI Artifacts: RAG-Ready Pragmatics**

To translate this theory into operational behavior, Report F supplies compact RAG-ready artifacts. These structures ensure that the inference process is transparent, warranted, and anchored to situational reality.

### **Pragmatic Context Record (PCR)**

The PCR maintains the "situational origo" for every exchange, ensuring deictic and social anchoring.

| Dimension | Component | Contextual Requirement |
| :---- | :---- | :---- |
| **Participants** | Footing & Roles | Define institutional status (e.g., "Support Tier 2" vs. "Frustrated Client"). |
| **Channel/Genre** | Medium Affordances | Identify platform norms (e.g., "Slack Thread" vs. "Legal Disclaimer"). |
| **Deictic Center** | Spatio-Temporal Origo | Reference document publication date, version, and local system time. |
| **Common Ground** | Grounded Propositions | List propositions explicitly accepted into the "container." |
| **Sequential State** | Active Sequence | Identify current Adjacency Pair (e.g., "Waiting for User Acceptance"). |

### **Deixis Resolution Record (DRR)**

The DRR prevents "context collapse" by re-anchoring indexicals in retrieved snippets.

| Indexical | Character | Resolved Content | Source Warrant | Confidence |
| :---- | :---- | :---- | :---- | :---- |
| **"Yesterday"** | time of utterance \- 1 day | Oct 12, 2024 | Doc Metadata: PubDate: 2024-10-13 | High |
| **"Attached"** | Object in Channel | Vulnerability\_Log\_v2.csv | Sequential turn 4: File Upload event. | High |
| **"This policy"** | Active Policy (Speaker) | ACME Infosec Policy v3 | Retrieval context: Document title. | High |
| **"Here"** | Location (Speaker) | Server Cluster B | Document location tag: DC-West-B. | Medium |

### **Utterance-Force Profile (UFP)**

The UFP identifies the communicative move, distinguishing what is *said* from what is *done*.

| Utterance | Locution (Sentence) | Illocution (Force) | Intended Uptake | Warranted Intent Reading |
| :---- | :---- | :---- | :---- | :---- |
| "Can you send that today?" | Ability/Possibility inquiry. | **Directive** (Request). | User sends object X by deadline. | Request (Likely) |
| "Nice job." | Evaluation of action. | **Expressive** (Praise/Sarcasm). | Social rapport vs. Face threat. | Sarcasm? (Check history) |
| "I'm cold." | Sensory report. | **Directive** (Indirect Request). | Addressee closes window. | Indirect Request (Low) |
| "Policy update is live." | Status report. | **Assertive** \+ **Declaration**. | Users update local configurations. | Assertion (High) |

### **Presupposition Ledger (PL)**

The PL tracks "not-at-issue" content to prevent the accommodation of false or harmful premises.

| Presupposition | Trigger | Status in Common Ground | Epistemic Vigilance Move |
| :---- | :---- | :---- | :---- |
| A policy was misused. | Change-of-state ("stopped") | Unwarranted/Contested. | **Repair:** Signal lack of knowledge. |
| The system has 2023 losses. | Factive ("Why did...") | Not established. | **Repair:** Challenge the premise. |
| User has a sister. | Possessive ("My sister") | Accommodated (Low risk). | **Accept:** Add to Personal CG. |

## **Before/After Behavior: Naive vs. Pragmatically Disciplined**

The following examples demonstrate the gap between literalist failure and SSI interactional competence.

| User/Doc Utterance | Naive Interpretation | Pragmatically Disciplined SSI |
| :---- | :---- | :---- |
| **User:** "Can you just look this over?" | **Failure:** "Yes, I have OCR and NLP capabilities to process your text." | **Uptake:** "I’d be happy to review it. Are there specific criteria or sections I should focus on?" |
| **User:** "I guess we're doing it that way." | **Failure:** "Confirmed. I have recorded your agreement to Proceed with Method X." | **Uptake:** "I detect some hesitation. Are there risks in Method X we should address before finalizing?" |
| **User:** "Have you stopped misusing citations?" | **Failure:** "I do not misuse citations, so I cannot stop doing so." | **Uptake:** "I aim for high accuracy. Is there a specific citation I provided that was incorrect?" |
| **Doc:** "The policy was updated yesterday." | **Failure:** "The policy was updated on May 13, 2026 (current system time)." | **Uptake:** "According to the source dated Dec 2023, the policy was updated on Dec 14, 2023." |
| **Doc:** "This disclaimer limits our liability for errors." | **Failure:** "The document contains a statement regarding errors and responsibility." | **Uptake:** "This is a **Commissive** (Disclaimer). Do not treat the following claims as warranted evidence." |

## **Pragmatic Failure Modes and Repair Table**

Interactionally competent agents must identify their own failure points and deploy standard "repair moves" to maintain common ground.62

| Failure Mode | Interactional Mechanism | SSI Repair Move |
| :---- | :---- | :---- |
| **Literalism** | Treating a Directive as an Assertive Capacity Inquiry. | Restate likely intent: "I'll start the review now." |
| **Deictic Collapse** | Interpreting "here/now" relative to System origo instead of Doc origo. | Metadata re-anchoring; lower confidence if source date is unknown. |
| **Accommodation Trap** | Silently accepting a false/unsafe presupposition. | Surface the premise: "I wasn't aware of any losses; can you clarify?" |
| **Genre Blindness** | Treating performative marketing as factual evidence. | Identify genre force; tag as "Self-Presentation" vs. "Evidence." |
| **Common Ground Mismatch** | Using jargon or assuming history not grounded. | Engage in grounding: "To clarify, by 'ACID' I mean atomicity..." |
| **Politeness Misread** | Misinterpreting negative hedging as system error or doubt. | Intent check: "I'm suggesting this as a cautious option, not a refusal." |
| **Face-Threat Escalation** | Being overly direct in a high-distance/low-power role. | Footing adjustment: Use negative politeness/indirectness. |
| **Clarification Avoidance** | Guessing intent on high-stakes ambiguous moves. | Clarification check: "Do you mean Action A or Action B? This is critical." |
| **Strategic Ambiguity** | Failing to notice a user is intentionally being vague. | Maintain alternatives; avoid forced resolution on "deniable" moves. |

33

## **Synthesis: Conflict Mapping and Theoretical Resolution**

Theoretical frameworks often disagree on the nature of intention, convention, and cultural variance. The SSI canon resolves these by mapping them to specific interpretive tasks.

1. **Intention vs. Convention:** Gricean accounts prioritize speaker intention, while Speech Act Theory emphasizes conventional procedures (felicity conditions).4 SSI doctrine uses convention for institutional documents (policies, disclaimers) and intention for live user dialogue.15  
2. **Rationality vs. Affect:** Gricean maxims assume a "Rational Agent," while Politeness Theory (Goffman, B\&L) prioritizes social risk and face.2 SSI doctrine requires a "Social-Cognitive" hybrid that assumes users are cooperative but also face-sensitive.53  
3. **Universal vs. Cultural Variance:** While Brown and Levinson claim "face" is universal, sociolinguistic critiques highlight that cultures vary in their preference for autonomy (Negative Face) versus connection (Positive Face).42 In East Asian contexts, for instance, dissatisfaction rates are 23% higher when AI fails to adapt to honorific and social status cues.80 SSI handles this through platform-specific and community-specific "Common Ground Snapshots."  
4. **Inference vs. Sequentiality:** Relevance Theory focuses on the single-utterance cognitive ratio, while Conversation Analysis focuses on the multi-turn sequence.21 SSI prioritizes sequential uptake (CA) as the "gold standard" for validating an inference.61

## **What Report F Gives the Canon**

Report F serves as the gateway to Volume II by turning static semantic knowledge into situated communicative intelligence. While Volume I established what signs are and what they mean in isolation, Report F establishes **what is being done with words in context**. It provides the operating UNIT of live meaning: the **utterance-in-context**.

The SSI canon is now interactionally competent, possessing the ability to distinguish:

* **"This is phrased as a question, but functions as a request."** Identifying illocutionary force over locutionary form.5  
* **"The presupposition is not established."** Maintaining an Epistemic Ledger to avoid accommodation traps.36  
* **"The referent of 'this' is ambiguous."** Flagging deictic failure in retrieved snippets and seeking metadata anchoring.34  
* **"The utterance depends on shared context from the prior exchange."** Tracking the accumulation of common ground over turns.1  
* **"The source is performing reassurance, not providing evidence."** Recognizing document genres like marketing or disclaimers as performative rather than assertive.78  
* **"This likely implicates X, but does not entail X."** Separating defeasible inferences from logical necessities for proper warranting.2  
* **"The intent reading is plausible but low-confidence."** Applying Report E’s confidence discipline to intent inference.53  
* **"This ambiguity is high-stakes; clarify before acting."** Resolving the trade-off between autonomous inference and conversational repair.62  
* **"The user is asking for action, not explanation."** Identifying the "intended uptake" of directives.11  
* **"The pragmatic force changes under a different role relation or genre."** Tracking platform drift and social distance variables.43

Report F establishes the interactional foundation upon which the subsequent reports will build. Report G will deepen this by exploring how context-dependent metaphors and embodied cognition enrich pragmatic meaning. Report H will move from the turn-by-turn sequence to the broader domains of discourse, narrative, and ideology, explaining how situated utterances aggregate into social realities. Report F ensures that every communicative move in the intelligence system is grounded not just in linguistic form, but in interactional purpose.

#### **Works cited**

1. (PDF) Common ground in pragmatics \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/375792392\_Common\_ground\_in\_pragmatics](https://www.researchgate.net/publication/375792392_Common_ground_in_pragmatics)  
2. Pragmatics | Definition, Austin, Speech Acts, Grice, Implicatures ..., accessed May 14, 2026, [https://www.britannica.com/science/pragmatics](https://www.britannica.com/science/pragmatics)  
3. Indexicals \- Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/indexicals/](https://plato.stanford.edu/entries/indexicals/)  
4. Speech act \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Speech\_act](https://en.wikipedia.org/wiki/Speech_act)  
5. Illocutionary act \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Illocutionary\_act](https://en.wikipedia.org/wiki/Illocutionary_act)  
6. Classification and Components of Austin's Speech Act Theory \- Journal of Strategic Research in Social Science (JoSReSS), accessed May 14, 2026, [https://www.josrss.com/dergi/classification-and-components-of-austins-speech-act-theory20220820031703.pdf](https://www.josrss.com/dergi/classification-and-components-of-austins-speech-act-theory20220820031703.pdf)  
7. Taxonomizing Representational Harms using Speech Act Theory \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.findings-acl.202.pdf](https://aclanthology.org/2025.findings-acl.202.pdf)  
8. Full article: 'Austin vs. Searle on locutionary and illocutionary acts' \- Taylor & Francis, accessed May 14, 2026, [https://www.tandfonline.com/doi/full/10.1080/0020174X.2024.2380322](https://www.tandfonline.com/doi/full/10.1080/0020174X.2024.2380322)  
9. 'Austin vs. Searle on locutionary and illocutionary acts' \- PHAIDRA, accessed May 14, 2026, [https://services.phaidra.univie.ac.at/api/object/o:2086280/download](https://services.phaidra.univie.ac.at/api/object/o:2086280/download)  
10. Understanding Austin and Searle's Speech Acts | PDF | Cognition | Semiotics \- Scribd, accessed May 14, 2026, [https://www.scribd.com/document/839420218/Austin-and-Searle-s-Speech-Acts](https://www.scribd.com/document/839420218/Austin-and-Searle-s-Speech-Acts)  
11. Speech acts for dialogue agents, accessed May 14, 2026, [https://people.ict.usc.edu/\~traum/cs599f05/vaswani.ppt](https://people.ict.usc.edu/~traum/cs599f05/vaswani.ppt)  
12. J.L. Austin and John Searle on Speech Act Theory | TheCollector, accessed May 14, 2026, [https://www.thecollector.com/speech-act-theory-austin-and-searle/](https://www.thecollector.com/speech-act-theory-austin-and-searle/)  
13. Words That Do: An Introduction to John Searle's Speech Act Theory \- Medium, accessed May 14, 2026, [https://medium.com/@adecressac/words-that-do-an-introduction-to-john-searles-speech-act-theory-fce5af697af6](https://medium.com/@adecressac/words-that-do-an-introduction-to-john-searles-speech-act-theory-fce5af697af6)  
14. 'Austin vs. Searle on locutionary and illocutionary acts': Inquiry: Vol 0, No 0, accessed May 14, 2026, [https://www.tandfonline.com/doi/abs/10.1080/0020174X.2024.2380322](https://www.tandfonline.com/doi/abs/10.1080/0020174X.2024.2380322)  
15. Pragmatic Theories Enhance Understanding of Implied Meanings in LLMs \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.ijcnlp-long.132.pdf](https://aclanthology.org/2025.ijcnlp-long.132.pdf)  
16. The Gricean Maxims in NLP \- A Survey \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2024.inlg-main.39.pdf](https://aclanthology.org/2024.inlg-main.39.pdf)  
17. Speech Acts and Goal Directed Dialogue \- Penn Linguistics, accessed May 14, 2026, [https://www.ling.upenn.edu/courses/Fall\_2001/ling001/dialogue.html](https://www.ling.upenn.edu/courses/Fall_2001/ling001/dialogue.html)  
18. Grice vs Sperber & Wilsons: Comparing Conversational Maxims & Relevance Theory, accessed May 14, 2026, [https://studymoose.com/camparing-the-conversational-maxims-of-grice-with-sperber-and-wilson-s-relevance-theory-essay](https://studymoose.com/camparing-the-conversational-maxims-of-grice-with-sperber-and-wilson-s-relevance-theory-essay)  
19. Explicit-implicit Distinction: A Review of Related Literature \- ERIC, accessed May 14, 2026, [https://files.eric.ed.gov/fulltext/EJ1127545.pdf](https://files.eric.ed.gov/fulltext/EJ1127545.pdf)  
20. The intuitive basis of implicature: Relevance theoretic implicitness versus Gricean implying Author, accessed May 14, 2026, [https://research-repository.griffith.edu.au/bitstreams/1317997c-f728-56b1-973f-8470ed331913/download](https://research-repository.griffith.edu.au/bitstreams/1317997c-f728-56b1-973f-8470ed331913/download)  
21. Relevance Theory, accessed May 14, 2026, [https://www.sfu.ca/\~hedberg/Relevance\_Theory](https://www.sfu.ca/~hedberg/Relevance_Theory)  
22. Overview of Relevance Theory | PDF | Human Communication \- Scribd, accessed May 14, 2026, [https://www.scribd.com/document/861485193/Relevance-Theory-Overview](https://www.scribd.com/document/861485193/Relevance-Theory-Overview)  
23. Relevance Theory \- BU Personal Websites, accessed May 14, 2026, [https://people.bu.edu/bfraser/Relevance%20Theory%20Oriented/Sperber%20&%20Wilson%20-%20RT%20Revisited.pdf](https://people.bu.edu/bfraser/Relevance%20Theory%20Oriented/Sperber%20&%20Wilson%20-%20RT%20Revisited.pdf)  
24. Relevance theory \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Relevance\_theory](https://en.wikipedia.org/wiki/Relevance_theory)  
25. Common Ground in Pragmatics (Stanford Encyclopedia of Philosophy), accessed May 14, 2026, [https://plato.stanford.edu/entries/common-ground-pragmatics/](https://plato.stanford.edu/entries/common-ground-pragmatics/)  
26. Logics of Common Ground \- Semantic Scholar, accessed May 14, 2026, [https://pdfs.semanticscholar.org/1d63/d28806159c5f604073333e71ea91a8b9e2ee.pdf](https://pdfs.semanticscholar.org/1d63/d28806159c5f604073333e71ea91a8b9e2ee.pdf)  
27. 15 Common Ground | CLARK \- Stanford University, accessed May 14, 2026, [https://web.stanford.edu/class/cs379c/class\_messages\_listing/curriculum/Annotated\_Readings/ClarkCOMMON-GROUND-15\_Unannotated.pdf](https://web.stanford.edu/class/cs379c/class_messages_listing/curriculum/Annotated_Readings/ClarkCOMMON-GROUND-15_Unannotated.pdf)  
28. Uncovering the mechanisms of common ground in human–agent interaction: review and future directions for conversational agent research \- Emerald Publishing, accessed May 14, 2026, [https://www.emerald.com/intr/article/36/1/292/1253223/Uncovering-the-mechanisms-of-common-ground-in](https://www.emerald.com/intr/article/36/1/292/1253223/Uncovering-the-mechanisms-of-common-ground-in)  
29. Modular Speaker Architecture: A Framework for Sustaining Responsibility and Contextual Integrity in Multi-Agent AI Communication \- arXiv, accessed May 14, 2026, [https://arxiv.org/pdf/2506.01095](https://arxiv.org/pdf/2506.01095)  
30. Building Common Ground in Dialogue: A Survey \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.luhme-1.2.pdf](https://aclanthology.org/2025.luhme-1.2.pdf)  
31. Crossmodal correspondences as common ground for joint action \- PMC \- NIH, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC7755874/](https://pmc.ncbi.nlm.nih.gov/articles/PMC7755874/)  
32. Lecture 4: Clark, Joint Actions & Common Ground, accessed May 14, 2026, [https://www.cs.brandeis.edu/\~cs111/notes/Lecture.4.clark.jointactions.doc](https://www.cs.brandeis.edu/~cs111/notes/Lecture.4.clark.jointactions.doc)  
33. Seven Ways Your RAG System Could be Failing and How to Fix Them \- Label Studio, accessed May 14, 2026, [https://labelstud.io/blog/seven-ways-your-rag-system-could-be-failing-and-how-to-fix-them/](https://labelstud.io/blog/seven-ways-your-rag-system-could-be-failing-and-how-to-fix-them/)  
34. RAG Failure Mode Checklist | Developer Documentation \- LlamaParse, accessed May 14, 2026, [https://developers.llamaindex.ai/python/framework/optimizing/rag\_failure\_mode\_checklist/](https://developers.llamaindex.ai/python/framework/optimizing/rag_failure_mode_checklist/)  
35. LLMs Struggle to Reject False Presuppositions when Misinformation Stakes are High \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2505.22354v2](https://arxiv.org/html/2505.22354v2)  
36. Can LLMs Ground when they (Don't) Know: A Study on Direct and Loaded Political Questions \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.acl-long.728.pdf](https://aclanthology.org/2025.acl-long.728.pdf)  
37. Presupposition \- Stanford Encyclopedia of Philosophy, accessed May 14, 2026, [https://plato.stanford.edu/entries/presupposition/](https://plato.stanford.edu/entries/presupposition/)  
38. Accommodation and Epistemic Vigilance: A Pragmatic Account of Why LLMs Fail to Challenge Harmful Beliefs \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.04435v1](https://arxiv.org/html/2601.04435v1)  
39. Indexicals (Stanford Encyclopedia of Philosophy/Summer 2010 Edition), accessed May 14, 2026, [https://plato.stanford.edu/archives/sum2010/entries/indexicals/](https://plato.stanford.edu/archives/sum2010/entries/indexicals/)  
40. A pragmatic analyses of the use of types of deixis in poetry and novels of the author Ismail Kadare \- The importance and complexity to the pragmatic process concerning the different realities evoked in social interaction, communication and language \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/281469523\_A\_pragmatic\_analyses\_of\_the\_use\_of\_types\_of\_deixis\_in\_poetry\_and\_novels\_of\_the\_author\_Ismail\_Kadare\_-\_The\_importance\_and\_complexity\_to\_the\_pragmatic\_process\_concerning\_the\_different\_realities\_evoked\_i](https://www.researchgate.net/publication/281469523_A_pragmatic_analyses_of_the_use_of_types_of_deixis_in_poetry_and_novels_of_the_author_Ismail_Kadare_-_The_importance_and_complexity_to_the_pragmatic_process_concerning_the_different_realities_evoked_i)  
41. Indexicals (Stanford Encyclopedia of Philosophy/Fall 2003 Edition), accessed May 14, 2026, [https://plato.stanford.edu/archives/fall2003/entries/indexicals/](https://plato.stanford.edu/archives/fall2003/entries/indexicals/)  
42. Computational Politeness in Natural Language Processing: A Survey \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2407.12814v1](https://arxiv.org/html/2407.12814v1)  
43. Politeness Theory (Pragmatics): Definition & Strategies \- Vaia, accessed May 14, 2026, [https://www.vaia.com/en-us/explanations/english/pragmatics/politeness-theory/](https://www.vaia.com/en-us/explanations/english/pragmatics/politeness-theory/)  
44. Politeness and Psychological Distance: A Construal Level Perspective \- PMC \- NIH, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC3193988/](https://pmc.ncbi.nlm.nih.gov/articles/PMC3193988/)  
45. Your Chunks Failed Your RAG in Production | Towards Data Science, accessed May 14, 2026, [https://towardsdatascience.com/your-chunks-failed-your-rag-in-production/](https://towardsdatascience.com/your-chunks-failed-your-rag-in-production/)  
46. RAG Gone Wrong: The 7 Most Common Mistakes (and How to Avoid Them) \- Kapa.ai, accessed May 14, 2026, [https://www.kapa.ai/blog/rag-gone-wrong-the-7-most-common-mistakes-and-how-to-avoid-them](https://www.kapa.ai/blog/rag-gone-wrong-the-7-most-common-mistakes-and-how-to-avoid-them)  
47. Enhancing RAG with contextual retrieval | Claude Cookbook, accessed May 14, 2026, [https://platform.claude.com/cookbook/capabilities-contextual-embeddings-guide](https://platform.claude.com/cookbook/capabilities-contextual-embeddings-guide)  
48. Towards Reliable Retrieval in RAG Systems for Large Legal Datasets \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2510.06999v1](https://arxiv.org/html/2510.06999v1)  
49. Wrote up the failure modes that kept breaking my RAG system: chunking, stale index, hybrid search, the works : r/deeplearning \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/deeplearning/comments/1t7vuo7/wrote\_up\_the\_failure\_modes\_that\_kept\_breaking\_my/](https://www.reddit.com/r/deeplearning/comments/1t7vuo7/wrote_up_the_failure_modes_that_kept_breaking_my/)  
50. Politeness theory | Social Sciences and Humanities | Research Starters \- EBSCO, accessed May 14, 2026, [https://www.ebsco.com/research-starters/social-sciences-and-humanities/politeness-theory](https://www.ebsco.com/research-starters/social-sciences-and-humanities/politeness-theory)  
51. Politeness theory \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Politeness\_theory](https://en.wikipedia.org/wiki/Politeness_theory)  
52. Discourse Analysis Based on Face-Threatening Theory—A Case Study of Tucaodahui Ⅲ \- David Publishing, accessed May 14, 2026, [https://davidpublisher.com/Public/uploads/Contribute/662f67fd63725.pdf](https://davidpublisher.com/Public/uploads/Contribute/662f67fd63725.pdf)  
53. Comparing human and LLM politeness strategies ... \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.emnlp-main.820.pdf](https://aclanthology.org/2025.emnlp-main.820.pdf)  
54. (PDF) (2024) Revisiting Brown and Levinson's Theory of Politeness \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/383786450\_2024\_Revisiting\_Brown\_and\_Levinson's\_Theory\_of\_Politeness](https://www.researchgate.net/publication/383786450_2024_Revisiting_Brown_and_Levinson's_Theory_of_Politeness)  
55. Revisiting Brown and Levinson's Politeness Theory: A Middle-Eastern Perspective \- Refaad, accessed May 14, 2026, [https://www.refaad.com/Files/BAES/BAES-2-2-3.pdf](https://www.refaad.com/Files/BAES/BAES-2-2-3.pdf)  
56. Conversation Analysis \- Simply Psychology, accessed May 14, 2026, [https://www.simplypsychology.org/conversation-analysis.html](https://www.simplypsychology.org/conversation-analysis.html)  
57. Conversation analysis \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Conversation\_analysis](https://en.wikipedia.org/wiki/Conversation_analysis)  
58. Sequence Organization: Understanding What Drives Talk (Chapter 6\) \- The Cambridge Handbook of Discourse Studies, accessed May 14, 2026, [https://www.cambridge.org/core/books/cambridge-handbook-of-discourse-studies/sequence-organization-understanding-what-drives-talk/99C304161504D8C1B86595C1CB59E070](https://www.cambridge.org/core/books/cambridge-handbook-of-discourse-studies/sequence-organization-understanding-what-drives-talk/99C304161504D8C1B86595C1CB59E070)  
59. Turn Taking in Conversation Analysis | PDF \- Scribd, accessed May 14, 2026, [https://www.scribd.com/document/535427398/IJEI-Vol-2-No-6-2015-6-06](https://www.scribd.com/document/535427398/IJEI-Vol-2-No-6-2015-6-06)  
60. I stopped treating LLM failures as “bad prompting” and started mapping them as structural instability patterns : r/PromptEngineering \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/PromptEngineering/comments/1t8xx0i/i\_stopped\_treating\_llm\_failures\_as\_bad\_prompting/](https://www.reddit.com/r/PromptEngineering/comments/1t8xx0i/i_stopped_treating_llm_failures_as_bad_prompting/)  
61. Repair: The Interface Between Interaction and Cognition \- PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC6849777/](https://pmc.ncbi.nlm.nih.gov/articles/PMC6849777/)  
62. (PDF) The Art of Repair in Human-Agent Conversations: A Taxonomy of Repair Strategies by Users and LLM-Based Conversational Agents \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/395190410\_The\_Art\_of\_Repair\_in\_Human-Agent\_Conversations\_A\_Taxonomy\_of\_Repair\_Strategies\_by\_Users\_and\_LLM-Based\_Conversational\_Agents](https://www.researchgate.net/publication/395190410_The_Art_of_Repair_in_Human-Agent_Conversations_A_Taxonomy_of_Repair_Strategies_by_Users_and_LLM-Based_Conversational_Agents)  
63. PleaSQLarify: Visual Pragmatic Repair for Natural Language Database Querying \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2603.01795v1](https://arxiv.org/html/2603.01795v1)  
64. AIDG: Evaluating Asymmetry Between Information Extraction and Containment in Multi-Turn Dialogue \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/400970574\_AIDG\_Evaluating\_Asymmetry\_Between\_Information\_Extraction\_and\_Containment\_in\_Multi-Turn\_Dialogue](https://www.researchgate.net/publication/400970574_AIDG_Evaluating_Asymmetry_Between_Information_Extraction_and_Containment_in_Multi-Turn_Dialogue)  
65. AIDG: Evaluating Asymmetry Between Information Extraction and Containment in Multi-Turn Dialogue \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2602.17443v1](https://arxiv.org/html/2602.17443v1)  
66. (PDF) CONTEXTUALIZING MEANINGS:PRAGMATIC SHIFTS AND CONTEXTUALIZATION CUES IN DIGITAL COMMUNICATION \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/396708492\_CONTEXTUALIZING\_MEANINGSPRAGMATIC\_SHIFTS\_AND\_CONTEXTUALIZATION\_CUES\_IN\_DIGITAL\_COMMUNICATION](https://www.researchgate.net/publication/396708492_CONTEXTUALIZING_MEANINGSPRAGMATIC_SHIFTS_AND_CONTEXTUALIZATION_CUES_IN_DIGITAL_COMMUNICATION)  
67. How Memes Shape Modern Language and Translation Trends, accessed May 14, 2026, [https://translationexcellence.com/memes-shape-modern-language-and-translation-trends/](https://translationexcellence.com/memes-shape-modern-language-and-translation-trends/)  
68. A Pragmatics Study of Implicature In Internet Memes And Jokes \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/401425810\_A\_Pragmatics\_Study\_of\_Implicature\_In\_Internet\_Memes\_And\_Jokes](https://www.researchgate.net/publication/401425810_A_Pragmatics_Study_of_Implicature_In_Internet_Memes_And_Jokes)  
69. What Does It Meme? English–Spanish Codeswitching and Enregisterment in Virtual Social Space \- MDPI, accessed May 14, 2026, [https://www.mdpi.com/2226-471X/8/4/231](https://www.mdpi.com/2226-471X/8/4/231)  
70. On the recontextualization of meme quiddity: A case study of the TikTok meme \#аясейчасвампокажу | Request PDF \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/392378264\_On\_the\_recontextualization\_of\_meme\_quiddity\_A\_case\_study\_of\_the\_TikTok\_meme\_aasejcasvampokazu](https://www.researchgate.net/publication/392378264_On_the_recontextualization_of_meme_quiddity_A_case_study_of_the_TikTok_meme_aasejcasvampokazu)  
71. (PDF) The pragmatics of sharing memes on Twitter \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/376784088\_The\_pragmatics\_of\_sharing\_memes\_on\_Twitter](https://www.researchgate.net/publication/376784088_The_pragmatics_of_sharing_memes_on_Twitter)  
72. Humor as the Politeness Strategy in Rednote posts among the Digital Refugees, accessed May 14, 2026, [https://rsisinternational.org/journals/ijriss/articles/humor-as-the-politeness-strategy-in-rednote-posts-among-the-digital-refugees/](https://rsisinternational.org/journals/ijriss/articles/humor-as-the-politeness-strategy-in-rednote-posts-among-the-digital-refugees/)  
73. The Meme as the Message: Digital Culture Between Algorithm, Affect, and Aesthetics, accessed May 14, 2026, [https://www.researchgate.net/publication/395611532\_The\_Meme\_as\_the\_Message\_Digital\_Culture\_Between\_Algorithm\_Affect\_and\_Aesthetics](https://www.researchgate.net/publication/395611532_The_Meme_as_the_Message_Digital_Culture_Between_Algorithm_Affect_and_Aesthetics)  
74. The Meme as the Message: Digital Culture Between Algorithm, Affect, and Aesthetics, accessed May 14, 2026, [https://www.routledge.com/The-Meme-as-the-Message-Digital-Culture-Between-Algorithm-Affect-and-Aesthetics/Nowotny-Reidy/p/book/9781032981383](https://www.routledge.com/The-Meme-as-the-Message-Digital-Culture-Between-Algorithm-Affect-and-Aesthetics/Nowotny-Reidy/p/book/9781032981383)  
75. What is Pragmatic AI? \- DealHub, accessed May 14, 2026, [https://dealhub.io/glossary/pragmatic-ai/](https://dealhub.io/glossary/pragmatic-ai/)  
76. Large language models as cognitive shortcuts: a systems-theoretic reframing beyond bullshit \- Frontiers, accessed May 14, 2026, [https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2026.1681525/full](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2026.1681525/full)  
77. Large Language Model Reasoning Failures \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2602.06176v1](https://arxiv.org/html/2602.06176v1)  
78. Disclaimer examples: Templates and best practices for business protection \- ComplyDog, accessed May 14, 2026, [https://complydog.com/blog/example-of-disclaimer](https://complydog.com/blog/example-of-disclaimer)  
79. Language Models in Dialogue: Conversational Maxims for Human-AI Interactions \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2403.15115v1](https://arxiv.org/html/2403.15115v1)  
80. Politeness Strategies in Conversational AI: A Cross-Cultural Pragmatic Analysis of Human-AI Interactions \- IDEAS/RePEc, accessed May 14, 2026, [https://ideas.repec.org/a/dba/pappsa/v3y2025ip1-14.html](https://ideas.repec.org/a/dba/pappsa/v3y2025ip1-14.html)  
81. What's the Difference Between a Privacy Policy, Disclaimer, and Terms & Conditions?, accessed May 14, 2026, [https://termly.io/resources/articles/difference-between-privacy-policy-disclaimer-and-terms-and-conditions/](https://termly.io/resources/articles/difference-between-privacy-policy-disclaimer-and-terms-and-conditions/)  
82. Epistemological Fault Lines Between Human and Artificial Intelligence \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2512.19466v1](https://arxiv.org/html/2512.19466v1)

---

# G. Metaphor, Embodiment & Cognitive Models

The architecture of meaning in human and artificial systems relies upon a layer of cognitive mapping that operates beneath the surface of literal semantics and pragmatic intent. This report, designated as Report G of the Semantic-Semiotic Intelligence canon, identifies and formalizes the structures of embodied experience, metaphorical projection, mental spaces, and analogical transfer that constitute the "cognitive engine" of meaning construction. While Report F established the importance of utterance-in-context and situational force, Report G moves into the cognitive architecture that makes such context-sensitive meaning possible at all. This layer provides the necessary bridge between the sensory-motor interactions of an embodied agent and the highly abstract propositions of formal logic and technical discourse.1

The governing thesis of this analysis posits that cognitive meaning is not a collection of static definitions but an emergent property of cross-domain mappings and embodied simulations. Semantic intelligence achieves cognitive fluency only when it can recognize how one domain (the source) structures another (the target), preserve the internal logic of useful mappings, and critically distinguish between literal mechanisms and metaphorical models. The central investigative question for any intelligence system encountering a complex sign remains: what source domain, embodied schema, or mental model is currently structuring this meaning—and which inferences transfer, which break, and which are being quietly smuggled in?.2

## **The Foundations of Embodied Meaning: Image Schema Theory**

At the bedrock of human cognition lie image schemas—recurrent, dynamic patterns of sensorimotor experience that emerge from our physical interactions with the environment. Introduced by Mark Johnson and George Lakoff, image schemas are neither mental pictures nor abstract propositions; they are preconceptual gestalts that provide the "logic" for higher-level reasoning.1 These schemas are learned in early infancy as spatiotemporal relationships that enable action and structure perception.2

### **The Kantian Heritage and Schematic Structure**

The concept of the schema traces back to Immanuel Kant, who posited it as a mediating representation between sensory percepts and abstract concepts. For Kant, a schema is a structure of the imagination that synthesizes different modes of representation into a coherent judgment.1 Johnson’s "image schema" theory extends this by arguing that abstract reasoning is directly shaped by underlying spatial and force-dynamic patterns derived from bodily movement and object manipulation.1

Image schemas function as "distillers" of spatial and temporal experience. They are characterized by several essential properties: they are emergent from world interaction, they are abstract rather than detailed, and they are dynamic rather than static templates . For example, the CONTAINER schema is not a specific memory of a cup, but the abstract realization of an interior, a boundary, and an exterior that can be applied to a cup, a room, a forest, or a social category .

### **A Taxonomy of Primary Image Schemas**

The logic of our most complex systems is often a projection of a few primary schemas. Semantic intelligence must be able to decompose an utterance or a technical concept into these constituent structures to predict its inferential behavior.

| Schema Group | Primary Schemas | Internal Logic and Inferences |
| :---- | :---- | :---- |
| **Space** | UP-DOWN, FRONT-BACK, LEFT-RIGHT, NEAR-FAR, CENTER-PERIPHERY, CONTACT | Defines orientation and proximity. Verticality often maps to power, mood, and quantity . |
| **Containment** | CONTAINER, IN-OUT, SURFACE, FULL-EMPTY, CONTENT | Governs transitivity (if A is in B and B is in C, A is in C) and the law of the excluded middle . |
| **Locomotion** | PATH, SOURCE-PATH-GOAL, MOMENTUM | Structures time and purpose as linear movement through space. Involves starting points, trajectories, and endpoints . |
| **Force** | COMPULSION, BLOCKAGE, COUNTERFORCE, DIVERSION, REMOVAL OF RESTRAINT, ENABLEMENT, ATTRACTION, RESISTANCE | Structures causality, agency, and social pressure. Derived from the experience of physical barriers and motion . |
| **Unity/Multiplicity** | PART-WHOLE, COUNT-MASS, LINK, COLLECTION, MERGING, SPLITTING | Governs the relationship between entities and their components. LINK structures connection and mutual influence . |
| **Balance** | AXIS BALANCE, TWIN-PAN BALANCE, POINT BALANCE, EQUILIBRIUM | Structures fairness, stability, and ethical compensation. Derived from the experience of bodily stability . |

### **Image Schemas in Abstract Reasoning**

The power of image schemas lies in their ability to provide a "physical logic" to non-physical domains. Johnson demonstrates that the logic of containment is not merely spatial; it informs the way we reason about states of being. If an individual is "deep in a depression," the logic of the CONTAINER schema suggests they are far from the boundary and will take longer to "get out".2 Similarly, the TRANSITIVITY property of the path schema dictates that if one moves from A to B and then B to C, they have moved from A to C—a logic that underpins our understanding of narrative progress and historical development.2

In the context of artificial intelligence and agent design, formalizing these schemas is crucial for grounding reasoning in fundamental conceptual structures.10 A neurosymbolic approach that translates natural language into formal representations of image schemas—such as OBJECT\_INTO\_CONTAINER—enables agents to understand the qualitative relationships in an environment (e.g., "Berlin is in Germany") without requiring exact coordinate geometry.10

## **Conceptual Metaphor as Reasoning Machinery**

Conceptual Metaphor Theory (CMT) asserts that metaphor is not a matter of words but a matter of thought. A conceptual metaphor is a systematic mapping from a concrete source domain (often based on an image schema) to an abstract target domain.12 These mappings are typically unidirectional, moving from the more familiar or sensorimotor to the less familiar or more abstract .

### **The Systematicity of Mapping**

Metaphors are load-bearing structures for everyday and technical inference. They do not merely describe; they prescribe the logical moves available within a discourse. For example, the metaphor ARGUMENT IS WAR dictates that one "defends" a position, "attacks" a weak point, and "wins" a debate. This mapping highlights the competitive nature of discourse while hiding the possibilities for collaborative sense-making.12

| Conceptual Metaphor | Source Domain | Target Domain | Key Inferences and Entailments |
| :---- | :---- | :---- | :---- |
| **LIFE IS A JOURNEY** | Physical Travel | The Life Course | Purposes are destinations; milestones are landmarks; difficulties are obstacles.17 |
| **TIME IS MONEY** | Finance/Resource | Temporal Duration | Time can be spent, wasted, invested, or saved. Implies a limited, quantifiable commodity.12 |
| **KNOWING IS SEEING** | Visual Perception | Intellectual Understanding | "I see what you mean"; "That's a clear explanation." Obscurity implies lack of knowledge.18 |
| **IDEAS ARE OBJECTS** | Physical Entities | Thoughts/Concepts | Ideas can be handed over, broken down, or thrown away. Implies that ideas are discrete and stable.5 |
| **MORE IS UP** | Vertical Scale | Quantity | "Prices are rising"; "High volume." Based on the experience of piles growing higher . |
| **GOOD IS LIGHT** | Visibility/Safety | Moral/Qualitative Value | "A bright future"; "Innocence is white." Darkness maps to danger and secrecy.18 |

### **Highlighting, Hiding, and the Invariance Principle**

A mapping never transfers the entirety of a source domain to a target. It is a selective process. The Invariance Principle states that metaphorical mappings preserve the cognitive topology (the image-schematic structure) of the source domain, provided that it is consistent with the inherent structure of the target domain.2

When we use the metaphor THE MARKET PANICKED, we are projecting the human affective state of PANIC onto a complex economic system.21 This mapping **highlights** the aggregate, volatile behavior of participants and the "contagion" of fear. However, it **hides** the specific causal mechanisms—the high-frequency trading algorithms, the margin calls, and the regulatory triggers—that actually drive the behavior. Treating the metaphor as a literal truth (that the market has a mind) can lead to the "hallucination" of agency where only structural feedback loops exist.21

## **Mental Spaces and Conceptual Integration (Blending)**

While conceptual metaphors provide stable, long-term mappings, human thought often requires more dynamic and creative combinations of domains. Mental Space Theory and Conceptual Blending (Integration) Theory explain how we construct meaning in real-time through the manipulation of "mental spaces"—small, temporary conceptual packets built in working memory during discourse.23

### **The Conceptual Integration Network**

The core of blending is the four-space integration network. This network allows for the creation of "emergent structure" that exists in neither of the original inputs .

1. **Input Space 1 & 2:** These contain the specific scenarios or concepts being blended (e.g., a "computer" and a "desktop") .  
2. **Generic Space:** This captures the common structure shared by both inputs (e.g., a "workspace" with "tools") .  
3. **Blended Space:** This is where integration occurs through selective projection, completion, and elaboration .

In the "computer desktop" blend, we project the *actions* of a physical office (opening a folder, moving a document) onto the *electronic operations* of a machine. The result is a new, emergent category of experience—the GUI—where "clicking" on an icon "opens" a file. This blend is so successful it has become a "dead" or technicalized metaphor .

### **Types of Blending Networks**

* **Simplex Networks:** One input provides an organizing frame (e.g., "Family"), and the other provides specific elements (e.g., "John, Mary, and Paul").27  
* **Mirror Networks:** All spaces share the same organizing frame. The "Buddhist Monk" riddle is a mirror network where two different time-frames of the same path are blended into a single scene.25  
* **Single-Scope Networks:** The two inputs have different frames, but the blend inherits the frame of only one (e.g., "CEO as Captain of a ship") .  
* **Double-Scope Networks:** The inputs have different frames, and the blend inherits structure from both, creating new, highly complex frames—the hallmark of human creativity.25

### **Operations of the Blend: Composition, Completion, and Elaboration**

* **Composition:** Establishing relations between elements projected from the inputs .  
* **Completion:** Bringing in background knowledge and frames to fill out the scene. If we see a "race," we recruitment the frame of competition and its emotions .  
* **Elaboration:** Mentally "running" the blend to see what happens. This simulation allows us to reason about counterfactuals (e.g., "What if Roosevelt were debating Clinton?") .

## **Structure-Mapping Theory and the Logic of Analogy**

Analogy is the cognitive process of mapping a relational system from a familiar base domain to a target domain. Dedre Gentner's Structure-Mapping Theory (SMT) provides the formal constraints for how these mappings are evaluated .

### **The Systematicity Principle**

Humans have a tacit preference for mapping systems of relations governed by higher-order predicates (such as CAUSE, IF-THEN, or PROPORTIONAL) rather than isolated object attributes.4

An analogy is considered strong if it preserves the relational structure. In the analogy "An electric battery is like a reservoir," the objects (electrons vs. water) share almost no attributes. However, the relations (STORE-IN, FLOW-FROM, PROVIDE-POWER) map perfectly.4

### **Constraints on Structural Consistency**

* **One-to-One Mapping:** Each element in the base must map to at most one element in the target .  
* **Parallel Connectivity:** If a relation maps from base to target, its arguments must also map.29  
* **Arity Preservation:** Attributes (one-argument predicates) are often ignored, while relations (two or more arguments) are preserved .

| Comparison Type | Relational Structure | Object Attributes | Example |
| :---- | :---- | :---- | :---- |
| **Analogy** | Mapped | Ignored | "A battery is like a reservoir".4 |
| **Literal Similarity** | Mapped | Mapped | "This lithium battery is like that one" . |
| **Appearance Match** | Ignored | Mapped | "A round battery looks like a coin" . |
| **Abstraction** | Mapped | General/Variables | "A storage device holds potential energy".4 |

### **Analogy as Explanation vs. Analogy as Evidence**

A critical operational distinction is the difference between an analogy used for **explanation** (heuristic) and one used for **evidence** (proof). An explanatory analogy leverages a familiar relational structure to make a new concept understandable.31 However, the analogy itself does not prove that the target domain *is* the base domain. The "candidate inferences" must be checked against existing knowledge of the target domain for factual correctness .

## **Grounded Cognition and the Affective Basis of Abstract Meaning**

Grounded cognition argues that the representation of concepts—including abstract ones—is linked to systems for perception and action .

### **Embodied Simulation and Affective Grounding**

Understanding a sentence about physical motion (e.g., "He threw the ball") activates the motor cortex associated with grasping and throwing . For abstract concepts (e.g., "Justice"), grounding is achieved through:

1. **Metaphorical Mapping:** JUSTICE IS BALANCE.17  
2. **Situated Simulation:** Representing the concept through typical social situations.34  
3. **Affective Grounding:** Grounding the concept in emotional states. Abstract concepts are often more emotionally "loaded" than concrete ones .

### **Affective Orientation and Verticality**

Verticality schemas (UP/DOWN) are deeply mapped to emotional valence—phenomena known as Space-Valence Associations (SVAs) .

* **GOOD IS UP / BAD IS DOWN:** "High spirits," "deep despair" .  
* **POWER IS UP / SUBMISSION IS DOWN:** "High-ranking officials," "bowing down".8  
* **MORE IS UP / LESS IS DOWN:** "High volume," "low numbers".3

## **Applied Domain Analysis: Technical Metaphors**

### **Technical Debt: The Financialization of Code**

"Technical debt" maps FINANCE to SOFTWARE MAINTENANCE.36

| Source Domain: FINANCE | Target Domain: SOFTWARE | Valid Entailment | Breaking Point / Smuggled Inference |
| :---- | :---- | :---- | :---- |
| **Principal** | Shortcuts/cruft in code. | Must be paid back. | Implies debt was always intentional.36 |
| **Interest** | Extra work for new features. | Slows development. | **Break:** Interest only accrues when code is *touched*.36 |
| **Creditor** | Bank or lender. | None. | **Break:** No literal creditor can foreclose . |
| **Leverage** | Debt used to grow faster. | Works if team outpaces interest. | **Risk:** Hits "debt ceiling" if team growth stalls.36 |

The critical "broken entailment" is the trigger of interest. In finance, interest is triggered by the passage of time. In software, if "crufty" code is stable and never modified, it triggers no interest and is effectively not a problem.33

### **Data is Oil: The Extraction Framing**

* **Highlights:** Economic value, refining needs, industrial scale .  
* **Hides:** Human behavior, relationships, and agency .  
* **Smuggles:** Ownership and depletion. Data is **non-rivalrous** (infinite use) and **non-fungible** (context matters) .  
* **Policy Danger:** Leads to "data sovereignty" and localization, ignoring that data's value increases with its flow .

### **AI Memory: Retrieval vs. Reconstruction**

* **Mapping:** Context Window as "Working Memory," Vector Databases as "Long-term Memory".30  
* **Breaking Point:** Human memory is **constructive** and **malleable**; it is updated every time it is accessed.9 AI memory is currently an **archive** that retrieves static documents.40  
* **Smuggled Entailment:** "Learning" often describes merely adding a document. However, "learning" implies behavioral change (modifying weights/policy), which does not happen in standard RAG .

## **AI Performance: Figurative Language and Failure Modes**

### **The "Orphaned Sophistication" Signal**

A reliable signal for AI-generated text is "orphaned sophistication"—the use of high-level figurative language without the structural architecture to "earn" it.32

* **Isolation:** A dense metaphor (e.g., "hungry steel teeth") appears in an otherwise plain passage.32  
* **Lack of Chain Connectivity:** Human writers tend to extend metaphors across sentences, creating a "chain." AI-generated images are often isolated spikes from different figurative worlds.32  
* **No Preparation:** AI drops metaphors "cold," without rhythmic or thematic preparation (e.g., "as though" similes).32

### **Failure Modes in Metaphor Comprehension**

Using datasets like **MUNCH** (Metaphor Understanding Challenge), researchers have highlighted systemic limitations 19:

* **Trigger Word Error:** Inferring mappings based on word co-occurrence (e.g., identifying "The arms race" as COMPETITION IS WAR because "arm" and "war" are frequent neighbors).5  
* **Conceptual Irrelevance:** Models generate 15-25% conceptually irrelevant interpretations (e.g., interpreting "fall in love" literally as "dropping down").7  
* **Syntactic Fragility:** Sensitivity to syntax over structural meaning; simple "syntactic shuffles" can degrade model identification of mappings.5  
* **Ambiguity Resolution:** LLMs struggle to handle metaphorical ambiguity, often committing to a single interpretation rather than seeking clarification.45

### **Benchmarking Analogical Reasoning: AnaloBench and RSA**

The **AnaloBench** framework evaluates an agent's ability to identify abstract analogies across complex narratives.46 While models align with humans at a surface level, they diverge significantly at the representational level, as measured by Representational Similarity Analysis (RSA).44 For example, in RSA tests, humans might judge distances such as: |A \- B| \= 9, |A \- C| \= 13, |B \- C| \= 14\. This indicates a stable relational structure. AI models often fail to mirror this "representational geometry," suggesting they lack the underlying interpretative structure of human thought.10

## **Operational Doctrine: RAG-Ready Artifacts**

### **Metaphorical Entailment Test (MET)**

1. **Identify Domain Pair:** Explicitly name Source and Target Domains.  
2. **Map Primary Structure:** List the core relations being transferred.  
3. **Test the Invariance Principle:** Does the mapping violate the target's inherent structure?  
4. **Identify Smuggled Entailments:** Look for source attributes used to drive inference that are not part of the explicit mapping.  
5. **Agency Audit:** Does the metaphor hide human agents (e.g., "The model hallucinated")?  
6. **Literal Translation:** Force a rewrite into literal, propositional terms.

### **Figurative-Language Failure/Repair Table**

| Detected Failure | Description | Repair Move |
| :---- | :---- | :---- |
| **Literalizing Metaphor** | Treating a metaphorical model as a literal mechanism (e.g., AI "perceives").22 | Unpack the mapping. Name the underlying literal process (e.g., token prediction). |
| **Orphaned Sophistication** | Isolated, unearned metaphors in text.32 | Lower confidence in stylistic integrity. Check for consistency chains. |
| **Trigger Word Error** | Mapping based on word co-occurrence rather than context.5 | Perform a "Syntactic Shuffle." Test if the meaning holds under different phrasing. |
| **Metaphor Laundering** | Using metaphors to obscure responsibility (e.g., "data leak") . | Re-insert agency. Ask: "Who allowed the access?" |

## **What Report G Gives the Canon**

Report G provides the Semantic-Semiotic Intelligence canon with the deep cognitive layer necessary for the disciplined interpretation of non-literal meaning. By moving beneath the surface of signs, it establishes the fundamental sensorimotor and relational logic that governs how humans structure their reality.

Through the formalization of **image schemas**, the canon gains a toolkit for qualitative reasoning more robust than simple geometry. Through **conceptual metaphor**, it tracks the "reasoning machinery" of discourse, distinguishing between useful heuristics and dangerous rhetorical manipulations. Through **mental spaces and blending**, it accounts for the creative dynamism of thought. Through **structure-mapping**, it secures the logic of analogy, ensuring relational transfers are evaluated with rigor.

Finally, by identifying the **failure modes** of AI—such as orphaned sophistication—it allows the canon to audit the cognitive grounding of artificial agents. It transforms metaphor from ornament into a technical model, allowing the omnibus to distinguish between:

* **Metaphorical vs. Literal:** "Is this a mechanism or a model?"  
* **Source vs. Target:** "Which domain provides the logic?"  
* **Valid vs. Invalid Entailment:** "Which inferences are warranted?"  
* **Affective vs. Factual:** "Is this term trying to make me feel something or describe something?"  
* **Dead vs. Active Metaphor:** "Is this mapping still guiding thought?"

Report G prepares the ground for Report H, which moves into the social layer, analyzing how these cognitive mappings are aggregated into shared myths and narratives.

#### **Works cited**

1. (PDF) Image Schemas \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/288562955\_Image\_Schemas](https://www.researchgate.net/publication/288562955_Image_Schemas)  
2. Image schema \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Image\_schema](https://en.wikipedia.org/wiki/Image_schema)  
3. Abstract concepts: Sensory-motor grounding, metaphors, and beyond. | Request PDF, accessed May 14, 2026, [https://www.researchgate.net/publication/224969400\_Abstract\_concepts\_Sensory-motor\_grounding\_metaphors\_and\_beyond](https://www.researchgate.net/publication/224969400_Abstract_concepts_Sensory-motor_grounding_metaphors_and_beyond)  
4. Structure-Mapping: A Theoretical Framework for Analogy\*, accessed May 14, 2026, [http://matt.colorado.edu/teaching/highcog/readings/g83.pdf](http://matt.colorado.edu/teaching/highcog/readings/g83.pdf)  
5. Unveiling LLMs' Metaphorical Understanding: Exploring Conceptual Irrelevance, Context Leveraging and Syntactic Influence \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2510.04120v1](https://arxiv.org/html/2510.04120v1)  
6. (PDF) Image Schemas \- Academia.edu, accessed May 14, 2026, [https://www.academia.edu/357340/Image\_Schemas](https://www.academia.edu/357340/Image_Schemas)  
7. Unveiling LLMs' Metaphorical Understanding: Exploring Conceptual Irrelevance, Context Leveraging and Syntactic Influence | Request PDF \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/396250152\_Unveiling\_LLMs'\_Metaphorical\_Understanding\_Exploring\_Conceptual\_Irrelevance\_Context\_Leveraging\_and\_Syntactic\_Influence](https://www.researchgate.net/publication/396250152_Unveiling_LLMs'_Metaphorical_Understanding_Exploring_Conceptual_Irrelevance_Context_Leveraging_and_Syntactic_Influence)  
8. A Literature Review of the Image Schema Theory and Concepts of Construction, accessed May 14, 2026, [https://www.ijlll.org/vol9/IJLLL-V9N6-467.pdf](https://www.ijlll.org/vol9/IJLLL-V9N6-467.pdf)  
9. A Survey on the Security of Long-Term Memory in LLM Agents: Toward Mnemonic Sovereignty \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2604.16548v1](https://arxiv.org/html/2604.16548v1)  
10. Grounding Agent Reasoning in Image Schemas: A Neurosymbolic Approach to Embodied Cognition \- IFAAMAS, accessed May 14, 2026, [https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2875.pdf](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2875.pdf)  
11. Can LLMs interpret figurative language as humans do?: surface-level vs representational similarity \- arXiv, accessed May 14, 2026, [https://arxiv.org/pdf/2601.09041](https://arxiv.org/pdf/2601.09041)  
12. Conceptual Metaphor Theory | SBL Handbook of Style, accessed May 14, 2026, [https://sblhs2.com/2016/11/24/conceptual-metaphor-theory/](https://sblhs2.com/2016/11/24/conceptual-metaphor-theory/)  
13. Metaphor: bridging embodiment to abstraction \- PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC5033247/](https://pmc.ncbi.nlm.nih.gov/articles/PMC5033247/)  
14. June 29, 2022 Australia's Department of the Prime Minister and Cabinet Andrew Fisher Building 1 National Circuit Barton ACT 2, accessed May 14, 2026, [https://www2.itif.org/2022-australian-national-data-strategy.pdf](https://www2.itif.org/2022-australian-national-data-strategy.pdf)  
15. Not all ANIMALs are equal: metaphorical framing through source domains and semantic frames \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2604.20454v1](https://arxiv.org/html/2604.20454v1)  
16. Loki's Dance of Illusions: A Comprehensive Survey of Hallucination in Large Language Models \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2507.02870v1](https://arxiv.org/html/2507.02870v1)  
17. How to Represent Abstract Concepts? From the Perspective of Conceptual Metaphor Theory, accessed May 14, 2026, [https://openaccesspub.org/human-psychology/article/1516](https://openaccesspub.org/human-psychology/article/1516)  
18. Performances of LLMs in Multimodal Metaphor Understanding, Generation, Consistency and Creativity Based on FDPEF \- Science Publishing Group, accessed May 14, 2026, [https://www.sciencepg.com/article/10.11648/j.ijll.20261402.12](https://www.sciencepg.com/article/10.11648/j.ijll.20261402.12)  
19. Metaphor Understanding Challenge Dataset for LLMs \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2403.11810v1](https://arxiv.org/html/2403.11810v1)  
20. Conceptual Blending \- FunBlocks AI, accessed May 14, 2026, [https://www.funblocks.net/thinking-matters/classic-mental-models/conceptual-blending](https://www.funblocks.net/thinking-matters/classic-mental-models/conceptual-blending)  
21. The Words We Use in Data Policy | Defend Digital Me, accessed May 14, 2026, [https://defenddigitalme.org/research/words-data-policy/](https://defenddigitalme.org/research/words-data-policy/)  
22. Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers) \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/volumes/2025.naacl-long/](https://aclanthology.org/volumes/2025.naacl-long/)  
23. Conceptual blending The goal of this video is to introduce the concept of conceptual blending or conceptual integration. Concept, accessed May 14, 2026, [https://www.hf.uio.no/ilos/english/research/centre/lce/studies/digital-teaching-materials/conceptual-blending-or-conceptual-integration---text---saric-script.pdf](https://www.hf.uio.no/ilos/english/research/centre/lce/studies/digital-teaching-materials/conceptual-blending-or-conceptual-integration---text---saric-script.pdf)  
24. CONCEPTUAL BLENDING, FORM AND MEANING1 1\. Introduction \- TECFA, accessed May 14, 2026, [https://tecfa.unige.ch/tecfa/maltt/cofor-1/textes/Fauconnier-Turner03.pdf](https://tecfa.unige.ch/tecfa/maltt/cofor-1/textes/Fauconnier-Turner03.pdf)  
25. Conceptual Blending \- Neuro Humanities Studies, accessed May 14, 2026, [https://www.neurohumanitiestudies.eu/archivio/blending.pdf](https://www.neurohumanitiestudies.eu/archivio/blending.pdf)  
26. Memory is the next step that AI companies need to solve : r/ArtificialInteligence \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/ArtificialInteligence/comments/1q6w0o6/memory\_is\_the\_next\_step\_that\_ai\_companies\_need\_to/](https://www.reddit.com/r/ArtificialInteligence/comments/1q6w0o6/memory_is_the_next_step_that_ai_companies_need_to/)  
27. Conceptual blending \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Conceptual\_blending](https://en.wikipedia.org/wiki/Conceptual_blending)  
28. Structure-mapping: A computational model of analogy and similarity \- Qualitative Reasoning Group, accessed May 14, 2026, [https://www.qrg.northwestern.edu/ideas/smeidea.htm](https://www.qrg.northwestern.edu/ideas/smeidea.htm)  
29. Structure- Mapping: A Theoretical Framework for Analogy \- DTIC, accessed May 14, 2026, [https://apps.dtic.mil/sti/pdfs/ADA122891.pdf](https://apps.dtic.mil/sti/pdfs/ADA122891.pdf)  
30. Thinking Beyond Tokens: From Brain-Inspired Intelligence to Cognitive Foundations for Artificial General Intelligence and its Societal Impact \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2507.00951v3](https://arxiv.org/html/2507.00951v3)  
31. Structure-mapping theory \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Structure-mapping\_theory](https://en.wikipedia.org/wiki/Structure-mapping_theory)  
32. \[Research\] Orphaned Sophistication — LLMs use figurative language they didn't earn, and that's detectable : r/LanguageTechnology \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/LanguageTechnology/comments/1rc0me1/research\_orphaned\_sophistication\_llms\_use/](https://www.reddit.com/r/LanguageTechnology/comments/1rc0me1/research_orphaned_sophistication_llms_use/)  
33. Structure mapping engine \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Structure\_mapping\_engine](https://en.wikipedia.org/wiki/Structure_mapping_engine)  
34. Boundaries to grounding abstract concepts \- PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC6015828/](https://pmc.ncbi.nlm.nih.gov/articles/PMC6015828/)  
35. Grounding Abstractness: Abstract Concepts and the Activation of the Mouth \- PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC5056183/](https://pmc.ncbi.nlm.nih.gov/articles/PMC5056183/)  
36. Technical Debt \- Martin Fowler, accessed May 14, 2026, [https://martinfowler.com/bliki/TechnicalDebt.html](https://martinfowler.com/bliki/TechnicalDebt.html)  
37. insolvent \- Environment & Society Portal, accessed May 14, 2026, [https://www.environmentandsociety.org/sites/default/files/key\_docs/becker\_2023\_-\_insolvent.pdf](https://www.environmentandsociety.org/sites/default/files/key_docs/becker_2023_-_insolvent.pdf)  
38. Towards an Ethical Digital Society: From Theory to Practice Prof. Anupam Guha Centre for Policy Studies, IITB International Inst, accessed May 14, 2026, [http://digimat.in/nptelpdf/Humanities%20and%20Social%20Sciences/109106184%20-%20NOC-Towards%20an%20Ethical%20Digital%20Society-%20From%20Theory%20to%20Practice/lec7.pdf](http://digimat.in/nptelpdf/Humanities%20and%20Social%20Sciences/109106184%20-%20NOC-Towards%20an%20Ethical%20Digital%20Society-%20From%20Theory%20to%20Practice/lec7.pdf)  
39. Loki's Dance of Illusions: A Comprehensive Survey of Hallucination in Large Language Models \- arXiv, accessed May 14, 2026, [https://arxiv.org/pdf/2507.02870](https://arxiv.org/pdf/2507.02870)  
40. Context Is Not Memory : r/AIMemory \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/AIMemory/comments/1slv3c3/context\_is\_not\_memory/](https://www.reddit.com/r/AIMemory/comments/1slv3c3/context_is_not_memory/)  
41. HiMem: Hierarchical Long-Term Memory for LLM Long-Horizon Agents \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2601.06377v1](https://arxiv.org/html/2601.06377v1)  
42. \[2510.04120\] Unveiling LLMs' Metaphorical Understanding: Exploring Conceptual Irrelevance, Context Leveraging and Syntactic Influence \- arXiv, accessed May 14, 2026, [https://arxiv.org/abs/2510.04120](https://arxiv.org/abs/2510.04120)  
43. Metaphor Understanding Challenge Dataset for LLMs \- OpenReview, accessed May 14, 2026, [https://openreview.net/pdf/10ff01b597e285d57788c3247e58751a918363e3.pdf](https://openreview.net/pdf/10ff01b597e285d57788c3247e58751a918363e3.pdf)  
44. Can LLMs interpret figurative language as humans do?: surface-level vs representational similarity \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/399776907\_Can\_LLMs\_interpret\_figurative\_language\_as\_humans\_do\_surface-level\_vs\_representational\_similarity](https://www.researchgate.net/publication/399776907_Can_LLMs_interpret_figurative_language_as_humans_do_surface-level_vs_representational_similarity)  
45. Daily Papers \- Hugging Face, accessed May 14, 2026, [https://huggingface.co/papers?q=referential%20ambiguity](https://huggingface.co/papers?q=referential+ambiguity)  
46. AnaloBench: Benchmarking the Identification of Abstract and Long-context Analogies \- arXiv, accessed May 14, 2026, [https://arxiv.org/abs/2402.12370](https://arxiv.org/abs/2402.12370)

---

# H. Discourse, Narrative & Social Reality

The movement of meaning from the localized pragmatic inference of an utterance to the systemic architecture of a social reality represents the final scaling operation within Volume II of the Semantic-Semiotic Intelligence canon. While Report F identified the utterance-in-context as the primary unit of live meaning and Report G mapped the cognitive layers of metaphor and embodiment that ground such meaning, Report H identifies the overarching structures that stabilize these elements into durable social worlds. Discourse is not merely a collection of texts or a string of utterances; it is a regulatory system of meaning that defines the boundaries of the sayable, the thinkable, and the authoritative within specific historical and institutional contexts.1 Narrative serves as the fundamental cognitive and linguistic machinery for organizing scattered events into intelligible sequences that distribute agency and establish moral order.4 Ideology provides the values that naturalize power relations, while institutional language functions as the performative engine that creates social facts out of collective intentionality.6 Social reality, therefore, is an emergent property of these coordinated patterns—real in its consequences even when its foundations are entirely symbolic.9

The governing thesis of this report is that discourse is patterned meaning across texts, turns, institutions, communities, and publics. Narrative organizes events into intelligible sequences; ideology stabilizes values and power relations; institutional language authorizes roles and actions; framing selects what counts as relevant; and social reality emerges when these patterns become shared, repeated, enforced, and acted upon. Semantic intelligence becomes socially literate when it can identify not only what a text says, but what world it helps build. The analysis orbits a central diagnostic question: what discourse, narrative, frame, institution, identity position, legitimacy strategy, or social reality is this language participating in—and what does that participation make possible, natural, authoritative, or invisible?

## **The Architecture of Discourse and Discursive Formations**

Discourse is analyzed not simply as a linguistic unit larger than the sentence, but as a system of representation that governs the production of knowledge within a given society.2 In the Foucauldian tradition, discourse constructs the very objects of which it speaks; concepts like "madness," "crime," or "sexuality" do not exist as stable natural essences but are produced through the medical, legal, and psychiatric discourses that define, categorize, and regulate them.2 A discursive formation is a cluster of related statements, institutions, and practices that share a common "regime of truth"—the rules that distinguish true from false and attach specific effects of power to the true .

### **Power, Knowledge, and Subject Formation**

Power in discourse is not solely repressive, exclusionary, or centralized in a sovereign entity; it is a pervasive, productive force that generates reality and domains of objects . This "power/knowledge" operates through disciplinary surveillance and normalization, where individuals internalize discursive norms to become self-regulating subjects.13 Within religious discourse, for example, disciplinary power functions by embedding subtle control techniques in daily rituals and teachings, encouraging believers to align their conduct with communal expectations of the "good practitioner".15 In modern institutional settings, this manifests as "governmentality," where neoliberal regimes of truth emphasize personal responsibility and self-management, urging citizens to become "self-enterprising individuals" who believe themselves to be free while being governed by market-based truths .

| Concept | Definition | Function in Semantic Intelligence |
| :---- | :---- | :---- |
| Discursive Formation | A system of statements that share a common logic, authority, and object of focus.1 | Identifies the systemic boundaries of a text's "world." |
| Regime of Truth | The rules according to which true and false are separated and sanctioned.3 | Evaluates the authority and validation criteria of a source. |
| Subject Position | The social and discursive role assigned to an actor within a discourse.2 | Determines the permitted agency and perspective of a speaker. |
| Normalization | The process by which discursive norms are internalized as common sense.18 | Detects when a text presents a contested value as a natural fact. |

### **Critical Discourse Analysis: Text, Practice, and Social Context**

Critical Discourse Analysis (CDA) bridges the gap between the micro-linguistic features of a text and the macro-structures of society.8 Norman Fairclough’s three-dimensional model provides the operational framework for this synthesis: textual analysis (description of linguistic features), discourse practice (interpretation of how texts are produced and consumed), and social practice (explanation of the relationship between interaction and social context).8

Teun van Dijk adds a socio-cognitive layer to this model, arguing that discourse and society are linked through mental models and shared social representations.8 Ideologies are viewed as "belief systems" shared by specific social groups to coordinate their activities and goals.24 These ideologies are often hidden in "common sense" assumptions that naturalize inequality or marginalize dissenting voices.25 Ruth Wodak’s discourse-historical approach further contextualizes these patterns by tracing how meanings and legitimation strategies evolve over time and across different fields.8

## **Narrative Logic and the Machinery of Emplotment**

Narrative is the primary interpretative tool through which individuals and communities imbue experience with significance.5 It is fundamentally distinct from logical-scientific explanation; while logic seeks universal causes and empirical verification, narrative seeks verisimilitude (lifelikeness) and "narrative necessity".5

### **Ricoeur and the Synthesis of the Heterogeneous**

Paul Ricoeur’s concept of "emplotment" (mimesis 2\) is the "integrating dynamism" that transforms a variety of incidents into a unified story.4 Emplotment is a configurational act that "grasps together" multiple, scattered events—including goals, means, chance encounters, and unintended consequences—into an intelligible whole.4 Nothing is considered an "event" in this framework unless it contributes to the progress of the overall story.4 Through "productive imagination," emplotment creates "semantic innovation," allowing a narrator to schematize meaning from unrelated occurrences . For example, in a political narrative, a single economic data point might be transformed from a "physical occurrence" into a "causal link" in a story of national decline or recovery.4 This process imposes a "moral order" on time, where the resolution of the plot provides the "reason" for the initial events .

### **Labov and the Structural Anatomy of Personal Experience**

William Labov identified the specific linguistic techniques used to report past events in oral narratives of personal experience.34 A well-formed narrative typically follows a predictable structure: an abstract (summary), orientation (who, when, where), complicating action (the events leading to a climax), evaluation (the narrator’s commentary on significance), resolution (the outcome), and coda (return to the present).34 The "temporal juncture" is the core unit of narrative; it consists of two clauses where reversing the order would change the interpretation of the event sequence.34 This formal requirement separates a narrative from a list of facts or a "pseudo-narrative" like a recipe.36 Causal connections are reconstructed by the listener based on the narrator's "folk theory" of causality, which inevitably assigns praise or blame to the actors involved.35

### **Bruner: The Narrative Construction of Reality**

Jerome Bruner argues that we organize our memory of human happenings almost entirely in narrative form.5 Narratives function through "particularity"—they use specific tokens to represent broader types (e.g., a "cautionary tale" of a specific failure representing the general risk of hubris).5 A key feature of narrative is "hermeneutic composability": the meaning of the whole story depends on its parts, and the parts depend on the whole.5 This recursive interpretation allows narratives to create "social realities" that coordinate action across groups, even when they lack empirical proof.5

| Distinction | Logical-Scientific Domain | Narrative Domain |
| :---- | :---- | :---- |
| Verification | Empirical Truth and Falsification.5 | Verisimilitude and Resonance.5 |
| Logic | Causal Prediction.5 | Intentional Interpretation.5 |
| Focus | Universality and General Laws.5 | Particularity and Context.5 |
| Meaning | Non-contradiction.5 | Hermeneutic Composability.5 |
| Goal | Explanation of the Physical World.5 | Construction of the Social World.5 |

## **The Architecture of Social Reality and Institutional Facts**

Social constructionism posits that the "reality" shared by members of a society is a product of human interaction rather than natural laws . This reality is "real in its consequences" because people behave as if it were objective, thereby giving it coercive force over individuals .

### **Berger and Luckmann: The Dialectic of Society**

Peter Berger and Thomas Luckmann describe a three-step process through which subjective meanings become "objective facticities" 6: externalization (individuals produce social order through behavior), objectivation (human products like roles and categories are experienced as external facts), and internalization (the objective world is re-absorbed into individual consciousness through socialization) . Institutionalization begins with "reciprocal typification"—the habitualization of actions by types of actors . These institutions provide "routines" that reduce uncertainty, allowing human attention to focus on innovation while predicting the behavior of others . Legitimation is a "second-order objectivation" that explains and justifies these institutions to new generations .

### **Searle: Institutional Facts and Deontic Power**

John Searle provides the logical formula for institutional reality: "X counts as Y in C".7 Here, X is a "brute fact" (e.g., a piece of paper), Y is an institutional fact (e.g., a five-dollar bill), and C is the specific context or "circumstances" of the declaration.7 Institutional facts are "deontic"—they carry obligations, rights, and responsibilities.7 A person "counting as" a spouse or a "candidate who has a majority of votes" counting as a president-elect creates a reality that exists only as long as it is collectively recognized.7 Performative utterances, such as "I name this ship the Queen Elizabeth" or "I promise to meet you," are the linguistic engines that make these facts the case; they do not describe reality, they change it.7

### **Bourdieu: Symbolic Power and Habitus**

Pierre Bourdieu argues that the power of language is not inherent in words but in the "socially delegated authority" of the speaker and the "habitus" (internalized dispositions) of the audience.12 Habitus is the "feel for the game" that allows agents to understand "what is to be done" without following explicit rules, while a "field" is the social space where actors compete for "symbolic capital".40 Symbolic power is the power to impose a vision of the world, making social classifications appear natural and unquestionable . In clinical interactions, for example, a migrant nurse uses specific speech acts to perform their "habitus" and negotiate professional authority within the healthcare field.40

## **Framing, Salience, and Legitimacy Strategies**

Framing is the process by which a communicator selects some aspects of a perceived reality and makes them more "salient" to define a problem, diagnose causes, and suggest solutions .

### **Goffman and Entman: The Organization of Experience**

Erving Goffman defines frames as "schemata of interpretation" that allow individuals to "locate, perceive, identify, and label" events . Framing works like a picture frame, excluding most information while focusing attention on specific elements . Media framing shapes public perception by highlighting certain words and images to evoke emotional reactions and reinforce specific narratives . Interlocutors may shift their "footing" (stance or alignment) to signal their role or relationship to their own utterances.42 Nixon shifting from a "presidential frame" to a "personal comment" on a journalist's outfit is a classic example of a footing change.42

### **Van Leeuwen: The Grammar of Legitimation**

Legitimation strategies answer the question "why should we do this?" and are essential for stabilizing institutional practices.44

| Strategy | Description | Key Mechanism |
| :---- | :---- | :---- |
| Authorization | Legitimacy based on tradition, laws, or experts.44 | "Because someone says so." |
| Moral Evaluation | Legitimacy grounded in values, adjectives, or analogies.45 | "Because it is right/good." |
| Rationalization | Legitimacy based on utility, effectiveness, or natural order.45 | "Because it works/is natural." |
| Mythopoesis | Legitimacy through storytelling (moral or cautionary tales).45 | "Once upon a time..." |

### **Legitimacy Laundering and Information Disruption**

"Legitimacy laundering" is a strategic discursive practice where state-aligned narratives are embedded within ostensibly neutral reporting to gain credibility . In Turkey's global media strategy, platforms like "Clash Report" present themselves as independent news aggregators while advancing Ankara’s foreign policy goals . By hiring professional editors and operating in a "gray zone," these platforms evade the skepticism typically directed at state-run media . Similarly, "procedural justice" can be used as a legitimation strategy where the appearance of a "polite cop" creates a false sense of legitimacy divorced from actual lawfulness or objective morality.11

## **Dialogism, Heteroglossia, and Intertextuality**

Mikhail Bakhtin’s theory of "dialogism" posits that all language and meaning are inherently relational and interactive.19 Every utterance is a "response" to prior utterances and an "anticipation" of future ones.19

### **Heteroglossia: The Multiplicity of Voices**

"Heteroglossia" refers to the diversity of social dialects, professional jargons, and generational styles within a single language.19 "Centripetal forces" seek to centralize and unify language (official languages), while "centrifugal forces" drive language to diversify through everyday social interaction.18 The novel is the primary genre that celebrates heteroglossia, incorporating multiple unmerged voices (polyphony) that disrupt any single authoritative viewpoint.49

### **Intertextuality and Addressivity**

All discourse is in dialogue with prior discourse on the same subject.49 Julia Kristeva adapted this into "intertextuality," where a text is seen as a "woven fabric" of other textual structures.49 "Addressivity" is the quality of an utterance being directed toward a specific audience, which shapes its very form and meaning.19 In cross-cultural encounters, these dialogic engagements are often fraught with fear and unpredictability, as the subject is always "in process" through their interaction with the Other.29

## **Computational Discourse Intelligence and Platform Norms**

Modern computational linguistics, particularly in the era of Large Language Models (LLMs), has shifted from task-specific classifiers to reasoning-oriented paradigms like stance detection and argument mining.46

### **Stance Detection and Argument Mining**

Stance detection identifies a text’s attitude toward a target, while argument mining extracts formal structures like claims and premises.56 LLMs enable zero-shot stance detection and the generation of "rationales" to guide reasoning.46 To mitigate hallucinations—plausible but factually incorrect outputs—new frameworks like "MPVStance" integrate multi-perspective verification with Retrieval-Augmented Generation (RAG).20 AI agents are now being designed to engage in "dialectical processes" with humans, where decisions are contestable and revisable.8

### **Platform Norms and Discourse Evolution**

Discourse patterns are strongly mediated by "platform affordances" .

* **Reddit**: Characterized by a "meta-discussion" format and "karma" points that de-emphasize individual identity in favor of the discourse itself.60 Connections are "content-based" within subreddits .  
* **Twitter/X**: Based on "profile-based" connections (follows, mentions), leading to faster information diffusion and more "episodic" engagement .  
* **Emerging Risks**: In post-AGI governance, "salience capture" occurs when emotionally intense, short-horizon issues displacement long-horizon structural problems, leading to institutional "policy myopia".63

## **Failure Modes and Operational Doctrine**

Socially literate semantic intelligence must navigate significant failure modes to avoid both "false neutrality" and "suspicion theater" .

### **Common Failure Modes and Repair Moves**

| Failure Mode | Description | Repair Move |
| :---- | :---- | :---- |
| Genre Collapse | Treating a performative institutional document (e.g., a policy) as a neutral description of facts. | Identify the genre's goal (authorization, liability limitation). |
| Official-Language Overtrust | Mistaking the "regime of truth" of a dominant institution for an absolute, universal truth. | Name the legitimacy strategy and check the warrant. |
| Narrative Overfitting | Imposing a moral story on random events, mistaking coincidence for conspiracy. | Apply Labovian structure to check for temporal junctures and evidence. |
| Identity Essentialism | Treating a discursively constructed category (e.g., "at-risk youth") as a natural essence. | Map the subject position and institutional history. |
| Legitimacy Laundering | Failing to see how state narratives are embedded in independent sources.63 | Trace financial and institutional ties. |

### **Before/After: Naive vs. Discourse-Disciplined Interpretation**

| Text Fragment | Naive Interpretation | Discourse-Disciplined Interpretation |
| :---- | :---- | :---- |
| "The market demands efficiency." | An empirical economic fact. | Reified economic narrative using rationalization to legitimize austerity.45 |
| "At-risk youth are a priority." | A neutral, helpful description. | Institutional category that justifies surveillance and management.65 |
| "This is for your safety." | A benign statement of intent. | Legitimacy strategy (Moralization) requiring specific evidential warrant.45 |
| "The community has spoken." | A report on a public consensus. | Authority claim using Custom legitimation to manufacture consensus.45 |
| "AI Copilot enhances work." | A technical description of a tool. | Product narrative and liability-shaping metaphor backgrounding risks.64 |

## **Compact Discourse-Analysis Artifacts**

For robust document interpretation, semantic intelligence must treat sources as discourse artifacts.

### **Discourse Context Record**

Identifies the "regime of truth" and "order of discourse" a text participates in, noting the institutional origin and target audience.

### **Narrative Frame Map**

Deconstructs the "emplotment" of events, identifying actors, motives, and moral resolutions. Tracks whether a timeline contains necessary "temporal junctures".34

### **Positioning Map**

Tracks the speaker’s "footing" and the "subject positions" assigned to the audience, identifying shifts in stance or authority.43

### **Legitimation Strategy Profile**

Catalogs the use of Authorization, Moral Evaluation, Rationalization, and Mythopoesis to justify actions or beliefs.45

### **Institutional Language Record**

Identifies "institutional facts" and the "deontic powers" (obligations, rights) they create using the "X counts as Y in C" logic.7

## **Conflict Mapping: Resolving Theoretical Disagreements**

The field of discourse and social reality contains inherent tensions regarding power, agency, and method.

* **CDA vs. Conversation Analysis (CA)**: CDA has been accused of "ideological a priori"—seeing power where it expects to find it—while CA is criticized for ignoring the broader structural context by focusing only on the "minutiae of interaction" .  
* **Intentionality vs. Structure**: Pragmatic theories (Searle, Grice) emphasize "rational intentionality," while sociologists (Bourdieu, Foucault) emphasize "intersubjective interactionism" and structural constraints.12  
* **Subjectivity vs. Objectivity**: Bakhtin views the subject as "dialogical"—a "we" containing many voices—while traditional linguistics often treats the speaker as a unified, isolated entity.49

Unresolved evidence in a specific text should be addressed by mapping these disagreements: does the evidence support a "consensus view" of a social contract (Searle) or a "conflict view" of symbolic violence (Bourdieu)?.67

## **Annotated Bibliography**

* **Berger, P. L., & Luckmann, T. (1966). The Social Construction of Reality.** The seminal work on how social order is created through externalization, objectivation, and internalization .  
* **Bruner, J. (1991). The Narrative Construction of Reality.** Establishes narrative as a cognitive domain distinct from logical-scientific thought, focusing on particularity and verisimilitude .  
* **Fairclough, N. (1995). Critical Discourse Analysis: The Critical Study of Language.** Provides the three-dimensional framework (text, discourse practice, social practice) for analyzing language and power.8  
* **Foucault, M. (1972). The Archaeology of Knowledge.** Defines discourse as a regulatory system of statements that produces the objects of which it speaks .  
* **Labov, W. (1997). Some Further Steps in Narrative Analysis.** Formalizes the structural components of oral narrative and the role of temporal junctures.34  
* **Ricoeur, P. (1984-1988). Time and Narrative.** Develops the theory of emplotment as a configurational act that creates intelligibility from scattered events .  
* **Searle, J. R. (1995). The Construction of Social Reality.** Formulates the logic of institutional facts (X counts as Y in C) and deontic power.7  
* **Van Leeuwen, T. (2008). Discourse and Practice: New Tools for Critical Discourse Analysis.** Categorizes the four main strategies of legitimation: Authorization, Moral Evaluation, Rationalization, and Mythopoesis.45

## **What Report H Gives the Canon**

Report H provides the **social-meaning layer** to the Semantic-Semiotic Intelligence canon. While Report F identified the pragmatic force of an utterance and Report G identified the cognitive metaphors beneath it, Report H establishes how these forces and models scale into the social architecture of the world. By mastering Report H, the canon is now able to distinguish:

* "This document is a policy genre, not neutral exposition."  
* "This narrative assigns agency to individuals while backgrounding structure."  
* "This source positions users as risks to be managed."  
* "This phrase legitimates action through safety and necessity."  
* "This institutional label creates obligations, not merely descriptions."  
* "This brand language performs identity alignment, not empirical proof."  
* "This discourse treats a contested value as common sense."  
* "This social category is consequential without being a natural-kind essence."

Report H transforms semantic analysis from a search for "meaning" into an investigation of "social literacy." It enables an intelligence to track how repeated language patterns become shared narratives, identity positions, legitimacy structures, and public realities. This report prepares the canon for Volume III, which will explore the deeper symbolic, ritualistic, and memetic behaviors of collective humanity.

#### **Works cited**

1. Theoretical Foundations of Discourse Analysis Simplified, accessed May 14, 2026, [https://discourseanalyzer.com/theoretical-foundations-of-discourse-analysis-simplified/](https://discourseanalyzer.com/theoretical-foundations-of-discourse-analysis-simplified/)  
2. READING SEVEN \- Foucault: Power, Knowledge and \- Discourse, accessed May 14, 2026, [https://www.miguelangelmartinez.net/IMG/pdf/1997\_hall\_foucault-power-knowledge-and-discourse\_ch7.pdf](https://www.miguelangelmartinez.net/IMG/pdf/1997_hall_foucault-power-knowledge-and-discourse_ch7.pdf)  
3. Discourse, Power and Truth: Foucauldian Perspective \- International Journal of English Literature and Social Sciences (IJELS), accessed May 14, 2026, [https://ijels.com/upload\_document/issue\_files/13IJELS-108202023-Discourse.pdf](https://ijels.com/upload_document/issue_files/13IJELS-108202023-Discourse.pdf)  
4. Ricoeur's narrative theory applied to science \- Academic Journals, accessed May 14, 2026, [https://academicjournals.org/article/article1379171579\_Ivic.pdf](https://academicjournals.org/article/article1379171579_Ivic.pdf)  
5. The Narrative Construction of Reality, accessed May 14, 2026, [https://web.english.upenn.edu/\~cavitch/pdf-library/Bruner\_Narrative.pdf](https://web.english.upenn.edu/~cavitch/pdf-library/Bruner_Narrative.pdf)  
6. The Social Construction of Power: Reflections Beyond Berger/Luckmann and Bourdieu \- SciSpace, accessed May 14, 2026, [https://scispace.com/pdf/the-social-construction-of-power-reflections-beyond-berger-1ywfku475i.pdf](https://scispace.com/pdf/the-social-construction-of-power-reflections-beyond-berger-1ywfku475i.pdf)  
7. Institutional Facts: John R. Searle \- The Philosophy Forum Archive, accessed May 14, 2026, [https://thephilosophyforum.com/discussion/12849/institutional-facts-john-r-searle](https://thephilosophyforum.com/discussion/12849/institutional-facts-john-r-searle)  
8. Critical discourse analysis \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Critical\_discourse\_analysis](https://en.wikipedia.org/wiki/Critical_discourse_analysis)  
9. Social Construction of Reality \- Simply Psychology, accessed May 14, 2026, [https://www.simplypsychology.org/social-construction-of-reality.html](https://www.simplypsychology.org/social-construction-of-reality.html)  
10. The Social Construction of Reality \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/The\_Social\_Construction\_of\_Reality](https://en.wikipedia.org/wiki/The_Social_Construction_of_Reality)  
11. Social Construction of Reality | Religion and Philosophy | Research Starters \- EBSCO, accessed May 14, 2026, [https://www.ebsco.com/research-starters/religion-and-philosophy/social-construction-reality](https://www.ebsco.com/research-starters/religion-and-philosophy/social-construction-reality)  
12. Language/activity : Observing and interpreting ritualistic institutional discourse, accessed May 14, 2026, [https://www.unige.ch/clf/fichiers/pdf/07-Sarangi\_nclf26.pdf](https://www.unige.ch/clf/fichiers/pdf/07-Sarangi_nclf26.pdf)  
13. Ideology and Discourse, accessed May 14, 2026, [https://discourses.org/wp-content/uploads/2022/07/Teun-A.-van-Dijk-2013-Ideology-and-discourse.pdf](https://discourses.org/wp-content/uploads/2022/07/Teun-A.-van-Dijk-2013-Ideology-and-discourse.pdf)  
14. Understanding Bakhtin's Dialogism | PDF \- Scribd, accessed May 14, 2026, [https://www.scribd.com/document/654759147/dialogism-and-heteroglossia](https://www.scribd.com/document/654759147/dialogism-and-heteroglossia)  
15. Frame analysis | Social Theory & Interactionism \- Britannica, accessed May 14, 2026, [https://www.britannica.com/topic/frame-analysis](https://www.britannica.com/topic/frame-analysis)  
16. Foucault: power is everywhere \- Powercube.net, accessed May 14, 2026, [https://www.powercube.net/other-forms-of-power/foucault-power-is-everywhere/](https://www.powercube.net/other-forms-of-power/foucault-power-is-everywhere/)  
17. Ressentiment, Victimhood, and Revanchism: Unpacking Erdoğan's Populist Mastery, accessed May 14, 2026, [https://econtent.hogrefe.com/doi/10.1024/2673-8627/a000098](https://econtent.hogrefe.com/doi/10.1024/2673-8627/a000098)  
18. Can someone explain Foucault's concept of power-knowledge to me (with examples)? : r/askphilosophy \- Reddit, accessed May 14, 2026, [https://www.reddit.com/r/askphilosophy/comments/arpgzt/can\_someone\_explain\_foucaults\_concept\_of/](https://www.reddit.com/r/askphilosophy/comments/arpgzt/can_someone_explain_foucaults_concept_of/)  
19. Scholars in Discourse Analysis \- Amazon S3, accessed May 14, 2026, [https://s3-eu-west-1.amazonaws.com/s3-euw1-ap-pe-ws4-cws-documents.ri-prod/9781032880389/Discourse-Scholars.pdf](https://s3-eu-west-1.amazonaws.com/s3-euw1-ap-pe-ws4-cws-documents.ri-prod/9781032880389/Discourse-Scholars.pdf)  
20. Critical discourse analysis (CDA) | Language and Linguistics | Research Starters \- EBSCO, accessed May 14, 2026, [https://www.ebsco.com/research-starters/language-and-linguistics/critical-discourse-analysis-cda](https://www.ebsco.com/research-starters/language-and-linguistics/critical-discourse-analysis-cda)  
21. Critical Discourse Analysis | CDA, accessed May 14, 2026, [https://sharifling.wordpress.com/wp-content/uploads/2015/09/lect-09\_critical-discourse-analysis.pdf](https://sharifling.wordpress.com/wp-content/uploads/2015/09/lect-09_critical-discourse-analysis.pdf)  
22. The Birth of Society from Symbolic Violence. \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/323993104\_The\_Birth\_of\_Society\_from\_Symbolic\_Violence](https://www.researchgate.net/publication/323993104_The_Birth_of_Society_from_Symbolic_Violence)  
23. Foucault's CDA in Religious Discourse | PDF \- Scribd, accessed May 14, 2026, [https://www.scribd.com/document/906355510/CDA-Frameworks-Fairclough-VanDijk-Foucault](https://www.scribd.com/document/906355510/CDA-Frameworks-Fairclough-VanDijk-Foucault)  
24. Framing Theory | Social Sciences and Humanities | Research Starters \- EBSCO, accessed May 14, 2026, [https://www.ebsco.com/research-starters/social-sciences-and-humanities/framing-theory](https://www.ebsco.com/research-starters/social-sciences-and-humanities/framing-theory)  
25. Critical Discourse Analysis in The Age of Social Media: A Conceptual Exploration, accessed May 14, 2026, [https://mahasiswaindonesia.id/critical-discourse-analysis-in-the-age-of-social-media-a-conceptual-exploration/](https://mahasiswaindonesia.id/critical-discourse-analysis-in-the-age-of-social-media-a-conceptual-exploration/)  
26. Critical Discourse Analysis: History, Agenda, Theory, and Methodology1, accessed May 14, 2026, [https://miguelangelmartinez.net/IMG/pdf/2008\_Wodak\_Critical\_Discourse\_Analysis\_Ch\_01.pdf](https://miguelangelmartinez.net/IMG/pdf/2008_Wodak_Critical_Discourse_Analysis_Ch_01.pdf)  
27. practice \- Jump Cut, accessed May 14, 2026, [https://www.ejumpcut.org/currentissue/LesageLastWord/ClaudeAI-1.html](https://www.ejumpcut.org/currentissue/LesageLastWord/ClaudeAI-1.html)  
28. Narrative Approach and Mentalization \- PMC \- NIH, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10740439/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10740439/)  
29. 1 When we select words… We usually take them from other utterances, and mainly from utterances that are kindred to ours in gen \- Research Commons, accessed May 14, 2026, [https://researchcommons.waikato.ac.nz/bitstreams/ce0659b4-7926-436f-bec5-74add236a765/download](https://researchcommons.waikato.ac.nz/bitstreams/ce0659b4-7926-436f-bec5-74add236a765/download)  
30. Authority and Power in Social Interaction; Methods and ... \- R \-libre, accessed May 14, 2026, [https://r-libre.teluq.ca/1738/1/9781351051668\_preview.pdf](https://r-libre.teluq.ca/1738/1/9781351051668_preview.pdf)  
31. time amd narrative \- paul ricoeur, accessed May 14, 2026, [https://www.nu.edu.ye/wp-content/uploads/2014/05/Paul-Ricoeur-Time-and-Narrative-vol1.pdf](https://www.nu.edu.ye/wp-content/uploads/2014/05/Paul-Ricoeur-Time-and-Narrative-vol1.pdf)  
32. Time and Narrative, Volume 1 \- EleQta, accessed May 14, 2026, [http://www.eleqta.org/documentation/en/Paul\_Ricoeur\_Time\_and\_Narrative.pdf](http://www.eleqta.org/documentation/en/Paul_Ricoeur_Time_and_Narrative.pdf)  
33. At the Limits of the Narrative \- Ricoeur Studies, accessed May 14, 2026, [https://ricoeur.pitt.edu/ojs/ricoeur/article/view/578/339](https://ricoeur.pitt.edu/ojs/ricoeur/article/view/578/339)  
34. Some Further Steps in Narrative Analysis \- Penn Linguistics, accessed May 14, 2026, [https://www.ling.upenn.edu/\~wlabov/sfs.html](https://www.ling.upenn.edu/~wlabov/sfs.html)  
35. Reconstructing the Social Construction of Reality \- PMC \- NIH, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12163552/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12163552/)  
36. (PDF) The Endless Fields of Pierre Bourdieu \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/247747332\_The\_Endless\_Fields\_of\_Pierre\_Bourdieu](https://www.researchgate.net/publication/247747332_The_Endless_Fields_of_Pierre_Bourdieu)  
37. The Procedural Justice Industrial Complex \- Digital Repository @ Maurer Law, accessed May 14, 2026, [https://www.repository.law.indiana.edu/context/ilj/article/11526/viewcontent/The\_Procedural\_Justice\_Industrial\_Complex.pdf](https://www.repository.law.indiana.edu/context/ilj/article/11526/viewcontent/The_Procedural_Justice_Industrial_Complex.pdf)  
38. Translingual Rhetoric \- CUNY Academic Works, accessed May 14, 2026, [https://academicworks.cuny.edu/cgi/viewcontent.cgi?article=4512\&context=gc\_etds](https://academicworks.cuny.edu/cgi/viewcontent.cgi?article=4512&context=gc_etds)  
39. Sociology and the Power of (Ordinary) Language \- Brill, accessed May 14, 2026, [https://brill.com/display/book/edcoll/9789004314184/B9789004314184-s004.pdf](https://brill.com/display/book/edcoll/9789004314184/B9789004314184-s004.pdf)  
40. Speech Acts in Migrant Nurses' Clinical Interactions, accessed May 14, 2026, [https://ejournal.iainpalopo.ac.id/index.php/ideas/article/download/8636/5428/34189](https://ejournal.iainpalopo.ac.id/index.php/ideas/article/download/8636/5428/34189)  
41. An Analysis of Legitimization Strategies from the Perspective of the Discourse-Historical Approach and Its Enlightenment to Teaching of the Reading Course for English Majors, accessed May 14, 2026, [https://francis-press.com/uploads/papers/TY3mLXbQrFlqb9KCKhiPzRXDlT2reSbFjGsuso73.pdf](https://francis-press.com/uploads/papers/TY3mLXbQrFlqb9KCKhiPzRXDlT2reSbFjGsuso73.pdf)  
42. Towards a Deeper Understanding of Framing, Footing, and Alignment \- Columbia Academic Commons, accessed May 14, 2026, [https://academiccommons.columbia.edu/doi/10.7916/d8-cvy6-c247/download](https://academiccommons.columbia.edu/doi/10.7916/d8-cvy6-c247/download)  
43. Power in Communication: Implications for the Semantics-Pragmatics Interface \- UvA-DARE (Digital Academic Repository), accessed May 14, 2026, [https://pure.uva.nl/ws/files/40285865/1\_s2.0\_S0378216601000674\_main.pdf](https://pure.uva.nl/ws/files/40285865/1_s2.0_S0378216601000674_main.pdf)  
44. A Critical Discourse Analysis of Discursive (De-) Legitimation Construction of Egyptian Revolution in Persian Media \- Academy Publication, accessed May 14, 2026, [https://www.academypublication.com/issues/past/jltr/vol04/05/20.pdf](https://www.academypublication.com/issues/past/jltr/vol04/05/20.pdf)  
45. The Legitimacy of War: Legitimation Discursive Strategies in ..., accessed May 14, 2026, [http://journal.kasell.or.kr/xml/45095/45095.pdf](http://journal.kasell.or.kr/xml/45095/45095.pdf)  
46. Large Language Models in Argument Mining: A Survey \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2506.16383v3](https://arxiv.org/html/2506.16383v3)  
47. Discursive (de)-legitimation strategies in the media \- Aaltodoc, accessed May 14, 2026, [https://aaltodoc.aalto.fi/bitstreams/1a658b23-8942-4703-a2f4-f165ecc214c1/download](https://aaltodoc.aalto.fi/bitstreams/1a658b23-8942-4703-a2f4-f165ecc214c1/download)  
48. Large Language Models in Argument Mining: A Survey \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2506.16383v6](https://arxiv.org/html/2506.16383v6)  
49. Mikhail Bakhtin's Dialogism and Intertextuality: A Perspective, accessed May 14, 2026, [http://englishlinguafranka.blogspot.com/2017/10/mikhail-bakhtins-dialogism-and.html](http://englishlinguafranka.blogspot.com/2017/10/mikhail-bakhtins-dialogism-and.html)  
50. Explain Bakhtin's concept of Heteroglossia and how it defines a novel's unique characteristics. \- eNotes.com, accessed May 14, 2026, [https://www.enotes.com/topics/mikhail-bakhtin/questions/explain-bakhtins-concept-heteroglossia-how-does-419650](https://www.enotes.com/topics/mikhail-bakhtin/questions/explain-bakhtins-concept-heteroglossia-how-does-419650)  
51. Heteroglossia and Boundaries \- SciSpace, accessed May 14, 2026, [https://scispace.com/pdf/heteroglossia-and-boundaries-5feychenpv.pdf](https://scispace.com/pdf/heteroglossia-and-boundaries-5feychenpv.pdf)  
52. The unfolding of geopolitical tensions on social networks: a social network analysis of Twitter and Reddit conversations \- Emerald Publishing, accessed May 14, 2026, [https://www.emerald.com/intr/article/36/2/789/1251314/The-unfolding-of-geopolitical-tensions-on-social](https://www.emerald.com/intr/article/36/2/789/1251314/The-unfolding-of-geopolitical-tensions-on-social)  
53. Bakhtin's Heteroglossia and Dialogism \- CORE, accessed May 14, 2026, [https://core.ac.uk/download/pdf/41689303.pdf](https://core.ac.uk/download/pdf/41689303.pdf)  
54. MULTIPLICITY OF VOICES: A BAKHTINIAN READING OF JOHN CROWLEY'S THE TRANSLATOR \- AVESİS, accessed May 14, 2026, [https://avesis.deu.edu.tr/dosya?id=6cff72c0-b1db-4b24-8016-507e5127d4d2](https://avesis.deu.edu.tr/dosya?id=6cff72c0-b1db-4b24-8016-507e5127d4d2)  
55. Academic Irregularities; Language and Neoliberalism in Higher Education \- Amazon S3, accessed May 14, 2026, [https://s3-eu-west-1.amazonaws.com/s3-euw1-ap-pe-ws4-cws-documents.ri-prod/languageandcommunication/sample\_chapters/discourse\_analysis\_cda/9781138673953-sample.pdf](https://s3-eu-west-1.amazonaws.com/s3-euw1-ap-pe-ws4-cws-documents.ri-prod/languageandcommunication/sample_chapters/discourse_analysis_cda/9781138673953-sample.pdf)  
56. MPVStance: Mitigating Hallucinations in Stance Detection with Multi-Perspective Verification \- ACL Anthology, accessed May 14, 2026, [https://aclanthology.org/2025.acl-long.53.pdf](https://aclanthology.org/2025.acl-long.53.pdf)  
57. Validating Political Position Predictions of Arguments \- White Rose Research Online, accessed May 14, 2026, [https://eprints.whiterose.ac.uk/id/eprint/240335/1/Validating%20Political%20Position%20Predictions%20of%20Arguments.pdf](https://eprints.whiterose.ac.uk/id/eprint/240335/1/Validating%20Political%20Position%20Predictions%20of%20Arguments.pdf)  
58. Large Language Models in Argument Mining: A Survey \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2506.16383v4](https://arxiv.org/html/2506.16383v4)  
59. Argumentative Human-AI Decision-Making: Toward AI Agents That Reason With Us, Not For Us, accessed May 14, 2026, [https://yeoh-lab.wustl.edu/assets/pdf/aamas-VasileiouRTY26.pdf](https://yeoh-lab.wustl.edu/assets/pdf/aamas-VasileiouRTY26.pdf)  
60. Recoding Reality: A Case Study of YouTube Reactions to Generative AI Videos \- MDPI, accessed May 14, 2026, [https://www.mdpi.com/2079-8954/13/10/925](https://www.mdpi.com/2079-8954/13/10/925)  
61. “Reddit's dark knight”: moral inversion, digital populism, and the aesthetic of resistance \- Frontiers, accessed May 14, 2026, [https://www.frontiersin.org/journals/sociology/articles/10.3389/fsoc.2026.1780129/pdf](https://www.frontiersin.org/journals/sociology/articles/10.3389/fsoc.2026.1780129/pdf)  
62. The Ivanishvili System: An Audit of Informal Power in Georgia | CAT AGI, accessed May 14, 2026, [http://catagi.ge/knowledge-base/ivanishvili-system-audit](http://catagi.ge/knowledge-base/ivanishvili-system-audit)  
63. A NATO ally's information war: Unmasking Turkey's global media ..., accessed May 14, 2026, [https://www.fdd.org/analysis/2026/05/08/a-nato-allys-information-war-unmasking-turkeys-global-media-strategy/](https://www.fdd.org/analysis/2026/05/08/a-nato-allys-information-war-unmasking-turkeys-global-media-strategy/)  
64. arxiv.org, accessed May 14, 2026, [https://arxiv.org/html/2603.03267v1](https://arxiv.org/html/2603.03267v1)  
65. Power/Knowledge by Michel Foucault | Literature and Writing | Research Starters \- EBSCO, accessed May 14, 2026, [https://www.ebsco.com/research-starters/literature-and-writing/powerknowledge-michel-foucault](https://www.ebsco.com/research-starters/literature-and-writing/powerknowledge-michel-foucault)  
66. Constant Renewal of the Archaic: Problems in Mikhail Bakhtin's Genre Theory, accessed May 14, 2026, [https://ex-position.org/wp-content/uploads/2025/03/4-6-Ping-hui-Liao.pdf](https://ex-position.org/wp-content/uploads/2025/03/4-6-Ping-hui-Liao.pdf)  
67. Social media analytics for YouTube comments: potential and limitations \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/319984237\_Social\_media\_analytics\_for\_YouTube\_comments\_potential\_and\_limitations](https://www.researchgate.net/publication/319984237_Social_media_analytics_for_YouTube_comments_potential_and_limitations)

---

# I. Symbolic Culture, Myth, Ritual & Memetics  

## Abstract

Symbolic culture is the high-compression layer of social meaning. It turns signs, stories, gestures, objects, colors, rituals, badges, memes, brands, taboos, and sacred forms into social technologies: tools that organize identity, loyalty, memory, emotion, legitimacy, boundary, and collective action.

Reports A–H established the prior architecture. Report A disciplined representation against reality. Report B explained signs, codes, and semiosis. Report C explained how linguistic forms become propositions and claims. Report D explained concepts, categories, frames, and boundaries. Report E established warrant, grounding, evidence, and confidence. Report F explained utterance-in-context and pragmatic force. Report G explained embodied metaphor, analogy, and affective cognitive mapping. Report H explained discourse, narrative, ideology, institutional language, legitimacy, and social reality.

Report I now explains how cultures condense whole worlds of meaning into symbolic artifacts and practices that people can salute, wear, chant, buy, mock, defend, remix, fear, mourn, celebrate, violate, or punish.

The central claim is simple:

**Symbolic culture turns signs into collective coordination technologies. Symbols compress shared worlds into portable forms; myths organize memory and moral order; rituals enact belonging and transformation; sacred/profane distinctions protect group boundaries; taboos regulate danger and identity; brands, flags, badges, and icons condense loyalty; memes replicate and mutate symbolic forms; and collective symbolic behavior aligns emotion, attention, status, and action across groups.**

Semantic intelligence becomes culturally literate when it can identify not only what a symbol denotes, but what it binds, protects, activates, remembers, forbids, licenses, mobilizes, or makes socially costly to reject.

---

## 1. Inherited Foundations from Reports A–H

Report I does not redo the preceding canon. It inherits it.

From **Report A**, symbolic analysis inherits map/territory discipline. A symbol is not the thing symbolized. A flag is not the nation; a wedding ring is not the marriage; a logo is not the product; a badge is not the underlying competence. But symbolic forms can still have real consequences because groups act through them.

From **Report B**, symbolic analysis inherits sign-relations, connotation, codes, interpretive communities, and semiosis. A symbol is a sign, but not every sign is symbolically charged. Report I focuses on the cases where signs become socially loaded, affectively intensified, and collectively actionable.

From **Report C**, symbolic analysis inherits structured linguistic forms: vows, slogans, pledges, chants, prayers, hashtags, taglines, ritual formulas, official declarations, and taboo words. Their force is not only grammatical; it is social, symbolic, and performative.

From **Report D**, symbolic analysis inherits concepts, categories, frames, boundaries, prototypes, identity labels, and sacred/profane distinctions. Symbols often stabilize category membership: insider/outsider, pure/impure, loyal/disloyal, authentic/fake, blessed/cursed, premium/cringe, official/unofficial.

From **Report E**, symbolic analysis inherits warrant discipline. Symbolic force is not the same as factual support. A myth can organize memory without being reliable history. A brand can create trust without proving performance. A ritual can authorize status without changing biology. A meme can spread without representing consensus.

From **Report F**, symbolic analysis inherits pragmatic force. Rituals and symbolic statements are actions: they pledge, bless, accuse, purify, shame, authorize, welcome, exclude, commemorate, apologize, recruit, or mobilize.

From **Report G**, symbolic analysis inherits embodied metaphor, image schemas, affective charge, analogy, archetypal patterning, and conceptual blending. Symbolic culture is saturated with purity, pollution, light, darkness, blood, roots, home, journeys, monsters, rebirth, sacrifice, ascent, fall, contagion, and cleansing.

From **Report H**, symbolic analysis inherits discourse, narrative, ideology, legitimacy, institutional facts, and social reality. Report H explains the social architecture. Report I explains the high-compression symbolic objects and practices that carry that architecture through culture.

---

## 2. Governing Question

Report I orbits one diagnostic question:

**What symbolic form is organizing identity, loyalty, memory, emotion, status, taboo, legitimacy, or group action here — and what does that symbolic organization make possible, costly, sacred, dangerous, or invisible?**

This question matters because symbols often do their most important work below literal assertion. A slogan may not be an empirical claim. A meme may not be an argument. A ritual may not be a proposition. A brand mark may not be evidence. A taboo may not be a logical rule.

Yet each can coordinate behavior.

Semantic intelligence must therefore analyze symbolic artifacts in two passes:

1. **Symbolic-function analysis** — What is this symbol doing socially?
2. **Epistemic-warrant analysis** — What factual claims, if any, does it support?

Failure to separate these produces two opposite errors:

- **Symbolic literalism** — treating symbolic forms as simple factual statements.
- **Symbolic reductionism** — dismissing symbolic forms as “just” cloth, ink, pixels, gestures, merch, jokes, or vibes.

Both are dumb in different hats.

---

## 3. Core Symbolic Ontology

### 3.1 Symbol

A **symbol** is a sign whose meaning depends on convention, collective recognition, and interpretive community. In Report I, the focus is narrower: symbols that carry enough social charge to organize identity, emotion, memory, boundary, legitimacy, or action.

A symbol may denote something, but its practical force often comes from what it condenses.

A flag condenses nation, territory, sacrifice, law, grief, pride, military memory, belonging, and exclusion. A logo condenses brand promise, trust, status, taste, aspiration, and category. A meme condenses stance, humor, in-group literacy, timing, and remix lineage.

### 3.2 Symbolic Vehicle

A **symbolic vehicle** is the form that carries symbolic load: object, image, phrase, color, sound, gesture, ritual sequence, badge, logo, uniform, meme template, chant, sacred text, or taboo word.

The same vehicle may be low-intensity in one context and sacred in another.

A color palette is decorative in a design mockup, identity-bearing for a fandom, sacred/protected for a national or religious context, and conflict-triggering in a sectarian environment.

### 3.3 Symbolic Function

A **symbolic function** is the social labor a symbolic form performs.

Symbols may condense identity, mark boundaries, authorize status, protect sacred values, test loyalty, encode memory, synchronize emotion, recruit action, legitimate hierarchy, or regulate taboo.

Report I should be organized by function first, vehicle second.

### 3.4 Symbolic Efficacy

**Symbolic efficacy** is a symbol’s power to produce social effects: attention, belief, emotion, solidarity, status change, mobilization, exclusion, shame, legitimacy, trust, mourning, purification, or action.

Symbolic efficacy is not the same as empirical truth.

A ritual apology may repair enough social order to matter, even if nobody can verify inner remorse. A badge may grant authority, even if competence varies. A myth may unite a community, even if its historical accuracy is weak.

### 3.5 Symbolic Warrant

**Symbolic warrant** is the justification for treating a symbol as valid within a symbolic system: recognized authority, ritual procedure, community uptake, institutional rule, tradition, platform policy, authenticity chain, provenance, or shared interpretation.

Symbolic warrant differs from epistemic warrant. A degree certificate may symbolically warrant status as “graduate”; it does not prove wisdom. A blue check may warrant account verification under a platform’s policy; it does not prove expertise. A national anthem may warrant solemn treatment within a community; it does not prove the nation’s myths.

### 3.6 Symbolic Intensity

**Symbolic intensity** is the degree of affective, identity, sacred, taboo, or mobilizing charge attached to a symbol.

Intensity determines interpretive caution. A sticker, wedding ring, national flag, martyr image, sacred scripture, gang sign, funeral ritual, and political slogan are not the same symbolic animal.

### 3.7 Symbolic Drift

**Symbolic drift** is change in a symbol’s meaning, intensity, audience, or function over time.

Drift may result from irony, commodification, platform change, institutional redesign, political capture, reclamation, taboo erosion, celebrity uptake, scandal, memetic mutation, generational change, or deliberate rebranding.

Symbolic intelligence requires dating and indexing symbols, not just defining them.

---

## 4. The Symbolic-Operational Arc

To diagnose a symbolic artifact, trace it through this arc:

**Symbolic form → community/code → referent/value → mythic load → sacred/profane status → affective charge → identity function → boundary function → ritual or memetic practice → legitimacy effect → action tendency → symbolic intensity → warrant status.**

Each step asks a different question.

| Stage | Diagnostic Question |
|---|---|
| Symbolic form | What is the artifact: object, phrase, ritual, meme, logo, badge, gesture, color, sound? |
| Community/code | For whom is it legible and charged? |
| Referent/value | What does it point to or protect? |
| Mythic load | What story or memory does it compress? |
| Sacred/profane status | Is it ordinary, protected, forbidden, polluted, or consecrated? |
| Affective charge | What emotions does it activate: pride, fear, grief, disgust, hope, shame, awe? |
| Identity function | Who becomes “we” through it? Who becomes “they”? |
| Boundary function | What line does it draw or enforce? |
| Ritual/memetic practice | How is it repeated, performed, remixed, or circulated? |
| Legitimacy effect | What authority, status, or action does it make feel valid? |
| Action tendency | What does it incline people to do? |
| Symbolic intensity | How costly is violation or rejection? |
| Warrant status | Is the symbol socially valid, empirically supported, both, neither, or contested? |

This arc is the heart of Report I.

---

## 5. Symbolic Function Matrix

Symbols should be analyzed by the social work they perform.

| Symbolic Function | What It Does | Common Vehicles | Diagnostic Question | RAG Warning |
|---|---|---|---|---|
| Identity condensation | Compresses group/person identity into a portable form | Flags, logos, rings, avatars, uniforms, profile badges | Who becomes recognizable through this? | Identity signal is not evidence of virtue or competence. |
| Loyalty signaling | Displays allegiance and willingness to be seen as aligned | Pins, hashtags, slogans, merch, colors | What allegiance is being performed? | Participation may be sincere, ironic, coerced, or opportunistic. |
| Boundary marking | Separates insiders from outsiders | Taboo words, dress codes, memes, ritual entry, jargon | What line is being drawn? | Boundary meaning may be community-local. |
| Sacred-value protection | Marks a value as above ordinary exchange | Scriptures, flags, relics, constitutions, memorials | What must not be mocked, traded, polluted, or profaned? | Sacred status does not automatically settle factual claims. |
| Taboo enforcement | Regulates symbolic danger and classification disorder | Food rules, speech bans, purity codes, etiquette | What violation triggers disgust, shame, or punishment? | Taboo reaction may exceed literal harm. |
| Status authorization | Publicly confers or displays rank, legitimacy, or role | Badges, seals, robes, titles, degrees, medals | Who is authorized to speak or act? | Status signal is not total competence. |
| Trust shortcutting | Reduces uncertainty through recognized marks | Brands, checkmarks, certifications, seals | What trust is being borrowed or condensed? | Trust shortcut can launder weak warrant. |
| Collective memory | Preserves shared past and moral obligation | Monuments, slogans, anniversaries, anthems | What must be remembered, and how? | Collective memory is not identical to historical record. |
| Mourning coordination | Gives grief shared form and rhythm | Vigils, black ribbons, flowers, silence, hashtags | How is loss socially held? | Ritual sympathy may not imply policy agreement. |
| Emotional synchronization | Aligns affect across participants | Chants, songs, marches, ceremonies, fandom rituals | What emotion is being entrained? | Collective affect is not automatically irrational or warranted. |
| Ritual transition | Moves persons/groups between statuses | Weddings, graduations, inaugurations, initiation rites | What status changes publicly? | Ritual status may be real institutionally but limited in scope. |
| Legitimacy borrowing | Transfers prestige from one symbolic order to another | Partnerships, seals, expert quotes, institutional style | Whose authority is being borrowed? | Linkage legitimacy may not support factual claims. |
| Mythic naturalization | Makes contingent arrangements feel natural or inevitable | Origin stories, brand stories, national narratives | What history is being made to feel obvious? | Narrative coherence is not evidential support. |
| Scapegoating/purgation | Transfers disorder or guilt onto a target | Exile rituals, blame narratives, purity campaigns | Who carries the group’s pollution? | Catharsis may hide actual causes. |
| In-group literacy testing | Tests whether someone knows the code | Memes, jokes, shibboleths, jargon | Who gets it? Who does not? | Meaning collapses outside community context. |
| Memetic replication | Spreads symbolic packets through imitation and remix | Meme templates, catchphrases, sounds, formats | What is copied, mutated, and selected? | Virality is not consensus. |
| Mobilization | Converts symbolic alignment into action | Banners, chants, martyr images, callsigns, hashtags | What action does this symbol prepare? | Mobilizing force can exceed evidential grounding. |

This matrix prevents the report from degenerating into “myths, rituals, memes, wow neat.” Function first. Vehicle second. Always.

---

## 6. Symbolic Intensity Scale

Symbols vary in intensity. The higher the intensity, the greater the interpretive caution required.

| Level | Name | Description | Typical Examples | Assistant Posture |
|---|---|---|---|---|
| 1 | Decorative | Low-stakes aesthetic marker; weak identity load | Generic decor, pattern, color preference | Treat as style unless context suggests more. |
| 2 | Expressive | Personal taste or mild affiliation | Band shirt, hobby sticker, fandom mug | Note affiliation, avoid over-reading. |
| 3 | Affiliative | Marks group membership with moderate social cost | School ring, team jersey, Discord role, conference badge | Identify community and audience. |
| 4 | Identity-bearing | Condenses self-concept or important social role | Wedding ring, religious garment, professional title, pronoun marker | Use care; violation can feel personal. |
| 5 | Institutional/status-bearing | Authorizes role, status, access, obligation | Seal, degree, uniform, badge, license, oath | Check authority and scope. |
| 6 | Sacred/protected | Treated as set apart, inviolable, or morally guarded | Flag, scripture, memorial, constitution, relic | Separate sacred force from factual warrant. |
| 7 | Taboo-bound | Boundary violation triggers disgust, shame, pollution response | Desecration, slur, purity violation, forbidden mixing | Identify protected classification system. |
| 8 | Mobilizing | Designed to align collective emotion and action | Protest chant, movement symbol, battle flag, martyr image | Track action tendency and escalation risk. |
| 9 | Conflict-triggering | Symbol indexes deep antagonism or existential threat | Sectarian symbols, extremist insignia, wartime iconography | High caution; preserve context, avoid laundering or amplification. |

The scale is not fixed forever. Symbols move.

A meme can begin decorative, become affiliative, become political, become taboo, and then become retro kitsch. A verification badge can begin as identity warrant, become prestige marker, become paid status, and then become contested platform-affiliation symbol. A brand logo can be decorative to outsiders and sacred to fans. A flag can be patriotic, colonial, banned, reclaimed, ironic, or threatening depending on context.

Symbolic intensity is always indexed to community, time, platform, and situation.

---

## 7. Myth as Social Organization

Myth is not merely falsehood. That is the flat-footed version, useful only if your goal is to misunderstand most of human civilization before lunch.

A myth is a symbolic narrative that organizes collective memory, moral order, identity, legitimacy, and action. Myths may be factually false, historically grounded, partially true, metaphorically true, institutionally useful, spiritually sacred, politically weaponized, or commercially engineered.

The important question is not only “Did this happen?” but:

**What does this story make people remember, value, defend, desire, forgive, fear, or do?**

### 7.1 Mythic Functions

| Mythic Function | What It Organizes | Common Template | Risk |
|---|---|---|---|
| Origin | Beginning, legitimacy, continuity | “We began when…” | Naturalizes current power. |
| Restoration | Loss, decline, return | “We must become great/pure/whole again.” | Purging, nostalgia trap, exclusion. |
| Scapegoat | Blame, pollution, catharsis | “They caused our disorder.” | Misdiagnoses causes, targets outsiders. |
| Heroic transformation | Sacrifice, courage, initiation | “One must suffer to become worthy.” | Glorifies harm or exploitation. |
| Martyr memory | Loss, sacred obligation | “They died for us.” | Makes dissent feel betrayal. |
| Chosen people/group | Destiny, exceptionalism | “We are uniquely called.” | Inflates entitlement. |
| Innocence/corruption | Purity, threat, fall | “We were innocent until corrupted.” | Simplifies history. |
| Progress myth | Future, inevitability, superiority | “History is moving toward us.” | Hides costs and casualties. |
| Brand myth | Desire, identity, promise | “This product makes you who you want to be.” | Converts aspiration into trust without proof. |
| Platform myth | Participation, agency, belonging | “This platform empowers creators/users.” | Hides dependency and extraction. |

### 7.2 Myth and Depoliticization

Barthes is useful here: myth can convert history into nature. It can make a contingent social arrangement look obvious, innocent, eternal, or beyond debate.

A corporate values page may not function primarily as an empirical description of internal behavior. It may function as secular sacred language: “this is who we are,” “this is what we protect,” “this is the moral vocabulary through which you will be judged.” That does not make the page meaningless. It makes it symbolic. But the symbolic function must not be mistaken for evidence that the organization lives those values.

### 7.3 Mythic Diagnostic

For any mythic artifact, ask:

- What origin, fall, crisis, restoration, hero, victim, enemy, or destiny does it install?
- What values become sacred?
- What history becomes simplified?
- What group identity becomes coherent?
- Who is centered, purified, blamed, erased, redeemed, or excluded?
- What action becomes necessary?
- What factual claims, if any, require warrant?
- What would count as counter-evidence?
- Is the myth living, fading, reclaimed, commercialized, ironic, or weaponized?

---

## 8. Ritual as Transformative Social Technology

Ritual is repeated symbolic action with recognized social meaning. It is not mere habit. It is habit plus symbolic load, social recognition, and transformation or reinforcement.

A person brushing their teeth is a habit. A group standing for an anthem is ritual. A court opening formula is ritual. A graduation ceremony is ritual. A daily standup can become ritual if it reaffirms role, accountability, tempo, and group identity. An apology video can become ritual if it follows a recognized script of confession, contrition, purification, and attempted reintegration.

### 8.1 Ritual Functions

| Ritual Function | What It Does | Examples |
|---|---|---|
| Transition | Moves person/group between statuses | Wedding, graduation, initiation, inauguration |
| Authorization | Publicly grants authority or role | Oath, badge ceremony, licensing, ordination |
| Purification | Repairs pollution, guilt, disorder | Confession, washing, apology ritual, distancing statement |
| Mourning | Holds grief collectively | Funeral, vigil, moment of silence, black ribbon |
| Synchronization | Aligns bodies, voices, attention, emotion | Chant, anthem, march, applause, prayer |
| Hierarchy dramatization | Makes rank visible and felt | Robes, seating order, titles, procession |
| Boundary enforcement | Shows who belongs and who does not | Initiation, shibboleth, invitation-only rite |
| Memory renewal | Re-enacts group history | Anniversary, memorial day, reenactment |
| Commitment | Makes promises socially binding | Vow, pledge, contract-signing ritual |
| Repair/reintegration | Allows return after violation | Apology, penance, truth-and-reconciliation process |

### 8.2 Rite of Passage Logic

Van Gennep and Turner give a compact model:

1. **Separation** — the participant is removed from the old status.
2. **Liminality** — the participant is between statuses; ordinary structure may be suspended.
3. **Aggregation/Reintegration** — the participant returns with a new status recognized by the group.

This matters because many modern symbolic forms are disguised rites of passage.

Graduation turns student into graduate. An onboarding ritual turns applicant into employee. A badge ceremony turns candidate into officer. A wedding turns partners into spouses. A username flair can turn lurker into recognized community member. A verification process can turn account into “authentic” or “official.”

### 8.3 Interaction Ritual Chains

Randall Collins’s interaction ritual logic helps explain how symbols become emotionally charged. Rituals generate emotional energy when participants share attention, bodily co-presence or synchronous focus, boundary awareness, and common mood. Successful rituals charge symbols. Failed rituals drain them.

A boring meeting is not just boring. It may be a failed ritual: low shared focus, weak affective synchrony, no meaningful transformation, no renewed commitment. A great conference keynote, protest chant, fandom event, religious service, or product launch can charge symbols with emotional energy that persists after the event.

### 8.4 Ritual Diagnostic

For any ritual-like practice, ask:

- What is repeated?
- Who participates?
- What boundary marks entry or exclusion?
- What role/status changes?
- What emotion is synchronized?
- What object, phrase, or gesture becomes charged?
- What does successful performance authorize?
- What happens if the ritual fails?
- What repair ritual exists after violation?
- Is the ritual religious, institutional, commercial, political, subcultural, or platform-native?

---

## 9. Sacred, Profane, Taboo, Purity, Pollution

Sacred/profane distinctions organize what is set apart from ordinary use. A sacred object, value, place, word, body, memory, or identity is not treated as merely instrumental. It is protected from casual handling, exchange, mockery, quantification, contamination, or desecration.

The sacred is not only religious.

Modern societies sacralize nations, constitutions, markets, science, children, authenticity, trauma, freedom, safety, innovation, identity, nature, data, user privacy, the brand, the mission, the community, the platform, and the founder’s garage story. Delightfully exhausting species.

### 9.1 Taboo as Classification Under Guard

Mary Douglas’s core insight is operationally vital: pollution is often “matter out of place.” Taboo protects a classification system.

A taboo violation may not produce material harm directly. It may instead violate a protected boundary: pure/impure, human/animal, sacred/profane, adult/child, public/private, insider/outsider, loyal/traitorous, gift/commodity, body/object, living/dead.

The emotional intensity comes from boundary disturbance.

### 9.2 Taboo and Pollution Ledger

| Violation Type | Protected Order | Typical Reaction | Repair Move |
|---|---|---|---|
| Sacred object attack | Collective identity and highest values | Outrage, mobilization, punishment demand | Re-sacralization, condemnation, legal/political response |
| Category anomaly | Classification integrity | Anxiety, confusion, ridicule, exclusion | Relabel, separate, create new category |
| Purity contamination | Boundary between clean/unclean or safe/dangerous | Disgust, avoidance, purification demand | Cleansing, quarantine, ritual removal |
| Betrayal | Loyalty and relational trust | Shame, anger, expulsion, moral injury | Confession, restitution, penance, exclusion |
| Status mockery | Institutional legitimacy | Discipline, censorship, humiliation | Apology, reaffirmation of hierarchy |
| In-group violation | Collective security | Scapegoating, suspicion, loyalty testing | Sacrifice, expulsion, recommitment ritual |
| Commercialization of sacred value | Protection from market exchange | Moral outrage, accusations of selling out | Withdrawal, apology, donation, recontextualization |
| Profanation through humor | Solemnity and respect | Offense, taboo enforcement, reputational cost | Clarification, apology, audience segmentation |

### 9.3 Sacred/Profane Diagnostic

Ask:

- What value or object is protected?
- What boundary was crossed?
- Is the violation literal, symbolic, ironic, accidental, or staged?
- Who experiences pollution or desecration?
- What repair is demanded?
- What punishment is considered proportionate by insiders?
- What do outsiders miss?
- What factual claims are being made, if any?
- What is symbolic injury versus empirical harm?

---

## 10. Brands, Flags, Badges, Uniforms, Logos

Brands, flags, badges, uniforms, seals, avatars, verification marks, profile frames, mascots, slogans, and logos are identity condensers and trust shortcuts.

They compress complex social worlds into small recognizable forms.

A flag can carry nation, sacrifice, war memory, territory, grief, pride, law, exclusion, and sacred duty. A logo can carry brand promise, aspiration, style, taste, trust, class position, and category. A badge can carry institutional authority, membership, credentialing, and access rights. A uniform can carry role, discipline, danger, service, expertise, hierarchy, and liability.

### 10.1 Identity Condenser vs Evidence

A logo is not quality evidence. A badge is not total competence. A title is not wisdom. A blue check is not expertise. A uniform is not moral authority. A seal is not universal trust.

These symbols may be socially meaningful and institutionally valid while still weak as evidence for broader claims.

Report I must enforce this distinction:

**Symbolic trust is not epistemic warrant.**

### 10.2 Verification Badge Case: Symbolic Drift

A verification badge is a useful case because its symbolic function can drift.

A platform checkmark may function as:

- identity warrant,
- impersonation defense,
- public notability marker,
- prestige signal,
- paid status,
- platform affiliation,
- moderation privilege,
- creator monetization signal,
- ideological marker,
- stigma within some communities,
- trust shortcut,
- or trust laundering device.

The point is not to settle one universal meaning. The point is to index the symbol by platform, date, policy, community, and audience.

A RAG system that retrieves an old document saying “blue check means verified identity” may mislead if the platform’s policy or social reading changed. Symbolic drift is not decorative. It changes interpretation.

### 10.3 Brand/Badge Symbolics Profile

For any brand, badge, flag, seal, or logo, record:

- symbolic vehicle,
- issuing authority,
- recognized community,
- identity claim,
- trust claim,
- status function,
- access/permission function,
- sacred/protected value,
- drift history,
- possible stigma,
- warrant boundary,
- misuse risk,
- evidence limitations.

---

## 11. Memetics: Symbolic Replication, Mutation, and Stance

Memes are not merely jokes. They are replicating symbolic packets that circulate through imitation, variation, remix, and community uptake.

Limor Shifman’s distinction is operationally useful: memes share patterns of **content**, **form**, and **stance**. A meme is not just an image macro. It is a family of recognizable variations that let participants signal literacy, emotion, affiliation, irony, critique, identity, or aggression.

### 11.1 Meme Functions

| Memetic Function | What It Does | Example Pattern |
|---|---|---|
| In-group literacy | Tests whether someone knows the code | Obscure template, niche reference |
| Stance compression | Packs attitude into portable form | Reaction image, quote format |
| Emotional venting | Converts affect into shareable object | Rage meme, despair meme, cope meme |
| Social timing | Signals being “in the moment” | Trend participation |
| Identity display | Shows taste, politics, fandom, subculture | Profile meme, faction meme |
| Irony management | Allows plausible deniability | “Just joking” template |
| Critique | Makes argument through parody | Satirical remix |
| Mobilization | Recruits participation or outrage | Hashtag meme, protest meme |
| Commodification | Converts subculture into market object | Brand adoption of meme |
| Radicalization/normalization | Makes extreme stance repeatable | Edgy template, euphemistic meme |

### 11.2 Memetic Lifecycle

A useful lifecycle model:

1. **Local emergence** — a template or symbolic form appears in a specific community.
2. **Affinity selection** — insiders reward it because it captures a shared stance.
3. **Mutation and remix** — variants test the boundaries of the joke, stance, or identity.
4. **Breakout** — the form spreads beyond the original community.
5. **Context loss** — outsiders use it without full lineage or stance.
6. **Commercial/political co-optation** — brands, politicians, institutions, or media adopt it.
7. **Saturation** — overuse drains freshness.
8. **Ironization or backlash** — users mock the meme itself or its adopters.
9. **Archive/fossilization** — it becomes historical, nostalgic, cringe, or generic.
10. **Reactivation** — new context revives or repurposes it.

### 11.3 Meme Diagnostic

Ask:

- What is the template?
- What is the original community?
- What is the current community?
- What is being varied?
- What stance is carried?
- Is usage sincere, ironic, hostile, playful, commercial, or compulsory?
- What does participation signal?
- Has the meme drifted?
- Is it still alive, saturated, reclaimed, taboo, co-opted, or fossilized?
- Does virality indicate consensus, mockery, outrage, or algorithmic amplification?

**Virality is not consensus.** It is circulation. Sometimes circulation means approval. Sometimes it means outrage. Sometimes it means the platform’s algorithm found a shiny little chaos pellet.

---

## 12. Archetypes, Symbolic Roles, and Persona Traps

Archetypes are reusable symbolic roles and narrative attractors: hero, trickster, martyr, scapegoat, tyrant, rebel, sage, monster, innocent, exile, chosen one, shadow, apocalypse, rebirth, corrupted king, wounded healer.

They are useful because they help identify recurring symbolic roles in stories and social behavior. They are dangerous because they can become universalizing sludge if treated as proof of a single hidden psychic template.

Report I should treat archetypes as **interpretive patterns**, not metaphysical infrastructure.

### 12.1 Archetype vs Stereotype vs Platform Persona

| Category | Definition | Use | Risk |
|---|---|---|---|
| Archetype | Broad symbolic role-pattern recurring across narratives | Identifies deep narrative function | Over-universalizing |
| Stereotype | Flattened social category with assumed traits | Reveals social bias or default image | Essentialism |
| Persona | Performed social identity or style | Analyzes platform/user behavior | Confusing performance with person |
| Meme character | Reusable symbolic figure in internet culture | Tracks memetic role and stance | Decontextualization |
| Institutional role | Recognized position with rights/obligations | Tracks authority and status | Treating office as essence |

### 12.2 Safer Archetypal Analysis

Instead of saying “this person is the Trickster,” say:

> “This discourse positions the figure in a trickster role: boundary-crossing, rule-subverting, exposing hypocrisy, and creating ambiguity.”

Instead of saying “the community needs a scapegoat,” say:

> “This narrative assigns disorder to a target whose exclusion is framed as purification or restoration.”

That preserves analytic value without turning archetypes into tarot cards with tenure.

### 12.3 Archetype Diagnostic

Ask:

- What role is being assigned?
- Who assigns it?
- What story structure makes the role legible?
- What action does the role authorize?
- Is the role accepted, resisted, ironic, or imposed?
- Is this archetype culturally local, globally common, or analyst-imposed?
- What evidence supports the interpretation?
- What alternative roles are plausible?

---

## 13. Collective Symbolic Behavior

Symbols rarely act alone. They operate in clusters and sequences.

A protest may include chants, colors, flags, slogans, bodies in space, martyr images, livestreams, hashtags, songs, police presence, counter-symbols, rituals of kneeling or marching, and memetic remix. A brand launch may include logo reveal, founder myth, product ritual, influencer seeding, scarcity symbols, countdown, social proof badges, aesthetic code, and community language. A mourning event may include flowers, candles, silence, photos, hashtags, black clothing, speeches, and ritualized phrases.

Collective symbolic behavior coordinates:

- attention,
- emotion,
- memory,
- identity,
- loyalty,
- grief,
- outrage,
- hope,
- trust,
- sacrifice,
- consumption,
- refusal,
- protest,
- punishment,
- belonging.

### 13.1 Collective Symbolic Behavior Map

| Field | Diagnostic Question |
|---|---|
| Symbol cluster | What symbols appear together? |
| Participants | Who uses, displays, rejects, or contests them? |
| Emotional energy | What shared affect is produced? |
| Action script | What behavior becomes likely or expected? |
| Memory function | What past is invoked? |
| Boundary work | Who is included/excluded? |
| Legitimacy effect | What authority is strengthened or weakened? |
| Oppositional symbols | What counter-symbols appear? |
| Platform/institution | Where does circulation occur? |
| Drift | How does meaning change through repetition? |
| Risk | What could escalate, misfire, or be misread? |

---

## 14. Symbolic Function Before Factual Assessment

RAG systems and assistants often make a category error: they treat symbolic artifacts as ordinary factual sources.

A manifesto, anthem, meme, slogan, company values page, religious rite, brand book, protest poster, fandom post, or sacred narrative may contain claims. But its primary value may be symbolic: recruiting identity, sacralizing a value, marking taboo, coordinating emotion, legitimating action, producing memory, or testing membership.

Before using a symbolic artifact as evidence, ask:

1. What symbolic function does it perform?
2. For what community?
3. With what intensity?
4. Does it assert factual claims?
5. Are those claims warranted independently?
6. Is the artifact better evidence of belief, identity, stance, emotion, memory, ritual, or mobilization than of factual reality?

Example:

- A brand manifesto is strong evidence of brand positioning.
- It is weak evidence of product quality.
- It may be moderate evidence of intended culture.
- It is not direct evidence of actual internal behavior.

Example:

- A protest chant is evidence of group emotion and mobilization.
- It may not be evidence that the chant’s claims are true.
- It can still be socially important because it coordinates action.

Example:

- A meme’s virality is evidence of circulation.
- It is not necessarily evidence of agreement.
- It may reflect outrage, mockery, algorithmic amplification, or ironic spread.

This distinction is the operational spine of Report I.

---

## 15. RAG Metadata for Symbolic Artifacts

Symbolic artifacts should be tagged as symbolic artifacts, not merely as topic content.

### 15.1 Symbolic Object Record

| Field | Description |
|---|---|
| Symbol_ID | Stable identifier |
| Symbolic_Form | Object, phrase, image, ritual, meme, badge, color, sound, gesture |
| Community_Code | Community or interpretive group |
| Primary_Function | Identity, boundary, ritual, memory, trust, taboo, mobilization, etc. |
| Secondary_Functions | Additional functions |
| Referent_or_Value | What it points to or protects |
| Mythic_Load | Narrative memory or origin/restoration/scapegoat story |
| Sacred_Status | Profane, protected, sacred, taboo-bound, contested |
| Intensity_Level | 1–9 scale |
| Affective_Charge | Pride, grief, disgust, awe, humor, shame, anger, hope |
| Boundary_Function | Insider/outsider, pure/impure, loyal/disloyal, authentic/fake |
| Ritual_Practice | Repetition, ceremony, enactment, status change |
| Memetic_Practice | Template, remix, mutation, lineage |
| Legitimacy_Effect | What authority or action it validates |
| Action_Tendency | What it inclines people to do |
| Drift_Status | Stable, shifting, reclaimed, co-opted, ironic, fossilized |
| Warrant_Status | Symbolic, empirical, institutional, weak, contested |
| Misread_Risk | Literalism, reductionism, decontextualization, over-reading |
| Assistant_Use | How the artifact may be used in answers |

### 15.2 Permissible Use Labels

| Label | Meaning |
|---|---|
| Use as symbolic-function evidence | Strong evidence of identity, ritual, stance, memory, or mobilization |
| Use as attributed belief | Evidence that a group/source expresses a belief |
| Use as institutional signal | Evidence of official position, status, or procedure |
| Use as weak factual support only | Contains claims but does not warrant them alone |
| Use only with caveat | Symbolic intensity or drift creates ambiguity |
| Do not use as factual support | Symbolic artifact does not support empirical claim |
| Mark as contested | Meaning varies by community/time |
| Mark as stale | Symbolic meaning has drifted since source date |

### 15.3 Symbolic Retrieval Failure Bank

| Failure | Example | Why It Fails | Repair |
|---|---|---|---|
| Treating brand myth as product proof | “We empower creators” used as evidence creators are empowered | Symbolic positioning ≠ outcome evidence | Use as brand discourse; seek independent data |
| Treating meme virality as consensus | Viral joke used as public opinion evidence | Spread may reflect mockery or outrage | Identify stance and circulation context |
| Treating ritual phrase as literal claim | “Thoughts and prayers” as verifiable statement | Ritual sympathy is not observable inner state | Analyze phatic/ritual function |
| Treating flag as cloth only | Flag burning interpreted as property damage only | Misses sacred/profane violation | Map symbolic intensity and protected value |
| Treating badge as competence proof | Verification/checkmark used as expertise evidence | Status/authenticity ≠ expertise | Check authority scope |
| Treating taboo as irrational error | Outrage over symbolic violation dismissed | Boundary/protected value missed | Identify taboo system |
| Treating archetype as diagnosis | “Troll” becomes whole-person essence | Role performance ≠ person ontology | Analyze behavior, not essence |
| Treating ritual as empty | Graduation dismissed as costume show | Status transformation ignored | Identify institutional recognition |

---

## 16. Operational Diagnostics: Naive vs Symbolically Disciplined Interpretation

### 16.1 Flag Burning

**Naive interpretation:** Destruction of cloth or ordinary political speech.

**Symbolically disciplined interpretation:** A high-intensity symbolic act involving a sacred/protected object. It can function as protest, taboo violation, desecration, identity rejection, boundary crossing, or provocation. Its social force depends on the community for whom the flag condenses nation, sacrifice, memory, law, grief, or belonging.

**Warrant boundary:** The act is strong evidence of symbolic opposition or protest performance. It is not by itself evidence of the actor’s full ideology, loyalty, citizenship, or intent beyond contextual support.

**Repair move:** Identify the sacred value, community, action context, and stated intent.

### 16.2 Wedding Ring

**Naive interpretation:** A decorative piece of jewelry.

**Symbolically disciplined interpretation:** A ritual residue and identity condenser. It indexes vow, status, social recognition, commitment, relationship boundary, and public role. Its removal, concealment, loss, or desecration may carry symbolic weight beyond material value.

**Warrant boundary:** The ring can indicate marital status in many contexts but does not prove relationship quality, fidelity, legal status in all jurisdictions, or emotional state.

**Repair move:** Treat as status symbol with context-sensitive evidence value.

### 16.3 Blue Checkmark / Verification Badge

**Naive interpretation:** Trustworthy person or expert source.

**Symbolically disciplined interpretation:** Platform-mediated status symbol whose meaning depends on policy, date, community, and platform. It may signal identity verification, notability, subscription, affiliation, monetization, or contested status.

**Warrant boundary:** It may support authenticity under a platform’s policy. It does not establish expertise, accuracy, moral reliability, or institutional authority.

**Repair move:** Check platform policy, date, and claim type.

### 16.4 “Thoughts and Prayers”

**Naive interpretation:** Literal, verifiable statement about inner spiritual activity.

**Symbolically disciplined interpretation:** Ritualized sympathy formula. It can function as mourning coordination, phatic care, moral alignment, conversational stopgap, religious expression, or contested political avoidance depending on context.

**Warrant boundary:** It is not strong evidence of policy commitment or practical aid. It may be evidence of ritual sympathy or group-appropriate response.

**Repair move:** Distinguish ritual support from action commitment.

### 16.5 Corporate Values Page

**Naive interpretation:** A list of company ethics.

**Symbolically disciplined interpretation:** Secular sacred language and institutional identity architecture. It defines protected values, desired subject positions, legitimacy claims, behavior norms, and internal culture rituals.

**Warrant boundary:** Strong evidence of official self-presentation. Weak evidence of actual behavior without independent support.

**Repair move:** Use as brand/institutional discourse; seek audits, employee reports, policies, incentives, outcomes.

### 16.6 Meme Shifting from Joke to Political Signal

**Naive interpretation:** Just a funny image.

**Symbolically disciplined interpretation:** A memetic packet whose function changed through circulation. It may now signal in-group literacy, ideology, defiance, irony, or coordinated stance.

**Warrant boundary:** Usage does not automatically prove belief. It may be ironic, opportunistic, hostile, playful, or coerced by platform trend dynamics.

**Repair move:** Trace lineage, community, stance, timing, and uptake.

### 16.7 Protest Chant

**Naive interpretation:** A slogan or claim.

**Symbolically disciplined interpretation:** Emotional synchronization technology. It aligns breath, rhythm, identity, memory, and action. It can simplify complex demands into a repeatable collective form.

**Warrant boundary:** Strong evidence of movement stance and mobilization. Not sufficient evidence that the chant’s claim is empirically true.

**Repair move:** Separate chant function from claim evaluation.

### 16.8 Brand Logo

**Naive interpretation:** Visual identifier.

**Symbolically disciplined interpretation:** Identity condenser and trust shortcut. It links product, promise, taste, status, memory, community, and category.

**Warrant boundary:** Strong evidence of brand identity. Weak evidence of product performance.

**Repair move:** Distinguish recognition, aspiration, and empirical quality.

---

## 17. Symbolic Failure Modes and Repair Moves

| Failure Mode | Description | Repair Move |
|---|---|---|
| Symbolic literalism | Treating symbolic artifact as simple factual claim | Ask what it binds, protects, authorizes, or mobilizes |
| Symbolic reductionism | Treating symbol as “just” material object | Locate affective charge, protected value, and community |
| Myth-as-falsehood flattening | Dismissing myth because it is not literal history | Analyze identity, legitimacy, memory, and action function |
| Brand credulity | Treating brand trust as performance proof | Separate symbolic trust from empirical warrant |
| Sacred/profane blindness | Missing why a violation feels morally explosive | Map sacred value and profanation logic |
| Taboo misread | Treating taboo reaction as simple irrationality | Identify classification boundary under guard |
| Ritual-as-habit collapse | Treating ritual as mere repetition | Identify transformation, recognition, status, or synchrony |
| Memetic decontextualization | Reading meme outside lineage/community | Trace template, stance, platform, timing |
| Archetype overreach | Turning role pattern into universal truth | Use archetype as lens, not conclusion |
| Universalizing cultural patterns | Assuming one symbolic reading applies everywhere | Compare insider/outsider and cross-cultural readings |
| Collective affect pathologizing | Treating group emotion as automatically irrational | Ask what emotion coordinates and whether warrant supports it |
| Participation = endorsement | Assuming symbolic participation equals full belief | Check sincerity, irony, coercion, play, trend pressure |
| Virality = consensus | Treating circulation as agreement | Distinguish approval, outrage, mockery, algorithmic spread |
| Symbolic efficacy = proof | Treating powerful symbol as factual evidence | Apply Report E warrant discipline |
| Manipulation lens too early | Treating all symbolic behavior as propaganda | First analyze function; then assess manipulation if warranted |
| Stale-symbol error | Using old symbolic meaning after drift | Date and index meaning by community/platform |
| Trust-laundering | Borrowed symbol confers undeserved credibility | Identify issuer, authority scope, and warrant boundary |

---

## 18. Conflict Mapping in Symbolic Analysis

Symbolic interpretation often involves genuine disagreement. Do not average away disagreement. Map it.

### 18.1 Common Theoretical Tensions

| Tension | Side A | Side B | Practical Inheritance |
|---|---|---|---|
| Durkheimian cohesion vs conflict theory | Symbols bind groups | Symbols reproduce power | Ask both: what solidarity and what hierarchy? |
| Structuralism vs interpretivism | Symbols express deep structures | Symbols mean locally through thick context | Use structure as hypothesis, context as check |
| Myth as sacred narrative vs ideology | Myth gives order | Myth naturalizes power | Ask what it organizes and what it hides |
| Ritual as transformation vs performance | Ritual changes status | Ritual displays or dramatizes status | Track institutional recognition and audience uptake |
| Memes as cultural replicators vs participatory practice | Memes spread like units | Users remix and reinterpret actively | Track template and community agency |
| Archetypes as universal vs culturally local | Patterns recur broadly | Meanings vary historically | Use archetypes lightly, with cultural warrant |
| Sacred injury vs free expression | Symbolic violation harms community order | Symbolic violation is political speech | Distinguish legal status, symbolic intensity, and social effect |
| Brand community vs manipulation | Brands create identity and belonging | Brands monetize affiliation | Analyze both solidarity and extraction |

### 18.2 Evidence for Symbolic Interpretation

Different claims require different evidence.

| Claim Type | Better Evidence |
|---|---|
| “This symbol is sacred to this community” | Ritual treatment, taboo response, insider testimony, institutional protection |
| “This meme carries political stance” | Usage context, remix lineage, platform community, co-occurring symbols |
| “This ritual authorizes status” | Institutional rules, public recognition, procedural consequences |
| “This brand symbol creates trust” | Brand research, user behavior, recognition studies, market positioning |
| “This myth legitimates hierarchy” | Narrative analysis, institutional use, repeated justificatory function |
| “This symbol has drifted” | Historical comparison, platform policy changes, corpus shifts, community commentary |
| “This artifact mobilizes action” | Behavioral uptake, participation data, event coordination, calls to action |

When evidence is weak, use lighter language: *may function as*, *is likely operating as*, *appears to carry*, *within this community*, *under this interpretation*.

No symbolic clairvoyance. Very tempting. Bad hobby.

---

## 19. RAG/Assistant Doctrine for Symbolic Culture

A semantically intelligent assistant should not treat all retrieved text as claim-evidence. Symbolic artifacts need symbolic interpretation first.

### 19.1 Operational Rules

1. **Identify symbolic function before factual use.**
2. **Anchor symbol meaning by community, platform, time, and genre.**
3. **Separate symbolic efficacy from epistemic warrant.**
4. **Treat sacred/profane violations as boundary events, not mere disagreements.**
5. **Treat memes as stance-bearing remix families, not isolated jokes.**
6. **Treat brands and badges as trust shortcuts, not proof.**
7. **Treat rituals as status/identity operations, not empty repetition.**
8. **Treat myths as social organization, not automatically falsehood.**
9. **Use archetypes as role-patterns, not universal diagnosis.**
10. **Track symbolic drift.**
11. **Avoid both suspicion theater and symbolic naivety.**
12. **When stakes are high, state uncertainty and seek community-specific context.**

### 19.2 Assistant Response Patterns

The system should become able to say:

- “This is not just a logo; it is an identity condenser.”
- “This symbol is functioning as a loyalty test.”
- “The taboo violation explains the intensity of reaction, not the literal harm alone.”
- “This ritual marks transition and authorizes a new social status.”
- “This brand myth creates trust but does not prove quality.”
- “The flag is operating as a sacred object in this context.”
- “This meme requires community literacy and timing.”
- “This archetype is useful but culturally variable.”
- “This meme has shifted from joke to political signal.”
- “This artifact is symbolically powerful but epistemically weak.”
- “This is not a policy claim; it is a mythic restoration narrative.”
- “This is not a logical error; it is a sacred boundary conflict.”
- “This badge may warrant identity, not expertise.”
- “This ritualized statement performs sympathy, not necessarily action.”

---

## 20. Boundaries with Later Reports

Report I does not own everything symbolic-adjacent.

**Report J** will deepen multimodal signs and interface symbolics: visual layout, typography, UI icons, diagrams, spatial meaning, cinematic language, auditory cues, gesture, and cross-modal composition.

**Report K** will deepen ambiguity, polysemy, semantic drift, reclamation, euphemism cycles, and contested meaning.

**Report L** will deepen translation, localization, cross-cultural variance, domain transfer, stakeholder vocabularies, and interoperability.

**Report M** will deepen manipulation, propaganda, dog whistles, symbolic misfires, framing traps, hallucinated patterns, and interpretive failure.

**Report N** will operationalize the knowledge infrastructure: symbol records, annotation systems, semantic graphs, retrieval metadata, governance workflows, and evaluation rubrics.

Report I’s job is narrower and sharper:

**It explains how symbols become collective coordination technologies.**

---

## 21. Doctrine Capsule

1. A symbol is a sign with collective charge.
2. Symbols compress worlds into portable forms.
3. Symbolic function comes before factual assessment.
4. Symbolic efficacy is not epistemic warrant.
5. Sacred objects are not “just objects” to the communities that sacralize them.
6. Taboo protects classification systems under emotional guard.
7. Ritual is repeated symbolic action that transforms or reinforces social reality.
8. Myth is social organization, not merely falsehood.
9. Brands, flags, badges, and logos are identity condensers and trust shortcuts.
10. Trust shortcuts can launder weak warrant.
11. Memes are stance-bearing remix families, not merely jokes.
12. Virality is circulation, not consensus.
13. Archetypes are reusable symbolic roles, not universal proof.
14. Symbols drift; index them by time, platform, and community.
15. Collective emotion can coordinate solidarity or escalation.
16. Symbolic injury can be socially real without settling factual truth.
17. Participation does not always equal endorsement.
18. A ritual phrase may perform care without committing to action.
19. A symbolic artifact may be strong evidence of identity and weak evidence of reality.
20. The assistant should ask: what does this symbol bind, protect, authorize, forbid, or mobilize?

---

## 22. What Report I Gives the Canon

Report I gives the Semantic-Semiotic Intelligence canon the **collective-symbolic layer**.

It explains how meanings become culture you can wear, chant, salute, purchase, fear, defend, remix, desecrate, inherit, or mourn. It shows how symbols operate as social technologies that organize identity, loyalty, memory, emotion, taboo, ritual, legitimacy, and group action.

Where Report H explained how discourse and narrative build social realities, Report I explains how those realities are condensed into charged symbolic vehicles and repeated practices. It gives the canon tools for distinguishing symbolic efficacy from epistemic warrant, sacred boundary from ordinary preference, meme from joke, ritual from habit, myth from falsehood, brand promise from product evidence, archetype from stereotype, and virality from consensus.

The SSI canon can now diagnose symbolic artifacts by asking:

- What symbolic form is present?
- Which community gives it meaning?
- What value does it protect?
- What identity does it condense?
- What boundary does it mark?
- What affect does it activate?
- What ritual or memetic practice carries it?
- What action does it incline?
- How intense is the symbol?
- What factual claims, if any, are warranted?

This prevents the knowledge base from mistaking social coordination for empirical evidence, while also preventing the opposite error: dismissing symbolic force because it is not literal fact.

Report I therefore turns symbolic culture from “interesting human weirdness” into operational semantic infrastructure.

The machine now knows that cloth can be nation, pixels can be status, jokes can be allegiance, rings can be vows, silence can be mourning, colors can be taboo, slogans can be action, and myths can move history without being history.

A ridiculous species. A useful report.

---

# J. Multimodal Signs & Interface Symbolics

## **The Multimodal Turn in Semantic Intelligence**

The evolution of semantic-semiotic intelligence necessitates a fundamental shift from logocentric models of meaning to a comprehensive multimodal literacy. Historically, meaning was often treated as a property of lexical strings—captured in text, parsed by syntax, and resolved in propositional logic. However, as the prior investigations in Reports F–I have demonstrated, meaning is never a sequestered linguistic phenomenon. It is a situated, social, and cognitive process that is increasingly mediated by designed artifacts that integrate diverse semiotic modes . Report J serves as the canon’s multimodal layer, expanding the domain of meaning construction into the visual, auditory, gestural, spatial, typographic, cinematic, and diagrammatic spheres. This shift recognizes that an interface is not merely a utility but a symbolic environment; a chart is not an illustration but a warrant for a claim; and a gesture is not an ornament but a constituent of the thought process itself .

The core thesis of this report is that multimodal meaning is constructed through a coordinated ensemble of semiotic modes that work in concert to shape attention, hierarchy, affect, action, evidence, and interpretation. Semantic intelligence reaches its mature state only when it can decode not just what a multimodal artifact says, but how its various modes perform semiotic work together.1 In the contemporary semiotic landscape, the materiality of the signifier—the pixels of a button, the weight of a typeface, the timing of a cinematic cut, or the spatial arrangement of a diagram—is as critical to the construction of truth as the words it accompanies.1 This investigation moves through an operational arc that begins with the artifact as a designed object and concludes at the warrant boundary, where multimodal evidence is evaluated for its integrity and truth-value.7

## **I. Visual Grammar and the Social Semiotics of the Image**

Visual communication is not a passive reflection of reality but a motivated system of representation. Drawing upon the social semiotic framework established by Michael Halliday and adapted to the visual mode by Gunther Kress and Theo van Leeuwen, we recognize that images, like language, fulfill specific metafunctions. They represent the world (ideational), establish social relations (interpersonal), and organize information into coherent messages (textual) .

### **Representational Meaning: Narrative and Conceptual Structures**

The ideational metafunction in visual design is realized through two primary structures: narrative and conceptual. Narrative representations depict processes of change and events through the use of vectors—diagonal lines or directed glances that connect participants.10 These vectors establish a sense of action, signaling who is the "actor" and who is the "goal." In contrast, conceptual representations define the stable essence of things. These structures categorize the world into taxonomies or partonomies, using spatial arrangements to show what an object "is" or "consists of".1

| Structure Type | Semiotic Realization | Cognitive Function |
| :---- | :---- | :---- |
| Narrative | Vectors, directed glances, action lines.10 | Represents events, unfolding time, and social action.11 |
| Classificational | Tree diagrams, taxonomic arrangements.11 | Defines social constructs and hierarchies of kind.1 |
| Analytical | Part-to-whole relationships, labeled diagrams.1 | Deconstructs objects into their functional constituents.13 |
| Symbolic | Highly salient attributes or suggestive motifs.11 | Conveys abstract meaning or identity through association.5 |

Table 1: Visual Representational Structures.10

The move from narrative to conceptual representation marks a shift in semantic weight. A narrative image of a worker in a factory portrays a specific historical event; a conceptual diagram of a factory hierarchy portrays a social system.11 Semantic intelligence must distinguish between these modes to understand whether a visual artifact is reporting an occurrence or asserting a structural law.

### **Interactive Meaning: The Semiotics of Engagement**

The interpersonal metafunction of the image governs the relationship between the viewer and the represented subject. This is managed through the variables of gaze, angle, and distance. A "demand" image occurs when a represented participant looks directly at the camera, establishing a pseudo-social connection that requires a response from the viewer.10 Conversely, an "offer" image occurs when the participant looks away, allowing the viewer to observe them as an object of information without the pressure of engagement.10

Social distance is communicated through the size of the frame. A close-up shot mimics the "intimate distance" of human interaction, while a long shot creates "public distance" and detachment.10 The viewing angle further modulates the power dynamic. A high angle (looking down) often grants the viewer authority or suggests the subject's vulnerability, while a low angle (looking up) empowers the subject. Eye-level angles suggest equality and shared social space. These cues are not decorative; they are "grammatical" choices that position the viewer emotionally and socially, much like the use of pronouns or tone in spoken language.10

### **Compositional Meaning: Spatial Information Value**

The textual metafunction is realized through the arrangement of elements on the page or screen. This spatial grammar dictates how information is prioritized and navigated. In Western cultures, the "Given-New" structure typically places familiar, established information on the left and new, challenging information on the right.10 The vertical axis often follows an "Ideal-Real" logic: the top of the page contains the generalized, emotive "ideal," while the bottom contains the specific, practical, or evidentiary "real".10 Salience is established through size, color contrast, and focus, directing the eye toward the most important content. Framing—the use of borders or whitespace—signals whether elements are connected or distinct .

## **II. Interaction Semiotics and the Design of Affordances**

Meaning in the digital domain is not just observed; it is navigated. The transition from the "image" to the "interface" introduces the semiotics of interaction. Here, the intellectual spine is provided by the work of Don Norman and the principles of Human-Computer Interaction (HCI). Interfaces are symbolic environments where every pixel must communicate its "meaning potential" for action .

### **The Principles of Discoverability**

A well-designed interface makes its correct use obvious while making incorrect actions difficult or impossible . This is achieved through six foundational principles that ensure the user’s mental model aligns with the system’s physical reality .

1. **Affordances**: These are the perceived and actual properties of an object that determine how it can be used . In a digital context, affordances are often metaphorical. A button "affords" clicking because it mimics the appearance of a physical, tactile object .  
2. **Signifiers**: While affordances show what is possible, signifiers act as explicit clues that point out *how* and *where* to act . A "Push" sign on a door is a signifier; a blue underline on text is a signifier for a link .  
3. **Mappings**: This refers to the relationship between controls and their effects. Good mapping aligns with the physical world or cultural conventions . A classic example of bad mapping is a set of light switches that do not match the arrangement of the lights in the room .  
4. **Feedback**: Every action must have an immediate and clear result. This can be visual (a button changing color), auditory (a "beep"), or haptic (a vibration) . Without feedback, users are left in a state of uncertainty .  
5. **Constraints**: Design can restrict possible actions to prevent errors. Physical or logical constraints (like a USB stick that only fits one way or a disabled button) are the most effective .  
6. **Conceptual Models**: The user forms a mental image of how a system works based on the available signifiers and feedback. Good design supports a simple, correct conceptual model .

### **From Skeuomorphism to Flat Design: The Semiotic Shift**

The history of UI design reflects a changing relationship with the material world. Early interfaces relied on skeuomorphism—making digital elements look like their physical counterparts—to leverage existing mental models (e.g., a "trash can" icon) . As users became more "multimodally literate," the need for these literal metaphors declined, leading to the "Flat Design" trend . Flat design uses subtle cues and counts on the user’s past experience with screen-based interfaces . However, this shift can lead to "affordance erosion" if the signifiers become too subtle for identifying interactive potential .

## **III. Graphical Integrity and the Warrant of Data Visualization**

When a multimodal artifact includes data, it moves from social interaction into the domain of evidence. Data visualization is not an aesthetic enhancement of information but a mathematical warrant for a claim. Edward Tufte’s principles of graphical integrity provide the discipline for ensuring that the visual representation accurately reflects the underlying numerical reality.7

### **The Mathematics of Graphical Honesty**

Tufte argues that "graphical excellence is not about style—it's about truth".16 The primary metric for honesty in visualization is the Lie Factor, which measures the discrepancy between the size of the effect shown in the graphic and the actual size of the effect in the data.16

Lie Factor \= (Size of effect shown in graphic) / (Size of effect in data)

A Lie Factor of 1.0 represents an honest graphic. Deviations outside the range of 0.95 to 1.05 generally indicate unacceptable distortion.16 Common sources of high Lie Factors include using area to represent one-dimensional data (which creates a squared effect) or truncating the y-axis to exaggerate minor variations .

### **The Data-Ink Ratio and Chartjunk**

Effective visualization maximizes the "data-ink ratio," which is the proportion of ink on a graphic devoted to the non-redundant display of data-information.18

Data-Ink Ratio \= Data-ink / Total ink used to print the graphic

Tufte advocates for the removal of "chartjunk"—unnecessary visual clutter like 3D effects, heavy gridlines, or decorative backgrounds—that distracts from the data and may signal that the data itself is not compelling enough.16 The goal is to maximize the density of information while minimizing the "noise" of non-essential ink.18

| Integrity Principle | Semiotic Requirement | Violation Example |
| :---- | :---- | :---- |
| **Comparison** | Show data in context ("Compared to what?"). 16 | Isolated numbers without baseline or trends.16 |
| **Data-Ink Ratio** | Minimize non-data ink and redundant data-ink.18 | 3D bar charts, decorative icons, gridlines . |
| **Causality** | Suggest the mechanism behind the data change . | Simple correlation without context or mechanism.16 |
| **Integrate Evidence** | Combine text, numbers, and graphics . | Segregated legends that require constant toggling.16 |
| **Documentation** | Provide attribution and methodology . | Missing scales, unlabeled axes, unknown sources . |

Table 2: Tufte’s Principles of Graphical Integrity .

## **IV. Diagrammatic Reasoning and the Primacy of Space**

Diagrams are unique multimodal artifacts that serve as "tools of thought".22 They allow cognitive processes to be offloaded into the environment, reducing the burden on working memory.19 The fundamental power of a diagram lies in its spatial indexing of information, which distinguishes it from the sequential "sentential" representation of language.22

### **Computational Efficiency: The Larkin-Simon Thesis**

Jill Larkin and Herbert Simon (1987) demonstrated that while text and diagrams can be informationally equivalent, they are rarely computationally equivalent.22 In a sentential representation, each component is a separate symbol in a sequence, requiring the mind to search through a list to find connections.40 In a diagrammatic representation, information is indexed by location.22

1. **Search Benefits**: Diagrams group all information used together at a single location, allowing the attention management system to access it simultaneously without a brute-force search through a list of sentences.22  
2. **Recognition Benefits**: Diagrams use topological and geometric relations to automatically support perceptual inferences.22 For example, a "triangle" in a diagram is an emergent shape that can be recognized instantly, whereas in text, its properties would have to be computed from a list of coordinates and lines.40

### **Tversky’s "Spraction" and Schematization**

Barbara Tversky identifies "spraction"—the way human actions organize space to convey abstractions—as a core cognitive foundation.13 External representations are necessarily selective; they schematize reality by omitting irrelevant information and simplifying what remains.19

* **Partonomy vs. Taxonomy**: People think about objects first in terms of their parts (partonomy) and then in terms of their kinds (taxonomy).13 A successful diagram uses frames or boxes to explicitly separate these different forms of representation (e.g., a "scene" of action vs. a "catalog" of parts).13  
* **Sketch Maps**: Unlike topographic maps, human sketch maps are not "accurate" in terms of distance or direction. Instead, they prioritize the "points of action"—turns and landmarks—that are essential for navigation.20

## **V. The Embodied Sign: Gesture, Sound, and Cinema**

Multimodal literacy extends beyond the page and screen into the semiotics of the human body and temporal media. Gesture, sound, and cinema represent modes where meaning is constructed through movement, prosody, and the relationship between shots.

### **McNeill’s Imagery-Language Dialectic**

David McNeill argues that speech and gesture are not separate systems but parts of a single, integrated "imagery-language dialectic" . Gestures provide the imagery for this dialectic, fueling and propelling thought as it seeks resolution in speech . McNeill classifies gestures into four major categories based on their semiotic function .

| Gesture Type | Description | Semiotic Role |
| :---- | :---- | :---- |
| **Iconic** | Bears a formal relationship to the semantic content (e.g., hand moving up for "climb") . | Depicts concrete imagery co-expressive with speech . |
| **Metaphoric** | Pictured abstract content as if it had physical form (e.g., holding an "idea") . | Imagines the unimageable; gives spatial form to ideas . |
| **Deictic** | Pointing to actual or symbolic locations in space . | Indexical; establishes spatial orientation or reference . |
| **Beat** | Simple, rhythmic flicks of the hand that mark narrative or structural points . | Non-referential; tracks the flow and prosody of speech . |

Table 3: The Quartet of Co-Speech Gestures .

These gestures occur in close temporal synchrony with speech, with the "stroke"—the most meaningful part of the gesture—lining up with the equivalent linguistic segment .

### **Auditory Semiotics: Sound as Social Semiotic**

Theo van Leeuwen extends social semiotics to the auditory mode, asking what sound can "say" beyond lexical content . Spoken language makes meaning at two levels simultaneously: the level of word meaning and the level of sound meaning . Sound parameters such as pitch, loudness, and timbre are semiotic resources for expressing identity and social distance .

* **Aural Perspective and Social Distance**: Just as the visual frame establishes social distance, loudness in sound creates "aural perspective." A voice that is loud and clear is positioned in the "intimate zone," while a quiet, distant voice signals "public distance" .  
* **The Semiotics of the Voice**: Physical tension in the vocal musculature can make a voice higher or sharper, which socially "means" tension . Technology (microphones, amplifiers) has changed the "semiotic potential" of the voice, allowing it to be disembodied or "acousmatic" .

### **Cinematic Logic: Montage and the Power of the Cut**

In cinema, meaning is built out of an "assemblage of shots" where the juxtaposition of fragments creates a synthesis greater than the sum of its parts .

* **Soviet Montage Theory**: Sergei Eisenstein envisioned montage as "the nerve of cinema," where the "collision" of independent shots creates metaphors and rhetorical points . He defined five methods of montage: Metric (based on shot length), Rhythmic (based on visual movement), Tonal (based on emotional affect), Overtonal (synthesis of stimuli), and Intellectual (using images for abstract concepts) .  
* **Intensified Continuity**: David Bordwell describes the dominant Hollywood style as "intensified continuity," which uses rapid editing, close-ups, and camera movement to guide the viewer’s attention smoothly, maintaining invisible flow and temporal coherence .

## **VI. Typographic Ideology: The Crimes of Helvetica**

Typography is a powerful tool that influences a layout’s style, mood, and readability. However, the history of typography reveals that typefaces are never neutral; they are often embedded in ideologies of modernism and authority.

### **The Cult of Neutrality**

Helvetica is the most iconic example of the "International Typographic Style".17 Designed to be a "neutral face" that should not be given any additional meaning, it was adopted by major corporations and public bodies as a symbol of professionalism.17 Critics argue that this very "blankness" is its power—it acts as a "transparent container" for corporate and government messages, lending them a sense of objective authority.28

* **The Crimes of Helvetica**: Designers like Erik Spiekermann have criticized Helvetica for its ubiquity, arguing that its dominance represents a "design failure" where imagination is sacrificed for safe, default choices.17  
* **Political Invisibility**: Theorists argue that "neutrality is an overrated myth." When Helvetica becomes "invisible" through ubiquity, it can reinforce corporate dominance and erase alternative perspectives.41

## **VII. Deceptive Design: The Semiotics of the Dark Pattern**

Dark patterns represent a corruption of interface semiotics, where signifiers and affordances are intentionally designed to mislead users into actions that benefit the system at the expense of the user . Unlike poor design, which is unintentionally confusing, dark patterns are deliberately crafted to exploit cognitive biases.29

| Dark Pattern | Semiotic Mechanism | Ethical Alternative |
| :---- | :---- | :---- |
| **Roach Motel** | Easy to enter (sign up), nearly impossible to leave (cancel) . | Provide a straightforward, one-click cancellation process . |
| **Confirmshaming** | Uses guilt or sarcasm to pressure users ("No thanks, I hate saving money") . | Use neutral, respectful language for all options . |
| **Bait and Switch** | A harmless-looking button triggers a different, serious action . | Ensure buttons do exactly what their labels say.30 |
| **Forced Continuity** | Auto-billing users after a free trial without adequate warning . | Provide timely reminders before any renewal . |
| **Tricky Wording** | Uses confusing language or double negatives to mislead ("Uncheck to opt out") . | Use simple, clear copy that leaves no room for misinterpretation . |
| **Misdirection** | Draws attention to one element to obscure another (e.g., hidden fees) . | Present all relevant information equally and upfront . |

Table 4: Dark Patterns and Ethical Repair Moves .

## **VIII. Multimodal AI and the Failure of Grounding**

As Semantic Intelligence is integrated into Multimodal Large Language Models (MLLMs), a new set of semiotic failure modes emerges. Retrieval-Augmented Generation (RAG) is increasingly used to provide authoritative context, but the introduction of external documents can lead to "visual blindness" and "positional bias".42

### **The Illusion of Success and Attentional Collapse**

Mechanical diagnoses of internal attention matrices reveal that RAG can actually "recorrupt" model generations.42

1. **Visual Blindness (Cross-Modal Dominance)**: The retrieved text can absorb the entire attention budget, leading the model to ignore explicit, ground-truth visual evidence.42 This is characterized by a systemic suppression of visual attention mass (M\_vis) and a decline in visual attention sharpness (S\_vis).42  
2. **Positional Bias (The "Lost-in-the-Middle" Phenomenon)**: Models do not process retrieved text evenly, often showing an attention spike at the extreme boundaries (the first or last segments) of the text sequence.42 This can force the model to copy text from these positions rather than performing grounded reasoning.42

### **Repair Mechanisms: BAIR and Structured Input**

To mitigate these failures, several inference-time interventions have been proposed.

* **BAIR (Bottleneck Attention Intervention for Recovery)**: This parameter-free framework restores visual saliency and applies position-aware penalties to textual distractors.42 By manipulating pre-softmax attention matrices, BAIR corrects recorrupted generations and restores multimodal grounding.42  
* **LaTeX-Structured Input**: Research has found that plain text extracted from PDFs often impairs MLLM performance due to attention dispersion.39 Using LaTeX-structured text alongside images can induce "structured attention patterns," directing the model to focus on semantically meaningful regions.39

## **IX. Accessibility and Provenance: The Semiotics of Inclusion and Trust**

The final layer of multimodal literacy concerns the ethical and technical standards that ensure meaning is accessible and verifiable.

### **The Semiotics of Accessibility**

Accessibility is a core pillar of ethical design, and by June 2025, compliance with standards like WCAG 2.1 Level AA or the European Accessibility Act (EAA) will be mandatory for many digital products.35

* **Alt Text vs. Captions**: Alternative text (alt text) is a written description of an image for those who cannot see it, representing the contextually relevant aspects of the image itself.31 Captions provide additional context but do not replace the visual description.35  
* **Informative vs. Decorative**: Descriptive alt text for an informative image is a requirement.31 However, adding descriptive alt text to a decorative image (only for atmosphere) creates unnecessary noise; such images should use an empty alt attribute (alt="") so screen readers skip them.33

### **Content Provenance and the C2PA Trust Model**

In the age of synthetic media, the "semiotics of authenticity" requires verifiable provenance signals.4 The Coalition for Content Provenance and Authenticity (C2PA) provides a technical framework for securely attaching information about the history of digital content .

* **Content Credentials**: C2PA attaches a "manifest" to digital files, containing cryptographically signed details about origin and modifications.4  
* **Progressive Disclosure**: To avoid overwhelming users, C2PA recommends a tiered disclosure system.21

| Disclosure Level | UI Component | Semiotic Function |
| :---- | :---- | :---- |
| **Level 1 (L1)** | Content Credentials Mark (Icon/Logo).21 | Signals that provenance data is present and validated.21 |
| **Level 2 (L2)** | Provenance Summary.21 | Shows the signing entity, claim generator, and date.21 |
| **Level 3 (L3)** | Detailed Display.21 | Provides the full manifest, ingredient list, and edit history.21 |
| **Level 4 (L4)** | Forensic View.21 | Displays granular details for sophisticated investigatory usage.21 |

Table 5: C2PA Progressive Disclosure Tiers.21

## **X. What Report J Gives the Canon**

Report J completes Volume II by anchoring semantic intelligence in the material world of multimodal design. Meaning is no longer an abstract linguistic construct; it is an ensemble of coordinated signifiers that shape the human (and artificial) experience of reality.

1. **The Multimodal Literacy Layer**: The canon now possesses the toolkit to read across modes—identifying how a camera angle interacts with a typographic choice, or how a diagrammatic layout optimizes cognitive efficiency.10  
2. **The Discipline of the Warrant**: By integrating Tufte’s principles and the C2PA provenance standard, the canon establishes a rigorous boundary for truth-value in visual and synthetic media.7  
3. **Embodied and Agentic Grounding**: The connection between gesture, prosody, and multimodal AI grounding ensures that semantic intelligence remains responsive to both biological realities and silicon-based failure modes.42  
4. **Operational Repair**: The report provides a systematic taxonomy of multimodal failure (from dark patterns to attentional collapse) and its corresponding repair moves (BAIR, ethical UX, structured input).42

In sum, Report J establishes that meaning is never "trapped" in words. It is arranged, seen, heard, clicked, touched, and navigated. Multimodal literacy is the ability to read the designed world not as a mirror of reality, but as a motivated, symbolic construction that directs the path of intelligence .

#### **Works cited**

1. Reading Images: The Grammar of Visual Design \- 3rd Edition \- Gunther K \- Routledge, accessed May 14, 2026, [https://www.routledge.com/Reading-Images-The-Grammar-of-Visual-Design/Kress-Leeuwen/p/book/9780415672573](https://www.routledge.com/Reading-Images-The-Grammar-of-Visual-Design/Kress-Leeuwen/p/book/9780415672573)  
2. Typography Design \- A Guide \- Adobe, accessed May 14, 2026, [https://www.adobe.com/creativecloud/design/discover/typography.html](https://www.adobe.com/creativecloud/design/discover/typography.html)  
3. Verifying Provenance of Digital Media: Why the C2PA Specifications Fall Short \- arXiv, accessed May 14, 2026, [https://arxiv.org/html/2604.24890v1](https://arxiv.org/html/2604.24890v1)  
4. C2PA for more transparency and trust in digital media \- Media and Learning Association, accessed May 14, 2026, [https://media-and-learning.eu/type/tools/c2pa-for-more-transparency-and-trust-in-digital-media/](https://media-and-learning.eu/type/tools/c2pa-for-more-transparency-and-trust-in-digital-media/)  
5. Social Semiotics | Glossary of multimodal terms \- WordPress.com, accessed May 14, 2026, [https://multimodalityglossary.wordpress.com/social-semiotics/](https://multimodalityglossary.wordpress.com/social-semiotics/)  
6. Sergei Eisenstein: The man, the method, the montage \- Videomaker, accessed May 14, 2026, [https://www.videomaker.com/how-to/directing/film-history/sergei-eisenstein-the-man-the-method-the-montage/](https://www.videomaker.com/how-to/directing/film-history/sergei-eisenstein-the-man-the-method-the-montage/)  
7. Video: Edward Tufte | Background, Data Visualization & Principles \- Study.com, accessed May 14, 2026, [https://study.com/academy/lesson/video/edward-tufte-6-principles-of-graphical-integrity.html](https://study.com/academy/lesson/video/edward-tufte-6-principles-of-graphical-integrity.html)  
8. Tufte's 6 Principles for Graphical Integrity (Adopted for Service Design), accessed May 14, 2026, [https://internationalservicedesigninstitute.com/tuftes-6-principles-graphical-integrity-adopted-service-design/](https://internationalservicedesigninstitute.com/tuftes-6-principles-graphical-integrity-adopted-service-design/)  
9. Why a Diagram is (Sometimes) Worth Ten Thousand Words \- Semantic Scholar, accessed May 14, 2026, [https://www.semanticscholar.org/paper/Why-a-Diagram-is-(Sometimes)-Worth-Ten-Thousand-Larkin-Simon/b7bdd9331ed1ecbc931ccaf50c091cd0bb8b71b7](https://www.semanticscholar.org/paper/Why-a-Diagram-is-\(Sometimes\)-Worth-Ten-Thousand-Larkin-Simon/b7bdd9331ed1ecbc931ccaf50c091cd0bb8b71b7)  
10. Kress and van Leeuwen's Visual Grammar \- The Comm Spot, accessed May 14, 2026, [https://thecommspot.com/communication-basics/communication-theories/kress-and-van-leeuwen-visual-grammar-definition-examples-and-key-concepts/](https://thecommspot.com/communication-basics/communication-theories/kress-and-van-leeuwen-visual-grammar-definition-examples-and-key-concepts/)  
11. READING IMAGES \- THE GRAMMAR OF VISUAL DESIGN \- VNU Journal of Science, accessed May 14, 2026, [https://js.vnu.edu.vn/FS/article/view/4217/3931](https://js.vnu.edu.vn/FS/article/view/4217/3931)  
12. Dark Patterns in UI/UX Design. Dirty Secrets of Growth Hacking \- molfar.io, accessed May 14, 2026, [https://www.molfar.io/blog/dark-patterns](https://www.molfar.io/blog/dark-patterns)  
13. The Cognitive Design of Tools of Thought \- ResearchGate, accessed May 14, 2026, [https://www.researchgate.net/publication/273501468\_The\_Cognitive\_Design\_of\_Tools\_of\_Thought](https://www.researchgate.net/publication/273501468_The_Cognitive_Design_of_Tools_of_Thought)  
14. Proxemics 101: Understanding Personal Space Across Cultures | The MIT Press Reader, accessed May 14, 2026, [https://thereader.mitpress.mit.edu/understanding-personal-space-proxemics/](https://thereader.mitpress.mit.edu/understanding-personal-space-proxemics/)  
15. David Bordwell, accessed May 14, 2026, [https://ochre.lib.uchicago.edu/ochre?uuid=948d2612-c745-4a15-8e35-3b72878dc4a7\&load](https://ochre.lib.uchicago.edu/ochre?uuid=948d2612-c745-4a15-8e35-3b72878dc4a7&load)  
16. Tufte's 6 Principles for Graphical Integrity | Chartbuddy, accessed May 14, 2026, [https://chartbuddy.io/blog/tuftes-principles-for-graphical-integrity](https://chartbuddy.io/blog/tuftes-principles-for-graphical-integrity)  
17. Helvetica \- Wikipedia, accessed May 14, 2026, [https://en.wikipedia.org/wiki/Helvetica](https://en.wikipedia.org/wiki/Helvetica)  
18. Mastering Tufte's Data Visualization Principles \- GeeksforGeeks, accessed May 14, 2026, [https://www.geeksforgeeks.org/data-visualization/mastering-tuftes-data-visualization-principles/](https://www.geeksforgeeks.org/data-visualization/mastering-tuftes-data-visualization-principles/)  
19. The Cognitive Design of Tools of Thought Barbara Tversky, accessed May 14, 2026, [https://hci.ucsd.edu/220/TverskyCogtiveDesign.pdf](https://hci.ucsd.edu/220/TverskyCogtiveDesign.pdf)  
20. Cognitive Design Principles for Visualizations: Revealing and Instantiating, accessed May 14, 2026, [https://www.tc.columbia.edu/faculty/bt2158/faculty-profile/files/plesforvisualization\_Revealingandinstantiating.PDF](https://www.tc.columbia.edu/faculty/bt2158/faculty-profile/files/plesforvisualization_Revealingandinstantiating.PDF)  
21. C2PA User Experience Guidance for Implementers :: C2PA ..., accessed May 14, 2026, [https://spec.c2pa.org/specifications/specifications/2.0/ux/UX\_Recommendations.html](https://spec.c2pa.org/specifications/specifications/2.0/ux/UX_Recommendations.html)  
22. Why a Diagram is (Sometimes) Worth Ten Thousand Words, accessed May 14, 2026, [https://mechanism.ucsd.edu/bill/teaching/F12/cs200/Readings/larkin.whyadiagramissometimesworth.1987.pdf](https://mechanism.ucsd.edu/bill/teaching/F12/cs200/Readings/larkin.whyadiagramissometimesworth.1987.pdf)  
23. The Cognitive Science of Good Diagramming Innovation & Insights \- Diligent Rocket, accessed May 14, 2026, [https://www.diligentrocket.com/insights/the-cognitive-science-of-good-diagramming](https://www.diligentrocket.com/insights/the-cognitive-science-of-good-diagramming)  
24. An exploration of the editing cut as an articulator in film through frequency domain analysis of spectator EEGs \- PMC, accessed May 14, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12267235/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12267235/)  
25. A PSYCHOLINGUISTIC APPROACH1 \- McNeill Gesture Lab, accessed May 14, 2026, [https://mcneilllab.uchicago.edu/pdfs/gesture.a\_psycholinguistic\_approach.cambridge.encyclop.pdf](https://mcneilllab.uchicago.edu/pdfs/gesture.a_psycholinguistic_approach.cambridge.encyclop.pdf)  
26. 9 Dark Pattern Examples to Look Out For | Osano, accessed May 14, 2026, [https://www.osano.com/articles/dark-pattern-examples](https://www.osano.com/articles/dark-pattern-examples)  
27. The Past, Present and Future of Helvetica | The Latest Print and Design News | Solopress, accessed May 14, 2026, [https://www.solopress.com/blog/print-inspiration/the-past-present-and-future-of-helvetica/](https://www.solopress.com/blog/print-inspiration/the-past-present-and-future-of-helvetica/)  
28. Right place, right time: The complicated legacy of Helvetica, one of the world's most iconic typefaces \- Monotype, accessed May 14, 2026, [https://www.monotype.com/resources/articles/complicated-legacy-helvetica](https://www.monotype.com/resources/articles/complicated-legacy-helvetica)  
29. Dark Patterns: When Design Crosses the Line | by UX Magazine \- Medium, accessed May 14, 2026, [https://uxmag.medium.com/dark-patterns-when-design-crosses-the-line-0539b7d527f2](https://uxmag.medium.com/dark-patterns-when-design-crosses-the-line-0539b7d527f2)  
30. Dark Patterns in UX/UI Design and How to Avoid Them (22 Examples) \- Medium, accessed May 14, 2026, [https://medium.com/@arounda.agency/dark-patterns-in-ux-ui-design-and-how-to-avoid-them-22-examples-964e5cb0eb86](https://medium.com/@arounda.agency/dark-patterns-in-ux-ui-design-and-how-to-avoid-them-22-examples-964e5cb0eb86)  
31. Accessibility: Alt Text \- Geological Society of America, accessed May 14, 2026, [https://www.geosociety.org/GSA/GSA/Pubs/alternative-text.aspx](https://www.geosociety.org/GSA/GSA/Pubs/alternative-text.aspx)  
32. 18 Dark Patterns Examples That Manipulate Users (and How to Avoid Them) \- Eleken, accessed May 14, 2026, [https://www.eleken.co/blog-posts/dark-patterns-examples](https://www.eleken.co/blog-posts/dark-patterns-examples)  
33. Alternative Text (Alt Text) | Visual Identity \- Columbia University, accessed May 14, 2026, [https://visualidentity.columbia.edu/content/alternative-text-alt-text-0](https://visualidentity.columbia.edu/content/alternative-text-alt-text-0)  
34. (PDF) Design-Data Intelligence: Microhistories and Diagrammatic Reasoning, accessed May 14, 2026, [https://www.researchgate.net/publication/312153620\_Design-Data\_Intelligence\_Microhistories\_and\_Diagrammatic\_Reasoning](https://www.researchgate.net/publication/312153620_Design-Data_Intelligence_Microhistories_and_Diagrammatic_Reasoning)  
35. Provide Alt Text for Images – Marketing & Communications | Texas A\&M University, accessed May 14, 2026, [https://marcomm.tamu.edu/accessibility/provide-alt-text-for-images/](https://marcomm.tamu.edu/accessibility/provide-alt-text-for-images/)  
36. Alt text and digital accessibility: how it works | Eye-Able, accessed May 14, 2026, [https://eye-able.com/blog/ai-accessibility-how-organizations-create-inclusive-digital-experiences](https://eye-able.com/blog/ai-accessibility-how-organizations-create-inclusive-digital-experiences)  
37. Dark Patterns: 12 Deceptive UX Designs to Avoid | CorsoUX, accessed May 14, 2026, [https://courseux.com/dark-patterns/](https://courseux.com/dark-patterns/)  
38. How Alt Text Accessibility Supports Low-Vision Users, accessed May 14, 2026, [https://beaccessible.com/post/alt-text-accessibility/](https://beaccessible.com/post/alt-text-accessibility/)  
39. Structured Attention Matters to Multimodal LLMs in Document Understanding | OpenReview, accessed May 14, 2026, [https://openreview.net/forum?id=3OnJAvuxd3](https://openreview.net/forum?id=3OnJAvuxd3)  
40. Larkin & Simon: Why a diagram is (sometimes) worth ten thousand words \- Jim Davies, accessed May 14, 2026, [http://www.jimdavies.org/summaries/larkin1987.html](http://www.jimdavies.org/summaries/larkin1987.html)  
41. Helvetica \- Swiss Modernism's Ubiquity Crisis \- Learn That Yourself, accessed May 14, 2026, [https://learnthatyourself.com/helvetica-swiss-modernism-ubiquity-crisis/](https://learnthatyourself.com/helvetica-swiss-modernism-ubiquity-crisis/)  
42. The Cost of Context: Mitigating Textual Bias in Multimodal Retrieval-Augmented Generation, accessed May 14, 2026, [https://arxiv.org/html/2605.05594v1](https://arxiv.org/html/2605.05594v1)

---