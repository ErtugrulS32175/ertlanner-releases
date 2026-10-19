<p align="center">
  <img src="docs/images/icon.png" width="96" height="96" alt="Ertlanner icon">
</p>

<h1 align="center">Ertlanner</h1>

<p align="center">A personal planner for students and young professionals, on Windows and macOS.</p>

<p align="center"><b>English</b> · <a href="README.tr.md">Türkçe</a></p>

<p align="center">
  <a href="https://github.com/ErtugrulS32175/ertlanner-releases/releases/latest"><img src="https://img.shields.io/github/v/release/ErtugrulS32175/ertlanner-releases?label=latest&color=217a4b" alt="Latest release"></a>
</p>

Ertlanner is a desktop app for your class schedule, focus sessions and a daily study log. The interface is in Turkish.

![Card collection](docs/images/collection.png)

## Download

Get the latest version from the [releases page](https://github.com/ErtugrulS32175/ertlanner-releases/releases/latest) and pick one file:

| Computer | File |
| --- | --- |
| Windows 10 or 11, 64-bit | `Ertlanner-Setup-<version>.exe` |
| Mac with Apple silicon (M1 or newer), macOS 13+ | `Ertlanner-<version>-arm64.dmg` |
| Mac with Intel, macOS 13+ | `Ertlanner-<version>-x64.dmg` |

The other files (`.blockmap`, `.zip`, `.sig`, `latest*.yml`) are for the updater. You don't need them.

### First Run

- **Windows:** SmartScreen warns that the publisher is unknown. Click **More info**, then **Run anyway**.
- **Installer:** keep **Only for me**. An install for all users cannot update itself.
- **macOS:** if the app is blocked, go to **System Settings > Privacy & Security** and click **Open Anyway**. You only do this once.

After the first run Ertlanner updates itself on Windows: it downloads the new version in the background, checks its signature and installs it when you quit. On a Mac it tells you when a new version is out.

## What It Does

- Weekly class schedule. You can add classes to a single week, and your Google Calendar meetings show up too (read-only).
- A focus timer. Each finished session of 10 minutes or more gives you a card from one of nine illustrated collections. Longer sessions give rarer cards, in six tiers from Wood (10 minutes) to Titanium (2 hours). Cards have no scores.
- A study log: questions solved per subject each day, with a topic and a note. Questions you couldn't solve can be saved with a photo and reviewed later.
- History, stats and a private rating at the end of each day.
- School or university mode. School mode hides the CV, internship and project pages. University mode adds a CV and transcript archive, a study-abroad internship tracker and projects with weekly tasks.
- Optional Google sign-in to sync your own computers through a hidden app folder in your Google Drive.
- Optional teams: invite people by email, share weekly schedules and study logs, leave feedback, chat, mark someone as coach. In school mode you can add friends, see each other's weekly focus score and share collections.

![Study log](docs/images/study-log.png)

## Privacy

Your data stays on your computer unless you turn on sync, a team or friends. Details are in the [privacy policy](https://ertugruls32175.github.io/ertlanner-site/privacy/).

## About This Repository

This repository only hosts installers and update files. The source is private. For bugs and suggestions, open an issue at [ertlanner-site](https://github.com/ErtugrulS32175/ertlanner-site/issues).
