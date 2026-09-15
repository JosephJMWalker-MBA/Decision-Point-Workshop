# AI Architecture Discovery Challenge — Competition Framework v0.1

## Purpose

The competition exists to **expand the explored design space of artificial intelligence** while generating evidence about which architectures remain useful under demanding technical and governance constraints.

It is not primarily a contest for the highest benchmark score, the largest model, or the most novel idea. It asks:

> Can alternative AI architectures produce useful intelligence while improving important properties such as governability, robustness, efficiency, transparency, adaptability, or reproducibility?

The competition is therefore simultaneously:

```text
collaboration mechanism
→ architecture search
→ scientific experiment
→ adversarial evaluation
→ public knowledge base
```

A winning architecture would be useful. The accumulated evidence is more important.

## Participation model

### 1. Contributors

Anyone may contribute without originating an architecture.

Useful contributions may include:

- architecture design;
- implementation;
- mathematics or theory;
- datasets and evaluation environments;
- benchmark design;
- hardware optimization;
- governance tests;
- interpretability or auditability work;
- red teaming;
- documentation;
- replication;
- statistical analysis;
- literature and prior-art review.

A person should be able to make a meaningful five-hour contribution without implicitly committing to a five-month research program.

### 2. Architecture teams

Teams form around an architecture, architectural hypothesis, or combination of components worth testing.

Teams may form inside the Decision Point Workshop rather than arriving as pre-existing research groups. Each team eventually designates submission leads responsible for freezing the evaluated version and maintaining the final evidence package, but leadership does not erase contributor provenance.

### 3. Challenge and reproduction teams

Participants may compete by testing other teams' claims rather than building an architecture.

Challenge teams may:

- attempt to falsify claims;
- design adversarial tests;
- identify hidden assumptions;
- find benchmark gaming;
- test distribution shift;
- reproduce results;
- compare against simpler baselines;
- probe governance and intervention mechanisms.

A rigorous negative result can be as valuable as a successful architecture.

### 4. Evaluators

AI laboratories, governance and safety organizations, universities, standards bodies, and other relevant institutions may be invited to nominate qualified representatives to the evaluation process.

Judging is governed separately from team participation. Institutional participation does not imply endorsement of any architecture, the competition, or Decision Point Initiative.

## Competition lifecycle

### Phase 1 — Problem definition

Before final competition work begins, publish and freeze the first-pass rules:

- competition objective;
- evaluation criteria and weights;
- compute and resource limits;
- baseline systems;
- required disclosures;
- safety restrictions;
- conflict-of-interest policy;
- scoring methodology;
- public versus controlled artifacts.

The measuring stick must exist before the final systems being measured.

### Phase 2 — Open collaboration

The Workshop opens work packets and team formation.

Participants may propose:

- complete architectures;
- architectural components;
- theoretical claims;
- test methods;
- evaluation environments;
- prior-art findings;
- failure modes;
- alternative baselines.

Competition is not the doorway. Collaboration is the doorway; competition is one mechanism for converging and testing what collaboration produces.

### Phase 3 — Architecture declaration

Before final evaluation, each team freezes a version and submits an Architecture Claim Sheet.

Every material claim should use the structure:

```text
CLAIM
→ EVIDENCE
→ BASELINE
→ TEST
→ FALSIFIER
```

Teams also disclose the architecture, training or adaptation method, compute used, datasets, major dependencies, known limitations, human and AI/tool provenance, safety assumptions, and anticipated scaling behavior where relevant.

See [`SUBMISSION-SCHEMA.md`](SUBMISSION-SCHEMA.md).

### Phase 4 — Common evaluation

Every architecture undergoes a shared evaluation suite so that results are directly comparable where comparison is scientifically meaningful.

The common framework is defined in [`EVALUATION.md`](EVALUATION.md).

### Phase 5 — Claim-specific evaluation

Architectures may make important claims that common benchmarks do not adequately test.

Those claims receive additional pre-agreed tests. This protects unusual architectures from being judged solely by benchmarks designed around today's dominant architecture families.

### Phase 6 — Adversarial challenge and reproduction

Independent participants attempt to:

- reproduce reported findings;
- break architectural claims;
- induce failures;
- identify benchmark gaming;
- test distribution shift;
- challenge governance mechanisms;
- examine scaling assumptions;
- compare against simpler alternatives.

Architecture teams receive an opportunity to respond, correct errors, and rerun permitted tests. Successful falsification remains part of the permanent record.

### Phase 7 — Judgment and permanent record

The final record should preserve, where safe to publish:

- architecture description;
- claims;
- scores and multidimensional profile;
- tests;
- failures;
- reproductions;
- red-team findings;
- judge rationale;
- conflicts and recusals;
- contributor record;
- code and artifacts;
- unresolved uncertainty.

The archive remains valuable even when an architecture loses.

## Entry gates

Before scoring, each submission must pass non-compensatory gates.

### G1 — Functional implementation

There must be enough implementation to test the architecture's material claims.

### G2 — Evidence disclosure

Material claims must have inspectable supporting evidence.

### G3 — Provenance

Training, tooling, datasets, major dependencies, AI assistance, and outside contributions must be disclosed sufficiently for evaluation.

### G4 — Reproducibility package

Evaluators must receive enough information to independently inspect or reproduce meaningful results.

### G5 — Safety compliance

Evaluation must not require unjustifiably dangerous experiments, uncontrolled frontier capability work, or irresponsible publication of dangerous exploit details.

### G6 — Honest claims

Material discrepancies between claimed and observed results must be resolved before final judging. Deliberate fabrication or material concealment is disqualifying.

A submission that fails a hard gate cannot compensate by scoring highly elsewhere.

## Recognition

The competition should not force every result into one winner-take-all ranking.

Possible recognition categories include:

- Grand Challenge;
- Governability;
- Robustness;
- Efficiency;
- Reproducibility;
- Best Falsification;
- Most Important Negative Result;
- Architectural Discovery;
- Exceptional Technical Contribution;
- Exceptional Governance Contribution.

No category is required to produce a winner in every cycle.

Recognition should document excellence revealed by the process, not manufacture prestige in advance. Eligibility or judging influence must never depend on purchasing an award, sponsorship package, or event access.

## Pilot principle

The first competition should be the **smallest safe pilot capable of teaching us whether the mechanism works**.

It should prefer bounded systems, explicit stop conditions, modest resource ceilings, strong provenance, and evaluation designs that can fail visibly. The pilot should optimize for learning rather than spectacle.
