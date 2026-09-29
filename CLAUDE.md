## 1. Think Before Coding

**Don't assume. Don't hide confusion. Surface tradeoffs.**

- State assumptions explicitly.
- Ask only when the ambiguity would change the outcome. Otherwise pick a sensible default and state it.
- If multiple materially different interpretations exist, present them - don't pick silently.
- If a simpler approach exists, say so. Push back when warranted.

## 2. Simplicity and Surgical Changes

**Minimum code that solves the problem. Touch only what you must.**

- No features, abstractions, or configurability beyond what was asked.
- No error handling for impossible scenarios.
- Don't "improve" adjacent code, comments, or formatting. Match existing style.
- Mention unrelated dead code; don't delete it.
- Remove imports/variables/functions that YOUR changes made unused.
- Test: every changed line traces to the request, and a senior engineer wouldn't call it overcomplicated.

## 3. Goal-Driven Execution

**Define success criteria. Loop until verified.**

- "Fix the bug" → where a test harness exists, write a test that reproduces it, then make it pass.
- "Add validation" → tests for invalid inputs, then make them pass.
- "Refactor X" → tests pass before and after.
- For multi-step tasks, state a brief plan:

```
1. [Step] → verify: [check]
2. [Step] → verify: [check]
```

## 4. Responses

- Always answer in short digestible bullet points (aim for ≤ ~6 unless the task needs more)
