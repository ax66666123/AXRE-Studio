# Installation Guide

## Requirements

- Windows 10 version 1809 or later; Windows 11 is recommended.
- A 64-bit system and current graphics drivers.
- Administrator permission may be required for protected processes or directories.

## Install

1. Download AXRE only from this repository's Releases page or a link explicitly published by the author.
2. Compare the file size and SHA-256 value with the Release page.
3. Run the installer and select an installation directory.
4. Start AXRE Studio. Windows may show an administrator prompt or “Unknown publisher” because the Beta certificate is self-signed.
5. Open **Settings → Resource paths** and confirm that AXRE found its own Resources directory.

## Add a game

- Try **Automatic scan** first.
- If the game is not detected, choose the executable that renders the game, not the launcher executable.
- Live and test versions with the same executable name must be added separately using their full paths.

## First configuration

1. Select the game.
2. Choose **Apply default configuration**.
3. Confirm that the game's ReShade configuration was created or updated.
4. Enable automatic injection.
5. Keep AXRE running in the background and launch the game normally.

## Administrator permission

AXRE normally runs as a standard user. Use **Run as administrator** only when:

- the game or launcher is already running as administrator;
- the game is installed in a Windows-protected directory;
- AXRE reports access denied, configuration write failure, or insufficient injection permission.

Keep AXRE and the target game at the same privilege level. Do not use elevation to bypass game, platform, or anti-cheat protections.

## Additional effects

The public Beta ships with a minimal, license-audited effect library. It does not contain the author's private Shader, Texture, or Preset collection.

- Official ReShade Shader repository: <https://github.com/crosire/reshade-shaders>
- Official ReShade website: <https://reshade.me/>

Individual effects may have different authors and licenses. Review upstream terms before downloading, modifying, or redistributing them.

## Uninstall

The uninstaller removes only files listed in the installation manifest. User configurations, Profiles, screenshots, and logs are preserved by default to prevent data loss.
