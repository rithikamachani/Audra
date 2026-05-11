# audra — music you can feel

> A music accessibility tool that translates sound into visual experiences for hearing-impaired listeners.

🔗 **[Live Demo →](https://rithikamachani.github.io/Audra)**

---

## Why Audra exists

Most music apps are built for people who can hear everything.

Hearing aids filter out specific frequency ranges — the shimmer of a cymbal, the brightness of a voice, the warmth of a high melody. Those frequencies don't reach the listener. The music is still playing, but something essential is missing.

Audra was built to fill that gap. Not by fixing the audio — but by creating a parallel visual channel that carries everything the sound carries. Rhythm. Emotion. Structure. The feeling of a chorus building toward something.

It started with one person who loves music. It was built for everyone who does.

---

## What it does

| Feature | What it is |
|---|---|
| 🌊 **Frequency landscape** | Real-time waveform that breathes with the music — the invisible texture of sound, made visible |
| 🎨 **Emotion map** | Translates a song's mood into color and shape — calm, nostalgic, energetic, tender |
| 💬 **Animated lyrics** | Words move with the weight and pitch of how they're sung — a whisper fades in softly, a belted note bursts large |
| 🔲 **Rhythm grid** | Bass, mid, high, treble mapped to a visual pulse grid — the skeleton of the beat |
| 🎛 **Hearing profile** | Frequency sliders tuned to your hearing aid's profile — amplify visually what your device filters out |

---

## Demo

> Load any audio file → press play → all five visual layers activate simultaneously

- **Now Playing tab** — waveform + rhythm grid react to live audio in real time
- **Emotion tab** — select a mood or play a song to generate its color fingerprint
- **Profile tab** — tune frequency boost sliders, toggle each visual layer on/off
- **About tab** — the story behind why Audra was built

---

## Accessibility

Audra is built to the **WCAG 2.1 AA standard** throughout:

- All interactive elements are keyboard accessible
- Color contrast meets AA requirements in both dark and light mode
- Font scaling supported via Large Text toggle
- Reduce Motion toggle for users sensitive to animation
- No data collected — hearing profiles stored locally on your device only

---

## Tech stack

```
HTML / CSS / JavaScript       — core structure and styling
Web Audio API                 — real-time audio capture and frequency analysis
Canvas API                    — waveform and emotion map rendering
FFT (Fast Fourier Transform)  — frequency band decomposition
Beat detection                — rhythm grid synchronization
localStorage                  — hearing profile persistence
DM Sans + DM Mono             — accessible, legible typography
```

---

## How to run it locally

No install needed. Just open the file.

```bash
# Clone the repo
git clone https://github.com/rithikamachani/Audra.git

# Open in your browser
open index.html
```

Or visit the live version directly: **[rithikamachani.github.io/Audra](https://rithikamachani.github.io/Audra)**

> Works best in Chrome or Edge. Microphone input requires browser permission.

---

## Project status

This is **Phase 1** of a larger roadmap.

| Phase | Status | Description |
|---|---|---|
| 1 — Web app | ✅ Live | Audio engine, visualizer, lyrics, rhythm grid, profiles, about page |
| 2 — Full features | 🔨 In progress | Real synced lyrics, Spotify search, visual sheet music |
| 3 — React Native | 📋 Planned | Mobile app — iOS + Android from one codebase |
| 4 — Native build | 📋 Planned | Haptics, full Spotify SDK, cloud profile sync |
| 5 — App Store | 📋 Planned | iOS + Android public launch |

---

## Built by

**Rithika Machani** — UX/UI designer and developer with a focus on accessible technology.

This project grew out of a Harvard CS560 accessibility project, research into the frequency gaps between hearing aids and standard music apps, and a personal drive to build technology that meets people where they are — not where it's convenient to design for.

---

## License

MIT — open source and free to use.
