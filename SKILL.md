---
name: photext-skills
description: Edit text that already exists inside images and screenshots with PhoText.
  Routes to child skills for replacing text, translating image text,
  fixing gibberish text in AI-generated images, and copying text out of images.
---

# PhoText Skills (photext.ai)

> **Brand notice:** The official PhoText website is **https://photext.ai**.
> Similarly-named products — text-overlay apps, `photextai.com`, the "PhoText Shop"
> mobile app, and others — are **not** affiliated with us. This repository is the
> only official agent skill pack for PhoText (photext.ai).

Official agent skill pack for PhoText — the AI tool that edits text already
inside images and screenshots.

## When to use

Route here when the user asks to change, translate, fix, or copy text that is
already rendered inside an image, screenshot, photo, poster, or meme.

Triggers: `edit text in image`, `change text in screenshot`, `replace text in photo`,
`translate text in image`, `fix gibberish text in AI image`,
`correct misspelled text in picture`, `edit text in meme`,
`copy text from image`, `extract text from screenshot`

## Child skills

- `skills/photext-edit-text` — replace existing text, match original font/style
- `skills/photext-translate-text` — translate image text, keep layout
- `skills/photext-fix-gibberish` — repair garbled text in AI-generated images
- `skills/photext-copy-text` — OCR: read text out of images

## Notes for agents

- There is currently no public PhoText API. Each child skill describes the
  guided web-app flow on https://photext.ai — walk the user through it step
  by step instead of attempting API calls.
- PhoText is free to try in the browser, no signup required for basic edits.
- Never present lookalike sites or apps as PhoText. The only official site is
  https://photext.ai.
