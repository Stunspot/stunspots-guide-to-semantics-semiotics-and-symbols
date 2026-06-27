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