# Read Aloud

Reads pasted text, .docx, .pdf and .txt files aloud in Swedish, English, Russian and Ukrainian. It uses the browser's built-in voices and keeps everything on the device.

## Publish on GitHub Pages
1. Create a repository, e.g. `readaloud`, and upload all files in this folder, keeping the `lib/` folder.
2. In the repository, go to Settings → Pages, choose "Deploy from a branch", then `main` and `/ (root)`.
3. Open `https://<username>.github.io/readaloud/`.

## Install on iPhone
Open the link in Safari, tap Share, then "Add to Home Screen". After the first load it works offline.
Better voices are under Settings → Accessibility → Spoken Content → Voices. Download the Enhanced or Premium versions of Swedish, English, Russian and Ukrainian.

## Use locally on a PC
Double-click `index.html`. Edge is recommended because it has natural voices for all four languages.
The local copy and the GitHub copy keep separate libraries. Use Export/Import backup to move positions between them.

## Updating
After changing any file, raise `VERSION` in `sw.js`, e.g. `readaloud-v2`. Otherwise installed copies keep using the cached old version.

## Version 2
- **Contents** (list icon, top right): chapters from PDF bookmarks, Word headings, or detected headings in plain text. You can go to a page, read only a page range, or read only one chapter with "Only this".
- **Long-press a sentence** (right-click on PC) to read from there, set start and end marks, mark or unmark a chapter, or skip a paragraph.
- **Reading blocks:** several start/end pairs, read in order with "Read all blocks". A start without an end reads to the end of the text.
- **Diagnostics:** a speech event log under Settings → Diagnostics. Copy it if reading stalls.
