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

### Recommended
- [ ] Usage examples
- [ ] Code snippets where applicable
- [ ] Reference guides for complex skills
- [ ] Scripts for automation tasks

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

## Review Process

1. All submissions require review
2. Skills should be unique (check for duplicates)
3. Documentation must be complete
4. Examples should be tested and working

## Questions?

Open an issue for questions or discussion about new skills.
