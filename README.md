# Wipebot for Claude, ChatGPT and Codex

The Wipebot connector at https://wipebot.enfo.dev/mcp and its raid-log-analysis skill, as a plugin for any guild. With the skill,
the model reads raid logs the way the method says; a connector alone brings only the tools.

## Add it

In Claude (claude.ai or Claude Desktop): **Customize → Plugins → Add → Add marketplace**, enter `Enf0/wipebot-plugin`, then add
the Wipebot plugin and sign in with Warcraft Logs. With **Sync automatically** on, Claude keeps it up to date; the
marketplace's **Refresh** updates it at once.

In Claude Code: `/plugin marketplace add Enf0/wipebot-plugin`, then `/plugin install wipebot@wipebot`.

In Codex and the ChatGPT desktop app: `codex plugin marketplace add Enf0/wipebot-plugin`, then install Wipebot from the
Plugins directory and sign in with Warcraft Logs. A ChatGPT workspace admin can import this repository as a
marketplace (Admin console → Plugins). In ChatGPT on the web or a phone without a workspace, add https://wipebot.enfo.dev/mcp as a
custom connector instead (the tools without the skill).

Made with [Wipebot](https://github.com/Enf0/wipebot): `wipebot plugin DIR` writes this repository.
