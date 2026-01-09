I have created the spotify clone and it has javascript also.
Now in this website i have added the folders which on click will start to play their respective songs and we can do nex,previous and play.
It has features to stop the music any time and farward it using seek bar and can change volume also.
Here the photos of it..
![Screenshot 2025-01-04 113738](https://github.com/user-attachments/assets/d14a486a-2bbf-4e1c-a37b-fc9a273222b7)
![Screenshot 2025-01-04 113908](https://github.com/user-attachments/assets/949f0ee9-684e-4de7-adeb-5678e287bcba)
![Screenshot 2025-01-04 113844](https://github.com/user-attachments/assets/8b81e43a-4927-4473-8c15-9bdc126770ff)

# Spotify Clone

This repository contains a lightweight Spotify-inspired web player built with HTML, CSS and JavaScript. It is a local, client-side project intended to demonstrate interactive audio playback, playlist grouping, a responsive player UI, and basic playback controls.

## Overview

The app organizes songs into folders (moods/artists) — each folder includes an `info.json` and audio files. Clicking a folder loads its playlist and allows users to play, pause, skip, seek, and adjust volume. The UI includes a progress/seek bar and controls for next/previous track.

## Features

- Professional: Clean, responsive player UI with album/folder-driven playlists.
- Playback controls: Play/Pause, Next, Previous, Seek (progress bar), and Volume control.
- Organized content: Songs grouped into folders (e.g., `Chill_(mood)`, `Love_(mood)`, `Kishore Kumar`).
- Metadata support: Each folder contains an `info.json` used to load track metadata.
- Static, client-side: No backend required — open `index.html` in a browser.

## How to Use

1. Clone or download the repository.
2. Open `[index.html](index.html)` in your browser.
3. Click any folder card to load its playlist.
4. Use the player controls to play, pause, skip, seek, and change volume.

## Project Structure

- `index.html` — main entry and UI markup.
- `style.css`, `utility.css` — styling and utility classes.
- `script.js` — player logic, event handlers, and audio management.
- `images/` — screenshots and artwork used in the UI.
- `songs/` — folder of categorized song directories; each directory contains an `info.json` and audio files.

## Screenshots

Below are the screenshots you added — retained in their original order to preserve your examples of the UI:

![Screenshot 2025-01-04 113738](https://github.com/user-attachments/assets/d14a486a-2bbf-4e1c-a37b-fc9a273222b7)
![Screenshot 2025-01-04 113908](https://github.com/user-attachments/assets/949f0ee9-684e-4de7-adeb-5678e287bcba)
![Screenshot 2025-01-04 113844](https://github.com/user-attachments/assets/8b81e43a-4927-4473-8c15-9bdc126770ff)

## Tech Stack

- HTML5, CSS3
- Vanilla JavaScript (ES6+)

## Contributing

If you'd like to improve this project, consider:

- Adding more metadata to each `info.json` (artist, album art, duration).
- Improving accessibility (keyboard controls, ARIA labels).
- Adding playlist persistence (localStorage) or a simple backend for streaming.



