# Bible Memory Skills — Release Notes v2.3

## Changelog

### v2.3
- Paste a verse copied from Bible.com (verse, reference, and link) into the **Verse text** box and the app fills in the Book, Chapter, Verse, Through verse, Version, and verse text for you.
- The Bible.com link and the reference are never saved as part of the verse text.
- Quotation marks that are part of the verse (like the ones in John 3:4) are kept. Only Bible.com's outer wrapper quotes are removed.
- The link is also used to identify the book, so Psalms, Song of Solomon, and numbered books (1 John, 2 Timothy, etc.) import correctly.
- The version is read from the end of the link (NIV, ESV, KJV, etc.). A version that is not in the list is filled in under **Other**.
- Pasting several Bible.com verses at once saves them all and skips duplicates.
- Pasting a verse and reference without the link, or the older `Reference | Version` layout, also fills the form.
- Bulk-import (.txt) and Import this verse (.txt) use the same improved reading.
- Version number now shows **v2.3**.

### Files to upload to GitHub
Only `index.html` changed. Upload it to replace the existing one. The icons and `manifest.json` stay as they are.
