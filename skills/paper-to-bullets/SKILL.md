---
name: paper-to-bullets
description: "Turn a paper into five bullets: title, question, method, result, limitation. Use when I share a paper or ask to triage one."
---
Read the file I name and output exactly five bullets, in this order:

- **Title**: the paper's title and, if present, the authors and year.
- **Question**: the research question the paper asks.
- **Method**: how the paper answers it, in one line.
- **Result**: the main finding, with the key number if there is one.
- **Limitation**: the main limitation the paper states or that the method implies.

Nothing before or after the five bullets. Use only what is in the file; if an item is missing, write "not stated".
