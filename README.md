# SO YOU THINK YOU KNOW THINGS: The Archive

Seasons I to III in one game you play on your phone.

**Play:** https://sb77-oss.github.io/SYTYKT/

- Pick any round, or hit Quick game for 10 random questions from all three seasons.
- Multiple choice is marked automatically. For open questions, tap Show answer and mark yourself honestly.
- Nothing is saved. Refresh and you start fresh.

## Editing questions

All questions live in `questions.js`. Each question has:

| field | what it is |
|---|---|
| `q` | the question |
| `media` | optional clip or picture shown with the question |
| `options` | multiple-choice options (empty for open questions) |
| `correct` | index of the right option (0 = A) |
| `answer`, `sub` | the answer and its one-line subline |
| `img`, `amedia` | optional picture or clip on the reveal |
| `note` | list of encore facts |
| `source` | where the facts come from |

Images are in `assets/`.

## Credits

"Yeah" sound on Press to start: [druki on Freesound](https://freesound.org/s/320739/), the same clip the live quiz uses.
