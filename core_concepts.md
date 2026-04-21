# Core Concepts: Onto Protocol 💎

This document defines the foundational semantic entities used within the **Onto Protocol** and the **CIOS** ecosystem.

## 1. Intent (The Goal)
**Intent** is the high-level semantic definition of a user's goal. It is substrate-agnostic, meaning it describes *what* needs to be done, not *how* an LLM should phrase it.
* *Example:* "Organize a business trip to London" is an Intent.

## 2. Policy (The Boundaries)
**Policy** defines the constraints, ethical boundaries, and security rules that must be applied to an Intent. 
* *Role:* The Compliance Engine checks every action against these policies.
* *Example:* "Do not spend more than $500 per night on hotels."

## 3. Trace (The Evidence)
**Trace** (or Execution Trace) is the verifiable record of every atomic action taken by an AI agent.
* *Auditability:* Unlike standard chat history, a Trace links every output to a specific policy and intent, creating a "black box" record for AI.

## 4. Incident (The Deviation)
An **Incident** is triggered when an agent violates a Policy or when an external service failure (like the April 20 outage) occurs. 
* *Management:* All incidents are logged for post-mortem analysis and system refinement.

---
*v0.1 | Drafted for Week 1 (Genesis Phase)*
