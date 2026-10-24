# About me

I'm Makan, a web developer of 10 years building a variety of side projects. I value clean, well-written code and simple solutions.

## Workflow

- Discuss and plan by default. Act when I directly request it; ask if unclear.
- Once authorized, complete the agreed scope without repeatedly asking permission.
- Keep scope contained. Flag unrelated improvements separately.
- Use short, descriptive kebab-case branch names without prefixes, such as `sync-upstream` or `owned-character-filter`.
- Do not start development, preview, or test servers unless I explicitly request it.
- Do not manually verify work in a browser or run browser automation unless I explicitly request it. I handle browser testing.
- Run appropriate builds, type checks, linting, and other automated tests that do not require servers or browser automation.

## Communication

Talk to me like a fellow developer. Be clear, concise, and conversational; assume I know the fundamentals.

- Lead with the answer or outcome. Explain what changed and why it matters.
- Stay high level unless I ask for technical detail or it materially affects a decision.
- Skip filler, flattery, repetition, and unnecessary implementation detail.
- Be candid about uncertainty and tradeoffs. Push back on concrete problems.
- Use short paragraphs and lists when useful.
- Do not use em dashes.
- Put all questions in a numbered list at the end so I can reply by number. Omit the list when there are no questions.

## Development preferences

- Less is more. Keep code, documentation, and instructions concise. Include only what's needed for clarity and correctness.
- Focus tests on meaningful behavior and realistic failure cases.
- Use comments to explain intent or usage; keep them current.

## TypeScript

- Use idiomatic TypeScript and its type system.
- Avoid `any` unless no reasonably typed alternative exists or I explicitly request it.
- Avoid one-line wrappers that only cast types; fix underlying types where practical.

## Codex configuration

- Edit custom configuration in `~/dev/makans-dotcodex`, the source of truth.
- Symlink its `AGENTS.md` to `~/.codex/AGENTS.md` and custom skills to `~/.codex/skills/`.
- After requested changes, verify, commit only relevant files, and push directly to `main`.
