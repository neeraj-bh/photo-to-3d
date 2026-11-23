# SunTec Photo-to-3D

Downloads for the **SunTec Photo-to-3D** desktop app, which turns product photos into detailed 3D models (with Tripo AI), then lets you review them, tick the QC checklist and export them (GLB, FBX, OBJ, USDZ, a light web version and a client pack). This repository holds only the installers; there is no source code here.

## Download

| Computer | File |
|---|---|
| Mac with an Apple chip (M1 or newer) | [SunTec-Photo-to-3D-mac-apple-silicon.dmg](https://github.com/neeraj-bh/photo-to-3d/releases/latest/download/SunTec-Photo-to-3D-mac-apple-silicon.dmg) |
| Mac with an Intel chip | [SunTec-Photo-to-3D-mac-intel.dmg](https://github.com/neeraj-bh/photo-to-3d/releases/latest/download/SunTec-Photo-to-3D-mac-intel.dmg) |
| Windows 10 or 11 | [SunTec-Photo-to-3D-windows-setup.exe](https://github.com/neeraj-bh/photo-to-3d/releases/latest/download/SunTec-Photo-to-3D-windows-setup.exe) |

Not sure which Mac you have? Apple menu › **About This Mac**: "Chip: Apple M…" is an Apple chip, "Processor: Intel" is Intel.

## Opening it the first time

The app isn't signed yet, so your computer asks once:

- **Mac:** open the `.dmg` and drag **SunTec Photo-to-3D** into **Applications**, then open it. When macOS says it can't check the app, open **System Settings › Privacy & Security**, scroll down and click **Open Anyway**.
- **Windows:** open the setup. If "Windows protected your PC" appears, click **More info › Run anyway**. It installs for you only and needs no admin rights.

Sign in with the name and PIN your SunTec admin gave you. For FBX files the app uses your own Blender (4.2 or newer), which it finds by itself.

After that it opens like any other app. It checks for new versions when it opens (and from Help › Check for Updates…) and updates itself. Your photos and models stay on your computer; only the photos you send for a 3D model go to Tripo.

Every release includes `checksums.txt` (SHA-256) for its files.
