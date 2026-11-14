# Rainbow Six Siege VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **14 November 2026**. Documented branch: **R51 handling package / R202 development revision**.

## What has been checked

- The R201 startup path has a tester-confirmed Steam Frame/SteamVR image on an RX 9070 XT. This does not certify every headset.
- R202 support-grip acquire/steer/walk/release/re-grip behavior was checked in the actual game with XR Sim.

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

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.

## Кратко по-русски

Экспериментальный VR-мод поддерживаемой PC-сборки Throwback Y5S3 Shadow Legacy / Y5S3.3.1. Текущий маршрут тестирования — локальные Training Grounds, стереообзор, управление контроллерами и двуручное удержание оружия.

- Новому удержанию нужна проверка в физическом шлеме. Сетки прицелов, коллизия щита, покрытие гаджетов и видимость близких объектов ещё в работе.
- Ручные магазины, все операторы и наборы оружия, принятие FPS на железе и многопользовательская LAN-проверка не подтверждены.
