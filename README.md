# ASD-STE100

*Independent AI writing skills inspired by ASD-STE100 Simplified Technical English.*

**Clearer AI writing. Technical detail stays.**

Three small Agent Skills that guide an AI to write in ASD-STE100 style while keeping the technical meaning, terms, and important conditions intact.

## Install

Install the main skill:

```sh
npx skills add anugrahvibi/ASD-STE100 --skill asd-ste100
```

Add the optional skills when you want them:

```sh
npx skills add anugrahvibi/ASD-STE100 \
  --skill asd-ste100-compact \
  --skill asd-ste100-map
```

The installer will ask which supported agent to use. To install for your account across projects, add `--global`.

## Use

Ask your agent to use the skill. The exact command depends on the app. For example:

- **Codex:** `$asd-ste100`
- **Claude Code:** `/asd-ste100`

The main skill is for everyday answers, explanations, results, and plans. The other two are optional:

- **Compact** keeps the answer shorter while preserving details that matter.
- **MAP** gives a whole project iteration three sections: Outcome, Work map, and Checks and impact.

## Why I made this

I often find AI-written explanations, plans, and documentation hard to read. But asking for a simpler answer can remove technical details that matter. I made these skills to make the writing clearer while keeping the technical meaning intact.

## Example

**Before**

> If the request times out, retry it. This may create a second order if the first request succeeded but its response was lost.

**With the skill**

> If the request times out, check the order status before you retry. The first request may have succeeded even if the client did not receive the response. A second request can create a duplicate order if the operation is not idempotent.

The wording is easier to follow. The technical condition and the term `idempotent` stay.

## What the skills do

- Use shorter sentences and direct wording.
- Keep technical terms when a simpler word would be inaccurate.
- Preserve code, commands, names, values, conditions, risks, and important edge cases.
- Mark uncertainty and cite important sources when needed.
- Use Compact or MAP only when you ask for that option.

These skills guide an AI's writing. They do not check or certify formal ASD-STE100 compliance. They do not include the official standard or its vocabulary list.

## Independence and license

This is an independent community project. It is not affiliated with, approved, or endorsed by ASD. See [NOTICE.md](NOTICE.md) for details. The skill files and project documentation are provided under the [MIT License](LICENSE).
