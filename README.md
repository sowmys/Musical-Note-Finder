# Musical Note Finder (Swara Listener)

Sing or hum a note and see which Carnatic swara it is, relative to your Sa.

- Big swara readout with the Western note and frequency
- Tuning needle in cents (green within ±10¢)
- Raga filter: shows whether the note belongs to the chosen raga
- "Set Sa from my voice" calibration
- 8-second pitch trail with the raga's swara lines, so gamakas are visible
- Record up to 20 s and play it back with the swara trail replaying in sync
- Built-in accuracy check: plays known notes and compares detected pitch (direct, or through speaker and mic)

Open it at **https://sowmys.github.io/Musical-Note-Finder/** in Safari or Chrome and allow the microphone.
Pitch detection uses the YIN algorithm on the Web Audio API; nothing leaves the device.
