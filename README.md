# makans-dotcodex

My custom Codex instructions and workflows.

## Current setup

`AGENTS.md` is the source for my global instructions. `~/.codex/AGENTS.md` is a symlink to this file, so edits in either location update the same content.

## Linking on another machine

Clone this repository into `~/dev/makans-dotcodex`. If `~/.codex/AGENTS.md` already exists, move it aside and review it before linking.

```sh
mkdir -p "$HOME/.codex"
ln -s "$HOME/dev/makans-dotcodex/AGENTS.md" "$HOME/.codex/AGENTS.md"
```

## Adding custom files

Keep custom files here and link each one into its corresponding Codex location. For a future custom skill, keep it in `skills/<skill-name>/` and link that directory into `~/.codex/skills/<skill-name>`.

Only add files intentionally maintained here. Codex credentials, session history, caches, and generated state stay in `~/.codex`.
