# paper-to-bullets

A Claude Code skill that turns a paper into exactly five bullets:

- **Title**: title, authors and year
- **Question**: the research question
- **Method**: how the paper answers it, in one line
- **Result**: the main finding, with the key number
- **Limitation**: the main limitation

Missing items are written as "not stated".

## Install

In Claude Code, run:

```
/plugin marketplace add gandalf126/paper-to-bullets
/plugin install paper-to-bullets@gandalf126-skills
```

## Run

```
/paper-to-bullets:paper-to-bullets
```

Then name the paper file you want summarised.

A plugin can run code on your computer: install plugins only from people you trust.
