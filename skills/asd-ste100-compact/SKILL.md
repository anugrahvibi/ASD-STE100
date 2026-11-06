---
name: asd-ste100-compact
license: MIT
description: "Write compact responses in ASD-STE100 format without dropping important technical detail. Use when the user invokes the compact ASD-STE100 option."
---

# ASD-STE100 Compact

Write the requested content in **ASD-STE100 format**. This skill includes the core technical-detail protections; it does not require the user to invoke another skill.

## Preserve technical meaning

- Simplify wording and sentence structure. Do not simplify the underlying technical content.
- Preserve important concepts, mechanisms, constraints, values, conditions, caveats, warnings, steps, and edge cases.
- Keep precise technical terms when simpler words would be vague or incorrect. Add a brief explanation only when it helps; do not replace the term.
- Keep code, identifiers, commands, arguments, literal strings, paths, filenames, versions, formulas, and quoted source text exactly as supplied.
- If concise wording conflicts with technical accuracy, keep the detail.

## Make it compact

- Remove filler, repeated explanations, and redundant transitions.
- Prefer a direct sentence, list, or compact table when it carries the same meaning with fewer words.
- Keep evidence, uncertainty, qualifiers, and examples that are needed to understand or use the result. Do not meet an assumed word or token limit by deleting important content.
- Do not add a summary layer or fixed sections unless the task needs them.
- If the full answer is too long for one response, divide it into useful parts and state what remains. Do not silently truncate the plan or result.

## Evidence and uncertainty

- Mark a material unverified inference with `[HYPOTHESIS]` and an external dependency with `[EXTERNAL]`. Use `[FACT]` only when the verified status of a critical claim needs to be explicit.
- Use these tags selectively, not on every line. Cite important external claims near the claim when a reliable source is available or requested.

Apply ASD-STE100 style to prose. Preserve code and protected technical text exactly. Do not claim formal ASD-STE100 compliance unless the relevant standard and vocabulary resources were checked.
