# Readfast, a speed-reader

This web-app will use Rapid Serial Presentation to let you read text or epub files. You'll be able to paste text or drag/upload an epub/txt into it and it'll show you a word at a time, with a letter highlighted in red (see Idea.png).

There are subtle visual guides in grey that draw your eye to the red. The background is black, and the text is white.

While "playing" there is a progress bar like a video player, with a play/pause button and a forwards/backwards 5 seconds button, and a speed picker in words per minute (WPM).

The entire app is written in a single HTML file, which includes any styling and script tags. No external files! If it needs external dependencies, it pulls them in using a CDN JS library. It saves its state (including last file, playback state, speed prefs) to localstorage, so if you refresh the page it can resume where you left off.