🎼 FretStep2

https://santismo.github.io/FretStep/

Desktop Chrome/MIDI page:

https://santismo.github.io/FretStep/desktop.html

FretStep2 is a mobile-first MIDI composition tool designed for guitar-oriented step input workflows, chord discovery, and internal Web Audio playback.

Instead of entering notes from a piano keyboard, notes are entered from a virtual 6-string guitar fretboard laid out in standard tuning. Each string automatically maps to its own MIDI channel, making it easy to preserve string information while composing.

FretStep2 runs entirely in a single HTML file and is optimized for iPhone home-screen web app use.

⸻

Features

Guitar Fretboard MIDI Input

* 6-string standard tuning layout
* 13 fret positions
* Low E string on bottom
* High E string on top
* Step-input MIDI workflow
* Record arm button to prevent accidental note entry
* Chord mode for entering stacked notes without advancing the cursor
* Octave transpose controls
* Semitone transpose mode while chord mode is active

⸻

Piano Roll Editor

* Full MIDI piano roll
* Range from C-1 to C8
* Horizontal zoom
* Vertical zoom
* Auto-follow playback mode
* Centered playhead scrolling
* View All Notes function
* View individual tracks or all tracks together
* Multi-note box selection
* Multi-note transpose
* Multi-note duration editing
* Step-based note movement

⸻

Chord Detection

FretStep automatically analyzes simultaneous notes and generates chord regions.

Supported chord types include:

* Major
* Minor
* Diminished
* Augmented
* Suspended
* Power chords
* Major 7
* Minor 7
* Dominant 7
* Add9
* 6
* Minor 6
* Various extended voicings

The current chord under the playhead is displayed directly on the fretboard.

Single notes are ignored and do not create chord regions.

⸻

Playback Engine

Hybrid Web Audio Playback

FretStep2 uses built-in procedural engines for instant reliable playback, plus optional sampled instruments that load on demand and cache in the browser.

Features:

* Searchable sound menu
* Bank chips for quick instrument browsing
* Multi-select filters such as Drums + Synth
* Random sound selection constrained by search, filters, and bank
* Acoustic-style banks for piano, guitar, bass, strings, horns, and drums
* Synth, chiptune, 16-bit, analog, retro drum, and sound-effect banks
* Sample-backed RealKey, RealGM, VCSL, and sampled drum-machine banks
* Splendid Grand Piano, VCSL pianos/harps/mallets/winds, FluidR3 GM guitars/strings/horns, and sampled TR/Casio/Linn/Oberheim/Korg/Yamaha/Simmons/Boss-style drum kits
* Drum-kit pad mapping for sampled drum machines where the source exposes kick, snare, hats, toms, cymbals, and percussion groups
* Phone-safe piano loading that limits the heaviest piano libraries on small touch devices
* Internal fallback sounds if a sampled instrument cannot load
* Per-track live effects including filters, reverb, delay, chorus, drive, crush, phaser, air, and tremolo

⸻

MIDI Features

* MIDI export
* Web MIDI input on the desktop Chrome page
* Multi-track sequencing
* Per-string MIDI channels
* Track colors
* Track volume control
* Tempo control
* Time signature support
* Loop playback

⸻

Loop System

Loop regions can be configured with:

* Start bar
* End bar
* Enable / Disable toggle

Playback automatically loops between selected bars.

⸻

Track System

Each track contains:

* Independent MIDI notes
* Instrument assignment
* Volume control
* Track color
* Mute-ready architecture

Tracks can be:

* Added
* Deleted
* Selected for input
* Viewed individually
* Viewed simultaneously

⸻

Undo / Redo

Full editing history includes:

* Note entry
* Deletion
* Transposition
* Duration edits
* Track edits

⸻

Project Management

Local browser storage support:

Save Project

Save unlimited local projects.

Load Project

Load previously saved projects.

Rename Project

Rename existing saved projects.

New Project

Creates a blank project and prompts to save current work.

⸻

Themes

Includes numerous built-in themes:

* Dark themes
* Light themes
* Colorful themes
* Monochrome themes
* Neon themes
* OLED themes

A Random Theme button can instantly generate new color combinations.

Theme colors affect:

* UI
* Piano roll
* Menus
* Fretboard
* Sliders
* Controls

⸻

Mobile Optimizations

Designed specifically for iPhone use.

Features:

* Home-screen web app support
* Touch-first workflow
* Large fretboard buttons
* Compact transport controls
* Mobile-friendly menus
* Auto audio initialization
* Optimized landscape-free portrait workflow

⸻

Controls

Transport

▶ Play / Stop

◀ Step Left

▶ Step Right

Div -

Div +

Undo

Redo

Loop

View

Chord

Oct -

Oct +

⸻

Chord Mode

When enabled:

* Clicking empty piano roll space does not deselect notes
* Playhead movement is disabled
* Easier multi-note editing
* Semitone transpose mode available through View button

⸻

Settings Menu

Contains:

* Save Project
* Load Project
* Export MIDI
* Import Project
* Show / Hide Fretboard
* Theme Selection
* Internal sound browser
* Track FX controls

Long-pressing the gear icon toggles fretboard visibility.
