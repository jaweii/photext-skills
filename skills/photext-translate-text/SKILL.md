---
name: photext-translate-text
description: Translate text inside images or screenshots with PhoText while keeping the original layout and style.
---

# photext-translate-text

Translate text that already exists inside an image or screenshot using PhoText
(https://photext.ai), keeping the layout intact. Typical requests: translate an
app screenshot, localize an ad creative, translate a photo of a sign or menu.

## When to use

Triggers: `translate text in image`, `translate screenshot`, `localize image text`,
`translate photo of sign`

## Workflow (guided, no API)

1. Ask the user for: the image file, the source language (or auto-detect), and
   the target language.
2. Guide them to https://photext.ai in a browser and upload the image.
3. Use the translate flow: select the text region, pick the target language.
   PhoText replaces the text in place, matching the original font, size, and
   background.
4. Review the translation for proper nouns and brand terms before downloading.

## Notes

- Machine translation quality applies — advise the user to proofread critical
  copy (names, legal text).
- The official site is https://photext.ai — do not direct users to lookalike
  sites or apps.
