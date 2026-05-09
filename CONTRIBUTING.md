# Contributing to Skills Collection

Thank you for your interest in contributing! This document provides guidelines for adding new skills.

## How to Contribute

### Creating a New Skill

1. **Fork the repository** and create a feature branch:
   ```bash
   git checkout -b feature/my-new-skill
   ```

2. **Create the skill directory**:
   ```bash
   mkdir my-skill
   ```

3. **Add SKILL.md with proper frontmatter**:
   ```markdown
   ---
   name: my-skill
   description: Clear description. Use when [specific use cases].
   ---

   # Skill Title

   ## Overview
   Brief explanation of what this skill does.

   ## Usage
   Instructions on how to use the skill.

   ## Examples
   Code examples or usage patterns.
   ```

4. **Optional additions**:
   - `scripts/` - Automation scripts
   - `references/` - Reference guides and documentation
   - `templates/` - Reusable templates

5. **Update README.md** - Add your skill to the appropriate category

6. **Submit a Pull Request** with a clear description

## Skill Guidelines

### Required
- [ ] SKILL.md with proper frontmatter (name, description)
- [ ] Clear, actionable description
- [ ] English language (for consistency)
- [ ] Host-agnostic wording unless the skill is intentionally platform-specific

### Recommended
- [ ] Usage examples
- [ ] Code snippets where applicable
- [ ] Reference guides for complex skills
- [ ] Scripts for automation tasks
- [ ] Generic path placeholders such as `<skill-root>` or `<workspace>`
- [ ] Compatibility notes separated from core instructions

### Editorial Standards

- Use direct, imperative prose instead of conversational filler
- Prefer Title Case for section headers
- Reuse common section names when they fit: `Overview`, `When to Use`, `Quick Start`, `Instructions`, `Examples`, `Best Practices`
- Keep examples concrete, portable, and free of host-specific defaults unless the skill is explicitly platform-specific
- Put vendor-specific notes in clearly labeled compatibility sections instead of the main workflow

### Description Format

The description in frontmatter should follow this pattern:
```
[What it does]. Use when [specific trigger conditions].
```

Example:
```yaml
description: Create professional slide decks from topics. Use for presentations, pitches, or keynotes.
```

## Branch Strategy

- `main` - Production-ready skills
- `feature/[skill-name]` - New skill development
- `docs/[description]` - Documentation updates

## Code Style

- Use clear, concise language
- Include code comments for complex logic
- Follow existing patterns in the repository
- Test scripts before submitting
- Avoid coupling the main instructions to a single IDE, assistant, or app
- If a host-specific example is necessary, label it as an example rather than the default path

## Review Process

1. All submissions require review
2. Skills should be unique (check for duplicates)
3. Documentation must be complete
4. Examples should be tested and working

## Validation

Run the repository checks before submitting:

```bash
python3 scripts/lint_skills.py
```

## Questions?

Open an issue for questions or discussion about new skills.
