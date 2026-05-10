# Audra

Audra - music you can feel
A music accessibility tool that translates sound into visual experiences for hearing-impaired listeners.

Why Audra exists?

Most music apps are built for people who can hear everything. Hearing aids filter out specific frequency ranges such as the shimmer of a cymbal, the brightness of a voice, the warmth of a high melody. Those frequencies don't reach the listener. The music is still playing, but something essential is missing. Audra was built to fill that gap. It creates a parallel visual channel that carries everything the sound carries. Rhythm. Emotion. Structure. The feeling of a chorus building toward something. It started with one person who loves music. It was built for everyone who does.


Accessibility

Audra is built to the WCAG 2.1 AA standard throughout:
- All interactive elements are keyboard accessible
- Color contrast meets AA requirements in both dark and light mode
- Font scaling supported via Large Text toggle
- Reduce Motion toggle for users sensitive to animation


Tech stack

HTML / CSS / JavaScript       — core structure and styling
Web Audio API                 — real-time audio capture and frequency analysis
Canvas API                    — waveform and emotion map rendering
FFT (Fast Fourier Transform)  — frequency band decomposition
Beat detection                — rhythm grid synchronization
localStorage                  — hearing profile persistence
DM Sans + DM Mono             — accessible, legible typography



Built by
Rithika Machani — ISDS @ UIUC 

My personal connection to this project grew out of a research into the frequency gaps between hearing aids and standard music apps, and a personal drive to build technology that meets people where they are, not where it's convenient to design for.
