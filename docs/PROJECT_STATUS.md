# Rainbow Six Siege VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **14 November 2026**. Documented branch: **R51 handling package / R202 development revision**.

## What has been checked

- The R201 startup path has a tester-confirmed Steam Frame/SteamVR image on an RX 9070 XT. This does not certify every headset.
- R202 support-grip acquire/steer/walk/release/re-grip behavior was checked in the actual game with XR Sim.

## Follow-up tests reviewed 16 November 2026

R203/R51 Continuity exercised the input and stereo paths in XR Sim. The R208 report records the R205 foreground shot with same-weapon muzzle geometry, ammo decrement, recoil and new stereo pairs. Installation and behavior on all hardware, background shooting and native gadget placement need separate qualification.

Verification records used for this section

- `SIEGE_R203_TESTER_FOLLOWUP_20261115.json`
- `SIEGE_R208_NATIVE_SHOT_AND_RENDER_20261115.json`
- `SIEGE_R209_NATIVE_SCENE_AND_PLACEMENT_20261116.json`

## Current limits

- The new handling requires physical-headset testing. Reticles, shield collision, gadget coverage and near-object visibility remain open.
- Manual magazine reloading, full operator/loadout coverage, hardware FPS acceptance and multi-user LAN validation are not established.

## Build access

Ask for the current complete test package in the game’s Flat2VR thread. A local build record does not by itself mean a file has been uploaded to this repository’s Releases.

## Documentation basis

This overview was reconciled against the project’s recorded package notes and validation records. The following names identify the records reviewed; they are not download links:

- `SIEGE_R202_PLAYER_HANDLING_20261114.json`
- `SIEGE_R51_HANDLING_20261114/README.txt`
- `SIEGE_PLAYER_FIXES_20261114.txt`
- `Upstream xeralin/ThrowbackLauncher v0.2.2 release and Y5S3_ShadowLegacy manifest, checked 2026-11-14`

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.
