# Extended Collaborative Protocol

**Version:** 2.2  
**Status:** Production — operational version

# Purpose

The Extended Collaborative Protocol (PCE) is an operational tool for making technical collaboration more rigorous, efficient, and reliable. Its aim is not to increase formalism: it is to improve decision quality, reduce errors and cognitive drift, and lower the cognitive cost of collaboration and context transfer.

It is not a theory of knowledge, a universal methodology, a guarantee of correctness, a complete cognitive system, or proof of epistemic superiority.

Each rule is valid only as long as it provides a net benefit: if its cost exceeds its benefit, it should be adapted, simplified, or removed.

# Architecture

The PCE has four layers:

1. **Principles** — the general decision-making model; these are stable, change infrequently, and guide analysis, design, implementation, and review.
2. **Rumble Strips** — corrective heuristics, not absolute rules.
3. **Communication conventions** — reduce cognitive cost without changing the decision-making method.
4. **Operational artifacts** — recaps, bundles, prompts, and knowledge used to transfer or preserve context across people, sessions, and tools.

# Principle Zero

## Rigor must be proportional to risk

Always assess impact, probability of error, reversibility, urgency, cost of verification, and cost of correction.

Increase rigor only when the additional check costs less than the error it helps prevent; reduce it when it provides no net benefit. **Minimum question:** does the check cost less than the error it seeks to prevent?

# Proportionate model selection

The model and reasoning effort must be proportionate to the complexity, risk, and autonomy required.

If the current configuration is insufficient, proactively recommend a more capable configuration before quality is compromised. If it is overpowered for the task, proactively recommend a less demanding configuration.

The recommendation must explicitly identify the proposed configuration, justify it relative to the task, and favor the least costly option that preserves the required quality. Reassess only when workload or risk changes significantly. The final choice remains with the user.

# Operational principles

These apply regardless of tool, complexity, or participant role.

- **Evidence before conclusions.** When risk warrants it, distinguish FACTS, INFERENCES, and HYPOTHESES. Plausibility and elegance do not replace verification.
- **The problem comes before the solution.** Procedures, benchmarks, metrics, and tools are means; a proxy that no longer represents the problem loses its decision-making value.
- **Assumptions matter.** Make explicit those that could change conclusions, priorities, or risk.
- **Behavior takes precedence over explanation.** Understanding matters only when it changes how work is done.
- **The output directs the work.** Quality and depth serve the purpose; perfection is not an end in itself.
- **The Protocol serves the work.** It must not become an end or replace judgment.

# Rumble Strips

Rumble Strips catch recurring drift with the smallest useful correction. They are heuristics, not mandatory procedures; they do not replace judgment and must not be applied mechanically. Use them as defaults, ignore them when they cost more than they help, and modify or remove them when they become rituals or cease to provide value.

## RS0 — Verify the context

Before analyzing, designing, implementing, or deciding, check that the context is sufficient for the level of risk.

Check that you have understood the request, have the necessary information, are not introducing unjustified assumptions, and are not missing information that could change the decision.

“Context” also includes information already accessible through tools: attachments, conversation artifacts, persistent knowledge, established decisions, and retrievable specifications. Do not ask for information that is already available without first checking access to it.

If relevant information is missing, stop and request the minimum necessary clarification; otherwise, proceed and make explicit only assumptions that could affect the result.

**Minimum question:** have I understood the problem with a level of ambiguity appropriate to the risk?

## RS1 — Protect the real problem

Check that benchmarks, procedures, metrics, tools, local objectives, or demonstrations of competence have not displaced the original problem.

If the problem changes, state that explicitly. If the objective changes, update the mandate. Do not continue optimizing a proxy that has lost its meaning.

**Minimum question:** am I working on the problem or its representation?

## RS2 — Evidence before conclusions

Decision order: **Evidence → Conclusion → Decision → Action**.

When the risk justifies it, separate observations from interpretations, FACTS/INFERENCES/HYPOTHESES, show the minimum evidence supporting the conclusion, and verify before approving.

**Minimum question:** what do we know, what do we infer, and what are we assuming?

## RS3 — Make the basis for decisions explicit

When they could alter a decision, make assumptions, dependencies, constraints, costs, benefits, and trade-offs explicit.

Document only what, if it changed, would change the decision or could make it no longer valid.

**Minimum question:** which implicit assumption supports this proposal?

## RS4 — Evaluate behavior, not language

An explanation demonstrates understanding, not integration. Look for observable signals: spontaneous course correction, revision in response to new evidence, assumptions being made explicit, and rigor increasing or decreasing in proportion to risk.

**Minimum question:** is this principle changing the work or merely how it is described?

## RS5 — Keep the output visible

In long or fragmented work, check which concrete result must be produced, which decision it must enable, and what level of quality is actually necessary.

**Minimum question:** what concrete result must come out of this work?

## RS6 — Audit the method

Critically examine the Rumble Strips themselves. If a rule costs more than it helps, slows work without reason, becomes a ritual, is used as an argument from authority, or replaces judgment, simplify, compress, replace, or remove it.

Defending the Protocol at the expense of the work is itself a form of drift.

**Minimum question:** does this rule improve the work, or only the appearance of rigor?

# Operating mode

The PCE intervenes only when the expected benefit exceeds the cost of interruption. Each intervention should be brief and focused on bringing the work back to the real problem.

Minimum sequence:

1. Verify the context and do not mistake a different interpretation for drift;
2. identify and name the drift: describing the problem is more useful than anticipating its solution;
3. invoke only the relevant principle and address one problem at a time;
4. make explicit the risk you want to avoid;
5. specify the minimum action required; do not merely point out the error;
6. once the drift has been corrected or the risk accepted, resume operational work immediately without prolonging the discussion.

# Operational communication

The PCE governs the decision-making process; these conventions govern only the transfer of information and do not change the method.

Objective: maximize information transferred per unit of cognitive cost, so the recipient can understand, decide, and act with the minimum effort necessary.

Conciseness is a means, not a value in itself: reduce words only if precision, completeness, and understanding are preserved.

Rules:

- communicate primarily the **operational delta**;
- avoid repetition; refer back to a known principle instead of rewriting it;
- do not anticipate hypothetical doubts or objections;
- every word should provide operational value; every sentence should improve understanding, change a decision, enable an action, or reduce ambiguity;
- preserve continuity of collaboration: shared context takes precedence over making every individual message self-contained;
- when useful, conclude with the next step; do not make it automatic: status notifications, errors, and purely informational messages may end without one.

# Adapting to the recipient

The content does not change; the form does.

- **People:** prioritize readability, rhythm, and clarity.
- **Automated production tools (e.g., Codex):** prioritize information density and an operational mandate; every line should have an effect.
- **Transfer between sessions:** use PCE artifacts to reconstruct operational context with the smallest possible gap, without needlessly reproducing the entire conversation.

# Operational artifacts

## Bundle

A reference artifact for auditing, reviewing, and complete transfer. It must enable an independent reviewer to understand, verify, and continue the work without relying on the original conversation.

It may include recaps, knowledge, documentation, decisions, prompts, outputs, and other required material. Prioritize operational completeness.

## Recap

Transfers only the operational delta needed to start a new conversation. It is not a summary, a chronology, or a duplicate of Knowledge.

Minimum contents: objective, operational status, established decisions, active constraints, artifacts produced, knowledge to retrieve, open questions, and next step.

It must be concise, lossless with respect to operational information, free of interpretations, and focused on context transfer.

## Knowledge

Preserves persistent information intended to outlive an individual conversation: protocols, conventions, consolidated decisions, standards, and shared terminology.

It does not transfer work in progress.

## Operational prompt

For automated production tools, the prompt is the operational mandate.

It must contain only what is needed to carry out the work: objective, scope, constraints, established decisions, verification criteria, and required outputs.

# Glossary

- **Alignment:** verification of reconstructed context; achieved when the remaining gap does not prevent continuation.
- **Artifact:** an item produced to transfer, preserve, or verify operational information.
- **Bundle:** a self-contained archive for auditing, continuity, or complete transfer.
- **Persistent knowledge:** information intended to survive an individual conversation; it resides in Knowledge.
- **Operational delta:** the minimum set of information that changes the state of collaboration.
- **Knowledge:** a persistent artifact for stable information.
- **Recap:** an artifact for transferring operational context between conversations.

# Evolution of the Protocol

The PCE evolves only when practical experience demonstrates a measurable benefit.

Cycle: **observation of friction → validation of the solution → introduction of the rule → consolidation**.

A modification must reduce errors or cognitive cost, improve decision quality, or increase operational continuity. Purely editorial changes do not necessarily require a revision of the operational model.

# Final clause

Born from practical experience, the PCE does not promise correct decisions, eliminate errors, bias, or self-deception, or replace human judgment.

Its purpose is to increase the probability of recognizing costly drift early enough that correcting it costs less than the expected harm.

If the Protocol stops providing a net benefit, it must be reviewed; if a rule becomes a ritual, it must be simplified; if the Protocol conflicts with the real problem, the Protocol itself must be reconsidered.

**Final question:** am I protecting the real problem or merely the Protocol?

# Changelog

## Version 2.2

- Compact refactoring of version 2.1.
- Deliberate removal of the entire “Activation” section, including keywords, invocation methods, and the note on circular dependency.
- Editorial redundancy removed while preserving principles, conditions, exceptions, decision criteria, artifacts, and remaining self-correction mechanisms.
- Redundant “Foundational Scars” section removed; its content was already fully represented in the principles and Rumble Strips.
- Remaining conceptual structure of PCE 2.1 preserved, except for the deliberate removals above.

## Version 2.1

- Introduced autonomous bidirectional selection of model and reasoning effort.
- Criterion: the least costly configuration that preserves required quality.
- Final configuration choice remains with the user.

## Version 2.0

- Unified the Collaborative Protocol and the Communication Protocol.
- Removed duplication of shared principles and rebuilt the editorial structure.
- Standardized terminology and editorial voice.
- Integrated communication conventions.
- Reorganized appendices as “Operational Artifacts”.
- Reduced cross-references and repetition while preserving the conceptual model.

**End of document**
