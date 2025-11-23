# CATRE v0.9.3 — Conversational Edition (June 2025)

This is the first version of the Constraint–Affordance Theory of Relational Emergence that is **ready for real use** by anyone with an LLM.

### What works right now
- The full Triad Evaluation Workflow (WHAT → HOW → Quantitative Lens Check → WHY → Resonance Map)
- Strict gating: no “WHY” statement is allowed without passing the Quantitative Lens
- Every interpretive claim must be followed by its supporting number in parentheses
- Structured Inquiry replaces narrative mysticism
- Wisdom Index (WI) is now contingent on empirical evidence

### What is deliberately missing (on purpose)
Sections 3, 4, 6, 7, 8, 10 of the original technical reference document are **not included yet**.  
They will be added incrementally as living documents.  
This release is the **engine**, not the manual.

### How to use it today
1. Copy `catre_v0.9.3_prompt.txt` into Claude 3.5 / Grok-4 / Gemini-1.5 / etc.
2. Feed it any question or dataset you care about.
3. Watch it refuse to give contemplative answers until the numbers justify it.

### Example that already works perfectly
→ `case_studies/black_hole_information_paradox.md`

### Current status
- Engine:      complete and rigorously self-policing  
- Documentation:  ~30 % (the rest is coming)  
- Known limitation: LLM drift on long runs (we are building a LangGraph wrapper to eliminate it)

This is released under MIT license.  
Fork, break, improve, share.

—The bridge is open.  
Walk on it while we finish paving the road.
