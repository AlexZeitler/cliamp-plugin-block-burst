# cliamp-plugin-block-burst

A stereo step-meter visualizer for [cliamp](https://cliamp.stream) — nested rectangular tiers burst outward from a centered divider, each pumping with its own frequency range. Sibling of [led-burst](https://github.com/AlexZeitler/cliamp-plugin-led-burst).

<video src="assets/preview.mp4" controls loop muted></video>

## Install

```sh
cliamp plugins install AlexZeitler/cliamp-plugin-block-burst
```

Then start cliamp and press `v` to cycle visualizers until `block-burst` appears.

To pin a specific version:

```sh
cliamp plugins install AlexZeitler/cliamp-plugin-block-burst@v0.1.0
```

Remove with:

```sh
cliamp plugins remove block-burst
```

## Customizing

The plugin is a single Lua file at `~/.config/cliamp/plugins/block-burst.lua`. Open it and edit the `TIERS` table at the top — sizes, colors, and per-tier band ranges and thresholds are all there.

## Requirements

- cliamp with Lua plugin support
- A terminal with 256-color ANSI support

## License

MIT — see [LICENSE](LICENSE).
