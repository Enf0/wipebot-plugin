# Wipebot for Claude, ChatGPT and Codex

The Wipebot connector at https://wipebot.enfo.dev/mcp and its raid-log-analysis skill, as a plugin for any guild. With the skill,
the model reads raid logs the way the method says; a connector alone brings only the tools.

## Add it

In Claude (claude.ai or Claude Desktop): **Customize → Plugins → Add → Add marketplace**, enter `Enf0/wipebot-plugin`, then add
the Wipebot plugin and sign in with Warcraft Logs. No GitHub account is needed. For a new version, press
**Check for updates** in Manage marketplaces.

In Claude Code: `/plugin marketplace add Enf0/wipebot-plugin`, then `/plugin install wipebot@wipebot`.

In Codex, also Codex inside the ChatGPT desktop app: Plugins → **Add** → **Add plugin marketplace**, enter `Enf0/wipebot-plugin`
(or `codex plugin marketplace add Enf0/wipebot-plugin`), install Wipebot, then sign in to its server under Plugins → **MCPs**. A
ChatGPT workspace admin can import it for the workspace: Admin Console → Plugins → Add → Import marketplace, with
`https://github.com/Enf0/wipebot-plugin` as the source. ChatGPT's chats, on the web, a phone or the desktop app, don't run a
plugin's server: there add https://wipebot.enfo.dev/mcp as a custom connector (the tools without the skill).

Made with [Wipebot](https://github.com/Enf0/wipebot): `wipebot plugin DIR` writes this repository.
