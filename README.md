# 🎖️ AstridTitle

AstridTitle is a powerful plugin for managing and assigning custom titles to players on AstridCloud Minecraft server. Enhance player engagement with personalized titles and dynamic title management.

## Features
- 🎨 **Assign Titles**: Easily assign custom titles to individual players.
- 🔄 **Title Management**: Reload and manage titles seamlessly.
- 🔒 **Permissions**: Control access with a dedicated permission node.

## Commands

| Command                      | Description                             |
|------------------------------|-----------------------------------------|
| `🖋️ /playtitle <player> <title>` | Assign a specific title to a player.    |
| `🔄 /playtitle reload`          | Reload the plugin’s configuration.      |

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
