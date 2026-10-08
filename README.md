# Music App

A Spotify-style **music player web app** built with plain HTML, CSS and JavaScript. Browse songs and artists, then play tracks with a full set of player controls.

## Features

- Song list with poster art, title and artist
- Play / pause from the list or from the master player
- Next and previous track buttons
- Seek bar with current time and total duration
- Volume slider with a dynamic volume icon
- Animated wave indicator while a song is playing
- Horizontally scrollable "popular songs" and "popular artists" rows

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (HTML5 `Audio` API)
- Bootstrap Icons

## How to Run

```bash
git clone https://github.com/PRiNCeKUsHW/Music.git
cd Music
```

Open `index.html` in a browser. For the most reliable audio playback, serve the folder with a small local server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Project Structure

```
Music/
├── index.html   # App layout: menu, song list, artists, master player
├── style.css    # Styling
├── app.js       # Song data and all player logic
├── audio/       # Song files (1.mp3, 2.mp3, ...)
├── img/         # Song posters and artist images
└── bg.png       # Background image
```

## Adding a Song

1. Put the audio file in `audio/` as `<id>.mp3`.
2. Put the cover image in `img/` as `<id>.jpg`.
3. Add an entry to the `songs` array in `app.js` with the same `id`.

> The audio and images are for learning purposes only.
