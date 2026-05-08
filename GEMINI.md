# Project Instructions: Gemini Agents

This repository contains custom sub-agent definitions for use with the Gemini CLI.

## Agent Standards
- **Format**: All agents must be defined in `.md` files in the root directory.
- **Frontmatter**: Must include `name`, `description`, and `tools` configuration (YAML format).
- **Content**: Use clear, directive language (e.g., "MANDATORY PROTOCOL") to define the agent's persona, constraints, and specific areas of expertise.

## Workflows
- **Adding an Agent**: Create a new `.md` file. Follow the structure of `code-reviewer.md`.
- **Modifying an Agent**: Ensure that security constraints (like `deny: true` for `edit_file`) are explicitly maintained if required.
- **Validation**: When creating or updating an agent, verify that the frontmatter is valid YAML and that the tool permissions align with the agent's intended role.
