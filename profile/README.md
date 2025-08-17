# JiraGuard

Dev‑ready Jira tickets. Local AI. Fewer meetings, faster sprints.

JiraGuard helps teams write and ship clear, complete, and dev‑ready Jira tickets using local AI (Ollama) and smart validations. Built for engineers who prefer shipping over status meetings.

> Because "it works on my machine" shouldn't be your sprint plan.

## What’s available now (MVP + early work)

- Live ticket description validation
    - internal quality/clarity score,
    - AI suggestions on how to improve the text,
    - detection of vague wording and missing details.
- Key element checks
    - clear goals and context (why this matters),
    - structured, verifiable acceptance criteria,
    - formatting optimized for AI tools (e.g., Cursor, Copilot).
- Local by default, privacy-first
    - works with local models via Ollama (e.g., Llama 3, Mistral),
    - no data sent to any cloud unless you explicitly enable remote providers.
- Simple UI to create/validate tickets
    - editor with quick copy and “apply suggestions”,
    - “Create Ticket” and “Fetch from JIRA” tabs (Jira integration in progress - coming soon).
- Docs and community
    - basics are in place; Discord community for questions and ideas.

> Note: The repo includes experimental “remote” LLM paths for testing; local mode is the default and recommended for sensitive data.

## Vision and Mission

- Vision: Every ticket is dev‑ready before it reaches a developer.
- Mission: Eliminate ambiguity, gaps, and unclear specs using local AI, templates, and best practices - helping teams save 3–5+ hours per sprint and ship with less risk.

## Why JiraGuard?

- Reduces back‑and‑forth and clarification meetings.
- Increases team velocity: more coding, less guessing.
- Runs locally and protects privacy.
- Open to customization and community contributions.

## Tech Stack

- Framework: Angular 20 (standalone components, Signals)
- Styling: TailwindCSS
- AI: Ollama (local LLMs; supports Llama 3, Mistral…)
- Integrations: Jira REST API (Cloud/Server; in progress)
- Extras: ngx‑markdown, ngx‑clipboard, ngx‑cookie‑service

## Open‑source Scope

Our plan is to keep the core parts open-source:
- UI for ticket validation and editing,
- templates/prompts for different ticket types (bug/feature/tech‑debt),
- integration layer for local models (Ollama),
- basic Jira integration (with privacy‑respecting configuration).

Advanced and enterprise features may later be offered as additional modules, but the core that makes tickets better - we want to keep freely available to everyone.

## Project Status

Everything is still in preparation and active development. Early users help us prioritize. If you want more details, a demo, or to contribute - feel free to reach out.

- Link to the [App](https://jiraguard.com): https://jiraguard.com
- DM on [X](https://x.com/duxorX) or [LinkedIn](https://www.linkedin.com/in/dusanperisic/) - happy to respond.
- Join the [Discord](https://discord.gg/CsKxjPYPJz) community.

## How You Can Help

- Try the validator and send feedback (what worked well, what didn’t).
- Propose templates your team uses for tickets.
- Open an issue/PR for a bug or improvement idea.
- Share the project with teammates who struggle with unclear tickets.

Questions, ideas, or brutal feedback? Open an issue or reach out. Let's make unclear tickets a thing of the past.
