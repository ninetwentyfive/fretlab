# Fretlab: A Guitar Practice Tool Suite 🎸

A collection of practice tools made during my guitar learning journey.

[https://ninetwentyfive.github.io/fretlab/](https://ninetwentyfive.github.io/fretlab/)

---

## Tools Included

### 1. Sight Reading Generator
A random single-line melody generator that creates 4-bar phrases within specific fretboard constraints.

**Key Features:**
* **Random Note Generation:** Uses a scale-based next-note logic (C major/A minor pentatonic). Currently excludes sharps and flats for simplicity.
* **Configurable Range:** Supports contraints for specific strings and a fret range (up to 24 frets).
* **Rhythmic Patterns:** Supports quarter notes, eighth notes, and rests via weighted randomisation.
* **Cadence logic:** Generates a 2-beat cadence at the end of the phrase. Currently limited to perfect and plagal cadences (V-I, IV-I) as a design preference.
* **Audio Playback:** Plays the generated melody using Tone.js. Includes a tempo slider.
* **Vextab Editor:** Supports edits through a text-based editor.
* **Time signature toggle:** Toggle time signature display for bar-line alignment.
* **Mobile-Friendly:** Tried to make the CSS work smoothly on phones and tablets.

### 2. Rhythmic Recall
An ear-training tool that generates and plays random 2-bar rhythmic patterns on low E (E2).

**Key Features:**
* **Pattern Selection:** Can toggle specific rhythmic patterns on or off.
* **Adjustable Tempo:** Includes a tempo slider.
* **Editable Output:** Directly modify the rhythm by clicking/tapping on the score.
* **Mobile-Friendly:** Tried to make the CSS work smoothly on phones and tablets.

---

## Built With

* **Notation Engine:** [VexTab](https://www.vexflow.com/vextab/)
* **Audio Engine:** [Tone.js](https://tonejs.github.io/)
* **Vibe Coding:** [Google Gemini](https://gemini.google.com)
