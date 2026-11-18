# Repo conventions

- Skills live at `skills/<category>/<skill-name>/SKILL.md`. Categories: `engineering`, `marketing`.
- Skill folder names are kebab-case and match the `name` in the SKILL.md frontmatter.
- When adding or removing a skill, update both the category `README.md` and the `skills` array in `.claude-plugin/plugin.json`.
- Keep skills small and composable; put long reference material in sibling files and link to it from SKILL.md.
