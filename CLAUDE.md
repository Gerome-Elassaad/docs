# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Mintlify documentation site for Codinit, an AI-powered development tool. The documentation covers getting started guides, model providers, integrations, and advanced features.

## Development Commands

- **Start dev server**: `npm run dev` (or `mintlify dev`)
  - Preview at `http://localhost:3000`
- **Check for broken links**: `npm run check` (or `mintlify broken-links`)
- **Rename files**: `npm run rename` (or `mintlify rename`)

Note: The CLI can also be invoked directly as `mint dev` if installed globally via `npm i -g mint`

## Repository Structure

This is a Mintlify documentation site with the following architecture:

- **docs.json**: Main configuration file defining navigation structure, theme colors, tabs, and page organization
- **MDX files**: Documentation content organized in directories matching the navigation structure
  - `/getting-started/`: Installation and first project guides
  - `/features/`: Feature documentation including development tools
   - `/features/development`: Feature documentation including development tools
  - `/providers/`: Cloud AI provider guides (Anthropic, OpenAI, Google, etc.)
  - `/integrations/`: Third-party integrations (Git, Supabase, Netlify, Vercel)
  - `/prompting/`: Prompt engineering guidance
  - `/mcp-integration/`: Model Context Protocol integration
  - `/running-models-locally/`: Local model setup (Ollama, LM Studio)

## Navigation Structure

The site uses a tabbed navigation with three main tabs:
1. **Documentation**: Core docs including getting started, features, model config, providers, and prompting
2. **Advanced Features**: Essentials, integrations, and MCP integration
3. **Help**: FAQ and troubleshooting

## Key Configuration

- Theme: `aspen`
- Primary colors: `#3100FF` (primary), `#0C83F2` (light/dark)
- Contextual options enabled for: copy, view, ChatGPT, Claude, Perplexity, MCP, Cursor, VSCode
- External links: Blog at codinit.dev/blog, GitHub releases
- Redirects configured for legacy URL paths

## Git Workflow

After editing files, commit changes immediately. Each file should be added and committed once the edit is complete.
