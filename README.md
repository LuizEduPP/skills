# AI Skills Collection

> 🌐 Languages: **English** | [Português (BR)](README.pt-BR.md) | [Español](README.es.md)

A curated collection of portable AI skills - templates, guides, and automations that work with any AI assistant.

## What Are Skills

Skills are reusable knowledge modules that enhance AI-assisted development. Each skill contains:
- Specialized documentation (SKILL.md)
- Automation scripts and tools
- Templates and references
- Standardized workflows

### Where Skills Work

Skills are **portable knowledge modules** that work wherever you use them:

- ✅ Any AI assistant that can read markdown files
- ✅ Claude Code, Claude Desktop, Claude Web
- ✅ Copilot Chat, Cursor, Windsurf, Gemini CLI
- ✅ Even manual reference - just read the SKILL.md files

The `SKILL.md` format is plain markdown with frontmatter - usable anywhere.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Skill Categories](#available-skills)
  - [Development](#development)
  - [Architecture & Design](#architecture--design)
  - [Documents & Presentations](#documents--presentations)
  - [Frontend & UI](#frontend--ui)
  - [Data & Analytics](#data--analytics)
  - [DevOps & Tools](#devops--tools)
  - [Planning & Management](#planning--management)
  - [Content & Copywriting](#content--copywriting)
  - [Career & Professional](#career--professional)
  - [Memory & Systems](#memory--systems)
  - [Skill Management](#skill-management)
- [How to Use](#how-to-use)
- [Creating a New Skill](#creating-a-new-skill)
- [Contributing](#contributing)
- [License](#license)

## Repository Structure

```
skills/
├── [skill-name]/
│   ├── SKILL.md              # Main documentation
│   ├── scripts/              # Automation scripts
│   ├── references/           # Reference guides
│   └── templates/            # Reusable templates
```

## Available Skills

<details>
<summary><strong>Development</strong> — 13 skills</summary>

| Skill | Description |
|-------|-------------|
| `code-reviewer` | Automated code analysis (PRs, quality checks) |
| `code-commit` | Commit code changes with structured messages |
| `playwright` | End-to-end testing with Playwright |
| `playwright-skill` | Browser automation with Playwright |
| `webapp-testing` | Web application testing toolkit |
| `systematic-debugging` | Structured debugging and bug analysis |
| `debugging-strategies` | Systematic debugging techniques |
| `test-create` | Test case generation |
| `chrome-devtools` | Chrome DevTools automation and debugging |
| `async-python-patterns` | Python asyncio and concurrent programming |
| `modern-javascript-patterns` | Modern JavaScript patterns (ES6+) |
| `sql-optimization-patterns` | SQL query optimization strategies |
| `subagent-driven-development` | Implementation with subagents |

</details>

<details>
<summary><strong>Architecture & Design</strong> — 5 skills</summary>

| Skill | Description |
|-------|-------------|
| `architecture-diagrams` | Architecture diagrams (Mermaid, PlantUML) |
| `architecture-patterns` | Architecture patterns (Clean, Hexagonal, DDD) |
| `senior-architect` | Architecture assessment and technical decisions |
| `design-create` | Design document creation |
| `senior-frontend` | Frontend development (React, Next.js, TypeScript) |

</details>

<details>
<summary><strong>Documents & Presentations</strong> — 7 skills</summary>

| Skill | Description |
|-------|-------------|
| `docx` | Word document creation and editing |
| `xlsx` | Excel spreadsheet manipulation |
| `pptx` | Technical PowerPoint presentation editing |
| `ppt-creator` | Presentation creation with storytelling |
| `pdf` | PDF manipulation |
| `markitdown` | Convert files to Markdown |
| `obsidian-markdown` | Obsidian Flavored Markdown |

</details>

<details>
<summary><strong>Frontend & UI</strong> — 7 skills</summary>

| Skill | Description |
|-------|-------------|
| `frontend-design` | Web interface design |
| `ui-styling` | Styling with Tailwind CSS and shadcn/ui |
| `ui-designer` | Design systems and implementation |
| `theme-factory` | Visual themes for artifacts |
| `canvas-design` | Visual design and graphic art |
| `react-native-expert` | React Native development |
| `applying-brand-guidelines` | Corporate branding and styling |

</details>

<details>
<summary><strong>Data & Analytics</strong> — 4 skills</summary>

| Skill | Description |
|-------|-------------|
| `data-analysis` | Data analysis and visualization |
| `analyzing-financial-statements` | Financial analysis and metrics |
| `creating-financial-models` | Financial modeling (DCF, Monte Carlo) |
| `rag-implementation` | RAG systems with vector databases |

</details>

<details>
<summary><strong>DevOps & Tools</strong> — 6 skills</summary>

| Skill | Description |
|-------|-------------|
| `git-advanced-workflows` | Advanced Git workflows |
| `browser-use` | Browser automation via CLI |
| `agent-browser` | Browser automation for agents |
| `workspace-setup` | Development environment setup |
| `file-organizer` | File and folder organization |
| `mcp-builder` | MCP server construction |

</details>

<details>
<summary><strong>Planning & Management</strong> — 6 skills</summary>

| Skill | Description |
|-------|-------------|
| `planning-with-files` | File-based planning |
| `writing-plans` | Implementation plan creation |
| `executing-plans` | Structured plan execution |
| `doc-coauthoring` | Documentation co-authoring |
| `req-create` | Requirements documentation |
| `experience-record` | Experience and lessons learned recording |

</details>

<details>
<summary><strong>Content & Copywriting</strong> — 3 skills</summary>

| Skill | Description |
|-------|-------------|
| `copywriter` | Compelling copy for web and marketing |
| `brainstorming` | Structured brainstorming sessions |
| `deep-research` | Deep multi-source research |

</details>

<details>
<summary><strong>Career & Professional</strong> — 2 skills</summary>

| Skill | Description |
|-------|-------------|
| `resume-manager` | Resume creation and career tracking |
| `scientific-critical-thinking` | Scientific claims evaluation |

</details>

<details>
<summary><strong>Memory & Systems</strong> — 2 skills</summary>

| Skill | Description |
|-------|-------------|
| `memory-systems` | Agent memory systems |
| `context-optimization` | Context optimization for LLMs |

</details>

<details>
<summary><strong>Skill Management</strong> — 4 skills</summary>

| Skill | Description |
|-------|-------------|
| `skill-creator` | Creating effective skills |
| `skill-lookup` | Find and install skills |
| `skill-writer` | Writing Agent Skills |
| `skills-discovery` | Search and install Agent Skills |

</details>

## How to Use

### Loading a Skill

In AI assistants like Claude Code, Windsurf, and Cursor, skills are automatically loaded based on task description. You can also explicitly mention:

```
Use skill [skill-name] for [task]
```

### Creating a New Skill

1. Create a directory with the skill name
2. Add `SKILL.md` with frontmatter:

```markdown
---
name: my-skill
description: What this skill does. Use when [use cases].
---

# Skill Title

Content and instructions...
```

3. Add scripts, templates, and references as needed

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on creating new skills.

Quick contribution checklist:
- [ ] Create `SKILL.md` with proper frontmatter
- [ ] Add skill to appropriate category in README
- [ ] Test any scripts or code examples
- [ ] Submit PR with clear description

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

**Total Skills: 59** | Community contributions welcome | Last Updated: April 2026
