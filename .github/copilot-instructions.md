<!--
This file is an AI guidance surface for Copilot-style coding agents. It was generated
automatically because the repository currently contains no discoverable project files.
Edit and adapt the sections below to reference real files once your project has code.
-->

# Copilot instructions for this repository

These instructions help AI coding agents get productive quickly in this repository.
Keep this file short and actionable — prefer exact file paths and patterns over vague advice.

1. Repository status
   - As of generation, the repository root appears empty (no source, README, or package files).
   - If you add code, update the "Key entrypoints" and "Build & test" sections below.

2. Key entrypoints (update these when files exist)
   - Example: `package.json` — top-level JS project config. If present, use `npm run build`/`npm test`.
   - Example: `pyproject.toml` / `requirements.txt` — Python projects. Use `python -m pytest` to run tests.
   - Example: `src/` or `app/` — primary application code. Prefer changes here for feature work.

3. Architecture notes (what to capture when present)
   - Look for a top-level `services/`, `api/`, or `frontend/` folder to identify service boundaries.
   - Identify a single source-of-truth for configuration (e.g., `config/`, `.env`, or `settings.py`).
   - Note runtime boundaries (e.g., server vs. worker vs. client). Add them here once discovered.

4. Build & test workflows (examples to adapt)
   - Node: `npm ci` then `npm test` (or `npm run build` then `npm start`).
   - Python: create venv, `pip install -r requirements.txt`, then `pytest`.
   - If CI uses GitHub Actions, check `.github/workflows/*.yml` for exact commands.

5. Project-specific conventions to document (update with real examples)
   - File naming conventions (e.g., `*.spec.ts` for tests, `*_test.py` for Python tests).
   - Linting/formatting: reference config files (`.eslintrc`, `pyproject.toml`, `prettierrc`).
   - Branching or commit message rules: reference CONTRIBUTING.md if present.

6. Integration points to look for
   - External services: check for `services/*.config`, `terraform/`, or `docker-compose.yml`.
   - Third-party APIs: search for keys or clients under `lib/` or `clients/`.

7. How the agent should make changes
   - Make small, well-scoped changes with tests. When adding files, update README and run tests.
   - If unsure about which service to modify, add a brief note in the PR describing reasoning.

8. Example actionable prompts for the agent (replace placeholders)
   - "Add unit tests for `src/foo.py` covering null/empty inputs and an HTTP error path."
   - "Implement `GET /health` in `services/api/app.py` returning 200 and JSON `{status: 'ok'}`."

9. When you update this file
   - Replace generic sections above with concrete file paths and commands observed in the repo.
   - Keep entries compact — prefer single-line commands and 1–2 example code paths.

If you want, I can now:
- scan the repo again once you add code and automatically update the sections above to reference concrete files,
- or adapt this template into a project-specific version if you point me to key entry files (README, package.json, pyproject.toml, etc.).

Please tell me which files to inspect next or add the project files and I'll regenerate specific instructions.
