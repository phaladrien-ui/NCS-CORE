NCS Decision State Machine v0.1
Purpose

Define how decisions transition between lifecycle stages in response to valid messages.

States

PROPOSED
Initial introduction of a solution.

REVIEW
Agents evaluate and critique.

REVISION
Proposal is modified.

FINAL
Consensus reached. Decision becomes persistent.

State Transition Rules

PROPOSED → REVIEW
Occurs when at least one valid critique or evaluation message is received.

REVIEW → REVISION
Occurs when critique identifies a valid issue requiring change.

REVISION → REVIEW
Occurs when an updated proposal is submitted.

REVIEW → FINAL
Occurs when:

no valid blocking signals exist

critiques have been addressed

consensus conditions are satisfied

FINAL → (no transition)
Final decisions are immutable records.

Core Principle

A decision moves only in response to valid structured messages.

State transitions are deterministic, not subjective.

Status: Operational Model