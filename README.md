# Volnux Docs

Documentation for [Volnux](https://github.com/VolnuxSF/volnux), an event-driven workflow orchestration platform.

## Quick Start

This documentation site is built with [Mintlify](https://mintlify.com).

### Prerequisites
- Node.js 20.17.0 or higher
- npm or yarn

### Running Locally

```bash
# Install Mintlify CLI (one-time setup)
npm install -g mintlify

# Start the local dev server
mintlify dev

# View at http://localhost:3000
```

### Building for Production

```bash
mintlify build
```

## Project Structure

```
volnux_docs/
├── docs.json              # Navigation & site configuration
├── index.mdx              # Home page
├── getting-started/       # Getting Started guides
├── AGENTS.md              # AI agent context
└── README.md              # This file
```

## Contributing

To contribute to the docs:

1. Create a new `.mdx` file in the appropriate directory
2. Add it to the navigation in `docs.json`
3. Run `mintlify dev` to preview changes
4. Commit and push

For detailed context on the project, see [AGENTS.md](./AGENTS.md).

## Links

- **Main Repo**: [VolnuxSF/volnux](https://github.com/VolnuxSF/volnux)
- **Mintlify Docs**: [mintlify.com/docs](https://mintlify.com/docs)
- **Issues**: [GitHub Issues](https://github.com/VolnuxSF/volnux/issues)