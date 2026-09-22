# Speech sound model onboarding

A lightweight, interactive domain primer for students working on Sara's speech-sound detection model.

The site introduces:

- the current sound-level model task;
- basic IPA notation;
- correct productions, substitutions, distortions, rare additions, and word-level omissions;
- playable isolated-sound references;
- an interactive word-level listening challenge; and
- optional ASHA and external learning resources.

The primer supports model development and student onboarding. It is not a clinical diagnostic tool and does not replace review by a speech-language pathologist.

## Run locally

There are no dependencies or build steps. Open `index.html` directly, or run a static server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Repository structure

```text
.
├── index.html
└── audio/
    ├── base.mp3
    ├── d-reference.mp3
    ├── p-reference.mp3
    ├── round.mp3
    └── six.mp3
```

The site is intentionally self-contained. Styling and interaction code are included in `index.html`; audio files use relative paths so the site works locally and on GitHub Pages.

## Sharing and deployment

GitHub Pages can serve the repository directly from the root of the `main` branch. Linked Google Drive materials retain their existing sharing permissions.
