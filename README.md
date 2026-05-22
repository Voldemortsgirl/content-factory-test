# Content Factory

A shared repository for AI workflow configs, prompts, and recipes.

## Structure

| Folder | Contents |
|--------|----------|
| `claude/` | Claude project configs (CLAUDE.md) and reusable prompts |
| `goose/` | Goose recipe YAML files, organized by use case |

## How to use

- **Claude configs**: Copy the relevant `CLAUDE.md` into your project root, or reference prompts from `claude/prompts/`.
- **Goose recipes**: Run a recipe with `goose run <recipe-file>.yaml` from the `goose/recipes/` folder.
