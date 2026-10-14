# Instructions for coding agents

## Read the manifesto first

Before planning, designing, or coding, read [manifesto.md](manifesto.md) in full. Then read [README.md](README.md) for the defined MVP and current scope. Apply these instructions to all work in this repository, subject to the user's explicit directions.

**Xebrain is a founder's state of mind restoration system, not a project manager. Do not reinterpret it as a generic PM tool.**

## Preserve the product's purpose

- Make continuity of thought the primary objective. Do not substitute task throughput or productivity for successful restoration of context.
- Keep the loop of capture -> understand -> preserve -> re-enter intact.
- Support temporal re-entry: returning to thinking after time away with its earlier reasoning and subsequent changes visible.
- Support role re-entry: recovering the perspective associated with a founder's chosen responsibility while preserving connections to other perspectives.
- Center thoughts, intent, reasoning, uncertainty, context, and history. Do not default to projects, tasks, assignees, due dates, or completion status as the core model.
- Preserve original captures and distinguish them from interpretations. Make interpretations correctable and keep supporting source entries accessible.
- Do not invent context, certainty, decisions, or next steps that the founder has not recorded or confirmed.
- Treat roles as perspectives, not permission groups or task assignments. Treat a thread of thought as continuing reasoning, not a backlog.
- Keep possible next steps optional. Do not automatically convert thoughts into obligations.

## Scope and feature decisions

For each proposed feature, explain which part of the core loop it supports and how it helps the founder resume thinking. A familiar productivity feature is not justified merely because other apps have it.

Use the README's MVP as the initial scope. Task boards, deadline enforcement, team assignments, sprint planning, completion streaks, and productivity scoring are not part of that scope. Do not quietly expand the product into project management.

If an implementation request leaves a choice open, choose the behavior that best preserves the founder's context and agency. If a request materially changes the product's purpose, surface the conflict with the manifesto before implementing that change. Follow explicit user decisions and update the documentation when a change is authorized.

## Current work boundary

The current authorized work is documentation and MVP definition only. Do not create app code, scaffold a framework, install dependencies, or implement the MVP until the user separately requests implementation. This boundary can be superseded by a later explicit user request.

When implementation is authorized, validate the ability to recover thought across time and roles, the preservation of original material, and the distinction between recorded context and interpretation. Do not replace those outcomes with tests of task completion alone.
