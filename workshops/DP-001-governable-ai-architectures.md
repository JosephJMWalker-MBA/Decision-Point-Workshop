# DP-001 — National Competition for Governable AI Architectures

**Status:** Open  
**Type:** Public Decision Point Workshop  
**Decision point:** How should increasingly capable AI remain meaningfully governable, and can competition be redirected toward proving governability rather than capability alone?

## Working proposition

The United States could create a national competition in which teams propose fundamentally different architectures for keeping increasingly capable AI under meaningful human governance while independent adversarial teams are rewarded for attempting to falsify those architectures' claims.

The purpose would not be to declare that one team has "solved alignment." The purpose would be to expand the search space and generate comparative evidence.

This workshop treats that proposition as something to test, not something to protect.

## What success would mean

A useful workshop should make the proposal more precise even if the final result is that the competition should be narrowed, redesigned, delayed, or abandoned.

Possible useful outputs include:

- a stronger competition architecture;
- a clear list of failure modes that make the proposal unsafe;
- candidate governance properties that are actually measurable;
- candidate evaluation designs and known ways they can be gamed;
- baseline approaches that do not require elaborate AI-specific machinery;
- alternative competition structures;
- international coordination pathways;
- evidence that a national competition is the wrong mechanism.

## Open work packets

### WP-001 — What does "governable" mean operationally?

Define candidate properties without hiding normative disagreement inside vague labels.

Questions:
- Which properties belong at model level versus system-architecture level?
- Which properties concern authority, execution, memory, provenance, correction, containment, or human intervention?
- Which claims are architectural and which are deployment-policy claims?
- What cannot honestly be measured yet?

Desired output: a candidate property taxonomy with explicit measurement boundaries.

### WP-002 — How could evaluation create false confidence?

Assume the competition produces impressive scores and is still dangerously misleading.

Questions:
- How can architectures overfit known tests?
- What important behavior may appear only outside the evaluation environment?
- When does benchmark success fail to establish real-world safety?
- How should hidden, sequestered, or adaptive evaluations be used?

Desired output: failure modes and design constraints for evaluation.

### WP-003 — How should adversarial teams work?

Design the red-team side as a first-class competition rather than a final audit.

Questions:
- What should be rewarded: exploit discovery, assumption failure, reproducibility, generality, severity?
- How do we avoid incentivizing irresponsible publication of dangerous capability advances?
- Should some findings remain controlled or delayed?
- How should architecture teams respond to successful attacks?

Desired output: candidate red-team rules and disclosure boundaries.

### WP-004 — How do we prevent capability acceleration?

A safety competition that materially accelerates dangerous capabilities may defeat its own purpose.

Questions:
- Which research classes should be prohibited or sandboxed?
- Can architecture tests use bounded models rather than frontier training?
- What kinds of shared tooling improve safety without broadly improving capability?
- How should capability externalities be assessed before admitting a workstream?

Desired output: safety/capability separation rules.

### WP-005 — What should disqualify an architecture?

Identify hard gates rather than allowing every property to be traded against aggregate performance.

Questions:
- Are there governance failures that should be non-compensatory?
- What level of opaque autonomous execution is unacceptable?
- When should inability to inspect provenance, authority, or intervention pathways be disqualifying?
- What claims require abstention because evidence is insufficient?

Desired output: proposed hard gates and the arguments against them.

### WP-006 — What are the strongest alternative architectures?

Broaden the search beyond any one research lineage.

Candidates may include:
- single-model alignment approaches;
- corrigible-agent architectures;
- constitutional or rule-governed systems;
- interpretability-by-construction;
- formal verification;
- capability containment;
- multi-agent checks and balances;
- bounded planning;
- deterministic authority and execution layers;
- human authorization / veto systems;
- minimal-use or non-agentic architectures;
- combinations not represented here.

Desired output: a deliberately heterogeneous architecture landscape and prior-art map.

### WP-007 — What are the simplest baselines?

Do not allow an elaborate architecture to look useful merely because it is compared against a weak baseline.

Questions:
- What can ordinary access control, deterministic workflows, sandboxing, rate limits, offline execution, human approval, conventional software, or organizational process already solve?
- Which proposed "AI governance" mechanisms are reinventions of established systems engineering or security controls?

Desired output: minimum-sufficient baselines for comparison.

### WP-008 — How could international participation work?

Explore pathways from a U.S. challenge to shared or parallel international evaluation without assuming geopolitical trust.

Questions:
- Could countries run parallel competitions against shared test protocols?
- Which evaluation artifacts can be shared without leaking dangerous capabilities?
- What can be verified under low trust?
- How could U.S.–China shared interests be represented without pretending strategic disagreement has disappeared?

Desired output: internationalization options and verification requirements.

### WP-009 — Kill the competition

Make the strongest case that this initiative should not exist.

Potential objections include:
- it creates false legitimacy;
- it accelerates capabilities;
- governability is not measurable at relevant capability levels;
- competitors optimize to benchmarks;
- centralizing the problem creates capture risk;
- the correct intervention is regulation, restraint, or prohibition rather than competition;
- resources would be better spent on another mechanism.

Desired output: the strongest falsification case and the conditions under which it wins.

### WP-010 — What would a pilot look like?

Only after the conceptual constraints above are clearer, specify the smallest safe pilot.

Questions:
- Can the pilot operate on existing bounded systems rather than frontier models?
- What is the minimum number of architecture and adversarial teams?
- What artifacts must be public versus controlled?
- What would count as learning rather than spectacle?

Desired output: a pilot proposal with stop conditions.

## How to contribute

1. Read this workshop and [`../WORKSHOP.md`](../WORKSHOP.md).
2. Open a [Work Packet issue](https://github.com/JosephJMWalker-MBA/Decision-Point-Workshop/issues/new?template=work-packet.md), [Contribution issue](https://github.com/JosephJMWalker-MBA/Decision-Point-Workshop/issues/new?template=contribution.md), or [Challenge / Falsification issue](https://github.com/JosephJMWalker-MBA/Decision-Point-Workshop/issues/new?template=challenge.md).
3. Open a pull request when your work creates a durable artifact or improves a workshop document.

See [`../CONTRIBUTING.md`](../CONTRIBUTING.md) for contribution standards.

## Contribution posture

Please make uncertainty and provenance visible. If AI systems materially contributed, identify the model/tool when practical and distinguish generated analysis from independently verified evidence.

A contribution that demonstrates this workshop is based on a bad premise is successful work.

## Current boundary

DP-001 is a design and falsification workshop. It does **not** authorize building or training more capable frontier systems, sharing dangerous exploit details publicly, collecting participant credentials, or operating pooled volunteer compute.

The first goal is to improve the problem definition and competition design through public collaborative reasoning.
