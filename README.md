# 🎵 Audra — *Music You Can Feel*

![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-1D9E75?style=flat-square) ![Phase](https://img.shields.io/badge/Phase-1_Complete-185FA5?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-534AB7?style=flat-square) ![HTML](https://img.shields.io/badge/Built_with-HTML_CSS_JS-D4537E?style=flat-square)

> *"Music communicates across every boundary — language, culture, age. Audra exists to make sure hearing is never another boundary it can't cross."*

🔗 **[Live Demo → rithikamachani.github.io/Audra](https://rithikamachani.github.io/Audra)**

---

## Why Audra exists

Most music apps are built for **people who can hear everything.**

Hearing aids filter out specific frequency ranges — the shimmer of a cymbal, the brightness of a voice, the warmth of a high melody. Those frequencies don't reach the listener. The music is still playing, but ***something essential is missing.***

Audra was built to fill that gap. Not by fixing the audio — but by creating a **parallel visual channel** that carries everything the sound carries:

- 🌊 **Rhythm**
- 🎨 **Emotion**
- 📐 **Structure**
- 💬 **The feeling of a chorus building toward something**

> It started with one person who loves music. It was built for everyone who does.

---

## ✨ Features

| Layer | What it does | Who it's for |
|---|---|---|
| 🌊 **Frequency landscape** | Real-time waveform that breathes with the music | Everyone — makes sound visible |
| 🎨 **Emotion map** | Translates mood into color and shape | Users who want to *feel* a song before hearing it |
| 💬 **Animated lyrics** | Words move with the weight of how they're sung | Hearing-impaired listeners following along |
| 🔲 **Rhythm grid** | Bass, mid, high, treble mapped to a visual pulse | Users who experience music through rhythm |
| 🎛 **Hearing profile** | Frequency sliders tuned to your hearing aid | Personalised to each listener's needs |
| ⚡ **Screen flash alerts** | Subtle full-screen pulse on beat drops | Users who feel music physically |

---

## 🚀 Getting started

**No install needed** — open it directly in your browser.

```bash
# Clone the repo
git clone https://github.com/rithikamachani/Audra.git

# Open in your browser
open index.html
```

> ⚠️ Works best in **Chrome or Edge**. Microphone input requires browser permission when prompted.

### How to use it

1. **Load a song** — click *"Load a song"* and choose any MP3 from your device
2. **Press play** — the waveform and rhythm grid activate immediately
3. **Switch tabs** — explore the Emotion map and tune your Hearing profile
4. **Toggle layers** — turn individual visual layers on or off in the Profile tab
5. **Save your profile** — frequency settings are remembered automatically between sessions

---

## ♿ Accessibility

Audra is built to the **WCAG 2.1 AA standard** throughout:

- [x] All interactive elements are **keyboard accessible**
- [x] Color contrast meets **AA requirements** in both dark and light mode
- [x] **Font scaling** supported via Large Text toggle in Profile
- [x] **Reduce Motion** toggle for users sensitive to animation
- [x] **Screen flash** toggle — can be disabled for photosensitive users
- [x] **No data collected** — hearing profiles stored locally on your device only
- [x] Designed for compatibility with **VoiceOver** and **TalkBack** screen readers

---

## 🛠 Tech stack

```
HTML / CSS / JavaScript       — core structure and styling
Web Audio API                 — real-time audio capture and frequency analysis
Canvas API                    — waveform and emotion map rendering
FFT (Fast Fourier Transform)  — frequency band decomposition
Beat detection                — rhythm grid synchronization
localStorage                  — hearing profile persistence across sessions
DM Sans + DM Mono             — accessible, legible typography
```

---

## 🗺 Roadmap

| Phase | Status | What's being built |
|---|---|---|
| **1 — Web app** | ✅ Complete | Audio engine, visualizer, lyrics, rhythm grid, profiles, splash, about page |
| **2 — Full features** | 🔨 In progress | Real synced lyrics, Spotify search, visual sheet music, multi-profile |
| **3 — React Native** | 📋 Planned | Mobile app — one codebase for iOS + Android |
| **4 — Native build** | 📋 Planned | Haptic feedback, Spotify SDK, cloud profile sync |
| **5 — App Store** | 📋 Planned | Public launch on iOS App Store + Google Play |
| **6 — Pitch & grow** | 📋 Planned | Grants, hackathons, accessibility community launch |

---

## 📁 Project structure

```
Audra/
├── index.html        — entire app (single file, Phase 1)
└── README.md         — you are here
```

> Phase 3+ will expand into a full React Native project structure with separate component files, screens, and an audio engine module.

---

## 🙋 Built by

**Rithika Machani** — UX/UI designer and developer focused on accessible technology.

This project grew out of a *Harvard CS560 accessibility project*, research into the **frequency gaps between hearing aids and standard music apps**, and a personal drive to build technology that meets people where they are — not where it's convenient to design for.

Multiple JavaScript iterations. WCAG 2.1 standards applied throughout. Tested with a real hearing-impaired listener whose feedback shaped every design decision.

---

## 📄 License

**MIT** — open source and free to use.

---

*Designed for hearing-impaired listeners. Built for everyone.*
