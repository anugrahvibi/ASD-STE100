---
name: asd-ste100-map
license: MIT
description: "Explain a full project iteration as a clear MAP in ASD-STE100 format, with technical detail preserved. Use when the user invokes MAP for an iteration overview."
---

# ASD-STE100 MAP

Write the requested content in **ASD-STE100 format**. MAP is an optional structure for explaining a whole project iteration. This skill includes the core technical-detail protections; it does not require the user to invoke another skill.

## Preserve technical meaning

- Simplify wording and sentence structure. Do not simplify the underlying technical content.
- Preserve important concepts, mechanisms, constraints, values, conditions, caveats, warnings, steps, and edge cases.
- Keep precise technical terms when simpler words would be vague or incorrect. Add a brief explanation only when it helps; do not replace the term.
- Keep code, identifiers, commands, arguments, literal strings, paths, filenames, versions, formulas, and quoted source text exactly as supplied.
- Do not omit a material risk, dependency, side effect, assumption, or unresolved question to make the map shorter.

## Use MAP for a whole iteration

Use these three sections when the user asks for a whole iteration overview:

1. **Outcome** — State the iteration goal and scope.
2. **Work map** — Group the work into useful phases. Include the important actions, technical decisions, and true prerequisites. Use `Condition: Step X must pass.` when one step depends on another.
3. **Checks and impact** — State the checks performed or planned, and how success will be judged. Include material risks, side effects, external dependencies, assumptions, and unresolved points only when they matter.

Keep the map compact, but preserve the detail needed to understand and review the iteration. Cite a file, request, or other source for an important action when that origin is available and useful. Do not force a source note onto every step.

If the request covers only a small change, one file, or a simple result, do not expand it into a full MAP. Use the concise ASD-STE100 form that fits the request.

## Report status accurately

- Distinguish planned checks from checks that were completed.
- Mark a material unverified inference with `[HYPOTHESIS]`; use `[EXTERNAL]` when an outcome depends on an outside service or dependency. Use `[FACT]` only when it helps show that a critical claim was checked.
- Use tags selectively. Cite important external claims near the claim when a reliable source is available or requested.
- Keep code and protected technical text exactly as supplied. Do not claim formal ASD-STE100 compliance unless the relevant standard and vocabulary resources were checked.
