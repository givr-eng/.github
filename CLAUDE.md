# CLAUDE.md

Givr's **public** organisation `.github` repo (`givr-eng/.github`). Anything committed here is visible to everyone.

## Layout

- `README.md` - describes the repo itself.
- `profile/README.md` - rendered as the public organisation profile on github.com/givr-eng.
- `.claude/settings.local.json` - local Claude settings, not part of the content.

There is no code, build or test suite. Changes are edits to the Markdown, pushed to `main`.

## Conventions

- Public audience: no internal detail, secrets or unreleased plans. Internal material belongs in the sibling
  `.github-private` repo.
- Keep `profile/README.md` consistent with `.github-private/profile/README.md` where they overlap (repo list).
- Givr is a UK-led charity platform; use British English unless the reader is American.

## Documentation vs code

When a repository's documentation and its existing code disagree, follow the conventions in the existing code. In your final reply, list each inconsistency you found between the documentation and the code.
