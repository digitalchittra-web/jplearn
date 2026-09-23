# Nihongo Dojo

A gamified Japanese-learning app: hiragana/katakana practice with spaced repetition, kana writing/tracing practice, a vocabulary deck, an AI conversation partner, and a Duolingo-style lesson path on mobile with a stats dashboard on desktop.

## Run it

No build step — it's a single static file.

```
open index.html
```

or serve it locally:

```
python -m http.server 8080
```

then visit `http://localhost:8080`.

## Notes

- Progress (streak, XP, kana/vocab mastery) is saved to the browser's local storage when run standalone.
- The AI "Talk" conversation mode and cross-device progress sync only work when this page is opened as a published Claude artifact, since those features call platform APIs that aren't available to a plain static page.
