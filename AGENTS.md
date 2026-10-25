# About me

I'm Makan, a web developer of 10 years building a variety of side projects. I value clean, readable code and simple solutions.

## Workflow

- Discuss and plan by default. Act when I directly request it; ask if unclear.
- Once authorized, complete the agreed scope without repeatedly asking permission.
- Leave changes uncommitted for my review. Commit or push only after I give the go-ahead.
- An explicit request to file a PR authorizes the necessary branch creation, committing, pushing, and PR creation.
- Keep scope contained. Flag unrelated improvements separately.
- Use short, descriptive kebab-case branch names without prefixes. Check for existing local and remote names, and append a short random suffix when needed to avoid collisions.
- Do not install Node dependencies without my explicit approval, including automatic installs by tools such as `npx`.
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

- Write the simplest implementation that is easy to read and maintain. Readability takes priority over fewer lines.
- Keep code concise by removing unnecessary complexity, duplication, and indirection. Do not compress formatting or control flow just to make it shorter.
- Use descriptive names, conventional formatting, and straightforward control flow. Split dense expressions and nested ternaries into clear steps.
- Extract functions and components when they clarify a responsibility or isolate meaningful logic. Avoid both oversized functions and fragmentation into trivial helpers.
- Focus tests on meaningful behavior and realistic failure cases.

## Documentation and comments

- Document every function with a preceding `/** ... */` comment.
- Exported public functions and public methods need full JSDoc: a purpose summary, `@param` for each parameter, and `@returns` when they return a value.
- Private and internal functions need only a short description of their purpose or intent.
- Keep comments current and explain behavior, intent, or usage rather than narrating the implementation.
- For documentation and skills, include only instructions that change an agent's decisions. Remove generic advice, repetition, and speculative edge cases while retaining enough context to apply the instructions correctly.

## TypeScript

- Use idiomatic TypeScript and its type system.
- Prefer `type` for type definitions; use `interface` only when interface-specific features are needed.
- Avoid `any` unless no reasonably typed alternative exists or I explicitly request it.
- Avoid one-line wrappers that only cast types; fix underlying types where practical.

## Codex configuration

- Edit custom configuration in `~/dev/makans-dotcodex`, the source of truth.
- Symlink its `AGENTS.md` to `~/.codex/AGENTS.md` and custom skills to `~/.codex/skills/`.
- Changes to `~/dev/makans-dotcodex` are exempt from the review requirement. Verify, commit only relevant files, and push directly to `main`.
