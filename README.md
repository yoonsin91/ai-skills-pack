# AI Skills Pack

  A collection of reusable “skills” for different AI assistants (Codex, Claude, Gemini, and others).
  Each skill encodes a focused workflow, domain knowledge, or tool integration to make outputs more reliable and consistent.

  ## What’s inside

  Each skill lives in its own folder and includes:

  - `SKILL.md` (required): name, description, and usage workflow
  - Optional resources:
    - `scripts/` for reusable automation
    - `references/` for domain docs
    - `assets/` for templates or files used in outputs

  ## Skill format


  skill-name/
  ├── SKILL.md
  ├── scripts/        # optional
  ├── references/     # optional
  └── assets/         # optional


  ## How skills are used

  An assistant triggers a skill when a request matches the `description` in `SKILL.md`.
  The body of `SKILL.md` provides the steps and links to any resources needed.

  ## Notes

  - Keep `SKILL.md` concise and action‑oriented.
  - Put large docs in `references/`.
  - Prefer scripts for repeated or fragile steps.
