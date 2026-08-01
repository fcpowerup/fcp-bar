# FCP Bar

English · [中文版](README.md)

A native macOS taskbar replacement that blends Windows-style taskbar efficiency, a classic Start menu, and modern frosted / liquid glass visuals—with one-click restore of the system Dock whenever you need it.

By **FCPOWERUP**

---

## Get FCP Bar

Download the latest `.dmg` from this repository’s [Releases](https://github.com/fcpowerup/fcp-bar/releases/latest) (the attachment is always named `FCP-Bar.dmg`). Open the disk image, drag **FCP Bar** into **Applications**, then launch it from Launchpad or the Applications folder.

The current public release is **v0.1.3**.

If macOS says the developer cannot be verified: open **System Settings → Privacy & Security** and click **Open Anyway** next to the blocked-app prompt.

---

## Screenshots

Liquid glass vs. frosted glass:

![Liquid glass vs. frosted glass](assets/liquid-vs-frosted-glass-2026-07-27.jpg)

Start menu (left shortcuts + right-side app cascade):

![FCP Bar Start menu](assets/start-menu-cascade-2026-07-27.png)

Settings — taskbar:

![FCP Bar settings — taskbar](assets/settings-taskbar-2026-07-27.png)

About:

![About FCP Bar](assets/settings-about-2026-07-27.png)

---

## Features

- Windows-style taskbar with frosted or liquid glass
- Classic Windows-style Start menu with browsing of the Applications folder
- Multi-display support
- OLED burn-in protection
- Automatically hides the macOS Dock; restores when you quit
- More features on the way

---

## System requirements & permissions

FCP Bar requires **macOS 14** or later on both Apple Silicon and Intel Macs. The liquid glass look requires **macOS 26** or later.

On first launch, grant permissions when macOS prompts you:

- **Accessibility**: FCP Bar needs this to read windows, bring apps to the front, and minimize windows. Without it, the taskbar cannot work properly.
- **Automation (Finder)**: If macOS asks to control Finder, choose **Allow**. This lets FCP Bar show Finder tab and folder titles correctly. If you declined earlier, re-enable it under **System Settings → Privacy & Security → Automation**.
- **Screen Recording**: Only required if you turn on **Hover window preview** in Settings. It is off by default; you do not need this permission if you leave preview disabled.

---

## Tips

1. A **FCP** icon appears in the menu bar. Use it to open Settings, restore the Dock, or view About.
2. Settings let you adjust edge docking, thickness, glass style, grouping, alignment, multi-display behavior, Trash / Stacks / Show Desktop, and more.
3. Press and hold an app on the taskbar for about **0.8 seconds** before dragging to reorder; a short click still activates the window.
4. To stop using FCP Bar temporarily: choose **Restore Dock** from the menu bar or quit the app—the system Dock returns to normal.

---

## Updates

[View release notes](CHANGELOG.en.md)
