# Spotify_Paste_Playlist_Queries_Youtube_Apple_Links_GPT_Template

# Spotify Playlist 50 First Tracks

## Overview

This project is a simple web application that allows users to enter a Spotify playlist link and retrieve the first 50 tracks of that playlist. It displays each track's name and artist, and provides links to both Apple Music and YouTube for further listening or viewing. The application also includes a feature to export the displayed playlist to a PDF document.

## Features

- Fetches the first 50 tracks from a Spotify playlist.
- Displays track names and artist names.
- Provides links to the tracks on Apple Music and YouTube.
- Allows exporting of the playlist table to a PDF document.

## Technologies Used

- HTML
- JavaScript
- Spotify Web API
- jsPDF
- jsPDF-AutoTable

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-playlist-50-first-tracks.git
   ```
2. Open the project directory:
   ```bash
   cd spotify-playlist-50-first-tracks
   ```
3. Open the `index.html` file in your preferred web browser.

## Usage

1. Open the web application by opening `index.html` in a web browser.
2. Enter the Spotify playlist link in the input field.
3. Click the "Get Playlist Tracks" button to fetch and display the first 50 tracks.
4. Click the "Export to PDF" button to export the displayed tracks to a PDF document.

![Screenshot 2024-06-28 122959](https://github.com/GallonSchimmer/Spotify_Paste_Playlist_Queries_Youtube_Apple_Links_GPT_Template/assets/26065891/babbb005-d337-4d63-8dcb-b93b6549e672)


## Configuration

To use this application, you need to provide your own Spotify API credentials. Replace the placeholder `clientId` and `clientSecret` values in the `getPlaylistTracks` function with your actual Spotify API credentials.

```javascript
const clientId = 'your_spotify_client_id';  // Replace with your actual Spotify client ID
const clientSecret = 'your_spotify_client_secret'; // Replace with your actual Spotify client secret
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable)

---

Feel free to reach out with any questions or suggestions!
