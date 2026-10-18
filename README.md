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

## Your projects
- **＋ New Project** starts a blank game or a copy of a demo. Projects save automatically in the browser you're using.
- Saves stay in that browser on that device. To move a game to another device or keep a backup, use **☰ → Export project file**, then **☰ → Import project file** on the other device. The `.game.json` file includes your uploaded images, sounds and fonts.
- Clearing the browser's site data deletes saved projects. Export anything you care about.

## Features
- Editor with line numbers, syntax colors, and live error checking with "did you mean" hints
- 🎨 Assets panel: object library, sound designer, UI themes, dialogue boxes
- 📁 Upload your own images (sprites, backgrounds), sounds (effects, music) and fonts
- Speech bubbles, NPCs, dialogue boxes, 8-bit sound effects, 4 demo games

The **Language Reference** tab under the editor lists every command.
