# AstridTitle

Welcome to the AstridTitle plugin! 🎉 This plugin allows you to assign and manage custom titles for players on your Minecraft server.

## Features
- **Assign Titles:** Easily assign custom titles to players.
- **Title Management:** Reload and manage titles on the go.
- **Permissions:** Control access with a dedicated permission node.

## Commands

| Command                 | Description                            |
|-------------------------|----------------------------------------|
| `/playtitle <player> <title>` | Assign a title to a player.         |
| `/playtitle reload`     | Reload the plugin configuration.        |

### Examples

1. **Assign a Title:**
   ```plaintext
   /playtitle senseinova flytime30

## Configuration

The plugin’s configuration files can be found in the `plugins/AstridTitle` directory. Below is the configuration format for customizing titles:

```yaml
titlename:
  title: ''
  subtitle: ''
  fadein: 20
  staytime: 40
  fadeout: 20
```

Example Configuration

```yaml
flytime15:
  title: '&r'
  subtitle: '&e+15 minutes'
  fadein: 20
  staytime: 40
  fadeout: 20
```
