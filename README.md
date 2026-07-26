# mc-scanner-1

Single-file web app for printable MC answer sheet templates and browser-based auto-marking.

## Run

Open `/home/runner/work/mc-scanner-1/mc-scanner-1/index.html` in a modern browser.

## Features

- All-in-one HTML/CSS/JS (no backend required)
- Upload answer sheet image and perform client-side scanning
- Corner-marker alignment and bubble detection
- Answer key input (`1:A` lines or `A,B,C,...` CSV style)
- Auto-marking with score, wrong-question list, and ambiguity warnings
- Export result as JSON or CSV
- Built-in printable templates:
  - Template A: 50 questions, A-D
  - Template B: 60 questions, A-D
  - Template C: 40 questions, A-E

## Notes

- Best results require flat sheet, good light, and high contrast.
- For production-grade OMR, calibrate thresholds with real samples.