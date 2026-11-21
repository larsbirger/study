# Markdown Templates (`.templates_markdown_files/`)

This folder stores reusable Markdown boilerplate files that are copied into generated folders via `copy_from:` entries in [`../.templates/*.yaml`](../.templates/README.md).

These files also serve as **ready-to-use examples** alongside [`.templates/`](../.templates/) — you can inspect them or copy both folders into your own repository to get started quickly with `gendir`.

## What to Expect Here

- Flat `.md` template files only (no subfolders)
- Static Markdown documents describing folder purposes, checklists, and starter structures

### Current Example Markdown Templates

- [`base_readme.md`](base_readme.md) — Weekly notes README used by [`.templates/week.yaml`](../.templates/week.yaml).
- [`assignment_readme.md`](assignment_readme.md) — Root assignment README (overview, TODO checklist, and folder guide) used by [`.templates/assignment.yaml`](../.templates/assignment.yaml).
- [`assignment_input_readme.md`](assignment_input_readme.md) — README for an assignment's `input/` folder.
- [`assignment_workspace_readme.md`](assignment_workspace_readme.md) — README for an assignment's `workspace/` folder.
- [`assignment_assets_readme.md`](assignment_assets_readme.md) — README for an assignment's `assets/` folder.
- [`assignment_output_readme.md`](assignment_output_readme.md) — README for an assignment's `output/` folder.

## Notes

- Files referenced via `copy_from: ".templates_markdown_files/<file>.md"` are copied verbatim into the generated structure.
- This `README.md` documents the template folder itself and is not copied into generated projects.
- See [`../examples/README.md`](../examples/README.md) for usage examples and [`../docs/templates.md`](../docs/templates.md) for the full YAML template reference.
