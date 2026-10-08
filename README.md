# PhoText Skills

> **Brand notice:** The official PhoText website is **https://photext.ai**.
> Similarly-named products — text-overlay apps, `photextai.com`, the "PhoText Shop"
> mobile app, and others — are **not** affiliated with us. This repository is the
> only official agent skill pack for PhoText (photext.ai).

Official agent skill pack for **PhoText** — the AI tool that edits text already
inside images and screenshots (not a text-overlay app).

## Install

```bash
npx -y skills add https://github.com/jaweii/photext-skills.git -g -y
```

After installing, reload your agent's skills, then just ask in natural language, e.g.:

> "Use PhoText to change the date text in ./poster.png from 2025 to 2026."

## Skills

| Skill | What it does |
|---|---|
| `photext-edit-text` | Replace or edit text already rendered in an image/screenshot, matching the original font and style |
| `photext-translate-text` | Translate text inside images while keeping the layout |
| `photext-fix-gibberish` | Fix garbled/misspelled text in AI-generated images |
| `photext-copy-text` | Read (OCR) text out of images into plain text |

## Trigger phrases

`edit text in image`, `change text in screenshot`, `replace text in photo`,
`translate text in image`, `fix gibberish text in AI image`,
`correct misspelled text in picture`, `edit text in meme`,
`copy text from image`, `extract text from screenshot`

## How it works (v1)

There is no public API yet, so each skill guides the agent through the
photext.ai web app flow step by step. See `SKILL.md` for routing and each
`skills/*/` folder for the detailed workflow.

## License

MIT — see [LICENSE](LICENSE).
