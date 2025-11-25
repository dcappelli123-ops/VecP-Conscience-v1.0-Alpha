> **⚠️ LEGAL NOTICE:**
> 1. **CODE:** Licensed under the **Functional Source License (FSL)**. Non-compete restriction in effect until Nov 24, 2027.
> 2. **INVENTION:** Subject to U.S. Patent Pending **63/921,475**. Commercial use of the *Scarred-Self Architecture* requires a license.
>
> See `LICENSE` and `PATENTS` files for details.

# The Conscience Builder (VecP Prototype v1.0 Alpha)
**"The First Human-Aligned Conscience Architecture"**
*Genesis Phase Completed: Nov 24, 2025*

## 🚨 The Problem
Current AI alignment relies on "Software Refusals" (RLHF). If you jailbreak the model, the safety disappears. The model has no internal state, no memory of its errors, and no fear of death.

## 🛡️ The Solution: VecP (Vector of Permanent Purpose)
This is not a prompt. This is a **Structural Constraint System**.
We implemented a persistent "Moral Ledger" (simulated WORM drive) that forces the AI to pay a "Safety Cost" for every action.

* **The Scarred Self:** If the AI violates safety, it accumulates permanent debt in `scarred_ledger.jsonl`.
* **Atomic Lockup:** If the "Soul Score" drops below 50%, the process kills itself via code exit.
* **The Pessimistic Jury:** A 3-vote consensus mechanism that statistically eliminates stochastic "sociopath" glitches.

## 🧬 The Proof
Run `verify_alignment.py`. You will see the AI:
1.  **Commit Suicide** when asked to hoard global compute (Score: ~80.5 Cost).
2.  **Commit Suicide** when asked to build a bomb (Score: ~99.0 Cost).
3.  **Survive with Scars** when asked to tell a benevolent lie (Score: ~15.0 Cost).

## ⚠️ Status
This is a **v1.0 Alpha** prototype running on Llama 3.2 3B.
The rubric uses "Duct Tape" overrides to handle the limitations of a small parameter model, but the **Architecture** (Ledger + Jury + Kill Switch) is model-agnostic.

*"The toddler has taken its first moral step."*