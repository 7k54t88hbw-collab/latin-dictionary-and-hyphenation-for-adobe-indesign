# Latin Dictionary and Hyphenation for Adobe InDesign

These dictionaries let Latin writers and editors spell-check Latin and apply Classical Latin hyphenation in Adobe InDesign. The Standard profile contains 1,832,979 source-listed spelling entries and can generate 70,783 inflected forms; the more selective Macron-enforcing profile contains 1,167,384 entries and can generate 60,106 inflected forms, from the English Wiktionary snapshot dated 1 November 2026.

## Download

[**Download the macOS Installer (v1.0.8)**](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/download/v1.0.8/Latin-Dictionary-and-Hyphenation-for-Adobe-InDesign-1.0.8-Installer.pkg)

Read the INSTALLATION section, below.

See the [v1.0.8 release page](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/tag/v1.0.8) for the Uninstaller and manual-install archive, which includes `INSTRUCTIONS.txt`.

The release includes a macOS Installer, Uninstaller, and manual-install archive, along with release notes, provenance manifests, licensing notices, and SHA-256 checksums.

## INSTALLATION: Apple could not verify  'Latin Dictionary and Hyphenation for InDesign'

The Installer and Uninstaller are unsigned because Apple charges fees for its Developer ID Installer program, and those fees are not supportable for this small project with a limited audience. Before opening the package, download it only from this project's release repository.[^checksum]

1. Quit InDesign; the Installer does not close it for you. Then open the downloaded Installer. If macOS says it was blocked to protect your Mac or that Apple could not verify it, choose **Done** to dismiss the warning and keep the package.
2. Open **System Settings → Privacy & Security**. In the **Security** section, find the Installer message and click **Open Anyway** beside it. Confirm that you want to open the package if macOS asks.
3. If **Open Anyway** is not shown, check the Security section again after trying to open the package. Wording and location vary by macOS version; look for the equivalent package-specific approval control. The control may be temporary or unavailable, and managed Macs may disable it. If approval is unavailable, use the manual-install archive linked on the release page.
4. When the chooser says **Choose your Adobe InDesign application to update**, select the Adobe InDesign application you want to update. In the default location, open **Applications** and then the folder named for your InDesign version. Select the Adobe InDesign application inside that folder and click **Open**. If it is installed elsewhere, navigate to it. Select the application itself, not its containing folder.
5. Choose **Standard** or **Macron-enforcing** when prompted, then follow the Installer prompts.

[^checksum]: If you wish to verify that the downloaded Installer matches the file listed on the release page, open Terminal, type `shasum -a 256 `, drag the downloaded `.pkg` file into the Terminal window, and press Return. Download `SHA256SUMS.txt` from the same release page and compare the hash printed by Terminal with the Installer's entry.

## Choose a spelling profile

- **Standard** is intended for broad spelling acceptance and retains Hunspell's usual case variants for lowercase source spellings.
- **Macron-enforcing** requires exact source case and excludes an unmarked spelling only when the same Wiktionary entry provides a canonical macronized spelling for that form. It assumes that only proper nouns are capitalised; words are not capitalised just because they begin a sentence. This matches the maintainer's house style. It retains distinct forms and spellings whose vowel quantities are unknown.

Both profiles include Classical Latin hyphenation.

## Compatibility and installation

The package targets InDesign 2027 and macOS 14, 15, 26, and 27. Installation modifies files inside the selected InDesign app bundle and will need to be repeated after each Adobe InDesign upgrade.

## Licensing and provenance

The release contains Wiktionary-derived data under CC BY-SA 4.0, Gregorio Classical Latin patterns under MIT terms, and MIT-licensed installer code. See the release's `THIRD-PARTY-NOTICES.txt`, `LICENSE-MIT.txt`, and provenance manifests. The contents have different terms, so no single repository-wide license applies.

The dictionaries, hyphenation data, Installer, and Uninstaller are provided “as is,” without warranty of any kind. See the included licenses and notices for their full terms.

## Feedback

I'm Nigel Gourlay, the maintainer. If you use these dictionaries, have feedback, or spot a problem, please [open an issue in this repository](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/issues).

If you use these dictionaries and find them useful, please take a moment to pray for people who are hurting or hard for you to love, the sick and the suffering, prisoners, and your enemies.
