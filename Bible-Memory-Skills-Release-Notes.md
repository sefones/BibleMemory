# Bible Memory Skills (Verse Card) — Release Notes

**Current version: v2.6 · September 28, 2026**

This is the one running release-notes file for the app. Each new release adds a fresh "Latest change" recap at the top and moves the previous one down into the history.

---

## Latest change: v2.6 (September 28, 2026)

**Verse text fills in automatically.**

- Tap a result in **Find a verse** (a reference or a topic verse) and the Add screen opens with the reference set *and* the verse text fetched. Check it, then Save.
- A new **Fill in verse text** button on the Add screen fetches text for whatever Book / Chapter / Verse / Version is selected, so manual adds work too.
- **Works for:** KJV, WEB, ASV, and YLT (New Testament only). These are public domain, provided by bible-api.com.
- **Copyrighted versions (NIV, ESV, NLT, etc.):** can't be filled in automatically. The app says so and you paste the text as before. Tip: switch Version to KJV, WEB, or ASV to auto-fill.
- **Needs internet.** Offline, or if the free service is busy, you'll see a note and can paste instead (limit is about 15 lookups per 30 seconds).

---

## Version history

| Version | Date | What was added |
|---|---|---|
| v2.6 | Sep 28, 2026 | Auto-fill verse text (public-domain versions); Fill in verse text button |
| v2.5 | Sep 28, 2026 | **Find a verse** screen: search by reference (John 3:16, Psalm 23, Rom 8:28-30) or tap one of 33 topics (about 200 verses); picking one pre-fills the Add screen |
| v2.4 | Not recorded | **Share** button on the home screen to send all saved verses to someone else |
| v2.3 | Not recorded | Paste a verse copied from Bible.com to auto-fill book, chapter, verse, and version; only the verse text is saved, never the link |
| v2.2 | Not recorded | App icon; audible cheer on the celebration screen |
| v2.1 | Not recorded | Removed the Add to Home Screen prompt (it didn't work on iOS/Android); app now used through GitHub Pages |
| v1.x | Not recorded | Earliest builds (see below) |

Dates before v2.5 weren't tracked. If you remember roughly when they went out, tell me and I'll fill them in. From v2.6 on, every release gets a date.

## Overview: everything the app does today

**Practice**
- Prompts for your Bible version
- Learn a new verse at random, or choose a specific one from your saved verses
- When you miss a word, shows what you got right plus the next word, then lets you keep trying
- Adjustable hint amount ("how full") that you can change at any time
- Read-aloud so you can hear the verse
- Celebration screen with a cheer when you finish

**Adding verses**
- **Find a verse:** reference search or topic list, with the verse text filled in automatically for KJV/WEB/ASV/YLT
- Paste from Bible.com to auto-fill everything
- Paste or type the text yourself for any version
- Mic dictation on Add Verse, Practice, and the celebration screen

**Everything else**
- Splash screen on launch with the "love each other" image
- Version number shown next to the title
- Share button to send your saved verses to someone
- Hosted on GitHub Pages so it works on iOS and Android

---

## Updating your GitHub Pages site

1. Rename `Bible-Memory-Skills-v2.6.html` to `index.html`.
2. In the `sefones/BibleMemory` repo, upload it over the existing `index.html` and commit.
3. Wait a minute or two, then reload (hard refresh on your phone if you still see the old version).

## Adding more topics later

Topics live in one list in the "find a verse" section of the file. Each line is `Topic name|search words|Reference;Reference;...`. Tell me the topics you want and I'll add them in the next release.
