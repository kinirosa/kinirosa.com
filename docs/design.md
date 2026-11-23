# Design

## The idea

Two console eras in one screen: the **layout and interactions of a modern console home menu** (a row of app tiles, a full-screen backdrop that follows your selection, a Control Center that rises from the bottom), rendered with the **mood of an early-2000s bedroom CRT** at 2 AM: deep navy, phosphor cyan, soft bloom, a little grain and a dusty spotlight.

The goal was a portfolio that's memorable in the first five seconds, but still lets a recruiter find what they need in twenty.

## Layout

- **Home** keeps tiles in a fixed slot, like a console: the row slides under a steady highlight instead of the highlight running across the row.
- **The backdrop is the app.** Selecting a project, GitHub or LinkedIn fills the screen with that app's logo and colour.
- **Hints at the bottom** show the controls for the current screen, switching between keyboard keys and controller buttons depending on what the visitor last used.
- **Every screen scrolls and reflows**, from ultrawide monitors to phones. On a phone the Control Center becomes a grid and the dock wraps so everything stays tappable.

## The CRT look

| Layer | What it adds |
|---|---|
| Bloom | A soft glow around bright text and focused items |
| Film grain | A fine moving noise over the whole screen |
| Vignette | Darkened, slightly curved-looking edges |
| Spotlight and dust | A beam of light with drifting particles on system screens |
| Scanlines | Optional horizontal lines (off by default) |

Each layer is separate and can be switched off in Settings. Lower-powered devices automatically get a lighter version.

## Motion

Movement is quick and purposeful: tiles slide, panels rise, backdrops cross-fade. Every animation has a reduced-motion version (short fades instead of slides), used automatically when the visitor's system asks for less motion or when they turn it on in Settings.

## Sound

Interface sounds are short and soft (a tick for moving, a chime for selecting, a lower tone for back), synthesized live and quiet by default. Three procedural music tracks play only when the visitor chooses one, from the music button on Home, the Control Center or Settings.

## Originality

The look is inspired by console interfaces, but everything on screen is original: the emblem, the glyphs for controller buttons, the generated artwork, the fonts' pairing and every sound. No console maker's logos, fonts, sounds or animations are used.
