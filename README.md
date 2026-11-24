# Latin and Ancient Greek Dictionaries for Adobe InDesign

Version 2.0.0 · Combined Latin and Ancient Greek release

These dictionaries provide Latin and Ancient Greek spelling and hyphenation for Adobe InDesign 2027. The combined Installer and Uninstaller let you choose Latin and Ancient Greek independently, with a spelling profile for each selected language.

## Download

[**Download the macOS Installer app (v2.0.0)**](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/download/v2.0.0/Latin-and-Ancient-Greek-Dictionaries-for-Adobe-InDesign-2.0.0-Installer.app.zip)

Read the INSTALLATION section below. See the [v2.0.0 release page](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/tag/v2.0.0) for the Uninstaller app, manual-install archive, release notes, notices, provenance manifests, and checksums.

Installing a selected language replaces its existing dictionary folder without keeping a copy. Deselecting a language leaves it unchanged. The Uninstaller removes project-managed dictionaries and registrations.

## Included dictionaries

- **Latin:** Standard and Macron-enforcing spelling profiles, with Classical Latin hyphenation.
- **Ancient Greek:** Standard and Polytonic-enforcing spelling profiles, with Greek hyphenation.

Latin Standard is intended for broad spelling acceptance; Latin Macron-enforcing requires source case and canonical macron spellings where recorded. Ancient Greek Standard ignores pitch accents during lookup while enforcing breathing; Ancient Greek Polytonic-enforcing requires source-backed accents and capitalization. Macron and breve are ignored for Greek lookup.

Both tools select the highest-version InDesign app found under `/Applications` by default. They show its name, version, and full path; the final confirmation screen offers **Change Target…**.

## INSTALLATION: Open the Installer app

The Installer and Uninstaller apps are unsigned. macOS may show a Gatekeeper warning. Download them only from this project's release repository.[^checksum]

1. Expand the Installer app ZIP in Finder. Quit InDesign, then Control-click the app and choose **Open**. If macOS blocks it, choose **Done** to dismiss the warning and keep the app.
2. Open **System Settings → Privacy & Security**. In the **Security** section, find the Installer message and click **Open Anyway**. Confirm that you want to open the app if macOS asks.
3. If **Open Anyway** is not shown, check the Security section again after trying to open the app. The approval control may be temporary or unavailable; managed Macs may disable it. If approval is unavailable, use the manual-install archive linked on the release page.
4. The target prompt selects the highest-version InDesign app found under **Applications** and displays its name, version, and full path. Choose **Use This App** or **Change…** to select another app.
5. Choose Latin, Ancient Greek, or both. Select a spelling profile separately for each chosen language, then confirm the installation.

## REMOVAL: Use the Uninstaller app

1. Download and expand the Uninstaller app ZIP from the [v2.0.0 release page](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/releases/tag/v2.0.0).
2. Control-click **Latin-Greek-Hunspell-InDesign-Uninstaller.app** and select **Open**. If Gatekeeper blocks it, use the app-specific approval options in **System Settings → Privacy & Security**.
3. Choose the InDesign app shown as the target, or select **Change…**. Confirm **Remove Dictionaries** and authorize the removal when macOS requests it.

## Help! My spell-check stopped working!

If InDesign stops spell-checking text in any language and shows no error:

1. Save your work and quit InDesign.
2. Download and run the Uninstaller from the release page. Select the InDesign application you use and remove the project-managed dictionaries.
3. Start InDesign and spell-check any document.
4. Quit InDesign again.
5. Run the Installer from the same release and reinstall the Latin and/or Ancient Greek dictionaries you use.
6. Start InDesign again to use the dictionaries.

[^checksum]: To verify a downloaded app ZIP, open Terminal, type `shasum -a 256 `, drag the downloaded `.app.zip` file into the Terminal window, and press Return. Compare the result with that asset's entry in `SHA256SUMS.txt` on the release page.

## Compatibility and licensing

The apps target InDesign 2027 and macOS 14, 15, 26, and 27. Installation modifies resources inside the selected InDesign app bundle, may affect its code signature, and will need to be repeated after each InDesign upgrade.

The release contains Wiktionary-derived data under CC BY-SA 4.0, Gregorio Classical Latin patterns under MIT terms, Ancient Greek patterns with their MIT notice, and MIT-licensed installer code. See the release's `THIRD-PARTY-NOTICES.txt`, `LICENSE-MIT.txt`, and provenance manifests. The contents have different terms, so no single repository-wide license applies.

The dictionaries, hyphenation data, Installer, and Uninstaller are provided “as is,” without warranty of any kind. See the included licenses and notices for their full terms.

## Feedback

I'm Nigel Gourlay, the maintainer. If you use these dictionaries, have feedback, or spot a problem, please [open an issue in this repository](https://github.com/7k54t88hbw-collab/latin-dictionary-and-hyphenation-for-adobe-indesign/issues).

If you use these dictionaries and find them useful, please take a moment to pray for people who are hurting or hard for you to love, the sick and the suffering, prisoners, and your enemies.
