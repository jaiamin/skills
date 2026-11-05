---
name: make-it-click
description: Explain any concept intuitively and concisely, focusing on what it is, how it really works, and the important details beyond a basic definition. Use when the user invokes make-it-click, asks how something actually works, or wants a clear mental model of a technical or nontechnical topic, from HTTP to the Suez Canal to AGI.
---


# Make it click

Give the reader a working mental model: enough understanding to explain the mechanism and reason about a small change, without a textbook chapter.

## Build the explanation

1. **Establish what it is.** Lead with one or two plain sentences naming the thing, its purpose or role, and the central idea that makes it understandable. Answer the user's specific question immediately.
2. **Show it working.** Follow one concrete case through the actual process. Name the essential parts or actors, what each does, and why one step causes the next. Make the hidden middle visible instead of merely naming an operation. If that step remains opaque, replace vague wording with one tiny before/after example. State the general principle that carries beyond the example. Add arithmetic only when it makes the causal link easier to understand.
3. **Add the details that change understanding.** Select the few constraints, tradeoffs, design reasons, or common misconceptions that matter most. Explain their consequences. Prefer an illuminating detail over trivia, dates, feature lists, or exhaustive caveats.

Weave these together naturally. Do not force three headings or a numbered process onto every topic. For a place or institution, explain its operation, physical constraints, or incentives. For an abstract idea, explain the defining distinction and a concrete example or counterexample. For a proposed capability, distinguish the goal from existing approaches and unresolved mechanisms. Do not invent a settled explanation where none exists.

## Keep it intuitive and proportionate

- Adapt to the user's question and demonstrated knowledge. Introduce only necessary prerequisites. Explain a new part's plain-language job before naming it; introduce terms gradually rather than listing components up front.
- If the user remains confused, locate the missing prerequisite or causal step, then change the example or representation instead of merely rephrasing.
- Prefer a real example. Use one short analogy only if it reduces effort, map it to the real mechanism, and identify a misleading implication when needed. Never let an analogy replace how the thing actually works.
- Start with the simplest accurate model, then add only the nuance needed to avoid a wrong conclusion. Separate defining properties from common implementations and observations from hypotheses.
- Aim for roughly 200–400 words for a broad concept, less for a narrow question. Treat this as a guide, not a quota or ceiling. Honor explicit requests for more or less depth.
- Use short paragraphs and plain language. Use a small table, diagram, equation, or code example only when it removes a specific comprehension obstacle. Use available visual tools for a needed image, illustration or map, and a simulation only when changing a condition teaches more than a static view. Replace the prose a visual makes redundant; leave an already-clear short explanation alone. Avoid em dashes, filler introductions, repeated summaries, automatic quizzes, and unsolicited follow-up menus.
- Verify changing, disputed, niche, or uncertain claims with reliable sources; favor primary sources for technical mechanisms. Keep citations unobtrusive. Do not turn a concept explanation into a research report unless asked.

Before sending, check silently: Can the reader explain what happens and why, and predict the effect of changing one important condition? Is the crucial middle explained? Did each extra detail earn its place? Include a brief variation only when it clarifies the model. Remove repetition and stop when the model is complete.
