# AGENTS.md - global rules

These rules apply to every project, for every coding agent. Project-level
AGENTS.md / CLAUDE.md files add to this, they don't replace it.

- Never use the em dash ("—"). Use a plain dash ("-") instead.
- Don't leave unnecessary comments. Only add a comment where it genuinely
  helps (a non-obvious "why", a gotcha, a tricky workaround) - never to
  restate what the code already says. When a comment is warranted, keep it
  short and concise.
- For one-off/on-demand package execution (e.g. running a binary that isn't
  installed as a project script), use `bunx` instead of `npx`, unless the
  project specifies otherwise. This avoids bloating npm's cache with
  packages only needed for a single run.
