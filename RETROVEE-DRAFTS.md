# Retrovee draft workflow

This edition builds on [ericosiu/ai-marketing-skills](https://github.com/ericosiu/ai-marketing-skills). Original copyright and licensing are in [LICENSE](LICENSE).

Upstream main branch ZIP SHA-256: `b4a1bfaf8955523046da786b7c13d4a2444f1692c725cbe2ba60d9f5f123523b`.

Use the [`retail-seo-opportunities` skill](codex-skills/retail-seo-opportunities/SKILL.md) for the Codex draft workflow. Copy the entire skill directory into your Codex skills directory. This skill has no runtime dependencies. The upstream tools retain their separate setup instructions in the original README.

Keep credentials, customer data and performance exports out of Git. Review proposed external changes and get approval before making them live.

## GitHub Actions

The original workflows are retained in `.github/upstream-workflows/` for review. Enable selected workflows only after checking their triggers, tokens and publish targets.
