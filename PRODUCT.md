# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Astro 7 + Tailwind CSS v4 + TypeScript + Lucide Icons

## Users

Gaming, anime, tech, and web3 Discord server owners, administrators, and moderation teams who require ruthless zero-day phishing defense without paying recurring bot subscription fees, while fostering a vibrant, engaging community atmosphere.

## Product Purpose

Tsubaki safeguards Discord servers from credential stealers, token harvesters, typosquatted scam links, and multi-channel raid bots by intercepting threats before messages render, rescuing compromised accounts with automated recovery guidance, and entertaining members with a Groq-powered anime companion.

## Positioning

Unlike native Discord AutoMod or isolated third-party bots, Tsubaki combines pre-spread deep inspection (scanning raw text, embed metadata, and attachment descriptions) with a decentralized Turso/libSQL community blocklist—delivering immediate collective threat immunity across servers with a strict zero-download file security policy.

## Operating Context

- High-activity Discord servers with open chat, trade channels, and bot lobbies.
- Moderator channels (`#mod-logs`, `#security-alerts`) receiving rich forensic embeds with interactive component buttons (`Pardon User`, `Ban User`, `Allow URL`).
- Self-hosted environments on Render (free tier with automated `/health` endpoint) or VPS/local environments managed via Astral `uv`.
- Distribution strategy: Promoted primarily as an open-source, self-hosted system, with a direct public bot invite link launching in the near future.

## Capabilities and Constraints

- Deep URL extraction covering message bodies, rich embed fields, footers, and attachment descriptions.
- Automated typosquatting and homoglyph detection algorithms.
- Multi-channel rapid spread rate limiting (3+ channels in 10s and duplicate screenshot flood detection).
- Safe quarantine: unclickable code-block previews, reconstructed embed data, and proxied 4-image grid gallery without downloading files.
- Strict Discord role-hierarchy enforcement on all moderator actions.
- Automated 5-step victim account restoration direct messages.
- Full slash command dashboard (`/antiphishing settings`, `/antiphishing stats`, `/test`, `/setup`, `/clear`, `/ask`, `/ping`, `/hello`).
- Scheduled automated channel purges daily at 3:00 AM UTC via `CLEAR_CHANNEL_ID`.
- Anime AI companion (`/ask`) with Japanglish dialogue, tsundere personality, kaomoji reactions, and anti-abuse safeguards.

## Brand Commitments

- Name: Tsubaki (椿 - Japanese red camellia, representing resilience, vigilance, and grace).
- Identity: Obsidian dark tech foundation (`#07080C`) energized by crimson and rose camellia hues (`#E11D48`, `#FB7185`).
- Voice: Playful, caring anime assistant with light tsundere banter, contrasting with precise, mission-critical security logs.
- Ethics: 100% open-source under MIT, zero telemetry lock-in, and zero paywalled moderation features.

## Evidence on Hand

- Complete bot source code in `~/dev/python/Tsubaki` with automated tests (`pytest`, `SimCord`, `ruff`).
- Production deployment configuration: `render.yaml` blueprint and `uv.lock`.
- Landing site implementation in `~/dev/web/Tsubaki-site` with Astro 7, Tailwind v4, Prettier, ESLint, and TypeScript diagnostics.

## Product Principles

1. Intercept Pre-Spread: Neutralize malicious payloads before members see or click them.
2. Collective Defense: A zero-day attack blocked on one server protects all connected instances via Turso synchronization.
3. Zero Host Danger: Never download untrusted binaries or attachments to the hosting disk.
4. Compassionate Incident Response: Differentiate between malicious raiders and compromised community members; help victims recover accounts.
5. Sovereign & Open: Prioritize self-hosting and open code over closed commercial ecosystems.
6. Personality with Purpose: Balance military-grade defense with a warm, memorable community mascot.

## Accessibility & Inclusion

- High-contrast text meeting WCAG AA requirements on dark surfaces.
- Semantic HTML tags, clear ARIA labeling, and keyboard-navigable interactive components.
- Safe forensic blocks preventing accidental link activation by visually impaired or mobile users.
