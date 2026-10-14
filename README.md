<p align="center">
  <img src="images/metaedit-logo.png" alt="MetaEdit" width="112">
</p>

<h1 align="center">MetaEdit</h1>

<p align="center"><b>Advanced Tag Editor</b></p>

<p align="center">Organise metadata and artwork across entire libraries with batch editing, rules, chapters, preflight and undo.</p>

<p align="center">
  <a href="https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/releases/latest"><b>Download</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub"><b>Studio Hub</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#editions-and-licensing"><b>Editions</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#support"><b>Support</b></a>
</p>

<p align="center"><img src="images/divider.svg" width="720" alt=""></p>

## Overview

MetaEdit is a metadata workstation for audio and video files. It edits one file or thousands, shows every change for review before it is written, and keeps a complete undo history, artwork included. Persistent libraries index the folders you choose, Auto Tag identifies recordings and releases from eligible catalogue data and references, and rules, delivery checks and automation keep a collection consistent over time.

### Editing

- Batch and per-file editing of 46 standard tag fields, plus format-specific and custom fields and video container metadata
- Change review before anything is written, with undo and redo of complete snapshots
- Artwork collections with picture types, cover search, resizing and format control
- Reusable field sets and editor layouts

### Tagging and organisation

- Auto Tag with acoustic matching, trusted references, MusicBrainz CC0 core facts and optional Wikidata structured metadata; exact release mapping and field-by-field review
- Artwork from your embedded/sidecar/reference images and verified CC0 Commons images; lyrics from embedded text, matching sidecars and indexed references
- Tags from filenames, filenames from tags, text tools, and CSV, JSON, HTML and playlist interchange
- Rule Studio with conditions, actions and format expressions, and Clean & Organize with rollback protection

### Libraries and delivery

- Persistent indexed libraries with metadata filter expressions, library health and duplicate review
- Delivery Check against built-in and your own profiles, with a report
- ReplayGain loudness after EBU R128 and native chapter editing
- Studio Automation: saved jobs with a dry run, watch folders, a command-line runner and job reports with checksums

<p align="center"><img src="images/divider.svg" width="720" alt=""></p>

## Editions and licensing

Basic is a complete tag editor. Every Premium workflow opens and previews in Basic; Premium is needed where its result is applied.

| | Basic | Premium |
|:--|:--:|:--:|
| Batch editing, artwork, text and filename tools | ✓ | ✓ |
| Auto Tag | Single files | Single files, releases and whole libraries |
| Rule Studio and Clean & Organize | Preview | ✓ |
| Indexed libraries | One | Any number |
| Delivery Check | Music library profile | All profiles, your own, and reports |
| ReplayGain and chapters | Measure and inspect | Write |
| Studio Automation | — | ✓ |
| **Price** | **Free** | **€29.99** one-time |

### Premium license

- **One-time purchase.** No subscription and no renewal. Prices are final; Arctisoft Studio is a small business under the Austrian small-business rule and charges no VAT.
- **Three computers.** One license is for one person and works on up to three computers at the same time. Premium keeps working offline for 30 days at a time.
- **Version rights.** Your entitlement states the covered maximum major version, including earlier supported majors. Later major upgrades require separate rights unless included in your licence.
- **Try before you buy.** Signed in, you can use Premium for 14 days on one computer, without payment details. MetaEdit offers it under Help → Edition & License, and wherever a Premium step is reached.
- **14-day refund** in full, without giving a reason.
- **Transferable** to another Arctisoft account from 30 days after purchase, once in 12 months.

Premium is purchased in [Studio Hub](https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub) under **Store & Upgrades**. Payment is handled by Stripe; the product key is sent by email and registered to your account.

<p align="center"><img src="images/divider.svg" width="720" alt=""></p>

## System requirements

| Requirement | |
|:--|:--|
| **Operating system** | Windows 10 or Windows 11, 64-bit |
| **Runtime** | Included with the installer; nothing else to install |
| **Internet connection** | Optional Wikidata/CC0 artwork lookup, public data downloads, signing in and updates. Reference/catalogue searches, fingerprints and local lyrics work on your computer. |
| **Identification data** | Worldwide core data and broader acoustic coverage are optional downloads and need substantial disk space. Your reference library can be indexed without them. |

## Installation and updates

1. Download the installer from the [latest release](https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/releases/latest).
2. Run it and follow the setup. It installs for your Windows user account, so no administrator rights are needed. Setup can also install Studio Hub alongside it.
3. MetaEdit checks for new versions on the update channel you choose: Stable, Preview or Manual.

Updates are taken only from this repository's official releases. Before an update runs, its installer is checked against the size and SHA-256 digest that GitHub records for the release, and an installation signed by Arctisoft Studio accepts only an installer from the same publisher. MetaEdit can always update by itself; [Studio Hub](https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub) offers the same releases from one place.

## Account and privacy

Your files are read and written on your computer. Audio and fingerprints are not uploaded for identification. Optional Wikidata lookup sends your search terms; catalogue downloads and verified CC0 artwork requests contact their public hosts. MetaEdit works without an account; signing in adds Premium, the trial and optional preference sync.

### Identification in MetaEdit 2

Catalogue & References lets you index trusted recordings and install reusable identification data. MusicBrainz's [CC0 core](https://musicbrainz.org/doc/MusicBrainz_Database) provides worldwide recording, release, track-list and credit facts. Search runs locally; supplementary noncommercial tags, genre associations and search indexes are excluded. [Wikidata structured facts](https://www.wikidata.org/wiki/Wikidata:Licensing) can provide eligible online metadata.

Acoustic identification compares compatible fingerprints with your indexed references and optional [AcoustID public data](https://acoustid.org/database), without using its commercial lookup API. One downloaded month provides partial coverage; historical data extends it and can be large. Fingerprint data is CC-BY-SA-3.0, with public-domain recording mappings. Anyone sharing an adapted fingerprint database must retain applicable attribution and share-alike rights. Metadata facts do not grant copyright permissions for cover images or lyrics; use local content you are entitled to use.

Full third-party licence texts, required library sources and replacement/build instructions accompany the application. Open-source rights remain available for their components; MetaEdit application source remains proprietary. These source changes describe the forthcoming qualified MetaEdit 2 release.

## Support

- **Help in the application:** the **Help** menu in MetaEdit, and **Help & Support** in Studio Hub.
- **Email:** [support@arctisoft-studio.com](mailto:support@arctisoft-studio.com). Include your account ID (Account & Security in Studio Hub) for questions about an account or an order. Never send a password or a product key.
- **Problems and suggestions:** [GitHub Issues](https://github.com/Arctisoft-Studio/MetaEdit-Advanced-Tag-Editor/issues).

## License

MetaEdit is commercial software by Arctisoft Studio. Use is governed by the license agreement in [LICENSE](LICENSE), which the installer also presents, together with the Terms of Service and Privacy Policy available in Studio Hub under **Legal**. 

<p align="center"><img src="images/divider.svg" width="720" alt=""></p>

<p align="center">
  <b>Arctisoft Studio</b> · Austria<br>
  <sub>© 2025–2026 Bernd Julian Hagen. All rights reserved.</sub>
</p>
