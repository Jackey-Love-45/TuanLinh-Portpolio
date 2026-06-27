# TuanLinh Portfolio V3

Updated portfolio with bilingual English/Vietnamese content, selectable color tones, a larger hero identity block, CodeGym Java certificate placement, and six project illustrations per case study.

## Preview

The JSON content must be served over HTTP. A preview server is currently running at:

- http://127.0.0.1:4289/

To run it later from this folder:

- Python: `python -m http.server 4289`
- Node.js: `npx serve .`
- VS Code: open `index.html` with Live Server.

## What changed

- Added English/Vietnamese language switching.
- Added Blue, Emerald, Amber and Rose color tones with readable foreground contrast.
- Enlarged the avatar and name block in the hero section.
- Added the CodeGym Professional Java Programmer Training certificate to the learning journey.
- Added six illustrated images for each selected project, visible in cards and the case-study Gallery tab.

## Customize

- Main layout: `index.html`.
- English/Vietnamese content: `data/content.en.json` and `data/content.vi.json`.
- Project illustrations: `assets/images/project-gallery/`.
- Certificate image: `assets/certificates/codegym-java-certificate.png`.
- Design tokens and responsive styles: `assets/styles.css`.
