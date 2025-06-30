[<- Index.md](index.md)

# AI-assisted coding for creative prototyping

Tools like Figma Make, ChatGPT, Claude, and GitHub Copilot now enable designers to generate functional prototypes using natural language. You can prompt them to produce HTML/CSS, React components, or interactive UI sketches—quickly turning ideas into code.

## Purpose to prototype

Before diving in, it’s worth stepping back: why are you prototyping in the first place? Design thinking has long emphasised prototyping as a way to explore ideas, test assumptions, and align teams. That hasn’t changed. But in the era of AI-assisted design, being crystal clear on your intent helps in two ways:

- It keeps stakeholders aligned on what you’re building and why.
- It improves your prompts. AI responds better when you give it context—what you’re trying to learn, who you’re designing for, and what format the output should take.

With AI, the old debate around fidelity becomes less relevant. You can generate a near-production UI with the same effort as a low-fi wireframe. But the purpose of prototyping still matters: you’re not just building screens—you’re building insight. Validation, iteration, and learning are still deeply human activities.

### Problem statement template

Use this as a tool for staying focused as you prototype: “Our [users] need a way to [accomplish task] because [underlying need]. This prototype will demonstrate [specific capability] to validate [assumption].”

## Picking the right tool

### Software Reviews

| Tool  | Type | Notes |
| ------------- | ------------- | ------------- |
| Cursor  | AI powered coding environments (Local)  | -  |
| Replit | AI powered coding kickstarters (Cloud) | - |
| v0 | AI powered coding kickstarters (Cloud) | - |
| Bolt | AI powered coding kickstarters (Cloud) | - |
| Claude | LLM | - |
| ChatGPT | LLM | - |
| Deepseek R1 | Open source LLM | This model can be used locally on your map, it can be really useful if you're working inside a company that is very sensitive to using cloud-hosted software. |
| LLaMA | Open source LLM | This model can be used locally on your map, it can be really useful if you're working inside a company that is very sensitive to using cloud-hosted software. |

### Running LLMs Locally on Mac

| Tool  | Type | Notes |
| ------------- | ------------- | ------------- |
| AnythingLLM  | Native Mac App | -  |
| LM Studio | Native Mac App | - |

## Example Prompts
ADD

## Existing libraries to take advantage of
The LLMs can often be quite keen to write all of their code from scratch, but a simple Google search or a few questions about existing code libraries that you might include in your project can actually get you a very long way with much less code, and create a set of guide rails for the LLMs. So that you have functionality that has been defined and tested and works out the box and you can concentrate on what's unique about the prototype that you're creating.

- p5.js – A JavaScript library for creative coding. Ask ChatGPT to generate p5.js sketches for data visualisations, interactive animations, or custom UI behaviour.
- ML5.js – A library that wraps common machine learning models into beginner-friendly JS functions. Combine it with ChatGPT to write code for real-time classification or generative effects in the browser.

## No-code machine learning in prototyping
Designers can explore machine learning behaviours in prototypes today using visual, no-code tools:

- Teachable Machine by Google – Train models using your webcam, voice, or image inputs. These models can be exported and embedded into prototypes to create gesture-driven, audio-reactive, or image-responsive interactions.
- Wekinator – Use real-time input data (e.g. from sliders, webcams, sensors) to train a model and trigger outputs. You can connect this to creative coding environments like Processing or Unity.
- Runway ML – Offers drag-and-drop access to powerful generative models for video, image, or text – useful for building experimental creative interfaces.

## AI prototype mining: A systematic approach to discovering unexpected solutions
This process leverages AI's natural variability in interpreting requirements to expand your solution space beyond initial assumptions. Rather than generating a single prototype that reflects your preconceptions, you create multiple AI-generated variants that reveal alternative approaches and features you might not have considered. The key value lies in the collaborative evaluation phase - prototype mining sessions where teams systematically review these "serendipity features" to identify genuinely useful discoveries. It transforms AI's tendency to interpret briefs differently from a limitation into a deliberate exploration tool, helping teams break out of familiar design patterns whilst maintaining focus on core requirements.

### Step-by-step guide

**Phase 1: Requirements preparation**
1. Gather inputs - Collect business expectations, user research findings, and team assumptions
2. Document hypotheses - Write down your solution hypotheses and key assumptions
3. Create PRD - Use an LLM to help structure all the documents you have into one context bundle in the style of a PRD

**Phase 2: Prototype generation**
1. Select AI tools - Choose your favorite AI enabled tool or a mix e.g. Figma Make, v0, Cursor
2. Generate variants - Run the PRD through tools 8+ times to create multiple working prototypes. Tip: Resist steering - Don't attempt to control interface design details - let the AI interpret freely
4. Capture outputs - Save all generated prototypes, even ones that seem off-target

**Phase 3: Mining session preparation**
1. Review prototypes - Identify serendipity features and unexpected approaches across variants
2. Document discoveries - Note interesting differences, new features, or alternative interpretations
3. Schedule session - Book prototype mining session, include a cross-function spread of people from product and dev...

**Phase 4: Prototype mining session**
1. Present variants - Show prototypes to the team without initial commentary
2. Identify serendipity features - Discuss unexpected elements that emerged from AI interpretation
3. Evaluate potential - Assess which discoveries merit further exploration or testing
4. Decide next steps - Choose whether to test prototypes as-is or amalgamate interesting features

**Phase 5: Synthesis**
1. Document decisions - Record which serendipity features the team wants to pursue
2. Plan testing - Define how to validate promising discoveries
3. Iterate requirements - Update PRD based on insights from mining session

## Technical Conepts For Designers
Why is this useful in the context of AI assisted prototype building? When you're trying to build these more technical prototypes, working prototypes, a bunch of these concepts are going to come up and having a good grounding is useful if not necessary to become an expert in all of them but understanding what they are is very useful.

### Frontend Fundamentals
What it is: The building blocks of modern web interfaces including React components, responsive design, and state management. 
Why it's useful: These skills form the foundation of interactive digital products. Understanding how components work, how to make designs adapt to different devices, and how to manage application data will empower designers to create more sophisticated and user-friendly experiences. 
When to learn: Start here if you're transitioning from pure visual design to more technical implementation work.

🧱 COMPONENTS
Think of components like reusable recipe cards:
Components = Recipe cards with ingredients and instructions
Props = Customizable ingredients you can change each time
State = Notes you make while cooking (changes during use)
Example: A Button component can have props for color, size, text, and state for "pressed" or "loading"

📱 RESPONSIVE DESIGN CONCEPTS
Media queries = Instructions that say "when screen is this size, do this instead"
Flexbox = Magical shelves that rearrange items automatically
Grid = Digital graph paper for precise layouts
Mobile-first = Design for phone, then expand (not shrink from desktop)

🧠 STATE MANAGEMENT
State = Memory for your app:
Local state = Short-term memory (this component only)
Context = Shared memory among a family of components
Redux/Zustand = Central memory bank for entire application

🧩 COMPONENT LIBRARIES
Component libraries = Pre-built collections of UI elements 
Material Design/Chakra UI = Ready-to-use libraries with consistent styling 
Design Systems = In-house collections of components with company standards 
Benefits = Faster development, consistency across products, built-in best practices 
Customisation = Adapting library components to match your specific needs

### User Experience Enhancement
What it is: Techniques that elevate user experience beyond static designs, including animations, transitions, and interactive elements. 
Why it's useful: These concepts help create polished, professional experiences that feel responsive and alive. Well-implemented animations provide feedback, guide attention, and make interfaces feel more intuitive. 
When to learn: After you've mastered basic implementation, focus here to take your interfaces from functional to delightful.

🎬 ANIMATION CONCEPTS
CSS Transitions = Simple A→B movements
CSS Animations = Pre-programmed sequences
GSAP = Hollywood-level special effects for websites
Framer Motion = React-friendly animation with physics

### Technical Infrastructure
What it is: The behind-the-scenes systems that power digital products, including deployment processes, package management, and version control. 
Why it's useful: Understanding these systems helps you work more efficiently with development teams and gives you the ability to publish and iterate on your own prototypes. These skills bridge the gap between design and development. 
When to learn: These become important when you're ready to share your work publicly or collaborate with developers.

🚀 DEPLOYMENT
Vercel/Netlify = Services that put your prototype online
Environment Variables = Different settings for development vs. live versions
Build Process = Packaging your code for the web (like publishing a book)

📦 NPM & PACKAGES
Think of npm as the world's biggest cookbook collection:
npm install = Adding a recipe to your collection
package.json = Your personal index of recipes
node_modules = The giant cabinet where all recipes are stored

🔄 VERSION CONTROL
Git is like a time machine for your project:
Commit = Taking a snapshot
Branch = Creating an alternate timeline
Merge = Combining timelines
Pull Request = Asking to add your timeline to the main one

### Data Integration
What it is: Methods for connecting your interface with real data, including API basics, security considerations, and state management patterns. 
Why it's useful: Real products need real data. Understanding these concepts allows you to design with actual content in mind and create interfaces that handle the complexities of working with dynamic information. 
When to learn: These become critical when moving from static mockups to functional prototypes that use live data.

🔄 API BASICS
APIs are like library systems:
GET = Borrowing a book (retrieving data)
POST = Donating a book (sending new data)
PUT/PATCH = Updating library records (modifying data)
DELETE = Removing a book (deleting data)

🔐 SECURITY ESSENTIALS
API Keys = VIP passes to access data services
.env files = Secret drawers where you keep your keys
Never put API keys directly in your code - they belong in environment variables
When sharing your prototype, use mock data if possible

### Code Quality & Scalability
What it is: Tools and practices that improve code maintainability, including TypeScript, proper state management, and structured component architecture. 
Why it's useful: As projects grow in complexity, these practices help prevent bugs, make code easier to understand, and enable more efficient collaboration with developers.
When to learn: Focus on these as you start working on larger, more complex projects or when joining established development teams.

🧰 JAVASCRIPT VS TYPESCRIPT
JavaScript = A language where anything goes
TypeScript = JavaScript with strict rules (variables must be specific types)
Types help prevent bugs by ensuring data is the right format
