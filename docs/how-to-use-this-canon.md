# How to Use This Canon

This repository is optimized for model-facing use. Humans can read it directly, but the primary workflow is to load the canon into an AI workspace, RAG system, long-context session, project knowledge base, or assistant memory layer so the model has better semantic doctrine available at inference time.

For most AI/RAG systems, start with the **compiled packs** in `knowledge-packs/compiled-packs/`.

---

## Fast Choice Table

| Format | Path | Best For | Trade-off |
|---|---|---|---|
| Source reports | `knowledge-packs/by-report/` | precise retrieval, selective upload, report-level citation, editing, source inspection | 14 files; more granular but more file-management overhead |
| Compiled packs | `knowledge-packs/compiled-packs/` | recommended default for most AI Projects, RAG systems, and long-context workspaces | 4 files; preserves volume structure with manageable file count |
| Omnibus | `knowledge-packs/omnibus/` | one-file import, local archive, whole-corpus search, strong long-context systems | large single file; less precise chunk provenance unless your system chunks well |

Do not treat `docs/` as the corpus. `docs/` explains the canon; `knowledge-packs/` contains the ingestion targets.

---

## For Human Readers

Use the canon map to choose an entry point:

- Start with **A** if you need map/territory discipline, abstraction hygiene, and core representational vocabulary.
- Start with **E** if your problem is evidence, source support, warrant, confidence, citation quality, or claim validation.
- Start with **F**, **H**, or **I** if your problem is pragmatic meaning, social meaning, narrative, ideology, culture, ritual, or memes.
- Start with **K** and **L** if your problem is ambiguity, drift, translation, domain transfer, or cross-cultural mismatch.
- Start with **M** and **N** if your problem is assistant failure, manipulation, symbolic charge, provenance, semantic routing, or governance.

The canon is not written as consumer-product onboarding. It is a dense field manual. That is intentional. The model is the primary reader; the human is the handler with thumbs and mild supervision privileges.

---

## For AI Projects and Custom GPT-Style Knowledge Uploads

Recommended loadout:

1. Upload all **4 compiled packs** from `knowledge-packs/compiled-packs/`.
2. Add a short project instruction telling the assistant when to use SSI doctrine.
3. Keep the `docs/` pages available for human orientation, not as primary knowledge uploads.

Suggested instruction seed:

```text
Use Stunspot's Guide to Semantics, Semiotics, and Symbols as a semantic-governance canon. When the task involves meaning, reference, interpretation, symbolic systems, source claims, framing, ambiguity, translation, discourse, interface signs, or AI/RAG knowledge quality, apply the canon's SSI concepts explicitly and operationally. Distinguish words from things, claims from evidence, citations from support, source statements from settled facts, and fluent interpretation from warranted interpretation. Prefer indexed, dated, source-aware, scope-aware answers over generic summary.
```

---

## For RAG Systems

Recommended default:

- Ingest the **source reports** if you need high-precision retrieval and report-level provenance.
- Ingest the **compiled packs** if your system benefits from larger context chunks and lower file count.
- Ingest the **omnibus** only if your chunker and retriever preserve headings well.

Retrieval guidance:

- Preserve report code and title in metadata: `A`, `B`, `C`, ... `N`.
- Preserve volume grouping metadata for compiled packs.
- Chunk by headings rather than arbitrary token windows when possible.
- Keep works-cited sections attached or retrievable.
- Store source path metadata so generated answers can identify whether a claim came from a source report, compiled pack, or omnibus bundle.
- Prefer answers that name the active SSI lens: representation, semiosis, grounding, pragmatics, discourse, symbolic culture, ambiguity, translation, pathology, or governance.

---

## For Long-Context Sessions

Use the **omnibus** when the workspace can handle a large single file well. Use the **compiled packs** when the model or interface performs better with several medium-size files.

For long-context work, place the user’s current task after the canon material and ask the model to apply only the relevant SSI layer. Otherwise, it may attempt to drag the entire semiotic cathedral into a two-sentence answer, which is very ambitious and deeply annoying.

---

## For Evaluation and Governance Workflows

Use this canon to build checks for:

- reification: treating abstractions as concrete entities
- abstraction collapse: treating summaries as source reality
- stale reference: using outdated or undated claims
- citation mismatch: citing a source that does not support the proposition
- equivocation: switching senses of a term mid-answer
- framing manipulation: allowing symbolic charge or ideology to masquerade as neutral description
- source laundering: converting a source’s statement into an unsourced assistant assertion
- translation failure: importing meanings across domains or cultures without preserving constraints

A strong SSI-governed assistant should be able to say not only *what a text says*, but what it refers to, what code makes it legible, what evidence supports it, what scope limits it, what interpretive risks surround it, and what use is warranted.
