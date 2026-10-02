# Datacentre — Omarchy theme

Warm, low-contrast dark theme drawn from a night photo of a 1960s King St. data centre storefront: tobacco-brown facade, sodium-lit blinds, red feature wall, pale-blue cabinets.

![preview](preview.png)

## Install

```
omarchy theme install https://github.com/jbettcher-wg/omarchy-datacenter-theme.git
omarchy theme set datacenter
```

Or via the Omarchy menu: Install > Style > Theme, then paste the repo URL.

`omarchy theme install` names the theme after the repository, stripping `omarchy-` and
`-theme`, so this one installs as **datacenter** even though the prose below spells it
the British way.

## Rounded corners

`shell.bar.toml` floats the bar with a 12px radius. Shell surfaces (menus, popups, notifications) follow Hyprland's `decoration:rounding`, so set rounding to 12 in your own Hyprland look-and-feel config.

## Files
- colors.toml — full 24-key palette + gradient window border
- shell.bar.toml — floating rounded bar
- icons.theme — Yaru-wartybrown
- preview.png — theme switcher preview
- backgrounds/01-kingst-datacentre.webp (colour)
- backgrounds/02-kingst-datacentre-1963.webp (1963, black and white) — cycle with `omarchy theme bg next`

## Image credits

Both backgrounds are photographs of the IBM Datacentre on King Street, Toronto. They are reproduced unmodified (format conversion only) and are not owned by the author of this theme. All rights remain with the original copyright holder.

- `01-kingst-datacentre.webp` — Source: [SOURCE NAME](SOURCE_URL)
- `02-kingst-datacentre-1963.webp` — Photo, 1963. Source: [SOURCE NAME](SOURCE_URL)

The theme files themselves (colors.toml, shell.bar.toml, icons.theme) are free to use and modify.
