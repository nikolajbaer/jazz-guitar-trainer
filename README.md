# Jazz Guitar Woodshed

A single-page, mobile-first practice tool for jazz guitar. No build step and no dependencies: open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works).

## What it does

- **Changes**: blues forms (basic, jazz, Bird, minor), major and minor ii–V–I, a turnaround, rhythm changes, Autumn Leaves changes, an A Train A section and a modal form, in any key.
- **Backing track**: a swing trio synthesised with the Web Audio API (piano comping, walking bass, ride and hi-hat) with tempo control and per-instrument mutes.
- **Scales**: suggestions for the chord being played; tap one for a fretboard chart with fingerings that can be moved along the neck.
- **Fingerings**: movable chord shapes with finger numbers.
- **Subs**: chord substitutions with a short explanation; applying one updates the chart and the backing track.
- **Next chord**: guide-tone voice leading, the closest pair of shapes and connecting chords.
- **Licks**: licks in tab for the selected chord or the change it belongs to, with playback.

Everything lives in `index.html`: theory tables, chord shapes, licks and progressions are plain data near the top of the script.
