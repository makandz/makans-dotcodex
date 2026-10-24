---
name: file-pr
description: Create or update pull requests using Makan's preferred titles and descriptions.
---

Base the title and body on the final changes in the PR.

## Titles

Use conventional commit syntax: `type: description`.

Typically reserve scopes for monorepos, using the package name
that is the primary target: `type(package): description`.
Omit the scope when no package is the clear primary target.

Describe the overall change rather than listing individual edits.

## Bodies

Write like a developer explaining the change to another developer.
Use plain, natural language and focus on what changed and why.

Keep the description high level but substantive. Give related
changes context rather than turning the body into a checklist.

Prefer short paragraphs. Use bullets sparingly for distinct details
that are easier to scan as a list. Do not force every description
into the same structure.

Let the scope determine the length. Avoid repeating the title,
narrating the implementation process, or listing every file changed.

Omit build and test results, routine verification details,
and boilerplate sections. Include technical details or limitations
only when they materially help someone understand the change.
