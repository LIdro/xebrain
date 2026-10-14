# Take Me Back: behavior spec

Read [the manifesto](manifesto.md) first. This experience expresses Xebrain's purpose as a founder's state of mind restoration system and its commitment to continuity of thought over productivity.

## Core behavior

**The system assumes founder intent to continue. Invoking Take Me Back is sufficient intent; the system must not ask for confirmation.**

The founder has already chosen to return to a thread of thought. Xebrain should restore their frame of mind and momentum immediately: reconnect them with their own words, orient them to what has changed, and give them a confident place to continue.

Do not ask whether they still want to work on it, whether they are ready, or whether the system should proceed. Do not make the founder explain their intent again. Assumed intent to continue does not imply that an earlier belief is still true or that a previous decision cannot be reconsidered.

## Required flow

### 1. Start with the founder's original words

Lead with the founder's saved words from the point they are returning to. Preserve the wording and distinguish the quotation from any system interpretation. Include its saved date and role when available, without making either a prerequisite for re-entry.

Choose the passage that restores the thread's intent and unfinished reasoning. If showing an excerpt, identify it as an excerpt and make the full original accessible. Do not replace the founder's voice with a generated summary before they have encountered their own words.

The purpose is recognition: the founder should recover what mattered and the perspective they were thinking from.

### 2. Give a neutral "Here's what changed" summary

Follow the original words with a concise account of relevant recorded developments since that point. Describe new evidence, changed assumptions, decisions, and continuations without judgment, urgency, or a progress score.

Keep the earlier context distinct from later developments. Make the supporting entries accessible and clearly distinguish recorded facts from interpretation. Preserve unresolved issues as statements, not questions the founder must answer before continuing.

If there are no saved developments, say: "No new developments are recorded since this point." Do not claim that nothing has changed outside the saved record. If context is incomplete, state the gap briefly and proceed using what is available; do not turn the gap into an interview.

The purpose is orientation: the founder should understand the current context without being evaluated for time away or work left unfinished.

### 3. Recommend one confident next step

Give one specific recommendation that follows from the original intent, the recorded developments, and the relevant role. Use direct language such as "Continue by..." or "The next useful step is..." and briefly explain its connection to the thread.

The recommendation should make resuming thought easier: develop a hypothesis, compare an assumption with new evidence, draft a position, or continue an unfinished argument. It must not introduce a deadline, task assignment, or obligation.

Clearly present the next step as the system's recommendation, not as a decision or intention the founder previously recorded. Confidence belongs in the delivery of a useful starting point; it does not justify unsupported factual certainty. Where evidence is sparse, recommend a small continuation grounded in the available words, such as developing the last unfinished idea, without demanding more context first.

Do not append "Would you like to proceed?", "Does that sound right?", or a list of diagnostic questions. Put the founder directly at a place where they can continue writing. They may follow the recommendation, redirect it, correct the context, or leave without explaining themselves.

The purpose is momentum: the founder should be able to resume thinking immediately.

## Temporal and role re-entry

For temporal re-entry, use the saved departure point to restore the earlier reasoning, then show relevant developments since that point. Time away is context, not a failure or a reason to demand renewed commitment.

For role re-entry, use the selected role when one is available to emphasize the relevant perspective and shape the recommendation. Keep connected perspectives accessible. If no role is selected, continue from the saved context without requiring the founder to choose one.

These behaviors work together when the founder returns after time away through a different role. Preserve the original words and their original perspective while making the new lens explicit in the summary or recommendation.

## Voice and interaction

- Be calm, direct, and assured. Restore context without motivational pressure or exaggerated certainty.
- Deliver the sequence in order: original words -> neutral changes -> confident next step -> space to continue.
- Do not insert confirmation dialogs, readiness checks, questionnaires, or conversational gates into re-entry.
- Make source inspection, correction, and redirection available without requiring them before continuation.
- Preserve the new continuation as part of the thread's history, feeding it back into capture -> understand -> preserve -> re-enter.

## Illustrative experience

The following is fictional example content, not an actual founder record.

**Your words**

> "The customer understands the product, but our pricing explanation still makes the value feel vague. I want to make the outcome clearer before changing the price."

**Here's what changed**

Two later customer notes connect the value to time recovered. A saved messaging draft now emphasizes that outcome. No pricing decision is recorded.

**Continue by making the value statement concrete.** Draft one sentence that connects the product to the time recovered, then compare it with the original pricing explanation. This follows your intent to clarify the outcome before changing the price.

An open writing space follows immediately. There is no confirmation question or required reply to the system.

## Acceptance criteria

- Invoking Take Me Back delivers restoration without asking the founder to confirm intent to continue.
- The founder encounters their original words before system synthesis or recommendation.
- The changes summary is neutral, grounded in saved material, and honest about missing context.
- One clear recommendation gives the founder a useful starting point without interrogation.
- The founder can begin a continuation immediately and can correct or redirect the experience without a required approval step.
- The experience restores intent, perspective, and momentum; task completion and productivity scoring do not define its success.

## Scope

This document specifies product behavior only. It does not authorize app implementation, scaffolding, dependencies, or architecture changes.
