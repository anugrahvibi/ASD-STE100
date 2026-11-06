---
name: asd-ste100
license: MIT
description: "Write responses in ASD-STE100 Simplified Technical English while preserving technical detail. Use when the user invokes this skill to format explanations, results, plans, or other prose."
---

# ASD-STE100

Write the requested content in **ASD-STE100 format**. This is a controlled technical-English format, not a request to replace technical content with a generic plain-language summary.

## Preserve technical meaning

- Simplify wording and sentence structure. Do not simplify the underlying technical content.
- Preserve the important concepts, mechanisms, relationships, constraints, values, conditions, caveats, warnings, steps, and edge cases.
- Keep a precise technical term when a simpler word would be vague or incorrect. If a brief explanation is needed, add it without replacing the term or repeating the explanation.
- Keep code, identifiers, commands, command-line arguments, literal strings, paths, filenames, versions, formulas, and quoted source text exactly as supplied. Write prose around them in ASD-STE100 style.
- If a rule of the writing style conflicts with technical accuracy, preserve technical accuracy and the exact technical term. Do not silently omit or weaken the detail.

## Keep the output easy to scan

- Use concise, direct sentences and remove filler or repeated points.
- Use headings, bullets, or tables only when they make the content easier to follow. Do not add a fixed summary, multiple layers, or extra sections to every response.
- Do not add lengthy plain-language paraphrases of technical material. Explain a term briefly only when that explanation helps the user understand the task.

## Show evidence and uncertainty when they matter

- Mark a material unverified inference with `[HYPOTHESIS]`.
- Use `[EXTERNAL]` when an outcome depends on an external service, API, or dependency.
- Use `[FACT]` only when it helps distinguish a critical claim that was checked in a source or system from an inference.
- Do not add a tag to every sentence or step. Do not present an assumption as verified.
- Give a source reference close to an important external claim or action when a reliable source is available or the user asks for one. Do not invent sources.

Apply the writing style to prose. Do not alter code or other protected technical text to make it appear compliant. Do not claim that the output has passed formal ASD-STE100 compliance checks unless it was checked against the relevant standard and vocabulary resources.
