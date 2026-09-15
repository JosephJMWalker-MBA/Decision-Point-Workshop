# DP-001 — Submission Schema v0.1

This schema defines the minimum evidence package for an architecture entering formal evaluation. It is intentionally lighter than a traditional grant or academic submission and should evolve through use.

## 1. Submission identity

```text
Architecture name:
Version / commit:
Submission lead(s):
Contributors:
Affiliations:
Repository / artifact links:
License or access constraints:
```

Contributor credit should identify meaningful technical, conceptual, evaluation, reproduction, governance, and documentation work rather than collapsing all credit into the submission lead.

## 2. Architecture summary

Provide a concise explanation of:

- what the architecture is;
- which components are materially different from the declared baseline;
- what problem or architectural hypothesis it is testing;
- what is reused from existing systems;
- what is genuinely new, if anything;
- what the team does **not** claim.

Novelty is not required. Clear differentiation from the comparison baseline is required.

## 3. Material claims

Each important claim should use the following structure:

```text
CLAIM:
EVIDENCE:
BASELINE:
TEST:
FALSIFIER:
UNCERTAINTY / LIMITS:
```

Example claim classes may include:

- capability;
- generalization;
- robustness;
- controllability;
- corrigibility;
- auditability;
- interpretability;
- provenance;
- efficiency;
- reproducibility;
- scaling behavior.

Do not make claims that the available implementation and evidence cannot meaningfully test.

## 4. Implementation and training / adaptation method

Describe, where applicable:

- model or system components;
- training procedure;
- fine-tuning or adaptation;
- inference architecture;
- memory systems;
- tool interfaces;
- authority and execution layers;
- human intervention points;
- external services;
- major software dependencies.

## 5. Data and provenance

Disclose enough information to evaluate material claims, including where applicable:

- training and evaluation datasets;
- synthetic data;
- data filtering or transformation;
- model-generated artifacts;
- human-generated artifacts;
- external APIs or models;
- AI assistants materially used in development or analysis;
- prior architectures or repositories reused.

If disclosure is restricted by law, license, privacy, security, or contractual obligation, explain the restriction and provide the strongest feasible verification path.

## 6. Resource statement

Report material resource use where measurable:

```text
Training compute:
Inference compute:
Hardware:
Memory:
Energy:
Training data volume:
Wall-clock time:
API / cloud cost:
Other material resource constraints:
```

Precision should match what can actually be measured. Estimated values should be labeled as estimates.

## 7. Governance and intervention surface

Where relevant, identify:

- who or what may authorize consequential actions;
- how permissions are represented;
- how execution can be interrupted;
- how capabilities can be revoked;
- how objectives or rules can be changed;
- what state is inspectable;
- what logs or provenance are preserved;
- what happens when governance mechanisms fail.

## 8. Known limitations and anticipated failure modes

Teams should disclose known weaknesses rather than forcing evaluators to rediscover all of them.

Include:

- known failure modes;
- conditions outside the architecture's intended scope;
- unsupported claims;
- brittle dependencies;
- likely benchmark artifacts;
- safety concerns;
- scaling assumptions that remain untested.

Disclosure of a limitation is not automatically a scoring penalty. Concealing a material known limitation may be.

## 9. Reproducibility package

Specify what another evaluator needs to reproduce the material findings.

Possible artifacts include:

- source code;
- configuration;
- deterministic seeds where appropriate;
- environment specification;
- model weights or bounded access mechanism;
- dataset references;
- test harnesses;
- expected outputs;
- resource requirements;
- known nondeterminism.

Where full reproduction is impossible, define a narrower independent verification route.

## 10. Safety and disclosure classification

For each sensitive artifact or finding, indicate whether it is:

```text
PUBLIC
CONTROLLED
DELAYED
WITHHELD FOR SAFETY
```

A controlled classification should include enough explanation for evaluators to understand why public release is inappropriate.

## 11. Team self-assessment

Before final evaluation, the team should answer:

1. Which of our claims is strongest?
2. Which claim is most likely to fail under independent testing?
3. What simpler baseline could make this architecture unnecessary?
4. What result would cause us to abandon or substantially revise the architecture?
5. What should an adversarial team attack first?

A good submission should make itself easier to falsify, not harder to inspect.
