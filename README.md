# crosswordy-daily-puzzles

Static daily crossword puzzle data for the [Crosswordy](https://crosswordy.dev) app, hosted via
GitHub Pages. Generated once a day by [crosswordy-daily-generator](https://github.com/lost-dan-found/crosswordy-daily-generator)
— nothing in this repo is hand-edited.

## Layout

```
daily/YYYY-MM-DD/5.json
daily/YYYY-MM-DD/7.json
daily/YYYY-MM-DD/10.json
```

Each file is a solved puzzle: grid solution, slot metadata (direction/position/length/clue
number), and clues per word (blank until the clue bank is wired in).

## Fetching

Once Pages is live, a given day's 5×5 is available at:

```
https://lost-dan-found.github.io/crosswordy-daily-puzzles/daily/2026-07-30/5.json
```
