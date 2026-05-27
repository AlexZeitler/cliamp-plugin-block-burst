# cliamp-plugin-block-burst

A stereo step-meter visualizer for [cliamp](https://cliamp.stream) - nested rectangular tiers burst outward from a centered divider, each pumping with its own frequency range. Sibling of [led-burst](https://github.com/AlexZeitler/cliamp-plugin-led-burst), [vu-meter](https://github.com/AlexZeitler/cliamp-plugin-vu-meter), and [reverb](https://github.com/AlexZeitler/cliamp-plugin-reverb).

<video src="https://github.com/user-attachments/assets/c794b37f-30d1-41fa-a8fb-a595b2655578" controls></video>

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

The plugin is a single Lua file at `~/.config/cliamp/plugins/block-burst.lua`. Open it and edit the `TIERS` table at the top - sizes, colors, and per-tier band ranges and thresholds are all there.

## Requirements

- cliamp with Lua plugin support
- A terminal with 256-color ANSI support

## Related plugins

- [AlexZeitler/cliamp-plugin-led-burst](https://github.com/AlexZeitler/cliamp-plugin-led-burst) - Stereo LED matrix that bursts outward from a center divider, with green / yellow / red tiers and peak hold.
- [AlexZeitler/cliamp-plugin-vu-meter](https://github.com/AlexZeitler/cliamp-plugin-vu-meter) - Ten analog-needle VU meters, one per spectrum band, drawn with sub-pixel braille.
- [AlexZeitler/cliamp-plugin-reverb](https://github.com/AlexZeitler/cliamp-plugin-reverb) - Horizontal LED matrix inspired by vintage HiFi reverberation graphic displays, with quad-symmetric bars pulsing outward.

## License

MIT - see [LICENSE](LICENSE).
