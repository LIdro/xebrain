# Xebrain

**Xebrain is a founder's state of mind restoration system, not a project manager.** It helps a founder recover the intent, reasoning, uncertainty, and perspective behind a thought so they can continue after an interruption, time away, or a change of role.

Read [the manifesto](manifesto.md) first. It defines the product's purpose and the principle that guides every decision: **continuity of thought over productivity**. [Agent instructions](agents.md) describe how future coding work must respect that purpose.

## The core loop

1. **Capture:** record a thought in the founder's own words, with minimal friction.
2. **Understand:** make its intent, context, assumptions, and open questions explicit through a reviewable interpretation.
3. **Preserve:** retain the original thought, its context, its connections, and how the reasoning changes.
4. **Re-enter:** restore where the founder left off and provide a place to continue thinking.

**Temporal re-entry** restores a line of thought after time has passed, including the difference between its earlier state and later developments. **Role re-entry** restores a perspective when the founder switches responsibilities, such as moving from selling to building or from operating to strategy. Both can apply to the same thought.

## Defined MVP

The MVP serves one founder and proves one complete loop: capture a thought, preserve enough context to understand it, leave it, and return to continue it later or through another role.

| Capability | Minimum useful behavior |
| --- | --- |
| Thought capture | Save freeform text and a capture time. Allow an optional founder-defined role and context. Do not require task fields. |
| Context clarification | Let the founder record or review a short account of intent, why it matters, assumptions, and unresolved questions. Keep interpretations separate from original text and editable by the founder. |
| Thought preservation | Retain original captures and dated continuations or corrections. Link related thoughts and preserve role context so later reasoning does not silently replace earlier reasoning. |
| Finding a thread of thought | Let the founder find saved thinking by text, time, or role and follow its related entries. A thread is a continuing line of thought, not a task list. |
| Temporal re-entry | Present a brief account of where the thinking stood, its reasoning and open questions, and any recorded developments since that point. Keep the underlying entries accessible. |
| Role re-entry | Let the founder select a role and recover the relevant perspective, while retaining access to connected thinking from other roles. |
| Continuation | Provide a place to add the next thought from the restored context, feeding it back into the same loop. |

A re-entry brief should answer: What was I thinking about? Why did it matter? What did I believe or decide? What remained uncertain? What has changed in the saved record? Where can I continue?

If there is no recorded answer, the system should leave the gap visible. It must not fabricate missing context. A possible next step remains a suggestion or recorded intention rather than an assigned task.

## Example MVP journey

A founder captures a pricing concern while selling, preserving a customer's objection and an unresolved assumption about value. Later, the founder returns as a strategist. Xebrain restores the original concern, its reasoning, and related developments through the strategy perspective. The founder adds a new hypothesis, preserving the earlier thinking as part of the thread's history.

## MVP success criteria

- After time away, the founder can recover why a thought mattered, where the reasoning stood, and what remained unresolved without reconstructing it from scattered notes.
- After switching roles, the founder can recover the relevant perspective and understand its connection to other perspectives.
- The founder can inspect and correct the context used for restoration and distinguish original words from interpretation.
- Continuing a thought preserves its history and closes the capture -> understand -> preserve -> re-enter loop.

Evaluate these outcomes through founder use and feedback. Task throughput, completion counts, and time spent in the app are not the primary measures of success.

## Outside the MVP

Task boards, deadlines, reminders, team assignments, sprint planning, productivity scores, autonomous execution, and broad external integrations are outside the MVP. Voice capture and other input formats can be considered later if they improve the core loop.

No technology stack or AI dependency is selected here. Assisted understanding and re-entry must follow the same requirements for source visibility, correction, and honest uncertainty.

## Current status

This repository currently contains product definition and agent guidance only. App implementation, scaffolding, dependencies, and architecture decisions await a separate implementation request.
