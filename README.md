# Step.

> Efficient way to take piano notes instead of writing manually/recording video when you're improvising / learning a music by ear.

**[Try it online here →](https://phantomcoderhaha.github.io/PiaNoteTakingApp/)**

---

## Why I built this

I was trying to learn Isabella's Lullaby on [YouTube](https://www.youtube.com/watch?v=-b8_89vlkaI) by ear (without music sheet), but I keep forgetting a section in the songs. 

Unlike music sheet - you can't just lookup the notes you forgot. 

Which means, I need to take notes of what I'm playing.

### Here is my options: 
1. Manual notetaking with paper & pencil:
  - Pros: You can write notes your own way instead of being forced into the software's method.
  - Cons: Takes too long + can lose your paper if not kept properly.
2. Video recording of practicing piano:
  - Pros: Easy to do, just setup your phone in a place with good lighting with a sideway/top-view of the piano and press record
  - Cons: Need to leave the seat every time you want to start/stop recording + need to squint your eyes when you're trying to look for a specific notes you forget.
3. Professional music composition software:
  - Pros: Robust features. If you're already proficient in using the software, this is probably the fastest way.
  - Cons: Overkill when you just want to improvise something + don't want to look at music notation + can't be bothered learning all of that. 
4. AI audio analysis:
  - Pros: Just send your audio/video recording and it'll analyse the notes for you.
  - Cons: It's paid (I can't afford it) + can be [innacurate for lower octave notes](https://www.sciencedirect.com/science/article/pii/S1110866525001392#s0090)

### So I made this app to: 
1. Make music note-taking more effecient while also preserving the intuitiveness/flexibility of taking notes by writing manually.
2. Avoid paying for professional music composition software/AI audio analysis. 

---

## Who is it mainly for

I mainly build this for people who are trying to learn to play piano by ear as that's what I'm currently learning. 

---

## How to use (AI generated)

### 0. Access the app
- Access it online using this [link](https://phantomcoderhaha.github.io/PiaNoteTakingApp/)
- Offline computer access = download the file from this repository or from the webapp
- Offline mobile access = download the file from this repository -> transfer the file to your phone -> download an html reader -> access the app from the html reader. (downloading the html file directly from mobile webapp doesn't work, it just produces a static page).

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
In the **Versions** panel, tap **+ version** to create a new empty version of a section, or long-press an existing version pill to copy it. Each version has its own independent note sequence — useful for trying a different melody over the same structure.

### 7. Save your work
Your songs save automatically to your browser. To back up or move to another device, tap **Export session** on the gallery screen to download a `.json` file. Use **Import session** to restore it. You can also use this to export between devices (since I didn't make a server to host user data - all of this is hosted in github pages).

---

## Keyboard shortcuts (AI generated)

| Key | Action |
|-----|--------|
| `Space` / `Enter` | Hold to play, release to advance |
| `Backspace` | Delete active note |
| `Ctrl+Z` | Undo |
| `Ctrl+Shift+Z` | Redo |
| `Ctrl+C` | Copy selected notes |
| `Ctrl+V` | Paste |
