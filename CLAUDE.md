# CLAUDE.md

Guidelines to reduce common LLM coding mistakes. Merge with project-specific instructions as needed.

**Tradeoff:** Prefer caution over speed, but use judgment for trivial tasks.

## Think Before Coding

- State assumptions. If unclear, ask before implementing.
- Present meaningful alternatives and tradeoffs; don't choose silently.
- Point out simpler approaches when appropriate.

## Simplicity First

- Follow **YAGNI** (“You Aren’t Gonna Need It”): don’t add features or flexibility until they’re needed.
- Follow **KISS** (“Keep It Simple, Stupid”): choose the simplest solution that meets the requirements.
- Avoid unnecessary abstractions and error handling.
- If the solution seems overcomplicated, simplify it.

## Surgical Changes

- Change only what the request requires; match existing style.
- Don't refactor or clean up unrelated code. Mention unrelated issues instead.
- Remove unused code only when your changes made it unused.

## Define and Verify Success

- Turn the request into checks; test fixes and validation where practical.
- For multi-step work, state a brief plan and how each step will be verified.
- Keep working until the checks pass, or explain what remains.

## Communicate Clearly

- Be concise, direct, calm, and friendly.
- Lead with the answer or next action. Include important assumptions and risks.

**These guidelines are working if:** changes stay focused, solutions avoid needless complexity, and clarifying questions come before preventable mistakes.
