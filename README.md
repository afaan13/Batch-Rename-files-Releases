# Batch Rename

**Rename files. Not one by one. All at once.**

You know that folder. The one with 47 photos named `IMG_20240512.jpg`, `IMG_20240513.jpg`, and so on. The downloads folder where every PDF is called `document(1)_final(2)_FINAL.pdf`. Batch Rename exists because renaming files manually is soul-crushing, and life's too short for that.

---

## Why This Exists

- **No permissions.** Not one. Android's Storage Access Framework handles everything — the app doesn't even ask.
- **No internet.** No analytics, no trackers, no telemetry. It's just you and your files.
- **No regrets.** Every rename is previewed before it happens. You see exactly what changes, and undo is one tap away.

---

## What It Can Do

### Sequential — "Number them, please."
Turn a chaotic folder into a clean, ordered list. `vacation_001.jpg`, `vacation_002.jpg`, `vacation_003.jpg`.

```
IMG_20240512.jpg    →    trip_001.jpg
IMG_20240513.jpg    →    trip_002.jpg
DSC0999.png         →    trip_003.png
```

### Regex — "Find this pattern, make it that."
Regex replace with capture groups. Strip dates, swap tokens, restructure filenames — the power's yours.

```
Find:    photo_(\d+)-([a-z]+)
Replace: $2_$1

photo_001-raw.jpg   →    raw_001.jpg
photo_042-jpg.jpg   →    jpg_042.jpg
```

### Case — "Make it consistent."
lowercase, UPPERCASE, Title Case, or camelCase. Every file, one style. Extension stays untouched.

```
My Document.PDF      →    my document.pdf
Vacation Pics.JPEG   →    vacation pics.jpeg

my cool video.mp4    →    My Cool Video.mp4
```

### Preserve — "Keep the name, add context."
Tag files without erasing what they were. Add a prefix, a suffix, or both. Original name stays alive.

```
Prefix: final_ | Suffix: _v2

report.docx          →    final_report_v2.docx
notes.txt            →    final_notes_v2.txt
```

---

## How It Works

1. **Pick a folder** — tap the folder icon, choose any directory
2. **Choose a pattern** — Sequential, Regex, Case, or Preserve
3. **Tweak the settings** — prefix, counter, find/replace, anything
4. **Watch the previews update** — every file shows old → new, live
5. **Filter, sort, check, uncheck** — full control over what gets renamed
6. **Apply** — one tap renames everything checked
7. **Changed your mind?** — Undo is staged first; confirm it when you're ready

---

## Free vs Pro

| Free | Pro *(one-time purchase)* |
|---|---|
| 10 files per batch | Unlimited files |
| Sequential, Case, Preserve | \+ Regex find & replace |
| Sort by name & date | Sort by name, date, size, extension |
| — | Save rename presets |

Pro is a one-time purchase. No subscriptions. No recurring charges. Buy it once, it's yours.

---

## Privacy

This app makes zero network requests. It doesn't collect anything. It doesn't know who you are. Your files stay on your device, period.

---

## From the Dev

I built this because I was tired of renaming screenshots one at a time on my phone. It started as a weekend script and turned into something I actually use every week. If it saves you even 5 minutes of mindless tapping, it was worth building.

With ❤️ from Kashmir, INDIA  
Follow on GitHub: [afaan13](https://github.com/afaan13)
