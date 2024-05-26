# Music Player App

This project is a simple web-based music player built with HTML, CSS, and JavaScript. The application allows users to play, pause, navigate through songs, shuffle the playlist, and delete songs. It also visually highlights the currently playing song and displays its title and artist.

## Features

- **Play and Pause**: Play or pause the current song.
- **Next and Previous**: Skip to the next or previous song in the playlist.
- **Shuffle**: Shuffle the playlist randomly.
- **Delete**: Remove songs from the playlist.
- **Reset Playlist**: Reset the playlist to its original state.
- **Display**: Show the current song's title and artist.

## Technologies Used

- HTML
- CSS
- JavaScript

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/music-player-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd music-player-app
   ```
3. Open `index.html` in your web browser to start the music player.

## Usage

- **Play a Song**: Click the play button or any song title in the playlist.
- **Pause a Song**: Click the pause button.
- **Next Song**: Click the next button.
- **Previous Song**: Click the previous button.
- **Shuffle Songs**: Click the shuffle button to shuffle the playlist.
- **Delete a Song**: Click the delete button next to any song in the playlist. If all songs are deleted, a reset button will appear to restore the playlist.
- **Reset Playlist**: Click the reset button to restore the original playlist.

## Code Overview

### HTML

The HTML structure consists of a music player interface and a playlist. Key elements include buttons for play, pause, next, previous, and shuffle actions.

### CSS

Styles are defined in `styles.css` to layout the music player and playlist, and to handle the button designs and interactions.

### JavaScript

The JavaScript logic handles the core functionality of the music player:

- **Global Variables**: Define the playlist and user data.
- **Functions**:
  - `playSong(id)`: Plays the song with the given ID.
  - `pauseSong()`: Pauses the current song.
  - `playNextSong()`: Plays the next song in the playlist.
  - `playPreviousSong()`: Plays the previous song in the playlist.
  - `shuffle()`: Shuffles the playlist.
  - `deleteSong(id)`: Deletes the song with the given ID.
  - `setPlayerDisplay()`: Updates the display with the current song's title and artist.
  - `highlightCurrentSong()`: Highlights the currently playing song in the playlist.
  - `renderSongs(array)`: Renders the playlist.
  - `setPlayButtonAccessibleText()`: Updates the accessible text for the play button.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [freeCodeCamp](https://www.freecodecamp.org) for providing the song resources and inspiration for this project.

---
