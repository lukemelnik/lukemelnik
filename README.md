# Hey, I'm Luke

Fullstack developer based in London, Canada. I studied Mechanical Engineering at Queen's University, spent a decade in the music industry as a producer, artist, and audio engineer, and then taught myself to code. Now I build software that solves real problems I lived with for years.

## What I'm building

**[Songkeeper](https://songkeeper.io)** — a music production management platform for producers, mixers, and artists. Think of it as the project management tool the music industry never had. Currently in beta.

- Monorepo (Turborepo + pnpm) with a TypeScript API (Hono + tRPC + Drizzle), React frontend (TanStack Start/Router/Query), and native iOS app (SwiftUI)
- PostgreSQL, background job processing, structured logging, email notification system
- Auth, file uploads with CDN image transformations, real-time updates
- E2E tests (Playwright), integration tests, CI/CD pipeline

I built this because after years of managing sessions, splits, releases, and contacts across spreadsheets and DMs, I wanted something purpose-built. Managing music royalties and submitting to the various organizatiosn is particularly awful so I'm working towards automating the entire process.

**[Vocal Dojo](https://vocaldojo.app)** — a vocal warmup app for singers, voice actors, and anyone who uses their voice professionally. Native iOS app with a built-in piano sampler, 30 exercise patterns, and a music theory engine for generating exercises in any key. Built with SwiftUI, AVFoundation, and GRDB/SQLite — no backend, everything runs locally on device.

**[Luke Roes](https://lukeroes.com)** — my artist website, built with TanStack Start. It consumes the Songkeeper API via a generated OpenAPI SDK, so release data flows directly from the production management platform to the public-facing site. Has a full-featured members area similar to Patreon, runs on SQLite with FTS.

## Other projects

- **[Colorkeeper](https://github.com/lukemelnik/colorkeeper)** — a native macOS color picker and palette manager. Pick colors from anywhere on screen, organize into palettes, check WCAG contrast, visualize color roles, and export to 10+ formats. Built with SwiftUI, Swift 6, no external dependencies.
- **[Grove](https://github.com/lukemelnik/grove)** — a CLI for git worktrees with automatic port assignments, layered env files, and tmux workspace management. Built in Go, designed for monorepo and agent workflows.
- **[langueflow](https://github.com/lukemelnik/langueflow)** — a language learning app with AI-powered journaling, stories, and articles. Built with Next.js, tRPC, Drizzle, and OpenAI. This is where I learned the value of repository patterns and clean code organization.
- **[agent-skills](https://github.com/lukemelnik/agent-skills)** — my custom skills and config for AI coding agents (Claude Code, Gemini CLI, etc.). I'm constantly experimenting with better workflows for orchestrating agents, especially by customizing tmux.
- **Pi extensions** — small extensions for the [Pi coding agent](https://pi.dev): [model prompt](https://github.com/lukemelnik/pi-model-prompt) for per-model prompt addenda and [session recap](https://github.com/lukemelnik/pi-session-recap) for a configurable one-line session memory widget. Install with `pi install npm:@lukemelnik/pi-model-prompt` and `pi install npm:@lukemelnik/pi-session-recap`.
- **[monorepo-worktrees](https://github.com/lukemelnik/monorepo-worktrees)** — patterns and scripts for running multiple git worktrees of a monorepo simultaneously with automatic port isolation and tmux workspace setup.

## Current interests

Pushing the limits of tmux + AI agents for development orchestration — running multiple agents across worktrees, with hooks for completion signaling and automated review loops. Also exploring UX and design.

## Background

Before code, I spent 10 years making records — writing, producing, mixing, and releasing music. That work taught me how to ship creative projects under pressure, collaborate across disciplines, and obsess over details. Turns out those skills transfer directly to software.

## Get in touch

- [luke@lukemelnik.ca](mailto:luke@lukemelnik.ca)
- [lukemelnik.ca](https://lukemelnik.ca)
