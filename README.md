<p align="center">
  <img src="assets/branding/metaedit-icon.png" alt="MetaEdit" width="96" height="96">
</p>

<h1 align="center">MetaEdit</h1>

<p align="center"><strong>Advanced Tag Editor for Windows</strong></p>

<p align="center">Metadata, artwork and library care for audio and video collections.</p>

<p align="center">
  <a href="https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/releases/latest"><strong>Download</strong></a> ·
  <a href="https://arctisoft-studio.com/software/metaedit/">Product website</a> ·
  <a href="https://arctisoft-studio.com/pricing/">Editions &amp; pricing</a> ·
  <a href="https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/releases">Release notes</a> ·
  <a href="https://arctisoft-studio.com/support/">Support</a>
</p>

<br>

[![MetaEdit with the file library, metadata editor, embedded artwork and a staged change](assets/screenshots/metaedit-editor.png)](https://arctisoft-studio.com/software/metaedit/)

<p align="center"><sub>The metadata editor with a staged change, comparing staged and on-disk values for a fictional demonstration library. More views in the <a href="https://arctisoft-studio.com/software/metaedit/">product gallery</a>.</sub></p>

MetaEdit is the metadata editor of Arctisoft Studio. Correct individual files, tag whole albums, manage embedded artwork, identify releases and keep large libraries consistent with reusable rules. Every change is staged first: you compare the proposed values with the tags on disk before anything is written, and undo and saved workflow recovery remain available afterwards.

## Capabilities

- **Precise and batch editing.** Standard, custom and format-specific fields — credits, release information, identifiers, sorting, lyrics and video metadata — with field sets and editor layouts for recurring work.
- **Change review and recovery.** Staged values beside on-disk values, a per-file view of affected fields, undo and redo, and saved workflow recovery.
- **Artwork collections.** Add, replace, reorder, describe and export embedded images, assign picture types, and control dimensions and format.
- **Auto Tag.** Identify single tracks, whole releases or complete libraries against the Arctisoft Catalogue, with track mappings and confidence presented for review.
- **Autopilot.** One run through identification, metadata repair, artwork, lyrics and duplicate review. Eligible changes are applied; uncertain identities and conflicts are left for you.
- **Library care.** Indexed libraries, Library Health, duplicate detection by local audio fingerprint, and Clean & Organize for file and folder organisation that carries cover art, lyrics and cue sheets along.
- **Rules and text tools.** Rule Studio with per-action conditions and chained rules, text transformations, three filename converters, Transfer Tags, and CSV, JSON, HTML and playlist interchange.
- **Delivery preparation.** Delivery Check for metadata, artwork, formats and release consistency; loudness and true-peak measurement with ReplayGain (native R128 gain for Opus); and a Chapter Editor that imports and exports cue sheets, Audacity labels, Ogg and FFmpeg chapters.
- **Studio Automation.** Saved jobs with dry runs and reports, hourly or daily schedules through Windows Task Scheduler, watch folders and a command-line runner.

An offline user guide and keyboard reference are built into **Help**.

## Editions

Basic is a complete tag editor. Premium is the studio layer: work repeated by rule, applied to whole releases and libraries, or delivered to a specification. Every Premium workflow opens, analyses and previews in Basic; Premium is needed at the step where its result is applied. The number of files, tag fields and formats, undo and recovery are never limited by the edition.

| | Basic · free | Premium |
| --- | :---: | :---: |
| Batch and per-file editing, every field, artwork, text and filename tools | ✓ | ✓ |
| Change review, undo, redo and workflow recovery | ✓ | ✓ |
| Auto Tag for single files | ✓ | ✓ |
| Auto Tag for whole releases and libraries | Identify and review | Stage results |
| Autopilot and Clean & Organize | Plan and review | Apply |
| Rule Studio | Build and preview | Stage results |
| Library Health, duplicate review and filter expressions | ✓ | ✓ |
| Persistent indexed libraries | One | Any number |
| Delivery Check | Music library profile | All built-in and your own profiles, saved reports |
| Loudness and ReplayGain | Measure, review and export | Also stage values |
| Chapter Editor | Inspect, validate, import and export | Also write chapters |
| Container mapping profiles | Standard mapping | Your own profiles |
| Studio Automation | — | Jobs, schedules, watch folders and command line |

Auto Tag requires sign-in through [Arctisoft Studio Hub](https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub) in both editions and is subject to account allowances.

Premium is a one-time purchase for one person, covering the licensed major version and all updates within it, on up to three computers at a time; a licensed computer keeps working offline for 30 days. A 14-day trial is available once per account and computer. Nothing saved with Premium or during a trial is removed when Premium ends. See [current pricing](https://arctisoft-studio.com/pricing/); **Help > Edition & License** shows the state of this computer.

## System requirements

| | |
| --- | --- |
| Operating system | Windows 10 or Windows 11, 64-bit (x64) |
| Runtime | Included with the installer |
| Installation | For your Windows user account; administrator rights are not required |
| Internet | For Auto Tag, artwork and lyrics searches, sign-in, licensing and updates; editing works offline |

| Supported files | |
| --- | --- |
| Audio | MP3, FLAC, WAV, AIFF, Ogg Vorbis, Opus, AAC, M4A/M4B, WMA, APE, WavPack, DSF |
| Video | MP4, MKV, MOV, WMV, M4V, WebM |

Available fields, artwork and chapter operations depend on the container. Some playback, analysis and container operations use additional media tools; MetaEdit tells you when one is needed.

## Installation and updates

1. Download `v<version>-metaedit.exe` from the [latest release](https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/releases/latest).
2. Run the installer and accept the license agreement. Setup can also install [Arctisoft Studio Hub](https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub).
3. Start MetaEdit. Sign in through Studio Hub for Auto Tag, Premium or the trial.

MetaEdit checks this repository for updates and installs a new version only after verifying it against the SHA-256 checksum GitHub publishes for the release. Studio Hub can install and update the whole Arctisoft collection from one place.

## Accounts and privacy

Local metadata editing does not require an account. Auto Tag sends search text — album, artist, folder name and track information — and track lengths to the Arctisoft Catalogue; audio and full file paths are never sent. Artwork and lyrics searches you request contact the Cover Art Archive and LRCLIB. Audio fingerprints for duplicate detection stay on your computer. Preference sync is optional and off by default. The [Privacy Policy](https://arctisoft-studio.com/legal/privacy/) describes the connected services and account data involved.

## Support

Open the user guide from **Help**, visit [Arctisoft Support](https://arctisoft-studio.com/support/) or write to [support@arctisoft-studio.com](mailto:support@arctisoft-studio.com). Report reproducible problems and suggest improvements through [GitHub Issues](https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/issues). Please keep license keys, account details and personal files out of public reports.

## License

MetaEdit is proprietary commercial software. This repository holds its public documentation and official releases; the source code is not published. Use is governed by the [MetaEdit EULA](LICENSE), the [Arctisoft Studio License Agreement](https://arctisoft-studio.com/legal/license/) and the [Terms of Service](https://arctisoft-studio.com/legal/terms/). Open-source components are listed with their licenses in the third-party notices installed with MetaEdit. Artwork and lyrics remain subject to their rights holders' permissions.

---

<p align="center"><sub>© 2025–2026 Arctisoft Studio · Bernd Julian Hagen · Austria. All rights reserved.</sub></p>
