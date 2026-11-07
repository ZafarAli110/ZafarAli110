# Zafar Ali

**AI engineering · Agentic engineering · Harness engineering · Platform engineering · Performance**

I work on AI-native software delivery: building with coding agents, and the harness around them that makes them
reliable. That means the rules, tools, hooks, permissions, reviewers and checks that turn a model into a teammate you
can trust with a ticket, across the whole AI-DLC, from ticket to verified pull request. Under it, the platform that
lets a team and its agents move fast: one command to run every service, shared service defaults, a gateway, gates that
run on every commit. And I care about speed: software that stays fast at real data sizes, and agents whose cost you
can see while they work.

## Featured: Harness Engineering and AI-DLC with Claude Code

A workshop I created and ran for Contour Software Engineering (November 2026): how a model becomes a coding agent, and
how a coding agent takes a ticket all the way to a verified, reviewed pull request.

| Repository | What it is |
| --- | --- |
| [harness-engineering-slides](https://github.com/ZafarAli110/harness-engineering-slides) | the slides ([open them](https://zafarali110.github.io/harness-engineering-slides/)) |
| [tiny-harness](https://github.com/ZafarAli110/tiny-harness) | a coding-agent harness built in six steps, on a small local model: the agent loop, rules, permissions, limits, verification |
| [acme-dms](https://github.com/ZafarAli110/acme-dms) | a realistic dealer management system (TypeScript, NestJS, C#, .NET, React, Aspire): lab branches from a bare start to ticket-to-PR, each adding one piece of the harness |
| [acme-tracker](https://github.com/ZafarAli110/acme-tracker) | a small Jira-like backlog with an MCP server, so agents read and move tickets as they work |
| [claude-code-cost-meter](https://github.com/ZafarAli110/claude-code-cost-meter) | a Claude Code plugin: live cost, tokens, context window and every subagent's cost |
| [agent-slides](https://github.com/ZafarAli110/agent-slides) | slides your coding agent writes, and a harness that checks them |

## How I work

- **Harness over prompts.** What must hold every time belongs in a hook, a permission or a check, not a sentence the
  model may skip.
- **Evidence over claims.** A change is done when it is verified in the running system, with evidence anyone can re-run.
- **A platform, not a pile of services.** One command runs everything (Aspire); every service shares its defaults
  (telemetry, auth, errors, health); every project answers the same targets (format, lint, typecheck, test).
- **Performance at real sizes.** Query plans, streaming over loading, and data sets with millions of rows, not ten.
- **Cost you can see.** Tokens and spend measured during the run, so a habit is chosen on numbers.

## Stack

TypeScript · Bun · Node.js · React · NestJS · C# · .NET · Aspire · PostgreSQL · RabbitMQ · Claude Code · MCP
