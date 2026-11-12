# Annotated technical examples

## TL;DR

Make an unfamiliar concept inspectable: a plain definition, a concrete artifact and explanations beside the relevant parts. Use the example below as an explanation pattern, not a mandatory slide layout.

## Drafting contract

1. **Define the capability.** State what it is and what it is for before introducing file mechanics. Distinguish a tool, its configuration and the guidance it loads.
2. **Show enough of the artifact to explain its use.** Use a trimmed source file when teaching its contents, a folder tree for package organization, or a concrete interaction for a protocol. Preserve source wording, syntax, order and conditions when trimming. Label invented examples as illustrative; keep company-specific material in project context.
3. **Explain each displayed part at its location.** Put a short purpose beside a filename, field, heading or action. In a folder tree, every non-root row follows **name — purpose**, including container folders: `references/ — Detailed guidance the agent consults`. Describe what the reader or agent uses it for, rather than repeating its name. Mark required versus optional parts when that distinction matters. Distinguish standard fields from author-chosen sections. Derive an explanation from the supplied source, not from a heading's possible meaning elsewhere.
4. **State responsibility directly when relevant.** Name what the engineer or reviewer decides and verifies. A generic benefit slogan is not an ownership statement.

## Company-neutral example: a reusable review skill

This is an illustrative teaching example, not a claim about an installed package.

**Definition:** Reusable instructions and resources for a recurring task.

**Package organization:**

```text
review-change/
├── SKILL.md                  — Required metadata and task instructions
└── references/               — Optional folder for supporting guidance
    └── review-checklist.md   — Review criteria used by this example
```

Supporting folders are optional in the skill format; this particular example uses its checklist.

**Example — review-change/SKILL.md (trimmed):**

```markdown
---
name: review-change
description: Use when reviewing a proposed code change before merge.
---
## Review method
Read references/review-checklist.md.
Inspect the changed behavior and relevant callers.
Report findings with evidence; do not modify files.
```

Place these explanations beside their targets, outside the file content:

- `name` — Identifies the skill.
- `description` — Explains when the skill is relevant.
- `Review method` — Instructions for this review task; an author-chosen heading.
- `references/review-checklist.md` — Supplies the criteria used during review.

**Human ownership:** Reviewers assess the findings and approve the change.

## Annotation and layout checks

- Keep the approved grouping of the artifact and its explanation. A targeted wording or styling request changes that part, not the whole arrangement.
- For a supplied visual reference, match the callout shape, placement and attachment. When the visual form remains unsettled, align one representative annotation before repeating it.
- Keep inline explanations readable and preserve tree stems when comments wrap.
- Place callouts close to their exact targets. Fit containers to the text with consistent small padding and short pointers; the source remains visually primary. Use the established secondary typography and palette, such as smaller italic notes in a muted color.
- Let short explanations occupy one line when they fit; wrap longer ones without squeezing the text or stretching a pointer across the artifact.
- Verify two things separately: a newcomer can explain the concept and each shown part; the rendered annotations point to the correct targets with readable spacing and intact connections. An overflow check proves neither understanding nor visual clarity.

Use a different form when the reader needs a workflow, comparison or decision rather than an explanation of an artifact. Trees and speech bubbles are options, not requirements for every page.
