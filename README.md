# type_wrtr

A private journal that feels like a typewriter. It runs in your browser from a single HTML file, works offline, and saves your writing as plain Markdown files in a folder you choose. Pick a folder inside your Proton Drive (or any synced folder) and it syncs the way your other files do.

Nothing is sent anywhere. There is no account, no server, no tracking and no network access at all. Your entries never leave your computer except through the sync app you already use.

<img width="1156" height="451" alt="image" src="https://github.com/user-attachments/assets/b5104647-6024-479f-b4c0-36038221ed29" />

## Get started

1. Download `type_wrtr.html` from the [latest release](../../releases/latest).
2. Open it in **Chrome, Edge or Brave** (double-click the file, or drag it into the browser).
3. Click **Choose journal folder** and pick a folder, for example one inside your Proton Drive.
4. Start typing. Everything autosaves.

The next time you open it, click **Reopen** to go straight back to your folder.

You can also use it without downloading: Open the project's page [here](https://nwdthomas.github.io/type_wrtr/) or go to https://nwdthomas.github.io/type_wrtr/. The app still runs entirely on your own computer.

## Features

- **Daily entries.** One Markdown file per day, named like `2026-10-04.md`. Jump to today or pick any date from the calendar.
- **Notes.** Free-form notes that are not tied to a date, saved in a `Notes` folder.
- **Tags.** Write `#ideas` or `#travel` anywhere in your text. The Tags tab lists every tag, and clicking one shows the entries and notes that use it.
- **Search** across all of your entries and notes.
- **Bold.** Select text and press Cmd/Ctrl+B to wrap it in `**double asterisks**`. It shows in bold as you write, and it stays plain Markdown in the file.
- **Typewriter sounds.** Optional key clicks, a space bar thunk, backspace, a carriage return and a bell. Turn the whole thing or each sound on or off in Settings.
- **Focus mode.** Hides everything except the page. Press Esc to leave.
- **Light and dark themes**, and a setting to put the sidebar on either side.
- **Autosave**, plus Cmd/Ctrl+S to save right now.

## Your files

Entries are normal text files, so you are never locked in.

```
your-folder/
  2026-10-03.md
  2026-10-04.md
  Notes/
    Trip ideas.md
```

You can open, edit, back up or move them with any app that reads text or Markdown.

## Browser support

The app uses the File System Access API to read and write your folder directly.

| Works | Does not work |
| --- | --- |
| Chrome, Edge, Brave and other Chromium browsers on Mac, Windows, Linux and ChromeOS | Safari, Firefox, and any browser on iPhone or iPad |

On unsupported browsers the app tells you instead of failing quietly.

## Privacy

- The page has a strict content security policy that blocks all network requests, so it cannot send data anywhere even by accident.
- Your folder choice is remembered in the browser's own storage on your device. Settings such as theme and sound are kept the same way.
- Spell check uses your browser's built-in checker, which depends on your browser's settings.

## Build and edit

There is no build step. The whole app, including the font, is one file: `type_wrtr.html`. Open it in a text editor to change anything.

## License and credits

- The type_wrtr code is released under the [MIT License](LICENSE).
- The embedded font is [Courier Prime](https://fonts.google.com/specimen/Courier+Prime), copyright 2015 The Courier Prime Project Authors, used under the [SIL Open Font License 1.1](OFL.txt).
