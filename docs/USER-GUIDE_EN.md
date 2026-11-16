# User Guide

## Game library

Use automatic scanning first, then add missing games manually by selecting the real rendering executable. Games with identical executable names are kept separate by full path. Custom display names do not change injection matching.

## Configuration and presets

- **Apply default configuration** writes AXRE's portable resource paths for the selected game.
- **Apply this game's configuration** reuses a verified configuration on another compatible game.
- Close the game before changing configuration or preset files whenever possible.

## Automatic injection

Enable the switch on a game card and leave AXRE running in the background. Launch the game through its normal launcher. AXRE waits for the matching executable and loads ReShade without permanently copying the injection DLL into the game directory.

If injection fails, check that AXRE and the game use the same privilege level, then review the sanitized ReShade and AXRE logs.

## Effects and add-ons

The public build contains only a minimal audited effect set. Download additional effects from trusted upstream sources, such as the official ReShade Shader repository, and respect each author's license.

Use the Effect Center to search names and inspect bilingual parameter mappings. Use the Add-on Center to review purpose, usage, status, shortcuts, upstream source, and license information.

## Screenshot gallery

The gallery can organize ReShade screenshots, compare original and processed images with a horizontal slider, and group effect-breakdown captures from the same sequence.

## Depth troubleshooting

If depth appears white, black, inverted, or mirrored, open **Troubleshooting**, select the game, and apply the matching depth correction. Online games may intentionally block depth access; do not attempt to bypass that protection.

## Support

- GitHub Issues: include the AXRE version, Windows version, game, graphics API, launch method, and sanitized logs.
- Official QQ group: `1064259786`
- Bilibili: <https://space.bilibili.com/436127696>
