# Sword Art Offline

Official Windows and macOS player downloads for Sword Art Offline.

On **Windows**, download **SAO-Launcher-Setup.exe** from the [latest release](https://github.com/Cxrpss/sao-releases/releases/latest). Setup installs the launcher for your Windows account and lets you choose desktop and Start Menu shortcuts. Open **SAO Launcher** from the shortcut you chose.

For a portable installation, extract **SAO-Launcher-Windows-x64.zip** and open **SAO Launcher.exe** inside it. Keep the complete folder together.

On **macOS**, download the [Apple Silicon ZIP](https://github.com/Cxrpss/sao-releases/releases/latest/download/SAO-Launcher-macOS-Apple-Silicon.zip) for an M-series Mac, or the [Intel ZIP](https://github.com/Cxrpss/sao-releases/releases/latest/download/SAO-Launcher-macOS-Intel.zip). Open the ZIP, drag **SAO Launcher.app** to Applications, then open it. Java is included. Windows `.exe` files cannot run on macOS. See [Mac instructions](https://github.com/Cxrpss/sao-releases/releases/latest/download/READ-ME-FIRST-MACOS.txt).

The Mac beta app is not notarized. If Apple cannot verify its developer, use **System Settings → Privacy & Security → Open Anyway** after attempting to open this official download. Mac checksums are in the separate `SHA256SUMS-MACOS-*` files.

The launcher installs Minecraft, NeoForge, Sword Art Offline and its companion mods. Sign in with your own Minecraft Java account in the Microsoft sign-in window. Future releases appear in the launcher and under **Updates** in the game. **Update & Restart** verifies the download, closes Minecraft, installs the update, and starts Minecraft again.

The beta server is selected by the launcher; whitelist access is required. Public builds do not offer single-player. This repository contains downloadable releases and does not contain the game's source code.

Your game files are in `%LOCALAPPDATA%\SwordArtOffline\minecraft\instances\sao\.minecraft`. The launcher's **Game folder** button opens them. Worlds and personal settings are preserved during updates. A failed update keeps its recovery journal and backups in `%LOCALAPPDATA%\SwordArtOffline`.

The installer appears in Windows Installed Apps. Uninstalling it removes the launcher; your game files and personal settings stay in the separate folder above.

Windows may show SmartScreen for a new or unsigned release. Publisher trust is separate from the installer and icon. Download from the official release page; its `SHA256SUMS` file lists the exact release checksums.

Windows x64 or a supported Mac, plus an account that owns Minecraft Java Edition, are required. The launcher includes Java. Minecraft installation and Microsoft account sign-in are provided by the unmodified [Prism Launcher](https://prismlauncher.org), downloaded from its official releases. Companion mods are downloaded from their authors; see the in-game mod credits.

On macOS, game data is stored in `~/Library/Application Support/SwordArtOffline`.
