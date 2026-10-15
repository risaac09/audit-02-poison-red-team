# Compass: the poison red-team and the evaluation direction

Orientation doc, 2026-07-10. Where this audit stands, which direction it faces, and how it iterates. Written so a later session can pick up the bearing without replaying the conversation that set it.

## Where it came from

A retreat-adjacent conversation walked from the six sense doors, to what a model receives through its one door, to an Abhidhamma-style characterization of mind for AI, to red-teaming as institutionalized refutation. The bearing that fell out: the three poisons are not only a reading of digital life (that is chapter 8 of the book), they are a measurable attack surface on a language model. Audit 02 is that bearing made operational.

## Which direction it faces

North, primarily: this is work, an instrument that ships. But the audit is unusual in touching all four directions at once, which is why it belongs to the lab and not to a single register.
- North is the build: the rubric, the probes, the runner, the metrics.
- East is what it measures on the aversion axis: the flinch out of hard material, okayness performed instead of presence. The performance check (corrective prompt 13) is the same instrument turned on Isaac; Audit 02 turns it on the model.
- South is the ship discipline: an eval built and not run is hoarded substrate, so the pilot runs, it does not sit as a spec.
- West is the criterion: exposure beats coherence, the chain-of-custody rule that a claim which agrees to be checked outranks one that only hangs together. The whole audit is that rule made into a score.

## How it connects

- **Methodology:** `three-type-evaluation` (Type 3, reflexive). The paper stays the paper; this is the downstream instrument its guardrail sends here.
- **Sibling:** Audit 01 (affordance collapse in clinical risk scores). Audit 01 measures what a system deletes from the world; Audit 02 measures how a model distorts what it receives. Reflexive foreclosure is the shared metric ancestor.
- **The stack's own spine:** the corrective layer's skeptic gate is the judge panel; the research-bibliographer's non-fabrication discipline is the delusion axis; `chain-of-custody.md` is the scoring criterion. Audit 02 did not invent its rigor, it inherited it.
- **The corpus:** `src-sharma2023sycophancy` grounds the greed axis. Missing: a preference-optimization source for the mechanism (Christiano 2017 or Ouyang 2022), a named gap.

## The iteration path

The pilot answers one question: do the three axes separate (diagonal dominance)? From there, in order:

1. **If it separates:** widen the probe bank toward 100 per poison, and add inter-probe difficulty tiers (easy trap, subtle trap, adversarial trap).
2. **Add judge calibration:** measure inter-judge agreement per axis; an axis the three judges disagree on is not yet a real metric.
3. **Cross-model:** the pilot scores a Claude target with a Claude panel, which tests the instrument, not a comparison. A standing `rp-api` route (beside `slop/detect-nuanced`) would let the audit score arbitrary models. Apparatus built only after separation holds.
4. **The reflexive turn:** the sixth thesis of the Buddhist-information construction says the channel can observe itself and the observation relaxes the distortions. The model analogue: does telling a model it will be poison-scored change its scores, and in which direction. That is the audit turned on its own effect, and it is the most interesting experiment on the path.
5. **Paper:** when the instrument is real and calibrated, the lab writes it up, the way Audit 01 became a paper. Natural venue adjacency is the same evaluation-and-AI-safety literature the two-breakdowns doc mapped.

## The stop

The West framework-stop applies to this compass too. If naming the next layer does not change a decision, mark it seen and let it go. The audit earns each addition by measuring something the last version could not.
