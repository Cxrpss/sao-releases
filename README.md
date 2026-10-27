# Sword Art Offline

Official Windows and macOS player downloads for Sword Art Offline.

On **Windows**, download [**SAO-Launcher-Setup-7.exe**](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/SAO-Launcher-Setup-7.exe). Setup installs the launcher for your Windows account and lets you choose desktop and Start Menu shortcuts. Open **SAO Launcher** from the shortcut you chose.

For a portable installation, extract [**SAO-Launcher-Windows-x64-7.zip**](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/SAO-Launcher-Windows-x64-7.zip) and open **SAO Launcher.exe** inside it. Keep the complete folder together.

On **macOS**, download [SAO-Launcher-macOS-7.zip](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/SAO-Launcher-macOS-7.zip). The same app automatically detects **Apple Silicon or Intel** and uses the correct included Java runtime. Open the ZIP, drag **SAO Launcher.app** to Applications, then open it. No chip choice or separate Java installation is needed. Windows `.exe` files cannot run on macOS. See [Mac instructions](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/READ-ME-FIRST-MACOS-7.txt).

The Mac beta app is not notarized. If Apple cannot verify its developer, use **System Settings > Privacy & Security > Open Anyway** after attempting to open this official download. Launcher checksums are in [SHA256SUMS-LAUNCHER-7](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/SHA256SUMS-LAUNCHER-7).

The launcher installs Minecraft, NeoForge, Sword Art Offline and its companion mods. Sign in with your own Minecraft Java account in the Microsoft sign-in window. Then choose **Connect Discord** and confirm your accounts. **A linked Discord account is required to play through the launcher, even if you were already whitelisted.** Staff-approved players do not need a paid Discord role. Eligible supporter roles receive automatic whitelist access after linking. Use the launcher's download-update icon to update the launcher itself; Minecraft sign-in and game files are preserved. Future game releases appear in the launcher and under **Updates** in the game. **Update & Restart** verifies the download, closes Minecraft, installs the update, and starts Minecraft again.

The beta server is selected by the launcher; whitelist access is required. Public builds do not offer single-player. This repository contains downloadable releases and does not contain the game's source code.

Your game files are in `%LOCALAPPDATA%\SwordArtOffline\minecraft\instances\sao\.minecraft`. The launcher's **Game folder** button opens them. Worlds and personal settings are preserved during updates. A failed update keeps its recovery journal and backups in `%LOCALAPPDATA%\SwordArtOffline`.

The installer appears in Windows Installed Apps. Uninstalling it removes the launcher; your game files and personal settings stay in the separate folder above.

Windows may show SmartScreen for a new or unsigned release. Publisher trust is separate from the installer and icon. Download from the official release page; the [launcher checksum file](https://github.com/Cxrpss/sao-releases/releases/download/v0.1.731/SHA256SUMS-LAUNCHER-7) lists these exact launcher downloads.

Windows x64 or a supported Mac, plus an account that owns Minecraft Java Edition, are required. The launcher includes Java. Minecraft installation and Microsoft account sign-in are provided by the unmodified [Prism Launcher](https://prismlauncher.org), downloaded from its official releases. Companion mods are downloaded from their authors; see the in-game mod credits.

On macOS, game data is stored in `~/Library/Application Support/SwordArtOffline`.

Use **RAM** beside **Check for updates** to change Minecraft's memory allocation. It is remembered for the next launch, with a hardware-aware recommended amount and room left for your operating system.

If Windows Installer reports a file-security error for `Config.Msi`, use the Windows portable ZIP above. Extract the complete folder somewhere you own and open **SAO Launcher.exe**; it uses your existing sign-in and game data.

The Play button shows **Dead** for hardcore death bans, **Banned** for other server bans, and **No Access** when whitelist approval is missing. Use Check for updates to refresh access after a revival or unban.

Launcher update fix: if the Windows launcher reports **Unsupported URI content**, close Minecraft and the old launcher, then install the current Windows download above manually once. Future launcher updates open verified Setup executables directly.

Discord connection fix: this launcher accepts valid sessions when the computer clock is out of sync. On older launchers, sync the computer's date and time before trying again.
