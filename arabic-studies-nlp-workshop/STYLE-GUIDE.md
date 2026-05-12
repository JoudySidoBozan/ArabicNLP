# Workshop Style Guide

This guide keeps the repository readable for absolute beginners while preserving an academic tone.

## Design Principles

| Principle | Use It For |
| --- | --- |
| Predictable structure | Help participants find their place quickly |
| Short sections | Reduce cognitive load during live teaching |
| Tables for routes and schedules | Make file paths, timing, and sequences scannable |
| Numbered steps for actions | Support learners who are copying commands or navigating software |
| Callouts for cautions | Separate important warnings from ordinary explanation |
| Plain language first | Introduce technical terms only when they are needed |

## Standard Page Pattern

Use this pattern for participant-facing Markdown files:

1. `# Title`
2. One-line metadata block if useful: audience, purpose, time, or tools.
3. Short opening paragraph.
4. A callout for the main idea or caution.
5. Tables for navigation or comparison.
6. Numbered steps for actions.
7. A short "what success looks like" or "what to notice" section.

## Callout Style

Use Markdown blockquotes for important notes:

```markdown
> **Note:** Keep this sentence short and actionable.
```

Recommended labels:

- `Note`
- `For beginners`
- `Academic caution`
- `Teaching note`
- `If something breaks`

## Tone

Use direct, calm language:

- Prefer "Run this command" over "Simply execute".
- Prefer "What to notice" over "Analysis".
- Prefer "This output is evidence to interpret" over "The model says".
- Avoid jokes, decorative symbols, or unexplained technical shorthand.

## Formatting Rules

- Use sentence case for headings.
- Use tables for file maps, schedules, and reading lists.
- Use fenced code blocks for commands and Python examples.
- Use inline code formatting for file names, commands, variables, and package names.
- Keep participant-facing paragraphs short.
- Avoid long bullet lists when a table would be easier to scan.
