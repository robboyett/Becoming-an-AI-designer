````markdown
## Prompting overview

**Purpose.**  
A practical frame for using prompts in design work. It explains what prompting is, which frameworks and methods exist today, how dependable they are, and how to move from casual use to repeatable workflows and background system prompts. Link this with your sections on *prompt writting*, *problem framing*, *prototyping and workflows*, and *iterative testing and feedback* so readers can jump to detail. :contentReference[oaicite:0]{index=0}

---

### How to think about prompting

Prompting is essentially **writing a design brief for an expert collaborator**. A good prompt gives the model the same grounding you’d give a teammate: context, goal, constraints, and examples. Most useful techniques sit on a continuum from lightweight chat to embedded automation.

**A prompting maturity ladder**

1. **Ad-hoc chat** — one-off questions and quick experiments.  
2. **Reusable pattern** — save effective prompts as templates for repeat tasks.  
3. **Prompt library** — versioned collection shared across the team.  
4. **Prototyping scripts** — prompts wired into tools like Figma or the CLI.  
5. **Retrieval + tools** — model accesses design systems, research, or a11y checkers.  
6. **System prompts & agents** — embedded background instructions and automated reviewers.

---

### Common approaches

* **Structured prompts**
  Use a short framework such as **CARE** (Context, Ask, Rules, Examples) or **WIRE+FRAME** (Who, Input, Rules, Expected … Evaluate). They keep outputs focused and repeatable.

  * CARE → [https://www.nngroup.com/articles/careful-prompts/](https://www.nngroup.com/articles/careful-prompts/)
  * WIRE+FRAME → [https://www.smashingmagazine.com/2025/08/prompting-design-act-brief-guide-iterate-ai/](https://www.smashingmagazine.com/2025/08/prompting-design-act-brief-guide-iterate-ai/)

* **Stepwise reasoning**
  Ask the model to think or act in stages: diagnose → propose → check. This helps with complex reasoning like usability reviews or content checks.

* **Personas and examples**
  Assign the AI a role (“accessibility auditor”, “UX writer”) and show two or three good examples. Roles anchor tone and accuracy; examples teach style.

* **Constraints and guardrails**
  List short “do” and “don’t” points to prevent errors. For example:
  *Do* keep within 40 characters; *Don’t* use technical jargon.

* **Critique-refine loop**
  Let the AI review its own draft against simple criteria (“clarity”, “tone”, “accuracy”), then improve it. One or two cycles are usually enough.

* **Grounding and retrieval**
  Paste in small extracts from your design system, research, or WCAG so the AI works with trusted information. Avoid long documents; summarise or link.

* **Team reuse**
  Save well-performing prompts in a small library. Note the task, date, and version. Over time these become your in-house “prompt patterns”.

---

### When to use which

| Goal                       | Reliable pattern                    | Confidence    |
| -------------------------- | ----------------------------------- | ------------- |
| Generate new ideas fast    | Structured + persona + examples     | High          |
| Critique or QA a design    | Role + stepwise heuristic check     | Peer-reviewed |
| Write on-brand UI copy     | Structured + constraints + examples | Field-tested  |
| Prototype with context     | Retrieval of design-system snippets | Medium        |
| Accessibility & code audit | Role + tools (e.g. Axe + LLM)       | High          |

Evidence is strongest for structured and role-based prompting, heuristic evaluations, and accessibility repair tasks; more experimental for multi-agent panels or fully automated prototyping.

---

### Using it day to day

1. **Start simple.** Write one structured prompt for a recurring task (e.g. “generate tone-checked error messages”).
2. **Refine.** Add a persona, then test a stepwise version that includes a self-check.
3. **Record.** Save what works in your prompt library.
4. **Automate later.** When a pattern is stable, embed it in a Figma or CLI script or as a background “system prompt”.
5. **Keep a human in the loop.** Always review outputs for bias, clarity, and factual correctness.

---

### Risks and checks

* **Bias and inclusion.** Ask explicitly for inclusive language; check diversity in examples.
* **Hallucination control.** Require citations or clear grounding; never accept unverified facts.
* **Privacy and IP.** Strip client or user data; prefer local models for confidential work.
* **Quality assurance.** Use your usual heuristics and rubrics before anything goes live.

---

### Learning links

**In this doc**

* *Prompt writting* — Google and Anthropic guides. 
* *Problem framing* — NN/g research and applied framing methods. 
* *Prototyping and workflows* — Vibe Coding Field Guide and starter prompts. 
* *Iterative testing and feedback* — heuristic and accessibility resources. 

**External**

* UICrit (UIST 2024): [https://dl.acm.org/doi/10.1145/3654777.3676381](https://dl.acm.org/doi/10.1145/3654777.3676381)
* CHI prompting for UX evaluation: search “CHI 2025 prompting UX evaluation role chain of thought”
* WCAG reference: [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/)
* AccessGuru accessibility repair study: search “AccessGuru arXiv 2025 accessibility LLM”
* ReAct and RAG primers: [https://react-lm.github.io/](https://react-lm.github.io/) and provider blogs
* AI Design Kit (for ideation frameworks): [https://aidesignkit.github.io/](https://aidesignkit.github.io/)

```
```