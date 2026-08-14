# Cursor

Cursor is an AI-powered code editor designed to assist software engineers with code understanding, code generation, debugging, refactoring, documentation, and agentic development workflows.

---

## Overview

Cursor combines a traditional code editor experience with AI capabilities that can understand project context and assist engineers across the software development lifecycle.

It can be used for:

- Code understanding
- Code generation
- Code modification
- Refactoring
- Debugging
- Documentation
- Repository exploration
- Development workflow automation
- Agentic software development

---

## Core Capabilities

### Code Assistance

- Explain existing code
- Generate new code
- Modify existing code
- Refactor implementations
- Identify potential issues
- Generate documentation
- Assist with debugging

### Codebase Understanding

Cursor can use project context to help understand:

- Source code
- Project structure
- Dependencies
- Configuration
- Documentation
- Related files

### Agentic Development

AI agents can assist with multi-step development tasks such as:

- Analyzing a problem
- Planning changes
- Modifying multiple files
- Running development commands
- Investigating failures
- Iterating based on results

Human review and approval remain important for engineering and production changes.

---

## Cursor + MCP

Cursor can integrate with external tools and systems through the Model Context Protocol (MCP).

```text
Cursor
   |
   v
MCP Client
   |
   v
MCP Server
   |
   +-- Tools
   +-- Resources
   +-- Prompts
   |
   v
External Systems
