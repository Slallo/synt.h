# SYNT.H

A punctuation synthesizer. Each glyph is a voice. Each voice is an instrument. No libraries. No dependencies. One HTML file.

## The Instrument

Ten punctuation glyphs, ten unique sounds built with the Web Audio API:

| Key | Glyph | Name | Sound |
|-----|-------|------|-------|
| 1 | `.` | ping | Sine drop 1200→800Hz |
| 2 | `,` | nota | Plucked string, A4 harmonics |
| 3 | `;` | totem | Am chord, 2s sustain |
| 4 | `:` | ponte | Double tap, square wave |
| 5 | `?` | domanda | Rising tone, unresolved |
| 6 | `()` | abbraccio | Mirrored tones meeting at center |
| 7 | `&` | intreccio | Three weaving voices |
| 8 | `!` | colpo | Noise burst + bass punch |
| 9 | `\` | caduta | Falling sawtooth + echo |
| 0 | `~` | onda | Vibrato sine, 6Hz LFO |

## The Language

SYNT.H has its own vocabulary:

- **!A** — NOTA — a single glyph, once
- **!E** — NOTE — multiple glyphs together
- **!I** — ECO — hold a glyph, it loops
- **!O** — LEGATO — hold multiple glyphs, they blend
- **!U** — ???

## How to Play

**Click** a glyph to trigger it. **Hold** to loop. **Hold multiple** to layer.

Each glyph has its own **rate slider** — hover to reveal. Set independent tempos: a fast `.` pulsing at 50ms while `~` waves at 800ms.

**Keyboard**: keys `1-9` and `0` map to each glyph. Hold for sustain. Hold multiple for legato.

## Features

- **Pure synthesis** — Web Audio API oscillators, no samples
- **Color-coded waveform** — real-time oscilloscope blends colors when notes overlap
- **Per-glyph rate control** — independent loop tempo for each voice
- **Zero dependencies** — one HTML file, no npm, no build step
- **Live legend** — displays current play state with blended color indicator

## Run

Open `synth.html` in any modern browser. That's it.

## Origin

Born from a study of punctuation reflections — glyphs mirrored vertically reveal hidden forms: a comma becomes a musical note, a question mark becomes a 3, parentheses become a human silhouette. From observation to instrument.

## License

MIT

---

*Fra Lupo*
