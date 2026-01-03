# Claude Code Context

This document provides context and instructions for working with this repository using Claude Code.

## Project Overview

This is the ClaudeCodeTest repository - a test environment for working with Claude Code.

## Repository Structure

```
ClaudeCodeTest/
├── README           # Main project readme
└── CLAUDE.MD        # This file - Claude Code context and instructions
```

## Development Workflow

### Branch Strategy
- Main development occurs on feature branches
- Current branch: `claude/update-claude-md-WpNoy`
- All changes should be committed and pushed to the appropriate Claude branch

### Git Commands
```bash
# Check current status
git status

# Stage changes
git add .

# Commit changes
git commit -m "Description of changes"

# Push to remote (with retry logic for network issues)
git push -u origin claude/update-claude-md-WpNoy
```

## Common Tasks

### Adding New Files
When creating new files, consider:
- Appropriate file naming conventions
- Necessary documentation
- Test coverage if applicable

### Updating Documentation
- Keep README and CLAUDE.MD in sync
- Document any architectural decisions
- Update examples when functionality changes

## Testing

(Add testing instructions as the project develops)

## Architecture Notes

(Document key architectural decisions and patterns as the project grows)

## Helpful Context for Claude

### Current State
- Repository is in early stages
- Minimal files present
- Good opportunity to establish patterns and conventions

### Development Priorities
(Update as priorities become clear)

## Notes

- This file should be updated as the project evolves
- Add specific context that helps Claude understand your codebase
- Include any project-specific conventions or patterns

---

Last updated: 2026-01-03
