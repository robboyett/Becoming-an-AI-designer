# Project Review: Becoming an AI Designer
**Review Date:** January 2025

## Executive Summary

This is a thoughtful, practical resource that bridges traditional design thinking with AI-enabled design practice. The content is strong where it exists, but several sections are incomplete and significant developments since the last update need to be addressed.

**Content Philosophy (from project owner):**
- Curation-first approach: Link to existing resources rather than writing comprehensive guides
- Clear beginner entry point, then modular topic-based structure for dipping in
- Practical textbook that gets you going and helps you think about what to learn
- Minimal learning pathways—focus on topic accessibility
- **No tool reviews/deep dives:** Tools change too quickly; link out to existing reviews instead

---

## Structure Analysis

### Current Organization

**Strengths:**
- Clear separation between conceptual knowledge and practical tools
- Prompt library is well-organized and immediately useful
- Deep dives on specific topics (prototyping, contextual affordance) provide valuable depth
- Modular structure allows for dipping into specific topics
- Curatorial approach evident in design patterns section (aggregates multiple resources)

**Weaknesses:**
- Redundancy between `README.md` and `index.md` (both serve as entry points)
- Several sections marked "Links coming" or "ADD" indicate incomplete content
- Beginner content exists but not clearly marked/surfaced as entry point
- Missing navigation aids (table of contents, cross-references between related topics)
- No section indexing or wayfinding for users with specific needs

**Recommendations:**
1. **Consolidate entry points:** Make `README.md` the project overview and `index.md` the actual resource index
2. **Surface beginner content:** Add clear "Start Here" markers or a beginner section at top of index.md
3. **Add navigation structure:** Include a table of contents in `index.md` with anchor links for topic discovery
4. **Complete placeholder sections:** Fill "Links coming" sections with curated external resources + brief context
5. **Maintain modularity:** Keep topic-based structure—don't over-engineer learning pathways

---

## Content Strengths

### 1. **Mindset and Philosophy**
The Buzz Usborne advice section is excellent—it establishes the right mental model from the start. The emphasis on AI as infrastructure, not outcome, and the warning about critical thinking atrophy are particularly valuable.

### 2. **Unique Conceptual Contributions**
- **"Prototype Mining"** concept is novel and actionable—the systematic approach to leveraging AI's variability is brilliant
- **"Designing Contextual Affordance"** addresses a gap that many resources miss (the latent interface of AI systems)
- Both demonstrate original thinking that goes beyond generic "AI + design" content

### 3. **Prompt Library Quality**
The prompts are well-structured, practical, and cover key design workflows:
- PRD creation
- User flow conversion
- Problem framing
- Preference setting (challenging ideas)

These are immediately usable, which is rare in most design resources.

### 4. **Technical Grounding**
The technical concepts section in the prototyping doc (components, state management, APIs) is smart—it acknowledges that designers need grounding to work effectively with AI coding tools.

### 5. **Design Patterns Collection**
The aggregation of multiple pattern libraries (Shape of AI, AI UX Patterns, etc.) is excellent curation—exactly the right approach. You're pointing designers to the right resources without reinventing the wheel. Consider adding brief context notes (1-2 sentences) on when each library is most useful, but keep it minimal.

---

## Content Weaknesses & Gaps

### Incomplete Sections

1. **"Using AI To Get More Design Done"** has multiple gaps:
   - Problem framing: "Links coming"
   - Creative ideation and refinement: "Links coming"
   - Iterative testing and feedback: "Links coming"
   - Storytelling and presentation: "Links coming"

2. **"AI-assisted coding for creative prototyping.md"**:
   - Example Prompts: "ADD"
   - Software section could include links to external reviews/tool guides (avoid writing own reviews)

3. **Software & Model Guides**:
   - Currently has one entry (Midjourney guide—link to external review or own content?)
   - Missing coverage of major AI design tools
   - Should be directory/table format with links to **existing reviews** (avoid writing own reviews)

### Missing Critical Topics (2024-2025 Developments)

*Note: Given the curation-first approach, these should be filled with curated external resources + brief contextual notes, not comprehensive guides.*

#### 1. **AI Agents & Agentic UX**
- Curated resources on designing for autonomous AI agents
- User control and override patterns
- Agent transparency patterns
- Links to relevant design patterns

**Where it fits:** New section under "Designing AI Experiences For Users" or expansion of "Contextual Affordance"  
**Approach:** Curated list of resources with brief notes on what each covers

#### 2. **Multimodal AI Experiences**
- Resources on vision, audio, video generation
- Voice interaction design patterns
- Cross-modal interaction examples

**Where it fits:** Expand design patterns section or new subsection  
**Approach:** Link to existing pattern libraries + your brief context on when to use multimodal

#### 3. **AI-Powered Design Tools**
- Figma AI, Adobe Firefly, Canva AI, etc.
- Tool directories/tables with links to external reviews

**Where it fits:** Expand "Software & Model Guides" section  
**Approach:** Tool table format (like you have) + links to **existing reviews/guides** (don't write own reviews—they go out of date quickly)

#### 4. **AI Evaluation & Testing**
- Resources on testing AI experiences
- Prompt testing frameworks
- User testing AI interfaces
- Hallucination detection patterns

**Where it fits:** "Using AI To Get More Design Done" → "Iterative Testing and Feedback"  
**Approach:** Curated links to testing methodologies + brief note on what's different about testing AI

#### 5. **Cost & Token Management**
- Resources on understanding token usage
- Cost optimization guides
- Local vs. cloud decision frameworks

**Where it fits:** Expand "Software & Model Guides" or add to "AI-assisted coding" doc  
**Approach:** Links to practical guides + brief decision framework notes

#### 6. **Prompt Engineering for Designers**
- You have great prompt examples—add curated resources on:
  - Prompt testing methods
  - Prompt versioning tools
  - Advanced techniques for design thinking

**Where it fits:** Expand "Prompt writing" section in index.md  
**Approach:** Add links to comprehensive guides (Anthropic, Google) + your brief notes on what designers specifically need

#### 7. **AI Ethics & Bias for Designers**
- Practical frameworks for designers
- Bias detection resources
- Inclusive AI design practices

**Where it fits:** New subsection under "Designing AI Experiences"  
**Approach:** Curated links to ethics frameworks + your note on designer's responsibility

#### 8. **Real-time Collaboration with AI**
- AI in design workflows
- Collaboration patterns
- Pair programming with AI resources

**Where it fits:** "Using AI To Get More Design Done" → "Collaboration and Communication"  
**Approach:** Link to existing resources on AI collaboration + brief notes on design-specific applications

#### 9. **Model Selection Guidance**
- When to use Claude vs. GPT-4 vs. Gemini
- Open-source model options
- Model comparison resources

**Where it fits:** Expand "Software & Model Guides"  
**Approach:** Brief comparison table format + links to **existing detailed comparison guides** (don't write own comparisons—they go out of date quickly)

#### 10. **Case Studies & Examples** (Optional—may not align with curation approach)
- Real-world examples
- Lessons learned posts/articles

**Where it fits:** If added, keep it light—link to others' case studies rather than writing your own

---

## Recommendations by Priority

### High Priority (Complete Existing Gaps)

1. **Fill "Links coming" sections with curated resources:**
   - Problem framing: Link to existing frameworks + your problem-framing prompts
   - Creative ideation: Curated links to ideation techniques + AI-enhanced methods
   - Testing and feedback: Links to AI testing methodologies + brief note on what's different
   - Storytelling/presentation: Links to resources on using AI for presentations + brief context

2. **Complete Example Prompts section** in prototyping doc
   - Add 2-3 real example prompts with brief context on when/why to use them

3. **Surface beginner content clearly:**
   - Add "Start Here" section or clear markers at top of index.md
   - Ensure beginner path is obvious: Mindset → Fundamentals → First Steps

4. **Add navigation structure:**
   - Table of contents with anchor links in index.md
   - Cross-reference related topics

### Medium Priority (Add Missing Topics)

5. **AI Agents & Agentic UX** curated section
   - Links to agentic UX resources + brief context on what designers need to know

6. **AI Evaluation & Testing** curated links
   - Resources on testing AI experiences + brief notes on differences from traditional UX testing

7. **Expand Software & Model Guides:**
   - Tool/model directories/tables with links to **existing reviews** (don't write own reviews)
   - Links to comparison guides for models (Claude, GPT-4, Gemini)
   - Links to guides/tutorials for AI design tools (Figma AI, Adobe Firefly, etc.)

8. **Cost & Token Management** curated links
   - Resources on token management + brief decision framework notes

9. **Multimodal AI** design patterns
   - Links to multimodal pattern libraries + brief note on when to use

### Lower Priority (Nice to Have)

10. **AI Ethics** curated section (if you want to add it)
    - Links to ethics frameworks + brief note on designer's responsibility

11. **Community & Staying Updated** section (optional)
    - Curated list of newsletters, communities, conferences

12. **Case Studies** (optional - may not align with curation approach)
    - If added, keep it light—link to others' case studies

---

## Structural Improvements

### Suggested Reorganization (Aligned with Curation Approach)

```
README.md
├── Project overview
├── Quick start (point to beginner content)
└── Link to index.md

index.md
├── Table of Contents (with anchors for easy navigation)
├── START HERE: Clear beginner entry point
│   ├── Mindset Change (Buzz Usborne advice)
│   ├── Fundamentals (2weeks.ai link)
│   └── First Steps (point to key beginner topics)
│
└── Main content (modular topics - dip in as needed):
    1. Getting Started With AI
       - Mindset Change
       - Fundamentals (curated links)
       - Thinking resources (curated links)

    2. Designing AI Experiences For Users
       - Design Patterns (curated links to pattern libraries)
       - Contextual Affordance (your deep dive - keep as-is)
       - AI Agents & Agentic UX (NEW: curated links)
       - Ethics & Bias (NEW: curated links, if you add it)

    3. Using AI In Your Design Process
       - Empathy and user understanding (curated links)
       - Problem framing (your prompts + curated resources)
       - Creative ideation (curated links)
       - Prototyping workflows (your deep dive + links)
       - Testing AI experiences (NEW: curated links)
       - Collaboration (curated links)
       - Storytelling/presentation (NEW: curated links)

    4. Tools & Technologies
       - Software & Model Guides (tool directory with links to external reviews)
       - Cost Management (NEW: curated links)
       - Prompt Engineering (curated links + your prompts)

    5. Prompt Library
       - [Current prompts - keep as-is]
       - Maybe: Links to prompt testing tools

    6. Staying Updated (NEW, optional)
       - Curated newsletters, communities, conferences
```

**Key Principles:**
- **Beginner-first:** Clear "Start Here" section at top
- **Modular:** Topics can be accessed independently
- **Curation-heavy:** Most content is links + brief context
- **Minimal structure:** Don't over-engineer navigation
- **No tool reviews:** Link out to existing reviews—tools go out of date too quickly

### Cross-Reference Strategy

Add links between related content:
- "Prototype Mining" → links to "Contextual Affordance"
- "Problem Framing" prompts → links to "Using AI in Design Process"
- Design patterns → links to specific tools that implement them

---

## Content Freshness Issues

### Outdated or Missing Recent Developments

*Note: For tool updates, link to external reviews/announcements rather than writing own reviews.*

1. **2024 AI Design Tool Updates (link to external reviews):**
   - Figma AI features (June 2024)
   - Adobe Express AI capabilities
   - Canva AI suite expansions
   - Webflow AI integration

2. **Model Updates:**
   - GPT-4 Turbo (Nov 2023)
   - Claude 3.5 Sonnet (June 2024)
   - Gemini 1.5 Pro (Feb 2024)
   - Open-source model landscape changes

3. **Emerging Patterns:**
   - Agentic interfaces becoming mainstream
   - Voice + visual multimodal becoming standard
   - Real-time generation in production apps

4. **Industry Trends:**
   - "AI Designer" as defined role
   - AI design education programs
   - AI-first design system approaches

---

## What's Working Well

1. **Curation-First Approach:** Smart decision to link out rather than write comprehensive guides—keeps resource lean and maintainable
2. **Practical Focus:** The resource avoids theory-heavy academic content and stays actionable
3. **Original Thinking:** Concepts like "prototype mining" and "contextual affordance" add unique value that external resources don't cover
4. **Designer-Centric:** Speaks to designers' actual workflows, not generic "AI for everyone"
5. **Immediate Usability:** Prompt library provides instant value—no learning curve required
6. **Balanced Perspective:** Acknowledges both opportunities and risks (critical thinking atrophy)
7. **Modular Structure:** Topic-based organization allows designers to dip in where they need—perfect for practical textbook approach

---

## Final Thoughts

This is a strong foundation for a valuable practical textbook. The main work needed is:

1. **Complete placeholders:** Fill "Links coming" sections with curated resources + brief context
2. **Surface beginner content:** Make the entry point crystal clear
3. **Add navigation:** Table of contents + cross-references for topic discovery
4. **Add missing topics:** Cover 2024-2025 developments (agentic UX, multimodal) with curated links

The project has authentic voice and practical utility. Your curation-first approach is smart—it keeps the resource lean and focused while pointing people to the right places. The prompt library is immediately valuable, and the unique conceptual contributions (prototype mining, contextual affordance) differentiate this from generic AI design resources.

**Estimated effort to bring current (aligned with curation approach):**
- High-priority items: 1-2 weeks (mostly research and linking, not writing)
- Medium-priority additions: Additional 1-2 weeks (curating resources)
- Complete refresh: 3-4 weeks total (much faster with curation vs. comprehensive writing)

---

## Suggested Next Steps

1. **Audit existing links:** Check if all external links still work and are relevant
2. **Surface beginner content:** Add clear "Start Here" section at top of index.md
3. **Fill placeholder sections:** Start with highest-traffic areas (testing, problem framing, creative ideation) by curating external resources + adding brief context
4. **Add 2024 developments:** Curate resources on agentic UX and multimodal patterns
5. **Add navigation structure:** Table of contents with anchor links in index.md
6. **Maintain curation approach:** Keep it lean—link out, don't write comprehensive guides
7. **Avoid tool reviews:** Link to existing reviews/tool guides; don't write own reviews (they go out of date quickly)

---

*End of Review*

