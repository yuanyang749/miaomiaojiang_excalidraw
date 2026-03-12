# Contributing

Thanks for contributing to `miaomiaojiang_excalidraw`.

## Good contribution areas

- better examples
- new style presets
- new theme palettes
- improved render reliability
- clearer prompt-to-diagram routing
- educational diagram patterns
- documentation improvements

## Before opening a PR

Please keep contributions aligned with the project scope:
- prefer explanatory diagrams over decorative design
- prefer reusable workflow improvements over one-off prompt hacks
- validate visual output by rendering to PNG
- document new style phrases or themes clearly

## For style/theme contributions

If you add a new theme:
- define semantic fills and strokes
- define text hierarchy colors
- define evidence artifact colors
- define default line/arrow colors
- document intended use cases

If you add a new style phrase:
- explain the visual intent
- describe the expected parameter behavior
- include at least one example prompt

## For example contributions

Please include:
- the user-facing prompt
- the `.excalidraw` source
- a rendered PNG preview if possible
- a short note explaining why the example is useful

## Visual quality checklist

Before proposing changes, check that:
- text does not overflow containers
- spacing is balanced
- arrows land correctly
- the diagram matches the intended chart type
- the chosen theme is consistent throughout the image

## Notes

This project is an adaptation for OpenClaw workflows. If you change trigger behavior or prompt routing, update both:
- `SKILL.md`
- `README.md`
