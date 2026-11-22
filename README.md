# claude-plugins

Claude Code plugins by 2yong-k, listed in one marketplace.

## Install
In Claude Code, add the marketplace once:

```
/plugin marketplace add 2yong-k/claude-plugins
```

Then install the plugins you want:

| Plugin | What it does | Install | Source |
|---|---|---|---|
| groundwork | Start a software project from an empty folder and keep it on rails. Run it with `/groundwork:new`. | `/plugin install groundwork@2yong-k` | [2yong-k/groundwork](https://github.com/2yong-k/groundwork) |
| studio | Make images and videos by asking Claude in plain words; nothing is generated until you approve its price estimate. macOS only. Run it with `/studio:studio`. | `/plugin install studio@2yong-k` | [2yong-k/studio](https://github.com/2yong-k/studio) |

Each plugin's own README lists what it needs and the settings it asks for.

## Updates
- Automatic: `/plugin` → Marketplaces → turn on auto-update for `2yong-k`.
- By hand, in a terminal: `claude plugin marketplace update 2yong-k`, then `claude plugin update <plugin>@2yong-k`.

## License
MIT (see `LICENSE`). Each plugin carries its own license in its repository.
