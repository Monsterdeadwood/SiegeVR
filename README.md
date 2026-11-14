> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **Rainbow Six Siege VR** thread.

![Rainbow Six Siege VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# Rainbow Six Siege VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

An experimental VR mod for the supported Throwback Y5S3 Shadow Legacy / Y5S3.3.1 PC build. The current test path uses local Training Grounds, stereo viewing, motion-controller input and two-handed weapon handling.

**Current documented branch: R51 handling package / R202 development revision.**

## Installation

**Join the [Operation Throwback Discord](https://discord.gg/r6s-operation-throwback-1092820800203141130)** for season download/setup help and Throwback launcher support.

| Component | Download / source | Version / selection |
| --- | --- | --- |
| **Throwback launcher** | [ThrowbackLauncher.exe — direct download](https://github.com/xeralin/ThrowbackLauncher/releases/download/v0.2.2/ThrowbackLauncher.exe) · [release page](https://github.com/xeralin/ThrowbackLauncher/releases/tag/v0.2.2) | Community launcher by xeralin; upstream asset v0.2.2 checked on 14 November 2026. |
| **Game season** | Acquire the game files through the launcher with your Steam account that owns Rainbow Six Siege. | Select **Y5S3 Shadow Legacy**. The VR package targets the admitted **Y5S3.3.1** game-file identities. |
| **VR test package** | [Request SIEGE_R51_HANDLING on Flat2VR](https://discord.gg/P4q9zt7ek) | The VR test package is separate from the community launcher and the season’s game files. |

1. Download and run **ThrowbackLauncher.exe** from the upstream release linked above. Its source project is [xeralin/ThrowbackLauncher](https://github.com/xeralin/ThrowbackLauncher).
2. Use your Steam account that owns Rainbow Six Siege and select **Y5S3 Shadow Legacy** in the launcher. Keep this legacy installation in its own game folder.
3. Confirm the game is the supported **Y5S3.3.1** variant and can reach ordinary local gameplay, then close it. The VR launcher checks the admitted files; the season label alone does not establish compatibility.
4. Get the full **SIEGE_R51_HANDLING** VR package from the Siege thread on Flat2VR. Locate **RainbowSix.exe** in the installed season and extract the complete mod folder next to it.
5. Connect and wake PC VR, then open **RUN.bat** inside the VR folder normally. Keep its console open. The ordinary Throwback play button is not the VR entry point.
6. Enter **LOCAL Training Grounds** with keyboard/mouse; VR stereo activates in gameplay. Close the game or use Ctrl+C in the launcher when finished, then send **SEND_THIS_LOGS.zip** to the Discord thread.

Current test-package availability is coordinated in Discord. Use the complete package for your supported game build; this project page is separate from a release download.

## What this project brings to VR

- OpenXR stereo, a completed-left-eye mirror and fixed 2200-pixel eye width in the current candidate.
- Tracked weapon/hand handling and corrected nested attachment composition.
- Supporting-hand grip at a native foregrip or a captured support point.
- Crouch/prone, native context actions, reload and separate gadget buttons.
- Optional validated HANDLING.json calibration for the current candidate.

<details>
<summary><b>Controller quick reference</b></summary>

| Input | Action |
| --- | --- |
| Left stick / click | Move / toggle sprint |
| Right stick horizontal / click | Turn / melee |
| Right stick up / down | Secondary gadget / scoreboard |
| Right trigger / right grip | Native fire or activation / reload |
| Left trigger / left grip | Primary gadget / supporting hand |
| X / Y | Interact / cycle weapon |
| A / B tap / B hold | Vault-climb-rappel context / crouch / prone |
| Left Menu | Recenter |

The complete package control sheet takes precedence for its version and interaction profile.

</details>

## Current status

**Experimental preview.** The R201 startup path has a tester-confirmed Steam Frame/SteamVR image on an RX 9070 XT. This does not certify every headset.

- The new handling requires physical-headset testing. Reticles, shield collision, gadget coverage and near-object visibility remain open.
- Manual magazine reloading, full operator/loadout coverage, hardware FPS acceptance and multi-user LAN validation are not established.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | First-person exploration, climbing and sword interaction | Private |
| [Crysis 2: VRevamp](https://github.com/Monsterdeadwood/C2VR) | Nanosuit combat, physical interaction and spatial UI | Public |
| [Star Wars: The Force Unleashed II VR](https://github.com/Monsterdeadwood/TFU2VR) | Dual lightsabers, independent telekinesis and Force powers | Public |
| [NOVA · CS:GO Legacy VR](https://github.com/Monsterdeadwood/CSGOVR) | CS:GO Legacy local matches with motion controls | Public |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Time powers, nine weapons and roomscale posture | Public |
| [You Are Empty: Absolute Edition VR](https://github.com/Monsterdeadwood/YouAreEmptyAEVR) | Absolute Edition VR, weapons and hand interaction | Public |
| [Alone in the Dark 2008 VR](https://github.com/Monsterdeadwood/AloneInTheDark2008VR) | Survival-horror VR and held-item interaction | Public |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Stereo driving, vehicle menus and native effects | Public |
| [Titanfall 1 VR](https://github.com/Monsterdeadwood/Titanfall1VR) | Pilot combat and Titan cockpit VR | Public |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Original Metro VR and native physics experiments | Public |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Early VR integration research | Private |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Counter-Strike: Source VR development | Private |

Private repository links are available to invited collaborators. Public project pages are marked above.

## Credits & development notes

Project maintained by [Monsterdeadwood](https://github.com/Monsterdeadwood). This is an independent fan VR project; you need your own supported copy of the original game.

Documentation reviewed: **14 November 2026**.
