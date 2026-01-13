# Volnux Documentation - Agent Context

## Project Overview
This repository contains the documentation for **Volnux**, an event-driven workflow orchestration platform.

- **Main Repository**: https://github.com/VolnuxSF/volnux
- **Documentation Site**: Built with Mintlify
- **Purpose**: Serve as the documentation hub for Volnux platform

## Project Details

### Volnux Platform
Volnux is an open-source workflow orchestration platform designed for event-driven architectures. It simplifies the creation, management, and visualization of complex workflows and event pipelines.

**Key Features:**
- Event-driven workflow orchestration
- Visual workflow builder and visualization
- Multi-step workflow support
- Real-time event processing
- Extensible plugin system

**Repository**: https://github.com/VolnuxSF/volnux

### Related Projects
- **Volnux Dashboard**: Main UI/UX application (Event Pipeline Dashboard)
  - Location: `/Users/kwabenadarkwa/Documents/Playground/OpenSource/volnux_dashboard`
  - Tech Stack: Next.js 16.0.0, React 19.2.0, TypeScript, Tailwind CSS
  - Status: Running on http://localhost:3001

## Documentation Structure

### Sections to Document (from Volnux repo)
1. **Getting Started**
   - Installation
   - Quick Start Guide
   - Basic Concepts

2. **Core Concepts**
   - Workflows
   - Events
   - Triggers
   - Actions
   - Event Pipelines

3. **API Reference**
   - REST API endpoints
   - Event schema definitions
   - Authentication

4. **User Guide**
   - Creating workflows
   - Managing events
   - Monitoring and debugging
   - Configuration options

5. **Advanced Topics**
   - Plugin development
   - Custom integrations
   - Performance optimization
   - Deployment strategies

6. **Examples & Tutorials**
   - Sample workflows
   - Integration examples
   - Best practices

## Technology Stack

- **Documentation Tool**: Mintlify (Free Hobby tier)
- **Deployment**: Auto-deployment from GitHub
- **Hosting**: Mintlify hosting with custom domain support
- **Repository**: Separate from main Volnux repo
- **Language**: Markdown (MDX support)

## Development Setup

### Prerequisites
- Node.js 18+
- npm or yarn
- Mintlify CLI (for local preview)

### Local Development
```bash
# Install Mintlify CLI
npm install -g mintlify

# Navigate to docs directory
cd volnux_docs

# Start local preview
mintlify dev
```

Local preview will be available at `http://localhost:3000`

## Deployment

- **Platform**: Mintlify
- **Auto-Deployment**: Enabled via GitHub integration
- **Trigger**: Automatic deployment on push to main branch
- **Custom Domain**: TBD (docs.volnux.io or similar)

## URL Structure Decision

**Current Status**: Pending
- Option 1: Subdomain (docs.volnux.io)
- Option 2: Subpath (volnux.io/docs)

## Contributing Guidelines

When updating documentation:
1. Follow Mintlify's markdown conventions
2. Keep examples up-to-date with Volnux codebase changes
3. Test links and code examples before committing
4. Use consistent terminology with Volnux project
5. Include code examples where applicable

## Important Links

- **Main Volnux Repo**: https://github.com/VolnuxSF/volnux
- **Volnux Dashboard**: http://localhost:3001 (dev server)
- **Mintlify Dashboard**: https://dashboard.mintlify.com
- **Mintlify Docs**: https://mintlify.com/docs

## Notes for AI Agents

### Context Requirements
When making changes or updates, agents should:
- Reference the main Volnux repository for accurate feature descriptions
- Keep documentation aligned with the latest version of Volnux
- Test all code examples before including them in docs
- Maintain consistent formatting and structure
- Update this file when adding new documentation sections

### Key Contact Points
- Main Project Owner: See https://github.com/VolnuxSF/volnux
- Documentation Maintainer: [TBD]

---
Last Updated: 2026-01-13
