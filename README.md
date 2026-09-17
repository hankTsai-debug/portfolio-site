# ChengHan Tsai — Technical Portfolio

Static site. English at `/`, Traditional Chinese at `/zh/`.

## Layout

```
index.html         English (public build)
og-cover-en.png    Social preview, 1200x630
zh/index.html      Chinese (public build)
zh/og-cover.png    Social preview, 1200x630
```

## Editing

Do **not** edit these files by hand. They are build outputs.
Edit the sources, run the build, then copy the four public outputs here.

## Confidentiality

A `pre-commit` hook blocks commits containing internal identifiers.
Enable it once after cloning:

```bash
git config core.hooksPath .githooks
```
