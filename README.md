# SO YOU THINK YOU KNOW THINGS: The Archive

Seasons I to III in one game you play on your phone.

**Play:** https://sb77-oss.github.io/SYTYKT/

- Pick any round, or hit Quick game for 10 random questions from all three seasons.
- Every question works the same way: tap Show answer, then mark yourself with Got it or Missed it. Be honest.
- Tap any picture to see it full screen.
- The phone's back gesture goes one screen back. In the middle of a round it asks before leaving.
- On a laptop: Space or Enter presses the main button, right arrow is Got it, left arrow is Missed it, Esc goes back.
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

Images are in `assets/`. Keep them small (under about 300 KB each). For animated pictures, WebP is far lighter than GIF.

If the page ever shows "The questions did not load", there is a typo in `questions.js` (often a missing comma or quote). Undo the last edit and try again.

## Sharing

`assets/og.jpg` is the preview picture that appears when the link is shared. `assets/favicon.png` and `assets/apple-touch-icon.png` are the tab icon and the home-screen icon. If the site ever moves to a new address, update the `og:url`, `og:image` and `twitter:image` lines at the top of `index.html`.

## Credits

"Yeah" sound on Press to start: [druki on Freesound](https://freesound.org/s/320739/), the same clip the live quiz uses.
