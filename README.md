# prooflens
A human-readable verification layer for AI decisions — turning claims, evidence, confidence, risks and inference metadata into a portable Decision Passport.


# ProofLens

## Verifiable AI Decision Passport

**Don't just trust the AI decision. Verify how it was made.**

ProofLens is a human-readable verification layer for AI decisions.

Instead of only showing an AI-generated answer, ProofLens turns an important AI decision into a **Decision Passport** containing:

- Input
- Claims
- Evidence
- Confidence
- Risks
- Model information
- Decision
- Timestamp
- Input fingerprint
- Verification status

The goal is simple:

> AI should not only give answers.  
> The next person should also be able to understand and verify how that decision was produced.

---

## The Problem

AI systems can already summarize documents, review proposals, assess risks, recommend actions, and support business decisions.

But when an AI-generated decision is passed to another person, organization, or AI Agent, important context is often lost.

The next recipient may not know:

- What information the AI actually received
- Which statements were facts and which were inference
- Which model produced the result
- Whether the claimed inference service was actually used
- Whether the original input was modified
- How confident the AI was
- Which important evidence was missing
- Whether the AI Agent really performed the task it claimed to perform

As AI Agents begin to participate in economic activity, partnerships, grants, research, procurement, and other decision workflows, **“just trust the AI” is no longer enough.**

---

## The Solution

ProofLens converts an AI-assisted decision into a portable **Decision Passport**.

The system separates:

**Claims**  
What the source is saying.

**Evidence**  
What information supports the claim.

**Inference**  
What the AI concludes from the available information.

**Risk**  
What remains unclear or unsupported.

**Decision**  
What action or recommendation the AI proposes.

**Verification**  
Metadata showing how this particular decision was produced.

This creates a decision record that another person or Agent can inspect instead of receiving only a final answer.

---

# Decision Passport

A ProofLens Decision Passport can contain:

```text
Decision ID
PL-26-0904-A72F

Input Fingerprint
8f82a1...

Model
AI Model / 0G Model

Inference Provider
Verifiable AI Infrastructure

Decision
NEEDS HUMAN REVIEW

Confidence
68%

Verification Status
VERIFIED / NOT VERIFIED

Timestamp
2026-09-04 10:42:31
