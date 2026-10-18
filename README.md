# Custom DSL Game Engine

Make 2D games in your browser with a tiny scripting language that reads like English game rules:

```text
ADD CHARACTER Hero
  COLOR cyan
  SPEED 4

ADD ITEM Gem
  COLOR lime
  COUNT 3

ON Hero TOUCH Gem:
  SCORE + 1
  Hero SAYS "Found one!"
```

Everything is in one `index.html`: the editor, the parser, the engine, and the sound synth. Nothing to install.

## Use it
- **Online:** open the GitHub Pages link for this repo. You can install it as an app from the browser's address bar (the ⊕ install icon), and it keeps working offline.
- **On your computer:** download this repo and open `index.html` in Edge or Chrome.

## Saving your projects (read this!)
- **＋ New Project** starts a blank game or a copy of a demo. Projects save automatically (the header shows **✓ Saved**), and the last one you had open reopens next time.
- **Projects are saved in the browser you're using, not on GitHub.** Hosting the site doesn't upload your games anywhere.
- **Each browser and device has its own saves.** On a new computer, your phone, or a different browser, the site opens fine but your projects aren't there.
- **The online version and the downloaded `index.html` don't share saves either.** Projects you made by opening the file on your computer won't appear on the website, and the other way round.
- **To move a game or keep a backup:** use **☰ → Export project file**. That downloads one `.game.json` file with the script and every uploaded image, sound and font inside. On the other device or browser, use **☰ → Import project file**, or drag the file onto the page.
- **Clearing the browser's site data or history for this site deletes its saved projects.** The engine asks the browser to keep them, but export anything you care about now and then.
- **Demos aren't saved.** Edit one freely, but to keep your changes use **☰ → Save as my project** (or **＋ New Project**). Uploading a file to a demo turns it into a project automatically.
- If the header says **⚠ Saving unavailable** (some private or locked-down browser modes), the engine still works but can't save. Export before closing the tab.

## Features
- Editor with line numbers, syntax colors, and live error checking with "did you mean" hints
- 🎨 Assets panel: object library, sound designer, UI themes, dialogue boxes
- 📁 Upload your own images (sprites, backgrounds), sounds (effects, music) and fonts
- Speech bubbles, NPCs, dialogue boxes, 8-bit sound effects, 4 demo games

The **Language Reference** tab under the editor lists every command.
