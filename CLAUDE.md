# Claude Context Document

This document provides context for Claude Code sessions when working with this prompt engineering repository.

## Project Overview

This is a **prompt engineering repository** containing a curated collection of high-quality, token-efficient prompts organized by category. The project is purely focused on prompt templates and frameworks - there is no executable code, dependencies, or build processes.

## Repository Structure

```
prompt-engineering/
├── README.md                    # Main project documentation
├── CLAUDE.md                   # This context file
└── prompt-library/             # Core prompt collection
    ├── README.md              # Library navigation and overview
    ├── coding/README.md       # Software development prompts
    ├── writing/README.md      # Content creation prompts  
    ├── analysis/README.md     # Problem-solving prompts
    ├── business/README.md     # Strategy and planning prompts
    └── creative/README.md     # Innovation and brainstorming prompts
```

## Content Nature

- **Documentation-only**: All files are Markdown documentation
- **Template-based**: Prompts use `{variable}` placeholder syntax
- **Category organization**: 5 main domains (coding, writing, analysis, business, creative)
- **Tag system**: `#quick`, `#expert`, `#template`, `#systematic`, `#creative`

## Working with This Repository

### When asked to add new prompts:
1. Determine the appropriate category (coding/writing/analysis/business/creative)
2. Follow the existing format and tagging system
3. Include clear variable placeholders using `{variable}` syntax
4. Add appropriate tags based on prompt characteristics
5. Update the category README.md with the new prompt

### When asked to modify existing prompts:
1. Read the relevant category README.md file first
2. Maintain the established format and structure
3. Preserve the tagging system
4. Ensure consistency with other prompts in the same category

### File Structure Pattern:
Each category README.md follows this pattern:
- Header with category description
- Sections organized by use case
- Individual prompts with:
  - Descriptive title
  - Tags in bold
  - Code block with prompt template
  - Clear variable placeholders

## Key Principles

1. **Token efficiency**: Every word should add value
2. **Expert thinking**: Prompts should encourage high-level reasoning
3. **Reusability**: Template-based design for multiple contexts
4. **Clarity**: Unambiguous instructions and expected outputs
5. **Systematic approach**: Structured frameworks over ad-hoc requests

## Common Tasks

### Adding a new prompt category:
1. Create new subdirectory in `prompt-library/`
2. Add README.md following existing pattern
3. Update main `prompt-library/README.md` navigation
4. Update project README.md structure diagram

### Reorganizing content:
1. Maintain backward compatibility where possible
2. Update all navigation references
3. Preserve existing prompt formatting
4. Update last modified dates

## No Build/Test Requirements

This repository has no:
- Dependencies to install
- Build processes to run
- Tests to execute
- Code to compile or validate

All content is static Markdown documentation that can be directly edited and committed.

## Version Information

- **Created**: 2025-08-04
- **Last Updated**: 2025-08-04
- **Total Categories**: 5
- **Estimated Prompts**: 50+

---

*This context helps Claude understand the nature and structure of this documentation-focused prompt engineering repository.*