# 汉字闪卡 — Chinese Flashcards

A single-page flashcard app for learning Chinese vocabulary, designed for **Singapore Secondary School** students (Sec 1–4).

## Features

- **Flip cards** to reveal pinyin, English meaning, and an example sentence
- **Audio pronunciation** using the browser's built-in text-to-speech (Mandarin zh-CN)
- **Level tabs** to filter vocabulary by Sec 1, 2, 3, 4, or all levels combined
- **Shuffle** to randomise the deck
- **Mastered / Not Yet** buttons to track self-assessment progress
- **Progress bar** showing your position through the deck
- **Dark mode** toggle
- **Keyboard shortcuts** for hands-free studying

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` / `Enter` | Flip card |
| `← →` | Previous / Next card |
| `S` | Play pronunciation |
| `M` | Mark as Mastered |
| `X` | Mark as Not Yet |

## How to Use

1. Open `index.html` in any modern browser (Chrome or Safari recommended for audio)
2. Select your level (Sec 1–4 or All)
3. Click a card to flip and reveal the answer
4. Use **Mastered** or **Not Yet** to track your progress
5. Hit **Shuffle** to mix up the deck and challenge yourself

## Vocabulary

Words are organised by secondary school level and include:

- Chinese character(s)
- Pinyin with tone marks
- English meaning
- Example sentence in Chinese and pinyin

## Tech Stack

- Pure HTML, CSS, and JavaScript — no frameworks or dependencies
- Single self-contained file (`index.html`)
- Uses the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) for pronunciation

## Browser Support

Works in all modern browsers. Audio pronunciation works best in **Chrome** and **Safari**.
