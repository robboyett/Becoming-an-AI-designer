# Designing Contextual Affordance

When working with AI-powered features designers aren’t just shaping interfaces. We’re shaping **how systems understand**. This means working with the latent layers of context that guide model behaviour and define how intelligent, helpful, and usable the feature becomes.

## What is “context” in an LLM-enabled product?

Context is the total information available to the model at the time of generating a response. It’s not just the user’s input. It’s a combination of system-level guidance, memory, tools, and structured expectations.

Here are the core components you’ll likely encounter:

| **Component**                       | **Description**                                                                 |
|------------------------------------|---------------------------------------------------------------------------------|
| **User prompt**                    | The immediate query or input from the user—can be underspecified or ambiguous. |
| **Instructions / system prompt**   | Hidden directives that steer model tone, role, constraints, and response style.|
| **Short-term memory (state)**      | Conversation history or recent actions from the session.                       |
| **Long-term memory**               | Persistent knowledge: user preferences, past sessions, stored info.           |
| **Retrieval-Augmented Generation (RAG)** | Dynamic context from external sources—e.g. internal docs, databases.     |
| **Available tools**                | Functions the model can call—APIs, plugins, calculators, DB lookups, etc.     |
| **Structured output**              | The format required (e.g. JSON, table, Markdown) for integration or parsing.  |

These elements shape the *latent interface*. The one the user never sees but which defines how well the system works and feels.

---

## How this changes UX design strategy

Designing AI-powered experiences means adding to the upfront context and thinking we already do, things like understanding user needs, mapping networks and systems, user flows and testing ability to achieve tasks. We now mix in **how the system thinks about a request, interprets and responds**.

### New questions designers should ask:
- What does the system *already know*?
- What should it remember across time?
- What external data or tools does it need to do this well?
- How do we expose or surface what the model “understands” to the user?
- What are the risks of misunderstanding, and how do we make context visible or editable?

### What UX designers now design:
- Prompt templates and context structures
- Memory UX (e.g. “What we remember”, “Forget this”, editable timelines)
- External knowledge sources (retrieval logic, relevance filters)
- Tool selection (what the LLM can use, when and how)
- Output shaping (structured formats, content boundaries)

---

## Practical prototyping: context-aware UX techniques

| **Context Area**        | **UX Design / Prototyping Approach**                                                                 |
|-------------------------|--------------------------------------------------------------------------------------------------------|
| **User prompt**         | Prompt shaping, templating, A/B testing different phrasings.                                           |
| **System prompt**       | Run variations in tone/constraint sets and test model responses.                                       |
| **Short-term memory**   | Design visible history summaries, editable memory panels, session playback.                          |
| **Long-term memory**    | Personalisation flows, opt-in memory UIs, “what we know about you” explainer modals.                  |
| **RAG**                 | Simulate different knowledge sources; show citations and traceable retrieval for trust.               |
| **Available tools**     | Design and mock out tool affordances—what the LLM *could* do and how it's triggered.                  |
| **Structured output**   | Create resilient schemas, auto-formatting UX, error-tolerant designs for misalignment.                |

---

## Experimental approach

Use iterative design loops that test **context scaffolding** as much as UI:

1. **Build modular prototypes**  
   Allow toggling different context components on/off to see how the LLM responds.

2. **Audit the system’s context view**  
   Create a debug panel or user-facing visualisation of what the system “knows”.

3. **Test degraded states**  
   What happens when key context components are missing or incomplete?

4. **Design for adaptation**  
   Let users teach the system over time. Show what it learned. Allow correction.

5. **Feedback as signal**  
   Treat user corrections, edits, or frustrations as feedback loops for refining prompts, memory, or retrieval logic.