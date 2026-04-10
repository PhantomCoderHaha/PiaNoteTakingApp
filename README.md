# Step.

> Efficient way to take piano notes instead of writing manually/recording video when you're improvising / learning a music by ear.

**[Try it here →](https://phantomcoderhaha.github.io/PiaNoteTakingApp/)**

---

## Why I built this

<!-- Your words here -->

---

## Who is it for

<!-- Your words here -->

---

## How to use

### 1. Create a song

### 1. Create a song
Tap **+ New Song** on the gallery screen. Give it a title, an optional description, and a to-do list for things you want to work on in that session.

### 2. Add sections
Inside your song, type a section name (e.g. `Verse`, `Chorus`) and tap **+ Add**. Tap a section card to open it. You can drag sections to reorder them, or tap ⎘ to duplicate one.

### 3. Capture notes
Scroll to the **Note Input** panel. Set your key and scale to get a visual guide on the piano, then play:

**Mobile (touch)**

| Gesture | Result |
|---------|--------|
| Tap a key | Single note |
| Hold one key, tap a second finger | Chord |
| Hold 500ms + slide | Arpeggio |
| Slide immediately | Scale run |

**Desktop (mouse)**

| Gesture | Result |
|---------|--------|
| Click a key | Single note |
| Click while holding `Shift` | Chord |
| Click + hold 500ms + drag | Arpeggio |
| Click + drag immediately | Scale run |

You can also tap **+ custom chord** to build a chord by tapping any combination of keys manually.

### 4. Play it back
Hold the large circular **play button** to sound the current note. Release to advance to the next. It loops — keep holding and releasing to hear your melody play through.

### 5. Edit your notes
In the **Note Editor**, tap a note cell to set the cursor. Hold and drag a cell to reorder it. Use the toolbar to undo (↩), redo (↪), or delete (⌫). Tap ⊡ to enter select mode — tap cells to select them, then copy, paste, or delete as a batch.

### 6. Try variations
In the **Versions** panel, tap **+ v** to create a new empty version of a section, or long-press an existing version pill to copy it. Each version has its own independent note sequence — useful for trying a different melody over the same structure.

### 7. Save your work
Your songs save automatically to your browser. To back up or move to another device, tap **Export session** on the gallery screen to download a `.json` file. Use **Import session** to restore it. You can also use this to export between devices (since I didn't make a server to host user data - all of this is hosted in github pages).

---

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` / `Enter` | Hold to play, release to advance |
| `Backspace` | Delete active note |
| `Ctrl+Z` | Undo |
| `Ctrl+Shift+Z` | Redo |
| `Ctrl+C` | Copy selected notes |
| `Ctrl+V` | Paste |
