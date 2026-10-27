# Hackfest — iPhone beta

**Build the rig. Break the corp.**

[![This beta](https://img.shields.io/github/downloads/yodahlorian/hackfest-beta/latest/total?label=this%20beta&color=16c60c)](../../releases/latest)
[![Earlier betas](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fyodahlorian%2Fhackfest-beta%2Fmain%2Fdownloads.json&query=%24.retired&label=earlier%20betas&color=6a7f99)](downloads.json)

Downloads count AltStore / SideStore installs and direct downloads together.

You were fired from CorpoMax. Order parts, build your tower, image an operating system, boot into HackfestOS, and get even:
crack firewalls, read the logs for the names that open the next door, and seed malware that pays for better hardware.
Beta by **Devious Developments**.

**Play on PC:** [github.com/yodahlorian/Hackfest](https://github.com/yodahlorian/Hackfest/releases/latest)

## Install with AltStore (updates itself)

1. In **AltStore** → **Sources** → **+**, add this source:
   `https://raw.githubusercontent.com/yodahlorian/deviousdevelopments/main/source.json`
2. Open **Devious Developments** → **Hackfest** → **Free / Get**. New betas show up as updates.

## Or SideStore (refreshes anywhere, no computer after setup)

Add the same source in **[SideStore](https://sidestore.io)** → Sources → +. It works exactly like AltStore.

## Or Sideloadly (Windows / macOS)

1. Install **[Sideloadly](https://sideloadly.io)** on your computer (Windows also needs iTunes from apple.com, not the Microsoft Store).
2. Download the newest `Hackfest-<version>.ipa` from **[Releases → Latest](../../releases/latest)**.
3. Plug your iPhone in with a cable, unlock it and tap **Trust** if it asks.
4. Open Sideloadly, drag the `.ipa` onto it, enter your Apple ID and press **Start**.
5. On the phone: **Settings → General → VPN & Device Management** → tap your Apple ID → **Trust**.
6. iOS 16 and newer: **Settings → Privacy & Security → Developer Mode** → on (the phone restarts).
7. Open Hackfest and play in landscape. To update, repeat steps 2–4 with the new `.ipa`.

A free Apple ID signs apps for 7 days; re-sideload to refresh. Each new beta replaces the file (one release, one file).

## Touch controls

Everything is a tap: tap where you would click. Drag windows by their title bar; ✕ closes them. Typing fields bring up the
iPhone keyboard. A delivery you are not ready for has a **Later** button.

## Changelog



### 0.20.1.3 — 2026-10-27

- **The Notepad stays above the keyboard.** Once you had written a few lines you were typing under the keyboard; the pad is shorter on iPhone now, so the whole window (and its ✕) stays in view. If a text box would ever end up under the keyboard, the screen slides up until the keyboard closes.
- **No more PC keys in the game's words.** Windows and the phone said "ESC", the PC builder said "click the open case slot", and two lock puzzles said "Click the numbers…" / "Click the glyph…". They say tap now, and the ✕ / Home buttons are the way out.
- **Tapping the motherboard asks first.** One tap on the board in the PC builder used to pull every part out of your rig. Now it asks "Pull the motherboard?" (the Remove board button still works in one tap).
- **What the PC shows on hover is printed on iPhone:** why a RipStore item or dock is greyed out ("Need 10 RC — you have 3", "No drive has 800 MB free"), each Crapazon category's help, and the motherboard slot legend (c = CPU · r = RAM · g = GPU · s = Storage · p = PSU). Hiding the objective tells you how to bring it back.
- **The CryptoMiner and Ransomware no longer say they earn "0/s"** in the stores (the miner pays RipCoin, ransomware one big payout). On PC too.

### 0.20.1.2 — no more dead Exit buttons

- The main menu's **Exit**, the desktop start menu's **Quit** and the phone's **Quit Game** are gone on iPhone (an iPhone app is closed by swiping it away). The PC keeps all three.

### 0.20.1.1 — first iPhone beta

- Hackfest 0.20.1 on iPhone: the full game, landscape, touch (tap = click).
- Deliveries get a **Later** button (the PC closes them with ESC).
- Installs from the Devious Developments AltStore / SideStore source, alongside Killer 2s and Arcadeous.
