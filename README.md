# WYRDKEEP

**A desktop novel-writing studio.** Plan your story on a visual storyboard, write it in a full editor, and see it laid out like the pages of a real book. Everything is stored on your own computer.

## Download

Go to the **[Releases](../../releases/latest)** page and download the file for your computer:

| Your computer | Download |
|---|---|
| Windows 10 / 11 | the **setup `.exe`** |
| Mac | the **`.dmg`** |

## Install

### Windows
1. Download the setup `.exe` and double-click it.
2. If you see **"Windows protected your PC"**, click **More info**, then **Run anyway**. This appears because the app is not code-signed yet.
3. Follow the installer. WYRDKEEP then appears in your Start menu.

### Mac
1. Download the `.dmg`, open it and drag **WYRDKEEP** into **Applications**.
2. The first time, macOS may say it is from an unidentified developer, because the app is not signed or notarised. **Right-click (or Control-click) the app, choose Open, then Open again.**
3. The Mac version is new and has had less testing than the Windows one. If something does not work, please tell me.

## What it does

- **Storyboard.** A canvas of cards for scenes, chapters, characters, locations, plot events, notes, timeline events and plot threads. Connect them with arrows such as "Happens before" or "Foreshadows", and filter or rearrange them.
- **Writing.** A manuscript tree (book, acts, chapters, scenes), a rich-text editor, find and replace, focus mode, autosave and revision history.
- **Manuscript.** Your whole book as pages, with trim sizes, margins, two-page spreads, chapter headings in the fonts you choose, drop caps, scene-break marks (including your own picture), page numbers and print or PDF.
- **Fonts.** Built-in book and blackletter fonts, and you can add your own font files.
- **Reference.** Characters, locations, canon facts, plot threads and a timeline.
- **Proofreading and continuity checks.** Built-in checks, optional LanguageTool, and checks for things like a character appearing after they died.
- **Export.** Word (`.docx`), EPUB, Markdown and plain text.
- **Optional AI help.** Brainstorming, continuing a scene, rewriting and more, using a model on your own computer (such as Ollama or LM Studio) or an online service. Nothing changes your manuscript until you accept it.
![Storyboard](screenshots/storyboard.jpg)
## Your writing stays with you

- Your projects are saved on your own computer. The app makes no network requests by itself.
- AI is **off for online services by default**. Nothing is sent anywhere unless you add an online AI provider **and** switch on *Settings → Privacy → Allow project content to be sent to online AI services*.
- API keys for online AI are kept in the system's credential store (Windows Credential Manager or macOS Keychain), never in your project files.
- The app makes automatic backups while you work. You can also make one from **Settings → Library backups**.
  
![Writing view](screenshots/writing.jpg)
![Manuscript pages](screenshots/Manuscript.jpg)

## Getting started

1. Open WYRDKEEP and click **New project**.
2. Use the **Storyboard** tab to plan, or go straight to **Writing** and add a chapter and a scene.
3. Open the **Manuscript** tab to see the book as pages. The **Chapter style & pages** menu controls chapter headings, drop caps, scene breaks and page numbers.
4. Export from **File → Export manuscript** when you want a Word, EPUB or text copy.
5. Optional: add an AI provider in **Settings → AI providers**.

## Known limits

- The page view is a close preview on screen, not an exact print layout. Line and page breaks can differ slightly in other programs.
- Chapter styling, drop caps and fonts are not carried into the Word and EPUB exports, and fonts are not embedded in them.
- The one-click LanguageTool download installs Java automatically on Windows only. On a Mac, install Java 17 or newer first.
- The app is not code-signed, so Windows and macOS show a warning the first time you run it.

## Questions or problems

Open an **Issue** on this page and describe what happened, or contact the author directly.
