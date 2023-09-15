# JamBox

Local Music Player

This is a simple local music player web application built using HTML, CSS and JavaScript. It allows users to play audio tracks and control playback, mimicking a simplified Spotify-like interface.

## Features

- UI with tracklist, player and controls
- Displays track info like name, artist, cover art    
- Plays/pauses tracks
- Scrubs through tracks with a progress bar 
- Goes to next and previous tracks

## Usage

The app displays a list of track entries each containing:

- Track name
- Track cover art
- Play/Pause button

Clicking play begins playback. The currently playing track is highlighted and its info displayed in the player section.

Player controls:  

- Play/Pause button - Toggle playback
- Previous button - Go back one track
- Next button - Advance one track
- Progress bar - Scrub through track

## Implementation

Built using: 

- HTML5 for content and structure
- CSS3 for styling and responsiveness
- JavaScript for audio control and UI logic
- FontAwesome icons
- Designed to mimic Spotify for intuitive usage

Audio files are loaded via JS and played through the HTML5 audio element. Playback state is tracked to update the UI.

## Customization

The tracklist and audio files are configurable:

- `tracks` array in `script.js` contains track metadata
- Track DOM elements generated from this array
- Update audio sources in `script.js`
- Style colors, fonts, layout in `styles.css` 

Song data is easily editable to create your own playlists. Customize the UI layout and styling as needed for the desired look and feel.

This player app provides a nice starting point for building Spotify-like music web apps.

