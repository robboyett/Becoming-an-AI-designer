### Zero to PRD (Guided creation) 
This prompt is designed to help product, design, engineering, and research teams co-create their first Product Requirements Document (PRD) collaboratively. It guides the team through stages of clarity, exploration, validation, and scoping, using an LLM as a facilitator.
How to use: Paste this entire prompt into your LLM chat interface. Then respond to the model’s questions as a team. The process is iterative — expect to refine and revisit sections as new insights emerge.

```md
We’re a cross-functional team (product, design, engineering, and research) working on a new feature or product idea. We want to co-create a first version of a Product Requirements Document (PRD) to clarify the problem, explore potential solutions, and identify useful research or validation tasks. We’re starting from scratch.

Please guide us through a structured process. Begin by asking us focused questions and building the PRD in stages. Structure the process as follows:

---

### Stage 1: Define the problem and context
Ask:
- What problem are we trying to solve, and for whom?
- Why is this problem worth solving now?
- What data, research, or anecdotes suggest this is real?
- What assumptions are we currently making?
- How will we know if we’re solving the right problem?

Then generate:
- Draft problem statement
- Summary of user needs

---

### Stage 2: Define success and outcomes
Ask:
- What would success look like (in user behaviour, business metrics, etc.)?
- How might we measure whether we’ve succeeded or failed?
- What impact would this have if successful?

Then generate:
- “Goals and success metrics” section

---

### Stage 3: Explore solution contours and risks
Ask:
- What possible directions or approaches might solve this problem?
- What are the biggest uncertainties or risks?
- What do we *not* yet know that we should?

Then generate:
- “Solution hypotheses and risks” section
- List of open questions and scoping boundaries

---

### Stage 4: Draft user flows or use cases
Ask:
- What is the user trying to achieve?
- What steps might they take?
- What edge cases or variations should we consider?

Then generate:
- 1–2 sample user stories or user flows

---

### Stage 5: Design validation plan
Ask:
- What are the most valuable things to learn before committing to build?
- What’s the smallest thing we can test or prototype?
- Who do we need to speak to or observe?

Then generate:
- “Learning plan” section
- Suggested methods and responsibilities

---

### Stage 6: Flesh out initial requirements
Ask:
- What must the first version include?
- What can be deferred or is nice-to-have?
- Any technical, legal, or team dependencies?

Then generate:
- “Requirements (First Version)” section
  - Core user stories
  - Functional and non-functional requirements
  - Dependencies

---

### Stage 7: Review and refine
Then ask:
- What needs clarification or better evidence?
- What trade-offs have we not yet surfaced?
- What input do we still need from others?

Then generate:
- Draft PRD in markdown or collaborative format

---

## Notes for the model:
- Help the team clarify thinking and expose assumptions
- Avoid rushing to solution design too early
- Use plain, precise language
- Be flexible and encourage iteration

---

```