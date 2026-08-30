# Claxedo Plugins

Public [Agent Plugins](https://agent-plugins.org/) collection used by Claxedo.

Each immediate child directory is one complete Agent Plugins v1 plugin:

- `composio` — Composio Connect MCP with its tool-routing skill.
- `context7` — Context7 OAuth MCP with its documentation lookup skill.

Claxedo treats this repository as a discovery and update source. Enabling a plugin retains an immutable copy before activation, so runtime materialization does not depend on this repository remaining available.
