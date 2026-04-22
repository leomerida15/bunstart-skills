# Bunstart Skills

Agent skills for [bunstart](https://github.com/leomerida15/bunstart) - Build and development toolchain for Bun monorepos.

## Installation

```bash
npx skills add leomerida15/bunstart-skills
```

## Available Skills

### bunstart

Core skill for working with bunstart CLI and @bunstart/pack.

**Covers:**
- bunstart CLI commands (`buns`, `buns mono`)
- @bunstart/pack buildSetting() API
- Monorepo workspace management
- Project templates (api-rest, frontend-react, library)
- Migrating projects to @bunstart/pack

## What is Bunstart?

Bunstart is a build and development toolchain for Bun monorepos:

- **@bunstart/cli** - CLI for initializing and managing monorepos
- **@bunstart/pack** - Build engine with unified configuration

## Quick Start

```bash
# Install the skill
npx skills add leomerida15/bunstart-skills

# Initialize a monorepo
buns init

# Generate an app
buns mono generate app my-api --template api-rest

# Build it
buns mono build my-api
```

## Documentation

See the main repository: https://github.com/leomerida15/bunstart

## License

MIT
