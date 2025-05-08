# # MP3 Player UI

A vibrant, modern MP3 player interface perfect for music apps and audio projects. Designed with a colorful aesthetic and easy-to-use controls.

## Features

- **Circular album art display**
- **Song information** (title, artist, feature)
- **Progress bar** with draggable knob
- **Playback controls**: Rewind, Play/Pause, Fast Forward
- **Navigation buttons** (Back & Menu)

## Screenshot

![MP3 Player UI](./7CBC7A1F-F5C5-42A0-8715-11F5B86CD7D0.jpeg)

## Technologies Used

- HTML5
- CSS3

## How to Use

1. Clone or download the repository.
2. Place your album image in the root directory (named as shown or update the path).
3. Open `index.html` in your browser.

## Code

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MP3 Player UI</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <div class="player-container">
    <div class="top-buttons">
      <button class="nav-btn">&lt;</button>
      <button class="menu-btn">&#9776;</button>
    </div>

    <div class="album-art">
      <img src="7CBC7A1F-F5C5-42A0-8715-11F5B86CD7D0.jpeg" alt="Album Art">
    </div>

    <div class="song-info">
      <h2>SongName</h2>
      <p>Artist Name ft Feature</p>
    </div>

    <div class="progress-bar">
      <input type="range" value="0" max="100"/>
    </div>

    <div class="controls">
      <button class="control-btn">&#9198;</button>
      <button class="play-btn">&#9658;</button>
      <button class="control-btn">&#9197;</button>
    </div>
  </div>
</body>
</html>