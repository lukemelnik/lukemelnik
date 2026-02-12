# Hey, I'm Luke

Fullstack developer based in London, Canada. I studied Mechanical Engineering at Queen's University, spent a decade in the music industry as a producer, artist, and audio engineer, and then taught myself to code. Now I build software that solves real problems I lived with for years.

## What I'm building

**Songkeeper** — a music production management platform for producers, mixers, and artists. Think of it as the project management tool the music industry never had. Currently in beta.

- Monorepo (Turborepo + pnpm) with a TypeScript API (Hono + tRPC + Drizzle), React frontend (TanStack Start/Router/Query), and native iOS app (SwiftUI)
- PostgreSQL, background job processing, structured logging, email notification system
- Auth, file uploads with CDN image transformations, real-time updates
- E2E tests (Playwright), integration tests, CI/CD pipeline

I built this because after years of managing sessions, splits, releases, and contacts across spreadsheets and DMs, I wanted something purpose-built. Managing music royalties and submitting to the various organizatiosn is particularly awful so I'm working towards automating the entire process.

**[lukeroes](https://github.com/lukemelnik/lukeroes)** — my artist website, built with TanStack Start. It consumes the Songkeeper API via a generated OpenAPI SDK, so release data flows directly from the production management platform to the public-facing site.

## Other projects

- **[langueflow](https://github.com/lukemelnik/langueflow)** — a language learning app with AI-powered journaling, stories, and articles. Built with Next.js, tRPC, Drizzle, and OpenAI. This is where I learned the value of repository patterns and clean code organization.
- **[agent-skills](https://github.com/lukemelnik/agent-skills)** — my custom skills and config for AI coding agents (Claude Code, Gemini CLI, etc.). I'm constantly experimenting with better workflows for orchestrating agents, especially by customizing tmux.
- **[monorepo-worktrees](https://github.com/lukemelnik/monorepo-worktrees)** — patterns and scripts for running multiple git worktrees of a monorepo simultaneously with automatic port isolation and tmux workspace setup.

## Current interests

Pushing the limits of tmux + AI agents for development orchestration — running multiple agents across worktrees, with hooks for completion signaling and automated review loops. Also exploring UX and design.

## Background

Before code, I spent 10 years making records — writing, producing, mixing, and releasing music. That work taught me how to ship creative projects under pressure, collaborate across disciplines, and obsess over details. Turns out those skills transfer directly to software.

## Get in touch

- [luke@lukemelnik.co](mailto:luke@lukemelnik.co)
- [lukemelnik.co](https://lukemelnik.co)
