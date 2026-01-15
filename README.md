# Readfast

Readfast is a speed reader that uses Rapid Serial Visual Presentation (RSVP) to help you read faster. Paste in text or drop an EPUB, and it shows you one word at a time with a highlighted focus point so your eyes don't have to move.

## Why would I want this?

When you read normally, your eyes jump around the page—finding the next word, the next line, backtracking. All that movement takes time. RSVP eliminates it entirely by putting each word in exactly the same spot, with the optimal recognition point (the letter your eye naturally focuses on) highlighted in red and aligned to a fixed position.

The result? You can read significantly faster because your eyes just... stay still. The words come to you.

## What it looks like

Drop in some text, hit play, and words appear one at a time:

- The **red letter** marks the optimal recognition point (~30% into each word)
- **Grey guides** help your eye lock onto the right spot
- A **progress bar** lets you scrub through the text like a video
- **Keyboard shortcuts** for everything (space to play/pause, arrows to skip)

The UI fades away while you're reading so you can focus on the words.

## Features

- Paste text or drag-and-drop `.txt` and `.epub` files
- Adjustable speed from 100 to 1000 words per minute
- Smart pauses on punctuation (longer pause after periods and commas)
- Saves your place automatically—refresh and pick up where you left off
- Works on mobile
- Single HTML file, no build step, no dependencies to install

## Usage

Just open `index.html` in a browser. That's it.

Or if you want to serve it:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| Space | Play/pause |
| ← | Skip back 5 seconds |
| → | Skip forward 5 seconds |
| + | Speed up |
| - | Slow down |
| F | Toggle fullscreen |
| Esc | Exit reader |

## Contributing

Bug reports and pull requests are welcome on [GitHub](https://github.com/tpritc/readfast).

## License

Readfast is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
