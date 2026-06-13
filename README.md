# MusicEd Composer

## Mission

Help students understand the relationship between piano-roll composition and standard notation.

Core educational outcome:

> "That square became that note."

MusicEd Composer is a visual composition tool that bridges grid-based music making, playback, and traditional notation.

## Version 1 Goals

### Composer Grid

- 8 measures
- 4/4 time
- 64 eighth-note positions
- Diatonic pitch range from Middle C to C5
- Touch-friendly input for tablets and smartboards
- Melody mode and harmony mode

### Playback

- Play
- Stop
- Loop
- Tempo control

### Sounds

Initial sound set:

- Piano
- Bass
- Bell
- Synth
- Drum
- Weird/Fun
- Sine
- Triangle
- Saw
- Square

### Notation

- Real-time staff display
- Treble clef
- Correct staff placement
- Automatic rhythm grouping
- Automatic rests
- Clear connection between grid actions and notation results

### Harmony

Future harmony features:

- Chord detection
- Music Nerd popup
- Beginner, intermediate, and advanced analysis levels
- Roman numerals
- Jazz chord labels
- Figured bass
- Dissonance/tension descriptions

## Visual Design

The visual identity should feel like:

- manuscript paper
- music classroom
- method book
- modern web app
- serious enough for musicians
- simple enough for beginners

### Palette

| Purpose | Color |
|---|---|
| Background | `#F2F2F0` |
| Panels | `#FFFFFF` |
| Text | `#1C1C1C` |
| Primary accent / notes | `#B23A2B` |
| Playback cursor / highlight | `#D4A017` |
| Success / correct / completed | `#2E8B57` |
| Measure lines | `#999999` |
| Staff and notation | `#000000` |

### Design Principle

Grid notes may appear in red, but standard notation should remain black on a white staff.

This reinforces the learning objective:

> The red square became the black note.

## Educational Principle

Every action in the grid should immediately translate into notation.

Students should be able to:

1. Click or tap a square.
2. Hear the sound.
3. See the notation.
4. Understand the connection.

The software should teach notation through composition, not require notation before composition.

## Planned Feature Roadmap

### Stage 1

- Clickable grid
- Playback
- Looping
- Basic staff translation

### Stage 2

- Rhythm grouping
- Rests
- Cleaner notation display

### Stage 3

- Diatonic/chromatic toggle
- Improved instruments
- MIDI export

### Stage 4

- Harmony mode improvements
- Chord detection
- Music Nerd popup

### Stage 5

- Teacher mode
- Assignment templates
- Beginner note sets
- Recorder mode
- Beginning band mode

## Product Positioning

MusicEd Composer is not intended to replace GarageBand, MuseScore, Flat.io, or Chrome Music Lab.

It lives between them.

Chrome Music Lab helps students explore sound.

MuseScore helps musicians create notation.

MusicEd Composer helps students understand how musical ideas become notation.

## Guiding Question

Every feature should be tested against this question:

> Does this help students understand how musical ideas become notation?

If yes, it belongs.

If no, it may belong in a later version or a different product.
