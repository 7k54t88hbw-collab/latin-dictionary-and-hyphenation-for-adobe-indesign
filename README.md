# Latin Dictionary and Hyphenation for Adobe InDesign

These dictionaries let Latin writers and editors spell-check Latin and apply Classical Latin hyphenation in Adobe InDesign. The Standard profile contains 1,832,979 source-listed spelling entries and can generate 70,783 inflected forms; the more selective Macron-enforcing profile contains 1,167,384 entries and can generate 60,106 inflected forms, from the English Wiktionary snapshot dated 1 November 2026.

Download the latest release from the [GitHub Releases page](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/latest).

The release includes a macOS Installer, Uninstaller, and manual-install archive, along with release notes, provenance manifests, licensing notices, and SHA-256 checksums.

## Choose a spelling profile

- **Standard** is intended for broad spelling acceptance and retains Hunspell's usual case variants for lowercase source spellings.
- **Macron-enforcing** requires exact source case and excludes an unmarked spelling only when the same Wiktionary entry provides a canonical macronized spelling for that form. It assumes that only proper nouns are capitalised; words are not capitalised just because they begin a sentence. This matches the maintainer's house style. It retains distinct forms and spellings whose vowel quantities are unknown.

Both profiles include Classical Latin hyphenation.

## Compatibility and installation

The package targets InDesign 2027 and macOS 14, 15, 26, and 27. The Installer and Uninstaller are unsigned; macOS may require approval in System Settings → Privacy & Security. Installation modifies files inside the selected InDesign app bundle and may need to be repeated after an Adobe update.

Automated dictionary and package checks passed for the release. A previous InDesign 2027 probe used earlier dictionary artifacts; the released package has not received a fresh live-app smoke test. The project does not claim that every targeted InDesign/macOS combination was tested.

## Licensing and provenance

The release contains Wiktionary-derived data under CC BY-SA 4.0, Gregorio Classical Latin patterns under MIT terms, and MIT-licensed installer code. See the release's `THIRD-PARTY-NOTICES.txt`, `LICENSE-MIT.txt`, and provenance manifests. The contents have different terms, so no single repository-wide license applies.

The dictionaries, hyphenation data, Installer, and Uninstaller are provided “as is,” without warranty of any kind. See the included licenses and notices for their full terms.

## Feedback

I'm Nigel Gourlay, the maintainer. If you use these dictionaries, have feedback, or spot a problem, please [open an issue in this repository](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/issues).

If you use these dictionaries and find them useful, please take a moment to pray for people who are hurting or hard for you to love, the sick and the suffering, prisoners, and your enemies.
