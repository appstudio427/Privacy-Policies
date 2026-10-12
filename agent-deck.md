# Privacy Policy for Agent Deck for Claude Code

**Effective date:** October 12, 2026
**Publisher:** App Studio 427
**Contact:** support@appstudio427.com

Agent Deck for Claude Code ("Agent Deck", "the app") is a desktop app for running and managing Claude Code sessions on your own computer. This policy explains what information the app handles and where that information goes.

## The short version

- App Studio 427 does **not** collect, receive, store, sell or share any of your personal information.
- Agent Deck has no user accounts, analytics, advertising, tracking or crash reporting.
- Everything Agent Deck saves stays on your computer.
- Agent Deck starts other tools that you choose to use. **Claude Code** sends your prompts and the files it works on to Anthropic, under your own Anthropic account and Anthropic's terms. **Ollama** (Local mode) runs entirely on your computer.

## Information the app stores on your computer

Agent Deck saves the following data locally so it can work. None of this data is sent to App Studio 427 or anyone else.

| Data | Where it is stored |
|---|---|
| Settings, the list of project folders you add, schedules and their run history, change logs, agent links and recent session activity | `%APPDATA%\Agent Deck\data\` |
| Hook settings that let Claude Code report session activity to Agent Deck, including a random access token | `.claude\settings.local.json` inside each project you add |
| Agent definitions you create or edit | `.claude\agents\` in your project or user folder |

Agent Deck also reads Claude Code's own session transcripts (in `%USERPROFILE%\.claude\projects\`) so it can list sessions you can resume. It does not copy them anywhere.

The app receives session activity from Claude Code through a server that listens only on your own computer (`127.0.0.1`). Other computers cannot connect to it.

You can delete Agent Deck's data at any time by deleting the `%APPDATA%\Agent Deck\data\` folder. Uninstalling the app does not delete this folder.

## Your files and prompts

When you run a Claude Code session in Agent Deck, Claude Code may read files in the project folder you choose, run commands, and send your prompts and file contents to Anthropic to generate responses. Anthropic handles that data, not App Studio 427, under its own privacy policy: https://www.anthropic.com/legal/privacy

In **Local mode**, sessions use a model running in Ollama on your own computer, and Agent Deck tells Claude Code not to send non-essential traffic to Anthropic.

## Internet connections made by the app

Agent Deck connects to the internet only to:

- download the official Claude Code installer from `claude.ai` when Claude Code is missing,
- download the Ollama installer from `ollama.com` when you ask it to install Ollama,
- open help and download pages in your web browser when you click a link.

These requests send only what any web download sends, such as your IP address, to those sites. App Studio 427 does not receive this information.

## Children

Agent Deck is a developer tool and is not directed to children under 13. It does not knowingly collect information from anyone, including children.

## Changes to this policy

If this policy changes, the updated version will be published at https://github.com/appstudio427/Privacy-Policies/blob/main/agent-deck.md with a new effective date.

## Contact

Questions about this policy: **support@appstudio427.com**
