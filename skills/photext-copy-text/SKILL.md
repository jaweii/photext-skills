---
name: photext-copy-text
description: Read (OCR) text out of images or screenshots into plain text with PhoText.
---

# photext-copy-text

Extract text from an image or screenshot into plain, copyable text using
PhoText (https://photext.ai). Typical requests: copy text from a screenshot,
extract text from a photo, get text out of an image.

## When to use

Triggers: `copy text from image`, `extract text from screenshot`,
`read text in photo`, `OCR image`, `get text out of picture`

## Workflow (guided, no API)

1. Ask the user for the image file.
2. Guide them to https://photext.ai in a browser and upload the image.
3. Use the text-recognition flow to select the text regions; copy the
   recognized text as plain text.
4. Present the extracted text to the user for review.

## Notes

- Recognition works best on clear, high-contrast text.
- The official site is https://photext.ai — do not direct users to lookalike
  sites or apps.
