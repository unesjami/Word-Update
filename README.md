# WordFlow

<p align="center">
  <strong>A bilingual English–Persian vocabulary trainer for focused daily learning.</strong>
</p>

<p align="center">
  <a href="https://unesjami.github.io/Word-Update/"><img src="https://img.shields.io/badge/Live_Demo-Open-14b8a6?style=for-the-badge" alt="Live demo"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-2563eb?style=for-the-badge" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/English_%E2%87%84_Persian-Bilingual-7c3aed?style=for-the-badge" alt="Bilingual">
</p>

## Overview

WordFlow is a lightweight browser application for collecting, translating, reviewing, and memorizing English and Persian vocabulary. It runs as a static site and requires no build step.

## Features

- English-to-Persian and Persian-to-English learning modes
- Interactive flashcards with navigation and review controls
- Text and voice input through the Web Speech API
- Pronunciation playback
- Progress tracking and saved vocabulary in the browser
- Responsive interface with light and dark themes

## Technology

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Browser storage
- GitHub Pages

## Run locally

```bash
git clone https://github.com/unesjami/Word-Update.git
cd Word-Update
python -m http.server 8080
```

Open `http://localhost:8080`. You can also open `index.html` directly, although microphone permissions may work more reliably through a local server.

## Project structure

```text
Word-Update/
├── index.html
├── README.md
└── LICENSE
```

## Browser support

A recent Chromium-based browser is recommended. Speech recognition availability and supported languages depend on the browser and operating system.

## Contributing

Issues and focused pull requests are welcome. Please describe the problem, expected result, and browser used when reporting UI or speech-recognition issues.

## License

Released under the [MIT License](LICENSE).

## Author

Created by [Unes Jami](https://github.com/unesjami).
