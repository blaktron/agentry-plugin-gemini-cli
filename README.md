# Agentry for Gemini CLI

Agentry brings QuickAgents into your agent host. Search a registry, read a QuickAgent's capability contract, scan findings and signature, install it, and run it in Agentry's sandboxed runner with a preview you approve first. Build your own QuickAgent, validate it, get an AI Review and test it before you publish. The plugin drives the Agentry CLI on your computer; the CLI keeps your sign-in and enforces each QuickAgent's contract.

## Install

```sh
gemini extensions install https://github.com/blaktron/agentry-plugin-gemini-cli
```

Then run `/agentry:setup`.

## Requirements

- The Agentry CLI 0.6.63 or newer on `PATH`. Install it from https://secureagentry.net/download.
- Node 20 or newer on `PATH`.
- Docker, for runs on this computer.

The extension adds the `agentry` skill, the commands
`/agentry:find`, `/agentry:new`, `/agentry:run`, `/agentry:setup`, `/agentry:sign-in` and the Agentry MCP server
0.6.999, bundled in `server/`. Signing in stays in your terminal
(`agentry login`). Documentation: https://docs.secureagentry.net/agentry/mcp/. Privacy: https://secureagentry.net/privacy.
