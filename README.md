# Canada Geography Flashcards

Interactive flashcard app for learning Canada's 10 provinces, 3 territories, and their capital cities.

### ▶ [Play it live](https://kidsil.github.io/canada-geography-flashcards/)

No install, no signup. It runs entirely in the browser.

## What it covers

All 13 provinces and territories with their capitals, grouped into four regions:

| Region | Provinces / Territories |
|---|---|
| West | British Columbia, Alberta, Saskatchewan, Manitoba |
| Central | Ontario, Quebec |
| Atlantic | New Brunswick, Nova Scotia, Prince Edward Island, Newfoundland and Labrador |
| North | Yukon, Northwest Territories, Nunavut |

## Game modes

| Mode | What you do |
|---|---|
| **Flashcards** | Flip a card to reveal the capital, at your own pace |
| **Quiz** | Multiple choice, with a running streak counter |
| **Match** | Pair each province with its capital against the clock |
| **Type It** | Type the answer from memory, with no options to pick from |
| **Map** | Click the right region on an interactive map of Canada: *Find the Province* or *Name the Capital* |

## Progress tracking

Sessions are saved to `localStorage` (key `canada-flashcards-stats`), so progress survives a page reload and nothing leaves your machine. The stats bar tracks:

- **Best score** across all sessions
- **Session history** of your recent runs
- **Weak spots**: the provinces you keep missing, shown in a "Review these" list

## Running locally

It's a single self-contained `index.html` with no build step and no dependencies.

```bash
git clone https://github.com/kidsil/canada-geography-flashcards.git
cd canada-geography-flashcards
xdg-open index.html   # or just drag the file into a browser
```

## Sibling project

[europe-geography-flashcards](https://github.com/kidsil/europe-geography-flashcards) runs the same engine over the 44 countries of Europe. [Play it live](https://kidsil.github.io/europe-geography-flashcards/).

## License

MIT.
