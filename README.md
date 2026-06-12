# FretStep

https://santismo.github.io/FretStep/

🎶 FretStep

FretStep is a touch-first MIDI composition tool designed for iPhone and other mobile devices.

Instead of entering notes with a traditional piano keyboard, FretStep uses a virtual 6-string guitar fretboard as a MIDI input surface. Notes are entered directly into a piano roll using step input, making it easy to compose melodies, chords, bass lines, and arrangements entirely from a phone.

The project is implemented as a single-file web application and can be hosted on GitHub Pages, added to an iPhone Home Screen, and used like a lightweight standalone music workstation.

⸻

Features

Guitar Fretboard MIDI Input

* 6-string fretboard layout
* Standard guitar tuning
* 13 fret input surface
* Low E string on bottom
* High E string on top
* Touch pads for fast note entry
* Fretboard note monitoring even when recording is disabled
* Fret markers at:
    * 3rd fret
    * 5th fret
    * 7th fret
    * 9th fret
    * 12th fret

⸻

Piano Roll Editor

* Multi-track piano roll
* Touch scrolling
* Pinch horizontal zoom
* Vertical zoom strip
* Automatic playhead following
* Centered playback scrolling
* Piano roll note editing
* Multi-note selection
* Box selection
* Timeline navigation
* Bar numbering
* Time signature support

Supported ranges:

* C-1 through C8

⸻

Step Recording

FretStep is primarily designed around step input.

Features include:

* Quantized note entry
* Configurable subdivisions
* Step forward
* Step backward
* Chord entry mode
* Playback auditioning

Supported subdivision values include:

* Quarter notes
* Triplets
* Eighth notes
* Sixteenth notes
* Thirty-seconds
* Very fine grid resolutions

Changing subdivision only affects newly entered notes.

⸻

Chord Mode

Chord Mode allows multiple notes to be entered at the same timeline position.

When enabled:

* Notes do not automatically advance the playhead
* Multiple notes can be stacked into chords
* Existing selections are preserved
* Selection workflows are optimized for editing multiple chords

⸻

Chord Detection

FretStep automatically analyzes notes and detects chord names.

Features include:

* Chord region generation
* Chord lane display
* Current chord display on fretboard
* Extended chord recognition
* Chord updates during editing

Examples:

* Major
* Minor
* Seventh
* Major Seventh
* Minor Seventh
* Suspended
* Diminished
* Augmented
* Extended voicings

⸻

Multi-Track Workflow

Create arrangements using multiple independent MIDI tracks.

Each track includes:

* Independent MIDI notes
* Independent sound assignment
* Independent volume control
* Individual track color
* Piano roll visualization

Track menu includes:

* Add Track
* Delete Track
* Select Active Input Track
* View All Tracks
* Track Volume Slider
* Track Volume Numeric Input

View All mode displays all tracks simultaneously while still allowing a single active track for note input.

⸻

Sound Engine

SoundFont Playback

Supports SoundFont-based playback using:

Roland SC-55 SoundFont

Features:

* Multiple instrument presets
* General MIDI style workflow
* Track-based instrument assignment
* SoundFont preset browser

Internal Synth Engine

Optional built-in synth engine includes:

* Piano
* Electric Piano
* Organ
* Bell
* Guitar
* Bass
* Strings
* Brass
* Reed
* Flute
* Pad
* Pulse
* Triangle
* Square
* Sawtooth
* Sine

⸻

Mixer

Per-track volume controls:

* Slider adjustment
* Numeric volume entry
* Independent track balancing

⸻

Playback

Playback system includes:

* Play / Stop
* Loop playback
* Auto-scroll
* Center-follow playhead
* Quantized timing
* Metronome support

⸻

Metronome

Built-in metronome supports:

* On / Off toggle
* Time signature aware accents
* Quantized recording assistance

⸻

Loop Regions

Loop playback can be configured using:

* Start bar
* End bar
* Enable / Disable loop

Playback automatically repeats within the selected range.

⸻

MIDI Editing

Selected notes can be:

* Deleted
* Moved
* Transposed
* Octave shifted
* Semitone shifted
* Lengthened
* Shortened

Supports:

* Single note editing
* Multi-note editing
* Multi-chord editing

⸻

Undo / Redo

History system includes:

* Undo
* Redo
* Non-destructive editing workflow

⸻

Project Management

Local browser-based project storage.

Features:

* Save Project
* Load Project
* Rename Project
* Delete Project
* Multiple Local Projects
* New Project Workflow

Projects retain:

* Tracks
* Notes
* Sounds
* Colors
* Chords
* Loop settings
* Tempo
* Time signature

⸻

Export

MIDI Export

Export compositions as standard MIDI files.

Export preserves:

* Track data
* MIDI notes
* Timing
* Channels

Each guitar string is exported on its own MIDI channel:

* String 1 = Channel 1
* String 2 = Channel 2
* String 3 = Channel 3
* String 4 = Channel 4
* String 5 = Channel 5
* String 6 = Channel 6

⸻

Themes

FretStep includes a large theme system.

Features:

* Dark themes
* Light themes
* Colorful themes
* Monochrome themes
* Random theme generator
* Random monochrome generator

Theme changes are immediate and intended for experimentation.

⸻

Mobile First Design

Designed specifically for:

* iPhone
* Touch screens
* Home Screen web apps
* GitHub Pages hosting

Supports:

* Safari
* Chrome
* Mobile browsers
* Standalone Home Screen mode

⸻

Typical Workflow

1. Create or load a project.
2. Select a track.
3. Choose an instrument.
4. Set tempo and subdivision.
5. Enter notes using the fretboard.
6. Use Chord Mode for stacked chords.
7. Arrange multiple tracks.
8. Adjust track volumes.
9. Add loop regions.
10. Preview playback.
11. Export MIDI.

⸻

Philosophy

FretStep is intended to be a fast idea-capture tool.

The goal is to make MIDI composition feel as immediate as playing on a guitar fretboard while still providing a full piano-roll editing environment.

It is optimized for songwriting, arranging, sketching musical ideas, creating MIDI files, and composing directly from a phone without requiring a traditional desktop DAW.