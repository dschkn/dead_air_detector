# _dead_air_detector

`_dead_air_detector` is an experimental Max/MSP system that listens to live microphone input, extracts spectral partials, assigns them to selected instruments, and writes the result as a live score.

## Requirements

- Max 8.5 or newer
- `bach` package
- `fiddle~` external

## Run

1. Open `patchers/dead_air_detector.maxpat`.
2. Select the desired microphone in Max Audio Status.
3. Enable audio input.
4. Choose the instrument ensemble.
5. Start recording and produce sound near the microphone.

This is an early prototype. Note durations and instrumental allocation will be refined in later versions.

Copyright © 2026 Dmitrii Shchukin. All rights reserved.
