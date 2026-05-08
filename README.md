# Olafur's Claude Code plugins

A marketplace of Claude Code plugins I've authored.

## Add the marketplace

```
/plugin marketplace add olioskar/claude-plugins
```

## Available plugins

- **[comb](https://github.com/olioskar/comb-the-desert-claude-plugin)** — code-review pipeline (`/comb:review` → `/comb:plan` → `/comb:fix`) with configurable reviewer agents and authoritative project directives.

## Install a plugin

```
/plugin install <plugin-name>@olioskar-marketplace
```

For example:

```
/plugin install comb@olioskar-marketplace
```

## Updating

When a plugin ships a new release, refresh the cache and reinstall:

```
/plugin marketplace update olioskar-marketplace
/plugin uninstall <plugin-name>@olioskar-marketplace
/plugin install <plugin-name>@olioskar-marketplace
```
