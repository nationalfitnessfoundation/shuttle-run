# Presidential Fitness Test — 20m Shuttle Run

Web app that administers the 20-meter shuttle run using the Léger protocol (Léger & Lambert, 1982). Twenty-one progressive levels, 244 total shuttles, ~21 minutes maximum duration.

## What's in here

- `index.html` — the app. Single file, no dependencies.
- `audio/` — 31 voice clips that play during the test.

## How to use

Open `index.html` in any modern browser, or visit the deployed URL. Hit **Start Test** to administer.

## How it works

Voice and beep timing are derived from the published Léger formula (`shuttle duration = 72 ÷ speed in km/h`). Audio is real-recorded ElevenLabs narration, mixed live with synthesized beeps and level-transition chimes.

## Credits

Léger, L.&nbsp;A. & Lambert, J. (1982). A maximal multistage 20-m shuttle run test to predict VO<sub>2</sub> max. *European Journal of Applied Physiology,* 49(1): 1–12.
