# Scripts

Helper scripts for repository automation, renaming, and templating.

## Available Scripts

*(Add scripts here as you create them.)*

## Suggested Scripts to Add

| Script | Purpose |
|--------|---------|
| `new-unit.sh <domain> <source> <unit-id>` | Scaffold a new unit folder with `.tex` and `.ipynb` templates |
| `new-log.sh` | Create today's daily log file from a template |
| `lint-bib.py` | Check `bibliography/references.bib` for missing fields |

## Conventions

- Shell scripts: `kebab-case.sh`, executable (`chmod +x`).
- Python scripts: `kebab-case.py`.
- No hard-coded absolute paths — use paths relative to the repo root or `$REPO_ROOT`.
