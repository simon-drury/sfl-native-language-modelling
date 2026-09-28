# SFL-Native PhD Proposal Reader Content Ledger

## Status

Canonical page-level content dataset for the public GitHub Pages proposal reader.

This ledger records the substantive content contract for each page, its formal materials, visual objects, read-aloud vignette, source status, and outstanding fields. It supports reconstruction, review, and implementation without requiring manual recovery from prior chat material.

## Reader contract

- Public proposal repository: `simon-drury/sfl-native-language-modelling`
- Implementation repository: `simon-drury/sfl-meaning-matrix-llm`
- Core reader: a compact, navigable doctoral proposal with a front-map page and linked formal appendices
- Desktop vignette placement: right-hand marginal card
- Mobile vignette placement: inline card
- Formal materials: linked appendix pages containing rendered LaTeX, copyable LaTeX source, notation, algorithms, worked cases, citations, and source records
- Editorial control: `SFL-Native Editorial Style Guide`
- Visual mode: dark paired-colour reader using the established deep palette family; body text, contextual text, vignettes, and mathematical figures retain stable paired treatments

## Evidence classes

| Class | Meaning |
|---|---|
| Direct specification | User-authored requirement or architecture statement |
| Repository evidence | Inspected repository file, commit, data path, or public-reader material |
| Research proposal | Intended research method, test, or future investigation |
| Candidate or unresolved | Material requiring source verification or a user decision |

---

# Page 1: Document Map and Orientation

## Purpose

The front-map page is the first page of the proposal document. It establishes the reader route and prepares the reader to move through a formal doctoral proposal.

## Required content

- Proposal title.
- Concise doctoral proposition.
- A short map of the document’s movement through language as social semiotic, SFL-native preprocessing, meaning-state representation, trajectory, research design, evaluation, and appendices.
- Reader controls and route into the proposal.
- Direct links to the proposal repository and the implementation repository.

## Visual and interaction

- The document map is the primary visual object.
- The page functions as proposal orientation rather than decorative front matter.
- Include a compact orientation vignette.

## Source status

| Item | Class | Status |
|---|---|---|
| Front-map page as first document page | Direct specification | Established |
| Final title line | Candidate or unresolved | Requires final title selection |
| Concise doctoral proposition | Candidate or unresolved | Requires approved wording |
| Repository links | Repository evidence | Both repositories identified |

---

# Page 2: Research Problem and Contribution

## Purpose

State the doctoral problem and the contribution.

## Required content

- Meaning-making as an explicit object of computational representation, analysis, generation, and evaluation.
- The research contribution expressed through the project’s own representational and operational commitments.
- A concise account of why explicit meaning-state representation matters for the research programme.

## Visual and interaction

- One conceptual visual only where it improves orientation.
- Right-hand or inline read-aloud vignette.
- Link to terminology and notation material.

## Source status

| Item | Class | Status |
|---|---|---|
| Meaning-making as explicit computational object | Direct specification / repository evidence | Established as project framing |
| Final research question | Candidate or unresolved | Requires source-led formulation |
| Final contribution statement | Candidate or unresolved | Requires source-led formulation |
| Literature framing | Candidate or unresolved | Requires verified scholarly sources |

---

# Page 3: Language as Social Semiotic

## Purpose

Establish the theoretical foundation for the proposal.

## Required content

- Language as social semiotic.
- Ideational, interpersonal, and textual metafunctional organisation.
- Field, tenor, and mode as contextual or register variables.
- The relation between social context, meaning configuration, and realised language.
- The SFL-native position of the project.

## Visual and interaction

- A simple organisation visual.
- Stable paired colours distinguish metafunctional organisation from contextual configuration.
- Right-hand or inline read-aloud vignette.

## Source status

| Item | Class | Status |
|---|---|---|
| Metafunctions: ideational, interpersonal, textual | Direct specification | Established |
| Contextual/register variables: field, tenor, mode | Direct specification | Established |
| No fixed pairing imposed between the two sets | Direct specification | Established |
| Scholarly citations and page references | Candidate or unresolved | Requires verification |
| Final strata visual | Candidate or unresolved | Requires design asset |

---

# Page 4: SFL-Native Preprocessing and Encoding

## Purpose

Show how incoming language enters the project’s meaning-making environment.

## Required content

- The SFL-native preprocessing environment.
- Transformation into structured meaning-making representations.
- The role of contextual configuration and metafunctional organisation in establishing the input representation.
- The relation between preprocessing, GPU computation, and boundary realisation.

## Visual and interaction

- Figure: incoming language to SFL-native preprocessing to 3×3 meaning-state matrix.
- Figure-side vignette explains the transformation in reader-facing prose.
- Link to formal appendix material.

## Source status

| Item | Class | Status |
|---|---|---|
| Incoming language mapped into SFL-native meaning representations | Direct specification | Established |
| GPU computation over resulting meaning representations | Direct specification | Established |
| Exact encoding procedure | Candidate or unresolved | Requires formal specification |
| Worked input-to-matrix case | Candidate or unresolved | Requires selected example |
| Formal mapping function and algorithm | Candidate or unresolved | Requires source-led derivation |

---

# Page 5: Meaning-Making Matrix M0

## Purpose

Introduce the 3×3 matrix as the central formal visual object.

## Diagram title

Metafunctions Mapped Across Contextual Variables

## Required content

- Rows: ideational, interpersonal, textual.
- Columns: field, tenor, mode.
- Each cell records a mapped location within the current meaning-state configuration.
- The matrix is introduced through an explanatory visual before detailed formal notation.

## Visual and interaction

- Quadrant 1, upper-left: matrix M0.
- Quadrant 2, upper-right: row and column orientation.
- Quadrant 3, lower-left: meaning-state explanation.
- Quadrant 4, lower-right: read-aloud vignette and formal appendix link.

## Read-aloud vignette requirement

The vignette guides the reader across rows and down columns, explains the distinction between metafunctional organisation and contextual configuration, and explains the nine mapped locations as the current meaning-state configuration.

## Source status

| Item | Class | Status |
|---|---|---|
| 3×3 presentation | Direct specification | Established |
| Matrix title | Direct specification | Established |
| Row and column labels | Direct specification | Established |
| Final cell notation | Candidate or unresolved | Requires final notation decision |
| Exact cell semantics | Candidate or unresolved | Requires formal definition |
| Worked M0 matrix | Candidate or unresolved | Requires selected case |
| LaTeX source and appendix definition | Candidate or unresolved | Requires formal apparatus |

---

# Page 6: Meaning Trajectory from M0 to M1

## Purpose

Make structured change between related meaning-state configurations visible.

## Required content

- Meaning trajectory.
- Delta as a structured change across related states.
- The relation between the nine mapped dimensions and the transition from M0 to M1.
- A reader-facing explanation before formal trajectory notation.

## Visual and interaction

- Initial matrix begins in the upper-left region.
- Subsequent configuration appears toward the lower-right region.
- The figure displays the structured relationship between the nine mapped dimensions.
- The visual route makes the measured delta visible across the configuration.

## Formal notation status

Current notation placeholder:

```latex
\Delta M_{0 \rightarrow 1} = M_1 - M_0
```

This is a notation placeholder. It remains subject to the final formal specification and may be revised without changing the page role or diagram sequence.

## Source status

| Item | Class | Status |
|---|---|---|
| M0 to M1 trajectory concept | Direct specification | Established |
| Delta between related meaning states | Direct specification | Established |
| Final delta notation | Candidate or unresolved | Requires formal decision |
| Formal definition of trajectory | Candidate or unresolved | Requires derivation |
| Worked trajectory | Candidate or unresolved | Requires selected case |
| Figure caption, alt text, and appendix derivation | Candidate or unresolved | Requires formal apparatus |

---

# Page 7: Computational Architecture and Implementation Record

## Purpose

Connect the research architecture to implementation evidence.

## Required content

- GPU computation over SFL-native meaning representations.
- Meaning-state configurations, trajectories, and deltas as computational objects.
- Boundary realisation.
- Direct link to `simon-drury/sfl-meaning-matrix-llm`.
- Visible distinction between direct specification, inspected repository evidence, research proposal, and unresolved candidate material.

## Visual and interaction

- Clear architecture-flow figure.
- Academically labelled repository evidence routes.
- Right-hand or inline read-aloud vignette.

## Source status

| Item | Class | Status |
|---|---|---|
| Separate implementation repository | Repository evidence | Established |
| GPU computation over meaning representations | Direct specification | Established |
| Specific code and data behaviour | Repository evidence | Requires direct source inspection |
| Boundary-realisation account | Candidate or unresolved | Requires approved formal statement |
| Architecture-flow figure | Candidate or unresolved | Requires source-led design |

---

# Page 8: Research Design and Evaluation

## Purpose

Set out how the research studies and tests the architecture.

## Required content

- Corpus-grounded analysis.
- Controlled generation tasks.
- Human linguistic judgement.
- Error analysis.
- Dataset provenance and annotation logic.
- Clear distinction between proposed research design and completed empirical results.

## Visual and interaction

- Research-design figure.
- Small evidence-class key.
- Read-aloud vignette explaining how a claim becomes testable.

## Source status

| Item | Class | Status |
|---|---|---|
| Evaluation modes named in existing proposal reader | Repository evidence | Established as page wording |
| UAM-related annotation and provenance priority | Direct specification | Established as research requirement |
| Confirmed dataset inventory | Candidate or unresolved | Requires audited dataset record |
| Licences, access routes, sizes, and references | Candidate or unresolved | Requires verification |
| Final experimental configuration and measures | Candidate or unresolved | Requires research-design specification |

---

# Page 9: Research Programme and Repository Record

## Purpose

Connect the doctoral proposal to a durable research programme.

## Required content

- Contribution to research in SFL, computational linguistics, AI, and language modelling.
- Public proposal repository.
- Implementation repository.
- Formal research record and citation metadata.
- Research programme statement.

## Visual and interaction

- Minimal repository map.
- Clear hyperlinks to research artefacts.
- No corporate showcase material.

## Source status

| Item | Class | Status |
|---|---|---|
| Proposal and implementation repositories | Repository evidence | Established |
| Final programme statement | Candidate or unresolved | Requires approved wording |
| Repository descriptions | Repository evidence | Requires direct source inspection |
| Citation and reproducibility information | Candidate or unresolved | Requires audited metadata |

---

# Page 10: References and Appendix Access

## Purpose

Provide scholarly traceability and routes into formal depth.

## Required content

- Verified references.
- Quotation register.
- Appendix map.
- Links to each formal appendix page.
- Citation and source-record policy.

## Visual and interaction

- Minimal formal-access map.
- Clear return paths from every appendix to its originating reader page.

## Source status

| Item | Class | Status |
|---|---|---|
| Formal appendices paired with reader-facing vignettes | Direct specification | Established |
| Verified bibliography | Candidate or unresolved | Requires source verification |
| Exact quotations, editions, and page references | Candidate or unresolved | Requires quotation register |
| Appendix contents | Candidate or unresolved | Requires formal content development |

---

# Formal Appendix Register

| Appendix | Required content | Linked reader page |
|---|---|---|
| A. Terminology and Notation Register | Definitions, notation rules, symbol index | 2–10 |
| B. SFL Organisation and Representational Definitions | Metafunctional and contextual-variable definitions | 3 |
| C. SFL-Native Preprocessing | Formal transformation procedure and worked encoding case | 4 |
| D. Meaning-Making Matrix | Rendered matrix, LaTeX, cell definitions, worked M0 case | 5 |
| E. Meaning Trajectories and Deltas | M0 to M1, delta definition, formal examples | 6 |
| F. Computational Operations | Algorithms, functions, implementation-evidence routes | 7 |
| G. Research Design and Evaluation | Data, annotation, procedures, evaluation logic | 8 |
| H. Repository Evidence and Reproducibility | Paths, commits, artefacts, evidence status | 9 |
| I. Quotations and Source Register | Verified quotations, editions, pages, source status | 10 |

## Implementation rule

Each public reader page receives:

1. Main proposal prose.
2. One purposeful visual object where it improves comprehension.
3. A read-aloud vignette: right-hand marginal card on desktop and inline card on mobile.
4. An explicit formal-appendix link where relevant.
5. Evidence-class discipline for all substantive claims.
6. Return routes that preserve the reader’s navigation position.

## Dataset use

This file is the canonical content contract for the proposal reader. It supports source recovery, page construction, appendix construction, static preflight, and future revision without reconstructing the public document from chat history.