# Wipebot for Claude

The Wipebot connector at https://wipebot.enfo.dev/mcp and its raid-log-analysis skill, as a Claude plugin for any guild. With the skill,
Claude reads raid logs the way the method says; a connector alone brings only the tools.

## Add it

In Claude (claude.ai or Claude Desktop): **Customize → Plugins → Add → Add marketplace**, enter `Enf0/wipebot-plugin`, then add
the Wipebot plugin and sign in with Warcraft Logs. With **Sync automatically** on, Claude keeps it up to date; the
marketplace's **Refresh** updates it at once.

In Claude Code: `/plugin marketplace add Enf0/wipebot-plugin`, then `/plugin install wipebot@wipebot`.

Made with [Wipebot](https://github.com/Enf0/wipebot): `wipebot plugin DIR` writes this repository.
