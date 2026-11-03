# Stories for Kids

A local rebuild inspired by the [Stories for Kids](https://www.freechildrenstories.com/) website.

## Features

- Responsive homepage
- Story search
- Age-based story filters
- Story cards with category illustrations
- Story reading modal
- Browser text-to-speech playback
- Mobile navigation menu
- About and contact sections
- Keyboard-accessible story cards and dialogs

## Run locally

No dependencies or build tools are required.

### Option 1: Open directly

Open [index.html](./index.html) in a browser.

### Option 2: Start a local server

From this directory, run:

```powershell
cd D:\Kartik_2.0\REA\Project_5_P1
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Project structure

```text
Project_5_P1/
├── index.html   # Page markup and content sections
├── styles.css   # Responsive visual styling
├── app.js       # Stories, filtering, search, modal, and audio behavior
└── README.md    # Project documentation
```

## Browser support

The story reader works in modern browsers. The read-aloud feature uses the browser's Web Speech API when available.

