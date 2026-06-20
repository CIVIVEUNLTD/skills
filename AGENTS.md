# Purpose

- This repo is the CIVIVEUNLTD fork of `mattpocock/skills`.
- It stores reusable engineering and productivity agent skills that can be installed into Scott's global Codex skill root.
- Keep upstream attribution intact and maintain Codex compatibility for any skill intended to be installed globally.

# Ownership

- Owner: Scott Berry / Civive Unlimited.
- Upstream: `https://github.com/mattpocock/skills`.
- Fork remote: `https://github.com/CIVIVEUNLTD/skills`.

# Local Contracts

- Preserve MIT license attribution from upstream.
- Keep `origin` pointed at the CIVIVEUNLTD fork and `upstream` pointed at Matt Pocock's repo.
- Do not overwrite Scott's existing global skills with upstream versions unless the replacement is intentional and validated.
- Do not install `deprecated`, `in-progress`, or `personal` skills globally by default.

# Work Guidance

- Read the specific `SKILL.md` before editing or installing a skill.
- For Codex-installed skills, frontmatter must validate with the Codex skill validator.
- Treat upstream pull-ins as source material, then adapt lightly for Scott's Codex environment.
- Keep changes small enough to rebase or compare against upstream later.

# Verification

- Validate changed or installed skills with:
  `C:\Users\scott\.cache\codex-runtimes\codex-primary-runtime\dependencies\python\python.exe C:\Users\scott\.codex\skills\.system\skill-creator\scripts\quick_validate.py <skill-folder>`
- After GitHub operations, verify `git status`, remotes, branch, and recent commits.

# Child DOX Index

- `skills\engineering\`: Active engineering workflow skills.
- `skills\productivity\`: Active general workflow skills.
- `skills\misc\`: Specialized utilities; install only when directly useful.
- `skills\deprecated\`: Upstream deprecated skills; do not install by default.
- `skills\in-progress\`: Experimental upstream skills; do not install by default.
- `skills\personal\`: Upstream personal workspace skills; do not install by default.
- `scripts\`: Upstream helper scripts.
- `docs\`: Upstream documentation.
