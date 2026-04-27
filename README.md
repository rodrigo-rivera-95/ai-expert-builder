# AI Expert Builder

A system prompt that turns any AI into a structured guide for designing, building, and deploying custom **AI Experts** inside your organization.

---

## What is an AI Expert?

An AI Expert is a custom AI model built around a specific domain — configured with the right instructions, connected to the right data sources, and designed around the actual use cases your subject matter experts handle every day.

Not a general chatbot. A purpose-built assistant that embeds institutional knowledge and makes it available to everyone on your team — not just the people who have been there for years.

---

## What does this prompt do?

Paste `expert-builder.md` into any AI model (Claude, GPT-4o, Gemini, or an open-source model via Open Web UI) and it will guide you through two phases:

**Phase 1 — Design**
Runs a structured intake interview covering identity, scope, tools, and question types. Generates a production-ready system prompt for your Expert.

**Phase 2 — Setup**
Walks you through deploying your Expert step by step: base model selection, parameter tuning, system prompt placement, tool connections, and knowledge base setup.

---

## Quick Start

1. Open your AI platform of choice (Claude, ChatGPT, Open Web UI, etc.)
2. Start a new conversation and paste the full contents of `expert-builder.md` as the system prompt
3. In your first message, say: **"I want to build an AI Expert"**
4. Follow the intake interview — the AI will guide you from there

---

## Before You Deploy

Customize these four things for your organization:

| Placeholder | Replace with |
|---|---|
| `[YOUR PLATFORM]` | Your AI platform name and URL (e.g., `chat.yourcompany.com`) |
| `[YOUR PLATFORM URL]` | The direct URL your team uses to access the platform |
| `[YOUR AI ADMIN OR SUPPORT CONTACT]` | The person or team that handles AI support at your org |
| Tools table in Phase 1 | The integrations your platform actually supports |

---

## What Makes a Good AI Expert

Based on production deployments, the Experts that get adopted share three traits:

- **Scoped tightly.** They answer a specific set of questions for a specific audience — not everything for everyone.
- **Built with SMEs.** The people who understand the domain were involved in designing it, not just the people who wanted to build something.
- **Maintained like a product.** The system prompt is versioned, the question types are updated as gaps are discovered, and there is a clear owner.

---

## Files

| File | Description |
|---|---|
| `expert-builder.md` | The full system prompt — paste this into any AI to start building |

---

## Contributing

Found a pattern that works well? Discovered a question type worth adding to the architecture? Open a pull request or issue — contributions are welcome.

---

## License

MIT — use freely, share freely.
