# About

This is a repository to hold configuration files for [GlazeWM](https://github.com/glzr-io/glazewm) and [Zebar](https://github.com/glzr-io/zebar). They are a tiling window manager and a customizable taskbar respectively.

My config takes the stock configurations for both and adds some aesthetic and functional changes.

*GlazeWM* changes:

> [!NOTE]
> `hide_title_bar` can cause rendering issues with some apps. If that does occur change the value back to false in the config.

- `hide_title_bar` is *enabled* for active/inactive windows
- Border color for active windows are `#7EBC89`
- Gaps between windows/edges are `8px`

**Zebar** changes:

> [!NOTE]
> `dockToEdge` only works on Windows

- Make the background transparent
- Dock to edge is *enabled*

# Install

After installing [GlazeWM](https://github.com/glzr-io/glazewm), which will also install [Zebar](https://github.com/glzr-io/zebar), copy the contents of this repository to the `~/.glzr` directory. Start GlazeWM or reload the config to use.
