NCS Message Validity Rules v0.1
Purpose

Define the minimum conditions required for a message to participate in collective reasoning.

✅ A message is VALID if ALL conditions are satisfied

Identity is defined
The message specifies an agent id and role.

Decision target exists
The message references a specific decision.

Intent is explicit
The message declares its action (propose, critique, support, reject, revision).

Position is clear
A core statement is provided.

Justification exists
At least one argument contains reasoning.

Responsibility is acknowledged
Risks or impact evaluation are present.

Coordination signal is provided
The message indicates support, revision request, or blocking.

❌ A message is INVALID if ANY condition occurs

Anonymous reasoning
No agent identity.

Undefined decision scope
Message does not target a specific decision.

Opinion without reasoning
Claim exists without justification.

Pure natural language without structure
Unstructured text only.

No risk awareness
No consequences considered.

Contradictory coordination signal
Message both supports and blocks.

Missing intent
System cannot determine message function.

System Behavior

Invalid messages must be rejected from the decision process.
They may be archived but cannot influence consensus.

Status: Draft
Scope: Foundational Rule