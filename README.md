# LotusIDE — Downloads

**Lotus ArduiBot IDE** — Learning by Doing. An Arduino-style IDE for Lotus robotics boards, built on Electron + Vue 3 + Blockly.

## Download

Get the latest version from the [**Releases page**](https://github.com/jaturong-kamonlers/LotusIDE-Releases/releases).

### Pick the right installer

| File | Size | Format | ESP32 bundled? | When to pick |
|------|------|--------|----------------|--------------|
| `Lotus-IDE-Setup-x.y.z.exe` | ~260 MB | Installer | No — lazy install | Most users at home with internet |
| `Lotus-IDE-x.y.z-win.zip` | ~270 MB | Portable | No — lazy install | No admin rights / USB key |
| `Lotus-IDE-Full-Setup-x.y.z.exe` | ~1.3 GB | Installer | Yes — pre-bundled | Classrooms / offline labs |
| `Lotus-IDE-Full-x.y.z-win.zip` | ~1.3 GB | Portable | Yes — pre-bundled | USB-stick deployment to many classroom PCs |

## Quick start

1. Download `Lotus-IDE-Setup-x.y.z.exe` (Slim, ~260 MB)
2. Double-click → Install (~30 sec to 2 min on SSD)
3. Open LotusIDE → start coding for Arduino Uno / Nano / Mega / Due / Lotus AVR boards

For ESP32 boards (Lotus DevKit), the first compile downloads the toolchain (~15-25 min, one-time). Or pick the Full SKU to skip that wait.

## Windows SmartScreen

The installer is not yet code-signed, so Windows will warn:

> Windows protected your PC

Click **More info** → **Run anyway**. This is normal for unsigned freeware.

## System requirements

- Windows 10 or 11, 64-bit
- ~600 MB free disk (Slim) or ~5.7 GB (Full + ESP32)
- USB port for board upload

## Report bugs

[Open an issue](https://github.com/jaturong-kamonlers/LotusIDE-Releases/issues/new) with:
- LotusIDE version (Help → About)
- Windows version
- What you were doing + what happened
- Screenshot or error message text

## License

LotusIDE is provided free of charge for educational use by students and teachers.

- ✅ Allowed: install, use, distribute the unmodified installer to students
- ❌ Not allowed: reverse engineering, decompilation, extracting source from binaries, republishing under another name

Source code is not publicly available. Copyright (c) 2026 Jaturong Kamonlers. All rights reserved.