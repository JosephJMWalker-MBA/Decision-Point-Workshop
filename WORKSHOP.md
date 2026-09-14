# Decision Point Workshop

The Decision Point Workshop is DPI's lightweight public working layer for consequential problems.

It starts from a simple premise:

> Most people use human attention, expertise, AI systems, software, data, and compute independently. What happens when we deliberately organize some of that intelligence around one shared problem?

The workshop is not a general discussion forum. It is a place to produce inspectable work.

## Why start on GitHub

DPI does not need to build community software before a community exists.

GitHub already provides public version history, issues for bounded work, pull requests for durable artifacts, review around changes, contributor attribution, and enough structure to discover what custom tooling is actually missing.

If real collaboration later outgrows GitHub, contributors can help specify and build the next workshop layer from observed needs rather than imagined ones.

## The workshop loop

```text
DECISION POINT
→ EVIDENCE
→ UNKNOWNS
→ WORK PACKETS
→ PARALLEL CONTRIBUTIONS
→ CHALLENGE
→ SYNTHESIS
→ DECISION / PROPOSAL
→ REALITY
→ REASSESS
```

### 1. Decision point
State the consequential choice clearly enough that a contributor can understand what could still change.

### 2. Evidence
Collect relevant primary evidence, existing research, prior art, observations, constraints, and known facts.

### 3. Unknowns
Make uncertainty explicit. Identify missing evidence, contested assumptions, unresolved tradeoffs, and unknown failure modes.

### 4. Work packets
Decompose the problem into bounded questions that can be attacked independently or sequentially.

### 5. Parallel contributions
Where useful, let different people, disciplines, models, tools, or methods work on the same packet independently. Diversity is useful when it creates genuinely different error surfaces or ways of seeing the problem.

### 6. Challenge
Try to break claims, reproduce results, identify confounders, compare against simpler alternatives, and surface what a synthesis is hiding.

### 7. Synthesis
Connect contributions without erasing provenance, uncertainty, minority views, or unresolved contradictions.

### 8. Decision / proposal
Produce the best current proposal, decision support, architecture, experiment, or next action the evidence warrants.

### 9. Reality
When possible, test the output against the external world rather than treating internal coherence as success.

### 10. Reassess
Preserve what happened and identify what should be retained, revised, reopened, replicated, escalated, or abandoned.

## Intelligence pooling

The workshop treats intelligence as an ecology rather than as one model or one class of participant.

Useful resources may include:

- **human attention** — reading, checking, comparing, reasoning, and noticing;
- **domain expertise** — technical, scientific, legal, historical, operational, civic, ethical, or lived knowledge;
- **AI inference** — different hosted or local models used as bounded contributors;
- **software and code** — deterministic analysis, simulations, parsers, validators, and prototypes;
- **data and evidence** — public datasets, primary documents, measurements, and observations;
- **physical access** — field checks, experiments, local knowledge, and contact with reality;
- **criticism** — red teaming, replication, falsification, counterexamples, and baseline comparisons;
- **compute** — CPU, GPU, API, or cloud resources where a defined workload genuinely benefits from them.

No participant needs all of these. Someone with no compute can still make a decisive contribution. Someone with compute but no relevant question may contribute very little.

## Compute pooling: later, if earned

Earlier DPI-related work proposed collective compute pooling: public challenges, shared resources, open outputs, and recurring focus events. The workshop inherits the underlying idea but starts one layer earlier.

Version 0 tests whether intelligence can be coordinated usefully before DPI builds infrastructure for pooling machines.

A possible maturity path is:

```text
LEVEL 1 — Bring Your Own Intelligence
People use the humans, models, tools, data, and compute already available to them.

LEVEL 2 — Shared Credits
Sponsors or contributors make bounded API/cloud budgets available to explicit work packets with provenance and allocation rules.

LEVEL 3 — Volunteer Compute
Sandboxed, signed, reproducible workloads can run on contributed machines under explicit security and governance constraints.
```

Level 3 should not exist until there is evidence that the collaboration model needs it and a credible security design exists.

## Contribution object

When practical, preserve:

```text
Decision point:
Subproblem / work packet:
Claim, finding, or proposed result:
Evidence / sources:
Method:
Human contribution:
AI / model / tool used (if any):
Compute or other resources used (if material):
Uncertainty / confidence boundary:
Known weaknesses:
What would falsify or change this result:
Dependencies / related contributions:
Artifacts / links:
```

This is not intended to turn participation into paperwork. It exists so another contributor can inspect what happened instead of inheriting only a polished conclusion.

## What the workshop is not

The workshop is not a popularity contest for determining truth, a social feed optimized for engagement, a place where one AI model synthesizes everything into institutional truth, a promise that crowds are automatically wise, an excuse to collect private data or credentials, a substitute for accountable decision-makers, or a requirement that disagreement eventually collapse into consensus.

## Current workshop

**DP-001 — Design the strongest possible National Competition for Governable AI Architectures**

See [`workshops/DP-001-governable-ai-architectures.md`](workshops/DP-001-governable-ai-architectures.md).

## Future platform principle

The workshop software should grow only after the work demonstrates what GitHub cannot do well enough.

A future purpose-built system may eventually need better support for problem decomposition and dependency graphs, provenance-preserving synthesis, consensus/disagreement mapping, parallel model runs, shared compute or credit allocation, contributor expertise discovery, structured replication and red teaming, evidence lineage, and reality-feedback tracking.

Those are hypotheses, not a v0 feature list.
