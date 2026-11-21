# Templates (`.templates/`)

This folder stores the YAML template definitions used by `gendir` to generate folder and file structures.

The templates in this repository also serve as **ready-to-use examples** — you can inspect them to learn the YAML format, run them directly with `gendir`, or copy this folder (together with [`.templates_markdown_files/`](../.templates_markdown_files/)) into your own repository as a starting point.

## What to Expect Here

- Flat `.yaml` template files (no subfolders)
- Each `.yaml` filename (without the `.yaml` extension) is used directly as the template name in `gendir` (for example, `assignment.yaml` -> `gendir <category> assignment`)

### Current Example Templates

- [`assignment.yaml`](assignment.yaml) — Generates a school assignment folder (`README.md`, `input/`, `workspace/`, `assets/`, and `output/`) with an interactive `name` prompt and per-folder Markdown boilerplate.
- [`week.yaml`](week.yaml) — Generates a weekly notes folder (`u<WEEK_NUM>-<context>/`) with an `assets/` folder, an inline JSON Jupyter notebook, and `README.md` files.

## Notes

- Reusable Markdown files referenced with `copy_from:` live in [`../.templates_markdown_files/`](../.templates_markdown_files/README.md) rather than in this folder.
- Only `.yaml` files are scanned by `gendir`; this `README.md` is ignored by the CLI.
- See [`../examples/README.md`](../examples/README.md) for usage examples and [`../docs/templates.md`](../docs/templates.md) for the full YAML template reference.
